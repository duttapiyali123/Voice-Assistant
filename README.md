# AI Voice Agent Prototype - Riverwood Estate

This is a prototype of a smart, human-sounding AI voice assistant built for Riverwood Estate customers. 

## What This Project Does
[cite_start]Instead of sounding like a standard robot, this assistant is designed to have a natural conversation[cite: 14, 15]:
* [cite_start]**Says Hello:** It greets the customer and gives them a quick update on the construction progress at Sector 7 Kharkhauda[cite: 25, 26].
* [cite_start]**Asks a Question:** It asks if the customer would like to visit the site this weekend[cite: 27].
* [cite_start]**Listens and Thinks:** It takes the customer's typed answer, thinks about what they said, and gives a friendly, logical reply[cite: 17, 19, 28].

## The Tools I Used
* [cite_start]**OpenAI:** Acts as the "brain" to understand what the customer says and decide how to reply[cite: 33].
* [cite_start]**ElevenLabs:** Acts as the "voice" to read the reply out loud so it sounds like a real, warm human being[cite: 34].
* [cite_start]**Google Colab & Python:** The workspace where the code is tied together[cite: 37].

---

## Technical Note: How to Call 1,000 Customers Every Morning
[cite_start]If Riverwood needs to call 1,000 people at once, running this script on a single computer won't work because it would have to call them one by one[cite: 40, 44]. 

To do it efficiently, I would use cloud computing. [cite_start]Instead of one computer doing all the work, I would set up an automated morning trigger that spins up 1,000 "virtual operators" in the cloud (using serverless functions like AWS Lambda and voice APIs like Twilio or VAPI)[cite: 35]. Each virtual operator handles exactly one phone call. This way, all 1,000 customers get called at the exact same time in parallel, and the whole process is finished in just a few minutes.

**Estimated Cost to Make 1,000 Calls:**
* AI Brain (OpenAI): ~$0.60
* Human Voice (ElevenLabs): ~$12.00
* Phone Connection (Twilio/VAPI): ~$15.00
* [cite_start]**Total Estimate:** ~$27.60 [cite: 45]

*Built by Piyali Dutta, IIT Mandi.*
