# Not auto-joining Wi-Fi networks

Auto join is a feature that allows your phone to automatically join any Wi-Fi network it already has the credentials 
for, or open Wi-Fi networks, without having to ask you to do anything. This can be a time saver at home and at work. 
But, it carries two major issues:

* It can cause your phone to randomly leave a stronger Wi-Fi network for a weaker Wi-Fi network that has come into 
range. Both Android and iOS developers have tried to stop their operating systems from doing this, but have only had 
limited success. When your phone switches over to a weaker Wi-Fi, it terminates your first Internet connection, 
interrupting your Internet usage. Once on the weaker network, performance goes down.
* When you automatically join open public Wi-Fi networks you put your data and privacy at risk. You do not know 
that the network is secure. You could be joining a clever network clone (rogue wireless access point) that is really 
a MitM attack trying to steal your passwords and usernames to sensitive accounts. 

On an Android device, often carriers install their own Wi-Fi monitoring apps. Each app works differently. Try:

* Go to Settings -> Wi-Fi. You will see a list of Wi-Fi network profiles. 
* Click the ones you want to (not) auto join with and toggle the switch to auto join.

Alternatively, you can try and navigate to your device’s Connections Optimizer, if it has one:

* Go to Settings -> More -> Mobile Networks. 
* In the Connections Optimizer you can disable/enable auto joining.