# MTA ADA Network Analysis

Ever wondered what the NYC subway looks like if you actually need an elevator? Danielle Schulz and Xiaofan Liang did. They (more like myself) dragged me along for the ride.

I helped out with the network part, but turns out the real pain comes from wrangling the data. Spoiler: it's mostly data wrangling.

## What Is This?

This project constructs an **ADA-compliant transit network** for the NYC subway system. We take MTA's GTFS data, layer on accessibility information scraped from MTA's website, wrestle with a truly chaotic set of naming conventions, and emerge (barely) with a navigable graph of accessible routes.

## The Journey

Building this involved:

- Discovering that `parent_station` means approximately nothing
- Learning that One Direction is still relevant (in the MTA accessibility hellscape)
- Manually labeling way more CSV files than any human should
- Consulting Claude more times than I'd like to admit

## Getting Started

I recommend using [uv](https://github.com/astral-sh/uv) for package management:

```bash
uv pip install -r requirements.txt
```

Then open up the notebook and enjoy the ride.

## Read the Notebook

All the gory details, data cleaning rants, and Renaissance art metaphors live in the notebook. Start there.

## Acknowledgments

- MTA, for the data (and the chaos)
- Claude, for parsing HTML and keeping me sane
- Carlo Crivelli, for painting a dragon-slaying scene that perfectly captures this experience
