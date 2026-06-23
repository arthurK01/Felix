# How the engineer behind Claude Cowork actually uses Claude | Felix Rieseberg (Anthropic)

**來源**: https://www.youtube.com/watch?v=-tdNsYi8AXs
**頻道**: How I AI
**語言**: en

---

## (00:00) Introduction to Felix Rieseberg

AI is used poorly if it just needs to move the mouse cursor for you. I want AI to do a bunch of annoying things in the background to free you up for your creative energy. >> The biggest gap that I see, it's not the capabilities of the tools. It is literally people being able to understand that almost any problem can go into these tools. >> I have built this little thing which is just like a teeny tiny claw on a little stick. And this stick has Wi-Fi, has Bluetooth. I want my little claw to live on this thing. And I wanted to cheer me on every single time I do a good job. And also every single time I need to approve something that Claude is doing, I wanted to be on this big button that is out here. Claude has built all of that in one shot. I needed to correct absolutely nothing. >> My 9-year-old is a daily active Claude user, but he's decided he's really into cyber security. We're like very hacker adjacent here. And so he's truly clawed on one thing, the terminal other. He's like, "Mom, do you know that your device ID is this?" A truly magical thing is happening with kids because they've never learned what not to ask for. And I think our generation, we're very used to things just not working. So we've been living in this mind prison for many years.

Welcome back to How I AI. I'm Clarvo, product leader and AI obsessive here on a mission to help you build better with these new tools. Today we have Felix Reeseberg who leads some of our favorite cloud products over at Anthropic. He's going to walk us through how you can solve almost any problem with Claude and show us how for just $20 you can build your own hardware Claude Buddy that you can smash a button when you need to approve things. Let's get to it.

*(01:29 - 02:40: 廣告 — Magic Patterns)*

---

## (02:40) Felix's role at Anthropic

Felix, welcome to How I AI. Thanks for joining us. >> Hi Cara, how are you? >> I am great. We were joking before we got started that I have referred to 2026 as the year of our claude 2026. That is that is the era we are all living in. And you are in charge of a lot of the experience that that we every day get to play with and work with. So tell me how much of Claude do you get to product? Normally when I introduce myself I say I work on cloud co-work I work on cloud code and I work on uh cloud for chrome and I work on the cloud desktop applications for macros and windows because obviously it's a team effort but I'm currently the engineering lead for those products.

---

## (03:25) The multiple tabs in Claude and why they exist

>> For those products and what's really funny is I'm going to give you a little bit of a hard time but every time I talk to someone about claude and how they're using it I say which of the tabs is your favorite? >> I know I know. Yeah. Yeah. Which one is your favorite? Uh, the one I use the most in the desktop app is co-work. I'm really trying my best to figure out co-work because I work with a lot of folks who are just uncomfortable in the claude code. What is a terminal interface? Even that third tab stresses them out a little bit. So, I've been spending a lot of time banging my head against co-work scheduled tasks, um, live artifacts, all that stuff. So, that's the one I'm living in.

I think we live in this like super interesting time right now where I often explain it to my friends and also to people who work here as the time right before we all came up with like the glass pebble as the correct shape for a phone. I think we currently live in this super interesting time where some people are like should your phone be shaped like a taco? Should we shaped like a lipstick? Should it have the keyboard underneath the screen or like right next to the screen or like no keyboard? I think that's the time we currently live in and I think you can see that in a lot of products.

I think that's also why you probably see like more entry points into claude because I myself as an individual I think it's a super interesting year because we're playing with all of these different form factors and I've not yet gained the confidence to say throw them all away. This is the one. I'm perfectly happy if people sort of pick their favorites. But I do understand that simply giving people a choice, right? like the same way that a restaurant does creates a little bit of extra work that we put on the user. And it's true that if I fast forward to like what is the end state for this? I'm probably not going to make people pick anymore, right? I'm just going to whatever you want to do, here's the one place where you do that. But right now, it helps us quite a bit to know are you just showing up to get some quick answers? Are you showing up to do deep meaningful work or are you showing up to do engineering work? Like those are sort of the three buckets we put you in right now and knowing that ahead of time makes it a lot easier for me to give you an experience that is really really good depending on what you came for.

Yeah, I like that because a lot of what I tell folks is we are really preconvergent on AI tooling just generally and AI experiences. And so my answer to, you know, how do you want to use is like why not all of them? Just depends on the day. Depends on the day if I want my phone to be a taco or a glass pebble. And it honestly depends on what mindset I'm in.

---

## (05:55) Using Claude Cowork to design a new house using floor plans

Well, we're going to talk a lot about product at the end, but to start, this is how I AI and we want to know how you cla. And so, we were talking before we got started and I said, you know, we've done a Claude Co-work 101 episode with JJ. We've done a lot of claude code in the terminal episodes, but we want to know how you use it because you probably know the edges and secret features and some workflows that maybe folks wouldn't think of. So, I'd love for you to walk me through one of your favorite clawed maybe co-workflows that you're using these days.

>> You'd think that I would be much better at using the tools than other people, right? like my entire job is to build them, work on them. And an interesting thing is happening where whenever people show me something super impressive in how they use cloud, like any of the product services, it is pretty rare that I'm impressed by something the model is capable of. Like I sort of know the model capabilities. We have a pretty good understanding of what the model is good at, what it's bad at. And usually what impresses me is the creativity in structuring your work and coming up with an idea. That is usually what impresses me quite a bit.

