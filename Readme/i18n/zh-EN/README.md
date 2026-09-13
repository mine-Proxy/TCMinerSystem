<div align="center">

<img src="../../../image/_logo.svg" alt="TCMinerSystem" width="520">

<h3>An End-to-End Operations Solution for Miners, Mining Farms, and Pool Nodes</h3>

<p>Pool Relay · Hashrate Management · Self-Hosted Pool Nodes · Encrypted and Compressed Transport · Web Operations Console</p>

<p>
  <a href="https://github.com/mine-Proxy/TCMinerSystem/tree/main/Readme/i18n/zh-EN">English</a>
  ·
  <a href="https://github.com/mine-Proxy/TCMinerSystem">简体中文</a>
  ·
  <a href="https://github.com/mine-Proxy/TCMinerSystem/tree/main/Readme/i18n/zh-RU">Русский язык</a>
</p>

<p>
  <a href="https://github.com/mine-Proxy/TCMinerSystem/releases">
    <img src="https://img.shields.io/github/v/tag/mine-Proxy/TCMinerSystem?label=version&color=0EA5E9" alt="Version">
  </a>
  <a href="../../../LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-22C55E" alt="MIT License">
  </a>
  <a href="https://t.me/TcstMinerSystem">
    <img src="https://img.shields.io/badge/Telegram-TCMinerSystem-2CA5E0?logo=telegram&logoColor=white" alt="TCMinerSystem Telegram">
  </a>
  <a href="https://github.com/mine-Proxy/TCMinerSystem">
    <img src="https://img.shields.io/github/stars/mine-Proxy/TCMinerSystem?style=flat&color=F59E0B" alt="GitHub Stars">
  </a>
</p>

<p>
  <a href="https://tcminersystem.gitbook.io/tcminersystem/chuan-tong-kuang-chi-dai-li/dai-li-chuan-tong-kuang-chi">Pool Proxy</a>
  ·
  <a href="https://tcminersystem.gitbook.io/tcminersystem/zi-jian-kuang-chi-jie-dian/cheng-wei-kuang-chi-jie-dian">Self-Hosted Pool</a>
  ·
  <a href="https://github.com/MinerProxyPro/TMS">TMS Secure Transport</a>
  ·
  <a href="https://tcminersystem.gitbook.io/tcminersystem">Documentation</a>
  ·
  <a href="https://tcminersystem.gitbook.io/tcminersystem/guan-yu/lian-xi-wo-men">Contact and Customization</a>
  ·
  <a href="https://tcminersystem.gitbook.io/tcminersystem/guan-yu/fu-wu-xie-yi">Service Agreement</a>
</p>

<img src="../../../image/review.gif" alt="TCMinerSystem dashboard preview">

</div>

## What is TCMinerSystem?

TCMinerSystem is a mining pool proxy and operations management system designed for miners, mining farms, and pool nodes. It can connect devices to traditional mining pools, centrally manage forwarding ports, and deploy self-hosted pool nodes when required.

