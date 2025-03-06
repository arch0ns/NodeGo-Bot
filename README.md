# NodeGo BOT

![image](https://github.com/user-attachments/assets/16a30dad-3a74-4857-b6db-1e0be6b4df7a)

- NodeGo BOT
- Register Here : [NodeGo](https://app.nodego.ai/r/NODEAB845E5C93B8)
- Use Code : NODEAB845E5C93B8

## Features

  - Auto Get Account Information
  - Auto Run With [Monosans](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/all.txt) Proxy - Choose 1
  - Auto Run With Private Proxy - Choose 2
  - Auto Run Without Proxy - Choose 3
  - Auto Claim Daily Check-In
  - Auto Complete Available Tasks
  - Auto Added Node & Send Ping Every 2 Minutes
  - Supports Multi Nodes For Each Account
  - Multi Accounts With Threads

Note: 
1. Only running 1 node if run without proxy.
2. If there is an error. Please first find out the meaning of the error with the status code displayed. if the error is with status code 500 or higher. The problem is on the project server. Some of you opened an issue and complained that there was an error with status code 502 and told me to update the bot. Hey sir, are you kidding me?

# How to Get NodeGO Access Token

1. Open your browser and login to the NodeGo dashboard.
2. Press `F12` to open the **Inspect Elements** panel.
3. Go to the **Console** tab and paste the following code:

   ```javascript
   localStorage.getItem('accessToken')
   ```

4. You will receive your user ID, which looks like this: `"eyjxxxx........"`
5. If you can't paste, type allow pasting and press Enter, then paste the line above.

## Requiremnets

- Make sure you have Python3.9 or higher installed and pip.

## Installation

1. **Clone The Repositories:**
   ```bash
   git clone https://github.com/arch0ns/NodeGo-Bot
   ```
   ```bash
   cd NodeGo
   ```

2. **Install Requirements:**
   ```bash
   pip3 install -r requirements.txt
   ```

## Configuration
```bash
nano tokens.txt
```
- Make sure `tokens.txt` contains data that matches the format expected by the script. Here are examples of file formats:
  ```bash
    eyjxxxx1
    eyjxxxx2
  ```
## For Proxy
```bash
nano proxy.txt
```
- Make sure `proxy.txt` contains data that matches the format expected by the script. Here are examples of file formats:
  ```bash
    ip:port # Default Protcol HTTP.
    protocol://ip:port
    protocol://user:pass@ip:port
  ```

## Run

```bash
python bot.py #or python3 bot.py
```

### 


Thank you for visiting this repository, don't forget to contribute in the form of follows and stars.
If you have questions, find an issue, or have suggestions for improvement, feel free to contact me or open an *issue* in this GitHub repository.
