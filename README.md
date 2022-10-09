# timmekeCC_SAICO_LINUX
Minecraft Console Client with linux script

How to use

Clone the repo with: git clone https://github.com/TimBilliet/timmekeCC_SAICO_LINUX

Install mono
https://www.mono-project.com/download/stable/#download-lin

Install screen with: sudo apt install screen

Edit start.sh and put your alts in

Give execute permisions with: chmod +x start.sh

Run start.sh with: ./start.sh

Use screen -r to see all the active alts
Use screen -r altX to resume that alt's screen session
Use kill (PID) to close an alt's screen session or press CTRL + C when in an active screen session

It's possible to run this on a rpi 3
