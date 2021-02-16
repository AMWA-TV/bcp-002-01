# AMWA BCP-002-01: Natural Grouping of NMOS Resources

[![Lint Status](https://github.com/AMWA-TV/nmos-natural-grouping/workflows/Lint/badge.svg)](https://github.com/AMWA-TV/nmos-natural-grouping/actions?query=workflow%3ALint)
[![Render Status](https://github.com/AMWA-TV/nmos-natural-grouping/workflows/Render/badge.svg)](https://github.com/AMWA-TV/nmos-natural-grouping/actions?query=workflow%3ARender)

This repository holds the source for this Specification, part of the family of [Networked Media Open Specifications](https://specs.amwa.tv/nmos) from the [Advanced Media Workflow Association](https://amwa.tv)

<!-- INTRO-START -->

### What does it do?

- Documents best practice and recommendations for how to indicate and handle "Natural Groups" of Resources in AMWA NMOS APIs.
- These are those created by the default operation of a Node/Device, and not user- or automation-defined Groups.

### Why does it matter?


- Provides a consistent way of referring to groups of related Resources (e.g. video and audio Senders of a camera)
- This helps with interoperability and integration.


### How does it work?

- Nodes add a `grouphint` tag to the JSON representation of each member of a Natural Group.

<!-- INTRO-END -->

## Getting started

There is more information about the NMOS Specifications and their GitHub repos at <https://specs.amwa.tv/nmos>.
