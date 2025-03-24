# ByData BOT
ByData BOT

- Register Here : [ByData](https://bydata.app/?refCode=C2DCNBG1)

## Features

  - Auto Get Account Information
  - Auto Run With [Monosans](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/all.txt) Proxy - Choose 1
  - Auto Run With Private Proxy - Choose 2
  - Auto Run Without Proxy - Choose 3
  - Auto Complete Available Tasks
  - Multi Accounts

## Requiremnets

- Make sure you have Python3.9 or higher installed and pip.

## Instalation

1. **Clone The Repositories:**
   ```bash
   git clone https://github.com/herisukses/by-data.git
   ```
   ```bash
   cd by-data
   ```

2. **Install Requirements:**
   ```bash
   pip install -r requirements.txt
   ```

## Configuration

- **accounts.txt:** You will find the file `accounts.txt` inside the project directory. Make sure `accounts.txt` contains data that matches the format expected by the script. Here are examples of file formats:
  ```bash
    your_evm_address_1
    your_evm_address_2
  ```
- **proxy.txt:** You will find the `proxy.txt` file in the project directory. Make sure `proxy.txt` contains data that matches the format expected by the script. Here are examples of file formats:
  ```bash
    ip:port # Default Protcol HTTP.
    protocol://ip:port
    protocol://user:pass@ip:port
  ```

## Run

```bash
python bot.py
