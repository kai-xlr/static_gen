# static_gen

A static site generator project.

## Overview

This project contains a static website with HTML and CSS files ready to be served.

## Project Structure

```
static_gen/
├── public/              # Static site files
│   ├── index.html       # Main HTML page
│   └── styles.css       # Stylesheet
└── README.md
```

## Usage

To view the site locally, you can use any static file server. For example:

```bash
# Using Python's built-in HTTP server
python -m http.server 8000 -d public

# Then open http://localhost:8000 in your browser
```

## Development

The site files are located in the `public/` directory. Edit the HTML and CSS files directly to make changes.
