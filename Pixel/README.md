# Pixel Skin
This repository contains a collection of Rainmeter skins for monitoring system statistics, including CPU usage, RAM usage, and network activity.

## Structure
The repository is organized into several directories, each containing a .ini configuration file for a Rainmeter skin:

- [Clock](Clock/README.md): Contains skins for displaying the time.
- [Cpu](Cpu/README.md): Contains a skin for monitoring CPU usage.
- [Network](Network/README.md): Contains a skin for monitoring network activity.
- [Ram](Ram/README.md): Contains a skin for monitoring RAM usage.

## Usage
To use these skins, you'll need to have Rainmeter installed on your system. Once Rainmeter is installed, you can load each skin by right-clicking the Rainmeter system tray icon, selecting "Manage skins", and navigating to the .ini file for the skin you want to load.

## Fonts
The skins in this repository use the VCR OSD Mono font, which is included in the @Resources/Fonts/ directory.

<!--## Detailed Explanation of .ini Files
### Cpu/Cpu.ini
This file configures a Rainmeter skin that displays the current CPU usage. It uses the Measure=CPU directive to measure CPU usage and displays it with the MeterUsedPercent meter. The text, font, color, and position of the meter are configured in the MeterUsedPercent section.

### Network/Network.ini
This file configures a Rainmeter skin that displays network activity, including upload and download speeds. It uses the Measure=NetIn and Measure=NetOut directives to measure network activity. The upload speed is displayed with the MeterUploadValue meter and the download speed is displayed with the MeterDownloadValue meter. The text, font, color, and position of the meters are configured in the MeterUploadValue and MeterDownloadValue sections.

### Ram/Ram.ini
This file configures a Rainmeter skin that displays the current physical memory usage. It uses the Measure=PhysicalMemory directive to measure memory usage and displays it with the MeterUsedPercent meter. The text, font, color, and position of the meter are configured in the MeterUsedPercent section.

### Clock/At Bottom.ini
This file configures a Rainmeter skin that displays the current time at the bottom of your screen. It likely contains settings for the font, size, and position of the clock. The Measure=Time directive is used to get the current time, and a meter is used to display this time on the screen. The format of the time (12-hour or 24-hour), the font, color, and position of the meter are configured in this file.

### Clock/Multi Clocks.ini
This file configures a Rainmeter skin that displays multiple clocks, likely for different time zones. It probably contains settings for each individual clock, including the time zone, font, size, and position. Each clock uses the Measure=Time directive with a different TimeZone setting to get the current time in different time zones. Each time is displayed with a separate meter, and the format of the time (12-hour or 24-hour), the font, color, and position of each meter are configured in this file.
-->