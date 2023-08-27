BulletDroid
=======
[![CodeFactor](https://www.codefactor.io/repository/github/lunapy17/bulletdroid/badge)](https://www.codefactor.io/repository/github/lunapy17/bulletdroid)

![watermark (2)](https://github.com/LunaPy17/BulletDroid/assets/69711934/0d3e1350-5edf-4dd3-b6aa-b02eea41911d)


Inspired by OpenBullet, this repository offers a powerful webtesting toolkit tailored for Android devices. The application presents an attempt of a user-friendly GUI built with Kivy, powered by a Python backend. Designed for a mobile experience, this tool is designed to execute requests, being suitable for data scraping and pentesting using custom configs, multi-threading, and proxy support.

## Features

- **User-friendly Interface**: An intuitive GUI built with the Kivy framework.
- **Custom Configs**: Offers flexibility to customize the checking process with config files.
- **Multi-threading Support**: Enables faster processing.
- **Proxy Support**: Provides an added layer of security during account checks.

![image](https://github.com/LunaPy17/BulletDroid/assets/69711934/eedb332d-4c07-4f4d-9973-8ba39502c9b1)


## Config Blocks

* REQUEST - Handle HTTP requests based on provided parameters (Headers, Postdata, etc).
* FIND - Parse a substring between two delimiters in a variable.
* SAVE - Set a string variable.
* PRINT - Show at logs a Variable or String
* RESULT - Return the response at display.

## Requirements

* Python 3.x
* Kivy
* Retry_requests

## Installation

1. Clone the repository: git clone https://github.com/LunaPy17/BulletDroid
2. Install the required packages: pip install -r requirements.txt

## License

This project is licensed under the GNU General Public License v3.0 [License](https://github.com/LunaPy17/BulletDroid/blob/main/LICENSE). See the LICENSE file for details.
