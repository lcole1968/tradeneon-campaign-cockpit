# TradeNeon Marketing Cockpit v2026 - Marketing Tool 2026

> **TradeNeon Marketing Cockpit is a browser-based marketing utility for UTM management and campaign naming that runs as a static, Supabase-backed workflow in the 2026 release.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/lcole1968/tradeneon-campaign-cockpit?style=flat-square)](https://github.com/lcole1968/tradeneon-campaign-cockpit)

---

<p align="center">
  <a href="https://lcole1968.github.io/tradeneon-campaign-cockpit/">
    <img src="https://img.shields.io/badge/Download-TradeNeon%20Marketing%20Cockpit%20Latest-brightgreen?style=for-the-badge" alt="Download TradeNeon Marketing Cockpit">
  </a>
</p>

> **[Direct Download - TradeNeon Marketing Cockpit v2026](https://lcole1968.github.io/tradeneon-campaign-cockpit/)**

---

[Download Latest Build](https://lcole1968.github.io/tradeneon-campaign-cockpit/)

---

## About TradeNeon Marketing Cockpit

TradeNeon Marketing Cockpit exists so marketing teams can keep campaign tracking details in order instead of juggling scattered spreadsheets and inconsistent naming habits. Its core focus is UTM handling and naming structure, which helps campaign data stay aligned across channels and launches.

The tool is built as a static web app with Supabase support, so it suits lightweight publishing and centralized data workflows. Teams that want a straightforward browser-based cockpit for preparing, reviewing, and maintaining campaigns will find it a good fit.

---

## Features

- UTM management built around campaign tracking structures
- Naming tool that keeps marketing labels consistent
- Static site architecture for straightforward deployment
- Data handling backed by Supabase
- Browser-accessible web interface
- Helps organize marketing workflows
- Lightweight option for campaign planning and upkeep
- Built around reusable naming and tracking patterns

---

## Installation

Clone the repository or grab the project files, then open the static site in a browser or deploy it to the web host of your choice.

    git clone https://github.com/lcole1968/tradeneon-campaign-cockpit.git
    cd campaign-control

When the project is connected to Supabase, configure the required backend values before first use, then launch the site from your hosting environment or a local preview server.

---

## Usage

Use the cockpit to define or review UTM values, apply naming rules, and keep campaign records consistent across marketing assets.

A typical workflow looks like this:

1. Open the web app.
2. Enter or update campaign details.
3. Apply naming conventions.
4. Save or sync entries through the Supabase-backed workflow.
5. Reuse the stored structure for future campaigns.

When hosting the static site locally, refresh the browser after updating files to make sure the changes are loaded.

---

## Configuration

Configuration details usually live in the site setup and the Supabase connection values. If your deployment relies on environment-based settings, keep them in the hosting platform or in a local config file that the static app references.

Example configuration pattern:

    {
      "supabaseUrl": "YOUR_SUPABASE_URL",
      "supabaseAnonKey": "YOUR_SUPABASE_ANON_KEY",
      "defaultCampaignPrefix": "brand"
    }

Adjust these values to match your workspace, naming policy, and data source setup.

---

## Requirements

- A current web browser
- Static hosting support for HTML-based deployment
- Supabase project access when backend storage is enabled
- Sufficient space for the site files and any stored campaign records
- Basic familiarity with UTM and naming conventions

---

## FAQ

**How do I update the project?**  
Download the latest build from the project page, replace the hosted files, and re-check any Supabase-related settings after deployment.

**Where do I change configuration?**  
Look at the site configuration files or your host-level environment settings, depending on how the static app is deployed.

**What if data is not loading?**  
Verify that the Supabase values are correct, that the project has the access it needs, and that the browser can reach the configured endpoint.

**Can I use this without Supabase?**  
The project is described as Supabase-backed, so any non-backend usage depends on how the static site is configured in your deployment.

**How do I get help?**  
The repository files, deployment settings, and connected service configuration are the most direct path to troubleshooting.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