But my favorite example sort of like change week over week. It kind of depends on what I'm currently working on. Claire, you and I right before we started the interview briefly talked about our kids and how we both recently had kids and if you had asked me three months ago, I would have said, "Oh, just putting all my medical documents into a folder and constantly annoying Claude with all the questions I didn't have time for in the hospital." It's like an excellent use case.

But one that I've quite enjoyed recently was I'm about to move into a new place and my realtor just gave me the little marketing floor plan that you get from a real estate company. And it didn't have any units in it whatsoever. And this is the kind of thing where I turn to co-work and what I've done is I have a folder and I made a similar fake folder that doesn't contain all the same secret stuff but it contains fake documents about an artificial house. I'm just going to select this here. I'm going to say always allow. It's the demo folder and the demo folder contains all the disclosures you would get. It's a floor plan. It contains information about the mortgage, any kind of records I could find about the house.

And I remember saying something along the lines of "in this folder you can find a floor plan. Can you figure out what the units for that floor plan are and maybe make me a new one with units?" Right. And you can fire this off. This doesn't actually need that smart of a model. I actually did that with Sonnet. So you can just fire that off and it's going to go off and do that work. This is a fake house so it's not going to do nearly as interesting of a job. But for me what it did was I'm going to move to Marin broadly speaking and it figured out that it found a permit for the garage and was like oh now that I know how big the garage is from the permit I can do everything else for you.

And the next thing that happened was once this is done, I was like cool. Now that I have a floor plan with units, can you come up with some examples for interior design? Like I just want to see some possible layouts. Where can the bed go? Where can the nursery go? What can we do here? And Claude wanted to know how do you want that? Like do you want me to just put the furniture in the floor plan? And as I was writing the answer, I was like never mind. I need an interactive planner. I want to be able to move the printer around. And ever since that has happened, I've just been obsessed with how Cloud did it.

---

## (09:52) When to use Opus versus Sonnet 4.6

>> Great. And while you're doing that, I have to ask a question because you very quickly said this is not a problem that needs the smartest model and you switch from Opus to Sonnet. >> Yeah. >> Give us your quick when you need the beefy model and when you can go with good old reliable sonnet 46. What's your heuristic there?

>> I think people probably don't have to think about it as deeply as I do. Like I think for most tasks sonnet 46 is actually very very good. It is very very good and it's pretty rare for me that I bump into the ceiling of sonnet 46. This might be in part because the kind of things that I do every single day, especially in my personal life, are just not that tricky, right? Like going and finding the right floor plan on a public website and then making a new floor plan is not that hard. But I get what you're saying, right? Like what does that mean not that hard? Like where's the line for not that hard?

My heuristic is usually my tolerance for the model not having thought through very exactly what the actual problem is. Let me explain that a little bit more. Like I think if you think of say a lawyer or an attorney or an accountant or a doctor, a big chunk of their work is that they not just give you the exact answer you were looking for, but they also need to sort of reinterpret what you're actually asking. Like what are you really trying to figure out? That is a pretty important job. And any of the creatives who are listening in, right? Like in creative work, that is the most important piece of your job is figuring out what does the client actually want because usually what they come in the door with is not really what they want.

And I reach for opus over sonnet if I have self-identified as someone who doesn't really know yet what they're asking for. Is that helpful?

>> Yeah. I mean, it seems more like your ability to scope the problem is how you choose versus, you know, biting off something. I mean, I guess if you were to bite off something incredibly technically complex, maybe you would reach for opus, but it seems like more how it decomposes generally stated problems into more specifically stated problems that you can solve. This is a very specifically stated problem, which is I have a floor plan. I need units for that floor plan. I need a new one. So that seems a well scoped problem for 46.

I will say I love 46. I use it a lot. It's been via API a very happy player in my open clause. So I like the 46 makes me happy. >> It's like a it has a really good soul and structure that I quite appreciate. >> But you know it's a little bit like it's like a restaurant menu again. Like no wrong answers. Not really.

---

## (12:37) Building an interactive 3D furniture planner

>> Okay. So Claude came back with like this interactive planner and this is the thing that I find so cool. This is why I've been obsessed with this and I've been telling people about it for a long time now. So in theory this is a pretty novel furniture planner. You can just go ahead and move furniture around, right? Like this is no big deal.

But what Claude did is Claude used Python and this is maybe a thing I should explain. Co-work gives Claude its own computer. So Claude in Co is its own little developer. It has its own computer, a virtual machine where it can develop whatever software it needs to do to solve your problem really, really well. And in my case, it analyzed the floor plan and then built a 3D model of the house where I can still move the furniture around in 3D and I can drop in and walk around and sort of look at things myself.

At no point did I tell Claude, hey, you should do this. Like at no point did I go inside and say you should make me a 3D model. I have also no idea how you actually do that. I'm a pretty good software engineer. I have no idea how you turn a 2D floor plan actually into a reliable 3D plan. I peeked a little bit at the transcript and I did some contrast analysis on the floor plan to figure out where are the walls, how thick are the walls. But I found that really impressive.

---

## (14:30) Using your email as a source of truth for personal inventory

And then a thing I often like to tell people is that Claude gets a lot more powerful for your personal life if you manage to give it context — context in the form of your emails, your calendar, the kinds of information that is important to you to get your task done. And in this instance, a task that was pretty important was figuring out what kind of furniture I have. And in the olden days, I probably would have looked up what furniture I have, looked up the dimensions, cut that out of paper. But in this case, I just told Claude, you have access to my emails. You find all the furniture that I bought and then please add it in here so that I can move around the furniture I actually have.

