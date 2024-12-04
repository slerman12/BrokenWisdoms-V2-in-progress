# <p align='center'>Holy Faith</p>

# Part 1 

## Right to Talk about Suicide Seriously

Most people seriously considering suicide can't talk about it, not unless they bury the very-conscious awareness of the standard medical policy of hospitalization and drugging. The more seriously somebody genuinely needs to talk about their depression amid a genuine imminent plan, the less they standardly can without risking the security of their plan. Suicide is legal in New York State, but so are coerced hospitalizations and drugging, threatening people into withholding communicating the severity of their suffering. 

These coercive medical practices are bad.

By the literal meaning of the words, I don't think "Right To Die" is "Right For Physician To Commit Physician-Assisted Suicide." Just in the literal sense, where "right" does not mean "accessibility," the two phrases are different: 
- One permits a person to take actions towards suicide, including talking to a therapist about those actions, without coercion (e.g., hospitalization, drugging, intervention), and without punishment.
- The other gives doctors permission to assist with the suicide.

"Right To Die," by my way more literal interpretation, only changes one item from the current legality in New York: gets rid of involuntary institutionalization and coerced chemicals for planning to commit suicide, so that somebody planning to commit suicide, but not wanting the security of their plan ruined, can get therapy, and not just through philosophy and art.

Here is my favorite Shakespeare sonnet:

> ### $\Huge &#8220;$
> &ensp;&ensp; *Tired with all these, for restful death I cry,*</br>
> &ensp;&ensp; *As to behold desert a beggar born,*</br>
> &ensp;&ensp; *And needy nothing trimm'd in jollity,*</br>
> &ensp;&ensp; *And purest faith unhappily forsworn,*</br>
> &ensp;&ensp; *And gilded honour shamefully misplac'd,*</br>
> &ensp;&ensp; *And maiden virtue rudely strumpeted,*</br>
> &ensp;&ensp; *And right perfection wrongfully disgrac'd,*</br>
> &ensp;&ensp; *And strength by limping sway disabled,*</br>
> &ensp;&ensp; *And art made tongue-tied by authority,*</br>
> &ensp;&ensp; *And folly, doctor-like, controlling skill,*</br>
> &ensp;&ensp; *And simple truth miscall'd simplicity,*</br>
> &ensp;&ensp; *And captive good attending captain ill.*</br>
> &ensp;&ensp; *Tired with all these, from these would I be gone,*</br>
> &ensp;&ensp; *Save that, to die, I leave my love alone.*
> ### $\Huge &#8221;$
>
> &ensp;&ensp;&ensp;&ensp;&ensp; - Sonnet 66, Shakespeare.

