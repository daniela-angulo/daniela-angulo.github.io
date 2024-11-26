---
layout: default
---
<!---
**What is this about?** This is a website to share my projects and thoughts related to physics and education. Maybe even cycling. 
-->
# What do I do? Who am I? 

Disclaimer: This website is by no means complete, I am working on it.

I'm Daniela Angulo and I'm from Colombia. I recently finished my PhD in experimental quantum optics. I also worked as a high school teacher for grade 12 for two years. I taught physics to a small group of amazing kids. I love sports and music. Cycling, swimming, running. Playing the guitar and singing. 

After my PhD, I started working as a postdoc for the same group but switched fields. Now I am working in the photons side of my lab in projects about quantum metrology and quantum foundations. 

Check out this <a href="https://www.youtube.com/watch?v=8QJ0atPx-Qc">interview </a>  I gave to Q-Site as part of their series "Quantum walk Wednesday".

# Quantum physics
I devote a lot of my time to studying quantum optics and quantum information. I'll use this section to tell you about some research topics that interest me or my own research. 

In our research group, we had to present a paper of our choice every three months or so to the rest of the group (journal club). I work with atoms and photons but photons are my biggest love so I usually used those presentations as an opportunity to talk about photonics research. 

I must say that I used to have a lot of difficulties with these presentations for the first two years of my PhD. I wasn't able to grasp the big ideas of the subjects and didn't exactly know what questions to ask to clarify the things I didn't understand. But I've got sooo much better at it and my prof even said how impressed he was with the pedagogical angle of my presentations. According to him, I was raising interesting questions and forcing the audience to think. 


## How much time do photons spend in the excited state? (my thing)

When a particle of light (a photon) travels through a cloud of atoms, it will meet one of two fates: either it will be transmitted through the cloud, or it will be absorbed by an atom, exciting it, and subsequently 'ejected' in a random direction when the atom decays to its ground state (de-excitation). It is straightforward to calculate how often photons are 'lost' in this way, and one can even calculate how long the average photon spends 'inside' an atom. An interesting question arises in this scenario: does the time that a photon spends inside an atom depend on its eventual fate? In other words, if a photon passes through a cloud of atoms without being lost, should we conclude that it never interacted with an atom, and therefore spent no time as an atomic excitation? This question turns out to be surprisingly challenging to answer theoretically as it entails discussing the 'history' of a quantum particle. However, we decided to take an experimental approach and perform the first experiment to measure the time that a transmitted photon spends as an atomic excitation.

![Schematics](/assets/images/setup.png)
**Experiment:** Cartoon view of my experiment. 

I have now a more complete summary of my research and check out the arxiv version of the <a href="https://arxiv.org/abs/2409.03680">experimental paper</a>. This summary is written for physics or related fields students. 

> Why does light slow down in glass? This is a deep question about how light interacts with matter. The short answer is that when a wave encounters an insulating material, the atoms respond to the wave by vibrating. These oscillations of charged particles generate new waves, which, when combined with the incident wave, cause the overall wave to move more slowly.
>
<img src="/assets/images/meme.jpg" alt="Meme" class="center"> 

>But light is made up of photons. So, what exactly are these photons doing inside the material that results in this delay?
>
>Although physicists tend to not take this picture too seriously, some might wonder if the delay happens because photons occasionally get absorbed by atoms and are later re-emitted. Does the photon spend some time "inside" the atom? If so, how long? And is this time equal to the total delay experienced by the light wave?
>
>To explore these questions, we need to dive into quantum mechanics. To talk about the value of an observable quantity, we have to imagine that there's some interaction with a probe system that can measure that quantity. In our experiment, we measured how long atoms stayed in an excited state, given that a photon passed through and was detected on the far side of the atom cloud. We did this by introducing an auxiliary beam that weakly interacts with the atoms, experiencing a phase shift proportional to the atomic excitation caused by the single photon. This approach let us probe the system gently, though at the cost of only gathering small amounts of information per trial.
>
>What we discovered is both surprising and fascinating: transmitted photons seem to cause atoms to spend positive, zero, or even negative time in the excited state. Even more remarkably, we confirmed that this excitation time matches the group delay—a concept in optics that describes how much a pulse of light is delayed while propagating through a medium.
>
>So, what’s going on? Does time run backward? Is special relativity in danger? The answer is no—time is not running backward, and the laws of physics, including that no signal can travel faster than the speed of light in vacuum, remain intact. The key lies in the nature of our measurement. Because it is a weak measurement and one that only accounts for transmitted photons, ignoring scattered ones, unusual outcomes can happen.
>
>Our measuring device was intentionally noisy to avoid disturbing the system. This imprecision makes it impossible to tell if a photon was transmitted by passing straight through the cloud without interacting with the atoms, or by briefly exciting an atom and being re-emitted in the same direction. As a result, the auxiliary beam ends up in a quantum superposition: part of it showing no time spent in the atom and another part showing a small positive time. The negative result emerges from destructive interference between these two components, imaging taking "zero" minus "something positive.” You can also think of it as constructive interference in regions where results are normally forbidden and destructive interference where they are allowed.
>
<img src="/assets/images/popsum2.png" alt="gaussians" class="center"> 

>This experiment gives us new insights into the interaction between light and matter, offering a glimpse into the history of transmitted photons. We’ve shown that group delay not only tells us where the center of a light pulse is located but also accurately describes the magnitude—and even the sign—of the effect transmitted photons have on the atoms they interact with.

### Controversy around "negative" times

The title of our arxiv paper is <b>Experimental evidence that a photon can spend a negative amount of time in an atom cloud</b>. The paper drew a lot of attention, but also sparked considerable controversy for understandable reasons. 

