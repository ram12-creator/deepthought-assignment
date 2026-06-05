# DeepThought Assignment

## Part A – Diagnosis

### Situation A – The Alert Nobody Responds To

What is the stated problem?
 Answer  : The daily alert emails were sent every morning and shows red items only. Even after seeing that alerts, people are not taking action [ because they feel like they are not responsible , so]. The CEO feels he still does not have proper visibility into what is happening because there is NO responsible people directly involved.
What is actually happening?
 Answer  : I feel alerting email not a problem here , real problem is that The email is working fine technically. But it just tells everyone there is a problem , it does not tell any specific person that they need to fix it. So everyone reads it and moves on 
The tracker is only showing department names like Purchase, Warehouse like that. That does not pointing out  the name of the person responsible. Because of this, Even thougth people know there is a problem, but nobody feels personal ownership to solve that.
Because of this, the same red items keep appearing every day without any action and if it goes like that this issue never solve .
Evidence from the scenario
 Answer  : The advisor clearly pointed out that the tracker showing only department names not individual names of that department , in addition to that , he also mentioned when a task is assigned to a department, nobody feels pressure. But when a person's name is attached to a task, that person comes prepared .The alert email also does not show ownership, escalation history, trend information, or changes from the previous day. This is Evidence i observed in this regard.

### Situation B – The Blank Field

What is the stated problem?
The root cause field in the deviation tracker is often left blank or filled with generic answers. Anil and Karthik believe people are not disciplined enough to complete it properly.
What is actually happening?
I do not think discipline is the main issue, The real issue is fear. The supervisors are fearing that if they write the real reason behind a problem, they may get blamed during review meetings in front of everyone that is the main reason behind.
Actually the system is Instead of helping people solve problems, it is making people protect themselves.Because of this, they either leave the field blank or write very general answers that do not point to anyone in the meeting.
I think So the real issue is not that people are lazy or undisciplined. It is that they have learned from experience that being honest gets you into trouble. I would feel the same way if I were in their position 
Evidence from the scenario
Also one supervisor said that if he writes the real root cause, people ask many questions and it becomes a blame game and then and there i needs to give answers to that questions so he make it generic or left blank only in that column.
Another supervisor said that after a maintenance issue was honestly reported, the maintenance head was criticized publicly in front of everyone so he decided to not to give real cause next time.After seeing this happen, people stopped writing honest root causes.
This shows that people are protecting themselves rather than hiding information because of laziness. If everyone consider every ones opinions ceriously then this situation would not happened like this


### Situation C – The Meeting That Eats the Day

What is the stated problem?
The daily meeting is scheduled for 30 minutes but usually takes 60 to 90 minutes. Many technical discussions happen during the meeting and create additional work for everyone.
What is actually happening?
I do not think this is only a meeting problem.I believe it is mainly a planning problem.The company has monthly plans and weekly plans, but it does not have daily plans.Because there is no clear daily plan, people do not know what is planned work and what is unplanned work.As a result, every issue gets discussed in the same meeting.
Basically the meeting is trying to do too many things at once status update, planning, problem solving, escalation, all in 30 minutes with 12 people. That is why it runs 90 minutes every single day 
This causes the meeting to become longer and creates more unplanned work during the day.
Evidence from the scenario
The advisor asked for daily plans and found that none existed.The advisor also found that nobody was tracking unplanned work or identifying its root causes.Technical issues that should have been handled separately were being discussed in the daily status meeting.
The meeting was originally planned for 30 minutes but often ran for 60 to 90 minutes.


## My Observation On PART A :
I noticed that Anil and Karthik were hired to build systems and improve processes. However, much of their time is spent following up with people, solving daily issues, and doing operational work themselves.
This suggests that the organization is still dependent on individuals pushing work forward instead of having systems that naturally drive execution.
This is not required by the assignment, but it shows deeper thinking.



## Part B – Intervention Design

