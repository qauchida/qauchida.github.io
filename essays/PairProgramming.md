---
layout: essay
type: essay
title: Pair Programming
# All dates must be YYYY-MM-DD format!
date: 2020-05-29
labels:
  - Education
  - IntelliJ
---	

Due to the current circumstances of the world right now caused by covid-19, people have been forced to find new ways to work together while still maintaining physical distance.
Computer programmers are stereotyped to be reclusive and to avoid human contact but the reality is that in person collboration is essential when trying to create a group project. This summer, I am participating in a research team and we experimented with remote pair programming.

## Geting Started
I first started trying to set up [floobits](floobits.com) by following the instructions listed on their website. Installing the plugin was easy but I made the mistake of attempting to have both the web editor and intelliJ open at the same time. Then, I closed both and attempted to run Floobits on my intelliJ again. I got a message saying:  "the following remote file is different from your version:  static/.nojekyll."
I wasn't able to open that file in IntelliJ and decided to overwrite the remote version of static/.nojekyll.

I found that if you use the web editor, you can video chat at the same time, without having to open another program up. It doesn't look like you can do the same thing using the intelliJ plugin so if I wanted to video or voice chat, I would have to open up another program. 
Although the web editor has built in video chat capabilities, it doesn't have any of the convieneces of the intelliJ features I use the most like the vim emulator or the "shift shift" search shortcut. 


[![Floobits Status](https://floobits.com/qauchida/docusaurus2.svg)](https://floobits.com/qauchida/docusaurus2/redirect)

## Session 1: Up and Running

In this session, I worked with [Angeli Amascual](https://angeli-amascual.github.io/) from 12:00 to 12:30 on 05/29/2020. Before we jumped right into using it, we talked for a bit about how this was going to work. We used Zoom at the same time as floobits so we could screen share our locally rendered version of radgrad.github.io and talk through our code. First, I invited Angeli to my workspace and talked through what I was doing while showing her my code. Then, she invited me to her workspace and did the same. I had trouble connecting to her workspace through the IntelliJ plugin so I had to settle on using the web editor. After we ended our Zoom call, I was able to join her workspace and use the IntelliJ plugin. 

30 minutes felt super short. We used most of our time just trying to get the hang of using Floobits and we didn't try to make changes to our code during this session. 

## Session 2: Trying to Break It

In this session, our research group wanted to see what happens when all 4 of us try to work at the same time. Angeli, [Max Deyo](https://maxdeyo.github.io/), [Hanna Park](http://hannaparkuh.github.io/) and I all tried to work on the same thing on 05/30/2020 around 1:30pm. Since Angeli and I used Floobits the day before, we tried using it again with the whole group. We also held a zoom call where all 4 of us could talk and respond in real time, as well as share the rendered version of their markdown with their cursor so the others could follow. In this sesssion, I noticed that even if a contributor was not typing, I could see their cursor and when they typed, the entire line they were typing on was highlighted. This made it easy to keep track of the changes as they were happening, rather than just seeing the code appear on the screen as it was being typed. 



## Session 3:
In this session, Angeli, Max, Hannah and I tried to use [Code Together](https://www.codetogether.com/). It was similar to Floobits but I found I disliked the fact that only one person could type at a time. With Floobits, multiple contributors could make changes at the same time. The shorcuts were confusing but I think that may just be part of the learning curve. During this session, we also had a Zoom call going.


## Session 4:
I would like to do a 4th session but I would like to use it while coding in JavaScript. Markdown was kind of simple and I feel like it wasn't helpful to test it. I think it could be a good group exercise to have someone give us buggy code and then we could do a pair/group debug using Floobits and Zoom. 

## What Worked (and What Didn't)
Having some kind of video call going while using the IntelliJ plugins proved useful. We didn't have to have the video on all the time, but having a voice channel open was used to give instruction faster than typing it in a chat. 

Both Floobits and Code Together have web editors and I found that I could access the web editors on mobile devices. If our team is not near a computer but needs to make a quick change, they could potentially use their smartphones. However, I would use the plugin over the web editor even though there are extra steps to connecting to the workspaces. The web editor for Floobits does have video chat capabilities but the IntelliJ plugin does not, so that is why we had a zoom call going. 

