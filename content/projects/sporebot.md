+++
title = 'Sporebot'
date = 2025-08-15T12:46:14+01:00
draft = false
+++

### SporeBot - Mushroom-Fetching Discord Bot

This summer while I was in Poland I built **SporeBot**, a Discord bot designed to fetch random mushroom information from Wikipedia.
The primary goal of this project was to not only refresh my Python skills over summer but also delve into web-scraping.

#### Core Features
- Random mushroom facts -- `$mushroom` makes SporeBot pick a random mushroom from the included database
- Mushroom lookups --  `$mushroom [name]` allows for querying of specific mushrooms
- Visuals of the mushroom displayed -- `$list` or `mushrooms` displays the first 20 mushrooms in the database 

#### How It Works

I used `requests` and `beautifulsoup4` to scrape Wikipedia and extract text and images from mushrooms mapped in `mushrooms.py`
