### Workings v2.0
## Created: Spring/Summer 2021

## TL;DR
This project was a recreation of the original Workings web app. The original was a simple client only app, made in plain JavaScript. It made no use of any frameworks or libraries outside of JQuery. While a few new versions were attempted, using TypeScript, Node.js, and React, they were never completed. This latest version makes use of ASP.NET, C#, and Blazor. It also features a backend API, with an SQL database, to support full customisation for a registered and signed in user. The app, like the original Workings, provides a **paperwork** from which a traditional roman blind can be assembled. This paperwork includes the customer and client details, the cut lengths of fabrics and linings, and measurements for assembling the blind.

## Aim
Provide an automated paperwork generator.

## Motivationasd
Dramatically simplify the process of calculating complex roman blind designs, including Cascade/Waterfall stacks, where each pleat has a varying length.

## Requirements
A full breakdown of the project requirements are:
* Provide a printable A4 paperwork
* Provide a simple form to fill out to generate the paperwork
* Form
    * Minimal
        * Show no more fields than required
        * Extend to show more fields where required