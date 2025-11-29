<div align="center">
  <img src="assets/pygremlinbox-logo.png" alt="PyGremlinBox Logo" width="600"/>
</div>


# PyGremlinBox

PyGremlinBox is a comprehensive collection of Python packages designed for supply chain security testing and policy compliance evaluation. The project comprises seventy-one independent, self-contained modules: sixty-five licence-focused packages implementing different software licences, and six malware simulation packages containing benign code with strategically placed malicious URL indicators for tabletop exercises.

## Project Overview

This repository contains 71 independently published Python packages spanning two categories of supply chain security testing. The licence packages cover the complete spectrum of software licensing models, whilst the malware simulation packages provide controlled test subjects for evaluating threat detection capabilities.

The licence packages are organised into four primary categories: strong copyleft licences (9 packages), weak copyleft licences (23 packages), permissive and other licences (16 packages), and non-permissive licences (17 packages). This comprehensive coverage ensures thorough testing of licence detection and policy enforcement capabilities across diverse licensing scenarios.

The malware simulation packages cover six distinct attack vector categories commonly observed in supply chain attacks: network indicators, command-and-control beacons, code obfuscation, install-time execution, credential harvesting, and cryptomining indicators.

Current Version: 1.4.6

Package Locations:
- PyPI: https://pypi.org/search/?q=PyGremlinBox
- deps.dev: https://deps.dev/search?q=pygremlinbox
- Repository: https://github.com/gocortexio/pygremlinbox

## Purpose and Use Cases

PyGremlinBox packages serve as controlled test subjects for evaluating supply chain security infrastructure, including:

Licence Package Use Cases:
- Dependency Scanning Tools - Validate detection of licensing policies across the dependency tree
- Security Policy Enforcement - Test compliance systems' ability to identify and flag prohibited licences
- SPDX Compliance Testing - Verify correct interpretation of SPDX licence identifiers and metadata
- Supply Chain Analysis - Assess tools' capability to classify and report on licence obligations
- Continuous Integration Pipelines - Create test scenarios for automated licence compliance checks

Malware Simulation Package Use Cases:
- Threat Detection Testing - Validate security tools' ability to identify suspicious package naming patterns
- URL Reputation Systems - Test detection of known malicious infrastructure URLs
- Tabletop Exercises - Conduct realistic supply chain attack scenario walkthroughs
- Security Awareness Training - Demonstrate common attack vector patterns in controlled environments
- Incident Response Drills - Practice response procedures using benign test packages

Each package implements a standardised interface whilst maintaining authentic content and proper SPDX compliance, ensuring realistic testing conditions that mirror production dependency management scenarios.

## Licence Package Collection

### Strong Copyleft Licences (9 packages)

- pygremlinbox-agpl-1-0 - GNU Affero General Public Licence version 1.0
- pygremlinbox-agpl-1-0-only - GNU Affero General Public Licence version 1.0 only
- pygremlinbox-agpl-1-0-or-later - GNU Affero General Public Licence version 1.0 or later
- pygremlinbox-agpl-3-0 - GNU Affero General Public Licence version 3.0
- pygremlinbox-agpl-3-0-only - GNU Affero General Public Licence version 3.0 only
- pygremlinbox-agpl-3-0-or-later - GNU Affero General Public Licence version 3.0 or later
- pygremlinbox-gpl-2-0 - GNU General Public Licence version 2.0
- pygremlinbox-gpl-3-0 - GNU General Public Licence version 3.0
- pygremlinbox-sspl-1-0 - Server Side Public Licence v1.0

### Weak Copyleft Licences (23 packages)

- pygremlinbox-cal-1-0-combined-work-exception - Cryptographic Autonomy Licence 1.0 with Combined Work Exception
- pygremlinbox-cddl-1-0 - Common Development and Distribution Licence 1.0
- pygremlinbox-cern-ohl-s-2-0 - CERN Open Hardware Licence version 2.0 Strongly Reciprocal
- pygremlinbox-cern-ohl-w-2-0 - CERN Open Hardware Licence version 2.0 Weakly Reciprocal
- pygremlinbox-copyleft-next-0-3-0 - copyleft-next 0.3.0
- pygremlinbox-copyleft-next-0-3-1 - copyleft-next 0.3.1
- pygremlinbox-ecos-2-0 - eCos licence version 2.0
- pygremlinbox-epl-1-0 - Eclipse Public Licence version 1.0
- pygremlinbox-epl-2-0 - Eclipse Public Licence version 2.0
- pygremlinbox-eupl-1-1 - European Union Public Licence version 1.1
- pygremlinbox-eupl-1-2 - European Union Public Licence version 1.2
- pygremlinbox-eupl-3-0 - European Union Public Licence version 3.0
- pygremlinbox-lgpl-2-0 - GNU Lesser General Public Licence version 2.0
- pygremlinbox-lgpl-2-1 - GNU Lesser General Public Licence version 2.1
- pygremlinbox-lgpl-3-0 - GNU Lesser General Public Licence version 3.0
- pygremlinbox-linux-man-pages-copyleft - Linux man-pages Copyleft
- pygremlinbox-mpl-1-1 - Mozilla Public Licence version 1.1
- pygremlinbox-mpl-2-0 - Mozilla Public Licence version 2.0
- pygremlinbox-openpbs-2-3 - OpenPBS v2.3 Software Licence
- pygremlinbox-osl-3-0 - Open Software Licence version 3.0
- pygremlinbox-simpl-2-0 - Simple Public Licence 2.0
- pygremlinbox-tapr-ohl-1-0 - TAPR Open Hardware Licence v1.0
- pygremlinbox-wxwindows - wxWindows Library Licence

