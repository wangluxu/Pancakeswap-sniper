# Pancakeswap-sniper
 Pancakeswap Sniper bot
Demo of a Pancakeswap sniping bot used to snipe during IDOs. With advanced options and a graphical user interface.
<H2>Please check the pdf guide I have added.</H2>


![image](https://user-images.githubusercontent.com/72505611/118034358-2db9f900-b36a-11eb-8152-1363f764af1c.png)



<H2>Prerequisites</H2>

- An ethereum/bsc address
- A Windows machine
- <i>Not sure whether needed anymore: Visual C++ build tools (www.visualstudio.microsoft.com/visual-cpp-build-tools/)</i>

<br> </br>
<H2>Getting started</H2>

0. Read prerequisites

1. Download the latest release or download "configfile.py" and "sniping_bot.exe" from the repository.


2. Open "configfile.py" (with notepad for instance) and add your ethereum address and personal key at the bottom of the file between the quotation marks(''). You can also define how many threads you want running at once (=how many instances of the bot at once). The latter option can not be changed within the GUI. Please note, that the bot will buy multiple times when more than 1 thread are used.

<pre>...
threads='1'
my_address = ''
my_pk = ''</pre>


3. Run "sniping_bot.exe"

- Make sure configfile.py and bot.exe are in the same folder.


5. Edit settings according to choice.


<br> </br>

<H2>Soon to be added</H2> 
1. Adding option to only buy if price is less than X$ when bot snipes.
<br></br>

2. Let the bot buy at max price impact if the initial BNB amount is too big for the liquidity provided.


<H2>Functions</H2>


<b>Token address</b>: Fill the token address of the token you want to trade (such as 0x0000000000000000000000000000000000000000)

<b>BNB to trade</b>: Amount of BNB you want to use in the sniping transaction

<b>Pcs version</b>: Which version of Pancakeswap you want to snipe on <b>(this setting can only be edited from the configfile.py)</b>

....




