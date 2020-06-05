<html>
  <head>DASH</head>
  <title>DASH - Deter Agents Simulating Humans</title>
<body>

<h1>Deter Agents Simulating Humans</h1>
<p>
  DASH (Deter Agents Simulating Humans) as a research project from <a href="http://www.isi.edu">USC's Information Sciences Institute</a>
  focusing on building and understanding cognitive models of human behavior in order to better predict the value of security protocols, including cybersecurity.
  DASH agents are used in by FARM — an agent-based simulation framework implemented in Python that supports large-scale distributed simulations.
</p>


<h1>Contacts</h1>

<h2>Jim Blythe</h2>
<a href="https://www.isi.edu/~blythe/">Jim Blythe's ISI home page</a>


<h2>Alexey Tregubov</h2>
<a href="https://www.isi.edu/people/tregubov/alexey_tregubov">Alexey Tregubov's ISI home page</a>


<h1>Publications</h1>
<h2>Farm: Architecture for distributed agent-based social simulations</h2>
<p>
<h3>Conference: International Workshop on Massively Multiagent Systems </h3>
In many domains, high-resolution agent-based simulations
require experiments with a large number (tens or hundreds of millions) of
computationally complex agents. Such large-scale experiments are usu-
ally run for efficiency on high-performance computers or clusters, and
therefore agent-based simulation frameworks must support parallel dis-
tributed computations. The development of experiments with a large
number of interconnected agents and a shared environment running in
parallel on multiple compute nodes is especially challenging because it
introduces the overhead of cross-process communications.
In this paper we discuss the parallel distributed architecture of the farm
agent-based simulation framework for social network simulations. To ad-
dress the issue of shared environment synchronization we used a hybrid
approach that distributes the simulation environment across compute
nodes and keeps the shared portions of the environment synchronized
via centralized memory storage. To minimize cross-process communica-
tion overhead, we allocate agents to processes via a graph partitioning
algorithm that minimizes edge cuts in the communication graph, esti-
mated in our domain by empirical data of past agent activities. The
implementation of the toolkit used off the shelf components to support
centralized storage and messaging/notification services.
This architecture was used in a large-scale Github simulation with up to
ten million agents. In experiments in this domain, the graph partitioning
algorithm cut overall runtime by 67% on average.
  <br>
  <a href="https://scholar.google.com/scholar?oi=bibs&cluster=18364638581314166609&btnI=1&hl=en">Read paper</a>
</p>



<h2>Massive Cross-Platform Simulations of Online Social Networks</h2>
<p>
<h3>Conference: Proceedings of the 19th International Conference on Autonomous Agents and MultiAgent Systems</h3>
As part of the DARPA SocialSim challenge, we address the problem of predicting behavioral phenomena including information
spread involving hundreds of thousands of users across three major
linked social networks: Twitter, Reddit and GitHub. Our approach
develops a framework for data-driven agent simulation that begins
with a discrete-event simulation of the environment populated with
generic, flexible agents, then optimizes the decision model of the
agents by combining a number of machine learning classification
problems. The ML problems predict when an agent will take a certain action in its world and are designed to combine aspects of
the agents, gathered from historical data, with dynamic aspects
of the environment including the resources, such as tweets, that
agents interact with at a given point in time. In this way, each of the
agents makes individualized decisions based on their environment,
neighbors and history during the simulation, although global simulation data is used to learn accurate generalizations. This approach
showed the best performance of all participants in the DARPA challenge across a broad range of metrics. We describe the performance
of models both with and without machine learning on measures of
cross-platform information spread defined both at the level of the
whole population and at the community level. The best-performing
model overall combines learned agent behaviors with explicit modeling of bursts in global activity. Because of the general nature of
our approach, it is applicable to a range of prediction problems that
require modeling individualized, situational agent behavior from trace data that combines many agents.
  <br>
  <a href="http://ifaamas.org/Proceedings/aamas2020/pdfs/p895.pdf">Read paper</a>


</p>


<h2>Massive Multi-Agent Data-Driven Simulations of the GitHub Ecosystem</h2>
<p>
<h3>Conference: International Conference on Practical Applications of Agents and Multi-Agent Systems</h3>
Simulating and predicting planetary-scale techno-social sys-
tems poses heavy computational and modeling challenges. The DARPA
SocialSim program set the challenge to model the evolution of GitHub, a
large collaborative software-development ecosystem, using massive multi-
agent simulations. We here describe our best performing models and our
agent-based simulation framework, which we are currently extending to
allow simulating other planetary-scale techno-social systems. The chal-
lenge problem measured participant’s ability, given 30 months of meta-
data on user activity on GitHub, to predict the next months’ activity
as measured by a broad range of metrics applied to ground truth, using
agent-based simulation. The challenge required scaling to a simulation of
roughly 3 million agents producing a combined 30 million actions, acting
on 6 million repositories with commodity hardware. It was also impor-
tant to use the data optimally to predict the agent’s next moves. We
describe the agent framework and the data analysis employed by one of
the winning teams in the challenge. Six different agent models were tested
based on a variety of machine learning and statistical methods. While
no single method proved the most accurate on every metric, the broadly
most successful sampled from a stationary probability distribution of
actions and repositories for each agent.
  <br>
  <a href="https://arxiv.org/pdf/1908.05437">Read paper</a>


</p>


<h2>The DARPA SocialSim Challenge: Massive Multi-Agent Simulations of the Github Ecosystem</h2>
<p>
<h3>Conference: Proceedings of the 18th International Conference on Autonomous Agents and MultiAgent Systems</h3>
We model the evolution of GitHub, a large collaborative software-development ecosystem, using massive multi-agent
  simulations as a part of DARPA's SocialSim program. Our best performing models and our agent-based simulation
  framework are described here. Six different agent models were tested based on a variety of machine learning and
  statistical methods. The most successful models are based on sampling from a stationary probability distribution of
  actions and repositories for each agent.
  <br>
  <a href="https://dl.acm.org/ft_gateway.cfm?id=3331935&type=pdf">Read paper</a>


</p>


</body>
</html>
