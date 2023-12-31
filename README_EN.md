<p align="center">
<a href="https://dq.amgl.work" target="_blank" rel="noopener noreferrer">
        <img width="100" src="https://i2.100024.xyz/2023/08/06/shxvov.webp" alt="Logo" />
</a>
</p>

<div align="center">

# FluffyDNS

[![GitHub release (latest by date)](https://img.shields.io/github/v/release/FluffyOx/FluffyDNS)](https://github.com/FluffyOx/FluffyDNS/releases) ![GitHub stars](https://img.shields.io/github/stars/FluffyOx/FluffyDNS?style=flat) ![LICENSE](https://badgen.net/static/license/MIT/green)

![JS.svg](https://img1.imgtp.com/2023/08/06/Qcj9M4eW.svg) ![HTML.svg](https://img1.imgtp.com/2023/08/06/wRHfPWlm.svg) ![CSS.svg](https://img1.imgtp.com/2023/08/06/RRZiXeWU.svg)
</div>

</div>

<p align="center">
<a href="https://dq.amgl.work">Website</a> &nbsp;&bull;&nbsp;
<a href="#introduction">Introduction</a> &nbsp;&bull;&nbsp;
<a href="#usage">Usage</a> &nbsp;&bull;&nbsp;
<a href="#features">Features</a> &nbsp;&bull;&nbsp;
<a href="#packaging">Packaging</a> &nbsp;&bull;&nbsp;
<a href="#deployment">Deployment</a>
</p>

<div align="center">
  <a href="https://github.com/FluffyOx/FluffyDNS/README.md">中文</a>
</div>

## Introduction

FluffyDNS is a DNS record query tool. It supports both a web interface and the curl command line.

## Usage

You can visit the [website](https://dq.amgl.work) to use FluffyDNS or download the [Releases](https://github.com/FluffyOx/FluffyDNS/releases) (Chinese users can also download from [123 Cloud Drive](https://www.123pan.com/s/xSj8Vv-UDxU3.html)).

- Using on the website:

1. Enter the domain name in the search box.
2. Press Enter, click "查询," or wait for automatic recognition.

- Using in the terminal (cmd and Linux terminal):

1. Execute `curl dq.amgl.work` to see usage instructions.
2. Execute `curl dq.amgl.work/y.qq.com` to see query results.

- Using in PowerShell (Win11 terminal, vscode terminal):

1. Execute `(curl dq.amgl.work).Content` to see usage instructions.
2. Execute `(curl dq.amgl.work/y.qq.com).Content` to see query results.

![Input to Search](https://img1.imgtp.com/2023/08/08/TxNqywc2.gif)

![cmd Demo](https://img1.imgtp.com/2023/08/08/7OlcZrZo.gif)

## Features

1. Developed using native HTML, JS, and CSS.
2. Recognizes over 9000 domain suffixes, supporting a wide range of domain queries.
3. Supports user interaction using the curl command line.

## Packaging
Refer to the [Tauri official documentation](https://tauri.app).

## Deployment
**Using BT.cn (Baota)**

### Step 1: Create a Website

BT.cn Homepage -> Websites -> Add Website -> Enter your domain name (leave other options unchanged) -> Click Submit

![external.png](https://img1.imgtp.com/2023/08/08/UdW6LiGx.png)

### Step 2: Deploy the Code

Copy the source code to the website's root directory

![external.png](https://img1.imgtp.com/2023/08/08/mRXaRqn0.png)

### Step 3: Add Nginx Rewrite Rules

Copy nginx.conf -> BT.cn Homepage -> Website List -> Click on the website -> Rewrites -> Paste the configuration

![img](https://img1.imgtp.com/2023/08/08/bqmJLeYH.png)

![img](https://img1.imgtp.com/2023/08/08/7EzflxLi.png)

## License

This project is licensed under the [MIT License](https://github.com/FluffyOx/FluffyDNS/blob/main/LICENSE).
