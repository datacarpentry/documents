
#Workshop proposal for 10th International Digital Curation Conference

[IDCC](http://www.dcc.ac.uk/events/idcc15)

proposal should include e.g. draft programme, speakers, technical requirements, audience and maximum numbers. - [See more](http://www.dcc.ac.uk/events/idcc15/submissions#sthash.4beJ8q4k.dpuf) 

Thoughts:
Do you think we should do the workshop for people who do digitial curation or for people who will be making use of digitized datasets?   
It seems like people attending will mainly be the ones who are **creating and maintaining these data collections**.   
What is it that they need/want to know from a Data Carpentry offering?   
I would imagine they are beyond the novice phase in working with data.   
Or could it be workshop to show what kinds of workshops they can offer to the people the work with - our more regular DC audience?

We had been thinking about developing a **'how to use APIs'** primarily using **ROpenSci tools** lesson. Would something like that be appropriate for this conference? I don't really know much about APIs, so my writing about this below could be off. 

The latter could be something like

*It has been established that the growing availability of well curated and publicly-available digitized datasets can be tranformative for research progress in many domains. However, many researchers still lack the skills to most effectively use these datasets from both a data handling and analysis perspective. Data must be accessed from data repositories and large scale analyses conducted with command line tools or programming languages such as Python or R. Data Carpentry workshops aim to teach these concepts, skills and tools for working more effectively with data to researchers, particularly those with little prior computational experience. In this workshop, we will conduct an introductory hands-on lesson for using R and ROpenSci packages to access data from the web through APIs. We will follow this with a discussion of the lesson and the effectiveness of the materials and approach and finally conduct collaborative lesson development/improvement through github. This workshop is for anyone interested in learning more about using APIs and R for accessing and working with data or if they are interested in learning more about Data Carpentry workshops to see if they would be useful for researchers they work with in their communities.*


###Draft agenda:
(full-day workshop)



Introduction  

Morning (2 hours)

Using R and ROpenSci to access and analyze data from the web through APIs

This module is an introductory hands-on R lesson on getting and using data from the web using ROpenSci packages. We will work in R to access data from an online data repository and conduct preliminary analyses. Focus will also be on how this workflow enables reproducible research. 

Coffee break

Then, I'd get them into small groups to discuss their experiences and give them a set of very open questions guiding their discussions (eg. 1. How did this style of lesson feel? 2. What was good? 3. What was missing? 4. What would I improve? 4. How? 5. Would that be beneficial for what I do at work? if so how?)

Ideally - each group comes up with "3 improvements we would like to make to the lesson" (these can be anything - sequence, fixing typos, adding more explanation etc. etc.)

Lunch break

Then the groups report back and discuss. This discussion may alter their "Improvements we would like to make"

Coffee break

We do "collaborative lesson development/improvement" via GitHub. Difficult to assess if the groups will have at least one person git-savvy. BUT why don't we leverage GitHub infrastructure - I create branches in MY FORK of our repo with lessons (branches "group 1" "group2" "group3") and get them to work in their respective branches in the GitHub via browser (basically, they edit files in the browser and once they click save, GH behind the scenes creates a Pull Request - this is the power of GH; anyone can fix your code but you get to decide if you merge it or not).

I merge selected changes that they made.
Basically the outcome isn't getting some incredible improvement, isn't making them git experts. It's showing them the power of collaborative lesson development.

Short discussion at the end.
Finish.

So the outcomes of our workshop:
- learning what it means to get datasets using API; the power of using API
- learning what DC teaching style is; the mode of deliver of our lessons
- learning about collaborative lesson development; how powerful it can be

I know it looks very ambitions. But I think the key is to have a very very small and simple example with API and I will thing through very very well how to guide them through collab. lesson development using GH website interface. We should remember that the outcome should be "Wow - I saw this cool thing at DCC Conference. I may not be able to replicate it just now. But that was so powerful. I am now aware this exist"

Even if the collaborative lesson development will be a bit messy. That;s not the point. They will see that SWC and DC give them power to improve the lessons they just went through. 
