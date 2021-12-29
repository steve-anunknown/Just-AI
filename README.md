# Just-AI
Artificial intelligence techniques implemented for the administration of justice.

## Summary

The goal is to use artificial intelligence so as to make tedious and time consuming tasks easier and faster for lawyers and judges
and to assist judges in their desicion making. Ideally, Just-AI will be able to categorise law cases based on their
characteristics and intrinsic details, allowing lawyers and judges to treat them, when possible, in "bulk", instead of devoting
extreme amounts of time to discrete cases that share a lot of similarities. In addition, it will be able to assist the judges in
their desicion making, by providing a general, data oriented, sentence that the judges can "humanise" and adapt to the specific
case.

## Background

The inspiration for the idea was the fact that, almost everywhere, justice administration is too slow and judges get overwhelmed
with cases that share many similarities. Hopefully,it solves a variety of problems:
* It speeds up the administration of justice.
* It assists judges in being more objective by providing them with a strict data-oriented sentence that they can adapt to individual cases.
* It reduces litigation costs.
* It encourages citizens to pursue their rights instead of remaining inactive in fear of losing time and money.

## How is it used?

Just-AI can be used for any law case, but mostly typical cases that consist of "objective" variables and not "human" variables
that complicate things. Example of a "typical" case would be a citizen claiming damages from a municipality for the tire of their
car that got damaged due to the bad quality of the road. On the other hand, a case with many "human" variables could be, not
neccessarily, a divorce case with adultery and children involved.

The user will enter the necessary data to the Just-AI system, which will in turn search into a data base and, either find a (one
or more) past case(s) with the exact same parameters, or present the user with a number of most similar cases. If the user is a
lawyer, it can present estimated time of resolution, win rate of past cases etc. If the user is a judge, it can present the
sentences of the previous cases and propose a new, supposedly more suitable, sentence.

## Data sources and methods

The data comes from a (national or state-wide) data base of solved cases, broken down to a wide variety of characteristics that
can be used to categorize the incoming new cases.

The k-nearest neighbour will be used so that the user, upon entering the data, will be presented with the k most similar cases. 

The estimated time of resolution and win rate will be predicted using the appropriate data from previous cases and by
drawing some data regarding the current state of running cases. The software can be trained using linear regression and
reinforcement learning. Finally, the proposal of a new sentence will too be acquired using linear regression.

## Challenges

It goes without saying that justice is a complicated issue and not something that can just be automated. As a result, law cases
that contain a lot of human factors and data unable to just be broken down to variables require special attention. In addition,
the manner in which "weight" is attributed to the different characteristics that are, ultimately, been used has to be constantly
reviewed in order to ensure that the system is, indeed, fair and up-to-date. Furthermore, issues of privacy are being raised, not
only regarding the participants but potentially the legal stuff as well. Finally, it is of utmost importance that the system
is secure and that the different variables and co-efficients that make up the results cannot be tampered with.

## What's next

The project requires the collaboration of a country in digitizing the justice administration system and creating a data base of
resolved cases. The assistance of legal scientists is crucial in determining the parameters which the cases will be broken down to
and the neccessary weight that each one of them has to be attributed with.

Perhaps, in the future, we will have successfully managed to break down any case into processable variables (using the expertise
of psychologists) that lead to a result, regardless of the individual case. Also, the software could draw data from penintentiary
systems and assess its own previous judgments based on their effectiveness on the convicted person. Moreover, the assessment of a
case could include the overall performance of the attorney that handled it and present more accurate data depending on one's
performance (for example, was a case lost because the attorney handled it poorly? or was it won because the attorney handled it
exceptionally well?). This would require for legal workers to be included in the data base as well.

In any case, we should always tread carefully, not get carried away by the effectiveness of the system and always consult
scientists and experts before putting our trust on this kind of technology.
