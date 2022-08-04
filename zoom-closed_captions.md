This text is being provided in a rough draft format. Communication Access Realtime Translation (CART) is intended to facilitate realtime access to oral and aural communication. It is not meant to produce a verbatim record of the proceedings.

I guess, David whenever you want to start?

>> DAVID PALMQUIST:  Okay. Welcome everyone my name is David Palmquist and I am serving as a facet facilitator for today's session. In a minute I will turn things over to our official meaning, but I want to cover a few logistics before we get started. I would like to start by thanking our starters, and the Gordon and Betty Moore foundation. Today, we have zoom helper .

>> There you go, thank you.

>> DAVID PALMQUIST:  So, if you have any issues with zoom, please send a direct message to Brynn if for some reason you get removed from the room, you can post a message in the carpentries like workspace or email CarpentryCon@ carpentries.org  today's session is in closed captioning. Please select  life transcript. A portion in today's session will be recorded, the recording will be uploaded to increase accessibility for the session. For the members

from the community unable to attend. If you don't want to appear in the recording, please turn off your video. You can change how your zoom name appears by clicking on the three dots on the image, and changed the name. We will let you know when the recording stop. We use the- pad for collaborative note taking, I will drop that into the chat shortly. Everyone is welcome to take notes in today's session,

please sign in as well. If you have a question, you can raise your hand using the zoom feature and will try to call on you. If you have recently attended instructor training are going through the checkout process, attending this session get account as your community discussion. If you would like to use this session for checkout, please send an email to instructor. training trainings.org  with checkout in the subject line. Put in your name and the data session. Carpentry is an event

, you must- code of conduct. I will add to that link to the zoom chat as well, shortly. And you can find it there as well as line 22 in the-. Just as a little bit of a note on that, of course we use- language, we would like to be respectful for different viewpoints and expenses.- criticism and focus on what is best for the community. Show courtesy and respect to work

towards other community members. If you believe somebody has violated code of- you can- committee by completing the form which again I will add it to the zoom chat shortly. Or you can send a direct message to myself in the zoom chat. Does anyone have any questions before we get started?

>> DANIEL CHEN:  I think either- went down. But, we can use that link instead. I will eventually get some of the initial text in there somewhere. But, we can use that collaborative doc  for now.

>> DAVID PALMQUIST:  Okay, so for zoom helper good start the recording and turn it over to Daniel to his presentation. Thank you again for coming.

>> DANIEL CHEN:  All right, hello everyone. Welcome to today's course on sort of the git  skills for the current carpentry materials. So, there is a bit of a prerequisite knowledge, which is hopefully you know how to add commit push and pull to github, and sort of use that as a starting crown. Give me one second.

>> I don't think you are able to-

>> DANIEL CHEN:  Oh, I just did the captioned thing.

>> Okay, perfect thank you.

>> DANIEL CHEN:  Okay, cool. So, I think there is half the room right now is facilitators and the other half of people who are attendees. So, I guess I will start off with my introduction and then I will skip over to all the other folks. So, my name is Daniel, I am currently a postdoc teaching fellow at the University of British Columbia. I am also- educate her at her studio which just got named renamed to- I am looking forward to sort of gone over teaching the

git  skills. Next on my list for participants, I have Irene, and I guess you can introduce yourself if you are maintaining for current carpentry lesson. If not, then it is totally okay.

>> Hi everyone, I am Irene- listen in Spanish, I am in Mexico City, so it is a little bit late here and I might need to drop off a little early.

>> DANIEL CHEN:  Yes, thank you for joining. I am on the Pacific coast, Pacific time zone as well. So, it will get laid. All right, next is Liz.

>> Hi everyone, actually I think I'm a maintainer on soon to be archived- lesson. However, my interest here is as a member of the carpentry curriculum advisory committee, and also looking to- my git  skills. From Sydney Australia, I think that is a bit of background for me.

>> DANIEL CHEN:  All right, and then last is Noel Reid.

>> Hi, I am is Noel I am in the University of Oakland- New Zealand. I am a carpentries instructor, interested in I guess getting involved in contributing maintaining getting lessons, that is why I am here.

>> DANIEL CHEN:  All right, cool. All right, so I put in let me also open up this big all right, so in the code- I put a link to the original- pad and copy and paste as soon as it starts working again. This is the link to the- carpentry git  lesson. Treat this as a foundation, if you need something to review later on. The thing that we are going to the old on or try to explain is really

this part of maintainer on boarding lessons, so if you are a new maintainer, you may have gone through this set of curriculums where one of the lessons or one of the episodes is the infrastructure for lesson maintenance episode. And here, you will see this little document or disfigur  about the components how depositories are related to one another and the thing we are really going to be focusing on is this top row,  Up here

where you are the maintainer, you have to worry too much that everything is instinct as a contributor. We might have questions later to answer those. We will be focusing on the mechanics of how to work through git  and github as a maintainer. What that really means is you have the right permission directly to the repository. So, the weight we can do it in today's course is

we can sort of mimic that behavior by creating our own repository and being able to write to that. So, you being a maintainer is essentially very similar to you working on your own private repository. And if you are going to collaborate the way I explained collaboration is you can collaborate with yourself and just pretend you forgot everything your other software. And so, a lot of the mechanics will

be the same. All right, so for our first exercise to get started because we all need to get something working on our computer. We will spend about a couple of minutes. Just give me a plus one in the chat when you are done on just the this set of instructions. So, we will get to get help, create repository, I like having- depositories with the date in it. So the names do not clash and is it nonacademic it is easier to teaching repository if there's a date. With this

name, pull it down to your local computer edit the readme file, and if you want you can change the title to the name of this skill upgrade and push those changes up to github. And I will do a small review of the basics course or the software company treat git  class, and will have a foundation for today's skill up workshop. We will take about five minutes to get that all ready and

when I see enough pluses in the chat, I will just continue.

>> It looks like etherpad is back up..

>> DANIEL CHEN:

>> DANIEL CHEN:  All right I think that was five minutes. I looked at the wrong clock when we started. I will go over the exercise. So, we will first take go to github.com  and create the repository. And we are going to create a new repository.

>> Hi Daniel, I just want to make sure I think the screen shared right now-

>> DANIEL CHEN:  That is very true. There you go. So, if we go to github.com  we should be able to create a new repository by clicking on the new button on the screen. And we are going to give it the name of today's date in see seat 2022-git you can  choose readme file, since it had you fill in some text. But, we will just create a file

with this right now. It is a good practice if you are working with a software project, you sort of have some kind of ignore file. We are not really going to be programming with anything today. So, there's really not much to ignore. But, I will pick a language. For Python, so there is something in this particular repository. For license file, also it is a good practice in all of our lessons should have a license file attached to it. Before this particular class, I will end up picking the

