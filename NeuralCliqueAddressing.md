# A computer science approach to memory and brain computations

New ideas / things to explore are in bold

## Ideas

- When coming out of dreams, a whole "RAM" module is swappet out - you forget almost everything you dream of except what you last thought about
  - You regain a base state of knowledge about the world
  - Could the swap between the two states be a swap of molecules inside the neurons: Neurons could be set to specific states / channels with a molecular make up instead of based on connections
- People closer to you are in different zones than people further to you
- Poeple who socialize more store people in a diferent zone that people who socialize less
- Need to find way to address items/people/concepts for many intellectual operations ("variable")
- Microcolumns: tons of groups of 120 neurons in the brain
- Multiple dimensions hashing / successive approximation : https://www.reddit.com/r/programming/comments/hd96p2/successive_approximation_hashes_in_high/
- Probably machine learning component to memory / autoencoding
- MongoDB wildcard indexing: it already can on specific collections index every field and then find the items by starting from which index most discriminates the item
  - Eg, I index milotic by "Pokemon / Water / Non-starter / Non-Firstgen / Evolution / Beautiful / very rare / snake / big", can find in the "Pokemon/Digimon collection with indexes on water / non - first gen / beautiful / very rare"
- Common language only uses 500 words - not that many concepts (2k?)
  - Link between mutliple languages and internal representation?
- Centralized / decentralized philospshy of large systems (bitcoin / internet / social groups / ...)

## Neural clique networks / Cycling through data

- Addressing based on core features
- **Possibility to cycle through data**
  - When searching based on characteristics, add specific characteristics. Eg "Poeple that... At xxx location"
  - Also add bloquers on charateristics: "People that... Not at xxx location"
  - Finally, ability to cycle through: "With characteristics... but not XXX. Get 2nd, third, fourth result"
  - Possibility to completely inhibit neurons not connected to first activated neurons (isn't that already done actually? - **NOT! - dig more**)
    - Implies no error correcting, but stronger addressing
    - Very fast stabilization!!
  - Instead of a fully evenly populated clique model, which starts to catastrophically fail when too much data is put in, think of cliques of different sizes?
    - Similarity to centralized / decentralized concept
    - Smaller cliques are stronger indexes
    - With the previous model of inihibitng everything not connected to the first data , it eliminates a lot of noise. Eg strongly connected nodes that aren't initially connected to anything won't create the noise they would
    - Conversely, strong nodes need to be chosen first. Finding a clique based only on weak nodes (large cliques) sucks because strong nodes not initially chosen will give a lot of noise
    - Error correcting can happen in larger cliques
    - Less connections needed: not as many connections between large cliques needed
    - More consistent with the k of n clusters instead of the k of k clusters / and with external addressing
    - Clusters can grow / reduce based on needs (but it doesn't fit)
    - Strong nodes can be categories / weak nodes special characteristics that discriminate
    - In general brainspace with tons of clusters, We can limit the clusters activated to reduce the scope - more research needed
  - Successful approx to enable / inhibit microcolumns
- Cliques don't have to be k of k, they can be k of n
- Indexing: each conceptual "item" still need to have an index that immediately refers to it. Those indexes can be used in cliques. For example index to refer to color blue can be used in addressing the sky

## Tooling

- Neural visualisation for simulations?
- Number of cycles