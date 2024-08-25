# **The WALDO NET**

The WALDO NET uses the undirected method for a weekly JS8 Net. The goal of this NET is to have fun, check-in, and find WALDO. The benefits, to name a few, are getting on the air, exercising your gear, and increasing your JS8 skills that could help in emergency communication scenarios.

The first round of the NET is used to send a basic Check-In with some current information and a short comment to all participants.

The basic Check-In round uses a pre-agreed **from** message to encode the following information:

**Status:** Green, Yellow, Red  
G=Green  
Y=Yellow  
R=Red

**Availability for a QSO after the NET:**  Yes, No  
Y=Yes  
N=No

**Basic Weather information for the day:**   
++Conditions++

1= Sunny  
2= Partly Cloudy  
3= Cloudy  
4= Light Rain  
5= Moderate Rain  
6= Heavy Rain  
7= Snow  
8= Sleet or Ice  
9= Thunderstorms  
A= Severe weather   
Temperature ranges  
1= Below 0F  
2= 0F \- 32F  
3= 32F \- 55F  
4= 55F \- 75F  
5= 75F \- 85F  
6= 85F \- 95F  
7= Above 95F  
**Comment (very short) with free text:** ON BATTERY, PORTABLE, NEW ANT, etc.   
NOTE: If on your first round dice rolls the sum of your three rolls is greater than 13 you are WALDO and need to put the word WALDO in your comment.

By using this âformâ (F\!104) we can keep the message short. The forms can be published on the Internet so as to not make any attempt to obscure or encrypt the messages. This format is still human readable and could also be used with other add-on tools or scripts for JS8call like JS8Spotter, but is not required. All you need is the JS8call application.

Below is a message sent to the group @NET as an inbox message.

**@NET MSG F\!104 GY17 HOT NIGHT**

This message says you are using form F\!104, you have an overall Green status (meaning all is well), you are available for a QSO after the NET, and you are having/had a sunny day with temperatures over 95 degrees F with a comment of HOT NIGHT.

If you are WALDO it would be the same except for the comment and would just include WALDO.

**@NET MSG F\!104 GY17 WALDO**

In the last round or the conclusion round, everyone will simply send a message indicating how many stations they copied (a number), and the call sign of WALDO. If there were more than one WALDO, just report the first one you copied. It is possible to have more than one WALDO and no WALDO at all, if you copied no WALDO, then just send NWF (No WALDO Found).

Below is a message sent to the group @NET as an inbox message.

**@NET MSG 3 NWF**

This message says you copied 3 other stations during the NET and No WALDO Found.

If WALDO was found, then the message would be the following.

**@NET MSG 3 K7ACF**

This message says you copied 3 other stations during the NET and the first WALDO found was K7ACF.

## **Full Example**

A 4 station NET with call-signs N6BB, K7ACF, W8ASK, and A5PIN.

**Step 1** \- Each station needs to roll dice to get their time slots numbers and find out if they are WALDO (if the sum of the first 3 numbers rolled is greater than 13). Below are the results of the rolls. N6BB rolled a 1,3,4 for the first round and 2,3,6 for the second. Remember, you need 3 unique non-repeating numbers for each round, if you roll a 1 then another 1, roll again until it is other than 1, etc. The sum of N6BBâs first round roll is 8 so he is not WALDO. Notice that K7ACF rolled a 4,5,6 and the sum is 15, so he is WALDO.

N6BB 		1,3,4 & 2,3,6 \- Total the numbers of the first numbers 1+3+4=8  
K7ACF	4,5,6 & 2,4,5 \- Total the numbers of the first numbers 4+5+6=15  
W8ASK	1,4,5 & 2,3,6 \- Total the numbers of the first numbers 1+4+5=10  
A5PIN		1,2,6 & 1,3,5 \- Total the numbers of the first numbers 1+2+6=9

**Step 2** \- Each station needs to use the Frequency Offset table to set a rough offset.

Referring to the offset table and the dice rolls, here are the slots and offsets for the stations to use in round 1\.

N6BB will use slots 1,3,4 offset 1000-1450 Hz  
K7ACF  is in slots 4,5,6 offset 1000-1450 Hz  
W8ASK is in slots 1,4,5  offset 1500-1950 Hz  
A5PIN is in slots 1,2,6 offset 1500-1950 Hz

N6BB will transmit the check-in message at the top of the hour in slot 1\. The message will be sent twice, once at normal speed, and once at slow speed. Since it will be sent as an inbox message, allow at least one frame time after the message to receive any ACK messages. This is not required but provides some feedback. No ACK doesnât mean the other station didnât get the message, it just means you didnât get the ACK, this is why we transmit multiple times. These messages should use most, if not all of the 5 minute time slot. 

This will continue for all 6 time slots, stations taking turns transmitting and receiving.  
