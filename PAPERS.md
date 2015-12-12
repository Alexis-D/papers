# Bitcoin: A Peer-to-Peer Electronic Cash System, 2008, [[pdf](https://bitcoin.org/bitcoin.pdf)]

_By Satoshi Nakamoto_

> A purely peer-to-peer version of electronic cash would allow online payments
> to be sent directly from one party to another without going through
> a financial institution. Digital signatures provide part of the solution,
> but the main benefits are lost if a trusted third party is still required to
> prevent double-spending. We propose a solution to the double-spending
> problem using a peer-to-peer network. The network timestamps transactions by
> hashing them into an ongoing chain of hash-based proof-of-work, forming
> a record that cannot be changed without redoing the proof-of-work. The
> longest chain not only serves as proof of the sequence of events witnessed,
> but proof that it came from the largest pool of CPU power. As long as
> a majority of CPU power is controlled by nodes that are not cooperating to
> attack the network, they'll generate the longest chain and outpace
> attackers. The network itself requires minimal structure. Messages are
> broadcast on a best effort basis, and nodes can leave and rejoin the network
> at will, accepting the longest proof-of-work chain as proof of what happened
> while they were gone.

# Chord: A Scalable Peer-to-peer Lookup Service for Internet Applications, 2001, [[pdf](http://pdos.csail.mit.edu/papers/chord:sigcomm01/chord_sigcomm.pdf)]

_By Ion Stoica, Robert Morris, David Karger, M. Frans Kaashoek & Hari Balakrishnan_

> A fundamental problem that confronts peer-to-peer applications is to
> efficiently locate the node that stores a particular data item. This paper
> presents Chord, a distributed lookup protocol that addresses this problem.
> Chord provides support for just one operation: given a key, it maps the key
> onto a node. Data location can be easily implemented on top of Chord by
> associating a key with each data item, and storing the key/data item pair at
> the node to which the key maps. Chord adapts efficiently as nodes join and
> leave the system, and can answer queries even if the system is continuously
> changing. Results from theoretical analysis, simulations, and experiments
> show that Chord is scalable, with communication cost and the state
> maintained by each node scaling logarithmically with the number of Chord
> nodes.

# Differential evolution–a simple and efficient heuristic for global optimization over continuous spaces, 1997, [[pdf](https://bitbucket.org/12er/pso/src/b448ff0db375c1ac0c55855e9f19aced08b44ca6/doc/literature/heuristic%20Search/Differential%20Evolution%20-%20a%20simple%20and%20efficient%20heuristic%20for%20global%20optimization%20over%20continuous%20spaces.pdf)]

_By Rainer Storn & Kenneth Price_

> A new heuristic approach for minimizing possibly nonlinear and
> non-differentiable continuous space functions is presented. By means of an
> extensive testbed it is demonstrated that the new method converges faster
> and with more certainty than many other acclaimed global optimization
> methods. The new method requires few control variables, is robust, easy to
> use, and lends itself very well to parallel computation.

# Dynamo: Amazon’s Highly Available Key-value Store, 2007, [[pdf](http://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf)]

_By Giuseppe DeCandia, Deniz Hastorun, Madan Jampani, Gunavardhan Kakulapati, Avinash Lakshman, Alex Pilchin, Swaminathan Sivasubramanian, Peter Vosshall & Werner Vogels_

> Reliability at massive scale is one of the biggest challenges we face at
> Amazon.com, one of the largest e-commerce operations in the world; even the
> slightest outage has significant financial consequences and impacts customer
> trust. The Amazon.com platform, which provides services for many web sites
> worldwide, is implemented on top of an infrastructure of tens of thousands
> of servers and network components located in many datacenters around the
> world. At this scale, small and large components fail continuously and the
> way persistent state is managed in the face of these failures drives the
> reliability and scalability of the software systems.
>
> This paper presents the design and implementation of Dynamo, a highly
> available key-value storage system that some of Amazon’s core services use
> to provide an “always-on” experience. To achieve this level of availability,
> Dynamo sacrifices consistency under certain failure scenarios. It makes
> extensive use of object versioning and application-assisted conflict
> resolution in a manner that provides a novel interface for developers to
> use.

# Evolving Neural Networks Through Augmenting Topologies, 2002, [[pdf](http://nn.cs.utexas.edu/downloads/papers/stanley.ec02.pdf)]

_By Kenneth O. Stanley Stanley & Risto Miikkulainen_

