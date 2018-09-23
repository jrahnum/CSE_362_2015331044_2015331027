                                     <<<<<<<<<CSE-362>>>>>>>>>>>>

                 <<<<<<<<<<<< A Multiple Chat Server System With Socket Programming >>>>>>>>>>>>>>>


					 Developed by:

		      1. Mahfuj Ahmed
		      Reg. no: 2015331027
		      2. Sheikh Junayed Ahmed
		      Reg. no: 2015331044
									      
				         Developed in:
					1.Java
                                        2.java Socket programming


--------Base Features---------- 

1. When the server system is loaded, it will initiate the required communication setup so that a client system can join it.

2.There are two server systems,Multi user server and single user server.Multi user allows a group chat and single user allows a single chat.

3. When the client system is loaded, an option to provide the IP address/port number of the chat server and the name of joining user.

 
4. A proper GUI with a read-only text box to show the exchanged messages, a text entry field to write a new message and a Send button.

 
5. Each time Send is pressed with a new message in a client system, all of the users connected to the server will immediately see the new message. 

5. A list in the GUI to show the joined user(s) with the server. 


6. An option, shown as a menu item, to save the exchanged messages. 





--------Overall Working Process---------


1. Open both the project Server_Socket and Client_Socket in Netbeans IDE.

2. Run Server_frame.java or Single_server_frame. A server window will pop up. 

3. Press 'START' button to start the server. The server will ready for joining new client.

4. Run Client_frame.java. A client window will pop up. Enter the IP address and port number of the server (The default is localhost and 2222) 
   and the name of joining user and press 'CONNECT'. A 'username'.txt file will be created in the users pc to save exchanged messages.Single user system allows only a user.

5. Both the server window and the client window will have read-only text area to show the exchanged messages and the client window will have 
   a text entry field to write a new message and a 'SEND' button.

6. Each time 'SEND' button is pressed with a message in a client window, 
   all of the users connected to the server will immediately see the new message.

7. Both the server window and the client window will have a text area to show all the currently joined user(s) with the server by pressing "SHOW USERS" button.

8. The client window will have a button 'SAVE' to save messages. If you press it then the program will save all the messages in the client window 
    in 'username'.txt file.

9. Both the server window and the client window will have a 'CLEAR' button to clear the text area.


10. Press 'DISCONNECT' to disconnect from the server0






