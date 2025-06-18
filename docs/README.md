<div align="center">
  <img src="./images/image-poster.png" width="60%">
</div>

**Welcome to the IEEE SSCS Chipathon 2025!** <br>
This guide provides key information for participants. During the Chipathon, you will choose one of the tracks shown below.

<div align="center">
  <img src="./images/image-tracks.png" width="70%">
</div>

We encourage you to follow the steps below:

1. General tool setup
2. Track-specific setup
    - MOSbius
    - Digital Building Blocks
    - Analog Automation

For the 2025 Chipathon, we will use the open-source GlobalFoundries 180nm (gf180) process design kit (PDK). You can refer to the links below for more information:

- [Github Repository](https://github.com/google/gf180mcu-pdk)
- [Documentation](https://gf180mcu-pdk.readthedocs.io/en/latest/)
- [YouTube Videos](https://www.youtube.com/playlist?list=PLZuGFJzpFksCU7yKn2P_xRTOktVBDWAJf) (credit: Amro Tork)

<br><br>

# 1. General Tool Setup

The following guidelines help you set up the tools using the [IIC-OSIC-TOOLS](https://github.com/iic-jku/iic-osic-tools) Docker image developed by Harald Pretl's team.

Please choose one of the following tutorial links to set up the tools, which best fits your environment. Experienced users may configure the tools using their own preferred approach.

The **MOSbius** and **Analog Automation** tracks require slight variations of the general tool setup. Once you are familiar with the general procedure, adapting it for each track should be straightforward.

- **[Windows/MacOS only]** <br>
👉 Kwantae Kim's [Blog Post](https://kwantaekim.github.io/2024/05/25/OSE-Docker/) <br>
🌱 Beginner-friendly
- **[Any OS]** <br>
👉 Saptarshi Ghosh's [Google Doc](https://docs.google.com/document/d/13r-pB7vhYnCb-n46CAAlqXrKSj99bQtmEeyoayEV3Ak/edit?tab=t.0) <br>
👉 Boris Murmann's [Github](https://github.com/bmurmann/EE628/tree/main/3_Tools)

The image below provides a quick overview of the open-source toolchain (credit: Harald Pretl).

<div align="center">
  <img src="./images/image-toolchain.png" width="100%">
</div>

<br><br>

# 2. Track-Specific Setup

## 2.1. MOSbius

- [`resources/MOSbius`](https://github.com/KwantaeKim/sscs-chipathon-2025/tree/main/resources/MOSbius) <br>
👉 Gateway redirecting to `mosbiuschip` repository (below), developed by Peter Kinget and Juan Sebastian Moya's team.
- [mosbiuschip](https://github.com/mosbiuschip/chipathon2025) <br>
👉 Github repository for general info and resources of `mosbius` track. The `mosbius`-specific setup guide can be also found.

## 2.2. Digital Building Blocks

- [`resources/Digital_Building_Blocks`](https://github.com/KwantaeKim/sscs-chipathon-2025/tree/main/resources/Digital_Building_Blocks) <br>
👉 General information and resources of Digital Building Blocks track.

## 2.3. Analog Automation

- [`resources/AnalogAutomation_gLayout`](https://github.com/KwantaeKim/sscs-chipathon-2025/tree/main/resources/Analog_Automation_gLayout) <br>
👉 General information and resources of `Glayout` developed by Mehdi Saligane's team, a Python-powered analog layout automation tool.
- [Google Doc (Glayout)](https://docs.google.com/document/d/13r-pB7vhYnCb-n46CAAlqXrKSj99bQtmEeyoayEV3Ak/edit?tab=t.dy4a5w3lme18) <br>
👉 `Glayout`-specific setup guide
- [Google Doc (Klive)](https://docs.google.com/document/d/13r-pB7vhYnCb-n46CAAlqXrKSj99bQtmEeyoayEV3Ak/edit?tab=t.gc3heib3ge74) <br>
👉 Setup guide required to run `Glayout` interactively