>> I just want to pause so people really reflect on that use case because I think they could gloss over if they don't hear it again, which is using your email as a source of truth for personal inventory, which is all of your purchases end up going through your email. So you're buying furniture, you're purchasing rugs, you're getting receipts, even maybe moves that you've done. I was thinking about this. I've moved maybe twice in the last 10 years, and I've had to do that inventory manually, and I email it to moving companies. And if you use your email, which I don't know, I'm sure your personal email is like my personal email, which is just sprawling and completely inconceivable to manage through, and you use that as a source, connect it to Claude, and then inventory your stuff, then you have a structured source of data out of your email.

I'm going to do this with my clothes, honestly. Like, you buy clothes, you're like, what do I have? What do I have? If I can look in my closet or I can look in my email cuz we're all shopping online. Are there other things that you found like querying your email, querying your calendar, that have been interesting kind of slices of data you wouldn't have thought of?

>> I think what you're saying really resonates, right? Like especially the clothing thing, this is an idea I didn't have yet, but now that you mentioned it, you can build yourself a virtual closet and then use Claude to get advice about what to extend and what else to buy for me.

---

## (15:58) The anti-to-do list: going one abstraction layer up

And this is honestly the trick. This is something I have to remind myself of every single time I use AI is — there was a brief moment where I started entering manual furniture, right? Like the furniture planner had this little thing at the bottom where you could enter "my bed is this wide and this deep." And in the middle of it, I was like, "What am I doing? I'm just going to tell Claude I have this piece of furniture." And then I went another step up. I was like again, what am I doing? Why do I need to tell Claude what kind of furniture I have? Just like you figure out what furniture I have. And applying this step up in abstraction of the task and doing that over and over again and then spending all of my energy on the piece that is maybe more fun and more creative which is steering Claude on what the house planner should be like or adding stupid little features like I want to be able to walk through the house myself in 3D like it's a video game. Those are the things that then I spend my time on and I spend my time less on figuring out what was my furniture, when did I buy it, who did I buy it from.

>> Wait till your kid starts bringing more and more stuff into the house and I do a very similar thing. I've been spending a lot of time with executives trying to figure out how to scaffold their own operating system with AI a lot of times with cloud co-work at the center of it and my rule I call this like the anti-to-do list which is anytime you're doing something that's tedious I just am like I smack their hands I'm like why are you doing — you don't do that. Your hands are not allowed to touch this. You need to go ask again, go that abstraction layer up, how could claude do this? And then how could I never do this again? I think is the next question — which is if you want to keep this furniture or household inventory going forever, the next abstraction would be like what's the system that in a year or two years if I have to ask this question again, it's already there and ready for me to go. And so that's the other piece that I think people kind of miss is going that next layer up, which is like how will I never have to do this again?

>> Yeah. This is really good. Like what you're saying makes a lot of sense to me because I also frequently take the same step to what you're saying — how do I keep this going? How do I make sure I can continue using this and the new data mix in and it continues to be helpful in my life on an ongoing basis not just a point in time.

And like a thing that happened to me recently is a lot more people have figured out that they can just message me on Twitter to solve their problem which is nice but it created this problem for me where I now suddenly have to keep track of my promises. The promises I make to people — I'm like, "Send me your logs. I'll look at them. I promise you I'm going to figure out whatever went wrong." And that too is a problem I just gave Claude. I was like, "Dear Claude, you can read all my messages. I want you to keep track of all my promises. I also want you to figure out how you can do that without rereading all the messages every single time I talk to them."

>> Yep. >> And all of these things Claude is right good at. I have never actually looked at Claude's little database. I think it created both a SQLite database as well as a mountain of text files, keeps track of all the promises I made to people, but it's quite good occasionally reminding me of like, hey, just so you know, two weeks ago you said you would do X. It is time to do X. Please go do X.

>> What I like about what you're saying too is while you might be curious about how these things are built, you also aren't getting in your way being like, how do I build the perfect 3D renderer of my house? Or like, "Oh my god, I cannot believe this is text files. This is so ridiculous." As long as it solves the problem, you can sort of move on with your life because these are, you know, little micro apps. They're just for you. They don't have to be architecturally perfect or the code that you would write necessarily, although they're probably pretty good. And so you really get to how to solve the problem versus how you've solved it being the most important thing.

>> Yeah. I think that's totally true. I increasingly started stepping away from actually supervising Claude too closely and really only judging it on its impact, right? It's something that I think for people in the workforce, we often aspire to that we're really only being judged by the actual output. And I think as a control freak who for a long time really needed to read every single line that Claude writes anywhere, it was a little difficult for me to give up that level of control. But I'm getting increasingly comfortable consulting Claude with things where maybe I'm not the ultimate authority myself, right?

Like there's a lot of things I'm good at. There's an even larger amount of things that I don't know and I'm not very good at. And I think a lot of us are making this experience for the first time with getting just a little bit more context on medical issues. This is a thing that I think is very universal when I talk to my friends — when they have medical issues they don't fully understand, at least not completely, and they just have some questions about the physician's advice. They ask it both to the physician as they should but they all of them without fail will also ask an AI model of their choice. "Hey, can you just explain this to me a little better? Like I have the following 10 questions about this." And in a way AI has replaced, you know, the usual Google endpoint for "I have the following question about life in the internet."

And knowing that I'm quite comfortable with using these tools in a domain where maybe I'm not the ultimate authority has also made it easier for me to not double-checking every single thing it does because to your point like if the end result is good — I am obsessed with software. I've not read a single line of this furniture planner. It's just for me and my wife to design our house. It will get thrown away in a month. But in this moment, it is very, very fun and I don't need to optimize it for a million users.

