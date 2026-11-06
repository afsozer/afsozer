# Alpaslan Fatih Sözer

Attorney at law in Denizli, Türkiye (Denizli Bar, registration no. 2858). My practice focuses on IT law, cybersecurity and data protection; I also handle employment, administrative and tax matters. I do security research on WordPress plugins and build tools that let AI assistants work with Turkish legal sources without inventing citations.

## Legal technology

- [Dayanak](https://github.com/afsozer/dayanak): MCP server for Turkish case law and legislation research, where every citation is checked against the official full text.
- [Doktor MCP](https://github.com/afsozer/doktor-mcp): source-based legal information for physicians on patient rights, informed consent and health data.
- [Belgelik](https://github.com/afsozer/belgelik): self-hosted legislation reader and document library that splits statutes down to the article and paragraph level.
- [Tensip](https://github.com/afsozer/tensip): keeps a local, searchable archive of case files from the UYAP lawyer portal (unofficial).
- [Telekumanda](https://github.com/afsozer/telekumanda): remote control for desktop coding agents from an Android phone, over a private network.
- [Seyir](https://github.com/afsozer/seyir): browser extension and MCP bridge that lets a coding agent work only in the tabs assigned to it.

## Security research

Five vulnerabilities in WordPress plugins validated through Patchstack so far: three have published CVE records, and two are awaiting vendor patches before disclosure.

- **[CVE-2026-110900](https://www.cve.org/CVERecord?id=CVE-2026-110900)**: missing authorization (CWE-862) in the BookIt WordPress plugin (2.6.0.5 and earlier), reported to the vendor through Patchstack under coordinated disclosure and fixed in 2.6.0.6.
- **[CVE-2026-111835](https://www.cve.org/CVERecord?id=CVE-2026-111835)**: missing authorization (CWE-862) in the Swish for WooCommerce payment plugin (3.7.8 and earlier) that let an unauthenticated user change the plugin settings, reported to the vendor through Patchstack under coordinated disclosure and fixed in 3.7.9.
- **[CVE-2026-48201](https://www.cve.org/CVERecord?id=CVE-2026-48201)**: unauthenticated stored cross-site scripting (CWE-79) in Fast Velocity Minify (3.5.7 and earlier, about 30,000 active installs), reported to the vendor through Patchstack under coordinated disclosure and fixed in 3.5.8.

[Patchstack profile](https://patchstack.com/database/researchers/27070f96-f225-4e2f-809a-4bbfde497266)

## Elsewhere

[avfatihsozer.com](https://avfatihsozer.com) · [LinkedIn](https://www.linkedin.com/in/alpaslanfatihsozer)
