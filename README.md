# Awesome

A collection of awesome scripts, queries, etc. 

- [Cyber threat intelligence](#cyber-threat-intelligence)
  - [Vulnerability intelligence](#vulnerability-intelligence)
  - [STIX 2](#stix-2)
- [Go](#go)
- [Tools](#tools)
- [APIs](#apis)
  - [Shodan](#shodan)
  - [Have I Been Pwned?](#have-i-been-pwned)
- [Frontend development](#frontend-development)
  - [Web](#web)
  - [TUI](#tui)

## Cyber threat intelligence

### Vulnerability intelligence

- [CVEProject/cve-schema](https://github.com/CVEProject/cve-schema): [JSON Schema](https://json-schema.org/) for [CVE JSON format](https://github.com/CVEProject/cve-schema)
- [CVEProject/cvelistV5](https://github.com/CVEProject/cvelistV5): list of all CVEs in CVE JSON 5.0 format

### STIX 2

- [mitre/cti](https://github.com/mitre/cti): MITRE ATT&CK for [Enterprise](https://github.com/mitre/cti/tree/master/enterprise-attack), [Mobile](https://github.com/mitre/cti/tree/master/mobile-attack), [ICS](https://github.com/mitre/cti/tree/master/ics-attack) in STIX 2.0 format, [MITRE CAPEC](https://github.com/mitre/cti/tree/master/capec) in [STIX 2.0](https://github.com/mitre/cti/tree/master/capec/2.0) and [STIX 2.1](https://github.com/mitre/cti/tree/master/capec/2.1) format
- [oasis-open/cti-stix-common-objects](https://github.com/oasis-open/cti-stix-common-objects): repository of common STIX 2 objects
- [oasis-open/cti-stix-elevator](https://github.com/oasis-open/cti-stix-elevator): STIX 1.2 (XML) -> STIX 2 (JSON)

## Go

- [palantir/amalgomate](https://github.com/palantir/amalgomate): Go tool for combining multiple different main packages into a single program or library.

## Tools

- [palantir/osquery-configuration](https://github.com/palantir/osquery-configuration): an incident detection and response focused configuration for osquery.
- [facebook/pcicrawler](https://github.com/facebook/pcicrawler): a Python-based command line interface tool which can be used to display, filter and export information about PCI or PCIe buses and devices, as well as their topology.
- [facebookincubator/below](https://github.com/facebookincubator/below): a time-travelling, command-line interface driven resource monitor for Linux systems
- [facebookincubator/nvdtools](https://github.com/facebookincubator/nvdtools): Go-based tools for working with the NIST National Vulnerability Database (NVD)
- [facebookincubator/xar]https://github.com/facebookincubator/xar): a tool for packaging files into a read-only filesystem image powered by SquashFS.
- [facebookincubator](go2chef): a Go tool for bootstrapping Chef installations.
- [gchq/sleeper](https://github.com/gchq/sleeper): serverless, cloud-native, log-structured, merge-tree-based key/value store for AWS
- [gchq/CyberChef](https://github.com/gchq/CyberChef): a Swiss-army knife for transforming data (e.g. compression/decompression, encryption/decryption, disassembly, encoding/decoding, etc.)
- [gchq/CyberChef-server](https://github.com/gchq/CyberChef-server): REST API for running Cyberchef recipes
- [mitre/caldera](https://github.com/mitre/caldera): an automated adversary emulation platform
- [mitre/skeleton](https://github.com/mitre/skeleton): a blank CALDERA plugin template
- [mitre/emu](https://github.com/mitre/emu): a CALDERA plugin for providing TTPs from Center for Threat Informed Defense (CTID) Adversary Emulation Plans
- [mitre/builder](https://github.com/mitre/builder): a CALDERA plugin for dynamically compiling code segments from abilities 
- [mitre/stockpile](https://github.com/mitre/stockpile): a CALDERA plugin
- [mitre/sandcat](https://github.com/mitre/sandcat): a CALDERA plugin
- [mitre/response](https://github.com/mitre/response): a CALDERA plugin
- [mitre/human](https://github.com/mitre/human): a CALDERA plugin
- [mitre/manx](https://github.com/mitre/manx): a CALDERA plugin
- [mitre/gameboard](https://github.com/mitre/gameboard): a CALDERA plugin that allows you to monitor red vs. blue team exercises (or, games)
- [mitre/access](https://github.com/mitre/access): a CALDERA plugin providing TTPs related to initial access
- [mitre/atomic](https://github.com/mitre/atomic): a CALDERA plugin providing TTPs from the Atomic Red Team framework
- [mitre/debrief](https://github.com/mitre/debrief): a CALDERA plugin for gathering campaign information and analytics for an operation within CALDERA
- [mitre/ssl](https://github.com/mitre/ssl): a CALDERA plugin providing TLS support for CALDERA
- [mitre/engage](https://github.com/mitre/engage): a framework for conducting Denial, Deception, and Adversary engagements
- [mitre/FindRogueElfs](https://github.com/mitre/FindRogueElfs): a Bash script for finding ELF files that aren't related to any RPM file on the system
- [xenoscr/AtomicCaldera](https://github.com/xenoscr/atomiccaldera): a CALDERA plugin for converting Atomic Red Team tests into MITRE CALDERA Stockpile YAML ability files
- [redcanaryco/atomic-red-team](https://github.com/redcanaryco/atomic-red-team): a library of small, highly-portable detection tests based on the MITRE ATT&CK framework
- [mitre-attack/attack-navigator](https://github.com/mitre-attack/attack-navigator): a web app for reading and writing MITRE ATT&CK Navigator layers
- [mitre-attack/attack-stix-data](https://github.com/mitre-attack/attack-stix-data): MITRE ATT&CK for [Enterprise](https://github.com/mitre-attack/attack-stix-data/tree/master/enterprise-attack), [Mobile](https://github.com/mitre-attack/attack-stix-data/tree/master/mobile-attack), [ICS](https://github.com/mitre-attack/attack-stix-data/tree/master/ics-attack) in STIX 2.1 format
- [mitre/terminal](https://github.com/mitre/terminal): a MITRE CALDERA plugin providing shell access into CALDERA along with reverse shell payloads for entering/exiting agents manually

## APIs

### Shodan

[Shodan](https://www.shodan.io/) is a search engine for the Internet of Everything.

- [go-shodan](https://github.com/ns3777k/go-shodan): Go client for Shodan.
- [awesome-shodan-queries](https://github.com/jakejarvis/awesome-shodan-queries): awesome Shodan queries.

### Have I Been Pwned?

[Have I Been Pwned?](https://haveibeenpwned.com/) is a website that allows Internet users to check whether their data has been compromised by data breaches.

- [go-hibp](https://github.com/wneessen/go-hibp): Go client for HaveIBeenPwned.

## Frontend development

### Web

- [facebook/react](https://github.com/facebook/react): a library for building user interfaces.
- [facebook/react-native](https://github.com/facebook/react-native): a library for building user interfaces for Android and iOS devices.
- [facebook/relay](https://github.com/facebook/relay): a GraphQL client for React.js.
- [palantir/blueprint](https://github.com/palantir/blueprint) is a React-based UI toolkit for the web. It is optimized for building complex, data-dense web interfaces for desktop applications which run in modern browsers. 
- [palantir/plottable](https://github.com/palantir/plottable) a library of modular chart components built on top of d3.js.

### TUI

- [facebookincubator/superconsole](https://github.com/facebookincubator/superconsole): Rust-based TUI framework
