![PyGremlinBox Logo](assets/pygremlinbox-logo.png)

# PyGremlinBox

PyGremlinBox is a comprehensive container project housing multiple Python modules for supply chain security testing. Each subproject contains different policy implementations that trigger alerts in dependency scanning tools, starting with comprehensive licence coverage, and can be individually published to PyPI.

## Project Overview

This repository contains twenty-two independent Python packages, each distributed under different licence types covering strong copyleft, weak copyleft, permissive, and non-permissive licences. These packages are designed to test the policy detection capabilities of supply chain security tools, with current focus on comprehensive licence coverage.

**Package Locations:**
- PyPI: https://pypi.org/search/?q=PyGremlinBox
- deps.dev: https://deps.dev/search?q=pygremlinbox

## Package Collection

### Strong Copyleft Licences
- **pygremlinbox-gpl-3-0** - GNU General Public Licence version 3.0
- **pygremlinbox-gpl-2-0** - GNU General Public Licence version 2.0
- **pygremlinbox-agpl-3-0** - GNU Affero General Public Licence version 3.0
- **pygremlinbox-agpl-2-0** - GNU Affero General Public Licence version 2.0

### Weak Copyleft Licences
- **pygremlinbox-lgpl-3-0** - GNU Lesser General Public Licence version 3.0
- **pygremlinbox-lgpl-2-1** - GNU Lesser General Public Licence version 2.1
- **pygremlinbox-mpl-2-0** - Mozilla Public Licence version 2.0
- **pygremlinbox-epl-2-0** - Eclipse Public Licence version 2.0
- **pygremlinbox-eupl-1-2** - European Union Public Licence version 1.2
- **pygremlinbox-eupl-1-1** - European Union Public Licence version 1.1
- **pygremlinbox-osl-3-0** - Open Software Licence version 3.0
- **pygremlinbox-cddl-1-0** - Common Development and Distribution License 1.0

### Permissive and Other Licences
- **pygremlinbox-cc-by-sa-4-0** - Creative Commons Attribution-ShareAlike 4.0
- **pygremlinbox-cc-by-sa-3-0-de** - Creative Commons Attribution-ShareAlike 3.0 Germany
- **pygremlinbox-apsl** - Apple Public Source Licence version 2.0
- **pygremlinbox-unlicense** - Unlicense (Public Domain)

### Non-Permissive Licences
- **pygremlinbox-busl-1-1** - Business Source Licence v1.1
- **pygremlinbox-c-uda-1-0** - Computational Use of Data Agreement v1.0
- **pygremlinbox-hippocratic-2-1** - Hippocratic Licence v2.1
- **pygremlinbox-ms-lpl** - Microsoft Limited Public Licence
- **pygremlinbox-ncgl-uk-2-0** - Non-Commercial Government Licence UK v2.0
- **pygremlinbox-polyform-noncommercial-1-0-0** - PolyForm Noncommercial Licence v1.0.0

## Purpose and Use Case

These packages serve as controlled test subjects for evaluating supply chain security tools and dependency scanning systems. Each package implements a standardised interface whilst containing policy indicators that should trigger appropriate alerts and classifications in security analysis tools.

## Package Interface

Each subproject provides consistent functionality through standardised methods:

- `retrieve_licence_content()` - Returns the complete licence text as specified in the LICENCE file
- `get_licence_identifier()` - Returns the standard licence identifier (e.g., "GPL-3.0", "AGPL-2.0")
- `get_package_metadata()` - Returns comprehensive package metadata including name, version, and licence information

## Installation and Usage

Each package can be installed independently from PyPI using standard Python package management tools:

```bash
pip install pygremlinbox-gpl-3-0
pip install pygremlinbox-agpl-3-0
# etc.
```

Once installed, packages can be imported and used for testing purposes:

```python
import pygremlinbox_gpl_3_0 as gpl_test

# Retrieve licence information
licence_id = gpl_test.get_licence_identifier()
licence_text = gpl_test.retrieve_licence_content()
metadata = gpl_test.get_package_metadata()
```