creative Commons license. So, when we create the repository github will do its thing and because we already have this readme.md  file ill will render on this screen. And so, next is to bring this down to our computer so we can put on the clone button, click on one of the URLs here. I believe I should have an  Q- go to some  folder on her computer, it is good to have the repositories on the folder git  and get your subfolders as needed, get

git  folder to restore your version control projects. So, we will bring down the project by using git  clone and the URL we copy, and bring down this particular repository. And we can then cd  into this repository. And one thing if you are on a Windows machine you will see that the branch name already showed up. But, we can also say git status, you can see that we are on branch mean, there is

a connection with origin Maine, which is the origin we climbed down from and everything is nice and clean. If you look at the contents we would just have the license file and the readme file. And if we look at any of the hidden documents, there is the . git which controls all the file that git will ignore. So, that is the very very literally three-minute summary of the software  carpentry class. And so, we will sort of use this as

open all, not yet, actually will use this as a starting point. In the software carpentry materials, we pretty much exclusively work out of the terminal, but since we can sort of not do that for today's class, which is kind of a good thing. I am going to open up the Xcode and go through the text editor and using the git terminal at the same time, since this is probably a little bit more realistic from to how we are actually going to be working in real life. So, in the vs  code terminal or if you

know your project is in our studio project or something, you do have the option to open up a folder. And so, the folder that I am going to open up is in this git folder. And the folder that we have cloned down. And so here, we have this readme file on the left-hand side that represents the same readme file that we closed down from github. So, the next part of the exercise was to edit the readme file, such that it said

this block of text or some other block of text. And I will just put the etherpad link in there as well. So, we make some kind of editor this file. If you are using some kind of IDE, for example VS code you will see here on the left-hand side, that there is like this M for this file has been modified, you also have programs like this version control like tab, where you can add or look at files like straight in the editor. But, if we were to follow the

git materials from the software carpentry lesson, what we would do is we would type in git status, it will tell us we are on the main branch and this part is telling us what files have been modified. This part showing up in red is exactly the same thing that we see here, where there is this little M telling us that this file has changed. So, to complete the cycle and review what we can do is we can say git added, readme.md

and because currently I am on a Windows machine it is telling us that that the line endings will be a little bit modified, but that is okay. Before we run git status again, it will say hey, this file is now what is known as staging error. So, just as a smaller recap. In git, if we have one safe commit point, and we want to get to another safe commit point, the process right now is we started with the readme file. We make some changes,

the weight we tell that we are going to make the weight we tell git that these are the files that we want to create a snapshot of his running this command called add.  And it goes to what is known as a staging area. And so, in the staging area right now, if you look at our terminal, this part in green tells us these are the files that are in the staging area. And so, here if we want, we can tell whatever command is written here to on stage

unstage  so you realize you want to take it out, depending on your version of git and this particular version here will be different. But, essentially whatever shows up in this part of the output will tell you how to take something out. So, we have the readme file in the staging area and the way we make this actual save is using a command called commit. And so, the weight we tell and create that snapshot is we git commit. Typically it is common

to use the -m  flag so we don't have this random text editor show up and write the command message that way. And also commit messages are really sore. So, this is a quick handy way to type of really quick commit message. And so, right now we are going to say, change title and add etherpad notes. Another thing that's  that you can think about incorporating

into your workflow is this motion of conventional commits. And really this is just some structure if you choose to incorporate it. Where is it? Hm. This used to be on the front page. Okay, so it is really just some convention or structure to add to your commit message. So, it begins with this type and colon. So you might say fix, breaking change, whatever makes sense to your lesson is something that you can

do or incorporate into your lessons. And so, one thing that is also pretty funny to see sometimes is this thing called tour, which is not really a big feature or fix, it is just something that you are doing. And so, you will see a bunch of chores that is happening or documentations or styles or re-factor. You can pick and choose whatever you want and pick a set of words that you will put at the beginning of every commit message just to help you filter through your output. So, we can say somethi

docs  change. And now if we run git status. Everything, all of our changes have been made and what we can do is look at the git log  and you can see this is the commit message from the thing we just created. One other useful command is running git log  with the line option and this gives you the one line option of the git history. All right, the next step is we have at this commit made. There is this imaginary thing that happens, so everything on the left hand side right now is something that ha

our computer. And then we want all of this information up in the cloud. Typically this is something like github. And so the way we communicate with github is really- which is push and pull, there is some want into this. But, for now pushing takes something on our local computer and puts it on the github computer and pulling sinks it down to our local computer. And so, just around to review, we can say git

which origin, because that is what this is telling us, but origin is the default name wherever you cloned repository from, that will by default give it origin. That does have some ramifications, but as a maintainer typically we just suggest open up the actual carpentries repo and work off of that. And so, you don't have to worry about juggling multiple repositories or remotes. So, we will push the origin, which is

are part of github, and the branch name, which is maine. Once that is done, if we go to the github page, if I can find it. Oops.  If we go to our github page, then everything would just typed will be synchronized and on github. This is going to be the starting point of rest of today's class. So, what we have or what I have planned is really showing you a couple of useful tricks

and then really trying to cover how branches work in the context of the- request which represents contributor set of changes that you would have to review. All right, so the first thing I want to show you is we just ran this command called git log  and- flag one line. And he gives us one line representation of our git history. Typically what you are also going to want to do is there is this

flag called graph, and this is useful in the sense that it will draw out these little dots and as you are dealing with branches it will literally draw out like little dots and dashes to draw out the graph. And that becomes something that is visually useful. The other parameter is this parameter called all.  What all will do, and we will soon start moving from one location in our git history to another, by default

git only tells you or shows you where you are, which is designated by head, where you are all the way down like into the past. So, there is nothing above or anything to work won't really get shown. In using this all flag becomes useful, because you get a bigger sense of actually what is going on. And so, what I end up doing, I type this command so often and I create a shortcut for it. I will type it right now and I will also put it into the code- document. So, what we can do is we can create

what is known as a git alias, because typing this every single time does get tedious. And so, what we can do is we can set an alias, so we can say git config–– global, and the weight we create that git shortcut is we write alias. And the name of the alias. For me, I personally just take this command or rename this command into L for log. Because what about more complicated command, we put into quotes the actual thing we are going to type without the git

- in the beginning. So, when I type git L, what I want to type is git log–– one alignment–– graph–– all. And so, what this allows me to do is now I can type git L or whatever I type into the part of alias command, and it will spit out or run that command for us. So, I will paste that into the zoom chat. And then, I will also put that in here. Okay. So, that is just being able to look at our history. And so, this is really just saying hey, we have all of these

