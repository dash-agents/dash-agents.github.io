<html>
  <head>
    <style>
.abs {
    width: 100%;
    border-style: solid;
    padding-top: 10px;
    padding-right: 10px;
    padding-bottom: 10px;
    padding-left: 10px;
    display: none;
}

.title {
    font-weight: bold;
    font-size: 1.25em;
    padding-top: 1em;
    padding-bottom: 0.25em;
}

.conference {
    font-size: 1em;
    padding-bottom: 0.5em;
}

.authors {
    font-style: oblique;
}

</style>
  <title>DASH - Deter Agents Simulating Humans</title>
  </head>
<body>

<h1>Deter Agents Simulating Humans</h1>
<p>
  DASH (Deter Agents Simulating Humans) is a research project from <a href="http://www.isi.edu">USC's Information Sciences Institute</a>
  focusing on building and understanding cognitive models of human behavior in order to better predict the value of security protocols, including cybersecurity.
  DASH agents are used in by FARM — an agent-based simulation framework implemented in Python that supports large-scale distributed simulations.
</p>


<h1>Contacts</h1>

<h2>Jim Blythe</h2>
<a href="https://www.isi.edu/~blythe/">Jim Blythe's ISI home page</a>


<h2>Alexey Tregubov</h2>
<a href="https://www.isi.edu/people/tregubov/alexey_tregubov">Alexey Tregubov's ISI home page</a>


<h1>Publications</h1>
<script>
  function showAbstract(but, id) {
    var x = document.getElementById(id);
    if (x.style.display !== "block") {
	x.style.display = "block";
	but.innerHTML = "hide abstract";
    } else {
	x.style.display = "none";
	but.innerHTML = "show abstract";
    }
  }
</script>

<div class="title">Massive Cross-Platform Simulations of Online Social Networks</div>
<div class=authors>Goran Murić, Alexey Tregubov, Jim Blythe, Andrés Abeliuk, Divya Choudhary, Kristina Lerman,
Emilio Ferrara</div>
<div class=conference>Proceedings of the 19th International Conference on Autonomous Agents and MultiAgent Systems, AAMAS 2020</div>
<button onclick='showAbstract(this, "aamasAbs")'>show abstract</button>
<div class="abs" id="aamasAbs">
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
</div>
<a target="_blank" rel="noopener noreferrer" href="http://ifaamas.org/Proceedings/aamas2020/pdfs/p895.pdf">Read paper</a>


<div class=title>Massive Multi-Agent Data-Driven Simulations of the GitHub Ecosystem</div>
<div class=authors>Jim Blythe, John Bollenbacher, Di Huang, Pik-Mai Hui, Rachel Krohn,
Diogo Pacheco, Goran Muric, Anna Sapienza, Alexey Tregubov, Yong-Yeol
Ahn, Alessandro Flammini, Kristina Lerman, Filippo Menczer, Tim
Weninger, and Emilio Ferrara
</div>
<div class=conference>International Conference on Practical Applications of Agents and Multi-Agent Systems, PAAMS 2019</div>
<button onclick='showAbstract(this, "paamsAbs")'>show abstract</button>
<div class="abs" id="paamsAbs">
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
</div>
<a target="_blank" rel="noopener noreferrer" href="https://arxiv.org/pdf/1908.05437">Read paper</a>

<div class=title>The DARPA SocialSim Challenge: Massive Multi-Agent Simulations of the Github Ecosystem</div>
<div class=authors>James Blythe, Emilio Ferrara, Di Huang, Kristina Lerman, Goran Muric, Anna Sapienza,
Alexey Tregubov, Diogo Pacheco, John Bollenbacher, Alessandro Flammini, Pik-Mai Hui,
Filippo Menczer</div>
<div class=conference>Conference: Proceedings of the 18th International Conference on Autonomous Agents and MultiAgent Systems, AAMAS 2019</div>
<button onclick='showAbstract(this, "aamas19Abs")'>show abstract</button>
<div class="abs" id="aamas19Abs">
We model the evolution of GitHub, a large collaborative software-development ecosystem, using massive multi-agent
  simulations as a part of DARPA's SocialSim program. Our best performing models and our agent-based simulation
  framework are described here. Six different agent models were tested based on a variety of machine learning and
  statistical methods. The most successful models are based on sampling from a stationary probability distribution of
