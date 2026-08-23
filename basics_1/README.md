# Basics #1

## Description
This project covers basic networking concepts, focusing on configuring DNS host resolution locally using the `/etc/hosts` file on an Ubuntu system.

## Tasks

| File | Description |
| --- | --- |
| `0-change_your_home_IP` | Bash script that configures `/etc/hosts` so that `localhost` resolves to `127.0.0.2` and `facebook.com` resolves to `8.8.8.8`. |

## Requirements
* Allowed editors: `vi`, `vim`, `emacs`
* All files will be interpreted on Ubuntu 20.04 LTS
* All files should end with a new line
* The first line of all files should be exactly `#!/usr/bin/env bash`
* A `README.md` file, at the root of the folder of the project, is mandatory
* All files must be executable (`chmod +x`)

## Usage
To execute the script, run:

```bash
chmod +x 0-change_your_home_IP
sudo ./0-change_your_home_IP
