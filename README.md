# Quit Journal — Vaping Trigger Tracker

A personal web app to support my journey to quit vaping before I retire on **31 January 2027**.

Built as a single HTML file, hosted on GitHub Pages, and saved to my phone home screen as a progressive web app.

-----

## Purpose

Quitting a long-term, heavy vaping habit isn’t just about willpower. It requires understanding *when*, *why*, and *how* the habit is triggered — before any reduction plan can work.

This app is Phase 1 of a structured quit plan: an awareness and data-gathering tool. Every vape event is logged in the moment, building a picture of patterns over time that will directly inform the reduction strategy in the months ahead.

-----

## What it tracks

Each log entry captures:

- **How the vape started** — was it a conscious urge, or fully automatic with no awareness?
- **Activity** — what was happening at the time
- **Feeling** — emotional state in the moment
- **Urge strength** — for conscious urges: Mild / Moderate / Strong / Overwhelming
- **Optional note** — any context worth remembering

-----

## Features

- **Overview** — today’s count, weekly total, top triggers at a glance, and a live countdown to retirement day
- **Log** — quick tap-through entry form optimised for one-handed mobile use
- **History** — every entry in reverse order, badged by type and urge intensity
- **Insights** — bar charts of top activities, feelings, urge patterns, and automatic vs conscious split

Data is stored locally on the device via `localStorage` — no account, no server, no tracking.

-----

## The quit plan

|Phase         |Period                  |Focus                                                                        |
|--------------|------------------------|-----------------------------------------------------------------------------|
|1 — Awareness |Now → June 2026         |Log every event. Map triggers. Build the data picture.                       |
|2 — Reduction |July → October 2026     |Systematic step-down. Lower nicotine. Hard boundaries. Substitute behaviours.|
|3 — Transition|November → December 2026|Switch to NRT (patches/gum). Break the vaping habit while managing nicotine. |
|4 — Freedom   |January 2027            |Wean off NRT. Retire vape-free.                                              |

-----

## Installation (phone home screen)

1. Open the GitHub Pages URL in **Safari**
1. Tap the **Share** button
1. Tap **Add to Home Screen**
1. Name it *Quit Journal*

It will appear on your home screen and open full-screen like a native app.

-----

## Tech

Plain HTML, CSS, and vanilla JavaScript. No frameworks, no dependencies, no build step. Runs entirely in the browser.

-----

*Started: May 2026. Target: 31 January 2027.*