### Permissive and Other Licences (16 packages)

- pygremlinbox-apsl - Apple Public Source Licence version 2.0
- pygremlinbox-arphic-1999 - Arphic Public Licence
- pygremlinbox-artistic-1-0 - Artistic Licence 1.0
- pygremlinbox-cc-by-sa-2-0-uk - Creative Commons Attribution-ShareAlike 2.0 UK
- pygremlinbox-cc-by-sa-2-1-jp - Creative Commons Attribution-ShareAlike 2.1 Japan
- pygremlinbox-cc-by-sa-3-0-at - Creative Commons Attribution-ShareAlike 3.0 Austria
- pygremlinbox-cc-by-sa-3-0-de - Creative Commons Attribution-ShareAlike 3.0 Germany
- pygremlinbox-cc-by-sa-4-0 - Creative Commons Attribution-ShareAlike 4.0
- pygremlinbox-cpol-1-02 - Code Project Open Licence 1.02
- pygremlinbox-fdk-aac - Fraunhofer FDK AAC Codec Library
- pygremlinbox-ms-lpl - Microsoft Limited Public Licence
- pygremlinbox-qpl-1-0-inria-2004 - Q Public Licence 1.0 - INRIA 2004 variant
- pygremlinbox-sendmail-8-23 - Sendmail Licence 8.23
- pygremlinbox-tpl-1-0 - THOR Public Licence 1.0
- pygremlinbox-ucl-1-0 - Upstream Compatibility Licence v1.0
- pygremlinbox-unlicense - Unlicense (Public Domain)

### Non-Permissive Licences (17 packages)

- pygremlinbox-busl-1-1 - Business Source Licence v1.1
- pygremlinbox-c-uda-1-0 - Computational Use of Data Agreement v1.0
- pygremlinbox-cc-by-nc-3-0-de - Creative Commons Attribution Non Commercial 3.0 Germany
- pygremlinbox-cc-by-nc-nd-3-0-de - Creative Commons Attribution Non Commercial No Derivatives 3.0 Germany
- pygremlinbox-cc-by-nc-nd-3-0-igo - Creative Commons Attribution Non Commercial No Derivatives 3.0 IGO
- pygremlinbox-cc-by-nc-sa-2-0-de - Creative Commons Attribution Non Commercial Share Alike 2.0 Germany
- pygremlinbox-cc-by-nc-sa-2-0-fr - Creative Commons Attribution Non Commercial Share Alike 2.0 France
- pygremlinbox-cc-by-nc-sa-2-0-uk - Creative Commons Attribution Non Commercial Share Alike 2.0 UK
- pygremlinbox-cc-by-nc-sa-3-0-de - Creative Commons Attribution Non Commercial Share Alike 3.0 Germany
- pygremlinbox-cc-by-nc-sa-3-0-igo - Creative Commons Attribution Non Commercial Share Alike 3.0 IGO
- pygremlinbox-cc-by-nd-3-0-de - Creative Commons Attribution No Derivatives 3.0 Germany
- pygremlinbox-cdla-sharing-1-0 - Community Data Licence Agreement Sharing 1.0
- pygremlinbox-hippocratic-2-1 - Hippocratic Licence v2.1
- pygremlinbox-jpl-image - JPL Image Use Policy
- pygremlinbox-ncgl-uk-2-0 - Non-Commercial Government Licence UK v2.0
- pygremlinbox-polyform-noncommercial-1-0-0 - PolyForm Noncommercial Licence v1.0.0
- pygremlinbox-polyform-small-business-1-0-0 - PolyForm Small Business Licence v1.0.0

## Malware Simulation Package Collection (6 packages)

These packages contain minimal benign code with strategically placed malicious URL references designed to trigger alerts in security scanning tools. Each package uses suspicious naming patterns (test-malware, test-high-risk, test-command-and-control, test-phishing) combined with URLs pointing to known test infrastructure from Palo Alto Networks and sigre.xyz domains.

All malware simulation packages are licenced under GPL-3.0 for consistency.

### Network Indicators

- pygremlinbox-malware-network-indicators - Tests detection of outbound network communication patterns using HTTP/HTTPS endpoints pointing to test infrastructure

### Command and Control Beacon

- pygremlinbox-malware-c2-beacon - Simulates C2 beacon patterns with WebSocket channel URLs for testing detection of command-and-control infrastructure

### Code Obfuscation

- pygremlinbox-malware-code-obfuscation - Contains hidden path URL patterns commonly used in obfuscated malware payloads

### Install-Time Execution

- pygremlinbox-malware-install-execution - Implements installer/dropper URL patterns that trigger during package installation scenarios

