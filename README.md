# Awesome-GPU-Drivers-Macos-Hardware-Support

<p align="center">

  <img src="./assets/banner.svg" alt="Top GPU Drivers & macOS Hardware Support" width="100%" />

</p>



<p align="center">

  <a href="https://github.com"><img src="https://shields.io" alt="Awesome"/></a>

  <a href="https://discord.gg"><img src="https://shields.io" alt="Discord" /></a>

  <a href="https://github.com"><img src="https://shields.io" alt="GitHub stars" /></a>

  <a href="https://github.com"><img src="https://shields.io" alt="GitHub forks" /></a>

  <a href="https://github.com"><img alt="GitHub followers" src="https://shields.io" /></a>

</p>



# 🖥️ Top GPU Drivers & macOS Hardware Support



**Curated List of SaaS/Commercial Platforms & Open-Source GitHub Projects**  

*Focused on macOS GPU Drivers & Kexts (nvidia-macos-driver, OpenCore Legacy Patcher, WhateverGreen, NootedRed/NootRX), Graphics API Translation (MoltenVK, DXMT, Asahi Linux AGX) & Cloud GPU Workstations*  

**Last updated: November 2026**



This repository tracks notable **SaaS/Commercial platforms** and **open-source projects** for **GPU Drivers & macOS Hardware Support**. These tools power macOS NVIDIA/AMD/Intel GPU driver patches (`nullmoth/nvidia-macos-driver`, `OpenCore Legacy Patcher`, `WhateverGreen`, `NootedRed`, `NootRX`), Apple Silicon reverse-engineered GPU drivers (`Asahi Linux Mesa AGX`), Metal graphics translation layers (`MoltenVK`, `DXMT`), clean driver removal & bloat-free GPU utilities (`Display Driver Uninstaller`, `NVCleanstall`), and cloud GPU desktop streaming (`GeForce NOW`, `Paperspace`, `Shadow`, `AirGPU`) for Mac hardware enthusiasts and graphics engineers.



**Examples** include GeForce NOW (NVIDIA), NVIDIA GeForce Experience / NVIDIA App, AMD Software: Adrenalin Edition, Intel Arc Control, Parsec (Unity Technologies), Shadow PC (OVHcloud / Octave Klaba), Paperspace (DigitalOcean), Boosteroid, AirGPU, and Display Driver Uninstaller (Wagnardsoft) (the category leaders).



**🚀 Open-source emphasis**: This section is heavily expanded with every major active project for macOS GPU drivers & kexts (`nullmoth/nvidia-macos-driver`, `OpenCore Legacy Patcher`, `OpenCorePkg`, `WhateverGreen`, `NootedRed`, `NootRX`, `AppleALC`), Apple Silicon & Linux open-source GPU drivers (`Asahi Linux`, `Mesa 3D`, `NVIDIA Open GPU Kernel Modules`), Metal/Vulkan graphics bridges (`MoltenVK`, `DXMT`), and GPU telemetry & driver cleaners (`Display Driver Uninstaller`, `Stats`, `radeontop`, `nvtop`) — ideal for extending macOS hardware support and optimizing GPU stacks without vendor bloat.



🤝 Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## 📑 Table of Contents

- [📊 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)