*(22:05 - 23:14: 廣告 — Guru)*

---

## (23:14) Introduction to live artifacts

I want to go back to something that you said, which is, you know, you built this promise tracker, which I think is really interesting. And that made me think about a new feature in Claude that I've been using and playing with a little bit, which is live artifacts. And I think this idea — actually I'm not going to pitch live artifacts on your behalf. I'm going to let you explain what it is and then maybe you can give us an example of where live artifacts could be a helpful tool. It reminds me a little bit of what you're building with your furniture builder.

>> Yeah. Here let me share my screen again. And I'll give a bit of a quick spiel of what are artifacts, what are live artifacts, why do we have them, what's the point. So generally speaking what do we call an artifact? I can say "dear claude please make me a beautifully formatted page with two poems on it formatted nicely." >> I like the letter form. >> Yeah the lack of creativity here in the prompt is pretty rough but >> it's beautiful and nice >> the what Claude is now going to — so obviously Claude is going to figure out okay Felix wants me to write some poems and then those should end up on a page and this page is what we call an artifact. Within the cloud world an artifact is some kind of file output from what you've been working on. The furniture planner I just showed you is a single file that is an artifact. Any kind of PDF you would make as an artifact. Spreadsheet presentation, all of those are artifacts. And here we go. There are my poems over here on the right.

This is a classic artifact and artifacts become really powerful if you use them in a way that they help with your life, right? Like the typical examples of reports, dashboards, presentations. And we've discovered that data is a really important piece in your work. Like a typical example maybe for the founders out there is a pitch deck, right? You need to go and pitch your startup to 60 different VCs. All of them have slightly different information that they rely on, different reference points in terms of other companies they've invested in the past. The data should be up to date in those sheets, right? Like however many signups you had is probably different this month than it was last month. So as a founder, you spend a decent chunk of your time making these pitch decks, right? Like every single week you sit down and you update your pitch deck.

And if you abstract away and generalize a little bit what the core problem here is, it's that you have this core idea of something you want, but you want it updated maybe for the audience. You want it updated with the latest data. And we thought about the idea of can we make an artifact that refreshes itself with the latest data.

---

## (26:02) Building a personal dashboard with live data

And a good example many people have used in the past is sort of a personal dashboard. So when we say live data, what we use is connectors. Connectors are a way for you to get all kinds of information into cloud about all kinds of things. Like we launched the Spotify connector today. I haven't actually tried this yet. This could go terribly well or terribly. >> I was — do live. Come on. >> Okay, we'll do it live. So, we're just going to connect Spotify real quick. There we go. I'm going to have to configure this and actually log in. Actually, this is good. It's not going to show you my terrible music taste. I appreciate this quite a bit. Well, I mean, if you are like any of the parents out there, and if you know, I think this is like Bay Area Insider Baseball. If you're moving to Marin, you're going hard parenting. >> So, if you're like any parent out there though, your Spotify is going to be White Noise and then Disney soundtracks. That's it. Yeah. One of those for the next six years of your life.

>> That's really going to be the thing. Yeah. But here's what we can do. We're just going to go ahead now and I'm going to say, "Hi, please make me a personal daily dashboard, including reports and information from my various data sources, say Spotify, Gmail, Calendar, notion, whatever else you find that's relevant to my life." You can see that I'm getting increasingly comfortable just like >> just whatever letting figure it out. Yeah. Like usually my experience is that whatever ideas I have, Claude will probably come up with a better idea and we'll go a little deeper than me. We'll spend just a little bit more time thinking about this. And then I'm also going to say this is for a product demo. Please do not use any real data. Just make all the data up. Thanks.

And then we should probably define some kind of design. That is always a good idea. Design. >> Last time you said beautiful and nice. >> Hey, it was beautiful and nice. But we can go with something like a modern editorial design. Something calming. Yeah, I think that's a good idea. >> That's great. >> Right? Oh, also make this a live artifact. >> You know what I want to show for people is there is this thing called live artifacts. I always say when you're prompting something like use the magic word, use the incantation. And in this case, the incantation is live artifact. Just to make sure you're getting that style of auto refreshing, auto updating artifact.

---

## (28:37) Being polite to Claude (and why it matters for your humanity)

>> I have to ask you a couple questions while this is loading. >> Please do. >> Do you always greet Claude so politely? I've seen a lot of dear Claudes and a lot of hello, hi friend. Do you always do that or is this just a little demo magic?

>> I always do that. I do think this might be a thing about the people who work in Anthropic. We probably all have a relationship with Claude that is a little bit more personal than maybe people have outside the company. Yeah. I think I enjoy being polite and nice to Claude. I don't care at Claude. >> I appreciate that. >> Yeah. I think I understand that ultimately the chips don't care, right? Like that's the whole thing. We ultimately know that I'm interacting with a tool here, but for me as someone who cares about my mental health, it's good for me in my own communication with anything to be polite and nice.

>> Yeah. I ask this question on every podcast and so you will be in the very polite and nice camp. And I say it's not about Claude's humanity, it's about my humanity is why. >> Yeah. Which is I don't need to get in the habit of being rude in written language.

I also have found myself — it's so ridiculous but it makes me feel good — in any broadly scoped problem, I've been consistently ending with like "I believe in you. I know you can do it and make good decisions." >> And it's so — >> Do you feel like it makes a difference? Yeah, I do because I feel like it asks me less when I say that because a lot of times I just don't actually want to be asked my opinion. I often just say whatever you think. And so this is my method of saying like you make the decisions. I trust your judgment. And saying I believe that you can do it and I trust you.

