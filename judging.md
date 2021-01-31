---
id: judging 
title: Judging
---
# Judging

There are any number of ways you _could_ do judging.  Most of them are bad.  There is really only one _good_ way to handle judging.

# TL;DR
* You need to have ceiling(# teams/3.3) judges
* You'll do two rounds of judging
  * Round one:  Expo style
    * Each team gets to present for 8 minutes
    * Each team will get to present to 2 judges independently
  * Round two:  Theatre style: 4 minutes
    * There will be 5 finalist teams
    * Each team gets 4 total minutes, 1 minute of presentaion, 3 minutes of demo
  * After each round of judging, the judges will deliberate for ~30 minutes

# Details
## Discussion

In the end, this turns into a simple math discussion.  You need to provide A minutes of judging for B total teams.  Now, the traditional method of doing this would be to take B total teams and multiply it by C minutes to come up with the total amount of time for traditional theatre style judging.

This is a train wreck for any reasonable value of either B or C.   At the end of 30+ hours of hacking you're now asking people to sit through B*C minutes of serial presentations.  You're worried about that total time so you end up reducing C to the point that the teams that have been working this whole time feel like they didn't get an opportunity to really present what it is they accomplished.  Now they're irritated and less likely to come back next year, and you have a cycle of decay.

Or, you don't reduce C.  You now make it so everyone there has to sit through 1+ hours of presentations that are less and less interesting as time goes on, and they are less likely to come back next year, and you have a cycle of decay.  (No, I didn't cut-n-paste that).

## Criteria

You should spend a lot of time thinking about your criteria for judging.  Regardless as to what you come up with, you absolutely should do the following things:

* Specifically call them out to the teams at the beginning of the hackathon
* Use the same criteria for round 1 and 2

## Round 1 - Expo Style (aka Science Fair)

The first round of judging has a couple of goals: 

* Ensure that the judges have enough time to really know the projects. 
* Ensure the projects have an opportunity to present more than C minutes.
* Try to make sure that the most deserving projects make it to Round 2.

To this end, you have another math problem to solve.  To maximize the chances that you have great outcomes you have the following constraints:

* Each team must be seen by at least two judges
* The two judges need to see the team independently to avoid skewing the perspectives
* The judges need enough time to credibly evaluate the teams

The math now looks something like:

* You have D teams
* Because each team needs to be visited twice, you have D * 2 total visits to account for.
* You need to get round 1 done in E minutes. 

Let's take a brief step back and figure out how you would calculate E.  

* You want the entire hackathon to finish by time Z (for the sake of this example, let's call that 5:00 p.m. or 1700.  Why?  Because after two days, most people are more than ready to be done by then.)
* Award presentation needs to start by about Z - :15 (unless you're a super chatty group)
* A good rule of thumb for judge deliberation at each round is 30 minutes.  This means round 2 needs to be complete at Z - :45 or 1615.
* Now, round 2 is bounded by the total number of teams in the finals (Y) * their presentation time (X) + 1 minute for transition.
  * My recommendation on this is 5 teams * ( 4 + 1 ) minutes = 25 minutes.  For the sake of simplicity, let's call it :30, which is 1545.
* This means that Round 1 judging deliberation goes from 1545 to 1615.
* E is now the time between when the hackathon ends and 1545.  In our experience a good stop time is 1430 with a judging start time of 1445.  This means that E is now 60 minutes.  Feel free to adjust, but this will get you in the ballpark.

Now, back to figuring out two critical things:  
* How much time does each team get?
* How many judges do I need?

It's just math.

In our experience, having each judge get 8 minutes with each team, plus a minute of slack for tallying and moving to the next team works well.  That's 9 total minutes.

You have 60 minutes to get D*2 visits done.  

60 minutes / 9 = 6.67 visits per judge.  You are time limited by the max of that, so it's now 7 visits per judge.  7 * 9 = 63 minutes, which is close.

So now, you need F judges, where F is calculated as: 

* Total Visit time = D Teams * 2 visits * 9 minutes == D * 18 
* So for 60 minutes, you need 60/18 == 3.3 teams per judge

So, the example math now looks like:

* 20 teams / 3.3 = 6 judges
* 30 teams / 3.3 = 9 judges

So, now you can tell that you want a lot of judges.  How many may vary, but it's hard to have too many.

## Round 2

This is far simpler.  Now the goal is to have the finalists (recommendation is 5) present to all the judges.  The good news here, is that is bounded by the number of teams (F) and the presentation time.  

* Our recommendation is that presentation time be 4 minutes, broken up as:
  * 1 minute of presentation
  * 3 minutes of demo

You *need* to emphasize demo here, otherwise the question is whether or not a team just created slides or a working product.

If you go with F teams and 5 minutes the number of judges doesn't matter, since they all judge at the same time.  F = 5 * 4 minutes + slack time puts you at about 30 minutes, as laid out above.