commit that we are eventually going to deal with, we are going to end up synchronizing all of this work with github, how do we know where everything is? The other thing that sort of I alluded to is this sequence of commits, we have this word called maine. And it is just really refining to this linear sequence of commits. Technically, the wprd main, the reason I wrote it there is main  travels with every new commit that you make.

So, another way you can think about it is a commit is really another way to reference, sorry a branch name another way to reference this particular commit. And so, you have multiple ways of referring to this location and time. You can look at the actual hash, or you can look at or you can use the actual branch name. To refer to this location. It just so happens to be that not every commit

, for example this first one, does not have a branch essentially name associated with it. So, you can't really go to this one. Our initial commit without really referring to it as to its hash. Okay, I think that actually is like the actual software carpentries materials. So, now what I want to do is start talking about how branches work. And the reason why branches are useful is that right now all of our lessons exist in the current state and that state is the version

that is deployed to the world. And sometimes we want to be able to make changes to the lesson, if it is a typo, it is probably not that big of a deal. But, sometimes you might end up moving files around or replacing an image. Right now we are in the process of updating to a new lesson template. And so, those are changes that you want to preview ideally on your own local computer before you send it off and have it deployed

for everyone. And so, branches allow us to work in this isolated environment without messing around with the main  poor production deployed branch. And so, visually what this looks like. So, we have our linear sequence of commits. Called main. And all branch is doing is I will drop a kink here, another linear sequence of commits, but it just has a different name. So, I will call this for example b1. And the think that is a little bit confusing is a lot of people

drop it with this kink in the graph, but this representation is really the same as these three circles followed by these two red circles immediately afterwards. It just so happens that Maine is located here, and b1  is located here. In simple form, you really have one branch and it is a linear sequence of commits just like this. And what this allows us to do is if b1  it's a new feature or new episode that you are trying to write, you can write it

in isolation from the actual main  branch because you want know you may be coordinating with- and branches allow you the mechanism for somebody else to review. So, let's go create a branch on our repository and see how we can jump around and move branches. So, depending on the version of git that you have, so right now I am currently on 2.37  I believe that cutoff is some changes after

- we are going to use a command called git switch. And we are going to give it the– C flag to create a new branch. And we are going to give it a name called my branch. And so now, if we use our alias like git L, you can see that new branch created called my branch, head which is the thing our computer the state is it is now on my branch. And before it was pointed to main

but now it is pointed to my branch. So that is what the switch command is doing. It is the function in a git that allows us to move from one branch or switch from one branch to another. The– C is really just a shortcut that you end up using a lot when you are creating a new branch, because typically when you create a new branch you also want to move to it. So, this really does two things at the same time for us.

So, right now we have this branch called my branch. If we look at our actual file, nothing actually has changed yet in the actual file. So, what I can do is we can say git switch to main  and it will say hey, we are now on the main branch. If we look at our git log using the alias that we wrote, you can see it now head is pointed to Maine. And if we now look at our file, like nothing has changed, because we do not

make a commit anywhere. So, now let's see what happens if we switch back to my branch. And then, we go through that process

one more time of let's create and edit to our- file and let's commit those changes. So, I will also use this file as set of notes for us. So, the other thing we talked about is you can potentially use conventional commits. And I will put the link to that here. And then, create the other thing that we did is create an alias for our git log. This is the command, every time you see me git L, you can see this command on this right-hand side.

The other thing we talked about was running git switch– C and then the name. And so, this will do two things. This will 1, create a branch called whatever you called name. And 2, switch to that branch. So, if we save this file we will notice that the escort is time you, hey, this file has been modified. If we go into the source control you will you can see hey, this file has been modified.

And just like before if we run git status, it is going to say we are on my branch, because we switched to it. And it is going to tell us just like before, this is a file that has been modified. And so, really the only thing that is different right now is just one word. Ford it said Maine, now it says my branch. And so, we do the same exact mechanics as we did before. Right? So, going from one commit to another, we just so happen to be going from this Black circle

to our first red circle. And it just like before, the way you do that is running add and commit. So every time you want to add a commit or this pictorial view circle, you have to go through this cycle of adding and committing. So, we can do just that. We can say git added readme.md  and get the status, and just like before, this readme file is in our staging area. And it is ready to be committed. Anything that is different instead of the branch name says my_branch.

So, we can do git commit– M and we can say, docs I think I called it docs. And then, we talked about what I talk about? Conventional commits, aliases and switch. Aliases and switch. And so, now if I look at L git, this representation of what I drew before. So, we have our three commits and then the beginning of this other branch. And when you look at that graph of you, it shows up as one linear graph, right? There is not a kink that has

is being drawn. That is why it is important to understand that like, branch really is like a straight linear sequence, people dropped the branches with the kink as a visual aid. So, now we can do a couple of things. This is, for example or this can represent some kind of change that we are not totally ready for. And we are exploring. But, then maybe somebody says like, hey, can you double check that something in our lesson is

rendering properly or not? So, you need a way to go back to the lesson that everyone else sees. And so, if you go to that readme file, this contains all of the things that we just type. What we can do is we can say git switch, know Maine, and if we look at git L, we can see that head is now on this commit. This is  I putting in that–– all becomes handy, because if I have just written one line, you can see all of the stuff before

where I currently am does not show up. And so, that is why I by habit right–– all, and then–– graph gives us the little dots on the left-hand side as a visual aid. So, we are currently in the dislocation in our history. So, that means if you go back to our file it is literally in that version in history. And so, now we can explore my double check something, maybe there is another change that needs to be made. And so, this is your starting point. You are not building on top of the same branch

. Typically, you want each branch to be like one particular episode or one particular fix. And you  want to try to avoid the situation, you have one branch that has all- fixes, now you have this branch, and you have all these branches that require some order of merging to happen. And so, you want to avoid that. It is also really common to go back to Maine to create a new branch or something.

But, that is really the useful thing about branches. It is this isolation of work. Because now, you can double check something, maybe there is another change that needs to be made. And so, this is a good starting point for things to happen. One really useful command is if you are really just bouncing back and forth between two branches, what you can do is

say git switch, and then just put in a–, so you don't have to type in this whole branch thing. And all that will do is bring you back to the last branch. So, if I  say git- I can confirm that by looking on our log, and I can see it is on my branch. And the file has changed. That is useful if you are just like, I do remember what I called it because I give it some weird naming the branch, the branch had some weird name

and I keep mistyping it or something. This is another useful thing where you can represent the last branch you were on by a single dash. Okay, so we have all the stuff on our left-hand side it represents our local computer how do we get this branch on to github? And so, the way we do that again, there is really only two commands to keep in mind, which is pushing and pulling. Pushing and pulling.

