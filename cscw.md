# Hacks are not Hacks

## Abstract

## Intro

Code in science matters. Now is a remarkable moment. It is positioned in a history of increased abundance of more varied and hihg-resultion data and more robust computational capabilities.

In this work, we distinguish programming that MUST work [a la Kelly] from programming that can exist in an experimental, beta flux. Kelly makes this distinction articulated as ..... 

We conducted a qualitative 18-month study with 46 scientists in four oceanography teams, and up to 100 in various computational skill workshops attended or observed. After data collection, the first author presented some of the findings to the scientists. In this talk, I presented the claim that  the ``best practices'' that they occasionally worried about not pursuing with enough diligence (``_should_ be using gitHub, but haven't gotten around to it....'') were more formal versions of practices already in place, but which extended beyond code to data and figures. For example, through formal software engineering testing was virtually nonexistent in the group studied, all groups engaged in a thorough, systematic validation and verification processes usign consistent visual artifacts. We deveop this argument further in Section XXX, but the other sections (XX and XX) also take the stance that code work must not be critiqued in isolation of the data and visual products that it requires and enables.

The first author presented a preliminary articulation of these ideas to the interested study particupants, and one of the very last questions was: ``so you coverd in your talk some ways in which oceanographers can learned from software engineers and computer scientists, but what can computer scientists learn from oceanographers?'' We believe this is a question of utmost importance in the study of scientific programming practices by computer scientists, and this manuscript offers our answer so far.

## Background



## Introduce the Model

During dissertation research, the first author developed a model of deliberate change in code work based on ethnographic study of four oceanography teams in the Pacific Northwest. Oceanography constituted an 

FIGURE 1 goes here illustrating the model.


This model is agnostic relative to the specific tool. Indeed, it is very liberal with regard to what constitutes a tool. 

## 3 Arguments

When I say that the things that are called ``hacks'' are not hacks, I am claiming that they do not posess the qualities that make them seem like hacks: (1) contained to an individual who does not need to include the requirements of others; (2) a ``means to an ends'' meaning that there is no sense of elegance or instrinsic value of code driving it; and (3) ad-hoc, ephemeral.

### Code that would not convince peers does not convince the individual

### Beauty is in the Eye of the Beholder

``simply isn't interesting to most computer scientists.'' [B]

("students will now believe that it's worth learning how to test software systematically") [A] Well OF COURSE they beleive that! testing and reproducibility are never not on the horizon of the perfect world. But the journey there takes a long time, and is filled with uncertainty. The Incentive is missing for investing in learning any particular thing out of a cornucopia of viable and enticing possibilities.
For all the handwriging abotu not testing, in a retrospective of learnings from years of SWC workshops, Wilcon writes that the workshops ``don't do as good a job as we would like teaching testing. mechanics of unit testing are straightforward ... and it's easy to come up with representative test cases for things like formatting data files, but what should we tell scinetists about testing the numerical parts of their applications? Once we've covered floating-point roundoff and the need to use `almost equal' instead of `exactly equal', our learners quite reasonable ask, `What would I use as a tolerance for my computaiton?' for which no one has a good answer.'' [B]


(INCLUDE FIGURE 6.2)

In this section I make the argument

``The reason most computational scientists don't care about quality is that there's no incentive for them to do so''[A Greg Wilson] because of publication stuff. We see Howison and Herbsleb making similar incentive arguments that problematize certain software production systems. Young et al and Mislan et al both appeal to ways in which the sharing of data and code respectively can be made more streamlined and accessible, to support the overall value of sharing.


### Moments of Flux / No going Back

The model we introduce in Section XX defines the working environment as subject to deliberate change. There are many options for the direction of this change in any of the myriad small opportunities for decision making. The direction is decided using an imagination of the perfect world.

Another way to orient change is by appealing to a software advisor. WHAT IS AN SA.

For example, one of the team's SAs says this: “You know, I just watch them, I can see when their eyes glaze over. The Principal Investigator (PI) is really good at pushing me on it: `do I - as a scientist - really need to know this?’ '' An uncharitable reading of this statement seems to reinforce the idea that scientists do not care about the quality of their code, and this dooms them to a life of ad-hoc hacks. However, this was spoken in the context of a group that at the beginning of the study had recently begun adopting version control with some associated growing pains, and by the end had integrated GitHub substantially into collaborative work practices. Furthermore, it was a post-doc and a graduate student who then took the initiative to ask the SA about automating some of the testing in their analytic pipeline, which he was more than delighted to begin explaining. A ``hack''  is typically described as ``not the best way of doing things,'' ``not very elegant,'' ``ugly but it works,'' or fialing to use something it ``really should be.'' Instead of interpreting these terms at their face judgmental value, we can observe the progression of the ``ugliness'' over time and see that if there is truly a ``perfect world'' that the scientists prioritize, individual small moments of flux will slowly inch those ``hacks'' in that  direction.

## Implications for Practice

Of the model:

Reframe dismay or surprise as comparison of working environment to the perfect world. Is the imagination of the perfect world is shared enough to justify deliberate change?

Necessary for follow-through on change: [ ] awareness - I have heard of it & know what it is [ ] intention - I should probably be using it… [ ] momentum - If I already knew it, I would use it [ ] opportunity - Clear course of action is available

Evaluate not only technical, but social and skills components of the working environment. Never “back at square one!” 