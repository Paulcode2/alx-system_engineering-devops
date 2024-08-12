# Postmortem

### Issue Summary

- I once tried building a chat application.
- It took me about 1 month to build.
- The user experience was so poor and i just had to take it down.
- It was poor because i didn't implement the APIs well.

### Timeline

- The issue was dtected 2 days after launching
- I discovered it myself
- I tried changing the web RTC i used
- I employed 2 proffesionlas to test for me
- Me
- It was never resolved

### Root Cause

- The major bug was that the video call option wasn't working, and it was giving me a lot of concern cause i did everything right. In the end, i discovered it was because of the webRTC i used.
- I changed the webRTC i used to another. Though it didn't give the functions i needed, but it was still efficient.

### Resolution and recovery

- I used a new webRTC, so that corrected the issue. And testing was a very important aspect of what helped me solve the little bug.

### Corrective and Preventative Measures

- Next time, i'll make sure to read every doc before i use any API