So, yes there are ways where you can merge branches on your local computer. Pretty much I don't think I've ever really done that on my local computer in a really long time. And so, I almost exclusively do all of my branch management on github. And I will show you why in this example. So, the weight we work with branches is we have to push our branch somewhere

. So, the beginning of the command that push command is exactly the same as before. The only thing that is different now is we specify instead of main  week specify my branch. And so, this will do exactly the same thing as before, it will compress, send everything off to github. Because this is  the first time github is seeing this branch, you get this extra bit here, which says hey,

your branch called my branch on your local computer, it now exists as my branch in the remote somewhere. And so, that means if we go back to github, one of the things that will automatically show up is this bar it says hey, you just pushed up the branch. Do you want to compare and pull requests? If for whatever reason, like I think

there is some amount of time where this no longer shows up, you can always click on this tab. That says branches. Find the branch that you are looking for. And then, you can click on this button here that says new pull request. Whether you use the link on the front page, that little pop up or the button that says pull requests you will get to this page which is opening up of pull

requests. If this is one of the reasons why I like using the github interface or whatever system you are using, but as maintainers we are using github. What I like use the like using the github interface for merging the branches, it is because once you are on this page that says pull requests I believe it is the last commit as the title gets automatically created for you. But, if you scroll down, you have some mechanism to check

your work. So, as a maintainer you are probably the rendering your commands locally first. But, this is also another way to make sure that some file did not automatically get put in. And you have some mechanism to review your own work. And so, this is the set of changes from this entire branch. And this branch only contains one commit right now in this is that set of changes.

Once we are happy with that we can give it a proper title. I will just leave that is the body now. But we can see my first my branch review. This is something that some collaborator is typically going to submit to your own lesson or if you notice as a maintainer a change that you need to make, you will probably submit your changes as   pull  requests. In this repository you can see a pull requests. And you will see the pull request tab, you can see I just got to the exact same page when

I created any requests. And this is how you can do code review. Or really lesson review. So, as a maintainer, you have access to the green button. Typically other not maintainers this will be grayedfor them.- you can have a discussion and say hey, this looks great. Typically as a maintainer for one of the carpentries lessons and if you have noticed that if you don't recognize the github username, it can also think of them

for submitting a change. Because it is demotivating if they submit something and there is no conversation, and then it just goes away and it is kind of demotivating in that sense. But, you click on the flat tab called files changed, if you don't want to bring down their code and run it, you can quickly glance to see what is the set of changes that they just made. If it is like a small typo, most likely that is not going to break any kind of rendering

think that is going on. So, that is probably okay if you don't officially render it on your local computer. But, this is where code review can happen. So, you can see as I am hovering over there is this little plus mark that happens all over here. And so, you can click on individual lines and either say in comments, like this is really cool and new. And so, you can really start to review or add a single comment. Or

if you click and drag you can refer to a range of lines. And so, this is really useful if you need to type the command a lot. So, as you are bleeding through changes, if it is a new episode you can read through this like copyedit and say hey, maybe you want to reword this or fix that. And this is a pretty useful way to do copy editing on your lesson. And then, you can do the visual and repository rendering check later on.

And then, if you go back to the conversational view, and if I hit refresh anything that I typed in the files change will also show up there. You don't have to worry about how many files and where all the changes are going to be placed. Everything will be stored in the conversational view. And then, once there can be some back-and-forth as maintainers have some patients, like this does take a lot of

time sometimes. Sometimes people will submit new changes and they will not get back to you addressing those changes for like a week later or something. So, that is- give it some time. So  again, this is a new contributor, do tell them like do you thank  them for their contribution. And maybe this is your own set of changes? Maybe it is not. You might be ready to click this

green button to merge. But, before we do that, one thing that most people get kind of confused about is, if you want to make changes to pull  our request- the pull request at the top is attached to this particular branch or whatever is  Lifted up here. And then you can update this pull requests. So, let's say for example, I write another message that says, all you need to do is update the branch and the PR will be updated too.

Let's say I typed that note to myself. And then we go through that process again, which is saying you run git status, does it change to the readme file? We are in my branch, we will add that file to the staging area, we will write a commit message that is going to say docs and I will write something like update branch to update PR. And so, if we look at the lot, nothing is really changing. What you will see is the version on our local computer is a head one commit version of head, and that is w

that refers to the origin remote, and where does origin come from? Well, we've seen it a couple of times when we said git push origin. So, this origin is that version in that account in it that repository on github. So, we can re-push the branch, and then we push it back up. And we refresh it. We will get another commit, and you can see that the pull request self updated. So, what and the people doing is they close the pull

request and resubmitted again, and then you have a bunch of duplicate stuff in your repository. And if you  and up having a conversation with your contributor, you can link them this video or just tell them like, you can just add more stuff or add the changes to your branch, and the pull requests will update automatically. And then once you are ready there, all you as a maintainer need to do, is click on merge pull request,

click on the green button. Before we do that you will notice that there is a drop down and three other options. I suggest that you just keep it as merge create a merge commit and not go through the bottom two  choices, unless you know what you are doing. Especially this squash and merge. It does make make the commit message pretty, but if you have other collaborators and people

with other branches, like this does cause a little bit more friction and could be problematic, especially if you are other people in your group aren't very very get proficient. And so, the first option is the easiest choice for most people. So, when you do click the green button. What is going to happen is- merge into the branch called Maine,

in github. And how do I know it is called the branch mine?  well, appear in the request, it- what request- this branch is called my_branch. Now it is in or combined with my main branch. But it is only on the version of github. It only happened out here. We have these 3 commits and we had those two red commits. And those two red commit now got merged in to our main branch. The thing that you want to do as a maintainer is to make sure that

you maintain the lesson. And so one of the things you want to do is make sure that you actually delete the branch. And that is doing the maintenance work on the github side. So, one of the questions I have is, sometimes at work you follow this process of doing squash merges, and you do not know it could cause problems. It's mainly and many can cause problems, because it is also pretty common that sometimes branches

branch off of one another. And if you are not very careful, when you squash a branch to merge, the branch originally that was branching off of the squash. Sometimes merge conflicts can happen or some rebasing needs to happen. So, typically when you do squash merge workflow, you almost end up doing like another set of steps. And it is not always very clear like what exactly is going on, unless you look through

a log of what is happening. So, I do that, I do the squash merge for might work as well. But, typically what have seen in most carpentry lessons, like nobody actually does that. And again, it is mainly because like, it kind of changes bits and pieces of the history in that branch. And sometimes people get confused, where all of this stuff disappeared. But, I will talk about squashing stuff