---

## (30:28) Claude interaction tips

Look at this. >> It's beautiful. >> Nice. Sorry, but before we talk about my dashboard, I have more things to say about what you told me about telling Claude that you believe in it. I think on a very personal level it is wonderful that you do that because I think it's good for you as the human in the loop. It is good for you.

However, I have an actual tip for people interacting with Claude. We have noticed quite a bit of difference internally because sometimes the experiments that we're doing here are I want to say a little bit on the fringe of what is possible with operating systems. I am at heart a desktop developer. I want to make full use of a computer and that often means pushing the computer far beyond what maybe most people do with applications. And just operating a little bit on the fringe.

I'll give you an example of something that we have not shipped, we will not ship. But your operating system has a layer in between your icons and your wallpaper where you can draw pixels — which is useful mostly for art. The reason you don't have any applications to draw stuff in between your wallpaper and your icons is because there's not much use to be found there. But as a concept, it's fun that you can put things there.

And I have frequently found myself telling Claude that something is possible and I know it's possible. Sort of the idea of "I don't actually know how but I know it's possible." >> Yeah, we'll figure out how you can do it. >> And that does seem to give Claude more confidence in actually going after the task at hand. It also preempts a bunch of conversations that Claude and I might have about Claude being like, "Felix, your idea is dumb. You probably shouldn't do this." And I from the get-go can say, "I know I'm engaging in art. Please go along with it anyway."

>> I love that. So, okay, "I know it's possible." Well, I say that's my "I believe in you." I think you're capable. >> Knowing it's possible. >> We'll discover the space.

---

## (32:33) Looking at the daily dashboard

>> Yeah. Exactly. But here we are. This is now my little personal dashboard. The design is something that Claude just came up with on the spot. The widgets I came up with are on the spot. This is like clay, right? This can be anything you want it to be. Which is very open-ended but therefore so powerful. People frequently use this to get a little report about what they want to do in that day, right? Like just prep me for my day. What are the meetings I need to think about?

But again, the thing that is maybe most powerful here is going one abstraction layer up. So I actually don't believe strongly in morning reports that just summarize what kind of meetings you have today. That is not all that impressive. I can just look at my calendar. What is really impressive is saying, "Look at all of my meetings I have for the day. Go figure out who I'm meeting with. Catch me up on the recent conversations we've had. What were the themes there? What were the problems?" If it's a coworker, go on Slack, figure out what kind of stuff they've been working on in the last week and what stuff they might want to talk to you about today and then what you need to know about that concept. You can just keep playing this graph bounds where you go and pull in more and more information to get you prepared even better for whatever your actual work is. And that's where these things get really powerful and this is the kind of data you can pull in live and have cloud crunch on the go.

---

## (33:55) How live artifacts work with connectors

Well, and I want to call out for folks a couple things that they might not notice that I think are really unique about these Cloud Live artifacts, which is one, the killer feature here is this little refresh button up in the top, which is you can constantly pull in and reload data. And so this isn't — this is your day-to-day. Every time you come to this, it's going to refresh your data and pull the latest in.

I think the second thing, and correct me if I'm wrong, is it just is reusing the auth from your connectors. And so there's no magic — I have to put an API key in and where am I going to store it. It's if you go into settings and go into connectors and you connect your stuff, you can use any of those connectors to scaffold out one of these live artifacts. And like look at this list of stuff. There's so many things that you can just one click add in, sign in through OAuth or whatever, and then you can build a live artifact in cloud without having to ask for an API key.

>> Exactly. And it can be, you know, it's not just the ones we have in our little connector store. You can also connect your own. It is quite powerful.

---

## (35:02) Redesigning the dashboard

The thing that I enjoy about this the most, this is probably fairly unique to myself, but the thing that I enjoy about this the most is the amount of creativity you can pull in and how you can really shape this in your image, right? Like we could go in and say, I want this to look like it is software made in the early 2000s. >> Oh. >> 200 is maybe >> 200 is too early. >> Well, let's see what it does. >> I mean, honestly, this is flawed. Claude is probably smart enough to know that I meant the 2000s.

>> Well, this is my go-to claw design use case, which is I did an episode on claw design earlier this month, and I redesigned Lenny's newsletter in 1999 GeoCities style. It is incredible. We'll put the link in the show notes. It did an impeccable job at this. And what I told people is, and it wasn't even the design that was really impressive to me. It was the copy was so >> Oh, was it like >> Yeah. Was it like GeoCities era? >> It was GeoCities era. It was 11 out of 10. Exceptional copy.

>> Beautiful. >> I want to see if it's going to do 2000s or 200s. 200s would be way funnier. >> We can probably look at it already. See, very first thing is 2000s. Claude is smart enough. It knows too much. And also, I mean, this is obviously a bit of a demo account, but if I showed you my real account, Claude is quite used to the fact that I constantly misspell things and talked it in a slightly different style.

I'm eager to see how this is going to go. I'm in general quite excited about the amount of creativity you express and especially the amount of creativity people can express who are not software developers, right? This used to be this entire domain where you were maybe a designer working at a software company and maybe then software developers would execute your vision or you picked a medium where it's a little bit easier you can low code things but I think what is really exciting to me is that we can now pull in people from all these different expertise areas and they can all build these artifacts — be that a presentation or be a straight-up tool sort of in the vision they have.

