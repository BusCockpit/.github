# BusCockpit

Hobby project integrating real bus cockpit hardware with bus simulation games.

Work in progress.

## Repositories

| Repo | Language | Runs on | Purpose |
|------|----------|---------|---------|
| [BusCockpit](https://github.com/BusCockpit/buscockpit) | Markdown | – | Documentation of architecture, protocols, hardware etc. |
| [BusLink](https://github.com/buscockpit/buslink) | Rust | Gaming PC | Real-time business logic, interfaces game simulation and real world dashboard, listens and speaks to TML and OmsiLink REST API, listens to PoKeys57U and speaks to Busdriver in real world dashboard |
| [OmsiLink](https://github.com/buscockpit/omsilink) | C# | Gaming PC | HTTP REST adapter for OMSI 2 (via OmsiHook) |
| [openOMSI](https://github.com/buscockpit/openomsi) | Rust | Gaming PC | Private mirror of [openOMSI](https://github.com/openOMSI-Project/openOMSI), the open-source OMSI 2 reimplementation, with a built-in telemetry module that speaks OmsiLink's REST API to BusLink |
| [Busdriver](https://github.com/buscockpit/busdriver) | Python | Raspberry Pi 4 | Drives real world dashboard (24V lights and PWM tacho), listens to BusLink |
| [Fernbus](https://github.com/buscockpit/fernbus) | Python | Dev machines | Development and research tools |
| [DeployLink](https://github.com/buscockpit/deploylink) | PowerShell | Target machines | Deployment scripts and tooling for installing BusCockpit components |
| [Archive](https://github.com/buscockpit/archive) | – | – | Legacy and reference material |
