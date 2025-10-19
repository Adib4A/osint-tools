# 🕵️ OSINT Guide

## Introduction

OSINT (Open-Source Intelligence) involves the collection and analysis of information that is publicly available. Key domains include:

- **Introduction**: The foundational principles of OSINT as a method for lawful information gathering.
- **Information Gathering**: Data extraction from public sources.
- **[MITRE ATT&CK](https://attack.mitre.org/)**: A framework for understanding cyber attack tactics and techniques, providing detailed insights into this structure.
- **OSINT**: Open-Source Intelligence techniques.
- **Data Leaks**: Identifying leaked data such as emails and passwords.
- **Images**: Analyzing metadata (e.g., GPS, date/time) in images.
- **Search Engine**: Utilizing advanced search tools.
- **Deep Web and Dark Web**: Accessing the hidden layers of the internet.
- **Privacy**: Protecting personal data while conducting OSINT.
- **Email and Username**: Investigating user identities.
- **Data Leak Databases**: Reviewing compromised databases.
- **OSINT Testing**: Practical application of OSINT methodologies.

Other intelligence disciplines include **MASINT** (Measurement and Signature Intelligence), **GEOINT** (Geospatial Intelligence), **HUMINT** (Human Intelligence), **FININT** (Financial Intelligence), **CYBINT** (Cyber Intelligence), **TECHINT** (Technical Intelligence), **SIGINT** (Signals Intelligence), and **OSINT**.

***

## Frameworks and Models

- **Social Media**: A primary source for personal and social data.
- **[SANS Institute](https://www.sans.org/cyber-security-courses/open-source-intelligence-gathering/)**: An OSINT framework training course that offers comprehensive educational resources for learning.
- **Big Data**: Utilizing large datasets for analysis.
- **Cyber Kill Chain**: A model to describe the stages of a cyber attack.

***

## General Information Gathering Tools

- **Includes**:
- **[GitHub SpiderFoot](https://github.com/smicallef/spiderfoot)**: An automated OSINT scanning tool useful for autonomous data collection.
- **[Maltego](https://www.maltego.com/)**: A graphical tool for link analysis that visually represents relationships between data points.
- **[OSINT.ir](https://osint.ir/)**: A Persian OSINT resource that provides relevant OSINT content in the Persian language.
- **[GitHub theHarvester](https://github.com/laramies/theHarvester)**: An email and subdomain gathering tool designed for extracting information from public sources.

***

## Image and Media Analysis

- **Includes**:
- **[ExifTool](https://exiftool.org/)**: A command-line metadata editor used for reading and editing metadata.
- **[Pic2Map](https://www.pic2map.com/)**: Online EXIF location viewer that extracts the geographical location from images.
- **[Google Images](https://images.google.com/)**: Reverse image search used to find similar images.
- **[Yandex Images](https://yandex.com/images/)**: Advanced reverse image search offering more sophisticated search options.
- **[Bing Images](https://www.bing.com/images/)**: Reverse image search serving as an alternative to Google.
- **[TinEye](https://tineye.com/)**: A reverse image search engine operating based on specific algorithms.

***

## Mapping and Tracking

- **Includes**:
- **[Wikimapia](https://wikimapia.org/)**: User-generated interactive maps providing user-contributed information.
- **[Liveuamap](https://liveuamap.com/)**: Global live event maps showing current events.
- **[Flightradar24](https://www.flightradar24.com/)**: Flight tracking providing live flight data.
- **[RadarBox](https://www.radarbox.com/)**: Aircraft tracking, similar to Flightradar24.
- **[VesselFinder](https://www.vesselfinder.com/)**: Ship tracking showing vessel positions.
- **[IPLocation.net](https://iplocation.net/)**: IP geolocation that extracts IP location information.

***

## Search Engines and Dorks

- **Meta Search Engines**:
- **[DuckDuckGo](https://duckduckgo.com/)**: Privacy-preserving search engine that operates without user tracking.
- **[Google](https://www.google.com/)**: Advanced search with sophisticated operators.
- **Google Dorks**: Operators such as `site:`, `intitle:`, `filetype:`, `inurl:`, `AND`, `OR`, `NOT`, `~`. Example: `site:.ir intitle:"index of admin"`
- **[Shodan](https://www.shodan.io/)**: IoT device search engine that searches for connected devices.
- **[Censys](https://censys.io/)**: Device search providing internet scanning data.
- **[ZoomEye](https://www.zoomeye.org/)**: A cyberspace search engine useful for vulnerability searching.
- **[Biznar](https://biznar.com/)**: Business search that focuses on commercial information.

***

## Deep Web and Dark Web

- **Web Layers**: Surface Web, Deep Web, Dark Web.
- **Torch**: Search for .onion sites (requires Tor for access; the link is a direct .onion link, but refer to Tor resources for more information).
- **[Ahmia](https://ahmia.fi/)**: Secure Dark Web search that indexes .onion sites.
- **[Tor Project](https://www.torproject.org/)**: Anonymous network for Dark Web access that provides an anonymous browser.
- **[Proxifier](https://www.proxifier.com/)**: A proxy tool that routes traffic through a proxy.
- **[SourceForge Kodachi](https://sourceforge.net/projects/linuxkodachi/)**: A Linux distribution for anonymity that is a secure operating system.
- **[Tails](https://tails.net/)**: An anonymous operating system via USB, designed for privacy preservation.
- **[GitHub ProxyChains](https://github.com/haad/proxychains)**: Proxy chain tool used for chaining proxies.
- **[Gather Proxy](https://gather-proxy.com/)**: Proxy list collection that provides a list of free proxies.
- **[Hidden Wiki](https://thehiddenwiki.org/)**: Dark Web site directory that lists .onion links (Note: actual access requires Tor).

***

## Generators and Checkers

- **Includes**:
- **[Fake Name Generator](https://www.fakenamegenerator.com/)**: Fake name generation that creates fake identities.
- **[Fake Person Generator](https://www.fakepersongenerator.com/)**: Fake profile creation that provides complete details.
- **[BestRandoms](https://bestrandoms.com/random-username-generator)**: Tools like BestRandoms that generate random usernames.

***

## Email and Username Tools

- **Includes**:
- **[Outlook](https://outlook.live.com/)**: Email service used for creating email accounts.
- **[Emailable](https://emailable.com/)**: Email verification that checks the validity of emails.
- **[Email-Checker.net](https://email-checker.net/)**: Email check that confirms the existence of an email.
- **[Hunter.io](https://hunter.io/)**: Email finder that discovers emails associated with a domain.
- **[InfoTracer](https://infotracer.com/)**: Personal data search that looks up information about individuals.
- **[Gravatar](https://en.gravatar.com/)**: Profile images that display avatars linked to an email.
- **[InstantUsername](https://instantusername.com/)**: Username checker that checks across various networks.
- **[NameChk](https://namechk.com/)**: Username checker that indicates username availability.
- **[EmailRep.io](https://emailrep.io/)**: Email reputation check that assesses email risk.

***

## Data Leak Tools

- **Includes**:
- **[DeHashed](https://dehashed.com/)**: Leaked data search that searches hacked databases.
- **[HaveIBeenPwned](https://haveibeenpwned.com/)**: Email leak check that verifies known breaches.
- **[Spokeo](https://www.spokeo.com/)**: People search that aggregates public information about individuals.
- **[IntelX](https://intelx.io/)**: Advanced search that performs deep searching in leaked data.
- **[Pastebin](https://pastebin.com/)**: Leaked text search that hosts public text.
- **[SpyCloud](https://spycloud.com/)**: Data leak analysis that analyzes stolen data.

***

## Network and Attack Surface Tools

- **Includes**:
- **[ViewDNS](https://viewdns.info/)**: DNS tools that provide DNS information.
- **[Pentest-Tools](https://pentest-tools.com/)**: Penetration testing tools that perform security scans.
- **[Bettercap](https://www.bettercap.org/)**: Used for network attacks.
- **[Wayback Machine](https://archive.org/web/)**: Web archive that stores older versions of websites.

***

## API Services

- **Includes**:
- **[AbuseIPDB](https://www.abuseipdb.com/)**: Malicious IP reporting that reports bad IPs.
- **[Etherscan](https://etherscan.io/)**: Blockchain explorer that shows Ethereum transactions.
- **[FullHunt](https://fullhunt.io/)**: Attack surface search that scans the attack surface.
- **[Viz.GreyNoise](https://viz.greynoise.io/)**: IP noise analysis that analyzes internet noise (Note: may require access).
- **[Hybrid-Analysis](https://hybrid-analysis.com/)**: Malware analysis that examines suspicious files.
- **[IKnowWhatYouDownload](https://iknowwhatyoudownload.com/)**: Download tracker that tracks torrent downloads.
- **[IPAPI](https://ipapi.com/)**: IP information that provides an API for IP data.
- **[Host.io](https://host.io/)**: Domain data that aggregates information about domains.
- **[Leak-Lookup](https://leak-lookup.com/)**: Data leak search that searches for breaches.
- **[Maltiverse](https://maltiverse.com/)**: Threat intelligence that analyzes IOCs (Indicators of Compromise).
- **[NetworksDB](https://networksdb.io/)**: Network database that provides network data.
- **[Pulsedive](https://pulsedive.com/)**: IOC analysis that scans for threats.
- **[URLScan](https://urlscan.io/)**: URL scanning that examines URLs.
- **[WhatCMS](https://whatcms.org/)**: CMS identification that detects the content management system of websites.
