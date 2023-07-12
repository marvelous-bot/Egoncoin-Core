This package is developed for Egon Chain and must be used strictly for only Egon Mainnet. You are required to follow the instruction given as it is. If a problem occurs please raise an issue here<br />
This directory contains node source code, node setup, and startup script. <br /><br />

In order to become a validator in Egon Mainnet you first need to set up and start the node:<br /><br />
+-------------------------- NODE SETUP ------------------------------------+<br />

Follow the instructions given here<br />
https://docs.google.com/document/d/1l-tcXkaM9hbKzKwgyy6ejOuuMtdKp-De8IrZfMHRVCM/edit?usp=sharing<br />

+------------------------------------------------------------------------------------+<br /><br /><br />


+---------------------- NODE START --------------------------------------+<br />
To start node enter this command in terminal  <b>./node-start.sh --validator</b><br />

 To attach running tmux session: <b>tmux attach -t node1</b> <br />
 To detach running tmux session: press CTRL + b, then release both keys and press d<br />
 To exit the node once inside tmux session: type "exit" and enter<br />
+----------------------------------------------------------------------------------+<br /><br />

 Please note: Note setup is only required for the first time. i.e., when you have a new server with no prior running egon nodes. Once the setup.sh is done on a given server, you don't need to interact with ./node-setup.sh file. You can safely interact with ./node-start.sh script even after 1st time.<br /><br />

 Future updates will be pushed to the EgonChain GitHub repository. Stay tuned for advanced feature updates.<br /><br />
