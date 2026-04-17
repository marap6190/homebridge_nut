# 🔌 homebridge_nut - UPS alerts for HomeKit homes

[![Download homebridge_nut](https://img.shields.io/badge/Download%20homebridge_nut-5A9BD4?style=for-the-badge&logo=github&logoColor=white)](https://github.com/marap6190/homebridge_nut)

## 🧩 What this app does

homebridge_nut connects a UPS to Homebridge through NUT, short for Network UPS Tools. It helps you bring UPS status into HomeKit so you can check power, battery, and charging details from one place.

Use it if you want to:

- See UPS status in HomeKit
- Get battery and power updates in Siri
- Keep watch on a UPS from a Windows PC running Homebridge tools
- Link NUT data to your smart home setup

## 💻 What you need

Before you start, make sure you have:

- A Windows computer
- Homebridge set up and running
- A UPS that works with NUT
- Access to your router or local network
- A browser to open GitHub

For best results, keep the UPS and the Windows PC on the same network.

## 🚀 Download and set up

Visit this page to download and use the project files:

https://github.com/marap6190/homebridge_nut

Then follow these steps:

1. Open the link in your browser.
2. Check the repository files and read the main project files.
3. If the project includes release files or install files, download the one meant for your system.
4. Save the files to a folder that you can find later.
5. If the project uses Node.js or Homebridge plugins, place it in the Homebridge plugin folder or follow the project file layout.

If you use Homebridge on Windows, keep the folder simple, such as:

- `C:\Homebridge\plugins\homebridge_nut`
- or the folder used by your Homebridge install

## ⚙️ Install the plugin

Follow this setup flow on Windows:

1. Open the folder where Homebridge stores plugins.
2. Add the `homebridge_nut` files to that folder.
3. If the project uses package install files, run the install step from the project folder.
4. Restart Homebridge.
5. Open the Homebridge web page.
6. Check that the plugin appears in the list of installed plugins.

If the plugin does not show up at first, check the folder path and restart Homebridge again.

## 🔌 Connect your UPS

To use this plugin, your UPS must be available through NUT.

Typical setup steps:

1. Make sure NUT is running on the machine that talks to the UPS.
2. Confirm the UPS is seen by NUT.
3. Note the UPS name, host, and port.
4. Add those values in the Homebridge plugin settings.
5. Save the settings.
6. Restart Homebridge so the new UPS data loads.

Common values you may need:

- UPS name
- NUT host
- NUT port
- User name
- Password

Use the same details that your NUT setup expects.

## 📱 Use it in HomeKit

After setup, HomeKit can show UPS data as smart home items. You may see values such as:

- Battery level
- Input power
- Output status
- Load state
- Online or on battery

These values help you check UPS health from your iPhone, iPad, or Mac.

## 🛠️ Windows setup tips

If you run Homebridge on Windows, keep these points in mind:

- Use a fixed folder path
- Do not move plugin files after install
- Run Homebridge with the same user account each time
- Keep the UPS and PC on the same local network
- Check Windows firewall rules if Homebridge cannot reach NUT

If the UPS data does not appear, confirm that NUT is reachable from the Windows machine.

## 🧪 Basic checks

Use these checks if the plugin does not work right away:

1. Open Homebridge logs.
2. Look for NUT connection errors.
3. Check the UPS host and port.
4. Check the user name and password.
5. Make sure the UPS is on and connected.
6. Restart Homebridge after each change.

If you still do not see data, test the NUT service on its own before you try HomeKit again.

## 📁 Folder layout

A simple Windows folder setup can look like this:

- `C:\Homebridge\`
- `C:\Homebridge\plugins\`
- `C:\Homebridge\plugins\homebridge_nut\`

Keep the files together so Homebridge can load them without path issues.

## 🔒 Privacy and local use

This plugin is meant for local network use. Your UPS data stays inside your home network setup and flows through Homebridge and NUT.

That makes it a good fit for home labs, small offices, and rooms with one or more UPS units.

## 🧭 Common use cases

People use this kind of plugin for:

- A desktop PC with a UPS
- A NAS with backup power
- A Homebridge server that needs power status
- A home office with battery backup
- A small server rack at home

## 📚 Project info

Repository: `homebridge_nut`  
Description: `NUT (Network UPS Tools) Plugin for Homebridge, leveraging node-nut to integrate UPS monitoring into HomeKit and Siri.`  
Primary link: https://github.com/marap6190/homebridge_nut

## 🏁 Quick setup path

If you want the shortest path on Windows:

1. Open the GitHub link.
2. Download or copy the project files.
3. Put them in your Homebridge plugin folder.
4. Set your NUT host details.
5. Restart Homebridge.
6. Check HomeKit for UPS data