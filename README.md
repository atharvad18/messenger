Overview:

made a very simple version of Gmail using C++.used a doubly-linked list to store user accounts and two singly linked lists per user to store sent and received messages. a user can create an account, log in and send a message to another existing user. Logged-in users can log out and create another account, log in to another existing account, change the password of an existing account or delete an existing account. 
User while logged-in in can view a list of received, sent, deleted, and starred messages and can also search for messages sent to/ received from a user. For every sent/ received message user can read it, delete it, or mark it as important (star)/unstar. To display a list of messages sent to/ received from a user or a list of starred messages in the sent/ received singly linked list, used sequential search. 
Each time the message which satisfies the required condition is found its reference gets stored in a vector. This vector helps read, delete, or star/unstar a message in the list. References of deleted messages have been stored in a vector (trash). Users can either permanently delete a message from the trash or simply view it.

Limitations:

1.	A user can send only a string (text) to another user at a time.
2.	A user can't log in to multiple accounts at the same time.
3.	Deleted messages in the trash cannot be retrieved.