> An important question in neuroevolution is how to gain an advantage from
> evolving neural network topologies along with weights. We present a method,
> NeuroEvolution of Augmenting Topologies (NEAT) that outperforms the best
> fixed-topology method on a challenging benchmark reinforcement learning
> task. We claim that the increased efficiency is due to (1) employing
> a principled method of crossover of different topologies, (2) protecting
> structural innovation using speciation, and (3) incrementally growing from
> minimal structure. We test this claim through a series of ablation studies
> that demonstrate that each component is necessary to the system as a whole
> and to each other. What results is significantly faster learning. NEAT is
> also an important contribution to GAs because it shows how it is possible
> for evolution to both optimize and complexify solutions simultaneously,
> offering the possibility of evolving increasingly complex solutions over
> generations, and strengthening the analogy with biological evolution. 

# Git from the bottom up, 2009, [[pdf](http://ftp.newartisans.com/pub/git.from.bottom.up.pdf)]

_By John Wiegley_

> In my pursuit to understand Git, it's been helpful for me to understand it
> from the bottom up -- rather than look at it only in terms of its high-level
> commands. And since Git is so beautifully simple when viewed this way,
> I thought others might be interested to read what I've found, and perhaps
> avoid the pain I went through finding it.

# HyperLogLog: the analysis of a near-optimal cardinality estimation algorithm, 2007, [[pdf](http://algo.inria.fr/flajolet/Publications/FlFuGaMe07.pdf)]

_By Philippe Flajolet,  Éric Fusy, Olivier Gandouet & Frédéric Meunier_

> An on-line algorithm for computing approximations of rank-based statistics
> is presented that allows controllable accuracy. Moreover, this new algorithm
> can be used to compute hybrid statistics such as trimmed means in additional
> to computing arbitrary quantiles. An unusual property of the method is that
> it allows a quantile q to be computed with an accuracy relative to q(1 − q)
> rather than with an absolute accuracy as with most methods. This new
> algorithm is robust with respect to highly skewed distributions or highly
> ordered datasets and allows separately computed summaries to be combined
> with no loss in accuracy.

# In Search of an Understandable Consensus Algorithm, 2014, [[pdf](https://ramcloud.stanford.edu/wiki/download/attachments/11370504/raft.pdf)]

_By Diego Ongaro & John Ousterhout_

> Raft is a consensus algorithm for managing a replicated log. It produces
> a result equivalent to (multi-)Paxos, and it is as efficient as Paxos, but
> its structure is different from Paxos; this makes Raft more understandable
> than Paxos and also provides a better foundation for building practical
> systems. In order to enhance understandability, Raft separates the key
> elements of consensus, such as leader election, log replication, and safety,
> and it enforces a stronger degree of coherency to reduce the number of
> states that must be considered. Results from a user study demonstrate that
> Raft is easier for students to learn than Paxos. Raft also includes a new
> mechanism for changing the cluster membership, which uses overlapping
> majorities to guarantee safety.

# MapReduce: Simplified Data Processing on Large Clusters, 2004, [[pdf](http://research.google.com/archive/mapreduce-osdi04.pdf)]

_By Jeffrey Dean & Sanjay Ghemawat_

> MapReduce is a programming model and an associated implementation for
> processing and generating large data sets. Users specify a map function that
> processes a key/value pair to generate a set of intermediate key/value
> pairs, and a reduce function that merges all intermediate values associated
> with the same intermediate key. Many real world tasks are expressible in
> this model, as shown in the paper.
>
> Programs written in this functional style are automatically parallelized and
> executed on a large cluster of commodity machines. The run-time system takes
> care of the details of partitioning the input data, scheduling the program's
> execution across a set of machines, handling machine failures, and managing
> the required inter-machine communication. This allows programmers without
> any experience with parallel and distributed systems to easily utilize the
> resources of a large distributed system.
>
> Our implementation of MapReduce runs on a large cluster of commodity
> machines and is highly scalable: a typical MapReduce computation processes
> many terabytes of data on thousands of machines. Programmers find the system
> easy to use: hundreds of MapReduce programs have been implemented and
> upwards of one thousand MapReduce jobs are executed on Google's clusters
> every day. 

# On Designing and Deploying Internet-Scale Services, 2007, [[pdf](https://www.usenix.org/legacy/event/lisa07/tech/full_papers/hamilton/hamilton.pdf)]

_By James Hamilton_

> The system-to-administrator ratio is commonly used as a rough metric to
> understand administrative costs in high-scale services. With smaller, less
> automated services this ratio can be as low as 2:1, whereas on industry
> leading, highly automated services, we've seen ratios as high as 2,500:1.
> Within Microsoft services, Autopilot [1] is often cited as the magic behind
> the success of the Windows Live Search team in achieving high
> system-to-administrator ratios. While auto-administration is important, the
> most important factor is actually the service itself. Is the service
> efficient to automate? Is it what we refer to more generally as
> operations-friendly? Services that are operations-friendly require little
> human intervention, and both detect and recover from all but the most
> obscure failures without administrative intervention. This paper summarizes
> the best practices accumulated over many years in scaling some of the
> largest services at MSN and Windows Live.

