# Shopify Design Internship Challenge

### The problem: Tell us about the problem you’re solving. How did you learn more about the problem space? Were there constraints and what were they? 

I did the shopify's Design Project 

so the constraints were

-  The machine has a single touchscreen. There isn’t any kind of pinch and zoom, hard press or advanced touchscreen functionality supported.

- The parking meters can accept credit card payments, but are not otherwise connected to the internet and are not bluetooth enabled.

### Your process: What was your approach in solving the problem? If this was a group effort, what role did you play? Did your project go through multiple iterations? Tell us about it! 

I wanted to create a system that was

- Easy to notice 
- Easy to use
- From start to finish in 5 tap (<10 seconds per person)
- sofisticated but is as cheap as possible to manufacture

### Your solution: Describe your solution. How would you validate that your solution solves the problem? 

------------

#### Hardware:

Display:

- obeytec LCD 12.1 ~ 54$
- Embedded system running ubuntu~15$
- Square Reader for contactless ~ 59$
- housing and setup ~ 60$

Total cost would be 180$ per unit.

local server+ network ~ 400\$ every 500 $m^2$



--------------

#### Solution:

Actors perspective

1. The actor gets of out his/her car and proceed to the terminal.

2. They would then proceed to enter their licence plate number on the system, the system will verify if the format is correct or not

   (it does not check if the licence plate is valid or wrong, nor does it have a login feature since all that takes too long).

3. Then they would select if they want to pay their fine or buy a permit

   (if buying a permit) 

   1. they will select from a list of option on how long should their tickiet last
   2. they will simply touch their credit card on the blue dot behind which the RFID payment system is located.
      1. On successful payment they will be greeted with a recipe page and the session will end.
      2. the system will then update the local server that this user has a permit for this much time.

   (if paying a fine) 

   1. the user will be shown the amount of fine to be paid (entered by the local server).

   2. the user will enter the fine code placed on their car by the parking attendant.

      (this is done to protect user Privacy, only the person will the recipt will be able to see if the user has a fine or not)

   3. they will simply touch their credit card on the blue dot behind which the RFID payment system is located.

      1. on successful payment they will be greeted with a recipe page and the session will end.
      2. the system will then update the local server that this user has a paid the fine.

   

   Parking attendants prespective

   1. If they notice a car who's licence place does not appear in the registery(updated by the local server)

   2. They will then Issue a fine against the car's licence number and print out a recipt and place it on the car witha 6 digit licence code.

   ---------------

   

   

### Reflection: What was challenging about solving this problem? What did you learn while solving this problem? Is there anything in this project you’d like to get feedback on? If you had more time, or were doing this a second time, what would you do differently? 



I would like to get some feeback on my design style i don't want it too look too bland but i feel i go overboard with the design language.

If i had more time i would add error handling a more flushed out payment system and also design the local server architecture and Parking attendant's app view.

I also feel the authenication method is a bit off, but i can't think of a better way asking the user to tedious sign up.. enter a password... etc on a 12 inch touch screen makes for some terribe UX not to mention its going to be su