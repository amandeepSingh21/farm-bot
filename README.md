# farm-bot
1. Intall selenium-webdriver gem
2. Intall chrome webdriver for your browser version https://chromedriver.chromium.org/downloads
3. Set the path of the web driver in the script using driverPath variable
4. Run this command to run chrome in headless mode:
sudo /Applications/Google\ Chrome.app/Contents/MacOS/Google\ Chrome -headless -remote-debugging-port=8280 --user-agent="Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/60.0.3112.50 Safari/537.36" www.google.com
5. Set the port number in the script to match the port number of above command
6. Finally run the ruby script
7. To login, open chrome and login remotely to the headless chrome using localhost:portnumber
