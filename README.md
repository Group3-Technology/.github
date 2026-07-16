# Group3 Technology

Precision magnetic measurement instruments — and the software that drives
them.

This GitHub organisation hosts the software side of our instruments: the
desktop application customers use to control and log from a teslameter, and
the open-source driver library underneath it.

## Download the software

### [⬇ DTM 151-S Teslameter — Control GUI](https://github.com/Group3-Technology/dtm151s-releases/releases/latest)

Desktop control and monitoring for the **DTM 151-S digital teslameter** over
a serial connection: live field and temperature readout, real-time plotting,
CSV logging, and a configurable derived measure.

Available for **macOS** and **Windows 10/11**. No installer, no admin rights,
and no separate runtime — unzip and run. Each download includes the full User
Guide.

First-launch approval steps, checksums, and troubleshooting are in the
[downloads repository](https://github.com/Group3-Technology/dtm151s-releases).

## Repositories

| Repository | What it is |
|------------|------------|
| [**dtm151s-releases**](https://github.com/Group3-Technology/dtm151s-releases) | Downloads for the DTM 151-S Control GUI — installers for macOS and Windows, checksums, and release notes. MIT. |
| [**group3lib**](https://github.com/Group3-Technology/group3lib) | A typed Python driver library for Group3 digital teslameters. Layered transport / protocol / session / model, so further instruments slot in without rewriting the core. Python 3.10+, no required runtime dependencies. MIT. |

Talking to a Group3 instrument from your own code? Start with **group3lib** —
it's the same driver the Control GUI uses.

## Support

For help with an instrument or its software, contact
**info@group3technology.com**.

For software issues, it speeds things up if you include:

- the application version — shown in the header bar, and under **Help → About**
- your operating system
- if it's a connection problem, what the **CONSOLE** tab shows

## About

**Group3 Technology** — New Zealand
[www.group3technology.com](https://www.group3technology.com)
