# ATSDialFactory

<img width="2559" height="1306" alt="Screenshot 2026-10-17 082858" src="https://github.com/user-attachments/assets/17ec5ef5-f624-4a10-b208-b0e17b62a348" />

A browser-based watch face editor written in TypeScript for IDO smartwatches powered by Actions MCU platforms.

ATSDialFactory allows users to create, edit, preview, and export custom watch faces using the IDO watch face format.

## Features

* Browser-based watch face editing
* Interactive watch preview renderer
* IDO `.iwf` project support
* Custom image-based font rendering
* Clock hand editing with anchor and rotation support
* Widget-based watch face design
* `iwf.json` and `font.json` compatibility
* Watch face preview generation
* Exportable watch face packages

## Supported Devices

Currently supported:

### Smartwatches:
* IDW13
* IDW18
* IDW17
* IDW20

### Rugged Smartwatches:
* TIT15
* ID Sport03

### Smartbands:
* GTBand

Other smartwatches will be added in future releases.

## Important Notes
* Ring widgets, Progressbar widgets, and some custom widgets are not supported yet. They will be added once reverse-engineered further.
* IDO Smartwatches or Smartbands with Sifli MCUs are NOT compatible with this editor since they use an encrypted format `.watch`.

## About

ATSDialFactory is designed to provide a modern, browser-based workflow for creating watch faces for IDO smartwatches using web technologies without complex installations of Python, C++, or other coding languages.

The project focuses on compatibility with Actions MCU-based IDO devices while providing a more accessible alternative to traditional watch face creation tools.
