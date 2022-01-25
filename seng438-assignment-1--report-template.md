>   **SENG 438 - Software Testing, Reliability, and Quality**

**Lab. Report \#1 – Introduction to Testing and Defect Tracking**

| Group \#:       | 7 |
|-----------------|---|
| Student Names:  |   |
| Graydon Benson  |   |
| Eli St. James   |   |
| Seher Dawar      |   |
| Maxwell Botham  |   |

**Table of Contents**

(When you finish writing, update the following list using right click, then
“Update Field”)

[1 Introduction	1](#_Toc439194677)

[2 High-level description of the exploratory testing plan	1](#_Toc439194678)

[3 Comparison of exploratory and manual functional testing	1](#_Toc439194679)

[4 Notes and discussion of the peer reviews of defect reports	1](#_Toc439194680)

[5 How the pair testing was managed and team work/effort was
divided	1](#_Toc439194681)

[6 Difficulties encountered, challenges overcome, and lessons
learned	1](#_Toc439194682)

[7 Comments/feedback on the lab and lab document itself	1](#_Toc439194683)

# Introduction

The purpose of this lab was to develop a smooth introduction to hands-on Software application testing. Through different testing methods, our group comprehensively tested a simple ATM, given a lengthy requirements list. In pairs, and as a team, we worked through exploratory, manual scripted, and regression testing to find a number of bugs in two versions of the application. This lab also introduced the group into bug tracking software Backlog. In different versions of the program, bugs found in either app version were comprehensively recorded for later reference. Though each member of the group had a strong foundation in developing and testing their own programs and assignments, following a scripted, and regression testing was very new to us. In the past, much of our testing has focused on a high-level exploratory testing. Furthermore, the bug tracking software was new to the group, but each individual was able to learn the software with relative ease. 

# High-level description of the exploratory testing plan

We will start our exploratory testing plan by first switching on the system using the ON switch. Then we will provide the system with 3 different numbers for the amount of $20 bills at hand - 20 , 0 , -1 - and note down the outputs. After this we shall confirm that the system has connected to the bank. Then we will enter the ATM card number with varying inputs- a known card number actually connected to an account and a random number. Similarly, the PIN will also be checked for validity by entering correct and incorrect PINs and attempting transactions. We will attempt withdrawal transactions within the session by attempting legitimate and illegitimate withdrawals with positive and negative withdrawal amounts. We will also check the system by withdrawing from multiple different accounts.
We will test depositing money into all of the types of accounts available. At all stages of the deposit, we will test clicking the “cancel” button, and we will also test by giving it valid inputs. We will check the system’s behaviour against the requirements to determine whether deposit is working. We will test transferring money from one account to another. We will again test clicking cancel at every stage, and will test by entering valid inputs at every stage. Lastly, we will test ‘inquiry’ against every account that exists for the card entered. We will ensure that the information we see is valid. After turning off and on the system, we will check the system’s logs to ensure that all transactions we made were represented with correct communication to the bank (then stored in the logs). Lastly, we will test shutting down the system. At any point in this process, if a discrepancy between expected and actual results is discovered, the defect will be logged in backlog.

# Comparison of exploratory and manual functional testing

For this assignment, we used the aforementioned Exploratory Plan to find several defects in the ATM system. Then we used the functional test suite that was provided in Appendix C for the Manual Scripted Testing. 
While exploratory testing gives testers the freedom to use their instinct, skills, and experience for detailed testing, scripted testing requires testers to follow a series of guidelines to verify if the actual result is as intended.
Since our exploratory plan was so extensive, it was quite time consuming and quite hard to fit within the allotted 30 minutes. But the freedom that exploratory testing provides is really useful in finding defects, especially if one’s scripted plan misses edge cases. For example, in ATM v1.0, pressing 0 on some of the menu screens caused $20 to be dispensed. None of the test cases in the functional test suite triggered this defect. 
On the other hand, manual scripted testing is good for having a plan that covers the most important and basic functionality of the application. It is extremely efficient to go through all the test cases and check against the expected outcomes in the plan. While the coverage provided by the test cases is not 100%, it is still more than the Exploratory plan. There were quite a few defects that were found by both Exploratory and Manual Scripted Testing.
In conclusion, for this assignment, Exploratory testing was useful for unearthing a few more defects than Manual Scripted Testing, since most of the defects in the ATM v1.0 were unconventional and outside normal usage. 

# Notes and discussion of the peer reviews of defect reports

Text…

# How the pair testing was managed and team work/effort was divided 

In the pair testing stage, our group was divided into pairs of two. In the exploratory testing, one partner recorded bugs into Backlog, while the other executed the testing plan on the ATM. Each pair identified a number of bugs, both common and unique to the other pair. Bugs were then compared in Backlog, and duplicates were removed. The team completed the regression testing on V1.1 of the program together, taking turns testing the ATM, and entering bug details into the log. This approach led to each member getting a chance to experience the various steps involved in testing, and to become familiar with the software. 

# Difficulties encountered, challenges overcome, and lessons learned

During the testing of this interesting java ATM application, we ran innto a feww challenges along the way. One of those challenges was during the regression tests, when testing the ATM version 1.1, it was somtimes hard to remember what bugs existed in the ATM version 1.0, without having backlog open to look at. This just goes to show how important it is to record all the earlier bugs found, so you wont have to remember all of them and possibly miss some. Another challenge we encounterd as a group was when we split up into pairs for manual testing, sometimes we would report duplicate bugs.

# Comments/feedback on the lab and lab document itself

Tthe assignment was interesting, interactive, and at times challenging. It really gave us a taste of what its like to test a program. In terms of the instructions for the assignment. we believe, at some parts, the instructions were unclear, Mostly regarding splitting up into pairs.  It was hard to know how to merge our work, or if we needed to make two defect reports etc.
Overall Good Assignment.
