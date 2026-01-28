The file 'CoCo-GAN'introduces a game theoretic regularization of Wasserstein GAN.

The file 'Fibrations explain all you need!' introduces fibrations as a model for abductive reasoning and as an attention mechanism.

The key idea here is to treat being a fibration not as a property, but as structure.

Our fibration definition does not use a universal property - a property of some construction which boils down to (is manifestly equivalent to) the property that an associated object is a universal initial object of some (auxiliary) category.
 
Instead we introduce lifting structures.  One consequence of shifting to a structured definition is that notions of fibration which are logically equivalent as properties are no longer isomorphic as structures.  This leads to the imposition of compatibility conditions on liftings. 

So we trade imposition of universality, a form of optimization, for structural compatibility, that as we will see informs abductive reasoning and attention mechanisms.  

This curious nuance through shift in perspective finesses trying to conceptualize notions of best plausible explanation consistent with the data.  Moreover, it has a cognitive interpretation for human abduction which employs analogy and heuristics.  

Sidebar:  Perhaps a constructive model of univalent foundations also needs to be structural rather than universal property driven?


Abstract for the file 'Neural Network Abduction':
For hypotheses whose effect is manifested by observations, abduction seeks to explain a given observation by finding a hypothesis whose effect is that observation.  Abductive reasoning has a fibration semantics that can be implemented by neural networks; a step towards artificial general intelligence.  


For an effect, 'Parsimonious Neural Network Abduction' introduces a parsimonious learnable selection mechanism to choose the simplest most plausible explanation of an observation.


'Attention Fibration Abduction' shows that a certain neural network fibration embodies both attention and abduction.


'FibChat – It makes stuff up, but with structure.'
Query updating via fibration attention.
A new transformer attention mechanism via fibrations.


'Fibformer - a fibration transformer'
The generic transform attention mechanism (for sequence-to-sequence or next-token) applies a feed forward neural network element wise to query updates to introduce non-linearity in update refinement.  In contrast, we learn a lifting neural network for a fibration, that takes into account the semantics of the key-value pairing by abductively choosing a key that explains a continuation value.


'Formal query updating' introduces a formalism to generate query update algorithms founded on standard and fibration attention primitives.

'Multi-head abductive attention' Transformer multi-head attention can focus on different parts of an input query sequence, however without regard to potentially different key-value semantics.  We introduce an additional primitive to the vocabulary of formal query updating.  The new construct updates a query in parallel, learning multi-head abductive fibration liftings, to refine similarity based attention, utilizing the semantics of multiple key-value pairings.


'Contextual Fibration Attention' 
In a query-key-value attention model, the key-value pairing conveys language semantics.  
Query context also carries meaning.  
We introduce an abductive fibration attention model that holistically captures both.  
A fibration lifting, jointly learns from query context and language semantics 
(that abductively finds a key to best explain the returned value).


'Deep Fibration Attention' - meta abduction semantics for query updating.


'Attention Legos' - Fibration abductive attention building blocks for machines to learn world models.


'Jury Attention' - To address the Rashomon effect when multiple key-value semantics are present, we introduce a jury attention mechanism via fibrations.  This accomplishes query updates that take into account differing world views.


'Fibration Attention Dynamics' - We characterize the dynamics of query updating coming from fibration abductive attention mechanisms, using perturbed Koopman operators that are invertible.  Importantly, we identify conditions for Lyapunov stability of solutions near equilibrium points.  Depending on the Koopman resolvent, some key-value pairings can have query update trajectories that are Lyapunov stable.


'Quantum Attention' - The quantum nature of fibration abduction attention. A LLM paradigm shift from similarity to explanation.

'Quantum Attention Algorithm' DOI: 10.13140/RG.2.2.16357.87522


'Attention Entanglement' - Transformer attention uses statistical correlation to update queries, and 
fibration abduction attention on top, takes into account key-value semantics,finding a key to explain 
the value returned.  The latter has a quantum interpretation, indeed a fibration lifting is an entanglement.  
Entanglements (inner loop) can be refined using a Renyi α-entropy criterion, as part of a simultaneous 
query and key update (outer loop).  Thus the value returned then reflects refinement of both 
query-key similarity and key-value semantics.


