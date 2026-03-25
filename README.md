> [!WARNING]
> This project is in an early stage. the structure, data format, and workflows are not yet production ready please don't build systems around the current project

# Real-time Threat Intelligence Feed

This repository provides an open-access threat intelligence feed that is free to use and updated hourly. The data is aggregated and maintained through automated workflows, leveraging a range of external services to ensure timely and relevant intelligence.

## Feeds

ID | Name | Location | Schema | Last Updated
-- | ---- | -------- | ------ | ------------
CVE | CVE Records | [`data/cve`](./data/cve) | [`schema/cve.schema.json`](https://raw.githubusercontent.com/doodad-labs/threat-intelligence/refs/heads/main/schema/cve.schema.json) | `2026-03-25 07:13:28`
RANSOM | Ransomware Reports  | [`data/ransom`](./data/ransom) | [`schema/ransom.schema.json`](https://raw.githubusercontent.com/doodad-labs/threat-intelligence/refs/heads/main/schema/ransom.schema.json) | `2026-03-24 12:58:23`

## Disclaimer

This project does not host or distribute compromised, leaked, or illegal data. The feed only references publicly available information from external sources.

If you believe that personal, organisational, or otherwise sensitive information has been referenced improperly, please open an issue or contact the maintainers so it can be reviewed and addressed promptly.

## Donations

This feed relies on the work of external researchers and platforms that collect and publish security intelligence. If you are able, please consider supporting the projects that make this ecosystem possible.

- [ransomware.live](https://buymeacoffee.com/ransomwarelive)
- [haveibeenpwned.com](https://haveibeenpwned.com/Donate)