### Situation A
Situation A - The Alert Nobody Responds To
First Conversation
I would first talk to 2-3 department heads whose tasks have remained red for several days in the email alert systems. Then , I would ask them:
When you receive the alert email, what do you usually do?
How do you decide whether an issue needs escalation?
What stops a red item from becoming green?
When a task is delayed, who do you think is responsible for taking action?
My goal is not to blame anyone. I want to understand where action is getting stuck after the alert is received. I will only investigation to identify where is exactly problem happens and how can i solve.What changes in the first 2 weeks?
I would not build any new tool immediately.First, I would make sure every task has a clearly named owner instead of only a department name.I would introduce a simple rule:
"If a task is red, one person owns it."
I would also ask department heads to give a short update for overdue tasks:
What is the issue,What action was taken,What support is needed like questions then i will decide move forward.
The focus would be creating accountability before creating more reports.
System / Tool Design
What does the user see
A simple Excel tracker showing that has clearly structured parameters to evaluate everything in the organisation . they are like 
Task Name
Owner Name
Due Date
Status
Days Delayed
Blocker
Next Action
I think in this way , The user should immediately know:
What is pending
Who owns it
What happens nex
Workflow
          Owner updates task status.
                             ↓
              If task becomes red, reason must be entered.
                                 ↓
           If task remains red for 3 days, automatic escalation is sent.
                                                                      ↓
                                           CEO and COO can see ownership and escalation history.

                            
Technology i can Used for this
Excel (already accepted by HODs)
Power Automate for alerts
Outlook email notifications
I would continue using Excel because previous software adoption attempts failed.

Buy-in Strategy
I would not tell a supervisor like "You must update this tracker."
Instead, I would sit with him and ask:
"Every day people ask you for updates. Can we capture this information once so you don't have to answer the same questions repeatedly"
I would sit next to him, show him the simple sheet, and say  like 'Sir, right now people come to you 5 times a day asking for updates. If we fill this once in the morning, those 5 interruptions go away.' Most experienced people respond well when you show them a benefit for them personally 




### Situation B

Situation B - The Blank Field
First Conversation
I would speak privately with supervisors who regularly handle deviations.
I would ask like below saying like :
What happens after you submit a root cause?
Are people comfortable writing the real reason?
What concerns do you have when filling this section?
I would avoid discussing this in a group because people may not speak honestly [most people getting fear of getting blamed so ].What changes in the first 2 weeks?
Before changing the tracker, I would work on meeting behavior.If a deviation is discussed in a review meeting, the focus should be:
"What happened and how do we prevent it"
not
"Who should be blamed?"
I would encourage managers to discuss process failures rather than personal failures.The goal is to make people feel safe reporting problems.System / Tool Design
What does the user see?
A simple deviation form:
What happened?
Immediate impact
Possible root cause
Corrective action
Support required
There should also be an option: "Root cause still under investigation" instead of leaving fields blank.

Workflow
Deviation occurs.
Supervisor logs event.
Root cause investigation begins.
Department head reviews.
Corrective action is tracked until closure.

Technology Used
Excel form
Power Automate reminder emails
Claude for summarizing recurring deviation patterns
Claude can help identify trends, but humans should still verify root causes.

Buy-in Strategy
I would tell supervisors:
"The purpose of this tracker is not to find who made a mistake. The purpose is to stop the same problem from happening again."
I would also make sure management demonstrates this behavior during review meetings.
I know from experience that telling someone 'this is a safe space' means nothing if the next review meeting still turns into a blame session. The behavior of managers in meetings has to change first I believe that People trust actions more than instructions.



### Situation C

Situation C - The Meeting That Eats the Day
First Conversation
I would first speak with Anil and Karthik.
I would ask:
What topics consume most meeting time?
Which discussions could happen outside the meeting?
What work gets created after every meeting?
Then I would talk to a few HODs and understand their perspective.

What changes in the first 2 weeks?
I would divide meeting topics into three categories:
Routine work
Planned project work
Unplanned issues
Technical problem-solving discussions would be moved to separate meetings involving only relevant people.
The daily meeting should focus only on status, risks, and decisions.
I would also introduce a daily planning sheet for department heads.

System / Tool Design
What does the user see?
A simple daily planning sheet:
Task | Planned / Unplanned | Owner | Priority | Status
The above  sheet should clearly show where time is being spent.

Workflow
Department head creates daily plan.
New unplanned work is tagged separately.
Unplanned work is reviewed weekly.
Repeated causes are identified and addressed.

Technology Used
Excel
Shared Google Sheet (if allowed)
Power Automate for reminders
No complicated software because adoption has already failed before.

Buy-in Strategy
I would tell experienced supervisors:
"I am not trying to change how you run production. You know the process much better than I do."
Then I would ask:
"Can we spend one week tracking planned versus unplanned work? I want to understand where your time is actually going."
A person with 15 years on the shop floor does not need me to tell him how to run production. What I can offer is a simple way to make his own day less chaotic. That is the angle I would take 