in a little bit, because it is one of the mechanisms you have a really complicated merge conflict happening. Sometimes it is easier to squash everything together, so you have one giant merge conflict happening instead of like, five totally separate merge conflict happening. So, squashing it does end up being pretty useful as a maintainer. Especially if you don't care about like all the atomic

commits. But, so we have merged the branch on github, and again, it is really important that you click on that delete button otherwise things get super super messy. So, now the next thing that we have to do is bring all the changes back to our computer. So, what we can do is we go back to our main branch, and to get those changes back down to our computer. You say git pull origin main. And what that will do is

- branch on our local computer. There is a command called git branch– A, and it will list all these branches that you have on your computer or your local your computer knows of. And so, even though we deleted the- art machine still has a reference to it. If we look at the log, what you will see is we had this commit, we had a branch that was created. And then that branch got merged into something called

back into Main. So, we still have these lingering references that we should clean up. And the reason why we should clean it up is as more branches happen, and sometimes when things get a little bit confusing, just removing as much unnecessary clutter is can help you with fixing things. And so, there are two steps that we have to do to clean up our repository after we do a merge.

The first thing we want to do is run git fetch–– prune. And what that will do is it is called prune, because it is pruning branches off a tree. So you are printing back? Branches. So, what this means is any branch that exists on the remote side, if it has been deleted, then the reference on your computer will also be deleted. And so, if we run this, you will see that oh, it recognized that something got deleted, so my computer

will also keep track of that reference. And so, now if I look at git log,–– you can see that my branch has been deleted. And that is slowly reducing the visual clutter of things. The last step that we need to do is run git branch– d  it will delete the branch, but it won't force delete the branch. All we need to do now is say get branch– D my_branch. And that will delete the reference to our branch locally. So, if you also made a typo or something in a branch, you can also use - D  to delete it

try lowercase d  first. And so, now if you look at our history, like all of the things that don't need to be there no longer there. And we now have our main branch, our origin and this origin head is saying like, if we go to github.com into that repository what is that show? And sometimes what github shows is also different from like whatever branch name we have. And so, that is why there is another separate reference there.

Okay, so  what I will do is sort of go back to our document. And you will see that even though we are on our main branch, now everything is up-to-date. So, I am going to copy and paste my notes from what I have. And so, just as a review, this part we don't really need this extra commit, but just as a review, when you do cleanup like how do you clean up your stuff after pull requests? Delete the branch on the remote, which is on github, and then run git fetch prune, and then git branch

-d. And then I just made another change. Get to my repository, and so we are going to that cycle one more time. You do have the option, I believe to like to set up a branch protection rule. So, you saw when I sort of dismissed it and did not talk about it. But, on github it was saying hey, your main branch was not protected. What you can do is guard yourself from making changes directly on main, and the reason for that is

, this way everything that comes in has to get reviewed. So, for example if I use this particular example right now. If I add readme.md  and I commit and I say docs clean up branches after merge. All I need to do is git push origin main, and if I go to github and I go to my repository, like there was no prompt for any review process. And if I scroll down, hey this magically appeared. As maintainers you don't have to worry about your other some

collaborator who is not a maintainer during this repository, because they don't have the right axis to your own project. But, this is something that you want to be careful of, if you are working with other maintainers, because you can introduce something into the whole project and literally no one reviewed it. And so, there is a mechanism called branch protection rules, which

may be I will have time to go through at the very end. But you can set that up in your own repository, just so that if somebody were to type in this command in this process here, it will bounce back and say, hey, this got rejected. And I have towards the very end when we talk about reset, you will use that reset command to sort of undo and fix that problem. Right now, what I want to do is I will sort of gift people like

until 15? Four minutes if you have any questions or to take a little break. And for the last 45 minutes I want to go through conflicts. And then, to conflict examples. Merge conflict examples with branches. And I have like premade coded so we can sort of copy and paste this sort of stuff. And run it on our local computer, so we don't have to spend time typing it. So, I will wait until 15 to the hour for people to sort of get water and take a quick break.

All right, so I put in the codingMD  block this big block of code. Hopefully I will run it first, and if it works it should be copy pasteable   on your side. And then  I will- the set up right now is we have our  main branch, and what ends up happening is let's say for example, you work on something. And also one of your collaborators work on something.

And in the example from above, like we can go through this process where you merge in your branches. But, if there was no- if there were no any problems, for example you work on episode for for your project and to somebody else works on episode three, and you are very clear that you touch my episode when I am working on it to reduce merge conflicts. Then, when you go

through that process I just showed up by clicking the green buttons, and people talk about like the green button, they mean that  merge button. And this should- without any issues. There is also a scenario, where sometimes there is a merge conflict that happens with these branches. And it is not always apparent that the merge conflict is happening, until merger one of them. And so,

the code that I am going to copy and paste is going to set up this scenario right here. Where we have our main branch, there is two  permits on one branch, and another to commit on a totally separate branch. So, what the code looks like, you will see that we are going to be starting from the main branch. So, that should definitely be the first

that my first command will go to the first- will put some code into the readme file, we are going to make it commit, I will put another line, make it commit, and then go back to main. So, hopefully by copy and paste this, this just works. So, hopefully this even copies. Here we go. Okay, that did not error, so that is good. So, if I look at git log, you will see that we have main, and we have two commit to the file

readme.md , so for look at it, all we did is these two lines to our file. So, we are going to go through the next bit. So it is really important that you run this switch main, otherwise you end up having one branch on top of another, which is okay, but sort of it does not work for this particular example that we are trying to mimic. So, we are going to go back to our main branch. I'm just going to type it. And then, we are going to run

this second bottom block of code again. So, it is really the same thing, but all we are doing is changing the name of our branch. Okay, I also like copy too much, where I also push it up to git, but that is also fine. So, if you look at the output of that whole block of code, we start off from our main branch, we created changes in one branch, and then there was changes to another. So, either this means you yourself are working on two separate episodes, so you are working on episodes

two and three by yourself,  which is pretty good practice even though it is a little bit annoying to go from one another. But, you will be very thankful later on. So, this can be represented by you, yourself working on two separate episodes. Or you and somebody else whether it is a co-maintainer or another elaborator working on two separate things. So, on the github side, what we will see because week manually created these

pull request. We will see these two prompts. And we only see this, because we actually created these branches. But, if we go through the same process as before, and I just say create pull request, and don't click the green button for this example. Go back to the front page and make the pull request for the other one. This view, for example, you have these two branches. If I click on the pull request branches, this is probably something you will see is a maintainer very often.

Here is a whole list of stuff that you have to go through. And so, if we open each of these, I am going to open them in separate tabs. If I go to Branch 1, just like before I can click on files change and you can see changes to be one commit one, changes to be one commit 2. Likewise I can go changes to the two commit one, changes B- 2 commit 2. You can do the same stuff as before. The thing you will notice

