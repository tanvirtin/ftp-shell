# FTP-Shell
A simple FTP program in Python, enabling communication between two computers-- ideal for transferring files between virtual machines.

Installation instruction:

You will need to have Python 3 installed in your computer for this program two run. You need to run the server script first called vm_server.py and then the client script called vm_client.py. They need to be on seperate computers or on different hosts for this script to run. Both the server and the client script takes in command line arguments which are the user and password.

Run the server script by typing: python server.py -u username -p password

After that run the client script by typing: python client.py -u username -p password

The username and password needs to match for both the server and client. After the client is connected you need to provide the server's ip address for the connection to complete.

This program was created mostly from laziness. For university work I mostly had to use the virtual machine which had linux installed on it, I couldn't just drag and drop files from my windows machine to my linux in virtual box. I had to email stuff to myself and then retrieve it on my virtual machine. The client side python script runs like a shell which keeps prompting for commands and even has commands like a normal terminal shell would do, they are ofcourse very limited.

There is alot to be improved in this program, in the future I will be writing more code to maybe add more commands to give it full access to the machine running the server script.
