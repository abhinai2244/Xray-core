# Xray-core

## Overview
Xray-core is an advanced framework designed to streamline and manage network proxy solutions, offering enhanced security, scalability, and customization. It integrates multiple modular components to enable efficient and reliable data transmission. The project is built with flexibility and performance in mind, catering to developers and network administrators alike.

## Features
- **High Performance**: Optimized core components ensure low latency and high throughput.
- **Modular Design**: Easily customizable with a modular architecture.
- **Scalability**: Designed to handle a wide range of use cases, from small setups to large-scale deployments.
- **Security**: Implements robust encryption and authentication mechanisms to secure communications.

## Directory Structure
- **`app/`**: Contains the main application logic, including entry points and core functionalities. This is where the core business logic is implemented.
- **`common/`**: Houses shared utilities, helper functions, and constants that are reused across different modules.
- **`core/`**: Implements the core functionalities of the system, including key algorithms, protocols, and data processing.
- **`features/`**: Includes optional features and plugins that extend the core capabilities of the system.
- **`infra/`**: Manages infrastructure-related configurations and tools, such as deployment scripts, CI/CD pipelines, and environment setups.
- **`main/`**: Orchestrates the overall execution flow and integrates different modules of the project.
- **`proxy/`**: Focuses on proxy-specific implementations, including protocols, routing mechanisms, and data handling.
- **`testing/`**: Provides comprehensive testing scripts and frameworks to ensure the reliability and stability of the project.
- **`.github/`**: Contains GitHub-specific configuration files such as workflows for automated testing and deployment.

## Installation
To get started with Xray-core, follow these steps:

1. **Clone the repository:**
   ```bash
   https://github.com/abhinai2244/Xray-core.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd Xray-core
   ```

3. **Install dependencies:**
   If the project uses Python:
   ```bash
   pip install -r requirements.txt
   ```
   For other environments, follow the specific dependency management instructions provided in the documentation.

4. **Set up the environment:**
   Ensure all necessary environment variables and configurations are properly set by referring to the `infra/` or `.env.example` file.

## Usage
1. **Running the Application:**
   Launch the main application with the following command:
   ```bash
   python main.py
   ```
   You can customize the execution by providing configuration files or command-line arguments.

2. **Proxy Configuration:**
   Configure the proxy settings by editing the configuration files in the `proxy/` directory. Ensure compatibility with your network setup.

3. **Testing:**
   Run tests to validate the setup:
   ```bash
   python -m unittest discover testing
   ```

4. **Deployment:**
   Use the scripts in the `infra/` directory for deploying the application to production environments.

## Development Guidelines
To contribute to Xray-core, adhere to the following guidelines:

1. **Code Style:**
   - Follow the coding standards outlined in the `CONTRIBUTING.md` file.
   - Ensure code is properly documented with comments and docstrings.

2. **Testing:**
   - Write unit tests for new features or changes.
   - Ensure all tests pass before submitting a pull request.

3. **Branching Strategy:**
   - Use `main` for stable releases.
   - Create feature branches for new functionalities and bugfix branches for resolving issues.

## License
This project is licensed under the [License Name], which permits [summarize permissions and limitations]. See the `LICENSE` file for complete details.

## Roadmap
- **Version 2.0:** Introduce support for additional protocols and enhanced scalability.
- **Documentation:** Expand the documentation with tutorials and examples.
- **Community Support:** Foster an active community by providing detailed contribution guidelines and support channels.

