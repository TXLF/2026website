# Texas Linux Fest 2026 website

This repository contains the source code for [2026.texaslinuxfest.org][txlf].
It uses the [Hugo framework][hugo] with the [Eventre theme][eventre].

## Schedule, talks, and speakers

These come from [pretalx][pretalx], not from hand-edited files.
`scripts/sync-pretalx.py` reads the published schedule and writes:

- `data/schedule.yml` — the schedule grid data
- `content/grid-schedule-day-<n>.md` — all-rooms grid for one day
- `content/<room>-schedule-day-<n>.md` — single-room view for one day
- `content/talks/<title>.md`
- `content/speakers/<name>.md`

A [GitHub Actions workflow][sync-workflow] runs it nightly and opens a pull
request when the published schedule has changed. To run it by hand:

```
python3 scripts/sync-pretalx.py            # write files
python3 scripts/sync-pretalx.py --check    # exit 1 if anything would change
```

Only what is *published* in pretalx shows up — releasing a new schedule version
in pretalx is what makes a change visible to the sync.

Generated files carry `pretalx_managed: true` in their front matter and are
rewritten on every sync. Files without that key are yours: a hand-written
speaker page keeps its bio, photo, and social links, and the sync only merges
this year's talks into it. Delete a generated page's `pretalx_managed` line to
take it over by hand.

The schedule's title and intro text, and the switch that shows or hides it,
stay in `data/homepage.yml` under `tab:`.

## Sponsors and other content

If you are making changes to the sponsors,
make sure to update the following files:

- `data/homepage.yml`
- `static/images/sponsors/<name>.<extension>`

To preview your changes locally before submitting a pull request,
run the following command:

```
hugo server
```

[txlf]: https://2026.texaslinuxfest.org/
[pretalx]: https://pretalx.com/txlf2026/schedule/
[sync-workflow]: .github/workflows/sync-pretalx.yml
[hugo]: https://gohugo.io/
[eventre]: https://docs.gethugothemes.com/eventre/
