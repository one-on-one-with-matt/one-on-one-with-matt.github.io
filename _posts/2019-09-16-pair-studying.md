---
layout: single
title: Pair Studying
permalink: pair-studying
author_profile: true
read_time: true
comments: true
share: true
---

[![YouTube](http://img.youtube.com/vi/nw7tXpBNHKM/0.jpg)](https://www.youtube.com/watch?v=nw7tXpBNHKM)

## 6 Ways Pairing helps your Study time

![volume](/assets/images/posts/volume.png)
### 1) Communication
We're talking about how well you communicate the intent of your software through the code itself here.  Communicating well in all contexts is important, but communicating through code is something unique to software development, and something you need to practice, a lot.  [Uncle Bob says](https://cleancoders.com/) that its more important to communicate our intent through software than even have it work.  When you communcate well, you open up the possibility of others helping you to get broken code working.  Code that doesn't communicate its intent well is yours, and yours alone to deal with.

Good communication skills are an efficiency multiplier.  Every challenge you will ever concievably face will be helped by strong communication skills because through communicating clearly, you open up your co-workers and social network to help you.

#### What about the other type of communication?
What about verbal communication?  Surely, pair studying helps us improve the way we talk about code.  Absolutly!  Being able to talk outloud about our code improves our understanding of it, and also boosts our confidence in our own abilities.  When you hear yourself describing code, you know on a deeper level that you understand it.

### 2) Keep it clean
Double check the information you load into your brain.  Once something is in there, its harder to unlearn than it was to learn the first time.

Also keep in mind that the first way you learn to do somthing is much more memorable than that you learn later.  For example, we used to teach traditional for loops at Learn Academy during the first week of class.

```javascript
const someStuff = [...]

const filteredStuff
for(var i=0; i >= someStuff.length; i++){
	if(someStuff[i].length > 2){
		filteredStuff.push(someStuff[i])
	}
}

// vs.

const filteredStuff = someStuff.filter(item => item.length > 2)
```

After a few cohorts got into their 4th or 5th week, we noticed that everyone was still using the for loop instead of map, filter, sum, and the rest of the more convienient higher order functions we taught during week two.  Its better to learn the more modern map and filter, then go back to learn the for loop.  With a study partner, you are twice as likely to recognize situations like this, and study the right things first.  In the end, you'll save yourself an enourmous amount of time.

### 3) Cross Training
When most people first sit down to learn how to write code, being purpose driven, they have a specific gaol in mind.
>  I want to learn Javascript so I can use animations on my website

or
>  I need to learn Swift to build a mobile application for my business.

All well and good, those are the kinds of goals that get you headed in the right direction.  Soon after though, it becomes clear that coding is a very social activity, and the number of tools required to collaborate effectivly grows.  Some tools, like Git, have a steep enough learning curve of their own that they need to a study plan of their own.  But, why not use the time we're already studying to master the communcation tools as well?  Much of the learning curve for the tools we need to do our job is centered around forming good habits, and habits are only formed by doing them over and over.  Our study sessions are the perfect repetitive environment to get this practice in, and when we have a pair, it forces us to use these communication tools.

#### Master Git
Make sure you use Git tools as you are studying.  Git is nearly universally used among software developers today.  You have to know how to use it in both your day to day activity, as well as in those thorny situations where Git and Git alone can save you.  You will never get a chance to find more of those situations as when you are still learning.

#### Collaboration Tools
Use Collaboration tools like Cloud9 and T-Mate.  Remote work is very common these days, and they *will* be useful throughout your career. Why not learn them now while you are studying other things?  Then when you get the chance to work remote, or work with someone remote, you'll already be comfortable with the environment.

![brain funnel](/assets/images/posts/brain-funnel.png)
#### Emotional Maturity
How do we give feedback in a way that it is recieved as you intend?  Its an important skill, and one you work on everytime you study with someone else.  Everyone you ever interact with will appreciate the effort you put into learning how to make them feel valuable.  When we're learning new technologies, we often feel particulariy vulnerable, so through your study partner, you're learning how to deliver feedback and suggestions in a way that is heard and well recieved.  The skills you gain here are going to improve every aspect of your life.

![string on finger](/assets/images/posts/string-finger.png)
### 4) Intensity is Memorable
When you study with another person, you are more engaged.  When you are more engaged, it is more mentally consuming, and more memorable.  So, in short, working with a study partner is more efficient because you'll remember more of the material you cover.

![compass](/assets/images/posts/compass.png)
### 5) Talk it through
##### Your pair is a compass.
Its just more efficient to study with someone else.  Are you studying the right thing?  Are you studying the right materials?  All great questions, and better answered when you can talk them through with a study partner.

![car bumps](/assets/images/posts/bumps.png)
### 6) Smooth out the bumps
With a pair, you have double the experience than you do alone.  When you run into a topic you aren't familiar with, you can lean on your pair who may be able to explain what is going on.  Even if neither of you have seen that topic before, studying is better with a pair because you can break the task down into two smaller tasks.  One person focuses on application topics like syntax and logic, while the other explores the context and broader application of the subject.

By breaking apart these two aspects of learning a technical subject, you one of the hardest parts of learning something new.  For many topics, its hard to understand it before getting your head wrapped around both the application, and the theory of it.  With a pair, you get to that point much faster, and study work done from the more solid foundations is much more fruitful.