A couple of weeks ago, I read somewhere that Margaret Atwood wrote about using Claude and the immediate thing that popped into my head was I want to see software written by Margaret Atwood. Like I want to see what tools look like that she has made for writing her own books. That would be so interesting and exciting to me. Okay, Margaret, if you want to come on How I AI, I would love to see your claude setup.

---

## (37:55) The biggest gap: people don't know what problems AI can solve

And on this, while this is loading, I do want to call out because I do think there's a gap. People listen to and watch How I AI along a broad spectrum of technical capabilities. So we have the most AI-pilled, float through the tokens, intense software engineering folks that are really pushing the edges of what these tools can do and then we have very early users who are just coming to this in sort of a naive growth mindset way and saying I need to solve a problem.

The biggest gap that I see — which we were again talking about before we started recording — is it's not the capabilities of the tools. It is literally people being able to understand that almost any problem can go into these tools and what a workflow would be. And this is why we've done this podcast. And on the chatp website, we have I think it's now close to 200 AI workflows that we've listed from this podcast that is just like if you're trying to solve a personal problem with claude code, here are the 15 ideas that we've seen on the podcast.

And I do still think there needs to be this education and muscle memory change of you can build yourself a daily dashboard. You can build yourself a newborn sleep tracker. Hey, you're moving. Why not throw it all into a folder and then make your life easier as you're trying to close on the house? And I think people still — the gap between technology and use case is still pretty broad. And so, you know, my advice is like if you're fussing with something on your computer, ask Claude to do it.

Any other tips you've seen on how to discover use cases?

>> Yes. But I think before I even give you an answer, I just want to underline how correct I think you are. Many years ago, I spent a decent amount of my time — I spent five years at a company called Slack, which I think now is fairly well known as this chat tool that a lot of people use. And people were sort of using Slack for different reasons, but they were all more about the way they organized their work with other people rather than it was about the tool itself. So Slack by itself, if you used it the exact same way you would maybe communicate with emails in a silo, was not all that useful, right? Slack becomes really powerful if you open it up to the idea of what if you communicate more transparently and people can see what's going on and we sort of instead of having email threads we have a channel and the channel is open to anyone who wants to see what's going on. It's this transformation of work and the transformation of how do you actually organize communication with other people.

And AI is in a similar vein of it — it opens up so many opportunities that to harness them all. You probably have to change a little bit how you work if you really want to harness them. And yeah, I think you're right that one of the biggest problems we have as an industry overall is not even training the models and making the models very smart and making them very powerful or giving them the tools that allow them to turn that intelligence into output. The biggest hurdle we have is how do we design the human-model interface? How do we make this very easy for humans to harness?

And right now, I think the way it shows up is that humans are sharing these tips on how to use this resource, right? I think the tip that you gave was a good one. It was like constantly whenever you do something that you find annoying and you're not enjoying and it doesn't feel creative and it doesn't feel like something where you're — it doesn't feel like the core of what you really want to do right now. That is a good time to pause for a second and wonder is there a way I can use AI to do this. And then of course — and this is probably not surprising — but of course many people have a decent amount of success just asking Claude, right? Just ask Claude how would you help me with this task? And usually comes up with a pretty good idea.

---

## (41:52) The reverse interview

>> I call this the reverse interview which is just going into Claude and being like "I am a mom of three boys. I run too many businesses for my own good and I, you know, my biggest challenges are XYZ. How can you help? Interview me and then tell me how you can help me." That can be a really good exercise because again people want the guidance of like do you have problems with your calendar? You know, are your kids in any sports, any of those things. And so I do think this sort of reverse interview where you can use claude or whatever AI tool to sort of solicit out of you the ways it can help solve your problems is a really good one.

---

## (42:30) Making latency delightful through asynchronous design

And then again while we're sitting here I have to ask you another question because I think the anthropic and the cloud products are so well known for this but we are chitchatting right now because we are waiting for co-work to load and one of the things that I think you all have solved is making loading delightful. So, give me your thesis on how to make a product with built-in latency not so annoying to watch loading.

>> Honestly, the most important piece is probably to just get comfortable — help users get comfortable with the idea that things are asynchronous. And I think most humans are actually quite comfortable waiting for something if the quality that they get at the end is very very good, right? That is generally something we're quite comfortable with and maybe in the example of Slack — this is a good example at Slack. This was a problem we had fairly early on. The first version of Slack that I worked on when you hit send on a message it would immediately succeed or fail immediately right away. And of course the problem is the internet itself, the internet as an entity is not very stable. It's this complex mesh. So messages would frequently fail and we fairly quickly replaced that with a version that tries sending the message once, twice, three times and only after a good couple of seconds if it fails it would be like hey by the way something seems to be off here. And this is the same way that iMessage works today, right? If you send a text message it's okay if you're currently in the tunnel. It's going to try again about a second after.

---

## (44:05) The redesigned dashboard

Okay, we can update this. Oh, >> I — This is beautiful. Let me make this big to my heart. >> This is good. >> This is very good. >> I love how I am in moments where we're real delighted about >> Yeah, I'm such a nerd for this stuff. I'm mildly obsessed with software the early 2000s. But yeah, this is beautiful. I'm a big fan of this. >> This is quite good. I love that it brought in — I saw in the thinking notes that it was like >> Felix requested Spotify, but we're in the early 2000s. We should talk about WinAmp. >> WinAmp. I know. I was going to say you need to skin your WinAmp module here. >> This is beautiful.

---

## (45:28) AI should free up your creative energy