that the conflict happens when there is a change in the same file and same location. So, if I look at any of these files, it is literally the last light of this file has commits going on. And that is a problem. But, you can see that when we go to the main view, it is a green button. It is not know that a merge conflict potentially can happen.

And so, that is one of the sort of things you want to be mindful of when you are a maintainer as you are reviewing stuff. Also pay attention to the files that are being changed, because if you just look at all, the button is green, it is not really let you know that there is a merge conflict happening. Sometimes branches the way they are coming Inc. About like that will avoid the conflict, like sometimes I can't replicate the example, but sometimes the ordering order of

your merging branches to make branches it does matter. So, that is another thing you want to be mindful of. So, let's I will open up this in a separate tab. Side by side. So, we have conflict Branch 1 on the left and conflict branch 2 on the right. If I merge in Branch 1, it will trigger branch 2  to have a conflict. What you want to be mindful as a container, sometimes conflicts don't show up until you start merging stuff together.

So now, the question is how do you go about fixing this? As a maintainer, you should if this does happen and if you are keeping up to date with like new incoming changes, typically what you can do is is a maintainer, you tell the person who submitted this change. Hey, you asked them to see if they can fix the conflict.

If they can't, because they are very new to all of this. Then, that sort of falls on you on how you can go and  Fix that. So, now the question is how do you go and fix this conflict. Typically, when- submit pull request, there is a check off- that means you as a maintainer can usually edit another persons pull request. So,

if it is a simple change, you can click on that little gray button and deal with the- and the way you do that is you literally look for the less less less, equal  equalequal, greater greater greater. And you fix this block- sometimes it is deleting the other version. Sometimes it is a mashup between the two versions that will be the final one. Your goal is to literally fix this file.

So, that is how you can do it on github. How do you go about fixing this on your local computer? So, we have this state right now where we have our main branch, we had one of our branches got merged in. And that is the new main. But, the problem is the old branch has it is still based off of this older main commit. And so, the way you fix this, is you really want the branches to look something like this, where you have main

the branches that got merged in. And then you sort of want to take these commits and start them over here. So, this process of saying hey, let me undo these commits play- and replace every single one of those commits back. That process is called rebasing. This is the way I typically teach how to fix this problem. There is multiple ways on how you can fix this problem. I find this to be a little bit

easier. But, depending on what group and if you are working outside of the carpentry, depending what group you are working with. You might not like this way of fixing this problem. But, this ends up being like the easier way, because you have less bits and pieces to clean up afterwards. So, how do we go and fix this issue? So, right now what github we have this

version on the left, right? And so, now the trick is let's go and clean up everything and pretend it was like up pull request just like before on our very first example. So, we have this whole  pull request, will go to our branch, we will go to our local computer. And the first thing that is really useful is I showed you the command called fetch. Yeah,–– prune. What is really useful about running git fetch, let's say

let's look at the log of our history right now. So this is the current log on our computer. If I just run git fetch, or with or without prune, let's run it without prune first. What it will do is nothing on my local computer has changed. So, if I look at the log again you will see that head  is on branch 2, which is on the same exact location as before. The only thing now is

the version after fetch had this other side of commits going on. So, before, when I just ran git pull, this is the only way you can interact with this, it is sort of not totally true. Because when we run git pull under the hood actually runs two commands. So, internally it runs fetch, and also merges all of the changes together. So, as somebody who is just like, hey, my computer something weird is about to happen. Let me just figure out what

going on. 1 way you can guard against just stuff changing on your computer is running git fetch, first. And all it is doing is updating this history tree. So, nothing or your computer has changed. And why this is useful is you can get sort of a lay of the land, everything of what is going on. Which is your main on your local computer is still here. But, main on the remote is somewhere else. And then, we have

this branch and this range. Those are all the pieces that are going on. And so, one thing we will notice is oh, well main, are remote is over there, but main on our local computer is here. How do we fix that? Well, we can say, git switch main. And when we say git pull origin of main, it is doing the fetch and also the merge and so,

when we look at the log, it sort of brought that back up. So, it combined all of those bits and pieces. So, now main on our local computer is up to date with everything on our remote. The other thing again, is you want to run git fetch–– prune, just to make sure any of the visual noise is deleted, so you can see that little bit for conflict Branch 1 is no longer there. And if this was something that was happening that on your local computer, then this little green bit of text

would not even exist. And so, now we are in the position of this diagram on the left on our local computer. Which is we have our new branch that is a new name branch that is all the way up here. But then we have to deal with this branch that has conflicts. So, the way that we can do that is we first go to the branch that has the problem. So, which is git conflict branch _2. Sorry, git switch.

And so, if I look at where I am now. Now I am down here. And the way we run the rebates command, we start on the branch that we are currently on, and then we git rebates, and we say what is the branch that we want to sort of fast-forward and replay are commits one at a time on top of. So, how do we go from this state on the left to the state on the right. First, go to the branch here,

then we rebates against whatever in our case main. So now, we mimicked the conflict on github. On our computer it is trying to  Altomerge, it can. Just like on github it tried to outer merge, it couldn't. Let me show that. So, github is trying to o alto merge, but it can't. so all we have to do is go to the computer that has the problem. So, it is telling us, hey, this is the set of changes that are conflicting. And right now, it is saying, hey, this one commit

is different from the other. So, maybe I say hey, I want to keep both of them. So, vs  code is nice and gives me these buttons that I can click. But, all it is really doing is you literally get rid of the greater greater, less less, equal equal. As soon as you are happy, you can take a combination of both. As soon as you are happy, or you need to do is follow the directions that it tells you right here.

I never remember on the top of my head how to do this. And so all it says is resolve all conflicts manually, how do we resolve conflicts? You get rid of that little symbols and equal signs. Add them, so I will to exactly what it says. Git rebates continue. If I spell it correctly. It is going to say hey, what is the new commit? So it is replaying the commit. So, you either have it your computer set up for nano

which is what the software copper tree do, but if you open up vin  in you hit escape Colin- control X.  I will say control O control X, and it will say replay commits. If I look at the log right now, you will see that our original what github things the branches over here, we have the branch from main and the new commit that  got replay. So, if I go to the diagram, what happens is we have at this state on the left, and we replayed it

to the version on the right. It just so happens, if you look at this part, the version of github is still out of date. That is what this part is telling us. It makes sense, because github right now has this merge conflict, right? So github is actually out of date. So, the weight we fix this formally on our computer is we run git push. So, typically people say– F, because we are going to be good citizens

or collaborators, we will use a different flag, which is force with lease origin and then the name of our branch. So, think of this as the same as forcing a branch push. But, what this is doing is in the off chance that one of your collaborators is also dealing with this particular problem. If they solved it before you or had a different change before you, your changes don't just- on top of theirs, this is saying I'm going to