Scientific American wrote an <a href="https://www.scientificamerican.com/article/evidence-of-negative-time-found-in-quantum-physics-experiment/">article</a> about it. We were even featured in one of Sabine Hofsteder's  <a href="https://www.youtube.com/watch?v=ErLHm-1c6I4">videos</a>. Watch the video and try to spot her mistake around the 3:30 mark. 

One could argue both for and against the title being labeled as 'clickbait.' While it is true that the photon didn’t literally spend a negative amount of time inside the atom or travel backward in time, the experimental result did yield a negative number. Specifically, the quantum "watch" we designed measured a negtive time, which supports the title's claim. For this reason, while provocative, the title cannot be entirely dismissed as clickbait.

### Poster

If you are more into posters, here is a poster that I made to present my work at a conference in Milan in 2023. I even won an award for it.

![Poster](/assets/images/CEWQOP_2023_Poster.jpg)

## Quantum State Tomography: hidden degrees of freedom

This work shows that one can quantify and see the effect of distinguishability in multiparticle photon states. This distinguishing information is encoded in hidden degrees of freedom. The example used by the paper is reconstructing the state of two photons in polarization but can have distinguishing information in the spectro-temporal modes. The visible degree of freedom will be polarization and the hidden one is arrival times.  

They show that you can infer there is distinguishing information in arrival times by making tomographich measurements in polarization. The key idea behind this is that the density matrix for the visible degree of freedom contains no coherences between the symmetric and antisymmetric subspaces. For two photons in polarization, it is written as a diagonal block matrix with a 3x3 representing the symmetric subspace and a single element for the single state. 

An example to show the usefulness of this method is to consider a known polarization state (like HV) and reconstruct the visible density matrix for when the photons are indistiguishable. Then introduce a time delay greater than the coherence length of the photons and reconstruct the density matrix. They observed that in the first case, all the population is concentrated in the symmetric subspace (3x3 matrix), but when the delay is introduced, the singlet state subspace. 

# Teaching

I love teaching. I love the challenge of trying to understand something so well that you are able to explain it to all kinds of audiences with clarity. 

During my PhD, I was a teaching assistant (TA) for several courses. My favorite were Introduction to quantum physics and Introductory optics. I wrote python scripts to illustrate some of the subjects that we studied. Check the repositories for the demos in my <a href="https://github.com/daniela-angulo">github</a>. 

### Statement of Teaching Philosophy

>Physics, like every science, is a communal practice. One can start by observing a phenomenon, proposing a set of explanations, and testing them experimentally, usually in collaboration with other people. Even if one could manage to do the testing and experimenting alone, the results and conclusions still need to be communicated to and accepted by a big part of the scientific community to be considered valid. I think the communal character of science should be a key part of teaching physics. 
>
>When students come to class, they bring ideas, preconceptions and all their cultural background. They perceive the information with their senses and interpret it to form a mental image of a concept. I can not possibly tell if their mental image matches the one I am aiming to communicate but I can try to be as clear as possible conveying the fundamentals and creating consensus in the class. That clarity requires that I present information using different approaches to give everyone the opportunity to feel comfortable with their learning preferences; I could use a case study based on a real-life example, an experimental demonstration in class, or computer demonstrations. The students ultimately build their own knowledge and I have to make sure I provide all the tools for them to become active agents in their learning process; not to consume knowledge but to create their own. For this purpose, I include multiple means of engagement and assessment; online education has called my attention to tools like polls, discussion boards, interactive simulations and collective documents that I use to foster collaborative interactions among students. Regarding assessment, I combine traditional approaches along with open ended problems and exploratory projects that do not have a unique answer so students can experience a research-type activity and have freedom to pursue personal interests without feeling pressured about grading. 
>
>A good teacher should connect new ideas to existing ones; make the students feel a bit of discomfort with their preconceptions so they can be motivated to learn scientific ideas. When I teach optics, I often choose mirages to introduce total internal reflection of light. Before presenting any physics, I assess the students’ everyday conceptions and previous knowledge with a survey; some of them might think that mirages in a highway are caused by a reflection caused by water on the road. Then by organizing small discussion groups, they could see how their explanation is incomplete or contradicts others’. Finally, total internal reflection is gradually introduced by a series of steps, some of them are worked in groups, where they have to fill in the gaps. Asking them, for example, to qualitatively describe how the temperature and density of the air changes as you go higher above the road. In this session, the students describe a real world situation using mainly optics and that description is linked to other subjects like thermodynamics. By means of this example, I incorporate another one of my teaching pillars that is to always put physical concepts into context and show the connections between different fields of physics. 
>
>I acknowledge and value how every student is unique and diverse. As a woman in a heavily sexist field like physics, I have reflected and educated myself on equity issues like sexism and racism. I am aware of the fact that these are systemic problems and my individual efforts in a classroom are not going to fix them but it is still a priority for me to address them in my class; I want the students to see my class as a safe and comfortable space for them to be themselves. For that reason, I provide diverse means to participation and evaluation, welcome all questions and constantly encourage them, promote appreciation of others’ thoughts and opinions, and constantly work against my own biases.
>
>I love learning and that keeps me motivated to teach. Working with students always brings something new: a question you had not considered before, completely different approaches to solve a problem, new connections of what is taught in class to nature phenomena, etc. The more I teach, the more I learn. It is not only about understanding the contents on a deeper level, I also need to be constantly looking for better teaching practices and studying the context where my students live to relate better to them.  Besides all the things I learn, I can establish human connections with my students, maintaining professionalism, such that they feel listened and supported and we all feel a bit less lonely by learning together. 