> [!NOTE]
> ### Academia & Medicine
> 
> The relevance of "Art made tongue-tied by authority and folly, doctor-like controlling skill" is impossible to communicate. It's no coincidence that "doctor-like" is the simile Shakespeare turned to, as that is the perfect description of the kind of authority he refers to, which governs, not just Chenliang's group, but most of the university, academia, and — most un-medically — medicine. 
>   
> My intuitive ideas, way ahead of their time, were often preemptively dismissed and disregarded, until I found the right phrasing and pictures for the faculty to teach and convince them, like the use of rewards from past actions to inform new actions in similar states, similarity as measurable by geometrical (Pythagorean) distance between datapoints or representations, decomposing datapoints into parts and relations, or efficient relational reasoning by prioritizing information relative to those parts. "Simple truth miscall'd simplicity."
>
> I proposed these fundamental insights, and what methods would correspond to them, while they were still original or before they had appreciation:
>
> - (a) An agent "choosing" actions at first randomly in an environment, given "states" as input, remembering the actions chosen in a memory together with each state; then in future states, looking at those past actions, in memory, that corresponded to the most similar states to the current state, and taking the ones that got the highest environment rewards in the past, or, with some probability, exploring via taking random actions to get more state-action memory
>    - (relevant method examples: such as via K-nearest neighbors; model-free episodic control; neural episodic control; fully-parametrically, as hypothesized methods of reasoning, rather than symbolically, in RNNs or Decision Transformers),
> - (b) "similarity" as measurable by geometric distance between those numbers ("states") that represent input datapoints
>    - (relevant method examples: such as via Euclidean distance, cosine distance, parametric distance),
> - (c) decomposing those representations into representations of parts and relations
>   - (relevant method examples: such as via segmentation, parameter re-use inductive biases in neural networks like convolution, recurrence, attention, vector-quantization; or, more elementarily, weighted sums with non-linearities),
> - (d) efficient relational reasoning by prioritizing information for each part relative to each other part
>   - (relevant method examples: such as via MHDPA on vectors),
> - (e) representing each part with numbers that don't vary much for that part unless there are meaningful contextual changes
>   - (relevant method examples: such as with parameter re-use inductive biases in neural networks like convolution, recurrence, attention, vector-quantization; or gating; or frozen parameters of trained or symbolically-programmed encoders),
> - (f) training multiple such wisdoms in parallel to vote across each other and create a more general diversity
>   - (relevant method examples: such as via ensembling, evolutionary populations, and, more elementarily, mini-batches), and
> - (g) representing concepts more generally by learning across far more varied domains
>   - (relevant method examples: GATO).
>
> Each, individually or grouped, were dismissed by the faculty when they were still essentially mine (not always, but at least as the field of deep learning progressed, slowly), as I was repeatedly gaslit by my faculty listeners, with their authoritative rejection or suspicion, into doubting or tripping over my own far better understanding, as I tailored everything carefully to their understanding into symbolic methods or symbolic-neural hybrids, since most of them, initially, were skeptical of pure deep learning or thought deep learning was a fad.
>
> They are a really conservative and vampiric research department. What makes them conservative? They don’t come up with anything original or new. What makes them vampiric? They make incremental modifications to existing works or within existing research-area zeitgeists that have no profound or moral point in the sense of actual principle rooted in unsuperficial caring of others.
>
> The CS department's faculty, with occasional exception, didn't hear anything that they didn't want to, that they hadn't already internalized for multiple decades during their careers, that they weren't already clinically versed on, taught to them through their studies, normalized by their colleagues, and standardized, discussing "needy nothing trimm'd in jollity" while my ideas were "miscall'd simplicity" until they became mainstream, with credit for my teaching then "unhappily forsworn."
>
> As well as just simple intuitions that were pedagogically better:
> - (a) Backprop as just an algorithm for taking a derivative, wherein the change that would hypothetically increase or decrease a function is disseminated, operation by operation, from the output back to the input, to each parameter in that function,
> - (b) [LSTMs as biological neurons](https://drive.google.com/file/d/1i5hS2iDVuo24PnGicvn5dIZYXUzDfPAl/view?usp=share_link), and
> - (c) ["Convolution is all you need"](https://github.com/slerman12/BrokenWisdoms/blob/Ancillary/Conv-is-all-you-need.md).
>   - Quick rant, but worth reading:
>       - "Attention is all you need" sounds like a reply to "You just want attention." It’s in bad taste. That’s the name of the paper from DeepMind that most revolutionized deep learning after 2017. My later paper under Chenliang was going to be called, ["Relation is all you need,"](https://docs.google.com/presentation/d/1QbWNfnWAgm0rHTy4EFnDrjpaMP7Ako6isNxOUSR17_A/edit?usp=sharing) which brings the idea slightly closer to "Relationships are all you need" or John Lennon’s phrasing, "Love is all you need," and the method it uses is more algorithmically democratic (which is a good analogy, since governing systems are systems/algorithms for decision-making, meant to compose the knowlege and wisdom of smaller parts to that of larger collectives, relationally).
>         - I was rushing to make [this](https://docs.google.com/presentation/d/1QbWNfnWAgm0rHTy4EFnDrjpaMP7Ako6isNxOUSR17_A/edit?usp=sharing) into an ECCV, 2022 paper, because Chenliang said it makes him "sad" that almost no one in his group was submitting to ECCV, 2022. Solely out of love, I was about to rush another extremely fundamental new MHDPA innovation just because he ended that week's meeting, the week before the submission deadline, with "It makes me sad." I managed to run one experiment in time ([see here for code](https://github.com/slerman12/UnifiedMLold2/blob/master/Blocks/Architectures/LermanBlocks/ViRP.py)), and then resumed my regular work because I still had all of UnifiedML to build, and not even a tacit hint of dissatisfaction from Chenliang.
>         - He was the least-unappreciative of all of the CS faculty of my work, and that became more true than ever with each year he saw my thinking, efficiency, and work ethic, but just as quickly lost sight of that when he remembered my paper count, despite the fact that he was usually tolerant to my submitting fewer papers to conferences compared to his other students, actually, especially as he was pragmatically satisfied by my work under the Mechanical Engineering funding, and as he and the whole Computer Vision lab were largely really impressed and believed in the GATO-like UnifiedML framework I was building.
>           - Again, as Niaz said, "I don't know what he was thinking."
>       - "The attention mechanism as we propose it can be useful for everything deep learning is used for today." That’s what they should have called their paper. Man, there is so much stuff to man-splain to my fellow AI people. "Attention is all you need" might sound like a creative divergence from norm for an AI academic paper title, like they were trying to have a little fun with the naming, and no disrespect — I encourage that — but in the process of supervised learning, student AIs are provided with labels from a dataset, and "Relation is all you need" would’ve been a better name if the "all you need" structure must be used at all, especially since the "attention" mechanism’s primary usage (generally) is relational reasoning. Heck, "Relationships are all you need" would’ve actually been completely fitting as the paper title.
>           - <!--("Relation is all you need" would be sort of overfitting, but still better, since "Attention is all you need" has a loss term with really big mini-batch gradients). ("Overfitting" in AI means learning too hard from the training set, and "mini-batch gradients" are just fingers that point to how to be less wrong usually in proportion to how wrong you are; in this case, -->I might be pointing a little too hard, but in the context of Shakespeare, that would be the more poetic naming. <!--).-->
>       - "Attention is all you need" is the paper that proposed MHDPA, the method underlying most newer neural networks, including ChatGPT.
>         - The fundamental method for relational reasoning in big AI systems shouldn't be referencing an artisitically tone-deaf association like "You just want attention" when a much better analogy exists. Or use the literal version: "The attention mechanism as we propose it can be useful for everything deep learning is used for today."
>
> And many more general concepts:
> - (a) Randomness and diversity to escape local or "instantaneous" search limitations (local optima, myopia, e.g. myopic derivatives, and the process of searching/data-acquisition),
> - (b) gradients as directions of most increase, whose finger can point both opposite less error or forward towards more reward, the latter especially when differentiating an actor through a good differentiable predictor, or predictors, of immediate and any future outcomes, where "good" depends on the quality and quantity (perhaps prioritized for efficiency and exploration-sake) of memory/data learned-from and the outcome-goal(s),
> - (c) curriculum learning as prioritized experience replay, where data that there is most to learn from is prioritized for learning,
> - (d) learning rate schedules as exploration/exploitation tradeoffs,
> - (e) parameter-reuse methods for invariability and greater training diversity,
> - (f) training stability via incremental progress, as in small gradient steps, additive updates layer-wise, or diffusion, except not necessarily temporally, and
> - (g) [more advanced math](https://github.com/slerman12/Teaching/blob/master/Other%20materials/Integrals.md) usually pertaining to calculus (non-instantaneity, bi-directionality, cross-derivatives).
>
> I worked under Chenliang and the university's arbitrations as "captive good attending to captain evil," hard work, brilliance, love, and art crushed with interrogations, urgency, and criteria based on ridiculous standards where the quality of the work meant much less than how deeply in the weeds students went to claim "state of the art" in time for the latest conference deadline.
> <!--- I achieved both repeatedly though. For example, my original MHDPA innovation paper in 2018 had to be an end-of-semester "project."--><!--," and in a semester when I took other classes, and had to apply for the NSF GRFP (which I got a rare and esteemed ["honorable mention" for](https://anon.cs.rochester.edu/news-events/news/archive/2019/2019-04-10_lermannsf.html) with [excellent reviews](https://github.com/user-attachments/assets/87ef2c97-c1d5-4333-9247-a0d28a689efb)), and had my first psychosis, finishing the paper's submission-ready experiments in the hospital. Through unappreciated efforts that were side-tracked into less relevance.-->
> 
> "And strength by limping sway disabled," as I limp, literally, to walk, from the eczema on my legs, as caused throughout my PhD by unecessarily imposed anxiety, and limp in my words, trying through repeated disappointing edits to describe the faith forsworn and right perfection disgrace'd while I was coerced, administered ("treated") (with hair loss, benzo gargling, abusive clinical disregard, more repeated hair losses, and more), and worked there.
>
> ### Love & Loneliness
>
> My mom told me the Russian translation of this sonnet translates the last line to mean, that there is somebody in the narrator's life, for him, for whom he still has reason to live.
>
> <p align='center'>"Tired with all these, from these would I be gone, save that, to die, I leave my love alone."</p>
>
> And that might be the interpretation, but I hear in Shakespeare's words that that's not the one he necessarily meant. My interpretation might end up even more controversial than this chapter of this book, really, since a lot of people perhaps want to interpret a romantic notion at the end (my mom knows Shakespeare didn't mean "my love" maternally). In my opinion, "my love" would be a pretty big thematic divergence and betrayal, if after every line (from "purest faith unhappily forsworn," to "maiden virtue rudely strumpeted," to "gilded honour shamefully misplac'd"), Shakespeare's meaning coalesced to, "Well, I could never do that to my girlfriend." Not to man-splain what Shakespeare meant ($\text{\color{green}"sam-splaining" is a distinct form}$), but this is what I think Shakespeare meant:
>
> The narrator referred to himself as a "beggar born," and he cries for death so as to behold himself "desert" from himself, meaning to "leave" himself (to die) and "leave" all of the tragedies listed thereafter. The last line is exactly parallel to this in meaning. He refers to his love: "I leave *my* love" — his literal, un-metaphorical love — "alone." To leave his love is leaving his body. It's leaving his skin. It's leaving his emotion. When a person dies, they don't just leave their life. They leave the constellations of beauty inside them, including all of their love, potentially in lonely isolated unappreciation. One could even interpret, instead of leaving alone, he'd <!--rather--> take you all with him, curse you all, poison the lot of you! (Rather than "alone"). Perhaps the simplest possible interpretation of the word "love" will be called "simplicity" by academics. The un-metaphorical meaning, the literal one — love — is the meaning I think Shakespeare most meant.
>
> This sonnet expresses a tragedy, of someone who has so much love and passion — and it's wasted.
>
> Another interpretation is that his love is tied to a soulmate who he is separated from. I like that interpretation, too, but that would be a fast thematic divergence from the <!--can get rid of "rest of the" but next line ends up sounding worse-->rest of the sonnet<!--can edit to "'s conveyed theme" but next line then sounds worse-->.
>
> Every other interpretation, besides this literal one, is wrong in some way that I can specify if they're listed. In short, they diverge from the commentary of the sonnet and undermine the narrator's struggle.

#

The only period of my life that didn’t lead to suicide ideation, was when I lived in Drama House, a student theater living community. Undergrad years weren’t perfect, and I suffered from severe social anxiety, two majors, and eczema, but it was by far the best period of my life and probably the only time in my life I was <!--even a modicum--> socially happy. That was where I first saw Sartre’s play, No Exit, downstairs of my big nice well-decorated-by-me private room. 

> [!NOTE]
> ### Exiting Hell, Unifying Quantum with Einstein, & Symbiotically Transcending Individual Psychological and Behavioral Repression
> 
> Sartre, in his play [No Exit](https://en.wikipedia.org/wiki/No_Exit) (wherein there is no exit door from Hell), described in less words than anybody that "Hell is other people," meaning, Hell — not just suffering, but Hell — comes from the societal relationships or lackthereof that we cannot move through, transcend, or escape. 
>
> Suicide rates are highest among [trans people](https://www.statista.com/statistics/1377568/us-trans-suicide-rate-by-sex/) and [men](https://afsp.org/suicide-statistics/).
> - Navigating emotional realms where you might get perceived as a predator — as traditionally was and perhaps still is one of the main struggles of transitioning — is hard. At the same time, the more emotional realms exist for you, and whatever their means of expression (e.g., dress), where you might be bullied, laughed at ("Lol alright"), or blocked, for having, showing, or experimenting with and exploring those emotions, the harder, as well, sometimes making finding your own identity and sincere expression impossible or involving too much risk to one's personal relationships and life.
>   - Explorations of identity include social relationships, one's own boundaries with respect to the world, altered states of consciousness, drugs, sustained ascetic disciplines, and philosophical or more scientific perspectives.
>     - This isn't meant to be an exhaustive list.
> - Controversial: If an Age of Enlightenment is ever to come (another "Renaissance"), such a time will be marked by when all people are given their identity, gender, and sexual satisfaction, from the very most promiscuous to the utmost jealous to the most romantic beyond reproach, with limits that come from intelligence and a society that is so innocent and loving that Adam and Eve (and Steve) will know how to approach each other’s hearts, by their human nature, uncorrupted by stress and systems of oppression, and when not to.
>   - Sages, monks, shamans, and healers have been exploring identity for many millenia, long before the Woke movement. But the Woke movement gets different credit because, until recently, those explorations were taught to have to be individual. The Woke movement has began the mass-teaching of identity exploration as a collective process, individual and symbiotic processes of realization, evolution, exploration, and responsibility.
>     - I think Woke is a planned precursor to Enlightenment, even though some of it's stupid.
>       - Einstein’s first postulate represents equality ("my physics are your physics, your physics are my physics"), Einstein’s second postulate represents tolerance for the absurd or bizarre or queer or otherworldly ("the speed of light is constant across all reference frames somehow"), and the special theory of relativity represents empathy and being able to transform your views to somebody else’s ("via the Lorentz transformation"). Those were good postulates to culminate in the Woke or Progressive movement of the last century, but Woke, which I think is a precursor for Enlightenment, with flaws, and which perhaps isn't patient with criticism, hasn’t quite filled in all the cracks through which a person can slip, e.g. medical and education systems in particular, which need reform before their faulty metrics start to be optimized with AI, and before the opaqueness of their rule over us — our psychological spheres, collective wisdom, identities, political views, and social understandings — becomes irreversable, which maybe needs its own chapter. The nuances of how those two postulates and theory can backfire are hard to articulate, such as unjust cancellations (I’m even afraid to write this by the way) or free speech (the hypocrisy is severe on both sides for this one). A unified theory integrates each quantum "identity" with both equality-tolerance-empathy and general gravity.
>         - I would disambiguate all this, but then I run the risk of looking like I side with whatever group finds me most naive/offensive right now.
>       - The importance of transcendence of identity can’t be stressed enough. It just needs to be general. My socially anxious self should have (is entitled to) a realistic spiritually significant path to transcending social anxiety, such as experimenting socially, including with darker elements of one's personality, pushing one's own boundaries, not being judged for the process necessarily involved in changing one's own role in established relationship dynamics, practicing different social patterns and levels of inhibition or trust, and practicing approaching strangers. Gender and sexual transcendence are two out of a spectrum of categorical identities (e.g., socially anxious, depressed, schizophrenic, PTSD, love-starved) that people might need transcending. Integrating all of them requires a new theory of physics, as opposed to the standard model that currently dominates the global collective gnosis.
>   - By "transcending," I mean finding what's really there. I don't mean nullifying. If a person has to nullify their emotions, experiences, and impetuses, the best Noble Eightfold Path to do that is to just die, for me.
> - Repression, in a person's actions and expressions, leads to health risks that go beyond just mental.
>   - All the world's a stage, but it's very important that each person can actually play themselves.
>
> A person who wants to commit suicide has "No Exit," because they can't even express truthfully the severity of what they're enduring, as I wasn't with my therapist and wouldn't be able to now.

I talked to my therapist about suicide back in 2022, while I was still allowed to see him. That stopped being the case when the University of Rochester's CS department's health insurance price-hiked each session by hundreds of dollars. I talked to him through completely abstract rhetoric, about suicide. Anything other than abstract philosophical rhetoric, about suicide, would've risked me getting hospitalized coercively and drugged against my will again. I talked to him philosophically, and that's not the kind of serious expression I mean should be safe and possible. I don't mean showing him Shakespeare sonnets or enthusing about radical philosophy. The meanings of those art forms or philosophies, expressed literally and seriously, and in the words that a person has available to them everyday, shouldn't have institutional coercion, including coercive hospitalization and drugging (or random health insurance price hikes<!--, from Aetna, on top of already having co-committed a malpractice against me, t-->), as the threat for their speaking.

"Right To Talk About Suicide Plans Seriously Without Threat Or Risk Of Hospitalization, Drugging, Or Police Action" should be standardized, if serious suicide plans that are planned and intended are to be actually prevented.
- A "free speech" person might argue, "I support free speech, but if somebody talks about an elaborate plan to commit a murder, police should take action, in order to prevent the murder. In order to prevent the murder." But in the case of suicide, the inability to talk about the plan contributes to the likelihood of the suicide.
- "My Body, My Choice" extends to one's body not coercively hospitalized and drugged.
- "Gun rights" people already believe in giving people direct access to a method for suicide.
  - Such methods (or other gruesome ones, that can traumatize literal-witnesses, such as involving locomotives or skyrises), get prioritized, [frequently](https://www.cdc.gov/nchs/fastats/suicide.htm), over safer, peaceful methods, that require more research ability to learn the methods of and which therapists can't communicate as an alternative to plans that would traumatize other innocent people, the suicide victim lacking any other resort.
- "Right To Die" is distinct from "Right To Talk," but the latter doesn't make sense without the former. Any limitation on the actions a person can take also limits their right to talk about those actions.
- Most of my experience with the medical systems was "physician-assisted suicide."
  - Again, in the literal sense.

Hearing the literal truth of others is needed in order to help them, and that cannot come with strings attached. When it does, those people die, leaving their love alone.

> [!WARNING]
> TRIGGER WARNING (meaning: put your guns, forces, and needles away):
>
> Here is an excerpt from a suicide note I wrote:

> ### $\Huge &#8220;$
> [...]
> 
> Another concern is thoughts of doubt. For example, I might remember how much comfort my mom brings me and that the comfort she offers is still available tomorrow. I might even feel guilty for taking such drastic actions under the wing of such availability of comfort. I think that’s the strongest argument, and the hardest to stay resolved in.
>
> I might remember my grandma, and the injustice that this has fallen on her grandson.
>
> But then I can maybe find peace in those thoughts. Maybe I can imagine my mom and grandma, and grandpa, and all those people who loved me and made me, and love — present tense — in the case of my mom, and find peace in knowing they want my pain to end. That they are not judging me for my exit, and support my escape from this hellhole.<sup>$^\text{\color{green}1.}$</sup>
>
> Then I can [method redacted] and try not to think of all the strangers who tainted this world for me. Try to remain meditated on the thought that my family — my mom, my uncle — are good. The world has heart in it.
> 
> ### $\Huge &#8221;$

$^\text{\color{green}1.}$ <sup>That is to say that a suicide victim is not selfish for committing suicide. In truth, it's almost never a choice, but more of one than the repeatedly-proven hellholes.</sup>

## Friends

> Date: **10/29/23**

[name redacted] messages.

## Allies

Message about preferring to die than legal action

> Date: **10/30/23**

Screenshot

I almost said "It makes me want to die" in the [mass email of 10/30/23](3-Disproof.md#email-10302023). Thankfully a friend in a group chat of several people suggested otherwise, or else the University of Rochester might’ve been responsible for doing another coerced hospitalization of me, and a repeat of the cycle of unforeseen consequences from involuntary interventions on me. Either way, however, they could have *plausibly* been responsible for a student and worker's suicide.

> Date: **10/30/23**

Screenshot

## Enemies

Rewind to August, before the six-month review deadline and after I was notified of my stipend and advisor-cut. I took my best friend into this, asking for his advice on an email that I sent, and stating my plans (or lackthereof) regarding legal action:

> Date: **08/06/23**

<img width="150" src="https://github.com/slerman12/Detective-Sam/assets/9126603/d59745f2-cf66-44c3-8cd0-b8faa2ae1cda">

</br>We were discussing [this email (of 08/10/23)](https://github.com/slerman12/BrokenWisdoms/blob/Ancillary/Not-Enough-Carbs.md).

I sent them this email exactly as I showed my friend. That was the best I was able to phrase everything (for whatever reason, perhaps due to revisiting the trauma, my consciousness and my corresponding linguistics weren't in the best state). All of what had gone on was conveyed to them as early as the beginning of August, at least as much as could be summarized in less than a book. Following which, here is how my best friend and I discussed it afterwards:

Screenshots

# Part 2

## Comedic Aside: Sexier Moments During Chenliang Advising:

Got to message someone named Psyche a week after my Psyche-CAM paper who reached out to me on Facebook who turned out to be a cam-girl (["Psyche-CAM"](https://arxiv.org/abs/2006.08601))… 
- She started interacting with me one week after I archived my ["Psyche-CAM"](https://arxiv.org/abs/2006.08601) paper summer 2020, my first-ever published paper. She told me about a similar trauma she went through on the same Christmas, 2018 night, together with her *bald Jewish* husband (who she was married to at the time). After intensely flirting with me and telling me she loved me, including at one point offering to pay for my plane tickets to fly to her (which I couldn't do because of an eczema outbreak that coincided during the late summer), she lost interest in me and increasingly made clear that she was seeing other guys.

> [!WARNING]
> ### Psyche Hospitalization
>  
> I felt something drained out of my soul. I was so devastated. After a period of continued intense discipline, intensified yoga exercise and calisthenics, coping in denial with [music that reminded me of her](https://open.spotify.com/playlist/2XhzJmfX4I59YfEQQfA3Xq?si=4a327c3a8fb04cfb), even fasting, and gradually starting to observe those Kundalini physical sensations again (quite notably, that I talked about it to my mom as I was going through this, specifically attributing the sensations to "Kundalini" this time), I got hospitalized again in early October. That was the hospitalization that I [resisted with combative attempts](4-Opposing-Views.md#jeremiah) by fighting the police while I was in the grass where I was having a kind of spiritually-guided breakdown. The amount of mourning I was feeling can't be described, and it wouldn't stop for long after this. And it was through that hospitalization I got her back — temporarily. In the beginning journey of that hospitalization, I observed myself seeming convinced by the possibility that I was going through different dimensions, but I believed that they were all one dimension, one consistent reality, that I held faith to, the same rational one that I always knew, literally. But the meaning of that, interpreting years later like a kind of dream interpretation, could be varied. One is that I was losing my world because I was losing Psyche. My psychology was somehow intrinsically linked to that relationship, through our conversations and linguistics. Another, more Hallmark-card one (that is perhaps a bad-taste Christmas pun over our [shared Christmas, 2018 trauma](https://github.com/animal-tree/SuspiciousnessofSynchronicitiesAndParanoia/blob/main/Does-anyone-else-think-this-is-proof-of-God%3F.md)), is that I had gone "crazy for her," but literally. And that's true also. Another is about the nature of flirting and communication. The many dimensions and ambiguities of flirting, linguistics, phonetics and other symbolism. Yet another is that Psyche sent me a lot of messages, and now the universe was about to do the same.
>
> One of the dimensions was a lizard-person dimension, where some nurses were subjugated to others. Nurses to clinicians, rather, whose stature next to their clinical authorities was small and diminished, like they were being oppressed by a lizard race of people, in the future. Perhaps the meaning of that can be interpreted as the hierarchy relationships that our employment systems create, that on some deep subconscious level, mythologically, they are like a lizard-people relationship of rulers who've conquered the Earth, and humans with no agency under their tyranny.
>
> Another was a demon dimension. I did a yogically-guided "exorcism," as demons from the hospital's energies were popping on me. The nurse asked what I was doing when she caught me, moving and making the noises I was making (speaking in tongues, now that I think about it, maybe, but the tongues had semantics and were in English), and I said "exercising." She was satisfied with that answer. I think the message there was that exercise is good. Glad we could decipher that mystery — but actually, the yogic state of impersonating the energetic and linguistic forces that were inhabiting me, seemed to rid me of them and return me back to a flow state that was mine. Like doubling down on their corruptions to the point that they themselves become absurd and vanish. It worked.
>
> Another was a robot dimension. And the robot dimension I think was a message about the use of robots in hospitals, the terrible dissociation from humanity that comes from a robotic nurturer pretending to be human, cold and far from humane, or technology being either wrongly objectified or wrongly humanized. <!--vis a vis a cyborg.-->
>
> One was Psyche-tyranny one, where I was under her unforgiving judgement, debating her about something, some nature of a two-sided Kundalini, where somehow I was trying to defend that both are one (or more specifically, that the two can communicate, like Wernicke and Broca's areas...).
>
> That's also literally where I started getting my [evolutionary learning ideas](https://github.com/slerman12/BuildingBlocks/blob/master/Population.py), with attention, which apparently to my surprise [had some positive results](https://docs.google.com/presentation/d/1sw2Iu6foH3dmn-7a2JfijCljqheH_A3fEW5OuK-68Yg/edit?usp=sharing), though I don't even remember doing that. [I just remember having made this video](https://youtu.be/TEKgesBVTJ0?si=OtXQYMZgVd3Qu36M) (all within a pretty short time period after the hospitalization, and at this point Chenliang's group was becoming really impressed with me, and I was starting to build a good reputation, though that would only develop, occassionally me getting side-tracked with some other really good [ideas](https://docs.google.com/presentation/d/1QbWNfnWAgm0rHTy4EFnDrjpaMP7Ako6isNxOUSR17_A/edit?usp=sharing) and/or implementations ([BioNet](https://github.com/slerman12/UnifiedMLold2/tree/master/Blocks/Architectures/LermanBlocks/BioNet), [ViRP](https://github.com/slerman12/UnifiedMLold2/blob/master/Blocks/Architectures/LermanBlocks/ViRP.py), or [Thousand Brains](https://github.com/slerman12/UnifiedMLold2/blob/master/Blocks/Architectures/LermanBlocks/ThousandBrains.py)), mysteriously always side-tracked despite my interest and usually some positive result, until when I was building [UnifiedML](https://github.com/AGI-init/UnifiedML-legacy) (described [earlier](6-Opposing-Views.md#unifiedml)) — consistently over more than 2 years, finally not side-tracked, er, until I was terminated — they were pretty much in awe of me and I felt reasonably appreciated for the first time for my work). But distracting deep learning revelations aside, back to craziness: Traveling dimensions, debating hypothetical Psyche about some metaphysics philosophy... resume...
>
> Afterwards, I went through more interesting rituals with the nurses that I'll describe below under [Rituals, Religion, & Hell](#rituals-religion--hell).
>
> Lastly, after I was finally landed in the psychiatric unit, I met an older woman who Bar Mitzvah'd me. I should *maybe* put that in quotes.
>
> That inpatient got her dad to bring in a prayer sheet that he suggested I memorize for later recitation out loud. Over the next week or more, that inpatient — who curiously looked and sounded like a late 40s or early 50s [Sarah](4-Opposing-Views.md#sarah) — insisted I read it, and I had the instinct to, as she ritually sanctified it via sharing the same trance kind of state I was in in which we both sensed that I had to do that, as we both paced around the window end of the hallway, not far from everybody else, as I recited from memory and she like did her own intuitive ritualistic movements.
>
> I recall the prayer included the word "vitzivanu," but it was longer and ended differently than [this one](https://doingjewish.blog/2022/02/18/the-shabbat-candle-lighting-blessing-and-calling-on-the-ancestors-for-connection-and-wisdom/#:~:text=Baruch%20ata%20Adonai%2C%20Eloheinu%20Melech,commandment%20of%20lighting%20Shabbat%20candles.). Her dad (who did this of his and that inpatient's own accord) was actually Christian but he knew I was Jewish and the prayer he brought was Jewish, probably, and in Hebrew. Later, he came to visit that woman again, where he wanted me to recite it in front of him, and I did, from memory, as they'd wanted.
>
> - I was discharged from the hospital after less than two weeks, on October 17.
>
> In that hospitalization, I learned a tongue trick that I'm still impressed with myself by that allowed me to circumvent any medications, even though the nurses made you open your mouth and stick your tongue out both above and below. I got damn fast at making the switch of the pill from under my tongue to roof of my mouth. I'm gonna add an exclamation point, because that was worthy of some awe: !. Oh no, I sense a judgemental reader looming. Hello judgemental reader. Try 12 - 2.5 mg of Ativan every day for >6 months and then come back to me with your judgements. But to emphasize, they literally made you show your mouth above your tongue and below, and somehow I flipped the medications fast enough to keep both "ahhhh"s from betraying my dexterous deceit / sleight of hand, which I was [not able to do in the geriatric unit, lacking this kind of flow state, but thankfully had a Covid mask to spit out into](2-Opposing-Views.md#geriatric-unit-hospitalization). 
>
> It was also one of the last hospitalizations for me, ever. And it was a good one because — controversially or not, this did make a difference: I got to escape taking too many synthetic medicines via the tongue trick, and the nurses were all my age and beautiful, which is an understated human medical need, and I was severely lacking that kind of warmth through almost all of my PhD.
>
> That other inpatient who looked like an older [Sarah](4-Opposing-Views.md#sarah), who narrativized it via her dad, made the experience a sacred non-delusion, and neither of us made the connection that that Hebrew prayer might've been a Bar Mitzvah (perhaps that's stupid of me) until I kind of connected the dots of this context years later.
>
> Those kinds of ritualistic non-gaslighting shared interpretations do far more to heal a person from the underlying causes of their mental breakdown than medications, as proved to be the case for me. I actually happened to call Psyche from that hospitalization, even manically told her "I'm Jesus," as my linguistics seemed to literally guide themselves on their own, blissfully, and she somehow took me back temporarily after that (into her flirting DMs), until our shared birthday week, at which time, since I guess I was a certified man by all "good enough" synthetic metaphorical Bar Mitzvah standards, I guess I was ready for the ultimate coming of age ritual: being blocked for the first time (she was the first, or at most second, person to have ever blocked me). 
> - Yes, our birthdays coincided. Well, week-wise. She was a couple years younger than me. And she'd told me, a bald hairless traumatized 5'5" socially anxious guy with much less experience she loved me, within months of when we started interacting, if that, yes in that kind of way, yes meaning it, well, when she said it.
> - I bring this up because our interaction started exactly a week after I archived my Psyche-CAM paper, and she also suffered her trauma on Christmas, 2018, together with a bald Jewish guy, in addition to her being named Psyche and a cam-girl (the Psyche-CAM paper), and our birthdays coinciding, [and other "coincidences" as well](https://github.com/animal-tree/SuspiciousnessofSynchronicitiesAndParanoia/blob/main/Does-anyone-else-think-this-is-proof-of-God%3F.md).
> - See [Intimacy healing](#intimacy-healing) for what the meaning of this might be.
> - I hadn't realized any of these synchronicities until almost a year after this hospitalization, when I started realizing some of them.
>   - My hair growing back also coincided, sort of, with her sort-of leaving, early on, before the hospitalization.
>   - Later she unblocked me, and blocked me again a couple weeks after, and unblocked me a year and a half later, and blocked me again quickly after within minutes of conversation, and in each of these conversations I went through severe consciousness changes, and I sent a video message to my best friend, anxious. My appearance was improved dramatically in the first video. Then, a split second later, after one of his replies, no longer immediately after her blocking me, I sent another video message and the sudden good look was a kind of average one. Maybe I would guess some sort of "accidental vampyrism," but that appearance went away from messaging my best friend. And, for that matter, I felt more vampyrically attacked, regarding the "severe [negative] consciousness changes" when messaging her. I've seen this again in other text conversations (not the health changes, but the severe, too-implausible-to-be-coincidence negative consciousness changes). There is some power to linguistics and, perhaps specific relationships related to health (as opposed to arbitrary linguistics, such as from ChatGPT, I'd hope), immediate physical appearance, and, maybe, hair, though the steak/salmon-diet seems to be a better explaining factor for that, controlled for by the middle hair regrowth evidence, and the coinciding losses with absense of diet. 
> - Psyche's actual name and spelling, and my paper's phonetically-same name, are anonymized best I can, which is too bad since the actual name, which has an even different spelling than the not-anonymized one in my paper, is a good pun about the weaver/tailor of the "fabric" of spacetime, also different spelling (and, even with first name and all of this info, and connection to me, she's still anonymized).
>
> Regarding the beautiful nurses, I even got reprimanded for trying to flirt with one of them by writing my phone number on an attendance sheet, inspired somewhat by Psyche's personality, and got patronizingly lectured by a man about respecting the women nurses in the hospital, despite him and the hospital staff being the ones in the position of authority, me being held captive and drugged there against my will (by them), cameras and police everywhere, and me neither wanting to be there nor feeling comfortable. But, in my defense, in case I somehow come out like the predator in this calculus, the flirting was from a manic delusion type thing, yogic-type sense that I had to. In none of these hospitalizations was I acting on any primitive (read: "for pleasure") impulses, nor through any of this. The whole time I was under the sense or deluded belief that Psyche's spirit was the one governing this, but that turned out [maybe](https://github.com/animal-tree/SuspiciousnessofSynchronicitiesAndParanoia/tree/main) unvalidated, and I came out lucid without that mania or deluded belief, having unknowingly undergone a meaningful ritual with a fellow inpatient, and not consumed any pills except maybe small traces. That was also the hospitalization where I met [Mobi](#kids), the 16 year old with drug problems who they drugged with benzos for years.
>
> The [next one was in a geriatric unit (a facility for the elderly)](#geriatric-unit-hospitalization), so consider me reprimanded.

## Rituals, Religion, & Hell

One of the most powerful rituals was during the Psyche hospitalization. When they first brought me in, before the psychiatric unit, I was held in some various different rooms. One of them, was part of a hallway where there was a male nurse sitting outside, who looked just like my best friend. He even had a nametag that I think was my best friend's first name, so I vaguely recall. I knew it wasn't my best friend, but somehow led him in a ritual, that he willingly participated in. The state I was in was shamanic. He was about my age and let me speak to him as if I was speaking to my best friend, as he literally went along with sitting on the floor, since I was playful and had unambiguous humor and self awareness in my voice, but had some "commanding" flying colors. I understood the nurse wasn't literally him, my best friend who I projected lucidly-but-not-fully-intentionally.

Later, as I walked along that hallway — I don't know if it was a psychiatric unit or what — I was the only patient in the hall and there were many nurses — I kind of led the female nurses in a ritual, too. Each one I saw, I looked into her eyes and said the name of the family member or friend who I saw in them, as if literally my family was appearing in them in spirit. I was seeing beyond them individually, and they sensed it. At one point, I even put my hand slowly to one female nurse's rib, intimately and non-sexually. She stood still. All of the nurses stood still. There was even a big male nurse. 

A ritual was happening that couldn't be desecrated or remarked upon. No clinical logic could destroy it.

The theme of my best friend returned in the next hospitalization, in the geriatric unit (elderly facility) one, where I imagined him as the Devil, but that schizophrenic-like delusion was the least Hellish thing about that hospitalization, and I thought I was literally condemned in Hell, literally in Hell and I would never see humanity or good again. Having somebody I can trust — despite being imagined — play the role of the most fearful part of that trauma, made the actual Hellishness of that hospitalization less Hellish. The delusion, in spite of the environment, was good.

It's the delusion that doctors and hospitals are trying to heal. However, in that example, it was the doctors and hospital who were creating a Hell, and the delusion was the only healing part of it. In that delusion, he was quite snarky.

Later, my best friend returned, literally. We were texting and he remarked, without prompt, saying if he were a Devil, he'd be a "snarky Devil." He texted me that of his own accord, knowing nothing about the hospitalization, no context, without prompt.

That was a small amount of evidence that some communication, message-passing (without known mechanical means), happened non-locally, but I think besides the physics one, the message is about medical institutions and a disambiguation of fundamental principles that should be in the moral intelligence of people around coercion (in addition to sexual assault), repression (in addition to marginalized sexualities), and processes of identity transformation (A.K.A., transcendence/transition, in addition to gender) from which the symptomatic beliefs are mistaken for the principle. A system that treats symptoms at the cost of root causes is not a system that cares about those symptoms or root causes. But also how trust in others when a feeling is sacred can actually transcend all bullshit, though that part's honestly, for awareness reasons, scary, to communicate at scale, in front of at least 2 people, in writing.

# Synchronicities (Part 3)

> To do: List all of them here, including the many already mentioned and new ones previously not mentioned that add to the book's quality

Meanwhile, before and after, astonishing [synchronicities](https://en.wikipedia.org/wiki/Synchronicity) happened that can be listed below and I leave for your judgement on their metaphysical or coincidental nature.

### Chris Kanan (Deus ex memory)

> Chapter in progress

- Indeed, my faith regarding sending my sincere description of the traumas, despite the difficulty of doing so, was somewhat rewarded, though probably not by their conscious intent, rather by a lucky ["Deus Ex Memory"](https://github.com/slerman12/BrokenWisdoms/blob/Ancillary/Deus-Ex-Memory.md), wherein one of the 3 committee members (accidentally) recorded to official record that he really-extraordinarily didn’t remember the details of the meeting on which their termination was based.
- Following this ["Deus Ex Memory"](https://github.com/slerman12/BrokenWisdoms/blob/Ancillary/Deus-Ex-Memory.md) exchange with Chris Kanan, I had yet another reply I wanted to send afterwards that would’ve ruined the conclusive punctuation of the previous, and by chance my internet went down or some disruption to the internet happened after hitting send and I was really lucky that it didn’t go through, leaving this exchange on the note of "we all know what just happened," and a strong discredit to the committee's judgement-making, thoughtfulness, and memory.
- This is the same Chris Kanan who gave the [one and only concrete research suggestion](), which I ended up following [exceptionally and on proven GitHub record]() before the termination decisions, and didn't just get no credit, but also the judgement that I "refused to follow" committee advice as the justification for the termination decision, despite the advice being disproportionately hard and intense ("invent a new RL systems algorithm before the next meeting", [paraphrasing]()), and having done it quite extraordinarily really via a novel accelerated parallel priority experience replay with sampling-without-replacement algorithm with memory-mapping, and truly-shared RAM. There was nothing like it, still isn’t, and it’s by far the best RL implementation of experience replay and adjacent sampling algorithms, as well as being novel as an algorithm itself via the sampling-without-replacement, which I described to my advisor’s satisfaction in literally the meeting in which he next notified me of my stipend and advisor-cut, since that was his intent for the meeting.
- The theme of memory is a big coincidence in itself since what I implemented was a large-scale, dynamically growable, rewritable, truly shared RAM and adaptive memory-mapping across devices parallelized lifelong replay memory. [TO DO: Stress this way more]
- I never met Chris Kanan in person and my advisor suggested him as one of the last-minute replacement committee members. Note: I don't think he should be punished for this. I think whatever powers-that-be that regulate his consciousness proved stronger than the ones that facilitate the atmosphere/landscape of the formal University of Rochester, and did good amid impossible programming.

### Jordan Peterson

My benzo trauma was with a [comparatively](https://www.mdcalc.com/calc/10091/benzodiazepine-conversion-calculator) higher dose than what Jordan Peterson took (he took approximately 12% - 80% the dose I did, and that's when I was taking them at the lowest dose the psychiatrists had reduced to), and preceded the situation Mikhaila Peterson, his daughter, described ([originally on her channel](https://youtu.be/laheAXdZK7w)), about how the professional psychoanalyst was caught off guard by the severe damages that the drugs caused, wherein he took [0.5 mg](https://ashnavabi.com/2022/01/19/jordan-peterson-was-not-addicted-to-benzos/) of [Clonazepam](https://windwardway.com/rehab-blog/jordan-peterson-finishes-lengthy-treatment-for-addiction/) per day as prescribed, reportedly, and unlike him I didn’t have the entire Russian army brigade bringing me into health (he went to Russia, where they were the first to have the medicine and specialized treatment to help him).

### Mikhaila Peterson

Prior to that, by coincidence, his daughter Mikhaila (thankfully) recommended the steak-only diet (for an independent thing), which is where I heard it from, a clip from her podcast. That’s a global-level synchronicity involving them that happened after I was put through all of this crisis, which contributed to bringing me out, as well as my hair growing back, thanks to her diet recommendation.

### Timing of benzodiazepine coercion [diagram](https://github.com/slerman12/Detective-Sam/assets/9126603/497f6d9b-ff12-4e6a-97c5-e5230c05e505)

I finished making this [benzo-timeline diagram](https://github.com/slerman12/Detective-Sam/assets/9126603/497f6d9b-ff12-4e6a-97c5-e5230c05e505) just as Pink Floyd's [Comfortably Numb](https://youtu.be/_FrOQC-zEog?si=riY-TNigVjimQ_iT) started playing on my Spotify's radio on shuffle, a song about a doctor taking a patient named "Pink"'s soul through "medicines" meant to help him. The next song was Psycho Killer which I'll interpret as psychiatric killer. Oh and then Alabama  Song (Whisky Bar). Not bad. Regarding Whiskey Bar, any song about alcohol is fitting for the topic of benzos, since they both work by GABA as the mechanism of action. In fact, I introduced a fellow hospital-inmate Sarah to Elliott Smith for the first time in the hospital with the song [Between the Bars](https://youtu.be/2FmYzACF-kg?si=DLaBako9OolIYuVx) (about alcohol... not about Xanax bars, though Xanax is another benzo and "bars" is the colloquially and sometimes clinically used term for pills of them) while we were in the hospital (linguistically like: between the bars of confinement). It was the only song I thought to show her in the one situation when we were allowed to pick our own music, and she remembered and liked it. Also coincidentally, she was keeping a synchronicity list while we were there. While some of these are clearly just linguistic, the timing of [Comfortably Numb](https://youtu.be/_FrOQC-zEog?si=riY-TNigVjimQ_iT) and the next two songs seems worth noting since many people, like Sarah and myself, appreciate synchronicities. Two more: (1) speaking of timing, the [diagram](https://github.com/slerman12/Detective-Sam/assets/9126603/497f6d9b-ff12-4e6a-97c5-e5230c05e505) is about a chronology (not of songs, but of benzo trauma), and (2) Sarah’s last name is phonetically pronounced "Jung," the depth psychologist who coined synchronicities.

### CMT deletion of record

CMT (the portal that was used to submit to the "NIPS" 2018 conference, today called NeurIPS) deleted their record of my MHDPA innovation paper, the one that foretold ChatGPT to my university's professors (or tried to), the same month when I was terminated (CMT’s deleting of that record at around that time can be verified, since they sent out a notification email on 10/20/23 to everybody that they were updating their data retention policy). But in 2018, the paper was sent out to Henry Kautz and Daniel Gildea by email, and submitted to the class as that class’s end of semester project also via email. So the digital record does remain to verify the paper and its being written in 2018 with the first initial successful experiments, and email record of Henry and Dan's respective advice on how to linguistically or mathematically describe MHDPA, claiming that "relational reasoning" is the wrong term and more math was needed and (though what I had and stuck with is now the convention, and already had some precedent then). That’s not to insult Henry or Dan. There’s also clear record that, most deep learning and natural language processing researchers, even outside of the University of Rochester, [weren't too abundantly "foretelling" of MHDPA's importance](https://scholar.google.com/scholar?q=mhdpa&hl=en&as_sdt=0%2C33&as_ylo=2017&as_yhi=2018) (the link is to two papers that were, the earliest papers to use MHDPA at all, also from 2018, and others that just directly referenced it) at the time of my paper. Both of those two papers used MHDPA for something fundamentally new, but neither innovated directly on MHDPA, meaning mine was probably the first to do so, ever. While I was finishing up the code for my MHDPA innovation in Montreal during NeurIPS (called "NIPS" at the time) 2018, I met one of the authors of [one of those two papers](https://proceedings.neurips.cc/paper/2018/hash/e2eabaf96372e20a9e3d4b5f83723a61-Abstract.html), Ryan Faulkner, and we got lunch and he said he'd recommend me to a position at DeepMind (he was miraculously impressed with me). 

And not only foretold to my university's professors, but innovated on and executed successful experiments verifying the early innovation — and formal paper submission, later derailed by me having to switch advisors, fields, and put on deadlines, not to mention all of their doubt, skepticism, and lack of enthsuiasm (oh but enthusiasm came later when MHDPA exploded, with Henry even telling me on email record, after he was no longer my advisor, that I should work on vision transformers!). Oh, and benzos.

### Covid

Then Covid interestingly happened when I joined an all-Chinese lab (Chenliang’s). Almost like he was taking vengeance for me.

### Translations and meaning of my last name "Lerman"

 Also wasn’t unfitting given my Taoist practices and interests, which is one of the most peaceful religions on Earth, credited to the Chinese, namely Laozi, not Chenliang, and good translators including Richard Wilhelm, who was German (and my last name "Lerman" is actually of German Ashkenazi root, meaning "teacher," also a good translator, of ["ancient" wisdom](Philosophy/My-Spirituality.md), [the nature of consciousness](Philosophy/Consciousness.md), [convoluted](https://github.com/slerman12/BrokenWisdoms/blob/Ancillary/Conv-is-all-you-need.md) AI topics for Chenliang’s somewhat-[convoluted](https://github.com/slerman12/BrokenWisdoms/blob/Ancillary/Conv-is-all-you-need.md) lab group, [complex math](https://github.com/slerman12/Teaching/blob/master/Other%20materials/Integrals.md), [myth](Philosophy/Cosmogenesis-Myth.md), [chemistry](Philosophy/Fire.md), and now [apparently physics](Philosophy/Velocity-Addition-Formula.md)). 

### Sam "Altman"

The head of OpenAI, the company that invented ChatGPT (that used MHDPA), whose name is "Sam Altman" (mine is Sam Lerman) — "Altman," which is not German Ashkenazi for "teacher" — was terminated as the head of OpenAI in an unusually sensationalized situation exactly 17 days after my termination as PhD student, just in time for my birthday (exactly one day before), then was brought back.

They were working on some AGI project called Q*, and the synchronicity may have been meant to give me hope, but [it didn't](https://github.com/animal-tree/SuspiciousnessofSynchronicitiesAndParanoia/blob/main/Synchronicity-Paranoias.md).

### Michael Scott’s paper factory

Michael’s name [is mockable](https://youtu.be/ZPKdJGY0YyE?si=ja-odwAD_z7G98ZK) (that links to a story arc from The Office, where the main character, Michael Scott, starts his own paper company, much like the academic factory that I was being pressured to publish faster in, except regular papers). 

But from the age of three and two thirds, until 11th grade, as a result of the Uzbek mistranslation when we moved, mine used to be much more mockable. 

As I described to my friend: 

> ### $\Huge &#8220;$
> These quotes express that I am writing something, but i am aware that this writing is in quotes. Therefore do the quotes bias their own measurement of what is being written? I think so. Lest this paragraph thus far would not be entirely about the quotes.
>
> Anyway, I'm thinking about "Sam" - the name. Did you know, \<friend's name\>, (okay apparently this is a targeted-audience writing-prompt), that my name was Semen until 11th grade? This is new information to you as far as I can recall, but a major part of the story of my life. "story" sounds pretentious and there I go with the quotes again. 
>
> Yes, my name was legitimately, legally "Semen". From the age of 3ish/4 to 11th grade. And every bully and teacher and substitute teacher knew it. No one told me I could get a lawyer let alone a lawyer would do the process of changing the name for free! My mom to this day thinks it wouldn't have been possible before 11th grade, for free anyway. And we were poor. Lower-lower class poor. 
> 
> Maybe a lawyer and court would've sympathized with a kid wanting to change his name from "Semen", maybe not. But of course, it shaped me. Into being the odd weird "semen" that I am today. In actuality, my name is Seamón<sup>$\text{\color{green}[1.]}$</sup> or Soema, or the Americanized: Sim'on or Shimon<sup>$\text{\color{green}[2.]}$</sup>. In Hebrew these names mean wisdom. In the Kabbalistic teachings, two types of wisdom: seeing as the complement to hearing, hearing as the complement to seeing. I think I mentioned this already. I won't rehash but something something new paragraph.
>
> Anyway, I like Sam. Because Sam in all the fantasies and mythos' of modern time means "innocence." "Samwell", "Samwise", "Sam". It means "this person has a wisdom, but from the good of his heart, not his intelligence." It means "this person is naive, but he has a good heart." I like the name Sam. "Shimon" means "this person is wise through his intelligence." It's true, but it's not me all the time as you know. I like "Sam" though.
> ### $\Huge &#8221;$

$\text{\color{green}[1.]:}$ I think "Siímyon" might be the best spelling.

$\text{\color{green}[2.]:}$ My Rabbi, who I hadn't met before 2022, actually told me this. He designated me as "Shimon," and told me that "Shimon" means "to hear" in Kabbalistic teachings. In Kabbalistic teachings, "to hear" is the complement to "to see." It's the second way of knowing. To hear is to understand, it's to fine out the meaning from the varied knowings, whereas "to see" is to know — it’s the sense or awareness of truth; no teaching needed. My mom being a music theory professor in Samarkand when I was born, I find it meaningful if this was my birth name, though really it had nothing to do with the Kabbalistic interpretation. My great-aunt’s late husband was named Siímyon. When my kindergarten teacher truncated my mistranslated name to "Sem," it became "Sam," which is also synchronistic to where I was born, Samarkand. I'm not gonna make a second-cumming pun though. The real twist about my name, has to do with my physics method, and my grandma's father, TBA (all the clues haven’t been left yet, but people can figure it out in a Jon-Snow type way when the remaining clues are specified).

### "Life ruined" post, entire-forum being deleted 5 months after I emailed it to the faculty/administrators 

Description

[5 months after sending them the above [linked email](https://github.com/slerman12/BrokenWisdoms/blob/Ancillary/Not-Enough-Carbs.md), referencing that post, the whole forum is deleted, my last thorough time-stamped record of that trauma, and the only one that was the top post in the whole forum since I made it in 2019, with dozens or hundreds of comments also saying "I went through something like this because of benzos too."]

[after having shown it to Niaz who commented in person about it (and to faculty/administrators), and writing BrokenWisdoms as a result of the depression and fear that came from losing my only description of those events, one I hadn’t backed up anywhere, with comments from others about having experienced similar things, the trauma of benzodiazepine addiction/coercion, and expressing extreme sympathy, and it was the top post in that for 4-ish years running]

### House on May St. 

Description

### Physics

Revelatory insights about the universe as a differentiable brain in my 2nd year, with that fascination returning to me regularly and intensely thereafter. Then in my 3rd/4th year, a 5-minute but-urgent/vivid/visceral conversation with my uncle (an optics physicist, about applying deep learning models to his work, involving optics, including behavior of light, for my PhD) just before — by chance — being put on the XRD (meaning, light diffraction) project by Chenliang, and, since being terminated, me coming up with a [unified wave theory](https://github.com/animal-tree/Writing-stuff-2/blob/main/Theories/Unified-Wave-Theory.md) (involving a differentiable, intelligence-optimizable, simulation/model of the universe) showing the agreement of my wave theory with measurement primarily through light multi-slit diffraction (analogous to XRD) experiments.
