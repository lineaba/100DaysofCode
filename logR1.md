__This is the log for my #100daysofcode challenge started on Monday April 9th__

## Week 1 ##
### DAY 1 - Monday april 9th ###
Went to a python meetup and worked on preparing data for the project I got the idea for that morning. I am creating a LLC name generator
simply its a program that comes up with word combinations of three words, two first words starting with L, and third word starting with C. 
The results are supposed to be bandnames. Even though it is a very simple and silly idea, I believe it will be a very good learning project, 
and one that really encompases my goals of learning more about NLP. I invision the program can help me while I study:
- Data processing / data preparation (Words for generator - tagged for part-of-speech)
- Web development (+deployment)
- Front-end development (which I have very little experience with beyond my love (read: HATE) relationship with TKinter
- Database (I wan't to make people able to judge each generated name, and store that information)
- Supervised Machine Learning (I wan't to train a name-producing machine on the data I will hopefully be storing in a database to eventually be able to generator THE BEST NAME OF ALL TIMES)
SO yeah, that's the plan! 

### DAY 2 - Tuesday april 10th ###
Check in: Gonna do the last little bit of work on my temporary data for the LLC namegenerator, and then tweek my first draft of the name generator
to produce the different word patterns I decided on yesterday. 
IDEA: Se if there is any data from sentiment analysis about the "funnyness" of words, which might be an interesting property to consider in generating names.
Check-out: Ending up spending more time than I first imagined on the data preparation file, that I didn't get to work on the actual name generator.
Created a github repo for the project (lineaba/LLCgenerator), and uploaded the prepare_data code to it, together with the L-words and C-words file. 
Also decided to starts a questions file in this repo, with more general python questions that arise during coding, but that I wouldn't necessarily wanna have to research to answer straight away
I include an example of where the question arose for me in actual code, and mark it with the #$$$[texthere]$$$# in code, so I can refer back to it later.
Reflection: I was giving myself a 30-min timeframe today, and was planning to do some work in preparation for my bachelors tonight, and I was debating whether I should do one or the other(the other being coding) tonight
Ended up deciding to start with 30 mins. of code, and even set a timer, but when first I got started it was very hard to stop again when the timer rang. I will have to keep this in mine when planning my day (and find a balance, cause I am sure the same thing could've happended the other way around,where I got really into bachelor's research and didn't get around to coding before it became to late.

### DAY 3 - Wednesday april 11th ###
Check in:  working in my time on morning commute and before class. Not ideal, but better than not putting in time this morning.
Will work on first draft of name generator to fit the word patterns
Check-out: Did not get a full 30 mins in, but a little is better than none, and I have a very packed schedule today, so I am just happy I got some done
Worked on importing data from the two word-list files to name-generator. Also wrote a first draft for a recursive word-picking function (ensuring that the two l-words will not be the same)
However, I haven't tested it yet, so it might need a lot of reworking. I sense that my thinking about recursive functions have been so influenced by C++ and that I am confusing myself a bit in python, 
because I can't fully conceptualize the passing of data on the fly. I might wanna find a source to brush up on recursion in Python. 
Reflection: I wish there was a way to say "God Arbejdslyst" in English - good luck just doesn't feel like it cuts it. This is niot luck, these are people working hard to achieve a goal!

### DAY 4 - Thursday april 12th ###
Check-in: Unfortunately, I'll have to chop my 30 mins into chunks today. I am planning on adding the word-order patterns to the LLC name generator, and produce output randomly that fits one of the 3 current patterns. 
Check-out: Was able to actually carve out a full 30 mins later in the day, after having done a shorter burst of work earlier in the afternoon. Definately getting more done when I have full 30 min period, so I will try and do what I can to ensure that.
Worked on making the LLC generator able to generate names following 3 word-order-patterns, which is now working, and the names are quite great, honestly. 
While working, I realized that the wordlists didn't contain any adjectives, turns out adjectives are not tagged with "a" in  the dataset, but with "j". Get to know your data-set better, I guess. So had to make small changes to the dataprep program. 
Still need to work on some things, but I have made some progress, which is nice. 
Reflection: Procrastinating on something else is a solid way to force more time onto coding, but probably not the best idea in the long run

### DAY 5 - Friday april 13th ###
Check-in: I am exhausted, have had such a fun day at six flags, but now I am ready to put in my 30 mins, working on writing a better function to shape the progressive form of verbs from my dictionary. 
I actually took a little headstart in the bus, finding some rules to use for the algorhitm, and then starting to write some code. 
(later) check-out: Almost fell asleep while I was coding, but I did manage to write a few lines of code, dealing with some of the progressive rules. Definetely not my most focused work, but I am satisfied that I pushed thorugh and did some, despite how tired I was.

__Saturday april 14th__
I completely forgot to code saturday. Sunday will be day 6, extending my 100 days by one day

### DAY 6 - Sunday april 15th ###
Check-in: I have joined an accountability group with other codenewbies Scooter, nabheet, clifton and Marshall. Today I am coding for 1 hour, to get my self strong back into the game. I am continuing to work on the progressive form creation in the LLC generator. 
Check-out: I ended up spending waaaay more time than alloted, but it weas great, had fun. Spend some time on researching how to best handle the progressive form of verbs. I ended up going by the three step heuristics, using the CMU pronounciation dictionary to look up pronounciation patterns when needed. 
However, decided that the best solution would be to create a dictionary file with l-verbs and their progressive form using the heuristics (I have written a program that does this), rather than create the progressive form of the verb on the fly. This is due to the fact that it takes rather ling to look up the stress patterns since the CMU dictionary is large. There are not that many cases where this look-up is needed, but it sucks to have those cases being SO much slower than the other cases. 
Anyways, there is probably room for improvement here. Also, I need to describe all the code I have currently, before I forget the reasoning behind all my choices. I know I should be doing this while coding, but it is a very hard habbit to get into. 
Reflection: Favorite result of running the LLC generator today: longtime losing candidate

### DAY 7 - Monday april 16th ###
Check-in: I have been sneaking in blocks of time on FreeCodeCamp today, it is SO adictive! Whoever decided to make each challenge such a small bite, hit the exact same nerve as a good netflix series ("Just one more!")
I was planning to go to the python meetup today, but needed to fix some real-life stuff, so instead I am putting in my 30 mins tonight, working on the progress-keeper in TKinter. Wanna add a document as a simple database for saving the day-count, and wanna add a window that opens if it is the first time you run the program, where you can add your name, and a color, etc. to personalice the window. The information given at first use, will also be stored in the document database 
Check-out: This is it for the night - I have made some more plans for the actual layout and progress of the app. Had to get back into TKinter. Have made the initial window, which asks whether user is new or existing.
Reflection: I hope I can keep being as eager about putting in time for coding, as I am currently. 

## Week 2 ##

### DAY 8  - Tuesday April 17th ###
Check-in: Finished the jQuery part of FreeCodeCamp today, and getting ready for my first project - building a TributePage. Just gotta decide on whom. However, tonight is about progress-o-meter, I'm gonna continue working on the starting up part.
Check-out: Now have input of user's name, and if they are a new or returning user. Should look into trace function belongen to IntVar, StrVar, etc.
Reflection: I am defenitely not doing this project the best way, or even the right way, it could probably be done a million times easier with other languages, frameworks, etc. But it is not the important thing. The important thing is that I am doing it. And I am learning. And I can always change it, and rewrite it, etc. 

### DAY 9 - Wednesday April 18th ###
Check-in: Carving out extra time to work today. Will be spending 30 mins playing around with some layout for my FreeCodeCamp legacy page. Then an hour working on the progress-o-meter. Wanna finish the set-up part, i.e. creating a .txt file(or grabbing the file if already excisting), with the users information. I might also try and look into the trace function for IntVar, and how I can use that in the project. 
Check-out: Lot of good work today. Did not work on the FreeCodeCamp, because the page have been down, and I was more excited about working on the progress-o-meter. I am done with the set-up part. It works for both new and returning users. I have a bunch more ideas of additions and imporvements I can do to it, but before I start working on that, I definetely wanna clean up and comment the existing code, so that will be the task for the near future. 
Reflection: I am considering to open-source the idea, and see if I can find some other contributers on Twitter. I think it would be a nice way to better learn how to work on git and github.

### DAY 10 - Thursday April 19th ###
Check-in: Putting in a quick 30 mins session today, before going to a comedy show. Gonna work on a few smaller fixes on the progres-o-meter, such as disabiling the button when 100 is reached. 
Check-out: Input-button is disabled when max. number of days is reached. Started to research standards for documenting code. 
Reflection: Note to self. Document as you go. Having to write docstrings for entire program in one sitting one of these days. Would've been more ideal to write for each, as they were added

### DAY 11+12 - Friday April 20th, Saturday April 21th ###
COPY OF TWEET FROM THESE DAYS: 
#100DaysofCode day 11+12 entangled. I started working yesterday at noon, and it is now 4.30 am. I have gotten so much work done, and now I am just excited to see who will be joining me! https://lineaba.github.io/prog-o-meter/  @moferg0 @cliftonC76 @ScooterPhoenix @nabheet @nayonna1

1. Calling all #CodeNewbie and #100DaysOfCode doers looking to join an #OpenSource project. Now is the time to join Prog-o-meter. This is an #OpenSourceNewbie project, that I have started, to make it AS EASY AS POSSIBLE to get started contributing.
2. The Prog-o-meter project is about writing code together, learning together, failing together and having fun together. I have spent my entire day setting up a barebones repo on github, based on a project I had been working on in #Python and #Tkinter for a couple of days on my own.
3. I hope you will join me. Prog-o-meter is a program to graphically track one's progress during a #100DaysofCode challenge. It shows you how many days you have completed, and how many days you have left. But it can do so much more, if YOU wanna help me.
4. More
I have tried to write the issues clearly, and give some suggestions for how to solve them. Some of them are labelled #GoodFirstIssue, these are written how I had hoped they would look when I was looking to join a project. For longer challenges, check out the #enhancement issues
5. I look forward to meeting you all on github. Check out the repo here https://github.com/lineaba/prog-o-meter …, and follow the simple step-by-step guide on how to get involved, even if it is just by leaving me a message to say Hello. Message me, or comment your github username, and I'll add you
6. Check out a description of the project here https://lineaba.github.io/prog-o-meter/  I will be working hard to keep adding more simple explanations on how to get involved, but please don't ever hesitate to contact me here on twitter or on github (@lineaba) if you want help getting started.
7. I have learned SO MUCH today, literally using git for the first time, setting up the repo, documenting my code to my best abilities, etc. But what I really wanna learn is to cooperate on software development - If you wanna learn too, please JOIN ME, either of us can do it alone.
8. Finally, if you are an experienced #Python developer, or #OpenSource wiz, and you have a little time you can spare on mentoring or advising, please reach out! We will be grateful for any help you can give us. #CodeNewbie #100DaysofCode @CodeNewbies

### DAY 13 - Sunday April 22th ###
BELATED LOG

I spent some time on the prog-o-meter communicating with new contributors, and had the happy experience of merging the first couple of commits - Exciting stuff. To get some actual lines of code in, I did a challenge from exercism.io, counting occurences of words in a string. Had a little struggle with the ' which I needed to remove, when it was around words, like 'apple', but not when it was inside words, like don't. Didn't have enough time to solve that, but handled all the other cases pertaining to special signs, and I will return to solve this problem at some point. 

## Week 3 ##

### DAY 14 - Monday April 23th ###
Check-in: Have been keeping up with the contributors on the prog-o-meter today. A couple new merges, and a lot of good suggestions in the issues. I have a merge conflict to solve tonight, and hope to be able to work on a flow-issue in the code myself tonight, but it depends on how much time I have to spend on the merge issue. 
Check-out: Did not get much actual coding done. Reviewed commits to prog-o-meter project, solved the merge conflict. Luckily it was a simple conflict, could solve it in the github browser, did not need to deal with the commandline and vim!
Reflection: I am impressed with how fast we are getting lots of things done on the prog-o-meter. I just wanna make sure I still keep coding for it myself too. Tomorrow I will start out the morning coding. Solving the little issue about the code in line 130 (unused variable in for-loop), and the flow (preselecting one of the radio-buttons, keep the window popping-up when the user haven't added a valid name, shutting down the entire program, if user closes one of windows with the x in the corner). I might not have time to solve all these issues, but this is the order that I am progressing in. 

### DAY 15 - Tuesday April 24th ###
BELATED LOG

Spend 45 mins. in the morning researching and testing out some solutions to the radiobutton problem for the prog-o-meter start window. Didn't find a solution, but learned about IntVar. More maintaining work for prog-o-meter

__Wednesday April 25th__
Super busy day today. Did some maintaining work for prog-o-meter, but didn't actually have time to write any code myself, so I will not be counting this day. 

### DAY 16 - Thursday April 26th ###
Check-out: Plenty of maintaining work for the prog-o-meter today. Finally solved the radio-button issue. I had been to focused on making a fix that fit into my current version, instead of taking a step back, and looking at the actual intention for how the buttons should be used. Instead of having one of them being selected as default, I just needed to remove the submit button, and instead make the close_window function belong to the radiobuttons themselves. That way the user can't move in the flow, without choosing new/returning. I still need to fix the problem that they might click the red cross to close window, and then they shouldn't be taken further in the flow. That will be for tomorrow - I think I have a pretty good idea of what to do. 
Reflection: I haven't been so good at updating my log these last couple of days. I wanna be consistent with it. I do think it helps focus my attention on my goals, long- and shortterm.

### DAY 17 - Friday April 27th ###
Check-in: Trying my hands at creating a webapp with flask today. Hoping to use it for the LLC generator.
Check-out: Started working through [this](https://www.tutorialspoint.com/flask/index.htm) flask tutorial. It had a good balance between explaining things, and having me building things. As always with tutorials, it got frustrating when I ran into cases where my machine didn't behave like the tutorial said it would. I gave up at one of those points, but before that I had solved a couple other difficulties while working thorugh, so all in all I am pleased.
Reflection: I had such a frustrating experience with the tutorial, which all of a sudden switched vocabulary, or introduced vocabulary it hadn't used before. It just expected me to know what they meant by server, without having used the word in the tutorial at all. The action I was supposed to perform, I had being doing multiple times, so it makes sense they expected me to be abnle to do it. But note to self: A good tutorial does not introduce new terms for previous tasks, without giving a proper introuction to the term.

### DAY 18 - Saturday April 28th ###
Check-in: I'll keep working thorugh the flask tutorial today. Gotta see if I can get past the annoying part where I can't get the results I am supposed to.
(forgot checkout) 

__Sunday April 29th__
Kayaking and midterm studying today.

## Week 4 ##
### DAY 19 - Monday April 30th ###
Check-out: It was very hard to find time today, but I managed to work on HTML for a tribute side today. 
Reflection: It is amazing to me that even when I have such a busy day as today, I wanna code. Code doesn't feel like a chore, it is still something fun that I am looking forward to everyday.
