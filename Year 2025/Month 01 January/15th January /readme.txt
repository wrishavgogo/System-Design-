This that i learnt on 15th Jan 2025 related to system Design . 

I watched first video of Arpit Bhiyani on foundational course 



Imp Learnings : 

Epoch Seconds :- It is basically the number of seconds that have elapsed from the date 1st Jan 1970. 
Mostly Int ( 4B) is used to represent it . But as soon as we hit the year 2032 , we are going to run out of storage . 
And that's why most the the databases have thought this through and done some implementation accordingly . 

Here Arpit said that what if there was a way you could use 6 bytes to represent the entire spectrum of DateTime , 


ToDo : Recommended to read the paper on "How MySql stores dateTime" 
It covers from BCE to 20,000 years , Probably human Race is gone by then . 


ToDo: Go Through the implementation of Connection Pooling to understand how it works . 
