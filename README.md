
#### CHAPTER-1
###### Learning is a continuos and ongoing process. 
In the first chapter Andrew Hunt tells us about who is a `Pragmatic Programmer` and how to become one. First chapter contains small interesting life stories which teaches us about a lot of things in general. He tells us about how to take a charge of our own career and don't be afraid to admit errors. He also talk about to be proud of our abilities and to be honest about our shortcomings.  He emphasis on removing `it can't be done` with `what can be done to solve the solution`. Further he talks about `Software Rot` and how it effect the software engineer life. He also writes to not live with broken windows and fix each one as soon as it is discovered. He also shares about how people find it easier to join an ongoing process, and how the atittude of people changes when we show them the glimse of future with help of famou `Stone Soup` story. He emphasis on the importance of quality of code and involvement of users. 
Further he compares the `knowledge portfolio` with `financial portfolio`. And talks about investing regulary in the knowledge portfolio. He also pens down the importance of setting goals for eg: to learn one language every year, reading a technical book, reading a non-technical book (don't forget the human side as computers are used by people), to stay updated and so on. At the end of the first chapter he talks about the importance of communication and to be a good listener. 

And ends with the famous quote : "It's both what you say and the way you say it". 

#### CHAPTER-2
###### Approach to become a Pragmatic Programmer.
In chapter two Andrew Hunt pens down few points for a pragmatic approach. He talks about duplication of a code and how it plays like an evil in software engineer life. He writes down few reasons by which duplication arises (imposed duplication, inadvertent duplication, impatient duplication and interdeveloper duplication). 
Further in the chapter Mr. Andrew tells us about the benefit of `orthogonality` (if changes in one do not affect any other thing)in the software world.He further adds about `reversibility`. He pens down some points regarding how to use prototypes: correctness, completeness, style and so on. He later adds about the `Domain Language` and how it influece the thinking and communication of humans. he also explaisn abot the difference between `data language` and `impretive language`. At last of chapter 2 he talks about the importance of `estimation` ion a software developer life. 

And ends the chapter with: "Estimate to Avoid Surprises."

#### CHAPTER-3
###### The Basic Tools 
As the name of the chapter implies, Mr. Hunt pens down the tools that he think should be employed in all software projects. He further talks about the `power of plain text`. He mention the idea that data and code are knowledge, and any knowledge that remains readable by humans will outlast any other data. He further adds the tip "use the power of command shells". He talks about the advantage of having a power in shell that `Commandline are fairly universal, so knowing how to use them affords you a great deal of power in all kinds of environments`. He further talks about the importance of "Source Control" and "Version Control". And adds like how it give reversibility, if we want to go back to an earlier commit, and at least with git, orthogonality in that we can cherry pick changes from different commits. It also makes integrating changes from other developers far easier. And quotes - "There is no reason not to use source control".
Later he talks about `Debugging` and how we should `Fix the Problem, Not the Blame`. 

Following are the points he adds while talking about Debugging:
1. Don't panic
2. Don't waste time thinking "that's impossible"
3. Always try to discover the root cause of the problem
4. Start with syntax - use the highest compiler warning settings
5. Watch the user reproduce the bug
6. Automate the reproduction of the bug
7. Visualize data using a debugger or something like print statements
8. Trace the control flow programmatically
9. Question everything - if the bug seems impossible, check your assumptions

#### CHAPTER-4
###### You can't write Perfect Software
Andrew Hunt writes that no one in the recent history of computing has ever written a piece of perfect software. Pragmatic Programmers don't trust their code , either. 

He adds that  correct software program is one that does no more and no less than it claims to do; and emphasis to use:
1. Preconditions
2. Postconditions
3. Invariants

He pens down - "Write `lazy` code: be strict in what you will accept before you begin, and promise as little as possible in return". 

He further talks about `Data Base Computing` and how we can enumerate the design time by following these steps: 
<ul>
 <li> what the input domain range is</li>
 <li> what the boundary conditions are</li>
 <li> what the routine promises to deliver (and what it doesn't)</li>
 </ul>
He talks about two types of Invariants:
<ul>
 <li> Loop Invariants : Is true before and during the loop.</li>
 <li> Semantic Invariants : ie the error should be on the side of not processing a transaction rather than processing a duplicate transaction.</li>
 </ul>

Andrew Hunt writes that all errors give us information, the pragmatic programmers tell themselves that if there is an error, something very, very bad has happened.
`A dead program normally does a lot less damage than a crippled one`.
He further adds about `Assertive Programming` and it's advantage. 

Following are few points on assertive programming: 
<ul>
 <li>Assertions are also useful checks on an algorithm's operation.</li>
 <li> Don't use assertions in place of real error handling.</li>
 <li> Leave Assertions Turned On, unless you have critical performance issues.</li>
 </ul>

He lastly talks about balancing resources. 

And ends the chapter with "Finish What You Start"

#### CHAPTER-5
###### Bend or Break 
In this chapter Andrew Hunt talks about writing flexible code, or code that can be changed easily in order to keep up with changing demands of users, or just for the purposes of maintainability.