# Resilient Distributed Datasets: A Fault-Tolerant Abstraction for In-Memory Cluster Computing, 2012, [[pdf](http://www.cs.berkeley.edu/~matei/papers/2012/nsdi_spark.pdf)]

_By Matei Zaharia, Mosharaf Chowdhury, Tathagata Das, Ankur Dave, Justin Ma, Murphy McCauley, Michael J. Franklin, Scott Shenker & Ion Stoica_

> We present Resilient Distributed Datasets (RDDs), a distributed memory
> abstraction that lets programmers perform in-memory computations on large
> clusters in a fault-tolerant manner. RDDs are motivated by two types of
> applications that current computing frameworks handle inefficiently:
> iterative algorithms and interactive data mining tools. In both cases,
> keeping data in memory can improve performance by an order of magnitude. To
> achieve fault tolerance efficiently, RDDs provide a restricted form of
> shared memory, based on coarse-grained transformations rather than
> fine-grained updates to shared state. However, we show that RDDs are
> expressive enough to capture a wide class of computations, including recent
> specialized programming models for iterative jobs, such as Pregel, and new
> applications that these models do not capture. We have implemented RDDs in
> a system called Spark, which we evaluate through a variety of user
> applications and benchmarks.

# The Anatomy of a Large-Scale Hypertextual Web Search Engine, 1998, [[pdf](http://ilpubs.stanford.edu:8090/361/1/1998-8.pdf)]

_By Sergey Brin & Lawrence Page_

> In this paper, we present Google, a prototype of a large-scale search engine
> which makes heavy use of the structure present in hypertext. Google is
> designed to crawl and index the Web efficiently and produce much more
> satisfying search results than existing systems. The prototype with a full
> text and hyperlink database of at least 24 million pages is available at
> http://google.stanford.edu/
>
> To engineer a search engine is a challenging task. Search engines index tens
> to hundreds of millions of web pages involving a comparable number of
> distinct terms. They answer tens of millions of queries every day. Despite
> the importance of large-scale search engines on the web, very little
> academic research has been done on them. Furthermore, due to rapid advance
> in technology and web proliferation, creating a web search engine today is
> very different from three years ago. This paper provides an in-depth
> description of our large-scale web search engine -- the first such detailed
> public description we know of to date.
>
> Apart from the problems of scaling traditional search techniques to data of
> this magnitude, there are new technical challenges involved with using the
> additional information present in hypertext to produce better search
> results. This paper addresses this question of how to build a practical
> large-scale system which can exploit the additional information present in
> hypertext. Also we look at the problem of how to effectively deal with
> uncontrolled hypertext collections where anyone can publish anything they
> want. 

# The Google File System, 2003, [[pdf](http://research.google.com/archive/gfs-sosp2003.pdf)]

_By Sanjay Ghemawat, Howard Gobioff & Shun-Tak Leung_

> We have designed and implemented the Google File System, a scalable
> distributed file system for large distributed data-intensive applications.
> It provides fault tolerance while running on inexpensive commodity hardware,
> and it delivers high aggregate performance to a large number of clients.
>
> While sharing many of the same goals as previous distributed file systems,
> our design has been driven by observations of our application workloads and
> technological environment, both current and anticipated, that reflect
> a marked departure from some earlier file system assumptions. This has led
> us to reexamine traditional choices and explore radically different design
> points.
>
> The file system has successfully met our storage needs. It is widely
> deployed within Google as the storage platform for the generation and
> processing of data used by our service as well as research and development
> efforts that require large data sets. The largest cluster to date provides
> hundreds of terabytes of storage across thousands of disks on over
> a thousand machines, and it is concurrently accessed by hundreds of clients.
>
> In this paper, we present file system interface extensions designed to
> support distributed applications, discuss many aspects of our design, and
> report measurements from both micro-benchmarks and real world use. 

# Tor: The Second-Generation Onion Router, 2004, [[pdf](https://svn.torproject.org/svn/projects/design-paper/tor-design.pdf)]

_By Roger Dingledine, Nick Mathewson & Paul Syverson_

> We present Tor, a circuit-based low-latency anonymous communication service.
> This second-generation Onion Routing system addresses limitations in the
> original design by adding perfect forward secrecy, congestion control,
> directory servers, integrity checking, configurable exit policies, and
> a practical design for location-hidden services via rendezvous points. Tor
> works on the real-world Internet, requires no special privileges or kernel
> modifications, requires little synchronization or coordination between
> nodes, and provides a reasonable tradeoff between anonymity, usability, and
> efficiency. We briefly describe our experiences with an international
> network of more than 30 nodes. We close with a list of open problems in
> anonymous communication.
