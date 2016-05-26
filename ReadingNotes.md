# FOR CHAPTER 7??

## for code + data

[B] "a million-fold speed-up [mased on moore's law and commentary on the speedup of model processing time] is impressive, but hardware and algortihms are onyl two sides of the iron triangle of programming. the third is programming itself ... [setting the HPC minority aside,] the time is takes the `desktop majority' of scientists to produce a new computational result is increasingly dominated by how long it takes to write, test, debug, install, and maintain software. The problem is that most scientists are never taught how to do this."

## For "Dismay" rant in 70_

[A] Intro paragraph is lined with a combination of this surprise and dismay: "only 4 vc... only 1 tests software as matter of routine... none used any kind of code-checking tools ... I wish this were unusual but it's not" The timbre of software carpentry is "it doesn't have to be like this." When this criticism is raised, the implication is that not testing the software means errors in the science. But the other option is alternative modes of testing a la easterbrook, or other means of applying scientific skepticism to make sure the output is not spurious. The implication is that without testing, one cannot have the desired features of the perfect world (understandability, usability, extensibility; see fig X), but this does not hold. Scientists without testing and version contorl can and do produce robust software.

# FOR CHAPTER 2

## In transition around vocational change in 20_

[A] Software CARPNETRY rather than engineering is the name ``to emphasize the fact that it focuses on small-scale and immediately practical issues.'' 


## near F/LOSS

In his reflection on the design of the sfotware carentry curriculum, wilson holds that computational scientists do not have the publishing incentives to prioritize code quality, so the course does not attempt to ```sell' quality directly. Instead, it starts from the fact that the only way to improve productivty is to improve quality.'' [A] The F/LOSS take on this is the moral v material [Leach]

He continues: ``as in manufacturing and medicine, investments in quality repay themselves several times over because mistakes are more expensive to fix than to prevent.'' In Kelly's articulation of the subject of her ``risk-averse programmer'' she distinguishes this code - which MUST work - from the experimental kind which is undertaken by many scientists [kelly]

## Best practics

[A] Repeatable build (make), Scripting (Python), Debugging (using an IDE), Testing, Continuous Integration (rerunning test suite every rebuild, post result to project mailing list or website). Lastly, the "common core" advocates for selecting SOME structure for systematic code work: ``pick a process, any process'' and includes concrete ideas for project management.

## Agile

8 yars later in a retrospective he writes:`` [learned after 1998] textbook software engineering is not the right thing to teach most scientists ... careful documentation requirements and lots of up-front design are not appropriate for people who (almost by definition) do not yet know what they are trying to do. Agile development methods, which rose to prominence during this period, are a less bad fit to researchers' needs, but even they are not well suited to the `solo grad student' model of working so common in science.'' 
Another year later he coauthors with a dozen other scientists a best practices guide that takes as an opportunity every break down [C]
Sletholt et al agile.

## Publishing materials

[B] 04-05 materials published - materials useful, but ``did not find an institutional home'' - tension between the values of hte departments (computer science departments ee it as too easy to receive graduate credit, other departments expect CS to offer courses like this)
``what we teach simply isn't interesting to most computer scientists.''

# Ch 5

## Time Limits

two-day intensive workshop model of SWC restarted in Jan 2012 w new grant via Sloan foundation (footnote; both inclusion criteria based on sloan related stuff - DISCLOSE??) ``shortening the workshops made it possible for many people to attend, and increased the proportion of the material they retained. it also forced us to think much harder about what skills scientists really needed.'' things that were cut: OOP, XML, make, GUI, design patterns, software dev lifecycles. [B] Both Python and R were included in parallel, and sometimes LaTeS or domain-specific topics, which are the ``lingua franca'' of particular communities. [B]

## Tool vs Skill

``our real aim isn't to teach Python, Git, or any other specific tool: it's to teach _computational competence_'' ''tension between teaching the `what' and the `how' of programming'' referrin e.g. to Python syntax[B]

## Social resources + sprint

``as well as instructors, we rely on local helpers to wander the room and answer questions during practical sessions'' [B]

## dogfooding / credibility - for 72_ in discussion of using the thing

[B] stresses building "credibility" by using the materials tuaght by organizing workshops and hosting lessons through GitHub. and ``open everything'' in terms of process to build trust.

Sticky notes of different colors for ``im confused'' [B] and RN-M PI uses these in teaching.

## personalized working env 31_

``learners tell us that it is important to them to leave the workshop with their own working environment set up'' which is the reason they continue to teach all major platforms [B]. As a helper at several workshops, I noticed that set-up is often sprinkled with surprising yet inevitable setbacks due to peculiarities of the working environment already in place. In each case, the helpers self-organized where the helper whose own experience most closely aligned iwth that working environment would be helping. If aonther helper encountered the same problem elsewhere, he or she would call the relevant ``expert'' helper over. the working environment is not idiosyncratic but rather personalized. Its individual uniqueness is recognized as a valid outcome of the differences between scientists' backgrounds and interests. Even the most ``trivial'' things, like editing text, are ``always harder than we expect. Wilson goes on to note that they ``don't want to encourage people to use naive editors like Notepad, and two most popular legacy editors on Unix (Vi and Emacs) are both usability nigthmares. We now recommend a handful of GUI editors, but it remains a stumbling block.'' I have quoted the trouble with editors at such length to provide grounding to a recurrent theme about the study setting: even the most simple things manage to be consistently challenging. The differentiation and complementarity in oceanography and in scientific software development alike are adaptations to complex practices.

## uncertainty and software advisor as gate keeper

+that email i sent to marc and ivan

[B] ``getting software installed is often harder than using it'' - ``learners dont (yet) know about systems paths, environment variables, the half-dozen places configuration files can lurk on a modern system ... combined with two version of Mac OS X, three version of Windows, and two oddball Linux distribtions'' and unexpected behavior is ``inevitable.'' 

## testing and models

Edwards AVM Ch 13: how modelers validate, or verify, or evaluate climate models, a ``perilous choice among seemingly similar terms that amounts to the $100 million question for climate modeling: Can we trust model predictions of climate change?'' Verified/validated: by end of 1980, ``emboldened'' by ``icnreasingly precise data,'' would refer to a model that reliably reproduced observed climate. Critiqued by 1994, because `verification' implied ``definitive proof'' that is not possible in the ``essentially intricate inductive arguments'' that models are. Vlaidation was better: ``demonstrated internal consistenc andan absence of detectable flaws.'' #MODELS ARE VERSION OF REAL WORLDS
Finally, evaluaion is a ``claim of relevance and trustworthiness, rather than truth'' because it is based on comparison between models and real world data.

## Paramteres

AVM edwards ``may be fixed quantitites, such as coefficients, or they may be mathematical functions containing both coefficients and dependent variables.'' ``Tuning'' a paramter ``means adjusting the values of coefficients and even, sometimes, restructuring euqations in order to produce better overall model result.'' Betted may mean that the result agrees more closely with observations, or that is corresponds more closely to the modeler's expert judgment about what one modeler I interviewed called the `physical plausibility' of the change.'' <-- SEE PILE OF SALT. The ``plausibility'' of a phenomenon was apparent much.
``Parameterization and tuning remain, in effect, scientific art forms whose connection to physical theory anf observational data varies widelyform case to ae.''

# BIB

[A] Greg Wilson on Software Carpentry (2006, Getting Scientists to Write Better Code by Making them more Productive

[B] Greg Wilson Software carpentry: lessons learned (2014)

[C] the wilsonXXXbest