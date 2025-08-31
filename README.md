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