actions and repositories for each agent.
</div>
<a target="_blank" rel="noopener noreferrer" href="https://dl.acm.org/ft_gateway.cfm?id=3331935&type=pdf">Read paper</a>

<div class=title>Farm: Architecture for distributed agent-based social simulations</div>
<div class=authors>Jim Blythe and Alexey Tregubov</div>  
<div class=conference>IJCAI/AAMAS Workshop on Massively Multiagent Simulations, 2018</div>
<button onclick='showAbstract(this, "farmAbs")'>show abstract</button>
<div class="abs" id="farmAbs">
In many domains, high-resolution agent-based simulations
require experiments with a large number (tens or hundreds of millions) of
computationally complex agents. Such large-scale experiments are usually run for efficiency on high-performance computers or clusters, and
therefore agent-based simulation frameworks must support parallel distributed computations. The development of experiments with a large
number of interconnected agents and a shared environment running in
parallel on multiple compute nodes is especially challenging because it
introduces the overhead of cross-process communications.
In this paper we discuss the parallel distributed architecture of the farm
agent-based simulation framework for social network simulations. To address the issue of shared environment synchronization we used a hybrid
approach that distributes the simulation environment across compute
nodes and keeps the shared portions of the environment synchronized
via centralized memory storage. To minimize cross-process communication overhead, we allocate agents to processes via a graph partitioning
algorithm that minimizes edge cuts in the communication graph, estimated in our domain by empirical data of past agent activities. The
implementation of the toolkit used off the shelf components to support
centralized storage and messaging/notification services.
This architecture was used in a large-scale Github simulation with up to
ten million agents. In experiments in this domain, the graph partitioning
algorithm cut overall runtime by 67% on average.
</div>
<a target="_blank" rel="noopener noreferrer" href="https://scholar.google.com/scholar?oi=bibs&cluster=18364638581314166609&btnI=1&hl=en">Read paper</a>


<div class=title>Validating Agent-Based Modeling of Human Password Behavior</div>
<div class=authors>Korbar, Blythe, Koppel, Kothari and Smith</div>
<div class=conference>AAAI Workshop on Artificial Intelligence for Cyber Security, 2016</div>
<button onclick='showAbstract(this, "AICS16Abs")'>show abstract</button>
<div class="abs" id="AICS16Abs">
  Effective reasoning about the impact of security policy decisions requires understanding how human users actually behave, rather than assuming desirable but incorrect behavior. Simulation could help with this reasoning, but it requires building computational models of the relevant human behavior and validating that these models match what humans actually do. In this paper we describe our progress on building agent-based models of human behavior with passwords, and we demonstrate how these models reproduce phenomena shown in the empirical literature.
</div>
<a target="_blank" rel="noopener noreferrer" href="https://www.aaai.org/ocs/index.php/WS/AAAIW16/paper/view/12672/12360">Read paper</a>

<div class=title>Measuring the security impacts of password policies using cognitive behavioral agent-based modeling</div>
<div class=authors>Kothari, Blythe, Koppel and Smith</div>
<div class=conference>Symposium on the Science of Security, HotSOS 2015</div>
<button onclick='showAbstract(this, "hotsosAbs")'>show abstract</button>
<div class="abs" id="hotsosAbs">
Agent-based modeling can serve as a valuable asset to security personnel who wish to better understand the security landscape within their organization, especially as it relates to user behavior and circumvention. In this paper, we argue in favor of cognitive behavioral agent-based modeling for usable security, report on our work on developing an agent-based model for a password management scenario, perform a sensitivity analysis, which provides us with valuable insights into improving security (e.g., an organization that wishes to suppress one form of circumvention may want to endorse another), and provide directions for future work.
</div>
<a target="_blank" rel="noopener noreferrer" href="https://dl.acm.org/doi/10.1145/2746194.2746207">Read paper</a>


</body>
</html>
