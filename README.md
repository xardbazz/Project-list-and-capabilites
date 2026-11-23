# Project Portfolio

A curated set of software, systems, and troubleshooting projects. Most entries are personal projects, home-lab work, or study assignments; they are not presented as commercial client deployments. The write-ups focus on the problem, the approach, and the tools used.

## Systems and Infrastructure

- **Offline voice assistant on ODROID-C2** — local speech recognition, Qwen2.5 through Ollama, Piper speech output, and boot/audio troubleshooting on a 2 GB ARM board. [Case study PDF](./Edge%20AI%20%26%20Systems%20Engineering.pdf) · [Source code](https://github.com/xardbazz/light-AI-OdroidC2)
- **Windows 11 in VirtualBox on Arch Linux** — booted an existing Windows installation as a VM while isolating the host EFI and GRUB setup. [Case study PDF](./Virtualization%20%26%20Dual-Boot%20Architecture.pdf)
- **Arch Linux and Windows dual boot** — EFI partition planning, GRUB/Windows detection, and NVIDIA driver setup on one NVMe drive. [Case study PDF](./Arch%20Linux%20%2B%20Windows%20Dual-Boot%20System.pdf)
- **Linux troubleshooting and recovery** — image-first SD-card recovery and APT repository/network diagnosis on an ARM board. [Case study PDF](./Linux%20Troubleshooting%20%26%20Recovery.pdf)
- **RustDesk rendezvous setup** — configured and checked the hbbs service on Windows. The write-up distinguishes the rendezvous service from the separate hbbr relay component; it does not claim a complete relay deployment. [Case study PDF](./Networking%20%26%20Remote%20Access.pdf)

## Software and Automation

- **KamCam** — Python desktop tool that routes Android video to a Linux virtual camera using scrcpy and v4l2loopback. A separate Windows camera path uses a native C++ component and is still being evaluated. [Source code](https://github.com/xardbazz/KamCam)
- **Green API Chat** — React and TypeScript test assignment for sending and receiving WhatsApp messages through Green-API. [Source code](https://github.com/xardbazz/green-api-chat)
- **RoutesConverter** — standalone Windows batch script that converts route entries and subnet masks to CIDR notation. [Case study PDF](./System%20Administration%20%26%20Scripting%20Utilities.pdf)
- **Issa-Tech** — university e-commerce project with product management, a cart, and order processing. [Source code](https://github.com/xardbazz/Issa-Tech)
- **Farming Simulator** — Unity and C# game prototype with basic planting, growth, and economy mechanics. [Source code](https://github.com/xardbazz/Farming-simulator)
- **Half-Life Lambda Audio Visualizer** — Wallpaper Engine project combining an audio visualizer, a WebGL fluid simulation, and an animated Lambda logo. [Case study PDF](./Half-Life%20Lambda%20Audio%20Visualizer%20%28Wallpaper%20Engine%29.pdf) · [Source code](https://github.com/xardbazz/Custom-logo-Audio-Visualizer-for-Wallpaper-engine)

## Technical Writing

- **Valve and Linux** — personal article about choosing and configuring a Linux and Windows setup for gaming and development. [Article PDF](./Blog%20Valve%20and%20linux.pdf) · [Project summary](./Technical%20Writing%20%26%20Community%20Contribution.pdf)
