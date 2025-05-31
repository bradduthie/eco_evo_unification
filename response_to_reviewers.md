General response to reviewer comments
================================================

We thank both reviewers for their valuable comments and suggestions. They helped us to improve the presentation of a number of points that were not entirely clear in the previous version of the manuscript and focus our revision on better communicating the aim of our work. To summarise, it does not appear that the accuracy or novelty of our proposed equation is in question. But the motivation for seeking and reporting it clearly needs to be better communicated. Couching this motivation in terms of major historical breakthroughs in science has set an incorrect and unintended tone; the point was to explain why pursuing abstract unifying equations is a valid and important part of scientific theory (using the strongest cases available), not to suggest that what we've done is field-changing in its importance!

Consequently, the references to major advances in science, which we appreciate came across as self-aggrandising, were motivated primarily by what we feel is a need to justify the importance and validity of a particular kind of theory. We have scaled back on this emphasis, but we feel as though some such justification is still necessary given the nature of comments from both reviewers, with Reviewer 1 closing their review with "[e]xplaining why it might be useful would help too", and Reviewer 2 stating that "if this equation does not produce evolutionary or ecologically meaningful results on its own, it's unclear that it has any utility". While we believe that there is scope to derive pragmatic results from our equation (i.e., new predictions), the primary goal of this manuscript is, unapologetically, about conceptual and theoretical clarity rather than prediction. This is not different from George Price's works from the 1970s. For example, in his 1972 paper he states that his now famous formula "is intended mainly for use in deriving general relations and constructing theories, and to clarify understanding of selection phenomena, rather than for numerical calculation" (Price 1972, 485). In this sense, our manuscript follows a similar path. We ask, what is most fundamental to all eco-evolutionary change? And we deliver a formal answer, the accuracy of which does not appear to be in question. Ideally, all formalisms try to achieve three characteristics at the same: generality, realism, and precision (Levins 1966). However, as Levins (1966) points out, it is not possible to achieve all of them at the same time and one of them needs to be sacrificed. When you theorise the way that we do here, specific (precise) predictions are sacrificed in favour of generality and realism (more on this later in relation to "dynamic sufficiency").

We contend that this kind of theory is important in ecology and evolution, even if it is not of widespread interest or appreciation (Caswell 1988). For example, even if the Price equation served no other purpose than to provide a formal, abstract, link between the fundamental equations of population and quantitative genetics (Queller 2017), it would still be a valid contribution to evolutionary biology, useful for providing conceptual clarity to theoreticians and demonstrating the logical consistency of the field. Hence, while we are optimistic about where our starting point might lead for developing new theory, we do not see this as being the most important or interesting outcome of this work.

Our equation is general and realistic. It is also simple; it couldn't be anything else given what we set out to achieve (and while it is perhaps trivial to verify in hindsight, it was not trivial to find). A fundamental equation of eco-evolutionary change must, by definition, be able to recover the fundamental equations of evolutionary biology (the Price equation) and population ecology (N_{t+1} = N_{t} + Births - Deaths). Our equation thereby defines what eco-evolutionary change is in its broadest sense; verbally, it is an interaction between individual fitness components (birth, death, and identity) and an individual characteristic.



Reviewer 1 comment 1 [ ]
==================================

The literature that is cited is VERY selective. There is a huge body of literature on linking ecological and evolutionary theory. High-dimensional matrix models have now been routinely used to link ecological and evolutionary dynamics by Barfield, Boots, Childs, Coulson, Ellner, Lion, Rees, Tuljapurkar and others. They have shown how by writing equations to dynamically track distributions of individual-level phenotypic traits and genotypes you can retrieve: the Price equation (including for structured populations) selection differentials and gradients, heritabilities, genetic covariances, the Euler-Lotka equation, equations for population growth, rates of evolutionary change, evolutionary end points, species interactions, and coexistence mechanisms. This literature needs citing and appropriately summarising. (It turns out it is straightforward to retrieve their equation from this modelling framework. if the authors did this, it will help reveal its limitations. One example is their delta zi terms get split into ontogenetic development among surviving individuals and genetic and non-genetic inheritance between parents and their offspring in age-structured populations).


Author response to Reviewer 1 comment 1
=====================================

We have revised our introduction extensively to address this comment and better communicate the goals of our work.

