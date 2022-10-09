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


![image](https://user-images.githubusercontent.com/47719114/194757376-7d2650d6-4837-4047-ac13-ec1c9bf606be.png)

Use screen -r to see all the active alts
Use screen -r alt1 to resume alt1's screen session
Use kill 4599 to close an alt1's screen session or press CTRL + C when in the active screen session

It's possible to run this on a rpi 3
