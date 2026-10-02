<p align="center">
  <img src="https://raw.githubusercontent.com/DrakesCraft-Labs/GlobiaMachines/main/banner.svg" alt="GlobiaMachines banner" width="100%">
</p>

# GlobiaMachines

> ### 🏰 ¡Únete a la Comunidad Oficial de DrakesCraft!
> 
> * 🎮 **IP del Servidor**: `play.drakescraft.net` *(Java 1.21.11 & Bedrock)*
> * 💬 **Discord Oficial**: [discord.gg/drakescraft](https://discord.gg/rv3vtXZTk7)
> * 🌐 **Web & Guía**: [drakescraft.net](https://drakescraft.net) — 🛒 **Tienda**: [tienda.drakescraft.net](https://tienda.drakescraft.net)
> 
> *¡Juega con este addon y más de 80 expansiones optimizadas en vivo en nuestra network de supervivencia técnica!*

---

GlobiaMachines is a maintained Slimefun addon for the DrakesCraft 1.21.11 ecosystem. It restores the Budget Dust Fabricator as a compact early-game machine while preserving its original Slimefun item ID and stored-block compatibility.

## Features

- Budget Dust Fabricator with an energy-backed processing cycle.
- Native integration with the DrakesCraft Slimefun core namespace.
- Dedicated nested guide category and machine subgroup.
- Spanish in-game naming for the DrakesCraft community.
- Stable `GLOBIA_BUDGET_DUST_FABRICATOR` identity for existing worlds.

## Compatibility

| Component | Target |
| --- | --- |
| Minecraft | 1.21.11 |
| Server | Paper / Purpur |
| Java | 21 |
| Slimefun | DrakesCraft maintained core |

This repository is maintained independently by DrakesCraft-Labs. It is not a fork dependency and does not require the upstream repository at runtime.

## Build

```bash
mvn clean verify
```

The production artifact is written to `target/GlobiaSlimefun v1.0.0.jar`.

## Operational Notes

- Do not rename registered Slimefun IDs after deployment.
- Back up Slimefun block data before replacing production artifacts.
- A full server restart is required after updating the JAR.
- Existing machines remain valid because this port does not migrate or rewrite stored data.

---

## 📄 License & Upstream Attribution

This project is a sovereign fork maintained by [**JackStar6677-1**](https://github.com/JackStar6677-1) under [**DrakesCraft Labs**](https://github.com/DrakesCraft-Labs).

- **Original Project:** Created by the upstream authors and the open-source community.
- **DrakesCraft Optimizations:** Modernized for Paper/Purpur 1.21.11+, Java 21, high concurrency, asynchronous safety, and exploit/duplication prevention.
- **License:** Distributed under the original **GNU General Public License v3.0 (GPLv3)** (or original upstream license). See the [LICENSE](LICENSE) file for complete terms.