We agree with Reviewer 1 concerning the existence and importance of this literature integrating ecological and evolutionary theory. We are familiar with this literature, but all of the models developed by the authors mentioned by Reviewer 1, to our knowledge, are addressing questions that are fundamentally different from our own. These are highly general tools for integrating ecological and evolutionary dynamics, and we cited some key ones in our original introduction (Lion 2018; Patel, Cortez, and Schrieber 2018; Govaert et al. 2019). Lion (2018) and Patel et al. (2018) are particularly instructive examples because of how general they are: In Lion (2018), equations for ecological [ dn_{i}/dt = r_{i}(E)n_{i} ] and evolutionary [ f_{i}(r_{i}(E) - \bar{r_{i}(E)) ] change are defined as functions of an environmental vector E that can include other population densities or any relevant external variables. In Patel et al. (2018), ecological [ dN_{i}/dt = N_{i} f_{i}(N, x) ] and evolutionary [ dx_{j}/dt = e g_{j}(N, x) ] equations are similarly defined by general functions for population change (f) and trait change (g). Govaert et al. (2019) reviews eco-evolutionary feedback models.

There are, of course, other excellent examples by the authors Reviewer 1 cites.

For example, Barfield, Hold, and Gomulkiewicz (2011) develop a general model of eco-evolutionary dynamics in a stage-structured population. Their model is highly general, defining a multivariate quantitative trait with functions that define transition probabilities across different life stages; it makes some reasonable simplifying assumptions and nicely demonstrates that Lande's result of phenotypes evolving at the same rates across ages also applies to stages. This is an important and exciting theoretical result, but the authors also recognise the importance of putting it in the context of the fundamental equation of evolution: "In this section, we show how evolution in stage-structured populations can be related to a simple, universal law of evolution, Price's theorem (Price 1970), which provides a general statement about any evolutionary system -- including a stage-structured one". It is perhaps relevant to note that Price's (1970) motivation was solely to present a transparent "tool in qualitative evolutionary reasoning".

Lion, Sasaki, and Boots (2023) outline a theoretical framework linking quantitative genetics and adaptive dynamics, which reviews classical approaches to investigating eco-evolutionary dynamics and outlines key challenges for eco-evolutionary modelling. Rees and Ellner (2016) use an integral project model and compare it to an individual-based model (IBM), demonstrating how the former can be used to show why population structure changes are important for selection and generally recover results in the IBM. Coulson and Tuljapurkar (2008) investigate how selection on trait change can be partitioned into different components using an extension of the Price (1970) equation that accounts for age structure. 

We don't just point out these particular examples because they are written by authors that Reviewer 1 cites. These examples are also highly general models (with the ones cited in our original manuscript being especially general examples), and typically dynamically sufficient in a way that leads to interesting new eco-evolutionary predictions. They build off of very general functions as a starting point, as in Lion (2018) and Patel et al. (2018), or expand upon more fundamental equations such as that of Price (1970). But these models all have a different goal from ours; to be useful, they make simplifying assumptions to link ecological and evolutionary dynamics. 

Reviewer 1 is not correct in stating that these models retrieve the Price equation; the Price equation is not a predictive model but a mathematical identity that formally defines evolutionary change. Hence, it must always be possible, at least in theory, to retrieve the Price equation from any evolutionary model. These models don't retrieve the Price equation so much as the Price equation is necessarily embedded within them. The Price equation is not a simplified version of, e.g., Coulson and Tuljapurkar (2008), which includes a version of the Price equation that takes into account stage structure -- the latter is a specific case that is derived from the more abstract and exact former by making useful simplifying assumptions to generate novel predictions. The Price equation is also not just a generic mathematical function incorporating relevant evolutionary variables (as in, e.g., Lion and Patel examples mentioned above). Price (1970) is derived from first principles in evolutionary theory to define evolution in the same way that N_{t+1} = N_{t} + Births - Deaths defines ecological change.

Similarly, we attempt to define what is most fundamental to eco-evolutionary change. Our equation 1 does this formally, defining eco-evolutionary change in its most abstract and exact form as an interaction between fitness across different demographic components and individual characteristics. From eqn 1, the exact equations defining population and evolutionary change can be recovered. The simplicity of our equation is deceptive, and this is underscored by the fact that despite having never been discovered (to our knowledge), the equation can be used to derive the two most fundamental equations in ecology and evolution. As noted by Frank (1995, p. 381) in reference to Price's work, “[i]t is always difficult, in retrospect, to see the originality and insight of a simple idea”. While we certainly do not claim our work here to be field-changing, or as versatile as modelling tools from the abovementioned papers, we do believe that it is original and insightful in defining eco-evolutionary change.

In summary, are familiar with the literature pointed out by Reviewer 1, and we would even (quite happily) argue that this literature includes models that are highly general tools for modelling complex eco-evolutionary dynamics. The whole point of introducing the paper the way that we did was to illustrate that we are trying to ask a different question than the ones in those papers. We obviously need to try a different approach, and we have done this using extensive revisions in our introduction that address the points made above.


Reviewer 1 comment 2 [ ]
==================================

The equation that is developed is not dynamically sufficient. This means that without modification it is fairly limited in describing what happens over an individual time step. This is no surprise, because the Price is simply a tautology that is also not dynamically sufficient. The authors may have derived an equation that is worthy of publication. They need to be honest on its limitations (also see point 1). 


Author response to Reviewer 1 comment 2
==================================

We now state this more clearly in the text (Line XXX).

Reviewer 1 is of course correct that our eqn 1 is not dynamically sufficient. It couldn't possibly be, for exactly the reason that Reviewer 1 points out. The Price equation is a tool for unifying evolutionary models and providing conceptual clarity, which is necessarily achieved at the cost of any and all predictive power for a given system. Models need to make (simplifying, specific system) assumptions to be predictive (Levins 1966, Frank 2012), and a fundamental equation, by its nature, needs to be free of such assumptions and focus only on what is essential. The worthiness of our equation rests entirely on its power to unify fundamental equations of ecology and evolution and provide conceptual clarity, and its limitations are the same as any other fundamental equation.


Reviewer 1 comment 3 [ ]
==================================

The authors massively overstate the importance of their equation, starting with the title of "Darwin's dream". There is no evidence I am aware of that Darwin ever thought much about equations. The authors then talk about scientific breakthroughs, attempting to place their equation with other great equations of science. Astonishing self-belief, and not warranted given how much has been done in this space already and the limitations of their formulae. The paper needs toning down significantly. The equation is mildly interesting, but it is not field-changing. This self belief may come from the authors having been working in an echo chamber. This is even hinted at in the acknowledgements and author contributions.

If the authors were to say they have found a way to write an equation that links the Price equation to the equation that describes change in population size from one time step to the next, that would be an honest and critical placement of their work in the broader literature. Explaining why it might be useful would help too.


Author response to Reviewer 1 comment 3
==================================

We have changed the title and reframed the introduction. Our goal was to explain the importance of conceptual unification in the sciences (which, in our experience, is often underappreciated in the life sciences) without overselling our present results. In our revised introduction, we have attempted to tone down our own contribution while also not losing our central point that this kind of theory is important in science (i.e., *useful*, but because it demonstrates logical consistency and provides conceptual clarity -- not just because you can use it in the same way as a predictive model).

In our manuscript, we argue that our equation is fundamental to ecology and evolution. What we mean by this is that the fundamental equations of ecology and evolution can be derived from our eqn 1. What this illustrates is a logical consistency for developing theory, which has previously been assumed but never actually derived. It does not imply that our equation is more *important* than any other equation, and this might be at least partly responsible for what Reviewer 1 interpreted as an inflated self-belief and need to tone the writing down. We do not believe our work to be field-changing, but we do believe that it is more than mildly interesting, and that it is necessary for reasons that are not well-appreciated. 

What we have shown is a logical consistency between the fundamental equations of ecology and evolution (and, as far as we can tell, this is not disputed by either reviewer). This logical consistency has been assumed by theoreticians, and perhaps quite reasonably. But as a discipline, it is still important to do our due diligence and show that the theoretical foundations of ecology and evolution are solid. For example, within evolutionary biology, we can model evolutionary change using a population genetics framework or a quantitative genetics framework. In a population genetics framework, the average excess equation describes selection in terms of changes in allele frequencies, whereas in the quantitative genetics framework, the Breeder's equation describes selection in terms of changing quantitative traits (Queller 2017). These two equations are very important for modelling evolutionary change and predicting the consequences of selection. But an important role of theory is to demonstrate how (and why) these two equations are logically consistent, i.e., that they follow without contradiction from the same starting point that formally defines evolutionary change in any system. The Price equation and the framework that it establishes (Gardner 2020, Baravalle et al. 2025) is that starting point; it defines what evolution is in the broadest sense, meaning that any specific model of evolutionary change must be possible to derive from it. If a model of evolution cannot be put into the framework of the Price equation -- at least in principle -- then it is fundamentally flawed.

Hence, while the Price equation has very little direct relevance to the work of most evolutionary biologists, it is fundamental in the sense that it binds together all of evolutionary theory by defining what evolutionary change is (and is not). Our equation 1 fulfils the same criteria: from a deceptively simple starting point, eqn 1 can be used to derive the Price equation itself, but also the fundamental equation of population ecology. It therefore defines what eco-evolutionary change is (and is not), mathematically, at its most fundamental. Verbally, it is the interaction between absolute fitness and some characteristic of an individual.

The fact that the theoretical foundations of ecology and evolution are logically consistent is, of course, hardly a surprise. Had this not been the case, theoretical biologists would surely have noticed by now. But demonstrating this fact from first principles is, we believe, a worthy goal in itself, and something that we have considered exciting work.



Reviewer 2 comment 1   [ ]
======================

At the broadest level, I've always understood the Price Equation as explicitly including the birth-death process that would lead to the population growth rate equation from ecology. In the abstract sense, the Price Equation does not require ancestors and descendants to be different, and thus the relation between them necessarily captures births (when they are different) and deaths (when the ancestor is not among the descendants). This relationship allows mean fitness to capture the population growth rate, as first shown by Fisher (1930) and later by folks like Lande (1982) and Rice (2004). Day & Bonduriansky (2011) note that the total number of individuals in each time interval is the sum of all surviving parents and offspring; hence, they are Nt(births – deaths), which is Duthie & Luque’s equation 3. Now, a case could be made that stating this relationship in an obvious and explicit way is useful, but it seems to me that the original formulation of the Price Equation already subsumes population growth dynamics, so erecting an even broader equation isn’t necessary.


Author response to Reviewer 2 comment 1 
=====================

In some sense, it is true that the Price equation subsumes population change; if it did not, then we would not be able to produce a unifying equation from which both the Price equation and the general Nt(birhts - deaths) equation could be derived. However, in the traditional derivation of the Price equation, births, deaths, and population growth are not at all explicit. Instead, the number of individuals (or groups or genes -- whatever the entity is) is simply defined as the sum across n_{i} at t and n'_{i} at t + 1, and frequencies are then immediately defined by n_{i}/n and n'_{i}/n' (Price 1970; Frank 1997; 2012; Gardner 2008). Numbers of entities (n and n') are only mentioned so that the frequencies of entities (q_{i} and q'_{i}) can then be defined, and these frequencies are then used to work out entity fitness. To our knowledge, the Price equation has never been derived from births and deaths or with reference to population growth. Lande (1982) did introduce a demographic model for population demography and dN/dt = rN does appear (eqn 10), but this is in the context of a modelling assumption; the Price equation is then used to calculate a selection gradient. Similar to previously referenced eco-evolutionary models (see our response to Reviewer 1 comments), there is integration of ecology and evolution here, but not a demonstration of the key link from first principles. Similarly, Day and Bonduriansky (2011) define a value W that is the sum of offspring and survival, and this is used within a version of the Price equation to get mean fitness, but a formal link to population growth isn't made, with the goal instead being to predict evolving traits.

Overall, population change appears in models where the Price equation also appears, but what has always been missing is a derivation of both from the same starting point, from first principles of what actually happens in a population. Logically, this has to be possible because the same mechanisms that underlie population change (birth and death) also underlie evolutionary change. But up until now, to the best of our knowledge, the link between population and evolutionary change has always been carefully considered but ultimately ad hoc (as in the abovementioned references and, to our knowledge, all eco-evolutionary models). Given that we are looking at the same mechanisms of population change, we really should be able to demonstrate that both population change and evolutionary change can 'pop out' as intrinsically and necessarily linked from the same starting point. 

Figuring this starting point out was not easy; it needed to be done deductively, which inevitably led to many dead ends. Initially, we reasoned that because the Price equation is sufficiently abstract to describe trait change in any population (including groups and higher moments of traits), its recursive properties, and how useful it is for making formal links across disciplines such as physics and information theory (Frank 2015; 2016), we should be able to use it directly to recover population density change. This ended up being a dead end for reasons we will not dwell on (briefly, conservation of total probability -- that entity frequencies need to sum to 1 -- precludes the Price equation from being used to directly to recover absolute population change -- it's not a simple matter of, e.g., setting 'z' to population density). We had different issues when starting from population change and trying to recover the Price equation. There are a lot of ways to make coherent models using these avenues of inquiry, but none that recover universal and exact descriptions of population and evolutionary change. The broader equation, our equation 1, is indeed necessary to derive exact and universal eco-evolutionary change from first principles; it thereby serves as a formal definition for eco-evolutionary change in any system. It perhaps appears simple and obvious in hindsight, as if it could be inferred quickly from existing models by anyone giving it a modicum of thought. But we believe this appearance is highly deceptive; if this formal link were trivial to discover, then someone would have surely pointed it out already. After much investigation, we are confident that no one has, and while there are fundamental equations defining ecological and evolutionary change, separately, our work here is unique in establishing a fundamental equation that defines eco-evolutionary change.  

In our revision, we try to clarify the need for our equation more clearly.



Reviewer 2 comment 2 [ ]
======================

This leads me to my second point. The broader equation (1) is defined such that it introduces an abstract quantity (Omega), whose meaning depends on further definitions of variables. In its original formulation (1), it is meaningless. For example, if N = 3, beta = 1, delta = 1, z1 = 1, z2 = 2, and z3 = 3, and Deltaz = 0.5, then the first term in equation 1 reduces to 1, and the summation becomes a sum of z: 1.5 + 2.5 + 3.5 = 7.5, thus, Omega is the sum of z. But if the first term doesn’t reduce to 1, Omega becomes incomprehensible. Let’s say beta_1 = 2, with the other betas remaining as 1. Now,

Omega = (2-1 + 1)(1 + 0.5) + (1-1 + 1)(2 + 0.5) + (1-1 + 1)(3 + 0.5) = 10.5

What is "10.5" exactly? It has no meaning, as it is a unitless composition of both the number of individuals and the sum of the traits they possess. On Line 192, the authors suggest it might be £a quantity of ecosystem function", but I can’t imagine how that could be the case given that what it encompasses (traits and individuals) changes depending on the values of the summation, and different values of traits, birth, and death, would produce identical Omega values.



Author response to Reviewer 2 comment 2
=====================

As Reviewer 2 correctly states, the quantity Omega is abstract and lacks a concrete interpretation or predefined units in eqn 1. This isn't a problem and is actually necessary given what we are trying to achieve, which is to identify the equation from which fundamental equations of ecology and evolution can be logically derived. This requires a very high level of abstraction to encompass any possible eco-evolutionary change. 

The variable Omega is abstract and unitless for the exact same reason that 'z' is abstract and unitless in the Price equation. The Price equation requires a very high level of abstraction to be able to describe the change in some characteristic z for any possible evolving system. Units of z could therefore reflect any evolving characteristic (e.g., body size volume, discrete behaviour, phenology, number of hairs on a wing, carbon capture -- any measurable characteristic can be assigned to 'z' in the Price equation). Units of Omega in our equation will be identical to units of z, as used in the Price equation. Omega is just the sum across all individuals.

We appreciate that a concrete example can be helpful, and we thank Reviewer 2 for the suggestion. Here is how we would meaningfully use it: Let this small population of N = 3 be three different plants, which Reviewer 2 has assigned individual one a fecundity of beta = 2 and individuals two and three a fecundity of beta = 1. This population might be interpreted to have non-overlapping generations because death occurs for all individuals (delta = 1). Assume that we are interested in the rate of carbon capture of these plants, so this is the characteristic 'z' that we are measuring (e.g., in kg of carbon dioxide absorbed over some period of time). The DeltaZ = 0.5 would be a bit unusual, but could be caused by a change in carbon capture from t to t + 1 due to changing environmental conditions affecting the plants.

We could then calculate Omega as the summed rate of carbon capture attributable to the population from t to t + 1.

Omega = (2 - 1 + 1)(1 + 0.5) + (1 - 1 + 1)(2 + 0.5) + (1 - 1 + 1)(3 + 0.5) = 9

Note that Omega = 9 in the example Reviewer 2 gave (the 10.5 was just a calculation error). That is, the total carbon capture summed across all individuals is 9 kg. There is no problem with units here; the correct unit is kg, not a combination of individuals and kg.

Counts are unitless, inherently, and 'individual' is a label rather than a unit in this case, regardless of whether it is in beta (births attributable to individual i), delta (death indicator of i), or 1 (the count of i itself). 

From the Bureau International des Poids et Mesures (2019) The International System of Units (SI) (9th ed.) (https://www.bipm.org/en/publications/si-brochure/): "There are also some quantities that cannot be described in terms of the seven base quantities of the SI, but are quantities that are a number of entities. Examples are a number of cellular or biomolecular entities, or degeneracy in quantum mechanics. These quantities are also quantities with the unit one", then "The unit one is the neutral element of any system of units – necessary and present automatically. There is no requirement to introduce it formally by decision."

A major part of our work here is to set the fundamental equations of ecology and evolution on as solid of a foundation as possible. And while the point about units that Reviewer 2 raises is thought-provoking (we had to go back to the basics ourselves to work out whether or not this was an issue for our equation), the logic of our equation remains airtight.

Intuitively, note that if we were just interested in measuring total carbon capture in a population, then it wouldn't be a problem to, hypothetically, just sum up how much each individual captures carbon. Similarly, if we wanted to measure total biomass, or decomposition, or pollination in a system (anything, really), it would be entirely sensible (if it were possible in practice) to add up the contributions of each individual to the whole. And this is what we're after with Omega -- the summed value of traits across all individuals.

Now, in the special case in which z = 1 (which is, again, a unitless count), we recover the total number of individuals, as derived in our manuscript. In this case, Omega is interpreted as individual number (N), and,

Omega = (2 - 1 + 1)(1 + 0) + (1 - 1 + 1)(1 + 0) + (1 - 1 + 1)(1 + 0) = 4

Our population size has increased from 3 to 4 because two individuals produced one offspring each (beta = 1), and one produced two (beta = 2). All of those reproducing individuals died (delta = 1).

We thank Reviewer 2 for raising this query; it gave us pause to reflect and be even more deliberate about what our equation is describing. We now mention in our manuscript why this is not an issue by pointing out that individuals are unitless (LINE).



Reviewer 2 comment 3  [ ]
======================


Thus, if I'm understanding correctly, equation 1 only becomes meaningful once the steps are taken to reduce it to either the population growth rate equation or the Price Equation. This feels like deriving a fundamental equation in reverse – starting from two known fundamental equations, and then working backwards to piece them together. Which perhaps is a fine approach on its face, but if this equation does not produce evolutionarily or ecologically meaningful results on its own, it's unclear that it has any utility.


Author response to Reviewer 2 comment 3
======================

This is incorrect; eqn 1 is meaningful as written as a definition of eco-evolutionary change. It is, however, correct that the units associated with 'z' (and therefore 'Omega') are unresolved until 'z' is defined (see our response to Reviewer 2 comment 2 above). But this is no different from the Price equation itself. Our equation doesn't need to recover either the population growth rate equation or the Price Equation to be meaningful. On the contrary, the logic of our manuscript is to develop a unifying framework for eco-evolutionary change. Of course it is good and necessary to prove that we can recover the two most fundamental equations of ecology and evolution. But that is not the end of the story. If our equation only worked through specifying an ecological scenario or an evolutionary scenario, but not both, then it would not fulfil its intended purpose.  

We can appreciate why it might feel like our equation 1 works backwards from the fundamental equations of ecology and evolution separately. But this isn't the case, logically or methodologically (see our response to Reviewer 2 comment 1). What we show is that the appropriate starting point for defining eco-evolutionary change is the interaction between births/deaths and individual characteristics. Our starting point isn't arbitrary or contingent; it is exact and universal, and no other equation would work as fundamental (anymore than the Price equation or general population change could be substituted by something else as fundamental equations).

We now emphasise more clearly, in words, the interpretation of equation 1 and how it is meaningful even prior to the derivation of population change or the Price equation (LINE XXX).



Reviewer 2 comment 4  [ ]
=========================

Lastly, there are a series of statements made in the Abstract that feel like they either are not followed through on or only weakly mentioned in the Discussion. For example, we are told that this unification “shows how ecological and evolutionary change are reflected in the first and second statistical moments of fitness”, but this is fleshed out in a single sentence in the Discussion (Line 236–238): “Interestingly, the rate of change in ecology and evolution are reflected in the first and second statistical moments of fitness, respectively. Population growth rate reflects mean fitness w ̄ , while the rate of evolutionary change reflects the variance in fitness Var(w).” There appears to be no other mention of this outside the Abstract. Importantly, as the authors note, each of these things are already known – both the equivalence of population growth rate with mean fitness and the rate of evolutionary change being equal to the variance in fitness are found in Fisher (1930).



Author response to Reviewer 2 comment 4 
=========================

We now remove this from the abstract. In the manuscript, we now clarify that our derivation recovers this relationship, which has been pointed out previously.




Reviewer 2 comment 5 [ ]
=========================

Furthermore, the Abstract claims the unification links ecosystem function to population growth rates and evolutionary change, but this is only speculated on in the last paragraph of the Discussion. The authors cite others who have explicitly done this, suggest that their equation might do the same, but there’s no demonstration of it or suggestion of what it might be. Again, this could be because it’s not obvious to me the connection, so the authors need to be a little more explicit in showing these connections.



Author response to Reviewer 2 comment 5
=========================

We are grateful to Reviewer 2 for pointing this out, and we have revised to make our point about ecosystem function clearer with a more concise explanation of our point in our response to Reviewer 2 comment 2. We now elaborate on how Omega can be interpreted as a measure of ecosystem function for a population (LINE XXX).



Reviewer 2 minor comment 1 [ ]
=========================

Title – I like the title, but Darwin is never mentioned in the text! I kept expecting to see something about how “Darwin dreamed to unite these fields” or something.


Author response to Reviewer 2 minor comment 1
=========================

We also liked the title, but it is clearly causing confusion. We have switched to 'Foundations of ecological and evolutionary change'.



Reviewer 2 minor comment 2 [ ]
=========================

Lines 26-28 – I would also cite Betty Smocovitis’ excellent paper here on the unification of biology via evolution: Smocovitis, V. B. (1992). Unifying biology: the evolutionary synthesis and evolutionary biology. Journal of the History of Biology, 25(1), 1-65.



Author response to Reviewer 2 minor comment 2
=========================

This is a good suggestion; we have cited this paper now (Line XXX).




Reviewer 2 minor comment 3 [ ]
=========================


Lines 45-54 – This historical presentation seems odd to me. My reading of history is that these two fields have always been pretty tightly intertwined; Darwin’s argument relied on Malthusian concepts of population growth, after all, and one of the first concepts of density dependent selection comes from Haldane (1956). But I could be biased. Perhaps a citation after the sentence: “Until recently, population ecology and evolution in particular have taken almost parallel paths for developing theory” to others who have argued this would be helpful.



Author response to Reviewer 2 minor comment 3 
=========================

We are not historians and we don’t claim to have the ultimate answer on this issue. Our reading of history is the following. The theory of evolution by natural selection developed by Darwin is inherently an ecological theory, and the last third of the 19th century saw the development of ecological work rooted on ivolution. In a work devoted to the historical relationship between ecology and evolution, James P. Collins (1986, p. 260) states: "In 1866, for example, Haeckel claimed that the theory of evolution explained and formed the groundwork of ecology. Stephen Forbes argued in 1895 that the whole Darwinian doctrine belonged to ecology. Just after 1900 H. C. Cowles wrote, "If ecology has a place at all in modern biology, certainly one of its great tasks is to unravel the mysteries of adaptation." At that same time, J. G. Needham described ecology as "the study of the phenomena of fitness." 

However, that doesn’t imply that ecological theory/practice and evolutionary theory/practice have always been as intertwined as one would think. The progressive specialisation of both areas produced subdisciplines with no evolutionary input/perspective, or evolution (specially adaptation) was just taken for granted, orienting their research to mechanistic/proximate questions (in terms of Mayr and Tinbergen conceptualization of proximate vs. ultimate questions). Moreover, fields such as systems ecology (from Odum to Margalef) could be thought of as a renewed version of the Romantische Naturphilosophie, with little (if any) connection with evolution. Collins (1986, p. 258) cites works from the 1950s claiming for the necessity of an autonomous ecological theory, free of evolutionary thinking. All of this may explain remarks like the following during the 1960s: "The theory of evolution by natural selection is an ecological theory -founded on ecological observation by perhaps the greatest of all ecologists. It has been adopted by and brought up by the science of genetics, and ecologists, being modest people, are apt to forget their distinguished parenthood. Indeed, Darwinian plant ecology has been largely neglected" (Harper 1967 p. 267). 

After 1960, evolutionary ecology emerged and many ecology textbooks (Pianka 1974, Roughgarden 1979, Begon et al. 1986/2006) included an evolutionary perspective and entire chapters devoted to evolution. However, we think that the pursuit of a true synthesis of evolutionary and ecological change (eco-evo dynamics) has only taken place (roughly) in the last two decades, with several works trying to develop a more unified framework (as far as we know, only one textbook (Hendry 2017) has summarized these eco-evo efforts). Part of the motivation for this synthesis has been the relatively recent appreciation of concurrent ecological and evolutionary dynamics. From Yamamichi, Ellner, and Hairston Jr. (2023), "Although ecology and evolutionary biology have been neighbouring research areas ever since the age of Darwin, the prevailing assumption had long been that ecological processes occur much faster than evolutionary processes".

One of our critiques of eco-evolutionary theory is that there is no formal integration of the foundational axioms shared by both ecology and evolution. Our take is that we should have an eco-evo formalism tout court, which takes a separate but complementary role to existing eco-evolutionary models, which require simplifying assumptions and typically start with ecology or with evolution and then try to include the other one in the model. 

Finally, we also agree with Reviewer 2 that classic evolutionary works (like those developed by Haldane) had ecological ingredients. Actually, as we said in our manuscript, our claim is that, contrary to a spread view among evolutionary biologists (see page XXX of our manuscript for references), population genetics has ecology at its core, though not in an obvious way.

We now clarify this historical view (Line XXX) 



Reviewer 2 minor comment 4 [X]
=========================


Line 106 – “Fischer” should be spelled “Fisher”.


Author response to Reviewer 2 minor comment 4
=========================


Fixed (Line XXX).



Reviewer 2 minor comment 5 [ ]
=========================

Lines 273-274 – If these derivations were included here, it would dramatically clarify my confusion about the usefulness and meaning of Omega in the general formula.


Author response to Reviewer 2 minor comment 5  
=========================

We are reluctant to include too much work still in preparation, or distract from what we believe is the central message of the current manuscript. But we have now included some additional derivations in supporting information.



Author references
==============================

Baravalle, L., Jonathan Roffé, A., Luque, V. J., & Ginnobili, S. (2024). The Value of Price. Biological Theory. https://doi.org/10.1007/s13752-024-00482-4

Barfield, M., Holt, R. D., & Gomulkiewicz, R. (2011). Evolution in stage-structured populations. American Naturalist, 177(4), 397–409. https://doi.org/10.1086/658903

Bureau international Des poids et mesures (2019) The International System of Units (SI).
https://www.bipm.org/documents/20126/41483022/SI-Brochure-9.pdf 

Caswell, H. (1988). Theory and models in ecology: a different perspective. Ecological Modelling, 43, 33–44.

Coulson, T., & Tuljapurkar, S. (2008). The dynamics of a quantitative trait in an age-structured population living in a variable environment. American Naturalist, 172(5), 599–612. https://doi.org/10.1086/591693

Levins, R. (1966). The strategy of model building in population biology. In American Naturalist (Vol. 54, Issue 4, pp. 421–431). https://doi.org/10.2307/27836590

Frank, S. A. (1995). George Price’s contributions to evolutionary genetics. Journal of Theoretical Biology, 175, 373–388.

Frank, S. A. (1997). The Price equation, Fisher’s fundamental theorem, kin selection, and causal analysis. Evolution, 51(6), 1712–1729.

Frank, S. A. (2012). Natural selection. IV. The Price equation. Journal of Evolutionary Biology, 25, 1002–1019. https://doi.org/10.1111/j.1420-9101.2012.02498.x

Frank, S. A. (2015). D’Alembert’s direct and inertial forces acting on populations: The price equation and the fundamental theorem of natural selection. Entropy, 17(10), 7087–7100. https://doi.org/10.3390/e17107087

Frank, S. A. (2016). Common probability patterns arise from simple invariances. Entropy, 18(5), 1–22. https://doi.org/10.3390/e18050192

Price, G. R. (1970). Selection and covariance. In Nature (Vol. 227, Issue 5257, pp. 520–521). https://doi.org/10.1038/227520a0

Price, G. R. (1972). Extension of covariance selection mathematics. Annals of Human Genetics, 35(4), 485–490. https://doi.org/10.1111/j.1469-1809.1957.tb01874.x

Queller, D. C. (2017). Fundamental theorems of evolution. American Naturalist, 189(4), 000–000. https://doi.org/10.1086/690937

Lion, S. (2018). Theoretical approaches in evolutionary ecology: environmental feedback as a unifying perspective. American Naturalist, 191(1). https://doi.org/10.1086/694865

Lion, S., Sasaki, A., & Boots, M. (2023). Extending eco-evolutionary theory with oligomorphic dynamics. Ecology Letters, 26(S1), S22–S46. https://doi.org/10.1111/ele.14183

Patel, S., Cortez, M. H., & Schreiber, S. J. (2018). Partitioning the effects of eco-evolutionary feedbacks on community stability. American Naturalist, 191(3), 1–29. https://doi.org/10.1101/104505

Govaert, L., Fronhofer, E. A., Lion, S., Eizaguirre, C., Bonte, D., Egas, M., Hendry, A. P., de Brito Martins, A., Melián, C. J., Raeymaekers, J. A., Ratikainen, I. I., Saether, B. E., Schweitzer, J. A., & Matthews, B. (2019). Eco-evolutionary feedbacks—Theoretical models and perspectives. Functional Ecology, 33(1), 13–30. https://doi.org/10.1111/1365-2435.13241

Rees, M., & Ellner, S. P. (2016). Evolving integral projection models: Evolutionary demography meets eco-evolutionary dynamics. Methods in Ecology and Evolution, 7(2), 157–170. https://doi.org/10.1111/2041-210X.12487

Lande, R. (1982). A quantitative genetic theory of life history evolution. Ecology, 63(3), 607–615. http://www.primes.colostate.edu/Lande 1982.pdf

Rice, S. H. (2004). Evolutionary theory: mathematical and conceptual foundations. Sinauer Associates.

Gardner, A. (2020). Price’s equation made clear. Philosophical Transactions of the Royal Society B: Biological Sciences, 375(1797), 20190361. https://doi.org/10.1098/rstb.2019.0361

Gardner, A. (2008). The Price equation. Current Biology, 18(5), 198–202. https://doi.org/10.1016/j.cub.2008.01.005

Harper, J. L. (1967). A Darwinian Approach to Plant Ecology. In Source: Journal of Ecology (Vol. 55, Issue 2). https://about.jstor.org/terms

Pianka, E. R. (1974). Evolutionary ecology.

Roughgarden, J. (1979). Theory of Population Genetics and Evolutionary Ecology: An Introduction.

Begon, M. et al. (2020). Ecology: From Individuals to Ecosystems.

Hendry, A. P. (2017). Eco-evolutionary dynamics. Princeton university press.

Yamamichi, M., Ellner, S. P., & Hairston, N. G. (2023). Beyond simple adaptation: Incorporating other evolutionary processes and concepts into eco-evolutionary dynamics. Ecology Letters, 26(S1), S16–S21. https://doi.org/10.1111/ele.14197