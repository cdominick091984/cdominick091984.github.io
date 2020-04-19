---
layout: post
title:      "My CLI Project Journey"
date:       2020-04-19 12:47:00 +0000
permalink:  my_cli_project_journey
---


When I decided I was going to learn to code I knew it was going to push me out of my comfort zone. This project did that as soon as I started it. So, at this point for me it was like a puzzle. I had learned all the pieces, but it was time to put them together. At first, I was really overwhelmed not knowing where to start. On top of that I was looking at a screen of people who had been kidnapped. The project I chose was to scrape the FBI's missing person site and give my user all the names of the missing people. At that point, the user could chose a number prior to the person’s name and get more info. 

Once I had a conversation with my cohort lead things started to go much more smoothly for me. I was able to scrape the site and get to the info I wanted. I scraped the person’s name and URL, added them into a hash and pushed that hash into an array. Slowly the pieces started to come together. I then had this array of 40 people and didn’t quite know what my next step was. More research lead me to take the array and create individual person objects, so now each person had a name and a URL. Things were coming along nicely. I built my Cli interface and suddenly I was feeling pretty confident until I got to the most important part of my project, getting additional info on each person. I thought I could just iterate over each person and pull their details, but this was not the case. 

It turned out that the site I was scraping had JavaScript implemented in it, but I wasn’t aware of it. My cohort lead showed me a technique to reveal the actual URL I should use. This URL had "query=page1" where the other URL did not. With this change I could now get the details I wanted, but then I ran into another problem. The details were not the same for each person. What I mean by that is the way the site displayed the details was different for each person. For example, everyone started with a date of birth but after that, each person’s details changed. Trying to iterate over that information was proving to be the most difficult part of the entire project for me.  In the end, a friend of mine suggested something that worked and instead of iterating I just took everything all at once from each person. After that everything else went pretty smooth. For my first project I must say it was stressful, but a great experience and I learned a lot. Nothing is impossible as long as you don’t give up.

