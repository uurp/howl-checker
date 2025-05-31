
[![Hits](https://hits.sh/github.com/uurp/DiscordUsernameChecker.svg)](https://hits.sh/github.com/uurp/DiscordUsernameChecker)  
[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com)

# Discord Username Checker (Tokenless)

**Discord Username Checker** is a Python-based tool that checks the availability of Discord usernames using custom combinations and proxy support. It uses multi-threading for efficient performance without requiring a Discord token.

## Features

- Username availability check via Discord API  
- Multi-threaded for faster results  
- Proxy support to bypass rate limits  
- Live RPS (Requests Per Second) monitoring  
- Logs errors for troubleshooting  
- Compatible with Linux systems  

## Screenshot

![screenshot](https://media.discordapp.net/attachments/1242610410046230638/1243460374708092949/image.png?ex=66518e37&is=66503cb7&hm=b9d1877e771fe7785095f01ee077e6e994cac913da41e063c4144d5395af8c83&=&format=webp&quality=lossless)

## Getting Started

### Prerequisites

- Python 3.x  
- `requests` module  

### For Windows Users

1. Run `run.bat` to start the script.

### Manual Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/uurp/DiscordUsernameChecker.git
   cd DiscordUsernameChecker
   ```

2. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the script:

   ```bash
   python username_checker.py
   ```

## Usage

1. Add your proxies to the `proxies.txt` file.
2. (Optional) It can work without proxies, but will be significantly slower due to rate limits.
3. Adjust script parameters as needed (e.g., username length, thread count).
4. Run the script and monitor the results in real-time.

---

**Author:** Muha  
**GitHub:** [@uurp](https://github.com/uurp)
