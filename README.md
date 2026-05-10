# Logos

A central repository for the logos of my various projects and tools. This allows tools to link to a single source of truth for their visual identity, ensuring consistency across different platforms and websites.

## Structure

Logos are organized by project name within the `project/` directory:

```
project/
└── <tool-name>/
    ├── dark.svg          # Full logo for dark backgrounds
    ├── light.svg         # Full logo for light backgrounds
    ├── small_dark.svg    # Icon/minimal logo for dark backgrounds
    └── small_light.svg   # Icon/minimal logo for light backgrounds
```

## Usage

You can link directly to these SVG files using GitHub's raw content URL or a CDN like jsDelivr.

### GitHub Raw
`https://raw.githubusercontent.com/<username>/logos/main/project/<tool-name>/<variant>.svg`

### jsDelivr
`https://cdn.jsdelivr.net/gh/<username>/logos@main/project/<tool-name>/<variant>.svg`

## Copyright and Attribution
All logos in this repository are the intellectual property of their respective creators.
Please ensure you have permission to use these logos and provide proper attribution when required.