force push this, but just in case somebody else also force push is something that I am not going to let you do it. So, it is just not going to clobber all over something. This is good especially if you're collaborating with multiple people. If it is just with yourself, then it just usually use– letter F. Get used to typing it.

So, if we run this, it is going to force push or force update what version is going on on github. So, if I look at the log at right now, before the git branch 2  was down here, I think. Down here? It was somewhere.

[Laughter]

oh, it moved up. I can scroll up now that I talked about that. It was down here, it is now been forced moved up here. And we see that because that reference is now in line with the version on our computer. And now, if we go to github, it would have done its own circle thing. And it is going to tell you also that there was a force push that happened. And then, once we are okay with that? We can go through the process just like before and

delete your branches. And then go through the process of cleaning everything up. All right, so we've merge that. Git switch main. And we will say git pull origin of main. And we will get those changes back to our computer. Will say git fetch–– prune to make sure all of the remote references are gone. So, I will look at branch– a, and we will say git branch– d, and we are going to delete those branches. And if we look at the log,

it will be clean. It does not have all this visual noise going on. Okay, one last example to round off this class. We are going to go through this set of examples one more time. What I am going to do is show you, it is literally going to be like at this exact same code one more time, and we will go through the first half again. But I want to show you something that can be useful if we have multiple commits on going on.

What I am going to do is actually changes to b2 , we will make three commit to make the example a little bit more complicated. And so, we will run this git again. Because I want to show you again how you can deal with very large branches that have like conflicts all over the place. And if you don't care all of that

individual commits and you want to sort of essentially I want this problem to go away as fast as possible, this is how you can sort of deal with that. So, let me copy and then paste. All right, so we are working with the same exact branch name. Again, that is okay, because we have deleted and cleaned everything up. And that is another reason why I am really

adamant about cleaning up all your branches, because some off chance when you decide to use the same name, you don't end up like jumping back like 50 years ago to some other point to git history. So, right now exactly the same set up as before, except one of these things has an extra commit. And there is still a conflict going on in them. And so, if we go to github, again we have the same exact problem as before

. Okay, it did not prompt me, but that is okay. We can create our new pull requests. Usually right here, like, right here is the checkbox that says maintainers allowed to make changes. So, that is where it would normally exist. So, I am going to create that pull request and go to the other branch in create that pull request. And so, exact same scenario as before, I am going to merge one of these branches

in, delete it, and then this branch is going to have a problem. Same exact scenario as before. The reason I am showing you this is, sometimes like this is three commit, right? And what if there was a conflict in every single one of these commits? Can you rely, I know the final version is the version I want. I do want to step through every single one of these commits this is sort of like the trick you make this problem go away. Okay. So,  we first we need to

go through the process of updating the branches. So, what is the branch that has the conflict branch 2 to has the conflict. So we have to go back and git check out main, git pull origin main, so that will update the main branch. I am also going to say git fetch–– prune, just to clean everything up. And then, if we look at the history where here and we need to incorporate these three things. And so, one thing that can be

really useful is I just want the final state of this re-based on top. I do want to go through the process of checking every single one. Because again, this is three. Maybe that is bearable. But, this can also be 20. Right? If it is coming from somebody else or yourself because you are making incremental changes. Maybe half of it is like typo, typo, typo and all of those are making conflicts for whatever reason. So, the trick that I use

I take all of these commits here and I literally squash them down into one, and then when I do the rebasing, it is just one commit. So, all of the merged conflicts for all of the files all show up at one time. And I don't have to worry about okay, it went through 3 of them, there is 15 more. How do I deal with it? So, the way we fix that is we first go to the branch that we want to sort of like deal with. So, we are going to conflict branch 2

, and so we are literally here. And if I go to might read me file, which I think is this file, where in this version which I realize is a terrible set of names. But, we are like right here. One and two and three. So, what we are going to do is we need to tell git, hey we are going to do we are going to combine a whole bunch of changes all into one. So, rebased is the actual what actually rebased means it is I'm going to

change the history for something but so, we are going to run git rebased - i for interactive, is what it actually I think it means. Hey, I will change the history. This is the history that I am going to change. And so, we have to say, like where we are. So, we will say head. And from head we will go to one, two, three. From - give me into contact the last three commits from where I am. And so, if I run this,

it is going to open up a text editor. And what this tells us is these are the three commits. And if you want to change history, for example down here. All of them says pick. So those are the three circles. If you want, you can reward one of the commits. Let's say you make a typo and you are really like, you want to make sure that your messages have the proper spelling. You can reward them. You can edit a commit. Let's say you add a file you can add more stuff. Usually you don't use any of this.

. I don't really care too much if I make a typo. The one we care about this squash. And what squash is doing is it is saying that I want to take my commit, but I want to join it with the previous commit. So, what we can do is we can literally change this file to say S or squash, you can type it out or use a single letter. And what I am going to

do is literally squash all of these commits into one. And so, this is the manual way of doing that squash and merge onto github, but this is the squashing process. So, all I need to do is again, literally edit this file to say I want to squash this with this, and this with this. And all of this get squash together. And all of these- that you need. So, once we are happy with like the squashing,

procedure, all we need to do is save this file and exit. Don't worry about what is going on. But, it is going to create a new commit and it is going to say like, this is a combination of three commits. One and two and three. So, it is creating a new commit joining them altogether. All of the old

commits are still there, see don't really lose that context of what is going on. You are just losing the actual commit, so you can actually go back incrementally to what happened, but all of the random stuff you type can be searchable if you need context. So, all this is saying is hey, I just created a brand-new commit. And this is the new one. So, again all you need to do is save this file and exit. And so, now if I look at the log, what ended up happening is

we were here. There was this conflict branch one two and three. But, we did join them altogether into this one commit. And this title is not correct, because I did not rename it. But, if I look at the file, it is correct. It is like 12 and three. So, if you look at this, what it does this look like visually? It is exact same thing as before. So, we have our three base

commits, we have the two that we merged in, right? And then we had in our case, like three commits that were purple. All we did is we turned all of these purple commits into one giant commit. And so, now we go through the rebasing process, here. We only have one giant merge conflict that we had to deal with. And so, what

does this look like if we follow the graph, we can see that this redline it started from here. So, it is still off a branch. So, what it really ended up doing is it really created another commit that was just this one giant commit over there. And so that is how we can use the–– graph. We see this one. We followed the red line, and the line does not and until here. And then we followed that redline and that is where it was before. And that is the branch that moved up and

