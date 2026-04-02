> [!WARNING]
> This project is in an early stage. The structure, data format, and workflows are not yet production-ready. Please avoid building systems that depend on the current state of this project.

# Real-time Threat Intelligence Feed

This repository provides an open-access threat intelligence feed that is free to use and updated hourly. Data is aggregated and maintained through automated workflows that integrate multiple external intelligence sources, ensuring the feed remains timely and relevant.

The goal of the project is to provide a simple, transparent, and machine-consumable dataset that can be used for research, security monitoring, and experimentation.

## Feeds

ID | Name | Location | Schema | Index | Last Updated
-- | ---- | -------- | ------ | ----- | ------------
CVE | CVE Records | [`data/cve`](./data/cve) | [`schema/cve.schema.json`](./schema/cve.schema.json) | [`indexes/cve.index.json`](./indexes/cve.index.json) | `2026-04-02 02:29:14`

## Disclaimer

This project does not host, store, or distribute compromised, leaked, or otherwise illegal data. The feed references information that is already publicly available from external sources.

Some entries may reference or include proof-of-concept or exploitation code. Such material is retained strictly for educational, defensive, and security research purposes. The repository does not develop, modify, or distribute exploit code in a manner intended for weaponisation.

If you believe that personal, organisational, or other sensitive information has been referenced improperly, please open an issue or contact the maintainers so the matter can be reviewed and addressed promptly.

## Sources and Feeders

This feed builds upon the work of several external researchers, organisations, and platforms that collect and publish security intelligence.

- [ExploitDB](https://www.exploit-db.com/about-exploit-db)
- [NIST National Vulnerability Database](https://nvd.nist.gov/)
- [Shodan](https://www.shodan.io/)
- [Computer Incident Response Center Luxembourg](https://circl.lu/)
