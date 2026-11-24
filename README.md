# Project Portfolio

A curated portfolio of software, systems, infrastructure, design, and technical-writing work. Projects include personal experiments, home-lab work, and study assignments; they are not presented as commercial client deployments. Each entry describes the work and links to a case study, source code, or article when available.

## Systems and Infrastructure

- **Offline voice assistant on ODROID-C2** — explored local speech recognition with Qwen2.5 through Ollama and Piper speech output; documented boot and audio troubleshooting on a 2 GB ARM board. [Case study](./Edge%20AI%20and%20Systems%20Engineering.pdf) · [Source code](https://github.com/xardbazz/light-AI-OdroidC2)
- **Windows 11 virtualization on Arch Linux** — booted an existing Windows installation as a VirtualBox VM while isolating the host EFI and GRUB setup. [Case study](./Windows%2011%20Virtualization%20on%20Arch%20Linux.pdf)
- **Arch Linux and Windows dual boot** — planned the EFI layout, configured GRUB and Windows detection, and set up NVIDIA drivers on one NVMe drive. [Case study](./Arch%20Linux%20%2B%20Windows%20Dual-Boot%20System.pdf)
- **Linux troubleshooting and recovery** — used an image-first SD-card recovery approach and diagnosed APT repository and network issues on an ARM board. [Case study](./Linux%20Troubleshooting%20and%20Recovery.pdf)
- **RustDesk rendezvous setup** — configured and checked the `hbbs` service on Windows. The documentation distinguishes it from the separate `hbbr` relay and does not claim a full relay deployment. [Case study](./Networking%20%26%20Remote%20Access.pdf)

## Software and Automation

- **KamCam** — Python desktop tool that routes Android video to a Linux virtual camera using scrcpy and v4l2loopback. A separate Windows camera path uses a native C++ component and is still being evaluated. [Source code](https://github.com/xardbazz/KamCam) · [Case study](./KamCam%20Virtual%20Webcam.pdf)
- **Green API Chat** — React and TypeScript test assignment for sending and receiving WhatsApp messages through Green-API. [Source code](https://github.com/xardbazz/green-api-chat) · [Case study](./Green%20API%20Chat.pdf)
- **RoutesConverter** — standalone Windows batch script that converts route entries and subnet masks to CIDR notation. [Case study](./RoutesConverter%20Utility.pdf)
- **Issa-Tech** — university e-commerce project with product management, a cart, and order processing. [Source code](https://github.com/xardbazz/Issa-Tech)
- **Farming Simulator** — Unity and C# game prototype with basic planting, growth, and economy mechanics. [Source code](https://github.com/xardbazz/Farming-simulator)

## Design and Interactive Media

- **Adobe XD interface prototypes** — mobile UI concepts for EVE appointment scheduling, medication reminders, and Smile phone-number onboarding. These are design prototypes, not claims of implemented products. [Case study PDF](./Adobe%20XD%20UI%20UX%20Prototypes.pdf)
- **Half-Life Lambda Audio Visualizer** — Wallpaper Engine project combining an audio visualizer, a WebGL fluid simulation, and an animated Lambda logo. [Case study](./Half-Life%20Lambda%20Audio%20Visualizer%20%28Wallpaper%20Engine%29.pdf) · [Source code](https://github.com/xardbazz/Custom-logo-Audio-Visualizer-for-Wallpaper-engine)
- **Custom audio-reactive OBS overlay** — streaming overlay and visual assets built around OBS and audio-reactive presentation. [Case study](./Custom%20Audio-Reactive%20OBS%20Overlay.pdf)

## Technical Writing

- **Valve and Linux** — personal article about choosing and configuring a Linux and Windows setup for gaming and development. [Article PDF](./Blog%20Valve%20and%20linux.pdf) · [Project summary](./Technical%20Writing%20%26%20Community%20Contribution.pdf)