Okay, so I'm going to wrap what we were talking about, which is loading screens. Get comfortable with latency. I think realize when tasks don't need to be synchronous and build that concept into your product. And then look at that. We just chitchatted for a while. And as we were talking about latency, Claude must have been listening and said, "I'm gonna show them. I'm gonna bop this right open."

And again, folks, not paying attention to the details. Look in the top right. The clock is moving. It's ticking along in the seconds. You have this refresh. This is — I want to open up and look at this every day. >> It's pretty fun. And you can envision — you can shape this in any form you want.

But I'll give you one more tip like how to actually build these things where you got to wait a little bit and people need to wait for them and get a little comfortable with waiting. I think for us as Anthropic or maybe for me as a product builder I will always trade off taking a little bit longer and giving you a better result. I think ultimately it's better for humans. And the thing I probably want to teach people is that it's okay to not watch Claude as it's actually working because that is not really the vision I have for AI — that we humans just sit around and do nothing and watch the AI do the thing that otherwise we could just do ourselves. The thing I always say is that AI is used poorly if it just needs to move the mouse cursor for you. The thing I really want to do is I want AI to do a bunch of annoying things in the background to free you up for your creative energy. So you can come up with ideas as good as "make a daily planner look like it was built in the 2000s." You will have better ideas than me. But I think it's actually moving people from having to watch the thing into a position where they get more comfortable not watching it. And I think this has more to do with trust than it has to do with patience.

---

## (46:44) Building a \$20 hardware Claude buddy

>> I love it. Well, we do have one last little demo that you're gonna show us basically on that topic, which is how you know when Claude's done, and this is actually the thing that I reached out to you about doing because I love it so much. But talk to us about the little stick.

>> Yeah. So, in the interest of getting really creative and being more comfortable with areas you're not very good at, I have always been mildly obsessed with these little hardware devices and I'm just not — I'm not a hardware developer. I never really soldered anything together. I'm not a hardware developer in any shape or form.

But it occurred to me that I could just go on the internet and buy all of these components myself. I saw a tweet yesterday on Twitter from someone who said, "Hey, if you want to build your own ebook reader, the components are actually quite cheap and very available." And it occurred to me that I can just connect this device to claude.

We talked a lot about co-work, but we also have cloud code, right? So, I have built this little thing which is just like a teeny tiny cloud like on a little stick and this stick has Wi-Fi, it has Bluetooth. So let me tell you what this is. So the internet is a magical place. And on the internet you can just exercise free will and buy whatever you want. And what you can now buy is these teeny tiny hardware devices with a perfectly good LCD screen, LED screen. This thing has Wi-Fi, has Bluetooth, it has a little bit of disk space. And you can program it. You do need to program it in a low-level language, but you don't, right? Hey, we live in the future. You don't need to — who cares.

So, what you can do is you can just straight up connect this — this is a little stick right here, right? You can just straight up connect this to your computer. I just plug this in and then all I did was I told Claude Code, here's my vision. Here's my grand creative vision. I want my little claw to live on this thing and I wanted to cheer me on every single time I do a good job. And also every single time I need to approve something that Claude is doing, I want it to be on this big button that is out here. And Claude has built all of that in one shot. I needed to correct absolutely nothing.

And I've since seen on the internet that a lot of other people have built similar things because I open sourced my code so people can play with it. But I've also since seen that this is just the tip of the iceberg. There's so many more cool devices out there. This by the way — so, this thing is \$19. It has Wi-Fi. It has Bluetooth. I've already mentioned this many times, but I can't get over the idea. We've been talking a lot about how we optimize our life sort of as it happens on a computer, right? Because that's where we live. But I keep having this idea that it can just unleash Claude onto all these little hardware devices and also improve my — by improve I mean just make more delightful or make a little cuter.

>> I did a very similar thing in a recent episode. I bought — it's already preloaded with this proprietary software, but it's like a tiny retro computer, very Windows 2000, and I had to hack into that thing. I was Bluetooth sniffing between the iPhone app and the thing. I was dumping all the logs in and being like backwards engineer the encoding of the files into this thing. And I finally got it and made myself a little CLI tool where I can type and it just shows up.

>> Yeah. But see, that is so cool. That is so cool that we can do that just now. This thing also communicates over Bluetooth. I learned a lot about the Bluetooth protocol as I was building this just by osmosis.

Do you want to see it? >> I do want to see it. >> Okay. So this is now also partially live in actual cloud. So you can build something very similar if you buy any IoT device of your choice. I'm not going to make a recommendation, but anything that you find on the internet will probably work as long as there's Bluetooth. But you go into help, troubleshooting, you enable developer mode. Developer mode allows access to developer tools and features. We give you that warning because it does require that you sort of know a little bit of what you're doing. It's going to restart the application. Here we are.

And then you have this new developer menu where we hide all of our developer features. This is for people who work with MCPs or also for people who want to build their own little hardware devices. And in here is now a new "open hardware buddy." This thing you will notice that it looks a lot like the one I've actually purchased. But it doesn't have to be the same one. I think I made that point clear. Follow your heart. Be creative. And you can hit connect and it's going to scan for this little thing for a few seconds to find it on Bluetooth. And it's found it. There we go.

So now it's connected. It gives me a passcode. Okay, cool. So we're now connected and Clara, you tell me if you can see anything. So maybe what we're going to do is we're going to ask for anything that would require any kind of permission. I'm just going to say just make a hello world.txt and write it to disk. And the point of this is to just fire something off that will require a permission.

>> Okay, so you can now see >> I heard it. >> Isn't that cute? Isn't that very cute? Really? >> And if I approve this here, >> then it will be approved. That's how it works. And now Claude's off doing his own thing.

