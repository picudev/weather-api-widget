# Weather API Widget

![License](https://img.shields.io/badge/license-GPLv2-blue.svg)
![WordPress](https://img.shields.io/badge/WordPress-5.0%2B-blue)
![PHP](https://img.shields.io/badge/PHP-7.4%2B-green)
![Status](https://img.shields.io/badge/status-stable-success)

A lightweight WordPress plugin that displays real-time weather information using the OpenWeatherMap API.  
Includes shortcode support, caching, automatic icons, and a clean UI.

---

## Features

- Shortcode: `[weather city="Bucharest"]`
- Supports metric and imperial units
- Admin settings page for API key
- 30‑minute caching to reduce API calls
- Automatic weather icons
- Inline CSS (no external files)
- Error handling for API failures

---

## Installation

1. Download or clone this repository.
2. Upload the folder to `wp-content/plugins/`.
3. Activate the plugin from **Plugins → Installed Plugins**.
4. Go to **Settings → Weather API** and enter your OpenWeatherMap API key.

---

## Shortcode Usage

### Basic
```php
[weather city="Bucharest"]


== License ==

This plugin is licensed under the GPLv2 or later.