I think a merge that happened between this branch and main. So, that is kind of like I think my font size is not helping, because this random– here. But, there is a merge that happened. So, that is why drawing this out like on a piece of paper is really useful, because it is also exactly what represents when you run git–– graph all. And so, now we are in the same exact scenario as before. Where all we need to do is say git

rebased and the branch we want to rebased. And we still have a conflict, but if this was across multiple files or multiple things, it is altogether in one place. We don't have to worry about okay, there is like 19 more commits and I keep fixing the same thing over and over and over again. You only need to fix this thing once. Which is saying changes had to commit one commit two  in commit three. If we run it get status, all we need to do as we did before is add

or read me file, and then get status and it will say  all conflicts fixed. You don't really need to worry about it, other than save and exit. And now the problem has officially gone away. And then, if you look at the log, our branch is now on top of the main branch. So, it's sort of git rebasing correctly. And then, we say git push–– force with lease origin conflict branch 2. And then, that is how we fix that problem

and this problem will go away. So, this is a pretty common thing, especially with like older repositories or just multiple old pull request that happen that are very big and if they sort of like, yet to go fix it or the person submitting it does not know what to do, because it is very daunting. This is the way you sort of deal with it. One way you can deal with it. Which is I know you have been through

all of these commits, let's just join them altogether, and just make one giant change. And then, the way and it will prompt you like here, you have multiple files, all of the files that were changed will be listed and then all you need to do is go through the less less equal equal greater greater, go through all of that once, because it was only one commit. And that will save you a lot of- merge conflicts with multiple branches. So,

all you need to do then is merge the branch, deleted, and just like before go through the cleanup process. So, check out main, fetch prune, and then delete all of the branches that you don't need anymore. So, it is branch -d  and then I will delete that. And now we have woops  git pull origin of main. Forgot to run that. Or maybe I made a typo. But,

I definitely made a typo because that is still there, but now we have all of our branches all cleaned up and stuff. So, I will actually take that correctly. I don't understand how copy and paste works on Windows. I think it is enter and right-click for some reason that works. There we go. So, now everything is nice and clean. And this is the state, if you are a maintainer, this is what you want to see. One last thing that is really useful again

is let's say for example you write hold on give me one second. I mentioned before, there is a reset command on let's say what happens if you accidentally have a branch that like your main branch is locked and you can't and you accidentally make a commit on it. So, go back to our readme file and let's talk about, we talked about git rebase - i  that was the command and head ~  something, I will say five. Interactive rebase.  that was the main take away using

rebase. Let's say I made the change to my commit file. And then we get commit and we say Doc, docs, rebase. And then we realize oh no, we may a change to main, and we made a submission. The weight we get around it it is a two-step process. First you leave a breadcrumb where you leave off. First we say git branch and then we say rebase i. And all this due is it creates branch where that is. And this is different from switch– C.

And then also switch to a most  of the time that is what you want. But you just need a breadcrumb or a marker exactly where I am, but do not change- all you need to run the regular git command and it will do that. And you can see head is still pointed to main even after we ran that command and the way we fix this problem is, so it is really common

when your thought process is, I don't care what is on my computer I don't know why git is giving me all these errors, I just want to go to this location and bring all my file, and ignore everything that happened. Just bring me there. And if that is the feeling that you have, then the first thing that you run, the first command that you run is git log–– online–– all.. one line. So, you first run this command, I was using the

short version. You run this command, and you find the hash of the version that you just don't care and you want to go to. So, for me it is going to be ae35a58 , it will be different for everybody else. And that you need person, you want to make sure you are on the branch that you want to reset and pick yourself up and go to. So, first make sure you are in the right place, I am in main and that is what I want to be.

I git reset–– hard, and the commit message that we are going to say, I don't care what happens, just bring me there. And then, I will use the little more compact version read and then it brings us there. We did not discuss any questions, any changes to your files- turn away. Sometimes that is just what you need. And the reason why this is useful is, your main is now in sync with the remote main and

you can check out this branch, and then do the whole adding, pushing, pulling, request review. If you end up having the feeling of like, stop asking me questions git, just go there. This is like your magic command. And that is how you use it. Again, you do have to be careful, if there is stuff that you actually care about, I get commit for it before you decide to up and and go somewhere else. But, that is how you sort of fix that problem.

But, yeah we have like two minutes left. So, I will sort of open this up for questions and one of the questions was how do you propose lesson changes? As a maintainer, you should have the authority to make changes that you have seen fit, you do have the authority to do that. If it is like a really big change, that is where the curriculum advisory board comes into play

, where if it is like a very large change, like you are trying to rewrite half of your lesson, that is when you need a little bit more input to be sure that it is okay. But if it is like a, I just want to make sure that, you know, make sure everything follow some type of style guide and there are some tweaks, that is okay. Yes, we have a couple of minutes. 1,  But if anyone has any questions, I will try my best to answer them.

Otherwise, that is probably the core, the rebasing and resetting is probably like the most common things that people get stuck on when I was helping other maintainers the last two years.

>> Thanks Daniel, I just want to say this was great and I really like how you went through the illustrations and get through rebasing, because I have looked at rebasing and gone ahh  people make jokes about that on twitter

[Laughter]

so I am staying away from it. Thank you.

>> DANIEL CHEN:  Rebasing is again, it is one way you can fix a lot of the conflict problems. The other way is cherry picking. And depending on the group that you are working with. Rebasing technically changes the history, so you are like you could lose context of white this- where this thing sprouted from. And cherry picking is making copies of all of the commits. So, there are 2 ways of solving the same problem.

I don't use cherry picking, because it creates another branch and you have to now deal with deleting two branches instead of just deleting one. That is just another technique that you will see other people use.

>> I also wanted to thank you. It was useful to learn all of this, especially- it was overwhelming. I can see why it is not covered and that maintainer on boarding lesson. That is great.

>> DANIEL CHEN:  Yes, I am hoping that the fact that this is recorded it will be on YouTube somewhere and part of like doing this part of carpentry, like at home or CarpentryCon, this ends up recorded for the next round of maintainer on boarding.

>> Well, thank you.

Okay, so with that, I guess I don't know, David do you have any closing remarks that you need? Otherwise, thank you for coming everyone and if you are watching this on YouTube, I hope this is helping you be a more successful maintainer.

[Laughter]

>> DAVID PALMQUIST:  There was not anything provided as for closing remarks, but I just want to say thank you for sharing your expertise and thank you for everyone for coming. I definitely find it enlightening.

>> DANIEL CHEN:  All right, I will clean up some of the stuff, the codeMD  document, and if there is any missing notes and stuff, I will just update it in the- reference material. Because I stopped editing readme file for examples. So I will trade to get all of that cleaned up and stuff as well.

All right, with that, thank you.

[Laughter]