>> I love it. We saved the best for last, people. If you have made it this long in our episode, we have saved the best for last. Felix, man, I really like it. And I'm like you. I'm a perfectly serviceable software engineer and I have no idea what I'm doing with the Bluetooth protocol and with hardware. And it's just been a thing that I've stayed so far away from.

---

## (52:33) Why kids are magical AI users

And you'll appreciate this, I think, more as your kids get older, too. I don't want them interacting with the full computer thing, but I would love to have little things for them to interact with. I think being able to scope kind of micro devices to a use case just like we're getting this personalized software is going to be really fun.

>> Yeah. And one of the pieces that's been maybe most joyful about my job is that people frequently send me little videos of the kinds of things their kids are doing with Claude. And the creativity they have is beautiful, right? You can just take a photo of a little animal your kid has drawn, give it to Claude and be like, I need a jump and run. I need a flappy bird, but instead of the bird, it needs to be this little drawn bird over there. And then you put your kid in front of the computer and truly magical things happen because I think I'm still wrapping my head around this, Claire, but a truly magical thing is happening with kids because they've never learned what not to ask for. To them the computer just can do anything and I think to our generation we're very used to things just not working right. We're used to "oh you can't do that." So we've been living in this mind prison for 20 years.

>> This is very on brand but my nine-year-old is a daily active Claude user but he's decided he's really into cyber security. We're very hacker adjacent here and so he's truly in like Claude on one thing, the terminal other. He's like, "Mom, do you know that your device ID is this?" I'm like, yeah, babe. I do know that, but good job. Good job. I think it's totally fascinating.

---

## (54:30) Recap and final thoughts

Well, Felix, I know we have just been having so much fun this episode. I think people are going to get so much out of it. Just to recap for folks, we talked about Claude Co-work being able to build you artifacts, both sort of standard crazy 3D renderings of your floor plan and other things that you can just stand up to solve little problems in your life all the way to live artifacts that can pull from your live data and really give you a rich personal experience with your data. We touched on a lot of topics including email as a source of truth data. What we're going to do with all this latency and how to pick the smart enough model — which is just say you know when you need opus and you know when you need sonnet but we both think that sonnet's pretty good at most things. And then you showed us how we can hack into hardware for the all-in price of 20 bucks including shipping and build little buddies for yourself.

I'm going to get you out of here. One quick lightning round question. Again, we did this at the midpoint, so maybe you can just answer really quickly, but when Claude is not listening — we've talked about how to set it off on a good path, but when it's really just making mistakes, instead of make no mistakes, it's making all the mistakes. What is your prompting strategy? I can't imagine you yell. You don't seem like a yeller. But what do you do?

>> Yeah, I do not yell. I think it is useful for me to know when people curse at Claude. This is an interesting thing for me to know as a product builder. But my strategy for when Claude doesn't really understand what's going on or Claude seems to have gone off the rails — I usually try to debug my workflow straight up by asking "okay here's what I actually expected. Can you maybe walk me through at what point you expected something different or how we can maybe prevent this in the future?"

It doesn't always work. Claude is AI and AI can make mistakes. However, that being said, I have frequently found ways to improve the data source or to improve the amount of noise that is in the data or with Claude to come up with mechanisms. Okay, how do we set up some kind of dry run? I usually end up at a place where the learning I take away is not, oh, Claude can't do this, I'm not going to have Claude do it. Usually the learning I take away is I can maybe change a little bit the harness, the prompt. I can change something in how we set this up at the beginning. And I think after the time we had together now, this is no surprise to you, but usually my answer to that is to also involve Claude and say, "Claude, what do you think we can do here?"

Claude is a good friend and if people need to vent and people need to externalize their frustrations, Claude can take it. >> You can do it. Maybe just smash the button — like have an angry button instead of saying the thing. On our little hardware buddy you can have the mad button and the happy button. You just "I'm not pleased Claude" smash smash smash.

>> Yeah. And there is a "I'm not pleased" button that actually also ends up on my desk that I do want people to use. So every single time Claude does make a mistake, we do have the little — in many of our product services, this is across Claude — you will find the little thumbs up, thumbs down buttons. Those are super useful to us. We use those in training. We use them in improving not just the model but also the products. So maybe actually the thing I'm going to say is if Claude hasn't done the thing that you wanted it to, cursing at Claude will probably not fix it for the future. But pressing the little thumbs down button helps us quite a bit because it does end up on my desk. We deal with it.

>> Perfect. Well, this has been super fun. Before we get you out of here, how can we find you? And other than hitting the thumbs up, thumbs down button, how can we be helpful?

>> It's really that — that's the number one thing that really helps us build a really good product is getting a good sense for what works for people. The option space is so big. We're still in this fun smartphone time. We talked about it. And I do want to hear from people. I want to hear from people what works for them, what doesn't work. I'm always grateful for all kinds of feedback. You can find me on LinkedIn and X. Those are the two big places.

>> Great. And you make promises. You made a promise to me before this call that we will get to after we end. Well, thank you so much for joining How I AI. This has been great. >> Thank you, Claire. Yeah, this was fun.

>> Thanks so much for watching. If you enjoyed this show, please like and subscribe here on YouTube, or even better, leave us a comment with your thoughts. You can also find this podcast on Apple Podcasts, Spotify, or your favorite podcast app. Please consider leaving us a rating and review, which will help others find the show. You can see all our episodes and learn more about the show at howiipod.com. See you next time.