The companion local security client [TMS](https://github.com/MinerProxyPro/TMS) provides encrypted and compressed transport to reduce public network connections and bandwidth usage while improving link security. Before getting started, please read the [Service Agreement](https://tcminersystem.gitbook.io/tcminersystem/guan-yu/fu-wu-xie-yi).

## Core Capabilities

| Capability | Description |
| --- | --- |
| Traditional pool proxy | Centrally manage miner connections, forwarding ports, and destination pools to simplify large-scale device access and routine operations. |
| Self-hosted pool nodes | Deploy your own pool nodes for mining farms, node operators, and private hashrate operations. |
| Hashrate and fee management | Configure hashrate statistics, allocation rules, and custom fees while monitoring operational status. |
| TMS secure transport | Encrypt and compress traffic through the companion client to reduce bandwidth usage and limit link exposure. |
| Multi-platform deployment | Use the provided Linux and Windows executables and the Linux installation utility for fast deployment and updates. |
| Web operations console | View devices, ports, hashrate, logs, versions, and system health from a browser. |

## Quick Start

> [!IMPORTANT]
> The default administrator username is `qzpm19kkx`, and the default password is `xloqslz913`. Change the username, password, and Web port immediately after your first login, and restrict access to the management port with a firewall.

### Linux

Ubuntu is recommended. Run the following command in a Bash terminal to open the installation menu:

```sh
bash <(curl -s -L https://github.com/mine-Proxy/TCMinerSystem/raw/main/install.sh)
```

If GitHub access is slow in your region, try the alternative installation endpoint:

```sh
bash <(curl -s -L https://cdn.tcminersystem.com/mine-proxy/TCMinerSystem/raw/main/install.sh)
```

After the utility starts, follow the menu prompts to install, update, start, stop, and configure the service and its ports.

<p align="center">
  <img src="../../../image/install.gif" alt="TCMinerSystem Linux installation menu" width="560">
</p>

### Windows

1. Open the repository's [windows directory](https://github.com/mine-Proxy/TCMinerSystem/tree/main/windows).
2. Select the latest `tcstminersystem-*.exe` file. This is the executable filename used by TCMinerSystem.
3. Open the file page and click `View raw` to download it.
4. Run the downloaded program and follow the terminal prompt to open the management console in your browser.
5. Change the default username, password, and Web port immediately after your first login.

## Documentation

| Scenario | Resource |
| --- | --- |
| Connect to a traditional pool | [Traditional Pool Proxy Guide](https://tcminersystem.gitbook.io/tcminersystem/chuan-tong-kuang-chi-dai-li/dai-li-chuan-tong-kuang-chi) |
| Deploy a pool node | [Self-Hosted Pool Node Guide](https://tcminersystem.gitbook.io/tcminersystem/zi-jian-kuang-chi-jie-dian/cheng-wei-kuang-chi-jie-dian) |
| Use encrypted and compressed transport | [TMS Project](https://github.com/MinerProxyPro/TMS) |
| Read the complete instructions | [TCMinerSystem Documentation](https://tcminersystem.gitbook.io/tcminersystem) |
| Download a new version | [Releases](https://github.com/mine-Proxy/TCMinerSystem/releases) |
| Contact the team or request customization | [Contact Us](https://tcminersystem.gitbook.io/tcminersystem/guan-yu/lian-xi-wo-men) |
| Read the terms | [Service Agreement](https://tcminersystem.gitbook.io/tcminersystem/guan-yu/fu-wu-xie-yi) |

## Supported Algorithms

TCMinerSystem's supported algorithms and currencies may change between releases. The following are common examples documented by the project. Refer to the current management console and official documentation for the authoritative support list.

<details>
<summary>Show common algorithms and currencies</summary>

| Algorithm | Common currencies |
| --- | --- |
| SHA256 | BTC, BCH, and others |
| ETHASH | ETC, ETHW, ETHF, ETC+ZIL, ETHW+ZIL, ETHF+ZIL, and others |
| SCRYPT | LTC and others |
| KHEAVYHASH | KASPA and others |

</details>

## Transparent Access on Authorized Networks

If you operate a mining farm or have explicit administrative authorization for its routers and devices, contact the project team to assess a DNS-based or transparent proxy deployment. This can reduce the need to reconfigure miners individually.

> [!WARNING]
> Transparent access is permitted only on networks where the device owner has provided clear, informed authorization. Do not intercept, forward, or redirect devices, hashrate, or network traffic that you do not own or administer with permission.

## Community and Support

Use the following channels to receive release updates, discuss technical questions, or request customization:

<p>
  <a href="https://t.me/TcstMinerSystem">
    <img src="https://img.shields.io/badge/Telegram-TCMinerSystem-2CA5E0?logo=telegram&logoColor=white" alt="TCMinerSystem Telegram">
  </a>
  <a href="https://qm.qq.com/cgi-bin/qm/qr?k=O22gwKOK0v3JqVtOjwWzmK6H3Qd0h2Ty&amp;jump_from=webapi&amp;authKey=0FwwAgxRzswAFCgpiEKafzcgOgj8Uzm8DDzriyx7omj5MqPCQOAS/qQw3tXX6hrq">
    <img src="https://img.shields.io/badge/QQ-Community-12B7F5?logo=tencentqq&logoColor=white" alt="QQ Community">
  </a>
  <a href="https://github.com/mine-Proxy/TCMinerSystem/releases">
    <img src="https://img.shields.io/badge/Releases-Changelog-111827" alt="Releases">
  </a>
</p>

## Acknowledgements

We thank the following mining pools for the technical support they have provided within the relevant scope:

<table>
  <tr>
    <td align="center" width="160">
      <img src="../../../image/icon-logo-blue.png" alt="Technical supporter" width="100">
    </td>
    <td align="center" width="160">
      <img src="../../../image/poolin.svg" alt="Poolin" width="100">
    </td>
    <td align="center" width="160">
      <img src="../../../image/hd_logo.png" alt="Technical supporter" width="100">
    </td>
    <td align="center" width="160">
      <img src="../../../image/antpool.png" alt="AntPool" width="100">
    </td>
  </tr>
</table>

## Service Agreement

> [!CAUTION]
> TCMinerSystem is governed by the laws of Hong Kong. Countries and regions may impose different restrictions on cryptocurrency, miner management, and mining pool services. Confirm that your intended use is lawful where you operate before using the software.

<details>
<summary>Show compliance information</summary>

### Product Scope

- This product is an operations management tool for miners, mining farms, and pool nodes. It is not a VPN and does not provide a way to bypass network access restrictions.
- Every connected device must be configured by its owner or by an administrator with explicit authorization. The software must not be used to improperly obtain, control, or redirect another person's devices, data, or hashrate.

### User Eligibility

By using this service, you confirm that:

1. You are not a person or organization identified as participating in terrorism by the United Nations Security Council or another applicable authority.
2. You have not been restricted or prohibited from using this software by an applicable administrative, judicial, or law-enforcement authority.
3. You are not a resident of Cuba, Iran, North Korea, Syria, or another jurisdiction subject to applicable sanctions.
4. You are not a resident of a country or region whose laws or policies prohibit cryptocurrency-related activities.
5. Your use of the software and all of its features complies with the laws, regulations, and policies that apply where you operate.

### Responsibility

You are responsible for understanding and complying with applicable local laws. If your use of the service is unlawful because of local laws, policies, or other applicable rules, you bear the related risks and responsibilities. Downloading or running the software indicates that you have read and accepted the complete service agreement.

See the complete [TCMinerSystem Service Agreement](https://tcminersystem.gitbook.io/tcminersystem/guan-yu/fu-wu-xie-yi).

</details>

## License

This project is distributed under the [MIT License](../../../LICENSE).
