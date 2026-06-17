# Simple

[![Language](https://img.shields.io/badge/language-PHP-777BB4)]

[English](README.md) | [中文](README.zh-CN.md)

A lightweight, minimalist theme for [Typecho](https://typecho.org/) designed by JRTx. Built with Bootstrap, featuring a clean blog layout with mobile responsiveness.

## Screenshot

![Simple Theme Screenshot](screenshot.png)

## Features

- **Minimalist design** -- clean, distraction-free reading experience
- **Responsive layout** -- mobile-friendly with automatic device detection
- **Bootstrap-based** -- uses Bootstrap 3.1.1 for consistent styling
- **Fixed navigation bar** -- blog and about page links in the top navbar
- **Date-stamped post list** -- posts displayed as a simple list with dates
- **Custom pages** -- supports Typecho custom pages (e.g., about page)
- **Lightweight** -- minimal CSS and no JavaScript frameworks

## Requirements

- [Typecho](https://typecho.org/) blog engine
- PHP 7.0+

## Installation

1. Download or clone this repository into your Typecho themes directory:
   ```bash
   cd /path/to/typecho/usr/themes/
   git clone https://github.com/jrtxio/simple.git
   ```

2. Log in to your Typecho admin panel.

3. Go to **Control Panel > Appearance** and enable the **Simple** theme.

## Theme Structure

```
simple/
  index.php        # Blog homepage (post list)
  post.php         # Single post view
  page.php         # Custom page view
  iheader.php      # Header for homepage (includes navbar)
  pheader.php      # Header for post/page views
  css/
    bootstrap.min.css        # Bootstrap core
    bootstrap-theme.min.css  # Bootstrap theme
    home.css                 # Homepage styles
    main.css                 # Post/page styles
  images/
    logo.svg       # Site logo
    Octocat.jpg    # Favicon
  screenshot.png   # Theme preview image
```

## Customization

- Edit `css/home.css` and `css/main.css` to change the appearance
- Modify `iheader.php` to adjust the navigation links
- Replace `images/Octocat.jpg` with your own favicon

## License

This project does not currently include a license file.
