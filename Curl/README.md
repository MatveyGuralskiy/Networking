# 🌐 Curl
Curl it's a smart Web-browser

### ⬇️ Installation
**Linux :**

sudo apt-get install curl

**Windows :**

1. Go to Website --> curl.se/download

2. Copy all files inside directory bin

3. Run Terminal with administrator permissions go to *System32*

4. copy (YOUR PATH)\bin\ *

### 🎯 Commands
curl --version = To check curl version

curl google.com = Show you HTML page of google.com

curl -v google.com = A lot of information about site google.com (-v = verbose)

curl -s google.com/stone.png --output NAME.png = To download files from the Internet (-s = silent)

curl https://api.weather.net = To work with api (weather for example)

curl -s https://api.weather.net | jq = More beauty work with api

curl -s https://api.weather.net -d  '{'username': 'Bob', 'password': '12345' }' | jq = To send JSON message to the Website (-d = data)

curl -s https://api.weather.net -d @FILE.json | jq = Send JSON file to the Website

curl -s https://api.weather.net -d @FILE.json | jq  .owner -r = Search about owner and remove