## Contact
For questions, feature requests, or reporting issues, reach out to:
- **Email:** abhinaireddy2244@example.com
- **GitHub Issues:** [GitHub Issues Page](https://github.com/username/Xray-core/issues)



## Installation

- Linux Script
  - [XTLS/Xray-install](https://github.com/XTLS/Xray-install) (**Official**)
  - [tempest](https://github.com/team-cloudchaser/tempest) (supports [`systemd`](https://systemd.io) and [OpenRC](https://github.com/OpenRC/openrc); Linux-only)
- Docker
  - [ghcr.io/xtls/xray-core](https://ghcr.io/xtls/xray-core) (**Official**)
  - [teddysun/xray](https://hub.docker.com/r/teddysun/xray)
- Web Panel
  - [3X-UI](https://github.com/MHSanaei/3x-ui), [X-UI](https://github.com/alireza0/x-ui), [Xray-UI](https://github.com/qist/xray-ui)
  - [Hiddify](https://github.com/hiddify/hiddify-config)
  - [Marzban](https://github.com/Gozargah/Marzban)
  - [Libertea](https://github.com/VZiChoushaDui/Libertea)
- One Click
  - [Xray-REALITY](https://github.com/zxcvos/Xray-script), [xray-reality](https://github.com/sajjaddg/xray-reality), [reality-ezpz](https://github.com/aleskxyz/reality-ezpz)
  - [Xray_bash_onekey](https://github.com/hello-yunshu/Xray_bash_onekey), [XTool](https://github.com/LordPenguin666/XTool)
  - [v2ray-agent](https://github.com/mack-a/v2ray-agent), [Xray_onekey](https://github.com/wulabing/Xray_onekey), [ProxySU](https://github.com/proxysu/ProxySU)
- Magisk
  - [Xray4Magisk](https://github.com/Asterisk4Magisk/Xray4Magisk)
  - [Xray_For_Magisk](https://github.com/E7KMbb/Xray_For_Magisk)
- Homebrew
  - `brew install xray`

## Usage

- Example
  - [VLESS-XTLS-uTLS-REALITY](https://github.com/XTLS/REALITY#readme)
  - [VLESS-TCP-XTLS-Vision](https://github.com/XTLS/Xray-examples/tree/main/VLESS-TCP-XTLS-Vision)
  - [All-in-One-fallbacks-Nginx](https://github.com/XTLS/Xray-examples/tree/main/All-in-One-fallbacks-Nginx)
- Xray-examples
  - [XTLS/Xray-examples](https://github.com/XTLS/Xray-examples)
  - [chika0801/Xray-examples](https://github.com/chika0801/Xray-examples)
  - [lxhao61/integrated-examples](https://github.com/lxhao61/integrated-examples)
- Tutorial
  - [XTLS Vision](https://github.com/chika0801/Xray-install)
  - [REALITY (English)](https://cscot.pages.dev/2023/03/02/Xray-REALITY-tutorial/)
  - [XTLS-Iran-Reality (English)](https://github.com/SasukeFreestyle/XTLS-Iran-Reality)
  - [Xray REALITY with 'steal oneself' (English)](https://computerscot.github.io/vless-xtls-utls-reality-steal-oneself.html)
  - [Xray with WireGuard inbound (English)](https://g800.pages.dev/wireguard)

## GUI Clients

- OpenWrt
  - [PassWall](https://github.com/xiaorouji/openwrt-passwall), [PassWall 2](https://github.com/xiaorouji/openwrt-passwall2)
  - [ShadowSocksR Plus+](https://github.com/fw876/helloworld)
  - [luci-app-xray](https://github.com/yichya/luci-app-xray) ([openwrt-xray](https://github.com/yichya/openwrt-xray))
- Windows
  - [v2rayN](https://github.com/2dust/v2rayN)
  - [Furious](https://github.com/LorenEteval/Furious)
  - [Invisible Man - Xray](https://github.com/InvisibleManVPN/InvisibleMan-XRayClient)
- Android
  - [v2rayNG](https://github.com/2dust/v2rayNG)
  - [X-flutter](https://github.com/XTLS/X-flutter)
- iOS & macOS arm64
  - [FoXray](https://apps.apple.com/app/foxray/id6448898396)
  - [Streisand](https://apps.apple.com/app/streisand/id6450534064)
- macOS arm64 & x64
  - [V2rayU](https://github.com/yanue/V2rayU)
  - [V2RayXS](https://github.com/tzmax/V2RayXS)
  - [Furious](https://github.com/LorenEteval/Furious)
  - [FoXray](https://apps.apple.com/app/foxray/id6448898396)
- Linux
  - [v2rayA](https://github.com/v2rayA/v2rayA)
  - [Furious](https://github.com/LorenEteval/Furious)

## Others that support VLESS, XTLS, REALITY, XUDP, PLUX...

- iOS & macOS arm64
  - [Shadowrocket](https://apps.apple.com/app/shadowrocket/id932747118)
- Xray Tools
  - [xray-knife](https://github.com/lilendian0x00/xray-knife)
- Xray Wrapper
  - [XTLS/libXray](https://github.com/XTLS/libXray)
  - [xtlsapi](https://github.com/hiddify/xtlsapi)
  - [AndroidLibXrayLite](https://github.com/2dust/AndroidLibXrayLite)
  - [Xray-core-python](https://github.com/LorenEteval/Xray-core-python)
  - [xray-api](https://github.com/XVGuardian/xray-api)
- [XrayR](https://github.com/XrayR-project/XrayR)
  - [XrayR-release](https://github.com/XrayR-project/XrayR-release)
  - [XrayR-V2Board](https://github.com/missuo/XrayR-V2Board)
- [Clash.Meta](https://github.com/MetaCubeX/Clash.Meta)
  - [clashN](https://github.com/2dust/clashN)
  - [Clash Meta for Android](https://github.com/MetaCubeX/ClashMetaForAndroid)
- [sing-box](https://github.com/SagerNet/sing-box)

## Contributing

[Code of Conduct](https://github.com/XTLS/Xray-core/blob/main/CODE_OF_CONDUCT.md)

## Credits

- [Xray-core v1.0.0](https://github.com/XTLS/Xray-core/releases/tag/v1.0.0) was forked from [v2fly-core 9a03cc5](https://github.com/v2fly/v2ray-core/commit/9a03cc5c98d04cc28320fcee26dbc236b3291256), and we have made & accumulated a huge number of enhancements over time, check [the release notes for each version](https://github.com/XTLS/Xray-core/releases).
- For third-party projects used in [Xray-core](https://github.com/XTLS/Xray-core), check your local or [the latest go.mod](https://github.com/XTLS/Xray-core/blob/main/go.mod).

## Compilation

### Windows (PowerShell)

```powershell
$env:CGO_ENABLED=0
go build -o xray.exe -trimpath -ldflags "-s -w -buildid=" ./main
```

### Linux / macOS

```bash
CGO_ENABLED=0 go build -o xray -trimpath -ldflags "-s -w -buildid=" ./main
```

### Reproducible Releases

```bash



make
```

## Stargazers over time

[![Stargazers over time](https://starchart.cc/XTLS/Xray-core.svg)](https://starchart.cc/XTLS/Xray-core)
