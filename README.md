# Heading Style Field
<!--
The first paragraph of this file should be kept short as it will be used as the
project summary on BackdropCMS.org. Aim for about 240 characters (three lines at
80 characters each).

All lines in this file should be no more than 80 characters long for legibility,
unless including a URL or example that requires the line to not wrap.
|<- - - - - - - This line is exactly 80 characters for reference - - - - - - ->|

Detail in READMEs should be limited to the minimum required for installation and
getting started. More detailed documentation should be moved to a GitHub wiki
page; for example: https://github.com/backdrop-contrib/setup/wiki/Documentation.
-->
Heading Style Field allows you to define a flexible heading field that can be
any configured heading style, no style or even no heading. Each field instance
can be configured to have different styles available.

The main use case for this field type is with the
[Paragraphs](https://backdropcms.org/project/paragraphs) module. You can
add this field to each paragraph where there might need to be a heading and
allow the content editor to decide on the heading level. If you identify any
other use cases please feed back.

Default help text is provided to help users understand the purpose and benefits
of structured help text and this will be the default across all field instances
unless you have modified it consistently in more than one instance.

In addition to the default format that provides semantic HTML structure, a
Preview format is provided that gives in plain text the heading with the style
in brackets or "No heading" that can be used for the "Paragraphs Editor
Preview".

The default format includes an HTML ID and meaningful classes to help you target
a given heading.

### Icons
If you have the [Icon Field module](https://backdropcms.org/project/iconfield)
([GitHub](https://github.com/backdrop-contrib/iconfield)) installed, and the
paragraph type (or other entity this field exists on e.g. node) contains one or
more icon fields, then you will be given the option of using the selection of an
icon field in the heading.

If enabled and defined, then the first icon from that field will prefix the
title text. If you only want the icon in the heading then remove from the
display modes you are using.

This ability can be enabled and disabled in the field instance settings

If you use this module with
[Paragraphs jQuery UI Accordion 2](https://backdropcms.org/project/paragraphs_jquery_ui_accordion2)
then you will need to use the icon support functionality in that module rather
than this module.

## Installation
<!--
List the steps needed to install and configure the module. Add/remove steps as
necessary.
-->
- Install this module using the official Backdrop CMS instructions at
  https://docs.backdropcms.org/documentation/extend-with-modules.

## Issues
<!--
Link to the repo's issue queue.
-->
Bugs and Feature Requests should be reported in the Issue Queue:
https://github.com/backdrop-contrib/field_heading_style/issues.

## Current Maintainers
<!--
List the current maintainer(s) of the module, and note if this module needs
new/additional maintainers.
-->
- [Martin Price](https://github.com/yorkshire-pudding) - [System Horizons Ltd](https://www.systemhorizons.co.uk)
- Collaboration welcome!

## Credits
<!--
Give credit where credit's due.
If this is a Drupal port, state who ported it, and who wrote the original Drupal
module. If this module is based on another project, or uses third-party
libraries, list them here. You can also mention any organisations/companies who
sponsored the module's development.
-->
- Created for Backdrop CMS by - [Martin Price](https://github.com/yorkshire-pudding) - [System Horizons Ltd](https://www.systemhorizons.co.uk).

## License
<!--
Mention what license this module is released under, and where people can find
it.
-->

This project is GPL v2 software.
See the LICENSE.txt file in this directory for complete text.
