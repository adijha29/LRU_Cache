# LRU_Cache

NAME OF THE PROJECT : FrequentlyContacted

ALGORITHM USED : LRU (Least Recently Used) Cache

CACHE :  
-> Stores data to speed up future requests  
-> May be a previous computaion or redundant copy of the data  
        
LRU CACHE :   
-> Most recent element is brought to the top  
-> Element that exceeds the limit is dropped out  

DATA STRUCTURES :   
-> Doubly Linked List  
-> Binary Search Tree  

TIME COMPLEXITY :   
-> Searching element in BST - O(log n)  
-> Inserting new element in linked list - O(1)  
-> Deleting last element in linked list - O(1)  

SPACE COMPLEXITY : O(n)  

APPLICATIONS :   
-> WhatsApp Chat history  
-> Recently used apps on smartphone  
-> Notification Panel  
