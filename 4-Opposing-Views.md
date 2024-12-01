# Part 5

- **University psychiatric ward janitor**
- **University-hospital child and adolescent psychiatrists**
- **University-hospital police officers**

## Henry Kautz

The top-three contest-winning Parkinson's disease progression models I built at the Med Center in college as an undergrad earned me a recommendation back to Henry Kautz, [as well as an embarrassing interview](https://www.rochester.edu/newscenter/undergraduate-students-place-in-top-three-in-parkinsons-disease-data-science-contest-228912/). On top of that, I built [a sleek website interface for Twitter GNIP's involved data mining API](https://github.com/slerman12/TwitterDataCollector) for Henry's research group, and some sundry research projects together with one of his PhD students, and was praised by other affiliates of his that he recommended me to, at [Bryx emergency response](https://bryx.com). As a result of my skill, combined with appreciation for my extracurricular breadth, Henry accepted me into his PhD group as a doctoral student. 

### Fall, 2018 Semester, and the Dead Marshes

- I first injected Dupilumab summer, 2017
- My first semester in the PhD program began in Fall, 2017, with Henry as advisor
- I lived in the [House on May St.](#house-on-may-st) for about a year, when, in 2018, Aetna cut me off from Dupilumab and my hair rapidly fell out
  
After the house on May St., it was from my mom's apartment (in 2018) during a video call with my advisor that I described that biologically-inspired neuron architecture [above](#benzodiazepine-benzos-mechanism-of-action), with the specifics in the [video](https://drive.google.com/file/d/1i5hS2iDVuo24PnGicvn5dIZYXUzDfPAl/view?usp=share_link) comparing it to the LSTM architecture.

I also presented a description of the LSTM cell, then layer, then network, then bidirectional layers with attention, to my Semantic Parsing class from the ground up using that [biological formulation](https://drive.google.com/file/d/1i5hS2iDVuo24PnGicvn5dIZYXUzDfPAl/view?usp=share_link). My fellow PhD student told me in our office that it was really original, and she liked how I didn't use the usual LSTM diagram. The class was impressed with me.

I should add that since the house on May St., I was building a Keras-type framework for long-term memory for the Medical Center, including the semester I did my MHDPA innovation paper, that had generalized neural episodic control into a framework that I could use for disease prognostication, novel of course, and which I’d also suggested could be used for interpreting exactly what measurements of a patient’s history informed the model’s predictions, similar to how attention weights might do today. 

Also in that 2018 Fall semester, Henry made me apply for the NSF GRFP, one of the most competitive fellowships in the world. I submitted a personal background and research plan that got [excellent reviews](https://github.com/user-attachments/assets/87ef2c97-c1d5-4333-9247-a0d28a689efb), with one of the reviewers writing, "This is exactly the type of high-risk, high-reward research that the NSF is looking for to support." I proposed my long-term episodic memory model, biological neuron, and relational reasoning via MHDPA to feed "relational concepts" into a long-term memory.

As I worked on the NSF GRFP submission, I kept asking the I Ching for advice, in addition to Henry, Sri Pai, and Charles Venuto. The former tended to give the most consistent, helpful answers, and for most of the writing process, very positive and encouraging. By the "former," I mean the I Ching, but the three professors also were encouraging, read my submissions, looked at different drafts, and helped. Their opinions contradicted each other, especially on the choice between two versions of the research plan I wrote, where Henry and Sri, both Computer Science, preferred one, and Charles and someone my age I liked, and I, preferred the other. I ended up going with the one the CS professors preferred. It was more structured and rigorous-looking, but less natural, profound, and lacked as much of a deeper philosophical meaning.

Towards the end of the submission, just when I was ready to submit my final versions, including that structured research plan that the CS professors liked, the I Ching's tone had gotten far more ominous in its answers, consistently, suddenly, no matter what I asked it, whether it was the choice between those versions of the research plan, or different edits I considered or came up with. Its predictions were all negative. I submitted what I had, since the deadline was that day, and the result ended up being a very unfortunate "honorable mention," wherein all of the reviews were excellent, except one "Good" that tilted the scale. The last's reasoning? I didn't have enough paper publications, as he'd ["have expected"](https://github.com/user-attachments/assets/87ef2c97-c1d5-4333-9247-a0d28a689efb) from someone with such an interesting submission. Otherwise, it was a good submission, but [without paper publications, he couldn't give me an "Excellent."](https://github.com/user-attachments/assets/87ef2c97-c1d5-4333-9247-a0d28a689efb)

It was a lot of work, but concurrently, amid yet-other grad-level courses, I worked on my MHDPA innovation paper, as the semester project for the Semantic Parsing class. Neither Henry nor the professor had heard of MHDPA back then. Henry critiqued my use of the term "relational reasoning" to describe it, now the convention. Dan wrote that I wasn't clear on the math, and needed more equations. The amount of math I used fully described the method and was/is the convention.

But a strong interest or fascination with MHDPA, in 2018, didn't come by accident. Today, people who've heard of MHDPA have heard of it because of transformers, like the kind that underpins ChatGPT. In 2018, even an NLP professor whose students worked with deep learning models, including sequence-to-sequence attention models, as Dan was, was unlikely to have heard of transformers, let alone MHDPA, and of course Henry for that matter, since his background was in symbolic AI, and included little, if any, deep learning experience.
<!-- , and it was notable enough that he was one of the tenured professors in the CS department who believed deep learning wasn't a fad. -->

After the house on May St., I was coming up with and seeking a method that could do relational reasoning in deep learning. That is how I found MHDPA so early, before it had much recognition or almost any application (besides some groups at DeepMind) in the field. I was coming up with my own concept of relationally-attending-to image-features, and researching to find if anything existed in line with those principles, and (after [Relation Networks](https://arxiv.org/abs/1706.01427)) I found the other DeepMind applications in [reinforcement learning](https://arxiv.org/abs/1806.01830) and [RNN memory](https://arxiv.org/abs/1806.01822), respectively. I was coming up with a relational disentangled-attention type method for use as "relational representations" in a long-term episodic memory, and later how to innovate MHDPA for that purpose, a consideration that led to the innovation I evaluated on a question-answering dataset for my Semantic Parsing semester project, which outperformed the baseline MHDPA. Henry discouraged me from submitting my [paper](https://www.overleaf.com/read/qgmmzgsrctmg#6cd1b9) to the ICML conference. NeurIPS reviewers hadn't heard of MHDPA, (dismissively) compared it to other preexisting attention mechanisms (having conflated MHDPA as my innovation), and critiqued that I didn't have enough experiments. <!-- Adding experiments, back then though, wasn't so easy, because infrastructures for transformers and those benchmarks didn't exist. I programmed in TensorFlow 1.0 and Sonnet, in 2018. Furthermore, it would have gone deep into-the-weeds of something I wasn't primarily building the method for, so I proceeded with a mix of my own plans, as much bigger obstacles added themselves from the medical system, an unforeseeable change involving Henry's employment, and hugely-intensive demands that followed, not just benzos, but in vast majority consequences from benzos, and by the time transformers exploded, the method lost relevance in a saturated field, and I'd already been put on multiple new intensive projects that I didn't have much choice in. By the time I had a chance, I was now answering much more heavily to an overseeing authority, and tried to find time for other research directions that, unlike my method from 2018, at that point were still looking far ahead beyond where the rest of the research zeitgeist was. I didn't realize for a long time that I was the first to innovate on MHDPA, and that if not for the coercion of benzos, I would have very plausibly gotten credit for it.-->

<!--
Henry and I both didn't have experience with deep learning prior to when I entered the PhD program. Up until that summer before my first year as a PhD student, I had been working with random forest models. I had to teach myself—really quickly— and through hard-to-believe intuition, the full state of the art and then some as I started the program, as I took grad-level depth and "breadth" courses, none of which at the University of Rochester were especially helpful, and my professors and students around me had very little to offer.

That being said, and most CS students can relate to this: in college, most of what I learned was self-taught. That of course didn't change in the PhD program, as the professors were still bad teachers, except also didn't know anything about the material that would need to be taught, the state of the art of their own fields, yet. 

I'm not trying to be mean to anybody. This is the truth. It's hard to express, because it implies that the world is bad, that people with authority are stupider than they're credited and esteem themselves, that they're not just stupid, but actually really, really, like really stupid, and in vast majority. THAT might make writing and reading this hard. It might make it hard to believe, if you haven't seen this for yourself, as a student. I'd say the same about the other PhD students though. I'd say this about every professor and PhD student who was in the CS department. Not personally, not that they're always stupid, but that, in general, they were. Undergrads maybe see grad students as knowing so much more, but those grad positions, and professorial, don't require intelligence to earn, usually. In most cases, actual intelligence, or anything actually novel, would get in the way.

Most people get into those positions through natural memorization ability, or obsessive memorization, and then make some minor deviations from what was taught to them that they call research, and that combination of memorization and very-linear tinkering gets esteemed if they're able to write it up in the standard academic jargon. That last part—jargon—is most of what academia beyond the memorization-stage requires. Even those professors who make a dent, often get there by luck, usually around a really simple idea sufficiently complicatedly executed.

In med school, the ability to memorize which prescriptions correspond to which diagnoses, and which diagnoses correspond to which symptoms, and which anatomical events correspond to which symptoms, is something ChatGPT-like AIs can pass [exceptionally](https://arxiv.org/abs/2404.18416), with [even better bedside manner](https://www.nature.com/articles/d41586-024-00099-4).
-->

I went to a conference that year, NeurIPS, 2018, in Montreal. At the time it was called "NIPS, 2018." I met the DeepMind researcher Ryan Faulkner, who co-authored the [RNN memory](https://arxiv.org/abs/1806.01822) paper, that innovated on the RNN cell by applying internally the MHDPA method, who was so impressed with me, perhaps because of the really-concept-understanding comment I made at his poster session about disentangling something in their memory cell to improve their method (independent to what I'd been researching, completely to do with his method), that he invited me to lunch, and during lunch, as we were talking, he said he would recommend me to a position at DeepMind if I applied, back in 2018. 

I was walking around Montreal with headphones in my ears, listening to Of Montreal by momentum from listening to it by coincidence before the conference, and working, working really hard, in my hotel there. There was a group chat for people visiting for the conference, and lots of social events that I missed. I wanted to go to a hot tub party, but ended up working. I wanted to go to "strip karaoke," but was practicing strict ascetic disciplines, and asked the I Ching. The I Ching gave a resounding no. On the floor of my hotel, I cast the Feng Shui coins, and got the ominous hexagram "Decrease," and to my regret (having never gone to anything like either of those things), I listened, stayed in isolation, and worked. The snow outside was beautiful, and at least I walked from time to time to explore and to get groceries. "Organic" food is apparently called "biologique" in French.

I met Jürgen Schmidhuber in the conference itself, at his talk, was the last in line, had to wait longer than everybody, then talked to him a bit, he was friendly, and he shook my hand. I sent him a followup email, he replied, and it meant a lot to me.

I was wearing a hat all through the conference, to cover up my baldness, that I still wasn't used to, and still am not. It was winter, and the winter hat didn't look too out of place. Early December, less than three weeks before my RGH hospitalization.

The encroaching mental state on the social and self-image-based fronts <!--began its march-->escalated from the hair loss, in particular [about my confidence about my physical attraction.](https://www.reddit.com/r/socialanxiety/comments/dzx7or/not_to_get_into_toxic_territory_but_sometimes_i/) <!--Can also link: https://www.reddit.com/r/spirituality/comments/1dyn2es/comment/lce3ie3/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button-->

When I returned, my isolation on the work-based front deepened, as I was getting ready to submit my MHDPA innovation paper, coinciding with my first-ever hospitalization, the second time my frontier research ideas (the earlier alluded to in part in the [House on May St.](#house-on-may-st)) coincided with a sudden major health crisis, either 100% externally caused in the first instance, or unprecedented for me, almost suspiciously so<!--,--> in the second. 

I was also doing yoga, together with meditation and pranayama, every day, intensely and in deep trance through each session, by myself on a yoga mat or the floor, a yoga taught to me through the advanced technique of TM, that was being taught in tandem with a meditation retreat at a zen center I went on, earlier on my 23rd birthday, on November 18, 2018, where one of the instructors actually learned that it was my birthday and brought me cake and got everybody to sing happy birthday for me. It turned out, rather ironically/unfortunately, it was somebody else's birthday that day or weekend, too, who was in the large dining area where the instructor brought me cake, announced to everybody (against my will) that it was my birthday, and they all sang to me, but not to him (not knowing it was his birthday). He later told me at that event<!--, with good humor-->. Most (well, definitely all) of the people there were older than me.

This period was an extremely isolated time of work and esoteric in-the-weeds revelation. Besides stacks of printed academic papers, I was reading The Lord of the Rings, and there was one chapter that I read precisely in this narrow time span (the meditation retreat was a different time span) after I returned from Montreal, "The Passage of the Marshes," that resonated for its eerie imagery. 

Frodo and Sam are being led by Gollum through the Dead Marshes. It's an eerie chapter, as Gollum's world seems to be the ruling one now, and Frodo and Sam are navigating at his back through the boggy peril.

I was going deeper and deeper into a psychotic state, both of (a) brilliant awareness and foresight about my field's fundamental principles and trajectory, and (b) isolation, as if I was traversing by the lead of Gollum through the Dead Marshes.

## <!--Psychosis-->Crisis

### Tao as the Optimization of a Differentiable Universe

Since my realization that the physics of the universe could be intelligent, plausibly, through the sampling mechanisms in quantum physics' probabilistic nature, and together with the acute state of consciousness I acquired through meditation, including the physical sensations in my esophagus and within my body that I had acute control of, as well as those viscera sensations I experienced in yoga, I was highly conscious of a force in my body that I could guide, but also that seemed to have some guidance of me. This guidance, I interpreted as Tao, the universe's natural changes, the universe's natural erosions. But those changes and erosions don't always feel like that, as guidances, so specifically, I thought the state of consciousness I was experiencing, the same one with which I found the I Ching's answers to be improbably precise to my questions, had some mechanism tied to the physics of Tao, that they were not just in tune with arbitrary changes, but specific changes, that the Tao intended. Specifically, I realized that the Tao is optimizing the universe, and that the universe might be "differentiable," but that some states of consciousness might be "more differentiable" than others, more in line with the Tao's ability to predict and plan.

But some of these guidances were more sensible than others. Perhaps some were Tao, and others, in the I Ching's language, were "grace."

The I Ching had called those disruptions, the less sensible guidances that also appeared, "Grace." And in Taoist philosophy, "Grace" isn't necessarily good. Those winds, as they push us, are, to put it in Richard Wilhelm's words, "beauty in form," and in the I Ching's taxonomy, such a state to a person's psyche and cosmology "has success in small matters […] but he dare not decide controversial issues in this way." But if there's any doubt to the authenticity of these experiences and beliefs, let it be known that the I Ching gave this answer exactly the morning of the day before the crescendo of my psychosis, in an especially relevant answer to my question about whether the state of consciousness I was increasingly feeling was still based on primarily truth, or delusion.

> [!NOTE]
> ### I Ching and Synchronicity Hypothesized Mechanisms
>
> In Rorschach tests, a person looks at ink blots and tells the psychoanalyst their associations. Dream interpretations are similar. But the answers I was getting from the I Ching weren't just associatively relevant. They were specific, consistent, and profound. If not psychological projection, what else might be the mechanism?
>
> The I Ching depends on decisions involving yarrow stalks or the casting of Feng Shui coins. <!--The probabilistic nature of the universe is standardly theorized.--> The occurence of small but nonnegligible probabilistic divergences in quantum particles, can coexist in agreement with standard quantum physics, as long as the total statistical divergence is bounded. <!--Standard quantum physics assumes the nature of the universe is probabilistic.--> Such small divergences can bias physical matter collisions, such as the coins themselves, or<!--, they--> might have an evolved limited interplay in a person's consciousness with neurology/physiology, perhaps less limited with parts of consciousness related to yogic attunement, which can bias physical motor activity before the stalks or coins are even cast, hypothetically.
>
> Of course, a person's psychology cannot be dismissed as independent to the interpretations, either, even when the answers are uncannily precise. However, what's suggested in this physics mechanism is that some planning mechanism can subtly bias physical behavior in the universe, either outward or inward, by a small, limited divergence. Perhaps, beyond yarrow stalks and Feng Shui coins, other kinds of convergences can be gradually eroded into being, by such a latent planning factor, making possible the seemingly acausal phenomenon known as "synchronicity." Since planning is objective-based, that would make synchronicities a "teleological connecting principle" rather than Carl Jung's traditional definition for the term, "acausal connecting principle."

Let $Q$ be a qualia function, and $\theta$ the parameterization of the intelligence of the universe via the probabilistic samplings of particles within a bounded statistical divergence from the probability distribution of the particles, e.g., from the normalized wave function of the particle. $\Omega$ is the universe, Tao/God as the process of optimization of the following objective:

$$\max\limits_\theta Q(\Omega_\theta)$$

Qualia is defined as the yogas, the emotions, and their richness, goodness, beauty, and sacredness, relatively ranked numerically in the universe by the qualia function $Q$. 

Those senses, however, as I described went into increasingly “Gollum-esque,” psychotic places, less in the nature of a proof of the beauty of the power of consciousness and perhaps the universe, but more in perhaps the bogs of obsession, recent trauma, isolation, intricate understanding, and incongruently deep transcendence. 

### Wind

It was literally a wind that pushed me into the woods. 

I had left my apartment thinking my heightened energies were draining my mom, and walked through the snow aimlessly, but adhering to senses and what I thought were Tao guidances, to make a distance from her. Then I reached a road near the more commercial district, and then I turned towards the woods direction, and last second, I saw a man coming out of his car, and I shouted "Hey!" and I asked him if he had gloves, and he did and he gave them to me. 

Then, still not knowing I was going into the woods, a wind pushed me. A wind blew and I walked into those woods where I sat, in meditative silence, and peace, near a prettier part of the brook, thinking I had to stay there for a week, and if I did, my mom wouldn't die. 

And I stayed there, completely immune to the cold, but protected, physiologically, by a single coat, sweatpants, and those gloves that were given me. 

Somehow, from the moment I'd left my apartment door, to the rest of this venture, except for a health concern, the cold didn't feel too cold. My body, in this energy state, adapted so well. Humans have evolved mostly in the Ice Age. I cannot tell you the medical implications of how much power the body has. I was there, from the early morning I left to the rest of the day, in the cold, that through this extreme, psychotic/delusional, transcendent energy state didn't faze me in the slightest, didn't bite the way cold is thought to supposed to, and it varied—you see, every disobedience to the guidance of my energy state resulted in a physical grasp of me by the cold; I would shiver and shake, at increasingly extreme levels the more I stopped adherence. But as soon as I returned to adherence, the cold and the shaking stopped. 

This is not trivial. This reproducibly felt like a physical relationship between me and the cold, where had I disobeyed the exact adherence of my psychic state, the particles of the cold would (or I should say "did") get me. The shaking then wouldn't even vary. It would appear in exact increment proportion to my deviation from the adherence to that mental state. 

Still daylight, the meaning of ["Life is suffering,"](https://www.psychologytoday.com/us/blog/the-second-noble-truth/201609/existence-is-suffering) as it's colloquially said that the Buddha had said, decryptified to me: "Life itself, the source and the living, is currently suffering, in the world." I imagined grass dying as a symbolism for this interim worldly state of things. "Life is suffering," however, is not a permanent state or law of nature. It is the ongoing situation of life in the world.

It was at night, near 2 AM, 3 AM, or 4 AM when that terrible peace turned into a different kind of panic.

> [!NOTE]
> This was about 5 - 8 months after the hair loss. No prior history of psychosis or mania.

An ambulance found me, wet with brook water<!--, potentially at risk of frostbite-->. The only answer I gave as to what happened, was "for pleasure," here and thereafter, under the delusional belief that my mom's life was in danger if I didn't adhere to that secrecy.

### Rochester General Hospital (RGH)

#### Christmas Eve/Day, 2018

By chance, my psychosis happened from the morning of Christmas Eve to the morning/night of Christmas day, 2018 when the ambulance found me. By chance, since my only reason for doing this, the unspecified <!--self-endangering--> ordeal, was fear that my mom's life was in danger, and whether it was a Christian holiday or not was irrelevant to me since my family is Jewish by ethnicity and was secular. 

My interest in the I Ching began in the House on May St., when I heard of it by chance through hearing again a lecture from [Terence McKenna](https://youtu.be/9E5eBqG0cds?si=AZVe2xQMEci2s7Rr), who I used to enjoy in college. It resonated because of the randomness-dependent theory I had, and I ordered a Richard Wilhelm translation and copy as well as some Feng Shui coins. 

A nurse was there to help thaw my legs to prevent hypothermia and frostbite.  My legs were thawed in some machine and my mom arrived. I was still afraid her life was in danger, but I didn't say anything. I didn't talk much.

The nurse remarked on some damages I had. 

#### Catatonia, or Yogic Guidances

<!--Then in a different bed, while doctors or nurses or attendants were in the room, I felt some strange thing happen with my tongue and throat, like my tongue was going back into it: my mouth opened wide, and i-->
<!--
They brought me to a different room. One moment I was moving and walking, the next the intensity of the hospital environment guided me into a contortion. My mouth opened wide, it was as if my tongue went back into my throat—then it was as if I swallowed my tongue—and like the whole [Kundalini](https://en.wikipedia.org/wiki/Kundalini) that had "risen," although actually it was the physical inner sensation that moved through different parts of my body, that in the House on May St., through meditation, I had full control of, acutely—like with the brilliance of puppy's eyes, and on 3 axes of movement—had been swallowed, as if shoved down my throat by the hospital. Whatever that sense was, was a real physical thing.

I went into a conscious yogic surrender of all muscle. Even as the doctors picked me up, placed me down on wheels, and wheeled my limp body forward to the MRI machine, I stayed adherent to those [guidances](#Crisis), still thinking something important was at stake, if I disobeyed.

Then my sister came into the room. She saw me, staring forward, and gently touched my arm with a finger. A spark. Maybe just in my eyes, or from the corner of my mouth, but I gave an imperceptible smile. I was afraid. She told the doctor/attendant she thought she saw me smile. The doctor/attendant, standing nearby, declared calmly I was unconscious. 

A couple days later, an injection of benzos brought me out of the yogic state sooner than I'd planned to stay in it, as the daze of the benzos made me uninhibited to the perceived responsibility. Thereafter, as I noticed from my first meditation sensations in RGH, the Kundalini sensation, rather than descending or being adaptive to my will, was kind of locked up, uncomfortably, rigidly in what to this day seems like a less acute state of consciousness than the adaptive inner acute dynamics.
-->

I was in the bed of a different room. One moment I was moving and walking, the next the intensity of the hospital environment guided me into a contortion. My mouth opened wide, it was as if my tongue went back into my throat—then it was as if I swallowed my tongue—and like the whole [Kundalini](https://en.wikipedia.org/wiki/Kundalini) that had "risen" through me—something I had full control of, acutely—like with the brilliance of puppy's eyes, and on 3 axes of movement—back at the House on May St., through meditation—felt suddenly shoved down my throat by the hospital. That sensation, however it moved through my body, was real and physical.

I surrendered. Every muscle in my body relaxed into what felt like a conscious yogic submission. Even as the doctors moved me, placed me on a stretcher, and wheeled my limp body to the MRI machine, I remained in that state—still thinking I was bound to something important, something that would be lost if I disobeyed the [inner guidance](#crisis).

Then my sister entered the room. She saw me staring ahead, and gently touched my arm with a finger. A spark. Maybe just in my eyes, or from the corner of my mouth, but I gave an imperceptible smile. I was afraid. She told the doctor/attendant she saw me smile. The doctor/attendant, standing nearby, declared calmly I was unconscious.

A couple of days later, an injection of benzos pulled me out of the yogic state earlier than I’d planned to leave it. The haze of the drug dulled my inhibitions, and I let go of the perceived responsibility. But what followed wasn’t a return to the fluid, adaptive sensation I had once known. Instead, the Kundalini, once dynamic and responsive, felt locked inside me—rigid, unyielding, and far less acute than before. I first noticed this during meditation in RGH.

<!--
> [!NOTE]
> The brook-jumping "baptism" could be interpreted as spiritual birth/rebirth, the throat sensations as the Kundalini "rising"—a concept from Hindu tradition. [Psychosis-like symptoms are often described as characteristic of a Kundalini awakening](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9460011/). The "yogic grace guidances," I'd interpreted, since the House on May St., as Tao.
-->

> [!NOTE]
> The brook-jumping "baptism" could be interpreted as spiritual birth/rebirth, the throat sensations as Kundalini awakening—a concept from Hindu tradition, often [associated with psychosis-like symptoms](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9460011/). The "yogic guidances," I'd interpreted, since the House on May St., as Tao.

### Discharge from RGH
<!--
I also gave the "for pleasure" answer to the psychiatrist, who diagnosed me with a bipolar manic episode and catatonia.
-->

<!--
> [!NOTE]
> 
> "Bipolar mania" could perhaps be clinically regarded as accurate. "Catatonia" was a misdiagnosis, due to me not knowing the definition of "catatonia," the fear for my mom if I elaborated on what actually happened, the--> <!--physical--> <!--ability to have exited it, the yogic trance/grace/guidance that I was adhering to only due to fear of my mom dying, --><!--or the belief that something important was at stake,--><!-- which is not the same as "catatonia," and the difficulty of articulating what happened so soon after/amid the psychosis in the first place.-->

<!--
> [!NOTE]
>
> "Bipolar mania" might have had some clinical accuracy, but "catatonia" was a misdiagnosis. The doctors never asked me about what actually happened. I didn’t know the term *catatonia* at the time, and I was following a yogic grace/guidance out of fear for my mom’s life—not because I couldn’t move or respond. I could have exited the state I was in, but the doctors never considered that possibility. What I was experiencing wasn’t catatonia, and their misdiagnosis overlooked that crucial distinction.
-->
<!--
I ran the final experiments for my [MHDPA innovation paper](https://www.overleaf.com/read/qgmmzgsrctmg#6cd1b9) within just days of that, fully out of that altered state of consciousness now, in the hospital since the hospital staff allowed my mom to bring my laptop in.

Then RGH discharged me not much more than one week after admission.

More than two weeks since the first hospitalization, I end up not sleeping all night. My sister happened to visit the next day. Due to having not slept all night, she was worried I might be going through another "manic" episode and insisted to my mom and me to drive me to Strong Hospital. The doctors at Strong Hospital didn't question the prior "mania" nor "catatonia" diagnoses, nor ask for any further details about that earlier hospitalization or the--> <!--preceding--> <!--events.-->

I also gave the "for pleasure" answer to the psychiatrist, who diagnosed me with bipolar manic episode and catatonia.

<!--
> [!NOTE]
> 
> "Bipolar mania" might have been clinically accurate, but "catatonia" was a misdiagnosis. The doctors never asked me about what actually happened. I didn’t even know what "catatonia" meant, what its definition was. What I was experiencing was a yogic guidance, driven by the fear of my mom dying, and I could have exited it if I decided to. But the doctors didn’t consider that possibility. They simply settled on the misdiagnosis.
-->

> [!NOTE]
> 
> "Bipolar mania" could perhaps be clinically regarded as accurate. "Catatonia" was a misdiagnosis, due to me not knowing the definition of "catatonia," the fear for my mom if I elaborated on what actually happened, the <!--physical--> ability to have exited it, the yogic trance/grace/guidance that I was adhering to only due to fear of my mom dying, <!--or the belief that something important was at stake,-->which is not the same as "catatonia," and the difficulty of articulating what happened so soon after/amid the psychosis in the first place.

<!--
Just days after that, fully out of that altered state of consciousness, I ran the final experiments for my [MHDPA innovation paper](https://www.overleaf.com/read/qgmmzgsrctmg#6cd1b9). I was in the hospital, and the staff allowed my mom to bring in my laptop.

Then, only a week after admission, RGH discharged me.

More than two weeks later, I didn’t sleep at all one night. The next day, my sister, concerned that I might be going through another "manic" episode, took me to Strong Hospital. The doctors there didn’t question the previous diagnoses of mania or catatonia. They didn’t ask for any details about the events leading up to my hospitalization. The same assumptions were made without reconsideration.
-->

I ran the final experiments for my [MHDPA innovation paper](https://www.overleaf.com/read/qgmmzgsrctmg#6cd1b9) within just days of that, fully out of that altered state of consciousness now, in the hospital since the hospital staff allowed my mom to bring my laptop in.

Then RGH discharged me not much more than one week after admission.

More than two weeks since the first hospitalization, I end up not sleeping all night. My sister happened to visit the next day. Due to having not slept all night, she was worried I might be going through another "manic" episode and insisted to my mom and me to drive me to Strong Hospital. The doctors at Strong Hospital didn't question the prior "mania" nor "catatonia" diagnoses, nor ask for any further details about that earlier hospitalization or the events.

## The Unsampled World at Clover St.

My sister came to our apartment and brought my mom and I to her dark-red mid-size crossover, that I thought looked like a car that symbolized the Devil. Compared to the cars my mom and I drove, it was much newer, much nicer, dark red. She was working as a nurse at the time and making a middle class income. My mom was working two jobs with a low income, and I was a doctoral student.

When we were driving, I remember we stopped at Clover St., due to a red light, and some instinct told me to jump out. The feeling was ominous. But together with that ominous feeling, as the drive progressed, I sensed that a million worlds existed, and that all of them had evolved to converge to this one. So I sat somewhat reassured, in an uneasy anxiety, that what was happening will be okay. 

Except, the sense/vision/idea was wrong, this time. Instead of my fanciful ideas about quantum stochasticity in a single universe, I had this bizarre idea, specifically on this transit, about "Many worlds"—I know, how original. "Many worlds" is a standard interpretation in quantum physics, often an alternative to Copenhagen which also, like me, both usually and <!--I guess--> in my version here, tends to assume a single universe.

In "Many worlds," or at least my version that I was conjuring up in my mind in the car, or I should say was pouring into my mind through a sheer awareness, everything that happened in the universe was evolved, through countless cycles of different trajectories, over cosmogenesis origins upon cosmogenesis origins, into the perfect exact happenings that were happening then. Now that's not really "Many worlds." That's one world, where it just cycles many times, like an AI training algorithm, and we just happen to be in the version that cycled in this way.

"Many worlds" is more nuanced. It says: there's a LOT of worlds—like at least 6. No, maybe a million. No, googolplex. Infinity! Undefined! And we're in this one, because "reasons."

Both of these theories/interpretations are wrong. But neglecting to explain why for now, I think either of these serve as an accessible way to quickly show that, even under a pretty standard physics interpretation, the possibility of "God" is not... I think the word I want to use is "not necessarily stupid."

I mentioned stochasticity in the universe's quantum mechanics. That means randomness. The universe, as it's theorized today, is fundamentally probabilistic. And physics does a great job of telling us that those probabilities are probabilities. No no, just look at Schrödinger's quantum wave function. See, it's a bunch of probability densities that splash around like a kiddie pool. And when those waves are especially high, that's where the particle is more likely to get sampled, or that's the more likely velocity of the particle, or that's the more likely "World" that gets sampled, or in my especially terrible vision, that's the "Cycle" that the universe just permanently converges to forever. 

So where can "God" fit into any of those interpretations, besides the last one being just "Godawful," no-pun-unintended (my puns are deterministic)? Well, ultimately, something has to select which world gets chosen. One way that could happen is through just the magic power of randomness. Another way, is that some *will* known as "statistical divergence" is able to allocate the probable from the improbable, and, within its holy bounds, tilt the scales a bit. The "Sampler"—who is the "Sampler"?

I sensed an ominous feeling as we were driving, and that same inner sense that gave me that kind-of vision about the many cycling-evolving worlds converging to this moment's exact perfection, told me to make a run for it when we stopped at Clover St., at a red light. My doctoral advisor, Henry, actually lived on Clover St.

My sister's car was big and red, like a giant Dirt Devil, and before we got into it, I immediately had the "Devil" association, appear like a fear in my mind, the first omen (ominous sense) of that drive. Well, the "Sampler" that was about to sample my fate could only have been a little red vacuum cleaner, because, this transit, not specifically just this transit but this transit as well, was taking me to Hell, and the Devil drive did not end on Clover St., nor on the hospital grounds. No, each ticking moment from the drive to the psychiatric unit, even back to home, was a cruise controlled, speed-limit-obeying, insidious, maybe even pleasant drive, deeper, into Hell, to a Hell of mind that only one door leaves.

But at this time, we were stopped on Clover St. And there was my doctoral advisor's big house, on this street, that I could've, hypothetically, run to, in one of the many other worlds. 

My advisor, Henry Kautz, was the most successful man I knew, and his house, I <!--thought-->think, was a mansion (though honestly the one I had on May St. probably would've been preferable).

As my sister must've thought, I'd be getting just standard quality care. What a lucky day. What a lucky world that was sampled. And then we proceeded, from Clover St., to the first day of my benzo nightmare. 

> To do: Technical specifications of "Many Worlds" as an introduction to the study of an intelligent universe, e.g., Tao, through the lens of AI

- ChatGPT claims to use RL
- LLM's "exploration strategy" via beam search type methods can inspire RL
- Applied to RL environments, this equates to the "Many Worlds" concept, except now intelligent if those environment samplings are differentiable / optimizable towards a purpose
- After RGH hospitalization, was making a computer vision encoder architecture (A.K.A., a kind of vision transformer, early 2019) of disentangled MHDPA representations for use in an episodic memory to increase generalization across levels in RL
- I studied RL throughout my PhD
- I did RL my whole PhD
- Implemented everything, even built a Keras-type library back in 2018 with neural episodic control that generalized to my Med Center research, and a couple years later, was building a library called [UnifiedRL](https://github.com/slerman12/UnifiedRL) 

<!--
- ChatGPT claims to use RL
- LLM's "exploration strategy" via beam search type methods can inspire RL
- Applied to RL environments, this equates to the "Many Worlds" concept, except now intelligent if those environment samplings are differentiable / optimizable towards a purpose
 - And taking inspiration from MHDPA, can be applied to multi-headed particles, as my own theory does
- I studied RL throughout my PhD
 - I did RL my whole PhD
 - Implemented everything
- Was suddenly made credible for the first time thanks to ChatGPT, as my MHDPA research had been made in the earlier years thanks to the explosion of transformers, which also, next to RL for human feedback, underpins ChatGPT
 - And even more recently, has been made more credible with real-time RL robotics (which [I was one of the first to do](#real-time-rl-robotics)), and apparently even OpenAI's "Q*" project, for which the CEO, Sam Altman, was, not long after I was (17 days), terminated
-->
> To do: Write:
> 
> Before my area exam, I was building a vision transformer for generalizing across Sonic the Hedgehog levels, but I didn’t realize it was a vision transformer (in the Computer Vision domain) since it was purely applied to reinforcement learning, and the crux of it for me was to use disentangled relational representations as queries to the episodic memory (k-nearest neighbors, made differentiable via weighted averaging attributed rewards), meant to give the episodic memory more generalizability since the relational representations extracted parts and their relations rather than the full entangled context, effectively treating the MHDPA heads like an ensemble of independent memory queries using my disentangling method from my earlier paper. This is still an extremely insightful symbolic understanding of how models can generalize across domains, where the relational representations are the generalizable components and the episodic memory was like the parameterized or recurrently-stored knowledge trained into models today via giant data corpora, except in both cases more explicitly programmed in as novel inductive biases. None of this was appreciated by my department, whatsoever. 
> - I was studying reinforcement learning (RL), from DQN, to policy gradients, to actor-critic, since the beginning of my PhD. It was at the forefront of my research, but completely unsupported and un-believed in until ChatGPT, which, besides MHDPA, was able to train human feedback into the model via an RL type algorithm, not exactly reinforcement learning since N-step future rewards aren't used—more like moving parameters in the direction of a gradient to maximize outputs that are assigned higher rewards by humans—analogous to policy gradient methods in RL—but enough to lend credibility to RL's utility for the first time in my PhD. The models that succeeded ChatGPT may have been less simplified, using actor-critic type behavior maximization rather than policy gradients, which are a little weaker. The full potential of RL, using N-step reward, over long time-scales, online learning, and multi-agent, is still unrealized. Exploration sampling is analogous to beam search type methods, and the latter could be applied, hypothetically, to environments in RL, as is actually the best technical analogy for "Many worlds."

## University of Rochester's Strong Hospital

### Sarah

<!--
> [!NOTE]
> I define "synchronicity" as a "[teleological](https://www.linkedin.com/pulse/exploring-authentic-leadership-teleology-vs-causality-utpal-dutta-d5w6f) connecting principle," somewhat distinct from [Jung's analogous definition](https://www.abebooks.com/servlet/BookDetailsPL?bi=31992979134&ref_=pd_hw_o_1) of "synchronicity" as an "acausal connecting principle," in that I don't think that just because there is no known cause that there is not a cause, and that such a cause doesn't have a purpose, which is what (purpose) "teleology" refers to, and the link, by chance, refers to social healing.
-->

<!--
> [!IMPORTANT]
> I define synchronicity as a *teleological* [connecting principle](https://www.abebooks.com/servlet/BookDetailsPL?bi=31992979134&ref_=pd_hw_o_1), where there is a cause, and that cause is God/Tao/Brahman/Allah/etc./[physics](#the-unsampled-world-at-clover-st), and the teleology is health and [social healing.](https://www.linkedin.com/pulse/exploring-authentic-leadership-teleology-vs-causality-utpal-dutta-d5w6f)
-->

> [!NOTE]
> I felt, ever since that sensation that my tongue was going back into my throat, some vestibular situation—something really changed, and has been different since. That oceanic feeling that John Lennon captured really well about his experiences with TM in the song ["Across the Universe"](https://youtu.be/90M60PzmxEE?si=2n0PJKmeekYA6etl) ([John Lennon wrote the song about TM](https://en.wikipedia.org/wiki/Across_the_Universe#Composition), both explicitly in his reference to "Jai guru deva om" and more ambiguously with his spot-on description of the state of consciousness induced by and, with respect to the mantra, during, TM) was gone. Since that "catatonia" (tongue-throat situation), my experiences/words during and following TM weren't "like endless rain into a paper cup." They had become coarse somehow, and instead of that vibrant "Kundalini" movement I felt before, there was a physical feeling in my neck, a right-angle tilt, even when I wasn't meditating. I first began noticing this while trying to meditate in the hospital at RGH.

Since RGH<!--After the Christmas, 2018 trauma-->, I wasn't able to access my meditation anymore.

The meditation still relaxed me. I still felt less social anxiety afterwards. It still gave my thoughts more peace. But physically, it felt neither like bliss nor like a body part that I directly controlled. I couldn't maneuver the breath, kundalini, blood circulation, whatever it was, through the different areas of my physical psyche (and actual body), and my given mantra, that I repeated silently in my mind as part of the meditation, didn't carry itself to the same places of acuity that it naturally did before, where rather than the hard sensation of speaking my inner voice that now characterizes my mantra's audition, the mantra had before "tapped," "dissolved," become so soft until it literally couldn't be heard except in awareness and all of my thoughts were then fully adherent to both my will and my natural rhythm, and no energy was lost no matter how verbosely or viscerally I thought then, and each one came like ["endless rain into a paper cup,"](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://en.wikipedia.org/wiki/Across_the_Universe%23:~:text%3DThe%2520flavour%2520of%2520the%2520song,the%2520link%2520to%2520the%2520chorus.&ved=2ahUKEwjGvszQ1rOIAxXlhIkEHdwgLcwQFnoECBsQAw&usg=AOvVaw1MtnfbSbXSsMu_w1lg6V_v) where just the [right word](https://www.overleaf.com/read/qgmmzgsrctmg#6cd1b9), or visual or association, corresponded to both my will and my rhythm, beautifully, sometimes blissfully, sometimes catastrophically<!--, maybe even orgasmically-->.

The physical sensations before the hospitalization were ones I could control but which I didn’t feel controlling of, as in, they came naturally, were a part of me, and didn’t involve concentration or discomfort or movement through any kind of forcing. They felt like a tongue in my body and my consciousness was with them and everything else in my mind and behavior. Today, that level of unity doesn’t exist in me, even with far more discipline and knowledge.

The limit was physics and the physiology and neurology mechanics therein. The analogy I came up with, is that we are like individual neurons in a brain, similar to the analogy made about “waves in an ocean,” but which conveys intelligence in those constituent waves, that despite their independence somehow compose the larger intelligence of the universe, like neurons, not necessarily knowing what larger singularity we compose.

In my second hospitalization, the environment was much better than RGH's. I made friends with Sarah, Hudson, and other inpatients. We [played](https://youtu.be/cco_DvSzrts?si=pmfrQ4XEaLF1teEK&t=51) Guitar Hero together, there was a piano, there were TVs, one of the public rooms had big windows, we even were taken across floors of the hospital for music jamming sessions with lots of instruments, they had their yoga and meditation instructions as well, and of all of my hospitalizations to come, this was perhaps the best care unit I was gated by armored vault into. 

Sarah's sister's name is "Kundalini Grace." I hadn't heard of "Kundalini" until after I had those visceral, physical sensations in the House on May St. Then I looked up those sensations I was experiencing and found, for the first time, not having heard the word or of those movements and sensations before, the term "Kundalini," made more credible to me by the philosophy's appreciation by the depth psychologist Carl Jung, who I was reading at the time, and whose views, very distinct from Freud's, on the existence of a subconscious, and its mystical-transcendent connection, helped explain some of what I was witnessing.  

Sarah Young's last name is "Jung," she hadn't heard of Carl Jung, she and I kept observing synchronicities while we were there, and she kept a synchronicity list. To me, no synchronicities happened yet that were bigger than just the uncanny precision and specificity of the I Ching's answers. However, I was still seeing some unambiguous synchronicities, as well as not seeing many others, including that the word "synchronicity" was actually coined by Jung, and now I was remarking on them  together with one Sarah "Jung." But there were more I hadn't seen, and more, much bigger, that would come.

The House on May St., in retrospect was one big synchronicity. I got the Facebook student housing page moderatorship just before I had to move out, and was able to deliver on my promise to fill my landlord's house (and houses) with grad students. Not to mention, the house itself. Having that whole house, pretty much to myself, a beautiful antique house, for relatively pennies, the same house I had my AI and physics revelations—"luck" seems to forget a lot of context.

So the word "synchronicity" was already familiar, as was Jung, as was Kundalini, as was Grace, by the time Sarah and I met in the hospital. 

Sarah was early 20s, by chance hospitalized at the same time as me, also early 20s. She was a year older. 

We played Guitar Hero, I continued all of my meditation and yoga regimen, and my family, including my mom, uncle and aunt, and cousin brought in Paleo diet food for me, which I ate for my eczema but which also helped with my cognition, instead of the unhealthy processed type food of the hospital. And I shared crapes with Sarah<!--(another inpatient)-->, that my aunt brought in each time she and my uncle visited. They weren't 100% Paleo (buckwheat, goat cheese), but still delicious.

So to summarize, I was doing daily meditation, twice a day, daily yoga each morning, and eating a Paleo diet in the hospital, as well as now socializing well. On top of all of that, and antipsychotics, surely the missing ingredient to cure me would be an involuntary >6 months course of benzos.

My brother-in-law came in with my sister and I explained to him relational reasoning and the paper I submitted, the method of MHDPA. I explained to him the method underlying ChatGPT from my hospital ward 4 years before ChatGPT. And at the time, he thought my explanation was cool, but it'd've been hard to predict would be such a big thing, one that others in my field and the world would have heard of or have anywhere to as much belief in the utility in AI of, in the near-term or in the years to come. It was hard to predict for my professors and faculty, too. At the time, 2018/early-2019, most at the University of Rochester still thought deep learning was a fad. None of the professors or other PhD students were doing research on MHDPA, let alone had heard of MHDPA. [They might claim otherwise](4-Faith.md#academia--medicine). Besides the paper that proposed MHDPA itself, my innovation to MHDPA, was the first innovation to MHDPA ever, in the world/history. A small handful of others applied it, from research groups in DeepMind, none literally innovated *on* the method.

I showed my MHDPA innovation paper to Sarah. She was amazed that she could read it since usually, she said, that kind of stuff isn't readable, and brought up one more synchronicity. Her mom was a writer who had a published short story in a Stephen King anthology, a writer of horror. I was indeed in a hospitalization that was like a pretty good short story in an otherwise Stephen King anthology/horror. 

Not that my lucidity needed further evidence, but I explained the methods of late-2022 ChatGPT to inpatient and visitors, in early-February, Winter, 2019, while drugs were altering and innovating on the functioning of my biological neural networks.

<!--
> [!NOTE]
>
> ### Janitor Friend
>
> Sarah gave me permission to share this. I'm not sure I'm doing it justice. While in the hospital, separate from this stay when I was hospitalized, Sarah had sex with a 50-something year old janitor, still while she was hospitalized in one of the psychiatric units for psychiatric care. They got into a relationship afterwards, even when she got out. She ended up breaking up with him.
>
> Sarah was also treated with benzos. Benzos are like GHB. Both are GABA agonists. The two aren't exactly the same. GHB activates GHB receptors. But like the "date rape drug," benzos disinhibit a person's personality. Outside of confinement, or without high doses of disinhibiting drugs, it's a fact that Sarah, and the 50-something year old janitor, wouldn't have had sex in the psychiatric unit, since she would not have been in the psychiatric unit, under the premise of her being outside confinement, which was not the case.
>
> In addition to disinhibitory drugs, the hospital environment is oppressive. It can be lonely. And the janitor perhaps helped her. The hospital's responsibility isn't to increase the oppressiveness of the care units, but to provide care units that sufficiently socialize and help a patient, without overexposing them to drugs that increase impulsiveness, disinhibition, and so on. 
-->

> [!NOTE]
>
> ### Janitor Friend
>
> Sarah gave me permission to share this. I'm not sure I'm doing it justice. While in the hospital, separate from this stay when I was hospitalized, Sarah had sex with a 50-something year old janitor, still while she was hospitalized in one of the psychiatric units for psychiatric care. They got into a relationship afterwards, even when she got out. She ended up breaking up with him.
>
> Sarah was also treated with benzos. Benzos are like GHB. Both are GABA agonists. The two aren't exactly the same. GHB activates GHB receptors. But like the "date rape drug," benzos disinhibit a person's personality. Outside of confinement, or without high doses of disinhibiting drugs, <!--it's unknown whether Sarah, and the 50-something year old janitor, would've had sex--> that interaction might've not happened.
>
> In addition to disinhibiting drugs, the hospital environment is oppressive. It can be lonely. And the janitor perhaps helped her. The hospital's responsibility isn't to fire the janitor who she got into a relationship with, nor to increase the oppressiveness of the care units, but to provide care units that sufficiently socialize and help a patient, without overexposing them to drugs that increase impulsiveness, disinhibition, and <!--so on-->addiction. 

> [!NOTE]
> ### Kids
>
> My instincts still haven't ceased, and I still interpret them as Tao, except with more experience, and the "threats" have evolved into helpful or sabotaging suggestions, what others with frontal lobes might just observe in themselves, less acutely perhaps than somebody mid-psychotic-trance, as "social energies, social sense, social skill, maybe emotional intelligence, or emotion," and frontal lobes should, as a general rule of thumb, be handled delicately when just growing in, by the way, as they tend to in a person's early 20s, when by totally-random-amazing-coincidence, schizophrenic episodes are most likely to occur in a person whose relationships with those energies of their intelligence might not be as integrated as with other impressive energies of their intelligence, and that integration can be initially exactly as intense as it's supposed to be minus the external orders that make it quite paranoid and scary — did I just explain schizophrenia in one sentence? Anyway, that truth about not intervening while parts are still growing in, is quintuply true about people under 20.
>
> I met Mobi in my next hospitalization. A couple years later, I learned that Sarah had met Mobi in one of their hospitalizations, too, that he'd even braided Sarah's hair. Mobi was a recurrent inpatient care unit psychiatric recipient. He was 16, clearly intelligent, had a "sober" intelligence and humor, was respectful, kind, and chill. They'd been giving him benzos for 2 years at that point, on and perhaps-sporadically-off, from the age of about 14, and he was in there mainly, or perhaps only, for drug problems and addiction. Acclimating to benzos, one's brain becomes deprived of GABA and will crave something, usually drugs, to take the literal neural edge off, to silence those disproportionate Glutamates and other action potentials whose balancing complement, GABA, is downregulated, throughout the brain. Benzos are a hard drug, and are as addictive as any hard drug. He was a 16-year-old drug addict, and they kept institutionalizing him for his drug issues and prescribing daily benzos.
>
> Maybe he was such a big alcoholic at the age of 14 that the benzos were the inescapable treatment that the psychiatrists had to resort to, but I doubt it. When it gets to the point that kids are being inoculated with benzos, psychiatrists should ask themselves whether they have a problem, some kind of addiction maybe, to prescribing benzos, and seek help. There is a path to recovery, a 12-step program, starting with (1) stop. (2) Ask yourself, "Will society really be ruined if this kid is helped in some more-substantive way?" The next 10 steps involve reforming society, so I leave that as an exercise to the reader.
>
> These traumas are inflicted on kids, in hospitals and schools alike. Schools, today, are where kids give the best hours of their day. It's where, today, kids obey authority and follow merciless programs, with such stress that the authority and obedience structures disseminate to kids, and create a psychology of competition, mercilessness, and necessitated bullying. Rather than being like summer camps, schools today are literal concentration camps. Hospitals and schools should take inspiration from summer camps (no coercion, social, integrated with nature), monasteries (intuitive aesthetic for peace), and the fact that YouTubers make better educational content through their channels than what most schools offer, except often way faster-to-learn-from and more truthfully/deep/intelligently/respectfully-to-audience/entertainingly when it comes to the learning curriculum, from the intuitions to the in-the-weeds material specifics, that can be curated into many diversely branching tracks, while tools like [Quora](https://www.quora.com) and [Piazza](https://piazza.com/) make learning by oneself, in one's own designed, uncoerced fashion, more possible than ever.
>
> YouTube, Quora, and Wikipedia are how I taught myself physics.
>
> Before that, I took an AP class in high school that I didn't score high enough on to get college credits for, and I took a community college class at Monroe Community College in the summer after my freshman year, that I got an A in, that my university, the University of Rochester, didn’t even matriculate, because it was a community college.
>
> Schools are coercive torture camps. They should exist to socialize kids, while humble themselves from the status of being educational to the status of being easily outdone by creators on the internet, whose educational material are <!--"are" sounds better than is; "material" is technically plural, but some might argue that only "materials" is allowed--> more fun and uncoercive. This is a quiet truth that people may have a hard time realizing, as the tortures, on kids, continue.
>
> To do: Historical context, history of child labor. How practices today will be perceived in history.
> 
> I believe in autodidacticism via YouTube, Quora, and Wikipedia type apps and reconstructing schools as environments of peace and socialization. There is more than enough social incentive for kids to want to be more intelligent than other kids, or prepare themselves better for universities, which out of K-12 should not be grade-based or any metric, but that's where metrics can begin and universities for adults 21+ can exist that discriminate based on metrics.
>
> In the age of automation.

### Hudson

Our other companion was Hudson, who caught me as I was being discharged and handed me this letter in an envelope, that I opened later from my apartment:

<p align="center">
<img width="300" alt="Screenshot 2024-03-12 at 8 10 34 PM" src="https://github.com/slerman12/Detective-Sam/assets/9126603/d5414cba-2012-42f9-b516-f06dd8760cad">
</p>

It's great<!--I'm impressed--> he was able to write at all. He had depression, was in the hospital for depression, was being treated for depression, was medicated for depression, and was electroshocked weekly, for depression. 

Meanwhile, I was being brain damaged by benzos, but who could've known that? (I did, because I made the case articulately, sufficiently so, to all of my psychiatrists. As I predicted, longer-term benzo use is dangerous, causes extreme physical dependence, and can result in unthinkable suffering). 

I was told a court order would be acquired if I didn't take them, even as I was taking antipsychotics.

> [!NOTE]
> ### Jeremiah
>
> I ordered a margarita in a 2016 birthright Israel trip (a program that I really like, since otherwise I might've not been able to afford to go on any vacations), with Jeremiah probably somewhere at the table, thinking I was ordering a drink, and they brought me just this big margherita pizza. That's a fun story. Combined with benzos, that is, if I took my prescription for social anxiety that day, I suppose the effect would've been worse, neurologically and physically, than if they brought me a margarita.
>
> That was also the trip where I was complaining [my hair was too long](https://www.facebook.com/share/qQqsQLv4Cgvbv7UZ/) (as many people heard/"witnessed"), perhaps another almost-preternatural-seeming omen, besides the electric razor breaking, that preceded the [very vivid nightmare that I had](#part-1) and me growing out my facial hair (beard and mustache) for the first time, by chance.
>
> And we all got extremely sick, suddenly, everyone on our bus, 10 plus people, 10 - 30 people, originating from a guy on the trip who wasn't me or Jeremiah. My cousin Irina, who went with me, and I, got the most sick, of the whole bus, really severe fever, sneezing, sinuses, coughing, vomiting, more. I recall she was even prescribed an opioid, besides Sudafed.
>
> About two years after my first Strong Hospital hospitalization, Jeremiah, who I hadn't seen since the trip to Israel, commented on a Facebook post that I'd made about the trauma that benzos induced on me, about some of his experiences. He wrote publicly on my post about how some psychiatric medication he had to take caused him to have a seizure. "[...] I've had bad side effects from medications that caused me to have a seizure one time that was no fun. [...]" Benzos, one of the drugs he was prescribed and the only plausible culprit of the ones he told me, [cause seizures during the brain's GABA downregulation](https://pubmed.ncbi.nlm.nih.gov/21815323/#:~:text=Withdrawal%20seizures%20have%20occurred%20with,time%20and%20at%20high%20doses.), a widely suffered and standardly known side effect of longer-term benzo use. Those were almost definitely the medication <!-- of his--> he was referring to.
>
> He also wrote how he was held down and choked, on pavement outside, after being tackled, on the hard rough pavement, by the university-hospital police officers, when he tried to make a run for it. "I tried to escape and they held me down and choked me. I got to the driveway [...]" Analogously, my next hospitalization also involved combative resistance to hospitalization, following the >year of benzo-induced torture. In October, 2020, I was also physically coerced by the police, due to having a "breakdown," I suppose it can be called—quiet, peaceful, and spiritually-guided—in the grass of my apartment complex, where I'm pretty sure I was legally allowed to, or within perimeters. Efforts to escape medical custody might have other causes besides bravery and spirituality (if one is willing to extend the benefit of the doubt that I'm not stupid), for example (1) induced by disinhibitions from prescribed pharmaceutical drugs, or (2) the quality of the care provided within medical custody, or other snowballing longer-term medical-institution causes, such as (3) resistance due to earlier trauma from a previous medical intervention, like the benzo coercion that traumatized me. So, in consequence, the medical application of police brutality can result as one of the negative side effects of a pharmaceutical drug, wherein the medical system is committing physical violence in order to reinforce the drug, care, or practice that led to their own physical violence or the patient's combative resistance. They also are very coercive inside the hospital, especially in the early transit before the psychiatric unit, e.g., making you sit in one place, wear what they want you to wear, take the drugs they give you or otherwise be injected with them, etc.
>
> Jeremiah is a fellow hobbit, and brave.<!--He looks like the Cowardly Lion from Wizard of Oz, but he neither thinks he's cowardly—his spirit animal is a lion—nor is. Jeremiah is brave. Jeremiah is a hobbit, a fellow hobbit.-->

<!--
## From RL to "Many Worlds"

> To do:

- ChatGPT claims to use RL
- LLM's "exploration strategy" via beam search type methods can inspire RL
- Applied to RL environments, this equates to the "Many Worlds" concept, except now intelligent, and if differentiable, optimizable towards a purpose
 - And taking inspiration from MHDPA, can be applied to multi-headed particles, as my own theory does
- I studied RL throughout my PhD
 - I did RL my whole PhD
 - Implemented everything
- Was suddenly made credible for the first time thanks to ChatGPT, as my MHDPA research had been made in the earlier years thanks to the explosion of transformers, which also, next to RL for human feedback, underpins ChatGPT
 - And even more recently, has been made more credible with real-time RL robotics (which [I was one of the first to do](#real-time-rl-robotics)), and apparently even OpenAI's "Q*" project, for which the CEO, Sam Altman, was, not long after I was (17 days), terminated
-->
<!--
- I did RL my whole PhD
 - Studied, implemented, innovated, was fascinated with, even got a paper on
- 
-->

<!--
> Add description of my RL research, and how beam search type methods, as are used in LLMs (including ChatGPT), as an exploration strategy on RL environments, relates to "Many Worlds," and how ChatGPT's use of RL made my PhD-long study and implementation and innovation on RL algorithms suddenly credible for the first time, though that increased again with real-time RL robotics, later. 
-->
<!--

#### From RL to "Many Worlds," and Other Research

Before my area exam, I was building a vision transformer for generalizing across Sonic the Hedgehog levels, but I didn’t realize it was a vision transformer (in the Computer Vision domain) since it was purely applied to reinforcement learning, and the crux of it for me was to use disentangled relational representations as queries to the episodic memory (k-nearest neighbors, made differentiable via weighted averaging attributed rewards), meant to give the episodic memory more generalizability since the relational representations extracted parts and their relations rather than the full entangled context, effectively treating the MHDPA heads like an ensemble of independent memory queries using my disentangling method from my earlier paper. This is still an extremely insightful symbolic understanding of how models can generalize across domains, where the relational representations are the generalizable components and the episodic memory was like the parameterized or recurrently-stored knowledge trained into models today via giant data corpora, except in both cases more explicitly programmed in as novel inductive biases. None of this was appreciated by my department, whatsoever. 
- I was studying reinforcement learning (RL), from DQN, to policy gradients, to actor-critic, since the beginning of my PhD. It was at the forefront of my research, but completely unsupported and un-believed in until ChatGPT, which, besides MHDPA, was able to train human feedback into the model via an RL type algorithm, not exactly reinforcement learning since N-step future rewards aren't used—more like moving parameters in the direction of a gradient to maximize outputs that are assigned higher rewards by humans—analogous to policy gradient methods in RL—but enough to lend credibility to RL's utility for the first time in my PhD. The models that succeeded ChatGPT may have been less simplified, using actor-critic type behavior maximization rather than policy gradients, which are a little weaker. The full potential of RL, using N-step reward, over long time-scales, online learning, and multi-agent, is still unrealized. Exploration sampling is analogous to beam search type methods, and the latter could be applied, hypothetically, to environments in RL, as is actually the best technical analogy for "Many worlds."
-->
<!-- [TO DO:: Add Henry quote from interview about worrying about AI being like "worrying about traffic regulation on Mars"] --><!-- I'm the martian, perhaps who will undergo a hard "execution"] -->
<!--
Also before my area exam, I taught Henry "sequence-to-sequence attention" from my office, in a state of misery that I couldn't convey, as I was also working on further innovations to MHDPA, now suffering due to grad-level classes, TAship, impending area exam, and the brain damage. I tried to tell Henry what was going on and he couldn't understand the severity, giving me an anecdote about his son's medication.
