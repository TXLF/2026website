---
title: "Don't Mess With My Data: Local AI + MCP on Linux"
description: "Texas Linux Fest 2026"
page_header_bg: "images/background/page-title-bg.jpg"
format: "Talk"
when: "Saturday, November 7, 17:00 - 17:50"
where: "Lil Tex"
pretalx_code: "HQWWGD"
pretalx_link: "https://pretalx.com/txlf2026/talk/HQWWGD/"
pretalx_managed: true
track: "Artificial Intelligence"

speakers:
  - name: "Rajesh Alwar"
    image: "https://pretalx.com/media/avatars/GBACJM_dF1yGL4.webp"
    link: "speakers/rajesh-alwar/"
---

What if you could ask an AI "is my house good for solar panels?" - and get a real answer, without sending your address leaving your machine?


In this talk, we'll build a fully local AI agent stack on Linux that evaluates solar potential for any Texas property - no cloud APIs, no OpenAI key, no data leaving your network. We'll wire together Ollama running a local LLM, a custom MCP (Model Context Protocol) server exposing tools for geocoding and solar estimation, the free NREL PVWatts government API, and PostgreSQL for local storage. The result: an agent you can ask "what would solar look like on my roof?" and get a real, human-readable answer grounded in real data.


We'll cover:

- Running a local LLM with Ollama on Linux

- Building an MCP server that exposes real-world tools to any AI client

- Turning raw government solar data into plain-English savings estimates

- Persisting and querying results in local PostgreSQL

- Running the whole stack as a systemd service - no always-on laptop required


Texas gets 200+ sunny days a year and some of the most volatile electricity prices in the country thanks to ERCOT. This is a practical talk about what local, open source AI can actually do - on your hardware, on your terms, using a protocol you can reuse for your own tools tomorrow.


As the industry shifts from expensive frontier models toward cheaper, optimized inference this talk shows what's possible when you run capable AI agents directly on hardware you own.