'Domain Specific Abductive Attention'
DOI 10.5281/zenodo.17413742
- a mathematically grounded structure (fibrations and liftings) to perform constrained, explainable, abductive reasoning within specialized domains, directly addressing the critical flaws of hallucination and lack of domain specificity.


'Chu-former' - a semantic bridge from questions to answers 
via Chu duality in a fibration attention mechanism
DOI: 10.13140/RG.2.2.36204.22403


'Ouroboros' - Chats on the implications and applications of Chu-former on LLM.


'Amortized Chu-former' - fast semantic handshakes
DOI: 10.13140/RG.2.2.24574.86082
Chu-former semantic handshakes between questions and answers are achieved by learning a pair of fibration liftings.  We introduce an amortized version to reduce the computational burden at the expense of approximate explanation.


'Lost in translation'
Chu-former attention can be used in LLM for next token Q&A or translation and even medical differential diagnosus.


'Aperioc Mechanism' Attention via an implict model.
DOI: 10.13140/RG.2.2.24092.14725/1


'Noken: implicit contextual token learning'
DOI: 10.13140/RG.2.2.17440.24329/1
Given a token in a context string, an implicit deep learning model reveals a latent token, that we dub a ‘noken’, and token representations, such that keys embue meaning to queries and values.  This construction can then be construed as a machine oracle that aligns meaning utilizing a universal interlingua for next-token and sequence-to-sequence learning.


'Noken variations'
DOI: 10.13140/RG.2.2.33204.92805/1
Six variations to update and refine a query are presented, each a method for next-token or sequence-to-sequence learning.


'Noken squared' - implicit implicit contextual token learning 
DOI: 10.13140/RG.2.2.20497.49768/1
Composing implicit token models is a way to update queries in a query-key-value attention mechanism.  Coherent refinement is achieved when Renyi α-entropy is reduced.  This approach jointly learns query, key, value embeddings and query updates, coordinated by concatenated implicit models.

'Thinking machines via Noken networks' DOI: 10.13140/RG.2.2.10400.85765/1


'Sematic Attention via Noken Nen' DOI: 10.13140/RG.2.2.10508.99202
Noken, implicit deep learning models, can be composed into cascades, as well as connected into feedback loops, like Zen Nen.  Given a target input token from a context string, we can take a draw from a distribution over the string centered at the target, to provide auxiliary contextual information.  A Noken, a latent token representing the target, can be potentially refined in a cascade, or iterated in a feedback loop, to utilize the auxiliary information of the drawn token.  Convolution like network configurations are explored to reduce average Renyi α-entropy, for the purposes of zero-shot next-token and sequence-to-sequence learning.  Beyond statistical correlation, Noken networks introduce a novel attention mechanism based on semantic architecture.


'Semantic Transfer Learning' DOI:10.13140/RG.2.2.36220.40324
 For the purposes of zero-shot next-token and sequence-to-sequence learning, Noken implicit deep learning models, can be composed and connected into feedback loops, enabling a myriad of network configurations to be explored, and so find ways to lower average entropy.  Beyond statistical correlations, this novel attention mechanism is based on semantic architecture.  
	Suppose we have learned the semantics of two different subject domains and want to explore interdisciplinary inquiries.  Without starting over from scratch and training on the all combined data (which may in fact muddle matters) we introduce an algorithm to leverage and transfer the individual semantics to make sense of the interdisciplinary corpus.


'Noken Rademacher Descent' DOI: 10.13140/RG.2.2.20368.47367
Semantic refinement of Noken attention, via query-key similarity alignment, can be achieved by Rademacher descent of implicit model hyperparameters.


'Noken Genetic Algorithms' DOI:10.13140/RG.2.2.31041.01123
Beyond statistical correlation,  for the purposes of next-token and sequence-to-sequence token learning, networks of Noken implicit deep learning models with low Renyi α-entropy are sought, in order to sharpen semantic alignment between queries and keys.  Genetic algorithms, guided by evolutionary natural selection, are an efficient and systematic way to generate such Noken networks.
