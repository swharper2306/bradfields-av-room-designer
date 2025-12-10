# Bradfield's AV Room Designer

An interactive, browser-based tool for capturing concept-level AV room requirements
and sending them to Bradfield's AV engineering team.

This app is designed to live as a standalone web page (e.g. on GitHub Pages) and be
embedded into the main Bradfield's website via an `<iframe>`.

---

## Overview

The AV Room Designer lets customers describe:

- **Room basics** – name, type, dimensions, capacity, layout, special notes  
- **Use cases & technology** – conferencing platforms, presentation needs, cameras, audio, connectivity  
- **Budget & preferences** – budget band, timeline, support expectations, brand/standard notes  
- **Contact info** – who they are and how to reach them  

As they fill out the form, a **Live Concept Summary** is generated on the right side.
On the final step, the user can:

- Copy the full text summary, and/or  
- Click **“Send to Bradfield’s”** which opens an email (mailto) pre-filled with the summary.

By default, the email goes to:

- `steveh@bradfields.com`

This can be changed in the HTML (see **Configuration** below).

---

## Features

- Multi-step wizard:
  - Step 1 – Room Basics  
  - Step 2 – Use Cases & Technology  
  - Step 3 – Budget & Preferences  
  - Step 4 – Summary & Contact
- Live, structured summary with:
  - Room overview
  - Usage and platforms
  - Concept-level AV recommendations (display, camera, audio, connectivity, package tier)
- Copy-to-clipboard summary block
- “Send to Bradfield’s” email button using `mailto:` with subject and body pre-populated
- Bradfield’s branding:
  - Logo in header
  - Branded colors and footer text

---

## Running Locally

1. Clone the repo:

   ```bash
   git clone https://github.com/swharper2306/bradfields-av-room-designer.git
   cd bradfields-av-room-designer
