## Inspiration
Since this hackathon's theme is API, I choosed to make something that uses maximum of the sponsor APIs, and came up with an idea to make a smart door lock system using SAWO login.
why only using SAWO in virtual authentication and why can't we use it for our door authentication! 
Thats where i got the idea.!
## What it does
Firstly there will be a qr code which anybody can scan through their smart phone and open the door lock using OTP only if the admin had stored their ids in the cloudant DB else a alert notification will be sent to the admin's phone number with the id that is used for unauthorised login.
The admin can add or delete ids according to their choice from the admin app.
Also I had used AGOA to make a 1 to 1 video calling system with our door camera to talk with someone standing outside the door.
This can be implemented using the raspberry pi but due the time shortage I had shown using mobile phones only.
## How we built it

I had built the project in a low code environment (NODE-RED) for handling the backend and used IBM cloud's cloudant DB for storing the user Ids.
I had built and run the AGORA website using codesandbox.
The hardware part is built using the bolt wifi module connected with the relay module.

## Challenges we ran into
The main challenges I ran into are as follow:-
1. It was really hard to store and delete data in the cloudant db in a user-friendly in the UI.
2. the raspberry pi was not triggering it's camera when AGORA website is visited.
3. Sometime the SAWO login form does not appear in the node-red template.
4.Sometime twilio failed to send SMS notification to the registered mobile.

## Accomplishments that we're proud of
I loved what I had gained and built using the Sponsors API though I failed to implement the SYMBL.AI but still tried to gain at-least what I had though in this short span of time. 

## What we learned
1. Using of SAWO in the node red
2. How to use AGORA API
3.How SYMBL.AI works