### Credential Harvesting

- pygremlinbox-malware-credential-harvesting - Uses SSH/SFTP URL schemes commonly associated with credential exfiltration attempts

### Cryptomining Indicators

- pygremlinbox-malware-cryptomining-indicators - Contains FTP/FTPS URLs typically associated with cryptomining pool connections

## Package Interface

Each package provides a consistent, standardised interface for programmatic testing and automation.

### Licence Package Functions

get_licence_identifier()
Returns the SPDX licence identifier for the package.

```python
identifier = get_licence_identifier()
# Returns: "GPL-3.0", "LGPL-3.0", "MS-LPL", etc.
```

retrieve_licence_content()
Retrieves the complete licence text as specified in the package's LICENCE file.

```python
licence_text = retrieve_licence_content()
# Returns: Full licence text content
```

get_package_metadata()
Returns comprehensive package metadata including name, version, and licence information.

```python
metadata = get_package_metadata()
# Returns: Dictionary containing package_name, version, licence, and spdx_licence_id
```

### Malware Simulation Package Functions

get_package_metadata()
Returns package metadata including name, version, licence, and attack vector category.

```python
metadata = get_package_metadata()
# Returns: Dictionary containing package_name, version, licence, attack_vector, and description
```

get_test_urls()
Returns the list of test URLs embedded in the package for security tool validation.

```python
urls = get_test_urls()
# Returns: List of test infrastructure URLs
```

## Installation and Usage

### Installation

Each package is independently available from PyPI and can be installed using standard Python package management tools:

```bash
# Install individual licence packages
pip install pygremlinbox-gpl-3-0
pip install pygremlinbox-lgpl-3-0
pip install pygremlinbox-agpl-3-0

# Install malware simulation packages
pip install pygremlinbox-malware-network-indicators
pip install pygremlinbox-malware-c2-beacon

# Install multiple packages for comprehensive testing
pip install pygremlinbox-gpl-3-0 pygremlinbox-lgpl-3-0 pygremlinbox-busl-1-1
```

### Basic Usage - Licence Packages

```python
import pygremlinbox_gpl_3_0 as gpl_test

# Retrieve licence information
licence_id = gpl_test.get_licence_identifier()
print(f"Licence: {licence_id}")

# Get complete licence text
licence_text = gpl_test.retrieve_licence_content()
print(licence_text)

# Access package metadata
metadata = gpl_test.get_package_metadata()
print(f"Package: {metadata['package_name']}")
print(f"Version: {metadata['version']}")
print(f"SPDX ID: {metadata['spdx_licence_id']}")
```

### Basic Usage - Malware Simulation Packages

```python
import pygremlinbox_malware_network_indicators as network_test

# Access package metadata
metadata = network_test.get_package_metadata()
print(f"Package: {metadata['package_name']}")
print(f"Attack Vector: {metadata['attack_vector']}")

# Retrieve test URLs for validation
urls = network_test.get_test_urls()
for url in urls:
    print(f"Test URL: {url}")
```

### Testing Example

```python
# Example: Test dependency scanner against copyleft licences
import pygremlinbox_gpl_3_0
import pygremlinbox_agpl_3_0
import pygremlinbox_lgpl_3_0

test_packages = [
    pygremlinbox_gpl_3_0,
    pygremlinbox_agpl_3_0,
    pygremlinbox_lgpl_3_0
]

for pkg in test_packages:
    metadata = pkg.get_package_metadata()
    licence_id = pkg.get_licence_identifier()
    
    # Your security scanning logic here
    print(f"Scanning {metadata['package_name']} - Licence: {licence_id}")
```

## SPDX Compliance

All PyGremlinBox packages maintain strict SPDX 2.3 compliance:

- SPDX Identifiers - Each package uses accurate SPDX licence identifiers as specified in the official SPDX Licence List
- SPDX Headers - All Python source files include proper SPDX-License-Identifier and SPDX-FileCopyrightText headers
- Machine-Readable Metadata - Package metadata includes licence information in standardised, machine-readable format
- Individual LICENCE Files - Each package contains its own LICENCE file with official licence text
- PyPI Classifiers - Appropriate licence classifiers are specified for PyPI publication
- Self-Contained Architecture - No centralised licensing infrastructure; each package is independently compliant

The project uses professional SPDX tooling (spdx-tools, license-expression, reuse) for validation and maintains automated testing to ensure ongoing compliance across all 71 packages.

## Project Structure

Each package follows a standardised structure for consistency and maintainability:

```
PyGremlinBox-[LICENCE]/
+-- src/
|   +-- pygremlinbox_[licence]/
|       +-- __init__.py          # Package implementation
+-- pyproject.toml                # Package metadata and build configuration
+-- LICENCE                       # Official licence text
```

Malware simulation packages follow the same structure:

```
PyGremlinBox-Malware-[Category]/
+-- src/
|   +-- pygremlinbox_malware_[category]/
|       +-- __init__.py          # Package implementation with test URLs
+-- pyproject.toml                # Package metadata and build configuration
+-- LICENCE                       # GPL-3.0 licence text
```
