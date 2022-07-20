# Ufonet--The-Funniest-DDOS

Create your own botnet and enjoy it

For fans of botnets, I have developed this room where we will download our own zombie army botnet and attack a virtual machine on our own network.

Here you have the link to Try Hack Me: https://tryhackme.com/
And the link to my Blockchain room: https://tryhackme.com/jr/blockchainvkkgjrphsh

![ds](https://user-images.githubusercontent.com/109109176/180066396-21c22049-01a0-4771-97b2-36ac23ed9ba9.jpeg)


INSTRUCTIONS:

IMPORTANT!! : You can do this room with the "Try Hack Me AttackBox" machine, only if you are a subscriber. If you are using a free account you have to use your own linux virtual machine.



Download the hacking tool

The first thing we have to do, is start the machine "Bouncer Store", attached in this task.

To download the tool, we must connect to the machine via ftp.

Open your linux attack machine and run a terminal. Copy paste the following commands in the terminal:



ftp ip;

(ip= ip of "Bouncer Store")

Introduce the user:

bouncer

Enter the password:

cyberbouncer

Download the simulator with the command:

get ufonet-master.zip

We can exit from ftp session with:

Ctl + D

![1](https://user-images.githubusercontent.com/109109176/180069773-e744aa5c-e4bc-4bb6-9df9-6bc504d57665.PNG)


Now we are in possession of the tool the next step is to install it in our linux attack machine:

The file is in zip format...

Unzip the tool: 

unzip ufonet-master.zip;

Move to the tool directory:

cd ufonet-master;

Install the tool and run its gui:


sudo python3 setup.py build && sudo python3 setup.py install && sudo apt install python3-scapy; 
sudo python3 ufonet --gui;

![uf](https://user-images.githubusercontent.com/109109176/180067852-93b8753c-7c2f-4584-adc0-26ee81cb72fc.jpeg)

After the last command, the browser will automatically open with the ufonet page.


*If that doesn't happen, terminate the machine to reset it and start over from the beginning.
In the event that you are using your own attack machine and you cannot access the ufonet website, I leave you this link that could help you:
https://www.youtube.com/watch?v=F3cilMQAwzQ&ab_channel=MohammadKaisarHamid


REMEMBER!! This looks like a game but it's not. This is UFONET a powerfull hacking tool. Do not use it for criminal purposes.

![2](https://user-images.githubusercontent.com/109109176/180070577-cf485318-522a-4aa0-9d66-758145294bd1.PNG)


UFONet - is a tool designed to launch DDoS attacks against a target, using Open Redirect vectors on third party web applications, like botnet.

DDoS attacks are designed to overwhelm a bottleneck within the software or hardware on a blockchain node.  The primary ways to defend against them are to ensure that nodes have adequate storage, processing power, and network bandwidth and to build failsafes into the code.

In this case, to not do anything illegal, we are going to attack a virtual machine within our own network.
We can attack the "Bouncer Store" (the virtual machine attached in the task), now that we have downloaded everything we need from it, we don't mind knocking it out.


In the ufonet page click on: "Start a mothership"

Use the interactive menu to go to "Wormhole" > "Botnet"

Now to create a botnet we need to get the bots on board our mothership. We could create it ourselves, looking for bots on our own, but that would take time, luckily the "Ufonet" community can provide us with a complete crew.
In the "Download Botnet" section, leave the ip that comes by default and click on "TAKE IT!"
Scroll down the page, and you can see the process like in the terminal.
When the process finish, reload the page (ctrl+r)...

CONGRATULATIONS!! Now you have your own army, use it with caution.

![3](https://user-images.githubusercontent.com/109109176/180070997-a6671a70-af24-4fce-8c3e-d8de8d657315.PNG)



Question #1:

In the Botnet menu, we can see what types of bots make up our botnet.

Which one of this types of bot is not related with "Ufonet"? (Answer "a" or "b" or "c")

a) Droids

b) Aliens

c) Robots

Answer #1:

c

![4](https://user-images.githubusercontent.com/109109176/180071556-44643481-dfc9-4957-a649-aa648d043b24.PNG)

Question #2:

Which are the predominant bots in our botnet?

Answer #2:

zombies

Question #3:

Ufonet allows us to scan our target with some options:

Use the interactive menu to go to "Wormhole" > "Explore"
Click on: "ship abduction"
Another window opens to us...
In "Set your target", write:     "http://ip"       (ip = ip target machine, "Bouncer Store")
Click on: "Research!"...
Examine the result down below


Question #4:

What Apache version has our target?

Answer #4:

apache/2.4.29

![6](https://user-images.githubusercontent.com/109109176/180072993-78c3b14f-12bd-4a65-908e-c3941e5e6576.PNG)


Question #5:

What is our target OS?

Answer #5:

ubuntu


Question #6:

Come back to "ufonet" web page.
Click on: "ship inspect"
Another window opens to us...

Here we are going to scan our target to find any large file that will facilitate our DDOS attack, if we request a large file, our victim will need to invest more resources and we will get it to crash before:
In "Set page to crowl", write "http://ip" (ip = ip target machine)
Click on "inspect!"...
Examine the result down below.


Question #7:

What is the longest file of our target?

http://target_ip/

Answer #7:

icons/ubuntu-logo.png

![11](https://user-images.githubusercontent.com/109109176/180074221-30c5bab7-93cb-4da1-80f5-ebc1fcab7ea3.PNG)


Question #8:

Remember this file for later, because we'll use it for our attack.


Question #9:

Come back to "Ufonet" web page.
Use the interactive menu, go to "explore" > "attack"

In "Set your target" write: "http://ip" (ip = ip target machine)     
In  "Set place to attack", write here the path to the largest file you found earlier.
In "Number of rounds" write: 10
Check option: "Generate map!"

Click on ATTACK!!

![1](https://user-images.githubusercontent.com/109109176/180074958-199c0750-4e6c-451f-af3d-f02da3493c95.PNG)

Question #10:

We have programmed "Ufonet" to carry out 10 attack rounds, as soon as the first round is carried out (1 minut aprox.), a box with statistics about the attack will appear at the bottom of the map, with the sections of "Conn", "Zombies", "Hits" and ...

Answer #10:

fails

![2](https://user-images.githubusercontent.com/109109176/180075397-ce618807-eb1d-43ff-9132-43331f436331.PNG)

Question #11:

CONGRATULATIONS!! You have made your first attack with Ufonet, and your army is still standing, awaiting your orders.

This has been a very simple demonstration, "Ufonet" is capable of doing many more things, but it has helped us to create a first contact with this tool.

To be able to attack outside our own network we would need to do some additional configurations such as set up "Tor network" in our attack machine.

You can also use Ufonet exclusively using commands from your terminal...

If you want to go deeper into Ufonet you can try putting these commands in the terminal from the ufonet folder:

./ufonet --help

./ufonet --examples

Or go to this Ufonet description web, in this link:

https://ufonet.03c8.net/


Answer #12:

KING OF THE ZOMBIES