- [☁️ SaaS/Hosted & Commercial Platforms](#️-saashosted--commercial-platforms)

- [💻 Open-Source GitHub Projects](#-open-source-github-projects)

- [🛠️ How to Contribute](#️-how-to-contribute)

- [⚠️ Disclaimer](#️-disclaimer)

- [💖 Support & Thank You](#-support--thank-you)



## 📊 Sector Overview & Market Dynamics



The global GPU Compute, Cloud Workstation & Graphics Driver Software market is valued at approximately **$18.5B–$24.0B+ in 2026**, expanding at a ~24%–30% CAGR driven by Apple Silicon Metal 3/4 graphics workloads, cloud GPU workstation streaming, and open-source Linux/macOS GPU enablement. While proprietary vendor driver suites (**NVIDIA App/GeForce Experience, AMD Adrenalin, Intel Arc Control**) and cloud GPU streaming (**GeForce NOW, Paperspace, Shadow**) exhibit **strong vendor consolidation**, the **macOS legacy/eGPU driver patching, Apple Silicon reverse-engineered Mesa/Vulkan, and DirectX-to-Metal translation ecosystems are overwhelmingly open-source driven** (`OpenCore Legacy Patcher`, `WhateverGreen`, `NootedRed`, `Asahi Linux`, `MoltenVK`, `DXMT`).



## ☁️ SaaS/Hosted & Commercial Platforms



*Sorted descending by company valuation / annual revenue scale.*



| Platform | Description | Company Scale (Valuation / Revenue) | Starting Paid Tier | Free Tier / Trial Limit |

| :--- | :--- | :--- | :--- | :--- |

| **[GeForce NOW (NVIDIA)](https://nvidia.com)** | Cloud RTX GPU streaming service delivering cloud-rendered Windows PC games natively onto macOS, Linux, and low-power laptops at up to 4K/120fps. | **Part of NVIDIA Corp.** (~$130B+ annual revenue; ~$3T+ market cap) | **$9.99 / month** ($49.99/6 mos Performance) or **$19.99 / month** ($99.99/6 mos Ultimate RTX 4080/5080) | **Forever Free Basic Tier** (Ad-supported **1-hour session limit** with standard queue access on native macOS & web clients) |

| **[NVIDIA GeForce Experience / NVIDIA App](https://nvidia.com)** | Official NVIDIA GPU driver manager, ShadowPlay recorder, Freestyle shader overlay, and cloud game-optimization profile utility for Windows PCs & cloud VMs. | **Part of NVIDIA Corp.** (~$130B+ annual revenue; ~$3T+ market cap) | **$0 / Free Proprietary Driver Suite** (Bundled free for all NVIDIA GeForce and RTX GPU owners) | **100% Free Forever** (Unlimited Game Ready & Studio driver updates, GPU tuning, and hardware video capture with zero fees) |

| **[AMD Software: Adrenalin Edition](https://amd.com)** | Official AMD Radeon GPU driver suite featuring AMD Link remote streaming, FSR upscaling, Radeon Anti-Lag, telemetry overlays, and overclocking tools. | **Part of AMD Inc.** (~$25B+ annual revenue; ~$220B+ market cap) | **$0 / Free Proprietary Driver Suite** (Bundled free for all AMD Radeon RX and Ryzen integrated GPU owners) | **100% Free Forever** (Unlimited driver updates, GPU clock/voltage tuning, performance metrics, and HYPR-RX presets) |

| **[Intel Arc Control / Graphics Software](https://intel.com)** | Official Intel Arc discrete and integrated GPU driver control panel featuring XeSS upscaling, telemetry overlays, and studio AV1 encoding tools. | **Part of Intel Corp.** (~$53B+ annual revenue; ~$100B+ public market cap) | **$0 / Free Proprietary Driver Suite** (Bundled free for all Intel Arc and Core Ultra GPU owners) | **100% Free Forever** (Unlimited Game On driver updates, real-time GPU telemetry, and fan/power tuning) |

| **[Parsec (Unity Technologies)](https://parsec.app)** | Ultra-low-latency GPU-accelerated remote desktop and workstation streaming app connecting macOS clients to remote NVIDIA/AMD GPU hosts. | **Part of Unity Technologies** (Acquired for $320M; ~$1.8B+ Unity annual revenue) | **$8.00 / month** billed annually ($9.99/mo monthly for Parsec Warp with 4:4:4 color & multi-monitor) | **Forever Free Personal Plan** (Unlimited 1080p/60fps hardware-accelerated remote GPU streaming on macOS, Windows & Linux) |

| **[Shadow PC (OVHcloud / Octave Klaba)](https://shadow.tech)** | Full cloud Windows 11 desktop with dedicated NVIDIA RTX GPUs streamed natively to macOS for running CUDA, DirectX 12, and Windows-only apps. | **Backed by Octave Klaba / OVHcloud** (~€1B+ OVHcloud group revenue) | **$19.99 / month** (Discovery tier) or **$32.99 – $49.99 / month** (Boost / Power RTX GPU tiers) | **No Perpetual Free Tier** (Occasional first-month promotional discounts; full cloud GPU workstation requires active subscription) |

| **[Paperspace (DigitalOcean)](https://paperspace.com)** | Cloud GPU virtual machines and Parsec-ready Windows/Linux GPU desktops offering on-demand NVIDIA RTX A4000/A6000 and H100 instances. | **Part of DigitalOcean** (Acquired for $111M; ~$780M+ DigitalOcean annual revenue) | **$0.51 / hour** (Pay-as-you-go hourly GPU compute + $7/mo static IP/storage; or Gradient Pro at $8/month) | **Forever Free Gradient CPU/GPU Tier** (Free 6-hour Jupyter notebook sessions on select free GPUs; cloud Windows GPU VMs billed hourly) |

| **[Boosteroid](https://boosteroid.com)** | Native macOS and browser cloud GPU gaming platform streaming Windows DirectX 12 titles at up to 4K/120fps without local GPU hardware. | **~$100M–$200M Est. Valuation** (~$20M–$40M est. ARR; rapid EU/US server expansion) | **€7.49 / month** billed annually (€89.89/yr) or **€9.89 / month** monthly for Ultra 4K | **No Perpetual Free Tier** (Free account enables latency and bitrate connection diagnostics on macOS prior to subscribing) |

| **[AirGPU](https://airgpu.com)** | Pay-as-you-go hourly cloud gaming and Parsec/Moonlight GPU workstation service letting Mac users spin up high-end RTX rigs by the hour. | **Bootstrapped Cloud GPU Provider** (Independent hourly cloud gaming VM platform) | **$0.65 / hour** (Pay-as-you-go compute rates from $0.65/hr to $1.20/hr based on GPU tier & cloud region) | **No Perpetual Free Tier** (Pay-per-hour model; no free trial; $5 minimum wallet deposit to provision VMs) |

| **[Display Driver Uninstaller — DDU (Wagnardsoft)](https://wagnardsoft.com)** | Industry-standard GPU driver removal utility cleanly purging leftover NVIDIA, AMD, and Intel registry keys, shader caches, and driver files. | **Independent Freeware Utility** (Maintained by Wagnardsoft; Patreon & ad supported) | **$0 / Freeware Utility** (Optional Patreon sponsorship for independent developer support) | **100% Free Forever** (Unlimited clean Safe-Mode uninstalls of NVIDIA, AMD, Intel, and Realtek drivers) |



## 💻 Open-Source GitHub Projects
