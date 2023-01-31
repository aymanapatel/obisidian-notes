
---
type: podcast
note-written: Done
subject: "Database"
date: 2021
---










![Cover|200](https://images.weserv.nl/?url=https%3A%2F%2Fssl-static.libsyn.com%2Fp%2Fassets%2Fd%2F7%2Fa%2F5%2Fd7a5a500931246e3%2FCoding_Stories.png&w=200&h=200)


## Episode metadata
- Episode title:: [[Story: The Untold Story of SQLite]]
- Show:: [[CoRecursive: Coding Stories]]
- Owner / Host:: [[Adam Gordon Bell - Software Developer]]
- Episode link:: [open in Snipd](https://share.snipd.com/episode/05843a8c-7714-4c41-b936-f44d763fd19d)
- Episode publish date:: 2021-07-02
<details>
<summary>Show notes</summary>
> On today's show, I'm talking to Richard Hipp about surviving becoming core infrastructure for the world. SQLite is everywhere. It's in your web browser, it's in your phone, it's probably in your car, and it's definitely in commercial planes. It's where your iMessages and WhatsApp messages are stored, and if you do a find on your computer for *.db, you'll be amazed at how many SQLite databases you find.  Today, Richard is going to share his story. It's the story of creating a small open source project and having it grow beyond your wildest ambitions. It's the story of following that success wherever it leads: From relationships with tech-giants to interesting testing procedures and more.<br/>>    Episode Page <br/>>    Subscribe To Podcast <br/>>    Newsletter
</details>

- Show notes link:: [open website](https://chtbl.com/track/7D91G/traffic.libsyn.com/corecursive/066-sqlite.mp3)
- Tags: #podcasts #snipd
- Export date:: 2023-01-31T02:25


## Snips


### [02:56] The Problem Is That You Can't Connect a Data Base Server


[🎧 Play snip - 1min️ (02:49 - 04:42)](https://share.snipd.com/snip/6ef02752-e845-40c0-8fa5-a3b93ad3692f)
<audio controls> <source src="https://chtbl.com/track/7D91G/traffic.libsyn.com/secure/corecursive/066-sqlite.mp3?dest-id=628353#t=02:49,04:42"> </audio>


### ✨ Key takeaways
1. The solution to a problem can be computationally complex, but the general description of the problem is incomplete.
2. For systems that are designed by humans, the polynomial time solution is usually possible.
3. To solve a problem quickly, furistics are often used to approximate the solution.
4. If a system is not working correctly, it can be blamed on the developers even if it is not their fault.


#### 📚 Transcript
<details>
<summary>Click to expand</summary>
<blockquote><b>Speaker 1</b><br/><br/>Richard was brought in because the solution to this problem was computationally complex, and richard was for solving hard problemsbut really, when you come right down to it, the types of systems that are designed by humans tend to be solvable in polynomial time. Is just that the general description of the problem where you have an arbitrary directed graft is impty complete. So they were trying to to write code that would solve this and the hand analyze it, and they didn't realize thisd and they were you know, we're not getting a solution just running forever and chewing up see pu cycles. What's going on? Well, you know, that's because it's mp completed. And so you have to use furistics that we'll find fast, approximate solutions, and and put lots of things in there too to verify that it's not stuck in a loop somehow. And really, for the way they design these ships, the huristics can find the exact solution of the obtimal solution pretty quickly in every case. But it's just, you can't write a simple, naive algarithm and expect it to finish quickly, because you will get stuck in an expeditial search, try every valve combination to see which one's going to give you the best solution. So i was leading a team that was working on the and informinx just wasn't really working really well. I mean, once it was working, it worked great. But sometimes the server would go down, and and then our application would run and that was, that was embarrassing. Dialogue box wold pop up, thend of that big double click on the thing, and a dialogue box would pop up that says, can't connect a data base server. And wasn't our fault. We didn't have any control oer, mister vernel, what do you do if you can't connect the observer? And so we got, we got the blame all the same because we were painting the dialogue boxy.</blockquote>
</details>



---


### [33:17] How to Control Your Own Destiny and Not Depend on Third Parties


[🎧 Play snip - 2min️ (33:11 - 35:43)](https://share.snipd.com/snip/95ea86dd-65c3-4589-bac9-a90f6ea2090b)
<audio controls> <source src="https://chtbl.com/track/7D91G/traffic.libsyn.com/secure/corecursive/066-sqlite.mp3?dest-id=628353#t=33:11,35:43"> </audio>


### ✨ Key takeaways
1. By doing things yourself, you have more control over your own destiny.
2. It is a liberating experience to be selfsufficient.
3. Preppers are not less fair looking from the end of the world, they just want to be independent.


#### 📚 Transcript
<details>
<summary>Click to expand</summary>
<blockquote><b>Speaker 1</b><br/><br/>And so because i wrote it myself, it exactly mit me my needs, and is the perfect product for what i what it's doing. So by by by doing things yourself, ah, you control your own destiny. You have more freedom. Ah, you're not dependent upon third parties. I it's a very liberating experience. I kind of think of myself, idon'tknow, there's this phenomenon that you can see on you toob about a people living off grid. And, hm, he they go out and they buy a little bit of andthey're going to rasor and food, and they're hey're going to live off grid and stuff. What do they call that? Survivalists or preppers, preppers, maybe, maybe it's preppers, butno, they're not less fairly looking from the end of the world. They're just, they don't want to, they don't want to depend on trador joes. They don't want to depend ont local foods for they want to be self sufficient. And i guess there's an element of that in me, in we live, and we live in the city. I can't get by without kroger. If croger and aldian and publics go go under, i'll starve. I not im not to that extent. But i do appreciate the h people want to want to to control their own destiny andnd do things for themselves. Right now, i'm having some trouble with g male. I know that when we were setting up this, this meeting, you you you noted that a lot ofthe attempts to reach me by g mailr ar, bouncing back. And i'd, i've been struggling to forget how to solve that. And i'm thinking, and so now where does my mind go? Naturally, i'm going to write my own mail. Sirer, i was making notes on even as we were setting up this call, that's a big problem. And that's at least as difficult, if not more difficult, than writing a datavas ingine. But you know, i don't want to be beholden to gema. I don't want them controlling my destiny. I don't want them controlling the record of all my conversations. I want to control that myself. And so going to go through a lot of pain and a lot of work and a lot of effort to come up with some solution that i can control myself. I can go out in leas o a virtual machine out there in the cloud, and run it myself, and not depend on a third party to control my union.</blockquote>
</details>



---


### [38:07] Richard's Crazy Idea


[🎧 Play snip - 1min️ (36:45 - 38:06)](https://share.snipd.com/snip/efc3ac08-88bf-46e4-af28-33c649bdbcfc)
<audio controls> <source src="https://chtbl.com/track/7D91G/traffic.libsyn.com/secure/corecursive/066-sqlite.mp3?dest-id=628353#t=36:45,38:06"> </audio>


### ✨ Key takeaways
1. Richard's data base is the most used data base in the world, and by some counts, it's the most widely deployed sophomore mondule of any type.
2. If it disappeared, your web browser wouldn't work, your smart phone probably wouldn't up, and probably your car wouldn't start up as well.
3. Its impact on the world is massive.


#### 📚 Transcript
<details>
<summary>Click to expand</summary>
<blockquote><b>Speaker 2</b><br/><br/>If my lawn people disappeared, i'd be in trouble because my push motor is broken. But i'd be in more trouble if s c l a disappeared. Richard's data base is the most used data base in the world, and by some counts, it's the most widely deployed sophomore mondule of any type. If it disappeared, your web browser wouldn't work, your smart phone probably wouldn't up, and probably your car wouldn't start up as well. Its impact on the world is massive. And there's plenty of places where it could have lost its way. The consordium could have stifled progress, or run out of money, or the full year it took to address all the android bugs could have easily burnt richard out, but he prevailed, and now he's in a great position to offer advice to others who want to create impact full open source softwhere i had this crazy idea of it, and i'm going to build a data base engine that does not have a serven, that talks directly to disk and ignores the data types.</blockquote><br/><blockquote><b>Speaker 1</b><br/><br/>And if you ask any of the experts of the day, they would say, that's impossible. That will never work. That's a stupid idea. Fortunately, i didn't know any experts, and so i did it anyway. So this sort of thing happens. I think maybe just o, younow, don't listen to the experts too much. Dnnd n do what o do what makes sense. Solve your problem.</blockquote><br/><blockquote><b>Speaker 2</b><br/><br/>All right, that was the show. I hope you enjoyed richard's story.</blockquote>
</details>



---





Created with [Snipd](https://www.snipd.com) | Highlight & Take Notes from Podcasts