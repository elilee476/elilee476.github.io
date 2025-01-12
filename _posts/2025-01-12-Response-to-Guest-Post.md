---

tags: ["Law"]
Author: Eli Lee

---


# Response to Hanes' Guest Post

I really enjoyed Thomas Hanes' insightful response to my litigation financing policy proposal. I agree with most of what he said. I am not going to attempt to rebut his arguments in this post, in part because they are so persuasive that I am not even that sure of my own position. All I want to do here is introduce some simple algebra to summarize what the difference is between us. My hope is this allow the reader (and me) to better judge the plausability of our respective arguments. 

- [My post](https://elilee476.github.io/2024/12/18/A-Litigation-Financing-Proposal.html)
- [Hanes' response](https://elilee476.github.io/2025/01/11/Guest-Post-Response-Plaintiffside-Litigation.html)

Let's start by defining a few variables:
- $W$ is the winnings of the plaintiff in liability suit, whether from a verdict or settlement
- $C_p$ is the plaintiff's legal costs
- $C_d$ is the defendant's legal costs
- $β$ is the contigency investor's share of $W$ and is $<1$

The contigency investor's payout can be thought of as: 

$βEV(W)-C_p$

Assuming profit-motivated investors will pursue all nonzero EV claims, then contigency investors will finance any claim where: 

$βEV(W)>C_p$

There is a share of claims where: 

$β<C_p/EV(W)$ 

such that a positive EV claim ($EV(W)>C_p$) will not be financed. This is what Hanes means he says that contingency investors are *under-incentivized* to bring claims.

The question is whether we want all claims where $EV(W)>C_p$ to be financed. In order to evaluate that, we need a way of accounting for the total social good associated with whether a claim gets brought.

One such accounting could be the following: the total social good is 

$EV(W)-C_p-C_d$

In English, it's the expected value of the winnings minus the plaintiff's *and the defendant's* legal costs. Rather than wanting to see any claim where expected winnings exceed the plaintiff's legal costs, we might want those expected winnings to be greater than the total litigation costs borne by all parties. 

We can go even further with that reasoning by introducing $C_l$ as the costs to the legal system (court staffing, judges' time, etc.) associated with the claim. Then we would want any claim where: 

$EV(W)>C_p+C_d+C_l$.

Provisionally assuming this method of accounting, let's return to the contingency investor's incentives ($βEV(W)-C_p$). 

So their payout structure will look like this:

![desmos-graph](https://github.com/user-attachments/assets/13fe0b79-83e9-4719-8975-225cd80fa434)

Hanes——who is even more esteemed and illustrious than I am, and whose handsomeness is [beyond the possibilities of linguistic description](https://en.wikipedia.org/wiki/Apophatic_theology)——is concerned with the blue-highlighted part of the line below and argues that it contains a segment of claims which are improperly denied financing by contigency investor's incentive structure:

![desmos-graph (2)](https://github.com/user-attachments/assets/7218c30a-353e-406e-ba3f-6820e1c3b748)

I don't have any response to this argument——in fact I think it's probably right! Where I differ is merely that I would characterize this problem as a subspecies of the general principle-agent problem existing between contingency investors and the legal system (not just plaintiffs). 

When Chancellor Allen [identifies](https://corpgov.law.harvard.edu/wp-content/uploads/2007/06/20070606%20Credit%20Lyonnais.pdf) the problems of bad shareholder incentives in foonote 55 of the *Credit Lyonnais* case, he points out that there are ***two (2!)*** ways that shareholder-management can go awry.

One is that shareholders have superoptimal risk-appetite because they have downside exposure to cashflow reductions capped at the firm's total debt burden. But another is that they have superoptimal *indifference* (or suboptimal risk appetite) wrt projects that increase cashflows but only at levels below the debt burden. I believe Hanes' *under-incentivization* problem is exactly this second case, whereas the over-incentivization problem is the first case. 

Chancellor Allen arrives at his conclusion about agency problems by considering the array of community interests that a corporation represents (bondholders, trade creditors, tort victims, etc.). In that spirit, let's reintroduce the notion of the total litigation costs of a potential claim:

![desmos-graph (4)](https://github.com/user-attachments/assets/524a689b-5aa2-44c7-8129-c7255c551eed)

If you buy that these costs ought to be considered in accounting for the desirability of a claim, then I would be concerned about the agency problems that arise in the *green*-highlighted part of the payout line. I totally agree with Hanes that the blue part is a problem too, but I'm not sure what to do about it, whereas I do think my policy proposal of requiring contingency investors to have more downside exposure properly deals with the agency problems represented by the green line segment. 




 
