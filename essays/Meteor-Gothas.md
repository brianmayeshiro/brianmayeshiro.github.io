---
layout: essay
type: essay
title: "Meteor Gotchas"
date: 2017-03-09
labels:
  - Software Engineering
  - Meteor
---

## Extracting Header About Meteor Tool…
Like my header, extracting the meteor tool the first time when using it was painstakingly long. Okay, I admit that was lame attempt at a “play on words”, but the most irritating step in using Meteor for the ‘Digits’ exercise in my Software Engineering class. It didn’t matter whether I had a decent internet connection or not, the time it took to download and extract the meteor tool was at least 10 minutes. 
There were some ways to reduce the time, however. One way to reduce it is to turn off Windows Defender Real Time Protection (RTP). RTP may be the cause of increasing the download and extract time because the software checks to see if the meteor tool contains any viruses/malware (since it is a large download). Turning off RTP sped up the download and extraction process as I attempted it the second time.

## Meteor and Windows 10 is a Nightmare!
The biggest problem I had with meteor while running it on my Windows 10 machine is the throw error I kept receiving while trying to run my meteor application using the mongo database. 
'''
C:\Users\brian\AppData\Local\.meteor\packages\meteor-tool\1.4.1_1\mt-os.windows.x86_32\dev_bundle\lib\node_modules\meteor-promise\promise_server.js:190
      throw error;
      ^
'''
Despite Googling every possible solution to the problem, I had to resort to uninstalling all my software (meteor, nodejs/npm, intelliJ), deleting all leftover appdata from the software, restarting my computer, reinstalling the software, and then restarting my computer again to get things up and running. I am still unable to figure out the exact problem to this issue, but reinstalling and restarting everything seemed to solve it.
