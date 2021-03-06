Sedati is a simple tool to make reading EDMC trade logs easier. 

![Screenshot](http://i.imgur.com/jpNz8Bo.png)

I've been scavenging all over the place trying out trade tools here and there. and I find them too hard and or too overkill to fit my needs. Some are just heavy . I've been fan of pen and papers but it's too tedious for me now., I want easier way to access my edmc .csv logs and figure out my own routes. So far ive been only opening them using notepad but it's very tiresome. I ended up creating this. Simple tool, very light, simple to use, no need mysql, no trade route advisor, just something that you can do with pen and paper and figure out the trade yourself (which I prefer be doing)


----
## It is not:
* Crowdsourced. All data used are local, you will need to use EDMC to grab the market data.
* Trade Route Planner. Sedati is meant to be pen and paper replacement, it only holds information, you still need to figure out your own profitable routes.

----
## Requirement
* Elite Dangerous Market Connector (Market data in CSV format files) [sample](http://i.imgur.com/di8nxww.png)
* .Net Framework 4.5


----
## How to Use:
* Run "Sedati.exe"
* On "EDMC .csv Folder" paste the direct path to folder where you save your market CSVs generated by EDMC. (Must be direct path. For example you saved it on your Documents folder, instead of entering "Documents\EDMC" you put "C:\Users\YOURUSERNAME\Documents\EDMC")
* Click "Load"
* Market data will be listed on the left side. Choose a station you wish to check. Press "Open"
* Fill the "Search" field to find specific station/system, then press "F"
* Use "Purge Older Data" button to delete old data (only newest will be kept for each station)


----
## Links:
* You can download the program here: [Sedati.zip](https://github.com/ellivr/Sedati/releases/download/v1.0/Sedati.zip) (Simply extract, no installation needed)
* Frontier Forums Thread [https://forums.frontier.co.uk/showthread.php/315902-Sedati-Simple-Elite-DAngerous-Trade-Info](https://forums.frontier.co.uk/showthread.php/315902-Sedati-Simple-Elite-DAngerous-Trade-Info)

You are free to copy/use/modify my code as you wish.
