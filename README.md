# **Undirected JS8 Radio NET**

The JS8Call application has the ability to decode multiple stations at the same time. By using the Inbox message function with a call group, we can send information to multiple stations simultaneously and place the message in their Inbox.

To remove the need of a Net Control Station (NCS) and to create an undirected NET, we establish a NET with a duration of say 60 minutes, and divide it into 2 parts (rounds), each with 6 time slots for a total of 12 (See Time offset Table below). Each time slot is 5 minutes long. Participants of the NET transmit on random time slots. These transmit time slots are determined by a random number generator (e.g. dice rolls) before the NET begins. The first 6 time slots are the check-in period and the last 6 slots are the conclusion round. 

Participants of the NET, will transmit 3 times within the first 6 time slots (round 1\) and another 3 times within the last 6 time slots (round 2). Thus transmitting half the time and receiving the other half. Dice can be used to get three random and unique (non-repeating) numbers for the first round of time slots, and three more for the final round. This random assignment of time slots is what removes the need for a NCS.

In addition to the time-slots, each participant uses a different frequency offset so all the stations are spread out within the passband to reduce collisions with other stations. The rough offset is determined by the last letter of your call sign (see Frequency Offset table below) and should be adjusted as needed within that range based on other stations. Participants should send/receive group SNR? requests, 5-10 minutes before the NET begins to get a feel for the other stations' offsets.

Automatic Packet Reporting System (APRS) uses the concept of a “net cycle time”. This is the time within
which a station should be able to hear (at least once) all stations
within range, to obtain a more or less complete picture of activity.
The net cycle time can vary, and we are using two 30 minute cycle times. The random transmit time slots will allow everyone to be heard at least once, of course this is dependant on the number of stations participating.
Using JS8's Normal transmit speed which has a 15 second frame time. If we keep the messages to 4 frames (1 minute) and consider that we have about 25 offset frequencies. That would give us 25 messages per minute maximum, for full saturation. If we only use a third of this capacity, this method should support small NETs of 8-10 stations. If more station capacity is needed, the cycle time would need to be increased (e.g. two rounds of 60 minutes instead of 30 minutes). By using semi-automatic operation with the use of scripts and leveraging the JS8Call API, the rounds could be extended to hours along with larger slot times creating a much larger net cycle time, this could accommodate 100's of stations. Even with the simplest method, if you can not participate in a NET, you still have the option of leaving your station in monitor mode, and receiving the traffic for review later.
  
This method can be adjusted for various kinds of NETs and this two round system is used in the [Waldo NET](./waldo_net.md).


| Time offset | Slot Number | Round |
| :---: | :---: | :---: |
| :00 | 1 | 1 |
| :05 | 2 |  |
| :10 | 3 |  |
| :15 | 4 |  |
| :20 | 5 |  |
| :25 | 6 |  |
| :30 | 1 | 2 |
| :35 | 2 |  |
| :40 | 3 |  |
| :45 | 4 |  |
| :50 | 5 |  |
| :55 | 6 |  |

| Frequency Offset | Ending Letter of Callsign |
| :---- | ----- |
| 1000-1450 Hz | A,B,C,D,E,F,G |
| 1500-1950 Hz | H,I,J,K,L,M,N,O |
| 2000-2450 Hz | P,Q,R,S,T,U,V,W,X,Y,Z |

Alternative 30 minute NET 

| Time offset | Time Slot | Round |
| :---- | :---- | :---- |
| **:00:00 to :02:30** | **1** | **1** |
| **:02:30 to :05:00** | **2** |  |
| **:05:00 to :07:30** | **3** |  |
| **:07:30 to :10:00** | **4** |  |
| **:10:00 to :12:30** | **5** |  |
| **:12:30 to :15:00** | **6** |  |
| **:15:00 to :17:30** | **1** | **2** |
| **:17:30 to :20:00** | **2** |  |
| **:20:00 to :22:30** | **3** |  |
| **:22:30 to :25:00** | **4** |  |
| **:25:00 to :27:30** | **5** |  |
| **:27:30 to :30:00** | **6** |  |