## My Observation on Part B :

I also noticed that Anil and Karthik are spending too much time following up and solving operational issues themselves.
As the company grows from 2 projects to 8 projects, this approach will not scale.
Their role should gradually shift from chasing work to building systems that make ownership, planning, and escalation happen naturally.
This is the kind of observation that can help your submission stand out because it is not directly asked in the assignment but is clearly visible in the scenario.



## Part C – Scale Thinking

### Based on your diagnosis in Part A, what breaks first as the company scales?

I believe the first thing that will break is the accountability and follow-up system.
Today, many activities move forward because Anil and Karthik continuously follow up with people. They attend meetings, document action items, remind departments, and make sure work gets completed.
This works when there are only 2 active CDMO projects.
However, when the company grows to 8 projects, there will be many more tasks, dependencies, departments, meetings, and unexpected issues. At that stage, it will not be possible for a few analysts to manually follow up on everything.
At that point, Anil and Karthik or whoever the analysts are  will be running around all day just keeping things from falling apart. There will be no time to actually improve anything. That is when the whole operation starts cracking. 
This is why I believe accountability is the most dangerous failure point.
Evidence from the Scenario
Anil mentioned that most of his time is spent following up with departments instead of building improvements.
Karthik mentioned that they often end up doing work themselves when something is not getting done.
This shows that execution currently depends heavily on individuals rather than a scalable system.

### What system or process would you design now, at 2 projects, that prevents that breakdown at 8?

My Answer is 
If I joined the company today, I would focus on building an ownership and escalation system during the first three months.
The goal would be to make work move because of the process, not because someone keeps reminding people.
What the system would look like
Every task should have:
Task Name
Individual Owner
Due Date
Current Status
Next Action
Dependency
Escalation Level
Instead of assigning work to a department, work should be assigned to a specific person.
For example:
Instead of:
Purchase Department – PO Approval Pending
It should be:
Ramesh – PO Approval Pending
The system should also show:
Who is waiting for whom
What is blocking progress
How long the task has been delayed
Whether the issue has already been escalated
This will make accountability visible before the company grows.
Why build it now?
It is much easier to create good habits when there are only 2 projects.
If the company waits until 8 projects, people will already be overloaded and changing behavior will become much harder.

### What would you automate and what would you keep human?
My Answer is 
I would not automate everything because many of the company's problems are related to behavior, trust, and communication.
Technology should support people, not replace them.
What I would automate
1. Daily Status Alerts
Automatic emails showing:
Delayed tasks
New red items
Escalations
Reason:
People should not spend time manually preparing reports every day.

2. Reminder Notifications
Automatic reminders for:
Upcoming due dates
Pending actions
Overdue tasks
Reason:
This reduces manual follow-up work.

3. Trend Analysis
Use Claude or AI tools to identify:
Repeated deviations
Frequently delayed departments
Common bottlenecks
Reason:
AI is good at finding patterns in large amounts of data.

What I would keep human
1. Root Cause Discussions
Reason:
Understanding why a problem happened requires context, experience, and judgment.
A machine cannot fully understand shop-floor realities.

2. Escalation Conversations
Reason:
Many delays happen because of resource issues, conflicting priorities, or misunderstandings.
These situations require discussion between people.

3. Building Trust with Supervisors
Reason:
The biggest challenge in this company is not technology adoption.
It is getting people comfortable with new ways of working.
Trust can only be built through regular human interaction


## Final Thought On Part C
The company does not need more reports or more dashboards.
It already has reports, trackers, alerts, and meetings.
What it needs is a system where ownership is clear, problems can be discussed honestly, and work moves forward without depending on constant follow-up from a few individuals.
If that foundation is built now, the company will be in a much stronger position when it grows from 2 projects to 8 projects.
My focus would be to build a system that people willingly use, not a system that people use only because someone is reminding them every day 
     When I first read this situation, I also thought the email system was broken. But then I realized the email is actually working. The problem is what happens after the email lands in someone's inbox 


# Please find attached google doc file link below 
  https://docs.google.com/document/d/1t1unP34BB1aZOcv6ztTIGX7DrTw-Oc16ghc1jdG1V8k/edit?usp=sharing


## Part D – Hand Drawn Diagram

<img width="1430" height="1078" alt="PART D Hand-Drawn Diagram" src="https://github.com/user-attachments/assets/e4148772-6bc8-4d43-8d8c-3d4acfda0236" />

