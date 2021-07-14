# Reading List 



:fire: :collision: :anger: :exclamation: :cyclone: :ocean: :sweat_drops: :droplet: :turtle: :frog: :snake: :bug: :ram: :sheep: :rabbit2: :goat: :whale: :whale2: :fish: :dolphin: :rose: :maple_leaf: :fallen_leaf: :mushroom: :beer: :beers: :airplane: :fountain: :bullettrain_front: :rocket: :rowboat: :speedboat: 

:ear_of_rice: :pager: :page_facing_up: :page_with_curl: :book: :blue_book: :bookmark: :bookmark_tabs: :books: :clipboard: :bar_chart: :chart_with_downwards_trend: :chart_with_upwards_trend: :card_file_box: :card_index: :card_index_dividers: :flower_playing_cards: :newspaper: :newspaper_roll: :closed_book: :orange_book: :notebook: :notebook_with_decorative_cover: :ledger: :spiral_notepad: :green_book: :scroll: :pushpin: :fountain_pen: :pen: :pencil2: :santa: 



unsupervised/self-supservised; <a href="#anchor-emp">Emp</a>. ; <a href="#anchor-asp">(A)SP</a>; <a href="#anchor-metarl">meta-RL</a>; <a href="#anchor-HRL">HRL</a>; <a href="#anchor-comskills">combing skills</a>; <a href="#anchor-klreg">KL reg</a>.; <a href="#anchor-inference">inference</a>; <a href="#anchor-state-abstraction">State abstraction</a>; <a href="#anchor-MI">MI</a>; <a href="#anchor-cl">CL</a>; <a href="#anchor-disrl">Dis RL</a>; <a href="#anchor-DR">DR</a>; <a href="#anchor-sim2real">sim2real</a>; <a href="#anchor-transfer">transfer</a>(DA, DG, dynamics); <a href="#anchor-causual">causual</a>; <a href="#anchor-exploration">exploration</a>; <a href="#anchor-offline">offline</a>; <a href="#anchor-pareto">Pareto</a>; <a href="#anchor-supervised">supervised</a>; <a href="#anchor-goalcon">Goal con</a>; <a href="#anchor-irl">IRL</a>; <a href="#anchor-selfpaced">self-paced</a>; <a href="#anchor-curriculum">Curriculum</a>; <a href="#anchor-modelbasedrl">model-based</a>;  <a href="#anchor-trainingrl">training RL</a>; <a href="#anchor-marl">MARL</a>;  <a href="#anchor-constrainedrl">constrained RL</a>; <a href="#anchor-optimization">optimization</a>(CD, DRO, Trustworthy); 



<a name="anchor-emp"></a>  

### Emp. & ASP 

:partly_sunny: :full_moon: :shell: :seedling: :evergreen_tree: :mushroom: :leaves: :sunflower: :cactus: :bouquet: :herb: :palm_tree: :four_leaf_clover: :deciduous_tree: :rose: :chestnut: :bamboo: :ear_of_rice: :palm_tree: :maple_leaf: :paw_prints: :new_moon: :first_quarter_moon: :waning_gibbous_moon: :waning_crescent_moon: :full_moon: :milky_way: :globe_with_meridians: :earth_americas: :volcano: :jack_o_lantern: 

+ Empowerment — An Introduction https://arxiv.org/pdf/1310.1863.pdf :+1: 

+ Keep your options open: An information-based driving principle for sensorimotor systems  

  - It measures the capacity of the agent to influence the world in a way that this influence is perceivable via the agent’s sensors. 
  - Concretely, we define empowerment as the maximum amount of information that an agent could send from its actuators to its sensors via the environment, reducing in the simplest case to the external information channel capacity of the channel from the actuators to the sensors of the agent. 

  - An individual agent or an agent population can attempt and explore only a small fraction of possible behaviors during its lifetime. 

  - universal & local 

+ What is intrinsic motivation? A typology of computational approaches

+ [Variational Information Maximisation for Intrinsically Motivated Reinforcement Learning [2015] ](https://arxiv.org/abs/1509.08731)  :+1:  ​

  We focussed specifically on intrinsic motivation with a reward measure known as empowerment, which requires at its core the efficient computation of the mutual information. 

+ 强化学习如何使用内在动机 

  + Social Influence as Intrinsic Motivation for Multi-Agent Deep Reinforcement Learning 

+ A survey on intrinsic motivation in reinforcement learning https://arxiv.org/abs/1908.06976 :milky_way: :fist_oncoming: :fist_oncoming: :fire: :fire: :sweat_drops: :droplet: :droplet: 

+ Efficient Exploration via State Marginal Matching https://arxiv.org/pdf/1906.05274.pdf :volcano: 

+ Empowerment: A Universal Agent-Centric Measure of Control https://uhra.herts.ac.uk/bitstream/handle/2299/1114/901241.pdf?sequence=1&isAllowed=y 

+ SMiRL: Surprise Minimizing Reinforcement Learning in Dynamic Environments https://openreview.net/pdf?id=cPZOyoDloxl  :fire: :boom: :volcano: :boom: :fire: :droplet: 

  In the real world, natural forces and other agents already **offer unending novelty**. The second law of thermodynamics stipulates **ever-increasing entropy**, and therefore perpetual novelty, without even requiring any active intervention. 

  :curly_loop: [Unsupervised Skill Discovery with Bottleneck Option Learning](https://arxiv.org/pdf/2106.14305.pdf) :+1: :fire:  

  On top of the linearization of environments that promotes more various and distant state transitions, IBOL enables the discovery of diverse skills. 

  :curly_loop: [Paired Open-Ended Trailblazer (POET): Endlessly Generating Increasingly Complex and Diverse Learning Environments and Their Solutions](https://arxiv.org/pdf/1901.01753.pdf)  ​​ [Enhanced POET: Open-Ended Reinforcement Learning through Unbounded Invention of Learning Challenges and their Solutions](https://arxiv.org/pdf/2003.08536.pdf) :no_mouth:  ​
  
  :curly_loop: [The Viable System Model - Stafford Beer](https://www.businessballs.com/strategy-innovation/viable-system-model-stafford-beer/)  
  
  :curly_loop: [Reinforcement Learning Generalization with Surprise Minimization](https://arxiv.org/pdf/2004.12399.pdf) :no_mouth:  ​
  
  :curly_loop: [TERRAIN RL SIMULATOR](https://arxiv.org/pdf/1804.06424.pdf)   [Github](https://github.com/UBCMOCCA/TerrainRLSim)   



<a name="anchor-asp"></a>  

+ ASP: ASYMMETRIC SELF-PLAY 

  :curly_loop: INTRINSIC MOTIVATION AND AUTOMATIC CURRICULA VIA ASYMMETRIC SELF-PLAY https://arxiv.org/pdf/1703.05407.pdf [起飞 ASP] :fire: :fire: :+1: 

  :curly_loop: [Keeping Your Distance: Solving Sparse Reward Tasks Using Self-Balancing Shaped Rewards](https://papers.nips.cc/paper/9225-keeping-your-distance-solving-sparse-reward-tasks-using-self-balancing-shaped-rewards.pdf) [ASP] :fire: :volcano: :+1: 

  Our method introduces an auxiliary distance-based reward based on pairs of rollouts to encourage diverse exploration. This approach effectively prevents learning dynamics from stabilizing around local optima induced by the naive distance-to-goal reward shaping and enables policies to efficiently solve sparse reward tasks. 

  :curly_loop: [Mastering Chess and Shogi by Self-Play with a General Reinforcement Learning Algorithm](https://arxiv.org/pdf/1712.01815.pdf)  :droplet: 

  :curly_loop: [Learning Goal Embeddings via Self-Play for Hierarchical Reinforcement Learning](https://arxiv.org/pdf/1811.09083.pdf) [ASP] :fire: :+1: 

  :curly_loop: [Generating Automatic Curricula via Self-Supervised Active Domain Randomization](https://arxiv.org/pdf/2002.07911.pdf) [ASP] 

  :curly_loop:[ASYMMETRIC SELF-PLAY FOR AUTOMATIC GOAL DISCOVERY IN ROBOTIC MANIPULATION](https://openreview.net/pdf?id=hu2aMLzOxC) :no_mouth:  [ASP] 

  :curly_loop: [Language as a Cognitive Tool to Imagine Goals in Curiosity-Driven Exploration](https://arxiv.org/pdf/2002.09253.pdf) :fire: :boom:  ​ ​
  
  We introduce IMAGINE, an intrinsically motivated deep reinforcement learning architecture that models this ability. Such imaginative agents, like children, benefit from the guidance of a social peer who provides language descriptions. To take advantage of goal imagination, agents must be able to leverage these descriptions to interpret their imagined out-of-distribution goals. 
  
  



<a name="anchor-metarl"></a>  

### Meta-RL 

 :frog: :tiger: :snail: :snake: :camel: :tiger: :turtle: :bird: :ant: :koala: :dog: :beetle: :chicken: :rat: :ox: :cow2: :whale: :fish: :dolphin: :whale2: :cat2: :blowfish: :dragon: :dragon_face: :goat: :octopus: :ant: :turtle: :crocodile: :baby_chick: 

+ A Meta-Transfer Objective for Learning to Disentangle Causal Mechanisms 2020  https://arxiv.org/pdf/1901.10912.pdf Yoshua Bengio :milky_way: :fire: :fire: :+1: :maple_leaf: :sweat_drops:  [contrative loss on causal mechanisms?] 

  We show that under this assumption, the correct causal structural choices lead to faster adaptation to modified distributions because the changes are concentrated in one or just a few mechanisms when the learned knowledge is modularized appropriately. 

+ Causal Reasoning from Meta-reinforcement Learning 2019 :wink: :no_mouth: 

+ Discovering Reinforcement Learning Algorithms https://arxiv.org/pdf/2007.08794.pdf :+1: 

  This paper introduces a new meta-learning approach that discovers an entire update rule which includes both ‘**what to predict**’ (e.g. value functions) and ‘**how to learn from it**’ (e.g. bootstrapping) by interacting with a set of environments. 

+ Zhongwen Xu (DeepMind) 

  :curly_loop: [Discovering Reinforcement Learning Algorithms](https://arxiv.org/pdf/2007.08794.pdf)   Attempte to discover the full update rule :+1: ​

  :curly_loop: [What Can Learned Intrinsic Rewards Capture?](https://arxiv.org/pdf/1912.05500.pdf)   How/What value function/policy network :+1:  

  ​	lifetime return:A finite sequence of agent-environment interactions until the end of training defined by an agentdesigner, which can consist of multiple episodes. 

  :curly_loop: [Discovery of Useful Questions as Auxiliary Tasks](http://papers.nips.cc/paper/9129-discovery-of-useful-questions-as-auxiliary-tasks.pdf) :confused: 

  ​	Related work is good! (Prior work on auxiliary tasks in RL + GVF) :fire:  :+1:    

  :curly_loop: [Meta-Gradient Reinforcement Learning](http://papers.nips.cc/paper/7507-meta-gradient-reinforcement-learning.pdf)  discount factor + bootstrapped factor :sweat_drops:  ​

  

+ Unsupervised Meta-Learning for Reinforcement Learning https://arxiv.org/pdf/1806.04640.pdf [Abhishek Gupta, Benjamin Eysenbach, Chelsea Finn, Sergey Levine] :confused: :wink: 

  Meta-RL shifts the human burden from algorithm to task design. In contrast, our work deals with the RL setting, where the environment dynamics provides a rich inductive bias that our meta-learner can exploit. 

  :curly_loop: [UNSUPERVISED LEARNING VIA META-LEARNING](https://arxiv.org/pdf/1810.02334.pdf)  :wink:  ​We construct tasks from unlabeled data in an automatic way and run meta-learning over the constructed tasks. 

  :curly_loop: [Unsupervised Curricula for Visual Meta-Reinforcement Learning](https://arxiv.org/pdf/1912.04226.pdf)  [Allan Jabriα; Kyle Hsu] :+1: :droplet: :volcano: :fire: 

  Yet, the aforementioned relation between skill acquisition and meta-learning suggests that they should not be treated separately. 

  However, relying solely on discriminability becomes problematic in environments with high-dimensional (image-based) observation spaces as it **results in an issue akin to mode-collapse in the task space**. This problem is further complicated in the setting we propose to study, wherein the policy data distribution is that of a meta-learner rather than a contextual policy. We will see that this can be ameliorated by specifying **a hybrid discriminative-generative model** for parameterizing the task distribution. 

  We, rather, will **tolerate lossy representations** as long as they capture discriminative features useful for stimulus-reward association.  

+ Asymmetric Distribution Measure for Few-shot Learning https://arxiv.org/pdf/2002.00153.pdf :+1: 

  feature representations and relation measure. 

+ latent models 

  :curly_loop: [MELD: Meta-Reinforcement Learning from Images via Latent State Models](https://arxiv.org/pdf/2010.13957.pdf) :+1: :+1:  ​ ​

  we leverage the perspective of meta-learning as task inference to show that latent state models can also perform meta-learning given an appropriately defined observation space. 

  :curly_loop: [Explore then Execute: Adapting without Rewards via Factorized Meta-Reinforcement Learning](https://arxiv.org/pdf/2008.02790.pdf) :+1: :+1: 

  based on identifying key information in the environment, independent of how this information will exactly be used solve the task. By decoupling exploration from task execution, DREAM explores and consequently adapts to new environments, requiring no reward signal when the task is specified via an instruction.  

+ model identification and experience relabeling (MIER) 

  :curly_loop: [Meta-Reinforcement Learning Robust to Distributional Shift via Model Identification and Experience Relabeling](https://arxiv.org/pdf/2006.07178.pdf) :+1: :fire:  ​ ​

  Our method is based on a simple insight: we recognize that dynamics models can be adapted efficiently and consistently with off-policy data, more easily than policies and value functions. These dynamics models can then be used to continue training policies and value functions for out-of-distribution tasks without using meta-reinforcement learning at all, by generating synthetic experience for the new task. 



<a name="anchor-HRL"></a>  

### HRL 

+ SUB-POLICY ADAPTATION FOR HIERARCHICAL REINFORCEMENT LEARNING https://arxiv.org/pdf/1906.05862.pdf :-1:  

  :curly_loop: [STOCHASTIC NEURAL NETWORKS FOR HIERARCHICAL REINFORCEMENT LEARNING](https://arxiv.org/pdf/1704.03012.pdf)  

+ HIERARCHICAL RL USING AN ENSEMBLE OF PROPRIOCEPTIVE PERIODIC POLICIES https://openreview.net/pdf?id=SJz1x20cFQ :-1: 

+ LEARNING TEMPORAL ABSTRACTION WITH INFORMATION-THEORETIC CONSTRAINTS FOR HIERARCHICAL REINFORCEMENT LEARNING https://openreview.net/pdf?id=HkeUDCNFPS :fire: :+1: 

  we maximize the mutual information between the latent variables and the state changes. 
  
+ learning representation 

  :curly_loop: [LEARNING SUBGOAL REPRESENTATIONS WITH SLOW DYNAMICS](https://openreview.net/pdf?id=wxRwhSdORKG) :+1: :droplet: :fire: ​​  ​ ​

  Observing that the high-level agent operates at an abstract temporal scale, we propose a slowness objective to effectively learn the subgoal representation (i.e., the high-level action space). We provide a theoretical grounding for the slowness objective. 

   ​ ​




### CITING D... 

+ Latent Space Policies for Hierarchical Reinforcement Learning 2018 https://arxiv.org/pdf/1804.02808.pdf  

+ 

+ EPISODIC CURIOSITY THROUGH REACHABILITY [reward design] 

  In particular, inspired by curious behaviour in animals, observing something novel could be rewarded with a bonus. Such bonus is summed up with the real task reward — making it possible for RL algorithms to learn from the combined reward. We propose a new curiosity method which uses episodic memory to form the novelty bonus. :droplet: **To determine the bonus, the current observation is compared with the observations in memory.** Crucially, the comparison is done based on how many environment steps it takes to reach the current observation from those in memory — which incorporates rich information about environment dynamics. This allows us to overcome the known “couch-potato” issues of prior work — when the agent finds a way to instantly gratify itself by exploiting actions which lead to hardly predictable consequences. 



<a name="anchor-comskills"></a>   <a name="anchor-klreg"></a>  

+ Combing Skills & **KL regularized expected reward objective** 

  :curly_loop: [INFOBOT: TRANSFER AND EXPLORATION VIA THE INFORMATION BOTTLENECK](https://arxiv.org/pdf/1901.10902.pdf) :fire: :boom:  ​ ​

  By training a goal-conditioned policy with an information bottleneck, we can identify decision states by examining where the model actually leverages the goal state. 

  :curly_loop: [THE VARIATIONAL BANDWIDTH BOTTLENECK: STOCHASTIC EVALUATION ON AN INFORMATION BUDGET](https://arxiv.org/pdf/2004.11935.pdf) :fire: :boom: :volcano:  

  we propose the variational bandwidth bottleneck, which decides for each example on the estimated value of the privileged information before seeing it, i.e., only based on the standard input, and then accordingly chooses stochastically, whether to access the privileged input or not. 

  :curly_loop: [the option keyboard Combing Skills in Reinforcement Learning](https://papers.nips.cc/paper/9463-the-option-keyboard-combining-skills-in-reinforcement-learning.pdf)  

  We argue that a more robust way of combining skills is to do so directly in **the goal space**, using pseudo-rewards or cumulants. If we associate each skill with a cumulant, we can combine the former by manipulating the latter. This allows us to go beyond the direct prescription of behaviors, working instead in the space of intentions. :confused: 

  Others: 1. in the space of policies -- over actions; 2. manipulating the corresponding parameters. 

  :curly_loop: [Scaling simulation-to-real transfer by learning composable robot skills](https://arxiv.org/pdf/1809.10253.pdf) :fire: :+1: :boom: 

  we first use simulation to jointly learn a policy for a set of low-level skills, and a **“skill embedding”** parameterization which can be used to compose them. 

  :curly_loop: [LEARNING AN EMBEDDING SPACE FOR TRANSFERABLE ROBOT SKILLS](https://openreview.net/pdf?id=rk07ZXZRb) :fire: :+1: :boom:  ​

  our method is able to learn the skill embedding distributions, which enables interpolation between different skills as well as discovering the number of distinct skills necessary to accomplish a set of tasks. 

  :curly_loop: [CoMic: Complementary Task Learning & Mimicry for Reusable Skills](https://proceedings.icml.cc/static/paper_files/icml/2020/5013-Paper.pdf) :fire: :boom:  ​ ​

   We study the problem of learning reusable humanoid skills by imitating motion capture data and joint training with complementary tasks. **Related work is good!** 

  :curly_loop: [Learning to combine primitive skills: A step towards versatile robotic manipulation](https://arxiv.org/pdf/1908.00722.pdf) :+1:  ​

  RL(high-level) + IM (low-level) 

  :curly_loop: [COMPOSABLE SEMI-PARAMETRIC MODELLING FOR LONG-RANGE MOTION GENERATION](https://openreview.net/pdf?id=rkl44TEtwH) :+1:  ​

  Our proposed method learns to model the motion of human by combining the complementary strengths of both non-parametric techniques and parametric ones. Good EXPERIMENTS! 

  :curly_loop: [LEARNING TO COORDINATE MANIPULATION SKILLS VIA SKILL BEHAVIOR DIVERSIFICATION](https://openreview.net/pdf?id=ryxB2lBtvH) :fire: :+1:  ​ ​

  Our method consists of two parts: (1) acquiring primitive skills with diverse behaviors by mutual information maximization, and (2) learning a meta policy that selects a skill for each end-effector and coordinates the chosen skills by controlling the behavior of each skill. **Related work is good!** 

  :curly_loop: [Information asymmetry in KL-regularized RL](https://arxiv.org/pdf/1905.01240.pdf) :fire: :boom: :+1:  ​ ​ ​

  In this work we study the possibility of leveraging such repeated structure to speed up and regularize learning. We start from the **KL regularized expected reward objective** which introduces an additional component, a default policy. Instead of relying on a fixed default policy, we learn it from data. But crucially, we **restrict the amount of information the default policy receives**, forcing it to learn reusable behaviours that help the policy learn faster. 

  :curly_loop: [Exploiting Hierarchy for Learning and Transfer in KL-regularized RL](https://arxiv.org/pdf/1903.07438.pdf) :+1: :boom: :fire: :droplet:   

  The KL-regularized expected reward objective constitutes a convenient tool to this end. It introduces an additional component, a default or prior behavior, which can be learned alongside the policy and as such partially transforms the reinforcement learning problem into one of behavior modelling. **In this work we consider the implications of this framework in case where both the policy and default behavior are augmented with latent variables.** We discuss how the resulting hierarchical structures can be exploited to implement different inductive biases and how the resulting modular structures can be exploited for transfer. Good Writing / Related-work!  :+1:  

  :curly_loop: [CompILE: Compositional Imitation Learning and Execution](http://proceedings.mlr.press/v97/kipf19a/kipf19a.pdf) :no_mouth:  ​

  CompILE can successfully discover sub-tasks and their boundaries in an imitation learning setting. 

  :curly_loop: [Strategic Attentive Writer for Learning Macro-Actions](http://papers.nips.cc/paper/6414-strategic-attentive-writer-for-learning-macro-actions.pdf) :no_mouth:  ​

  :curly_loop:[Synthesizing Programs for Images using Reinforced Adversarial Learning](https://arxiv.org/pdf/1804.01118.pdf) :no_mouth: RL render RENDERS  ​

  :curly_loop: [Neural Task Graphs: Generalizing to Unseen Tasks from a Single Video Demonstration](https://arxiv.org/pdf/1807.03480.pdf) :fire: :+1:  ​ ​

   The NTG networks consist of a generator that produces the conjugate task graph as the intermediate representation, and an execution engine that executes the graph by localizing node and deciding the edge transition in the task graph based on the current visual observation. 

  :curly_loop: [Reinforcement Learning with Competitive Ensembles of Information-Constrained Primitives](https://openreview.net/pdf?id=ryxgJTEYDr) :fire: :volcano:  

  each primitive chooses how much information it needs about the current state to make a decision and the primitive that requests the most information about the current state acts in the world. 

  :curly_loop: [COMPOSING TASK-AGNOSTIC POLICIES WITH DEEP REINFORCEMENT LEARNING](https://openreview.net/pdf?id=H1ezFREtwH) :+1:  ​

  :curly_loop: [DISCOVERING A SET OF POLICIES FOR THE WORST CASE REWARD](https://openreview.net/pdf?id=PUkhWz65dy5) :+1: 

  the problem we are solving can be seen as the definition and discovery of lower-level policies that will lead to a robust hierarchical agent. 

   ​

+ Acquiring Diverse Robot Skills via Maximum Entropy Deep Reinforcement Learning [Tuomas Haarnoja, UCB]  https://www2.eecs.berkeley.edu/Pubs/TechRpts/2018/EECS-2018-176.pdf :fire: :boom: :sweat_drops: :sweat_drops: 

+ [One Solution is Not All You Need: Few-Shot Extrapolation via Structured MaxEnt RL](https://biases-invariances-generalization.github.io/pdf/big_35.pdf) :+1:  ​  

+ [Evaluating Agents without Rewards](https://openreview.net/pdf?id=FoM-RnF6SNe) :+1: ​ :sweat_drops:  ​

+ [Explore, Discover and Learn: Unsupervised Discovery of State-Covering Skills](https://arxiv.org/pdf/2002.03647.pdf) :+1: :fire: :volcano: :boom: ​

  It should not aim for states where it has the most control according to its current abilities, but for states where it expects it will achieve the most control after learning. 

  :curly_loop:  [Ensemble and Auxiliary Tasks for Data-Efficient Deep Reinforcement Learning](https://arxiv.org/pdf/2107.01904.pdf) :no_mouth:  ​
  
   we study the effects of ensemble and auxiliary tasks when combined with the deep Q-learning alg. 
  
  
  
   ​ ​



### Galaxy 

​	:milky_way: :snowflake: :cyclone: :ocean: :volcano: :earth_africa: :earth_americas: :earth_asia: :book: :dart: :gem: :lemon: :headphones: :pushpin: :artificial_satellite: :satellite: :rocket: :stars: :sunrise_over_mountains: :triangular_flag_on_post: :beer: :tea: :date: :golf: :hourglass: :camera: :pager: :balloon: :trophy: :apple: :rice: ​

+ Deep Reinforcement Learning amidst Lifelong Non-Stationarity https://arxiv.org/pdf/2006.10701.pdf 

+ Learning Robot Skills with Temporal Variational Inference https://arxiv.org/pdf/2006.16232.pdf 

+ Gaussian Process Optimization in the Bandit Setting: No Regret and Experimental Design https://arxiv.org/pdf/0912.3995.pdf [icml2020 test of time award] :confused: :question: 

+ On Learning Sets of Symmetric Elements https://arxiv.org/pdf/2002.08599.pdf [icml2020 outstanding paper awards] :confused: :question: 

+ Non-delusional Q-learning and Value Iteration https://papers.nips.cc/paper/8200-non-delusional-q-learning-and-value-iteration.pdf [NeurIPS2018 Best Paper Award] 

+ SurVAE **Flows**: Surjections to Bridge the Gap between VAEs and Flows [Max Welling] https://arxiv.org/pdf/2007.02731.pdf 

  :curly_loop: [Normalizing Flows: An Introduction and Review of Current Methods](https://arxiv.org/pdf/1908.09257.pdf)  :+1: ; Citing:  [Normalizing Flows for Probabilistic Modeling and Inference](https://arxiv.org/pdf/1912.02762.pdf) :+1: :boom: :boom: :boom: ; [lil-log: Flow-based Deep Generative Models](https://lilianweng.github.io/lil-log/2018/10/13/flow-based-deep-generative-models.html) ; [Jianlin Su: f-VAES](https://zhuanlan.zhihu.com/p/45090025) :sweat_drops: ; [Deep generative models](https://deepgenerativemodels.github.io/notes/) :sweat_drops:  [Another slide](https://drive.google.com/file/d/1SGGWQR_FCHzsg-_aYzCjgHypXNesl6ML/view);  

  :curly_loop: [Deep Kernel Density Estimation](https://zhuanlan.zhihu.com/p/73426787) (Maximum Likelihood, Neural Density Estimation (Auto Regressive Models + Normalizing Flows), Score Matching ([MRF](http://signal.ee.psu.edu/mrf.pdf)), Kernel Exponential Family ([RKHS](http://songcy.net/posts/story-of-basis-and-kernel-part-2/)), Deep Kernel);  

  :curly_loop: 

+ Self-Supervised Learning  [lil-log](https://lilianweng.github.io/lil-log/2019/11/10/self-supervised-learning.html) :sweat_drops: ; 

  :curly_loop: [Self-Supervised Exploration via Disagreement](https://arxiv.org/pdf/1906.04161.pdf)  :confused: :-1: 

  :curly_loop: 



<a name="anchor-inference"></a>   

+ **Control as Inference** 

  :curly_loop: [Reinforcement Learning and Control as Probabilistic Inference: Tutorial and Review](https://arxiv.org/pdf/1805.00909.pdf) :boom: :boom: :volcano: :volcano:  ​

  **Graphic model for control as inference** (Decision Making Problem and Terminology; The Graphical Model; Policy search as Probabilistic Inference; Which Objective does This Inference Procedure Optimize;  Alternative Model Formulations);    

  Variation Inference and Stochastic Dynamic(Maximium RL with Fixed Dynamics; Connection to Structured VI);     

  Approximate Inference with Function Approximation(Maximum Entropy PG; Maxium Entropy AC Algorithms) 

  :curly_loop: [On Stochastic Optimal Control and Reinforcement Learning by Approximate Inference](http://www.roboticsproceedings.org/rss08/p45.pdf) :sweat_drops:  ​

  emphasizes that MaxEnt RL can be viewed as minimizing an KL divergence. 

  :curly_loop: [Iterative Inference Models](http://bayesiandeeplearning.org/2017/papers/9.pdf)  [Iterative Amortized Inference](http://proceedings.mlr.press/v80/marino18a/marino18a.pdf)  :+1: :+1:  ​ ​
  
  Latent Variable Models & Variational Inference &  Variational Expectation Maximization (EM) &  Inference Models 
  
  :curly_loop: [MAKING SENSE OF REINFORCEMENT LEARNING AND PROBABILISTIC INFERENCE](https://arxiv.org/pdf/2001.00805.pdf) :question: :sweat_drops:  ​
  
  :curly_loop: [Stochastic Latent Actor-Critic: Deep Reinforcement Learning with a Latent Variable Model](https://arxiv.org/pdf/1907.00953.pdf) :volcano: :boom:  ​ ​
  
  The main contribution of this work is a novel and principled approach that integrates learning stochastic sequential models and RL into a single method, performing RL in the model’s learned latent space. By **formalizing the problem as a control as inference problem within a POMDP**, we show that variational inference leads to the objective of our SLAC algorithm. 
  
  :curly_loop: [On the Design of Variational RL Algorithms](https://joelouismarino.github.io/files/papers/2019/variational_rl/neurips_workshop_paper.pdf) :+1: :+1: :fire: ​ Good **design choices**. :sweat_drops:  :ghost:  ​
  
  Identify several settings that have not yet been fully explored, and we discuss general directions for improving these algorithms: VI details; (non-)Parametric; Uniform/Learned Prior. 
  
  :curly_loop: [VIREL: A Variational Inference Framework for Reinforcement Learning](http://papers.nips.cc/paper/8934-virel-a-variational-inference-framework-for-reinforcement-learning.pdf) :confused:  ​
  
  existing inference frameworks and their algorithms pose significant challenges for learning optimal policies, for example, the lack of mode capturing behaviour in pseudo-likelihood methods, difficulties learning deterministic policies in maximum entropy RL based approaches, and a lack of analysis when function approximators are used. 
  
  :curly_loop: [MAXIMUM A POSTERIORI POLICY OPTIMISATION](https://openreview.net/pdf?id=S1ANxQW0b) :+1: :fire:  :droplet:  :volcano:  ​
  
  MPO based on coordinate ascent on a relativeentropy objective. We show that several existing methods can directly be related to our derivation. 



+ 
+ [Action and Perception as Divergence Minimization](https://arxiv.org/pdf/2009.01791.pdf) :boom: :volcano: :ghost: [the art of design] :sweat_drops:  ​



<a name="anchor-state-abstraction"></a>     

+ **State abstraction** & :hourglass: :diamond_shape_with_a_dot_inside:  Representation learning. :diamond_shape_with_a_dot_inside: :hourglass: 

  Representation learning for control based on bisimulation does not depend on reconstruction, but aims to group states based on their behavioral similarity in MDP.  [lil-log](https://lilianweng.github.io/lil-log/2019/11/10/self-supervised-learning.html#bisimulation) :sweat_drops: 

  :curly_loop: Equivalence Notions and Model Minimization in Markov Decision Processes http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.61.2493&rep=rep1&type=pdf : refers to an equivalence relation between two states with similar long-term behavior. :confused:  

  [BISIMULATION METRICS FOR CONTINUOUS MARKOV DECISION PROCESSES](https://www.cs.mcgill.ca/~prakash/Pubs/siamFP11.pdf) 

  :curly_loop: DeepMDP: Learning Continuous Latent Space Models for Representation Learning https://arxiv.org/pdf/1906.02736.pdf simplifies high-dimensional observations in RL tasks and learns a latent space model via minimizing two losses: **prediction of rewards** and **prediction of the distribution over next latent states**. :mega: :milky_way: :confused: :boom: :bomb: :boom: 

  :curly_loop: [DBC](https://zhuanlan.zhihu.com/p/157534599): [Learning Invariant Representations for Reinforcement Learning without Reconstruction](https://arxiv.org/pdf/2006.10742.pdf)  :boom: :boom: :boom: 

  :curly_loop: LEARNING INVARIANT FEATURE SPACES TO TRANSFER SKILLS WITH REINFORCEMENT LEARNING https://arxiv.org/pdf/1703.02949.pdf :fire: :+1: 

  differ in state-space, action-space, and dynamics. 

  Our method uses the skills that were learned by both agents to train **invariant feature spaces** that can then be used to transfer other skills from one agent to another. 

  :curly_loop: [UIUC: CS 598 Statistical Reinforcement Learning (S19) ](http://nanjiang.cs.illinois.edu/cs598/) NanJiang :+1::eagle: :eagle: 

  :curly_loop: [CONTRASTIVE BEHAVIORAL SIMILARITY EMBEDDINGS FOR GENERALIZATION IN REINFORCEMENT LEARNING](https://openreview.net/pdf?id=qda7-sVg84) :boom: :sweat_drops:  ​ 

  :hourglass:  :diamond_shape_with_a_dot_inside:  :diamond_shape_with_a_dot_inside:  :hourglass: ***Rep***resentation learning. :hourglass:  :diamond_shape_with_a_dot_inside:  :diamond_shape_with_a_dot_inside:  :hourglass: 

  :curly_loop: [CURL: Contrastive Unsupervised Representations for Reinforcement Learning](https://arxiv.org/pdf/2004.04136.pdf) :fire: :volcano: :droplet:  ​ ​

  :curly_loop: [Sim-to-Real via Sim-to-Sim: Data-efficient Robotic Grasping via Randomized-to-Canonical Adaptation Networks](https://arxiv.org/pdf/1812.07252.pdf) :+1: :fire: 

  Our method learns to translate randomized rendered images into their equivalent non-randomized, canonical versions. This in turn allows for real images to also be translated into canonical sim images. 

  :curly_loop: [Time-contrastive networks: Self-supervised learning from video](https://arxiv.org/pdf/1704.06888.pdf) :fire:  ​

  :curly_loop: [Data-Efficient Reinforcement Learning with Self-Predictive Representations](https://arxiv.org/pdf/2007.05929.pdf) :fire: ​  ​ ​

  :curly_loop: [Intrinsically Motivated Self-supervised Learning in Reinforcement Learning](https://arxiv.org/pdf/2106.13970.pdf) :+1: :fire:  ​

  employ self-supervised loss as an intrinsic reward, called Intrinsically Motivated Self-Supervised learning in Reinforcement learning (IM-SSR). *Decomposition and Interpretation of Contrastive Loss.*  

  :curly_loop: [EMI: Exploration with Mutual Information](https://arxiv.org/pdf/1810.01176.pdf) :+1: 

  We propose EMI, which is an exploration method that constructs embedding representation of states and actions that does not rely on generative decoding of the full observation but extracts predictive signals that can be used to guide exploration based on forward prediction in the representation space. 

  :curly_loop: [Bootstrap Latent-Predictive Representations for Multitask Reinforcement Learning](https://arxiv.org/pdf/2004.14646.pdf) :+1: :fire: :volcano: 

  The forward prediction encourages the agent state to move away from collapsing in order to accurately predict future random projections of observations. Similarly, the reverse prediction encourages the latent observation away from collapsing in order to accurately predict the random projection of a full history. *As we continue to train forward and reverse predictions, this seems to result in a virtuous cycle that continuously enriches both representations.*   

  :curly_loop: [Unsupervised Domain Adaptation with Shared Latent Dynamics for Reinforcement Learning](http://bayesiandeeplearning.org/2019/papers/102.pdf) :+1: 

  The model achieves the alignment between the latent codes via learning shared dynamics for different environments and matching marginal distributions of latent codes. 

  :curly_loop: [RETURN-BASED CONTRASTIVE REPRESENTATION LEARNING FOR REINFORCEMENT LEARNING](https://arxiv.org/pdf/2102.10960.pdf) :+1: :fire: 

  Our auxiliary loss is theoretically justified to learn representations that capture the structure of a new form of state-action abstraction, under which state-action pairs with similar return distributions are aggregated together. *Related work: AUXILIARY TASK + ABSTRACTION.*  

  :curly_loop: [Representation Matters: Offline Pretraining for Sequential Decision Making](https://arxiv.org/pdf/2102.05815.pdf) :+1: 

  :curly_loop: [SELF-SUPERVISED POLICY ADAPTATION DURING DEPLOYMENT](https://arxiv.org/pdf/2007.04309.pdf) :+1: :fire:  ​

  test time training  [TTT](https://arxiv.org/pdf/1909.13231.pdf)         Our work explores the use of self-supervision to allow the policy to continue training after deployment without using any rewards. 

  :curly_loop: [What Makes for Good Views for Contrastive Learning?](https://arxiv.org/pdf/2005.10243.pdf) :+1:  :fire: :boom: :volcano: 

  we should reduce the mutual information (MI) between views while keeping task-relevant information intact. 

  :curly_loop: [SELF-SUPERVISED LEARNING FROM A MULTI-VIEW PERSPECTIVE](https://arxiv.org/pdf/2006.05576.pdf) :+1: :fire:  ​ ​
  
  Demystifying Self-Supervised Learning: An Information-Theoretical Framework. 
  
  :curly_loop:[CONTRASTIVE BEHAVIORAL SIMILARITY EMBEDDINGS FOR GENERALIZATION IN REINFORCEMENT LEARNING](https://openreview.net/pdf?id=qda7-sVg84) :+1: :+1: 
  
  policy similarity metric (PSM) for measuring behavioral similarity between states. PSM assigns high similarity to states for which the optimal policies in those states as well as in future states are similar. 
  
  :curly_loop: [Invariant Causal Prediction for Block MDPs](http://proceedings.mlr.press/v119/zhang20t/zhang20t.pdf) :sweat_drops:  
  
  State Abstractions and Bisimulation; Causal Inference Using Invariant Prediction; 
  
  :curly_loop: [CAUSAL INFERENCE Q-NETWORK: TOWARD RESILIENT REINFORCEMENT LEARNING](https://arxiv.org/pdf/2102.09677.pdf) :+1: 
  
  In this paper, we consider a resilient DRL framework with observational interferences. 
  
  :curly_loop: [Decoupling Value and Policy for Generalization in Reinforcement Learning](https://arxiv.org/pdf/2102.10330.pdf) :+1: :fire:  ​
  
  Invariant Decoupled Advantage ActorCritic. First, IDAAC decouples the optimization of the policy and value function, using separate networks to model them. Second, it introduces an auxiliary loss which encourages the representation to be invariant to task-irrelevant properties of the environment. 
  
  :curly_loop: [Robust Deep Reinforcement Learning against Adversarial Perturbations on State Obs](https://arxiv.org/pdf/2003.08938.pdf) :fire: :volcano: :droplet:  ​ ​
  
  We propose the state-adversarial Markov decision process (SA-MDP) to study the fundamental properties of this problem, and develop a theoretically principled policy regularization which can be applied to a large family of DRL algorithms. 
  
  :curly_loop: [Understanding Adversarial Attacks on Observations in Deep Reinforcement Learning](https://arxiv.org/pdf/2106.15860.pdf) :sweat_drops:  ​
  
  
  
  :curly_loop: [ROBUST REINFORCEMENT LEARNING ON STATE OBSERVATIONS WITH LEARNED OPTIMAL ADVERSARY](https://arxiv.org/pdf/2101.08452.pdf)  
  
  :curly_loop: [Loss is its own Reward: Self-Supervision for Reinforcement Learning](https://arxiv.org/pdf/1612.07307.pdf)  :+1:  :boom:  ​
  
   To augment reward, we consider a range of selfsupervised tasks that incorporate states, actions, and successors to provide auxiliary losses. 
  
  :curly_loop: [Unsupervised Learning of Visual 3D Keypoints for Control](https://arxiv.org/pdf/2106.07643.pdf) :+1: :boom: 
  
  motivation: most of these representations, whether structured or unstructured are learned in a 2D space even though the control tasks are usually performed in a 3D environment. 
  
  :curly_loop: [Which Mutual-Information Representation Learning Objectives are Sufficient for Control?](https://arxiv.org/pdf/2106.07278.pdf) :+1: :boom: :volcano: 
  
  we formalize the sufficiency of a state representation for learning and representing the optimal policy, and study several popular mutual-information based objectives through this lens.  ​
  
  :curly_loop: [Towards a Unified Theory of State Abstraction for MDPs](http://rbr.cs.umass.edu/aimath06/proceedings/P21.pdf) :+1: :fire::volcano: :droplet:  ​ ​ ​
  
  We provide a unified treatment of state abstraction for Markov decision processes. We study five particular abstraction schemes. 
  
  :curly_loop: [Learning State Abstractions for Transfer in Continuous Control](https://arxiv.org/pdf/2002.05518.pdf) :fire:  ​
  
  Our main contribution is a learning algorithm that abstracts a continuous state-space into a discrete one. We transfer this learned representation to unseen problems to enable effective learning. 
  
  :curly_loop: [Multi-Modal Mutual Information (MuMMI) Training for Robust Self-Supervised Deep Reinforcement Learning](https://arxiv.org/pdf/2107.02339.pdf) :+1:  :fire:  
  
  we contribute a new multi-modal deep latent state-space model, trained using a mutual information lower-bound. 
  
  
  
  

 ​

<a name="anchor-MI"></a>     

+ **mutual information**: 

  :curly_loop: [MINE: Mutual Information Neural Estimation](https://arxiv.org/pdf/1801.04062.pdf) :+1::droplet:  :fire:     [f-gan & mine](https://zhuanlan.zhihu.com/p/151256189) :sweat_drops: 

  :curly_loop: [C-MI-GAN : Estimation of Conditional Mutual Information Using MinMax Formulation](https://arxiv.org/pdf/2005.08226.pdf) :+1: :fire:  ​ ​

  :curly_loop: [Deep InfoMax: LEARNING DEEP REPRESENTATIONS BY MUTUAL INFORMATION ESTIMATION AND MAXIMIZATION](https://arxiv.org/pdf/1808.06670.pdf) :+1::droplet: ​  

  :curly_loop: [ON MUTUAL INFORMATION MAXIMIZATION FOR REPRESENTATION LEARNING](https://arxiv.org/pdf/1907.13625.pdf) :sweat_drops: :+1:  ​ 

  :curly_loop: [Deep Reinforcement and InfoMax Learning](Deep Reinforcement and InfoMax Learning) :sweat_drops: :+1: :confused: :droplet: 

  Our work is based on the hypothesis that a model-free agent whose **representations are predictive of properties of future states** (beyond expected rewards) will be more capable of solving and adapting to new RL problems, and in a way, incorporate aspects of model-based learning. 

  :curly_loop: [Unpacking Information Bottlenecks: Unifying Information-Theoretic Objectives in Deep Learning](https://arxiv.org/pdf/2003.12537.pdf) :volcano: 

  New: Unpacking Information Bottlenecks: Surrogate Objectives for Deep Learning 

  :curly_loop: [Opening the black box of Deep Neural Networ ksvia Information](https://arxiv.org/pdf/1703.00810.pdf) 

  :o: :o: UYANG: 

  [小王爱迁移](https://zhuanlan.zhihu.com/p/27336930), 

  :curly_loop: ​[Self-Supervised Representation Learning From Multi-Domain Data](Self-Supervised Representation Learning From Multi-Domain Data), :fire: :+1: :+1: 

  The proposed mutual information constraints encourage neural network to extract common invariant information across domains and to preserve peculiar information of each domain simultaneously. We adopt tractable **upper and lower bounds of mutual information** to make the proposed constraints solvable. 

  :curly_loop: ​[Unsupervised Domain Adaptation via Regularized Conditional Alignment](https://openaccess.thecvf.com/content_ICCV_2019/papers/Cicek_Unsupervised_Domain_Adaptation_via_Regularized_Conditional_Alignment_ICCV_2019_paper.pdf), :fire: :+1:  

   Joint alignment ensures that not only the marginal distributions of the domains are aligned, but the labels as well. 

  :curly_loop: ​[Domain Adaptation with Conditional Distribution Matching and Generalized Label Shift](https://arxiv.org/pdf/2003.04475.pdf), :fire: :boom: :boom: :sweat_drops:    

  In this paper, we extend a recent upper-bound on the performance of adversarial domain adaptation to multi-class classification and more general discriminators. We then propose **generalized label shift (GLS)** as a way to improve robustness against mismatched label distributions. GLS states that, conditioned on the label, **there exists a representation of the input that is invariant between the source and target domains**. 

  :curly_loop: ​[Learning to Learn with Variational Information Bottleneck for Domain Generalization](https://arxiv.org/pdf/2007.07645.pdf), 

  Through episodic training, MetaVIB learns to gradually narrow domain gaps to establish domain-invariant representations, while simultaneously maximizing prediction accuracy. 

  :curly_loop: ​[Deep Domain Generalization via Conditional Invariant Adversarial Networks](https://www.ecva.net/papers/eccv_2018/papers_ECCV/papers/Ya_Li_Deep_Domain_Generalization_ECCV_2018_paper.pdf), :+1:    

  :curly_loop: ​[On Learning Invariant Representation for Domain Adaptation](https://arxiv.org/pdf/1901.09453.pdf) :fire: :boom: :sweat_drops: 

  :curly_loop: ​[GENERALIZING ACROSS DOMAINS VIA CROSS-GRADIENT TRAINING](https://arxiv.org/pdf/1804.10745.pdf) :fire: :volcano: :volcano:    

  In contrast, in our setting, we wish to avoid any such explicit domain representation, **appealing instead to the power of deep networks to discover implicit features**. We also argue that even if such such overfitting could be avoided, we do not necessarily want to wipe out domain signals, if it helps in-domain test instances. 

  :curly_loop: ​[In Search of Lost Domain Generalization](https://arxiv.org/pdf/2007.01434.pdf) :no_mouth:  

  :curly_loop: [DIRL: Domain-Invariant Representation Learning for Sim-to-Real Transfer](https://arxiv.org/pdf/2011.07589.pdf) :sweat_drops:  ​

  :o: :o: ***self-supervised*** learning 

  :curly_loop: [Bootstrap Your Own Latent A New Approach to Self-Supervised Learning](https://arxiv.org/pdf/2006.07733.pdf) :fire: :volcano: 

  Related work is good!  ​ ​






<a name="anchor-disrl"></a>   

+ Distributional RL [Hao Liang, CUHK](https://rlseminar.github.io/2019/03/11/hao.html)  [slide](https://rlseminar.github.io/static/files/RL_seminars2019-0311hao_distributional_final.pdf) :sweat_drops: :sweat_drops:  ​ ​

  :curly_loop: C51: [A Distributional Perspective on Reinforcement Learning](https://arxiv.org/pdf/1707.06887.pdf) :sweat_drops:  ​
  
  :curly_loop: [CS598 - Statistical rl - NanJiang](https://www.bilibili.com/video/av929950486) :sweat_drops: ​
  
  :curly_loop: [Information-Theoretic Considerations in Batch Reinforcement Learning](http://proceedings.mlr.press/v97/chen19e/chen19e.pdf) :volcano: :confused: :sweat_drops:   
  
   





<a name="anchor-cl"></a>   

+ Continual Learning 

  :curly_loop: [Continual Learning with Deep Generative Replay](https://papers.nips.cc/paper/6892-continual-learning-with-deep-generative-replay.pdf)  :droplet: :no_mouth:  

  :curly_loop: online learning; regret :sweat_drops:  ​





<a name="anchor-DR"></a>  <a name="anchor-sim2real"></a>  

+ DR (Domain Randomization) & sim2real 

  :curly_loop: Active Domain Randomization http://proceedings.mlr.press/v100/mehta20a/mehta20a.pdf :fire: :boom: :fire: 

  Our method looks for the most **informative environment variations** within the given randomization ranges by **leveraging the discrepancies of policy rollouts in randomized and reference environment instances**. We find that training more frequently on these instances leads to better overall agent generalization. 

  Domain Randomization; Stein Variational Policy Gradient;   

  Bhairav Mehta [On Learning and Generalization in Unstructured Task Spaces](https://bhairavmehta95.github.io/static/thesis.pdf) :sweat_drops: :sweat_drops:   

  :curly_loop: [VADRA: Visual Adversarial Domain Randomization and Augmentation](https://arxiv.org/pdf/1812.00491.pdf) :fire: :+1:  generative + learner 

  :curly_loop: [Which Training Methods for GANs do actually Converge?](https://arxiv.org/pdf/1801.04406.pdf)  :+1: :droplet:   [ODE: GAN](https://zhuanlan.zhihu.com/p/65953336) 

  :curly_loop: [Robust Adversarial Reinforcement Learning](https://arxiv.org/pdf/1703.02702.pdf) :no_mouth:  ​

  Our proposed method, Robust Adversarial Reinforcement Learning (RARL), jointly trains a pair of agents, a protagonist and an adversary, where the protagonist learns to fulfil the original task goals while being robust to the disruptions generated by its adversary. 

  :curly_loop: [Closing the Sim-to-Real Loop: Adapting Simulation Randomization with Real World Experience](https://arxiv.org/pdf/1810.05687.pdf) :no_mouth:  ​

  :curly_loop: [POLICY TRANSFER WITH STRATEGY OPTIMIZATION](https://arxiv.org/pdf/1810.05751.pdf) :no_mouth:  ​ 

  The key idea that, instead of learning a single policy in the simulation, we simultaneously learn a family of policies that exhibit different behaviors. When tested in the target environment, we directly search for the best policy in the family based on the task performance, without the need to identify the dynamic parameters. 

  :curly_loop: https://lilianweng.github.io/lil-log/2019/05/05/domain-randomization.html :sweat_drops: 

  :curly_loop: [THE INGREDIENTS OF REAL-WORLD ROBOTIC REINFORCEMENT LEARNING](https://arxiv.org/pdf/2004.12570.pdf) :no_mouth:  ​

  :curly_loop: [ROBUST REINFORCEMENT LEARNING ON STATE OBSERVATIONS WITH LEARNED OPTIMAL ADVERSARY](https://openreview.net/pdf?id=sCZbhBvqQaU) :+1: 

  To enhance the robustness of an agent, we propose a framework of alternating training with learned adversaries (ATLA), which trains an adversary online together with the agent using policy gradient following the optimal adversarial attack framework.  

  :curly_loop: [SELF-SUPERVISED POLICY ADAPTATION DURING DEPLOYMENT](https://openreview.net/pdf?id=o_V-MjyyGV_) :+1: :fire:  

  Our work explores the use of self-supervision to allow the policy to continue training after deployment without using any rewards. 
  
  :curly_loop: [SimGAN: Hybrid Simulator Identification for Domain Adaptation via Adversarial Reinforcement Learning](https://arxiv.org/pdf/2101.06005.pdf) :+1: 
  
  identifying a hybrid physics simulator to match the simulated \tau to the ones from the target domain, using a learned discriminative loss to address the limitations associated with manual loss design. Our hybrid simulator combines nns and traditional physics simulaton to balance expressiveness and generalizability, and alleviates the need for a carefully selected parameter set in System ID. 
  
  
  
   ​

<a name="anchor-transfer"></a>  

+ **Transfer**: Generalization & Adaption & **Dynamics** 

  :curly_loop: [Automatic Data Augmentation for Generalization in Deep Reinforcement Learning](https://arxiv.org/pdf/2006.12862.pdf)  :punch: :+1:  ​  ​ ​

  Across different visual inputs (with the same semantics), dynamics, or other environment structures 

  :curly_loop: [Image Augmentation Is All You Need: Regularizing Deep Reinforcement Learning from Pixels](https://arxiv.org/pdf/2004.13649.pdf) :+1: 

  :curly_loop: [Fast Adaptation to New Environments via Policy-Dynamics Value Functions](https://arxiv.org/pdf/2007.02879.pdf) :fire: :boom: :+1:  ​ 

  PD-VF explicitly estimates the cumulative reward in a space of policies and environments. 

  :curly_loop: [Off-Dynamics Reinforcement Learning: Training for Transfer with Domain Classifiers](https://openreview.net/pdf?id=eqBwg3AcIAK) :fire: :boom: :volcano: :droplet:  

  The main contribution of this work is an algorithm for domain adaptation to dynamics changes in RL, based on the idea of compensating for **differences in dynamics** by modifying the reward function. This algorithm does not need to estimate transition probabilities, but rather modifies the reward function using a pair of classifiers. 

  **Related work is good!** :+1: 

  + general domain adaption (DA) =  importance weighting + domain-agnostic features 

+ DA in RL =  system identification + domain randomization + observation adaptation :+1: 
  + formulates control as a problem of probabilistic inference :droplet: 

  :curly_loop: [Mutual Alignment Transfer Learning](https://arxiv.org/pdf/1707.07907.pdf) :+1: :fire:  ​ ​

  The developed approach harnesses auxiliary rewards to guide the exploration for the real world agent based on the proficiency of the agent in simulation and vice versa. 

  :curly_loop: [SimGAN: Hybrid Simulator Identification for Domain Adaptation via Adversarial Reinforcement Learning](https://arxiv.org/pdf/2101.06005.pdf)  [real dog] :+1: :fire:  ​ ​

  a framework to tackle domain adaptation by identifying a hybrid physics simulator to match the simulated trajectories to the ones from the target domain, using a learned discriminative loss to address the limitations associated with manual loss design. 

   :curly_loop: [Disentangled Skill Embeddings for Reinforcement Learning](https://arxiv.org/pdf/1906.09223.pdf) :fire: :volcano: :boom: :boom:  ​ ​ ​ ​ 

  We have developed a multi-task framework from a variational inference perspective that is able to learn latent spaces that generalize to unseen tasks where the dynamics and reward can change independently. 

  :curly_loop: [**Transfer Learning in Deep Reinforcement Learning: A Survey**](https://arxiv.org/pdf/2009.07888.pdf)  :sweat_drops:  ​

  Evaluation metrics: Mastery and Generalization. 
  
  TRANSFER LEARNING APPROACHES: Reward Shaping; Learning from Demonstrations; Policy Transfer (Transfer Learning via Policy Distillation, Transfer Learning via Policy Reuse); Inter-Task Mapping; Representation Transfer(Reusing Representations, Disentangling Representations); 
  
  :curly_loop: [Provably Efficient Model-based Policy Adaptation](https://arxiv.org/pdf/2006.08051.pdf) :+1: :fire: :volcano: :droplet: :+1:  ​
  
  We prove that the approach learns policies in the target environment that can recover trajectories from the source environment, and establish the rate of convergence in general settings. 
  
  :o: reward shaping 
  
  + :curly_loop: [Useful Policy Invariant Shaping from Arbitrary Advice](https://arxiv.org/pdf/2011.01297.pdf) :+1:  ​
  
+ Action 
  

:curly_loop: [Generalization to New Actions in Reinforcement Learning](https://arxiv.org/pdf/2011.01928.pdf) :+1: 

  We propose a two-stage framework where the agent first infers action representations from action information acquired separately from the task. A policy flexible to varying action sets is then trained with generalization objectives. 

:curly_loop: [Policy Transfer across Visual and Dynamics Domain Gaps via Iterative Grounding](https://arxiv.org/pdf/2107.00339.pdf) :+1: :fire:  

alternates between (1) directly minimizing both visual and dynamics domain gaps by grounding the source env in the target env domains, and (2) training a policy on the grounded source env. 

 ​

  

  

   ​

  


:curly_loop: [ADAPT-TO-LEARN: POLICY TRANSFER IN REINFORCEMENT LEARNING](https://openreview.net/pdf?id=ryeT10VKDH) :+1: :+1:  ​

adapt the source policy to learn to solve a target task with significant **transition differences** and uncertainties.  

:curly_loop: [SINGLE EPISODE POLICY TRANSFER IN REINFORCEMENT LEARNING](https://arxiv.org/pdf/1910.07719.pdf) :fire: :+1:  ​ ​

Our key idea of optimized probing for accelerated latent variable inference is to train a dedicated probe policy πϕ(a|s) to generate a dataset D of short trajectories at the beginning of all training episodes, such that the VAE’s performance on D is optimized. 

:curly_loop: [Dynamical Variational Autoencoders: A Comprehensive Review](https://arxiv.org/pdf/2008.12595.pdf) :sweat_drops: :sweat_drops:  ​ ​

:curly_loop: [Dynamics Generalization via Information Bottleneck in Deep Reinforcement Learning](https://arxiv.org/pdf/2008.00614.pdf)​ :fire:  ​ ​

In particular, we show that the poor generalization in unseen tasks is due to the **DNNs memorizing environment observations**, rather than extracting the relevant information for a task. To prevent this, we impose communication constraints as an information bottleneck between the agent and the environment. 

:curly_loop: [UNIVERSAL AGENT FOR DISENTANGLING ENVIRONMENTS AND TASKS](https://openreview.net/pdf?id=B1mvVm-C-) :fire: :volcano: 

The environment-specific unit handles how to move from one state to the target state; and the task-specific unit plans for the next target state given a specific task.  

:curly_loop: [Decoupling Dynamics and Reward for Transfer Learning](https://arxiv.org/pdf/1804.10689.pdf) :+1: 

We separate learning the task representation, the forward dynamics, the inverse dynamics and the reward function of the domain.  

:curly_loop: [Neural Dynamic Policies for End-to-End Sensorimotor Learning](https://biases-invariances-generalization.github.io/pdf/big_15.pdf) :fire: :volcano: 

We propose Neural Dynamic Policies (NDPs) that make predictions in trajectory distribution space as opposed to raw control spaces. [see Abstract!] **Similar in spirit to UNIVERSAL AGENT.** 

:curly_loop: [Accelerating Reinforcement Learning with Learned Skill Priors](https://arxiv.org/pdf/2010.11944.pdf) :+1: :fire: 

We propose a deep latent variable model that jointly learns an embedding space of skills and the skill prior from offline agent experience. We then extend common maximumentropy RL approaches to use **skill priors to guide downstream learning**.    

:curly_loop: [Mutual Alignment Transfer Learning](https://arxiv.org/pdf/1707.07907.pdf) :+1: :fire: 

The developed approach harnesses auxiliary rewards to guide the exploration for the real world agent based on the proficiency of the agent in simulation and vice versa. 

:curly_loop: [LEARNING CROSS-DOMAIN CORRESPONDENCE FOR CONTROL WITH DYNAMICS CYCLE-CONSISTENCY](https://openreview.net/pdf?id=QIRlze3I6hX) :+1: :+1: :fire: 

In this paper, we propose to learn correspondence across such domains emphasizing on differing modalities (vision and internal state), physics parameters (mass and friction), and morphologies (number of limbs). Importantly, correspondences are learned using unpaired and randomly collected data from the two domains. We propose **dynamics cycles** that align dynamic robotic behavior across two domains using a cycle consistency constraint. 

:curly_loop: [Improving Generalization in Reinforcement Learning with Mixture Regularization](https://arxiv.org/pdf/2010.10814.pdf) :+1: 

these approaches only locally perturb the observations regardless of the training environments, showing limited effectiveness on enhancing the data diversity and the generalization performance. 

:curly_loop: [AdaRL: What, Where, and How to Adapt in Transfer Reinforcement Learning](https://arxiv.org/pdf/2107.02729.pdf) :fire:  :droplet: 

 we characterize a minimal set of representations, including both domain-specific factors and domain-shared state representations, that suffice for reliable and low-cost transfer. 

 <a name="anchor-ood"></a> 

:o: :o: :o: **Out-of-Distribution (OOD) Generalization**  [Modularity--->Generalization](https://zhuanlan.zhihu.com/p/137082457) 

:curly_loop: [Invariant Risk Minimization](https://arxiv.org/pdf/1907.02893.pdf) Introduction is good! :+1: :fire: :boom:   [slide](https://bayesgroup.github.io/bmml_sem/2019/Kodryan_Invariant%20Risk%20Minimization.pdf) [information theoretic view](https://www.inference.vc/invariant-risk-minimization/) 

To learn invariances across environments, find a data representation such that the optimal classifier on top of that representation matches for all environments. 

:curly_loop: [Out-of-Distribution Generalization via Risk Extrapolation](https://arxiv.org/pdf/2003.00688.pdf) :+1: :fire: 

REx can be viewed as encouraging robustness over affine combinations of training risks, by encouraging strict equality between training risks. 

:curly_loop: [OUT-OF-DISTRIBUTION GENERALIZATION ANALYSIS VIA INFLUENCE FUNCTION](https://arxiv.org/pdf/2101.08521.pdf) :fire: 

if a learnt model fθˆ manage to simultaneously achieve small Vγˆ|θˆ and high accuracy over E_test, it should have good OOD accuracy. 

:curly_loop: [EMPIRICAL OR INVARIANT RISK MINIMIZATION? A SAMPLE COMPLEXITY PERSPECTIVE](https://openreview.net/pdf?id=jrA5GAccy_) :droplet:  ​

:curly_loop: [Invariant Rationalization](http://proceedings.mlr.press/v119/chang20c/chang20c.pdf) :+1: :fire:  :boom: 

MMI can be problematic because it picks up spurious correlations between the input features and the output. Instead, we introduce a game-theoretic invariant rationalization criterion where the rationales are constrained to enable the same predictor to be optimal across different environments.  

:curly_loop: [Invariant Risk Minimization Games ](http://proceedings.mlr.press/v119/ahuja20a/ahuja20a.pdf) :droplet:  ​

 ​ ​

:o: influence function 

+ :curly_loop: [Understanding Black-box Predictions via Influence Functions](https://arxiv.org/pdf/1703.04730.pdf) :fire: :droplet:   
  
  Upweighting a training point; Perturbing a training input; Efficiently calculating influence :droplet: ;  
  
  + :curly_loop: [INFLUENCE FUNCTIONS IN DEEP LEARNING ARE FRAGILE](https://arxiv.org/pdf/2006.14651.pdf) :+1: :fire: :+1:  
  
    non-convexity of the loss function ---  different initializations; parameters might be very large --- substantial Taylor’s approximation error of the loss function; computationally very expensive ---  approximate inverse-Hessian Vector product techniques which might be erroneous;  different architectures can have different loss landscape geometries near the optimal model parameters, leading to varying influence estimates. 
  
  + :curly_loop: [On the Accuracy of Influence Functions for Measuring Group Effects](https://arxiv.org/pdf/1905.13289.pdf) :+1:  ​
  
    when measuring the change in test prediction or test loss, influence is additive. 
  
  :o: do-calculate ---> causual inference (Interventions) ---> counterfactuals 
  
  see [inFERENCe's blog](https://www.inference.vc/causal-inference-3-counterfactuals/) :+1: :fire: :boom:   the intervention conditional p(y|do(X=x^))p(y|do(X=x^)) is the average of counterfactuals over the obserevable population.  







<a name="anchor-causual"></a>  

+ Causual inference  [ see more in <a href="#anchor-ood">OOD</a> & [inFERENCe's blog](https://www.inference.vc/causal-inference-3-counterfactuals/) ] 

  :curly_loop: 

+ reasoning 

  :curly_loop: [CAUSAL DISCOVERY WITH REINFORCEMENT LEARNING](https://arxiv.org/pdf/1906.04477.pdf) :no_mouth:  ​

  :curly_loop: [DEEP REINFORCEMENT LEARNING WITH CAUSALITYBASED INTRINSIC REWARD](https://openreview.net/pdf?id=30I4Azqc_oP) :+1: 

  The proposed algorithm learns a graph to encode the environmental structure by calculating Average Causal Effect (ACE) between different categories of entities, and an intrinsic reward is given to encourage the agent to interact more with entities belonging to top-ranked categories, which significantly boosts policy learning. 
  
  :curly_loop: [Causal Confusion in Imitation Learning](https://arxiv.org/pdf/1905.11979.pdf) :+1: :droplet: 
  
  propose a solution to combat it through targeted interventions—either environment interaction or expert queries—to determine the correct causal model. 





 <a name="anchor-exploration"></a> 

+ [Exploration Strategies in Deep Reinforcement Learning](https://lilianweng.github.io/lil-log/2020/06/07/exploration-strategies-in-deep-reinforcement-learning.html) [[chinese]](https://mp.weixin.qq.com/s/FX-1IlIaFDLaQEVFN813jA) :sweat_drops: :fire: :fire:  :boom:   

  :curly_loop: [VIME: Variational Information Maximizing Exploration](https://arxiv.org/pdf/1605.09674.pdf) :+1: :punch: :droplet:  ​ ​BNN 

   the agent should take actions that maximize the reduction in uncertainty about the dynamics.

  :curly_loop:  [Self-Supervised Exploration via Disagreement](https://arxiv.org/pdf/1906.04161.pdf)  :+1: 

  an ensemble of dynamics models and incentivize the agent to explore such that the disagreement of those ensembles is maximized. 

  :curly_loop: [DORA THE EXPLORER: DIRECTED OUTREACHING REINFORCEMENT ACTION-SELECTION](https://arxiv.org/pdf/1804.04012.pdf) :fire: :+1: :droplet: 

  We propose **E-values**, a generalization of counters that can be used to evaluate the propagating exploratory value over state-action trajectories.  [The Hebrew University of Jerusalem] :+1: 

  :curly_loop: [EXPLORATION BY RANDOM NETWORK DISTILLATION](https://arxiv.org/pdf/1810.12894.pdf) :fire: :+1: [medium](https://medium.com/data-from-the-trenches/curiosity-driven-learning-through-random-network-distillation-488ffd8e5938)  :+1:  ​

  based on random network distillation (**RND**) bonus 

  :curly_loop: [Randomized Prior Functions for Deep Reinforcement Learning](https://arxiv.org/pdf/1806.03335.pdf) :fire: :boom: :sweat_drops:  ​ ​ ​

  :curly_loop: [Large-Scale Study of Curiosity-Driven Learning](https://arxiv.org/pdf/1808.04355.pdf) :+1:  ​ 

  :curly_loop: [NEVER GIVE UP: LEARNING DIRECTED EXPLORATION STRATEGIES](https://arxiv.org/pdf/2002.06038.pdf)  :punch: :+1: 

  episodic memory based intrinsic reward using k-nearest neighbors;   self-supervised inverse dynamics model; Universal Value Function Approximators; different degrees of exploration/exploitation;  distributed RL; 

  :curly_loop: [Self-Imitation Learning via TrajectoryConditioned Policy for Hard-Exploration Tasks](https://arxiv.org/pdf/1907.10247.pdf) :sweat_drops:  ​

  :curly_loop: [Planning to Explore via Self-Supervised World Models](https://arxiv.org/pdf/2005.05960.pdf)  :fire: :fire: :+1:  ​ ​ ​Experiment is good!  

  a self supervised reinforcement learning agent that tackles both these challenges through a new approach to self-supervised exploration and fast adaptation to new tasks, which need not be known during exploration.  **unlike prior methods which retrospectively compute the novelty of observations after the agent has already reached them**, our agent acts efficiently by leveraging planning to seek out expected future novelty.  

  :curly_loop: [Efficient Exploration via State Marginal Matching](https://arxiv.org/pdf/1906.05274.pdf) :fire: :volcano: :droplet:  :boom:  ​

  our work unifies prior exploration methods as performing approximate distribution matching, and explains how state distribution matching can be performed properly 

  :curly_loop: hard exploration 

  ​	[Provably efficient RL with Rich Observations via Latent State Decoding](https://arxiv.org/pdf/1901.09018.pdf) :confused:  ​

  ​	[Provably Efficient Exploration for RL with Unsupervised Learning](https://arxiv.org/pdf/2003.06898.pdf) :confused:  ​

  :curly_loop: [Learning latent state representation for speeding up exploration](https://arxiv.org/pdf/1905.12621.pdf) :+1:
  
  Prior experience on separate but related tasks help learn representations of the state which are effective at predicting instantaneous rewards. 
  
  :curly_loop: [Self-Imitation Learning](http://proceedings.mlr.press/v80/oh18b/oh18b.pdf) [reward shaping] :+1: :fire:  
  
  exploiting past good experiences can indirectly drive deep exploration.  we consider exploiting what the agent has experienced, but has not yet learned. Related work: Exploration; Episodic control; Experience replay; Experience replay for actor-critic; Connection between policy gradient and Q-learning; Learning from imperfect demonstrations.  
  
  :curly_loop: [Generative Adversarial Self-Imitation Learning](https://arxiv.org/pdf/1812.00950.pdf)  [reward shaping] :fire: ​
  
  GASIL focuses on reproducing past good trajectories, which can potentially make long-term credit assignment easier when rewards are sparse and delayed. 
  
  :curly_loop: [Diversity Actor-Critic: Sample-Aware Entropy Regularization for Sample-Efficient Exploration](https://arxiv.org/pdf/2006.01419.pdf) :fire: :droplet: 
  
  To take advantage of the previous sample distribution from the replay buffer for sample-efficient exploration, we propose sample-aware entropy regularization which maximizes the entropy of weighted sum of the policy action distribution and the sample action distribution from the replay buf. 
  
  :curly_loop: [LEARNING SELF-IMITATING DIVERSE POLICIES](https://arxiv.org/pdf/1805.10309.pdf) :+1: :fire: :fire:  ​
  
  We view each policy as a state-action visitation distribution and formulate policy optimization as a divergence minimization problem. We show that with Jensen-Shannon divergence, this divergence minimization problem can be reduced into a policy-gradient algorithm with shaped rewards learned from experience replays.  One approach to achieve better exploration in challenging cases like above is to simultaneously learn *multiple diverse policies* and enforce them to explore different parts of the high dimensional space.  
  
  :curly_loop: [Stein Variational Gradient Descent: A General Purpose Bayesian Inference Algorithm 2016](https://arxiv.org/pdf/1608.04471.pdf) 
  
  :curly_loop: [ADVERSARIALLY GUIDED ACTOR-CRITIC](https://arxiv.org/pdf/2102.04376.pdf) :+1: :fire: :fire: 
  
  While the adversary mimics the actor by minimizing the KL-divergence between their respective action distributions, the actor, in addition to learning to solve the task, tries to differentiate itself from the adversary predictions. 
  
  :curly_loop: [Diversity-Driven Exploration Strategy for Deep Reinforcement Learning](https://arxiv.org/pdf/1802.04564.pdf) :+1: :fire:  ​ ​
  
  adding a distance measure regularization to the loss function, 
  
  :curly_loop: [Provably Efficient Maximum Entropy Exploration](https://arxiv.org/pdf/1812.02690.pdf) :confused:  
  
  :curly_loop: [Reward-Free Exploration for Reinforcement Learning](http://proceedings.mlr.press/v119/jin20d/jin20d.pdf) :+1: :fire: :boom: 
  
  *How can we efficiently explore an environment without using any reward information?*  In the exploration phase, the agent first collects trajectories from an MDP M without a pre-specified reward function. After exploration, it is tasked with computing near-optimal policies under for M for a collection of given reward functions. 
  
  :curly_loop: [Rethinking Exploration for Sample-Efficient Policy Learning](https://arxiv.org/pdf/2101.09458.pdf) :+1:  ​
  
  BBE: bias with finite samples, slow adaptation to decaying bonuses, and lack of optimism on unseen transitions ---> UFO, produces policies that are Unbiased with finite samples, Fast-adapting as the exploration bonus changes, and Optimistic with respect to new transitions. 
  
  :curly_loop: [Provably Efficient Exploration in Policy Optimization](http://proceedings.mlr.press/v119/cai20d/cai20d.pdf) :confused: 
  
   design a provably efficient policy optimization algorithm that incorporates exploration. 
  
  
  
  
  
  
  
  
  
  
  
   ​ ​ ​
  
   ​ ​ ​
  
  
  
   ​
  
  

<a name="anchor-offline "></a> 

+ Offline RL 

  :curly_loop: [Offline Reinforcement Learning: Tutorial, Review, and Perspectives on Open Problems](https://arxiv.org/pdf/2005.01643.pdf)​  :boom: :boom:  ​ :droplet:  ​

  Offline RL with dynamic programming: distributional shift; policy constraints; uncertainty estimation; conservative Q-learning and Pessimistic Value-function; 

  https://danieltakeshi.github.io/2020/06/28/offline-rl/ :sweat_drops: 

  https://ai.googleblog.com/2020/08/tackling-open-challenges-in-offline.html :sweat_drops: 

  https://sites.google.com/view/offlinerltutorial-neurips2020/home :sweat_drops: 

  :curly_loop: [OPAL: OFFLINE PRIMITIVE DISCOVERY FOR ACCELERATING OFFLINE REINFORCEMENT LEARNING](https://arxiv.org/pdf/2010.13611.pdf) :boom:  when presented with offline data composed of a variety of behaviors, an effective way to leverage this data is to extract a continuous space of recurring and temporally extended primitive behaviors before using these primitives for downstream task learning. OFFLINE unsupervised RL. 

  :curly_loop: [Deployment-Efficient Reinforcement Learning via Model-Based Offline Optimization](https://arxiv.org/pdf/2006.03647.pdf) :+1: :volcano:  :boom: 

  :curly_loop: [BENCHMARKS FOR DEEP OFF-POLICY EVALUATION](https://openreview.net/pdf?id=kWSeGEeHvF8) :+1: 

  :curly_loop: [KEEP DOING WHAT WORKED: BEHAVIOR MODELLING PRIORS FOR OFFLINE REINFORCEMENT LEARNING](https://arxiv.org/pdf/2002.08396.pdf) :+1: :fire: :boom: 

  It admits the use of data generated by arbitrary behavior policies and uses a learned prior – the advantage-weighted behavior model (ABM) – to bias the RL policy towards actions that have previously been executed and are likely to be successful on the new task.    

  extrapolation or bootstrapping errors:  (Fujimoto et al., 2018; Kumar et al., 2019) 

  :curly_loop: [Off-Policy Deep Reinforcement Learning without Exploration](https://arxiv.org/pdf/1812.02900.pdf) :fire: :boom: :volcano:  ​ ​ ​

  We introduce a novel class of off-policy algorithms, batch-constrained reinforcement learning, which restricts the action space in order to force the agent towards behaving close to on-policy with respect to a subset of the given data. 

  :curly_loop: [Stabilizing Off-Policy Q-Learning via Bootstrapping Error Reduction](https://arxiv.org/pdf/1906.00949.pdf) :fire: :boom: :droplet:  ​

  We identify bootstrapping error as a key source of instability in current methods. Bootstrapping error is due to bootstrapping from actions that lie outside of the training data distribution, and it accumulates via the Bellman backup operator.  

  :curly_loop: [Conservative Q-Learning for Offline Reinforcement Learning](https://arxiv.org/pdf/2006.04779.pdf) :+1: :fire: :volcano: :sweat_drops:  ​ ​

  conservative Q-learning (CQL), which aims to address these limitations by learning a conservative Q-function such that the expected value of a policy under this Q-function lower-bounds its true value. 

  :curly_loop: [S4RL: Surprisingly Simple Self-Supervision for Offline Reinforcement Learning](https://arxiv.org/pdf/2103.06326.pdf) :no_mouth: 

   utilizes data augmentations from states to learn value functions that are better at generalizing and extrapolating when deployed in the environment. 

  :curly_loop: [Actionable Models: Unsupervised Offline Reinforcement Learning of Robotic Skills](https://arxiv.org/pdf/2104.07749.pdf) :+1: :fire: :boom: 

  learning a functional understanding of the environment by learning to reach any goal state in a given dataset. We employ goal-conditioned Qlearning with hindsight relabeling and develop several techniques that enable training in a particularly challenging offline setting. 

  :curly_loop: [Behavior Regularized Offline Reinforcement Learning](https://arxiv.org/pdf/1911.11361.pdf) :fire:  :boom: :+1: 

  we introduce a general framework, behavior regularized actor critic (BRAC), to empirically evaluate recently proposed methods as well as a number of simple baselines across a variety of offline continuous control tasks. 

  :curly_loop: [Offline-to-Online Reinforcement Learning via Balanced Replay and Pessimistic Q-Ensemble](https://arxiv.org/pdf/2107.00591.pdf) :no_mouth:  

  we observe that state-action distribution shift may lead to severe bootstrap error during fine-tuning, which destroys the good initial policy obtained via offline RL. 

  :curly_loop: [Offline Meta-Reinforcement Learning with Online Self-Supervision](https://arxiv.org/pdf/2107.03974.pdf) :+1: :fire: 

  Unlike the online setting, the adaptation and exploration strategies cannot effectively adapt to each other, resulting in poor performance. we propose a hybrid offline meta-RL algorithm, which uses offline data with rewards to meta-train an adaptive policy, and then collects additional unsupervised online data, without any ground truth reward labels, to bridge this distribution shift problem. 

  :curly_loop: [Offline Meta-Reinforcement Learning with Advantage Weighting](http://proceedings.mlr.press/v139/mitchell21a/mitchell21a.pdf) 

  :curly_loop: [AWAC: Accelerating Online Reinforcement Learning with Offline Datasets](https://arxiv.org/pdf/2006.09359.pdf) :+1: :fire: :volcano: 

  we systematically analyze why this problem (offline + online) is so challenging, and propose an algorithm that combines sampleefficient dynamic programming with maximum likelihood policy updates, providing a simple and effective framework that is able to leverage large amounts of offline data and then quickly perform online fine-tuning of RL policies. 

  

   ​ ​ ​

  

   ​ ​

  

  

  

   ​ ​

  

  

   ​

+    



<a name="anchor-pareto"></a> 

+ Pareto 

  :curly_loop: [Pareto Multi-Task Learning](https://arxiv.org/pdf/1912.12854.pdf) :boom: :boom: :fire: :droplet: 

  we proposed a novel Pareto Multi-Task Learning (Pareto MTL) algorithm to generate a set of well-distributed Pareto solutions with different trade-offs among tasks for a given multi-task learning (MTL) problem. 

  :curly_loop: [Efficient Continuous Pareto Exploration in Multi-Task Learning](https://arxiv.org/pdf/2006.16434.pdf) [zhihu](https://zhuanlan.zhihu.com/p/159000150) :boom: :fire: :+1:  ​ ​ ​

  :curly_loop: [Prediction-Guided Multi-Objective Reinforcement Learning for Continuous Robot Control](https://proceedings.icml.cc/static/paper_files/icml/2020/1114-Paper.pdf) :sweat_drops:  ​

  

+ BNN 

  :curly_loop: [Auto-Encoding Variational Bayes](https://www.ics.uci.edu/~welling/publications/papers/AEVB_ICLR14.pdf) :+1:  ​
  
  :curly_loop: [Unlabelled Data Improves Bayesian Uncertainty Calibration under Covariate Shift](http://proceedings.mlr.press/v119/chan20a/chan20a.pdf)  :+1: :fire: 
  
  we develop an approximate Bayesian inference scheme based on posterior regularisation, wherein unlabelled target data are used as “pseudo-labels” of model confidence that are used to regularise the model’s loss on labelled source data. 
  
  :curly_loop: [Understanding Uncertainty in Bayesian Deep Learning](https://arxiv.org/pdf/2106.13055.pdf) :sweat_drops:  ​





<a name="anchor-supervised"></a>  <a name="anchor-goalcon"></a>  

+ supervised RL & goal-conditioned policy 

  :curly_loop: [LEARNING TO REACH GOALS VIA ITERATED SUPERVISED LEARNING](https://openreview.net/pdf?id=rALA0Xo6yNJ) :no_mouth: iclr2020  iclr2021 

  an agent continually relabels and imitates the trajectories it generates to progressively learn goal-reaching behaviors from scratch. 

  :curly_loop: [Reward-Conditioned Policies](https://arxiv.org/pdf/1912.13465.pdf) :+1: :fire: conditioning on the reward rather than goal state 

  Non-expert trajectories collected from suboptimal policies can be viewed as optimal supervision, not for maximizing the reward, but for matching the reward of the given trajectory. 

  :curly_loop: [Search on the Replay Buffer: Bridging Planning and Reinforcement Learning](https://arxiv.org/pdf/1906.05253.pdf) :fire: :+1:  ​ ​

  combines the strengths of planning and reinforcement learning 

  :curly_loop: [DYNAMICAL DISTANCE LEARNING FOR SEMI-SUPERVISED AND UNSUPERVISED SKILL DISCOVERY](https://arxiv.org/pdf/1907.08225.pdf) 

  dynamical distances: a measure of the expected number of time steps to reach a given goal state from any other states 

  :curly_loop: [Contextual Imagined Goals for Self-Supervised Robotic Learning](http://proceedings.mlr.press/v100/nair20a/nair20a.pdf) :+1: ​​  ​ ​

  using the context-conditioned generative model to set goals that are appropriate to the current scene. 

  :curly_loop: [Reverse Curriculum Generation for Reinforcement Learning](https://arxiv.org/pdf/1707.05300.pdf) :+1: :fire:  ​ 

  **Finding the optimal start-state distribution**. Our method automatically generates a curriculum of start states that adapts to the agent’s performance, leading to efficient training on goal-oriented tasks. 

  :curly_loop: [Goal-Aware Prediction: Learning to Model What Matters](https://proceedings.icml.cc/static/paper_files/icml/2020/2981-Paper.pdf) :+1: :fire: :boom: Introduction is good! 

  we propose to direct prediction towards task relevant information, enabling the model to be aware of the current task and **encouraging it to only model relevant quantities of the state space**, resulting in **a learning objective that more closely matches the downstream task**.  

  :curly_loop: [C-LEARNING: LEARNING TO ACHIEVE GOALS VIA RECURSIVE CLASSIFICATION](https://openreview.net/pdf?id=tc5qisoB-C) :+1: :sweat_drops: :volcano: :boom:   

  This Q-function is not useful for predicting or controlling the future state distribution. Fundamentally, this problem arises because the relationship between the reward function, the Q function, and the future state distribution in prior work remains unclear.  :ghost: [DIAYN?] 

  on-policy ---> off-policy ---> goal-conditioned. 

  :curly_loop: [LEARNING TO UNDERSTAND GOAL SPECIFICATIONS BY MODELLING REWARD](https://openreview.net/pdf?id=H1xsSjC9Ym) :+1: :+1:  ​

  *ADVERSARIAL GOAL-INDUCED LEARNING FROM EXAMPLES* 

  A framework within which instruction-conditional RL agents are trained using rewards obtained not from the environment, but from reward models which are jointly trained from expert examples. 

  :curly_loop: [Intrinsically Motivated Goal-Conditioned Reinforcement Learning: a Short Survey](https://arxiv.org/pdf/2012.09830.pdf) :volcano: :volcano: :droplet: 

  This paper proposes a typology of these methods **[intrinsically motivated processes (IMP) (knowledge-based IMG + competence-based IMP); goal-conditioned RL agents]** at the intersection of deep rl and developmental approaches, surveys recent approaches and discusses future avenues.    

  SEE: Language as a Cognitive Tool to Imagine Goals in Curiosity-Driven Exploration  

  :curly_loop: [Self-supervised Learning of Distance Functions for Goal-Conditioned Reinforcement Learning](https://arxiv.org/pdf/1907.02998.pdf) 

  :curly_loop: [PARROT: DATA-DRIVEN BEHAVIORAL PRIORS FOR REINFORCEMENT LEARNING](https://openreview.net/pdf?id=Ysuv-WOFeKR) :+1: 

  We propose a method for pre-training behavioral priors that can capture complex input-output relationships observed in successful trials from a wide range of previously seen tasks. 

   :ghost: see model-based <a href="#anchor-modelbasedddl">ddl</a>  

  :curly_loop: [LEARNING WHAT TO DO BY SIMULATING THE PAST](https://openreview.net/pdf?id=kBVJ2NtiY-) :+1:  ​
  
  we propose the Deep Reward Learning by Simulating the Past (Deep RLSP) algorithm. 
  
  :curly_loop: [Weakly-Supervised Reinforcement Learning for Controllable Behavior](https://arxiv.org/pdf/2004.02860.pdf) :+1: 
  
  two phase approach that learns a disentangled representation, and then uses it to guide exploration, propose goals, and inform a distance metric. 
  
  :curly_loop: [Replacing Rewards with Examples: Example-Based Policy Search via Recursive Classification](https://arxiv.org/pdf/2103.12656.pdf) :volcano: :boom: 
  
  we derive a method based on recursive classification that eschews auxiliary reward functions and instead directly learns a value function from transitions and successful outcomes. 
  
  :curly_loop: [Outcome-Driven Reinforcement Learning via Variational Inference](https://arxiv.org/pdf/2104.10190.pdf) :+1: :fire: :droplet: 
  
  by framing the problem of achieving desired outcomes as variational inference, we can derive an off-policy RL algorithm, a reward function learnable from environment interactions, and a novel Bellman backup that contains a state–action dependent dynamic discount factor for the reward and bootstrap. 
  
  :curly_loop: [Discovering Diverse Solutions in Deep Reinforcement Learning](https://arxiv.org/pdf/2103.07084.pdf) :+1:  ​
  
  learn infinitely many solutions by training a policy conditioned on a continuous or discrete low-dimensional latent variable. 
  
  :curly_loop: [Goal-Conditioned Reinforcement Learning with Imagined Subgoals](https://arxiv.org/pdf/2107.00541.pdf) :+1: :fire: :volcano:  ​ ​ ​
  
  This high-level policy predicts intermediate states halfway to the goal using the value function as a reachability metric. We don’t require the policy to reach these subgoals explicitly. Instead, we use them to define a prior policy, and incorporate this prior into a KL-constrained pi scheme to speed up and reg. 
  
  :curly_loop: [Discovering Generalizable Skills via Automated Generation of Diverse Tasks](https://arxiv.org/pdf/2106.13935.pdf) :no_mouth: 
  
  As opposed to prior work on unsupervised discovery of skills which incentivizes the skills to produce different outcomes in the same environment, our method pairs each skill with a unique task produced by a trainable task generator. Procedural content generation (PCG). 
  
   ​
  
  
  
  
  
  
  
  




<a name="anchor-selfpaced"></a>   <a name="anchor-curriculum"></a> 

+ self-paced & curriculum RL 

  :curly_loop: [Self-Paced Contextual Reinforcement Learning](https://arxiv.org/pdf/1910.02826.pdf) :volcano: :sweat_drops:  ​ ​

  We introduce a novel relative entropy reinforcement learning algorithm that gives the agent the freedom to control the intermediate task distribution, allowing for its gradual progression towards the target context distribution.  

  :curly_loop: [Self-Paced Deep Reinforcement Learning](https://arxiv.org/pdf/2004.11812.pdf) :volcano: :sweat_drops:  ​ ​

  In this paper, we propose an answer by interpreting the curriculum generation as an inference problem, where distributions over tasks are progressively learned to approach the target task. This approach leads to an automatic curriculum generation, whose pace is controlled by the agent, with solid theoretical motivation and easily integrated with deep RL algorithms. 

  :curly_loop:[Learning with AMIGO: Adversarially Motivated Intrinsic Goals](https://arxiv.org/pdf/2006.12122.pdf) :+1:   [Lil'Log-Curriculum](https://lilianweng.github.io/lil-log/2020/01/29/curriculum-for-reinforcement-learning.html) :+1:  ​

  **related work (curriculum) is quite good!**   (Intrinsic motivation + Curriculum learning) 





<a name="anchor-modelbasedrl"></a>  

+ Model-based RL & world models 

  :curly_loop: [Learning Latent Dynamics for Planning from Pixels](http://proceedings.mlr.press/v97/hafner19a/hafner19a.pdf) ​​ :sweat_drops: :sweat_drops:  ​

  :curly_loop: [DREAM TO CONTROL: LEARNING BEHAVIORS BY LATENT IMAGINATION](https://arxiv.org/pdf/1912.01603.pdf) :sweat_drops:  ​

  :curly_loop: [Model-based Policy Optimization with Unsupervised Model Adaptation](https://arxiv.org/pdf/2010.09546.pdf) 

  :curly_loop: [CONTRASTIVE LEARNING OF STRUCTURED WORLD MODELS](https://arxiv.org/pdf/1911.12247.pdf) :fire: :volcano:  ​ ​

  :curly_loop: [Learning Predictive Models From Observation and Interaction](https://arxiv.org/pdf/1912.12773.pdf) :fire:  ​related work is good! 

  By combining interaction and observation data, our model is able to learn to generate predictions for complex tasks and new environments without costly expert demonstrations.  

  :curly_loop: [medium](https://jonathan-hui.medium.com/rl-model-based-reinforcement-learning-3c2b6f0aa323)   [Tutorial on Model-Based Methods in Reinforcement Learning (icml2020)](https://sites.google.com/view/mbrl-tutorial)  :sweat_drops:  ​

  [rail](http://rail.eecs.berkeley.edu/deeprlcourse-fa17/f17docs/lecture_9_model_based_rl.pdf)  [Model-Based Reinforcement Learning: Theory and Practice](https://bair.berkeley.edu/blog/2019/12/12/mbpo/) :sweat_drops: ​​  ​ ​

  :curly_loop: [What can I do here? A Theory of Affordances in Reinforcement Learning](http://proceedings.mlr.press/v119/khetarpal20a/khetarpal20a.pdf) :+1: :droplet:   

  “affordances” to describe the fact that certain states enable an agent to do certain actions, in the context of embodied agents. In this paper, we develop a theory of affordances for agents who learn and plan in Markov Decision Processes. 

  :curly_loop: [When to Trust Your Model: Model-Based Policy Optimization](https://arxiv.org/pdf/1906.08253.pdf) :fire: :volcano: :droplet: :boom:  ​

   we study the role of model usage in policy optimization both theoretically and empirically. 

  :curly_loop: [Deployment-Efficient Reinforcement Learning via Model-Based Offline Optimization](https://arxiv.org/pdf/2006.03647.pdf) :fire:  :volcano: :boom: 
  
  we propose a novel concept of deployment efficiency, measuring the number of distinct data-collection policies that are used during policy learning.  ​
  
  :curly_loop: [CONTROL-AWARE REPRESENTATIONS FOR MODELBASED REINFORCEMENT LEARNING](https://openreview.net/pdf?id=dgd4EJqsbW5) :sweat_drops: 
  
  :curly_loop: [Context-aware Dynamics Model for Generalization in Model-Based Reinforcement Learning](https://arxiv.org/pdf/2005.06800.pdf) :+1: :fire:  ​ ​
  
   The intuition is that the true context of the underlying MDP can be captured from recent experiences. 
  
  :curly_loop: [Optimism is All You Need: Model-Based Imitation Learning From Observation Alone](https://arxiv.org/pdf/2102.10769.pdf) :sweat_drops:  ​
  
  :curly_loop: [PlanGAN: Model-based Planning With Sparse Rewards and Multiple Goals](https://proceedings.neurips.cc/paper/2020/file/6101903146e4bbf4999c449d78441606-Paper.pdf) :+1: 
  
  train an ensemble of conditional generative models (GANs) to generate plausible trajectories that lead the agent from its current state towards a specified goal. We then combine these imagined trajectories into a novel planning algorithm in order to achieve the desired goal as efficiently as possible.  
  
  :curly_loop: [MODEL-ENSEMBLE TRUST-REGION POLICY OPTIMIZATION](https://arxiv.org/pdf/1802.10592.pdf) :+1:  
  
  we propose to use an ensemble of models to maintain the model uncertainty and regularize the learning process. 
  
  :curly_loop: [Sample Efficient Reinforcement Learning via Model-Ensemble Exploration and Exploitation](https://arxiv.org/pdf/2107.01825.pdf) :no_mouth: 
  
  MEEE, a model-ensemble method that consists of optimistic exploration and weighted exploitation.  
  
  
  
   ​
  
  
  
  
  
  :o: dynamic distance learning   <a name="anchor-modelbasedddl"></a>  
  
  :curly_loop: [MODEL-BASED VISUAL PLANNING WITH SELF-SUPERVISED FUNCTIONAL DISTANCES](https://openreview.net/pdf?id=UcoXdfrORC) :+1: 
  
   We present a self-supervised method for model-based visual goal reaching, which uses both a visual dynamics model as well as a dynamical distance function learned using model-free rl. Related work! 
  
  :o: model-based offline 
  
  :curly_loop: [Representation Balancing MDPs for Off-Policy Policy Evaluation](https://arxiv.org/pdf/1805.09044.pdf) :droplet:  ​
  
  :curly_loop: [REPRESENTATION BALANCING OFFLINE MODEL-BASED REINFORCEMENT LEARNING](https://openreview.net/pdf?id=QpNz8r_Ri2Y) :droplet:  ​
  
  



<a name="anchor-trainingrl"></a>  

+ Training RL & Just Fast & Embedding? & OPE(DICE) 

  :curly_loop: [Leave no Trace: Learning to Reset for Safe and Autonomous Reinforcement Learning](https://arxiv.org/pdf/1711.06782.pdf) :no_mouth:  ​

  :curly_loop: [Predictive Information Accelerates Learning in RL](https://arxiv.org/pdf/2007.12401.pdf) :+1:  ​

  We train Soft Actor-Critic (SAC) agents from pixels with an auxiliary task that learns a compressed representation of the predictive information of the RL environment dynamics using a contrastive version of the Conditional Entropy Bottleneck (CEB) objective. 

  :curly_loop: [Speeding up Reinforcement Learning with Learned Models](https://upcommons.upc.edu/bitstream/handle/2117/175740/143210.pdf) :sweat_drops:  ​

  :curly_loop: [DYNAMICS-AWARE EMBEDDINGS](https://arxiv.org/pdf/1908.09357.pdf) :+1:  ​

  A forward prediction objective for simultaneously learning embeddings of states and action sequences. 

  :curly_loop: [DIVIDE-AND-CONQUER REINFORCEMENT LEARNING](https://arxiv.org/pdf/1711.09874.pdf) :+1: 

  we develop a novel algorithm that instead partitions the initial state space into “slices”, and optimizes an ensemble of policies, each on a different slice. 

  :curly_loop:  [Continual Learning of Control Primitives: Skill Discovery via Reset-Games](https://arxiv.org/pdf/2011.05286.pdf) :+1: :fire:  

  We do this by exploiting the insight that the need to “reset" an agent to a broad set of initial states for a learning task provides a natural setting to learn a diverse set of “reset-skills".  

  :curly_loop: [DIFFERENTIABLE TRUST REGION LAYERS FOR DEEP REINFORCEMENT LEARNING](https://openreview.net/pdf?id=qYZD-AO1Vn) :+1: :droplet: 

  We derive trust region projections based on the Kullback-Leibler divergence, the Wasserstein L2 distance, and the Frobenius norm for Gaussian distributions. Related work is good! 

  :curly_loop: [BENCHMARKS FOR DEEP OFF-POLICY EVALUATION](https://openreview.net/pdf?id=kWSeGEeHvF8)  :+1: :fire: :droplet: 

  DOPE is designed to measure the performance of **OPE** methods by 1) evaluating on challenging control tasks with properties known to be difficult for OPE methods, but which occur in real-world scenarios, 2) evaluating across a range of policies with different values, to directly measure performance on policy evaluation, ranking and selection, and 3) evaluating in ideal and adversarial settings in terms of dataset coverage and support.  

  :curly_loop: [Trajectory-Based Off-Policy Deep Reinforcement Learning](https://arxiv.org/pdf/1905.05710.pdf) :+1: :fire: :droplet:  ​

  Incorporation of previous rollouts via importance sampling greatly improves data-efficiency, whilst stochastic optimization schemes facilitate the escape from local optima.  

  :curly_loop: [DualDICE: Behavior-Agnostic Estimation of Discounted Stationary Distribution Corrections](https://arxiv.org/pdf/1906.04733.pdf) :fire: :volcano: :boom: 
  
  Off-Policy Policy Evaluation (OPE) --->  Learning Stationary Distribution Corrections ---> Off-Policy Estimation with Multiple Unknown Behavior Policies. , DualDICE, for estimating the discounted stationary distribution corrections. 
  
  :curly_loop: [AlgaeDICE: Policy Gradient from Arbitrary Experience](https://arxiv.org/pdf/1912.02074.pdf) :+1: :volcano: :droplet:  ​ ​ ​
  
  We introduce a new formulation of max-return optimization that allows the problem to be re-expressed by an expectation over an arbitrary behavior-agnostic and off-policy data distribution. ALgorithm for policy Gradient from Arbitrary Experience via DICE (AlgaeDICE). 
  
  :curly_loop: [GENDICE: GENERALIZED OFFLINE ESTIMATION OF STATIONARY VALUES](https://arxiv.org/pdf/2002.09072.pdf) :+1: :fire: :fire: ​​ ​ ​
  
  Our approach is based on estimating a ratio that corrects for the discrepancy between the stationary and empirical distributions, derived from fundamental properties of the stationary distribution, and exploiting constraint reformulations based on variational divergence minimization. 
  
  :curly_loop: [GradientDICE: Rethinking Generalized Offline Estimation of Stationary Values](http://proceedings.mlr.press/v119/zhang20r/zhang20r.pdf) :confused:  ​
  
  :curly_loop: [Breaking the Curse of Horizon: Infinite-Horizon Off-Policy Estimation](https://papers.nips.cc/paper/2018/file/dda04f9d634145a9c68d5dfe53b21272-Paper.pdf) :+1: :fire: :droplet:  ​
  
  The key idea is to apply importance sampling on the average visitation distribution of single steps of state-action pairs, instead of the much higher dimensional distribution of whole trajectories.   
  
  :curly_loop: [Off-Policy Evaluation via the Regularized Lagrangian](https://arxiv.org/pdf/2007.03438.pdf) :fire: :confused: :droplet:  ​
  
  we unify these estimators (DICE) as regularized Lagrangians of the same linear program. 
  
  :curly_loop: [Minimax Weight and Q-Function Learning for Off-Policy Evaluation](http://proceedings.mlr.press/v119/uehara20a/uehara20a.pdf) :fire: :droplet:  ​ ​
  
  Minimax Weight Learning (MWL); Minimax Q-Function Learning. Doubly Robust Extension and Sample Complexity of MWL & MQL. 
  
  :curly_loop: [Minimax Value Interval for Off-Policy Evaluation and Policy Optimization](https://arxiv.org/pdf/2002.02081.pdf) :+1: :fire: :volcano: :droplet: 
  
  we derive the minimax value intervals by slightly altering the derivation of two recent methods [1], one of “weight-learning” style (Sec. 4.1) and one of “value-learning” style (Sec. 4.2), and show that under certain conditions, they merge into a single unified value interval whose validity only relies on either Q or W being well-specified (Sec. 4.3).  
  
  :curly_loop: [Reinforcement Learning via Fenchel-Rockafellar Duality](https://arxiv.org/pdf/2001.01866.pdf) :fire: :volcano: :droplet:  ​ ​ ​
  
  *Policy Evaluation*: LP form of Q ---> policy evaluation via largrangian ---> change the problem before applying duality (constant function, f-divergence, fenchel-rockafellar duality);  *Policy Optimization*: policy gradient ---> offline policy gradient via the lagrangian ---> fenchel-rockafellar duality for the regularized optimization (regularization with the kl-d) ---> imitation learning;  *RL with the LP form of V*: max-likelihood policy learning ---> policy evaluation with the V-lp; *Undiscounted Settings* 
  
  :curly_loop: [ADVANTAGE-WEIGHTED REGRESSION: SIMPLE AND SCALABLE OFF-POLICY REINFORCEMENT LEARNING](https://arxiv.org/pdf/1910.00177.pdf) :+1: :fire:  :boom: 
  
  Our proposed approach, which we refer to as advantage-weighted regression (AWR), consists of two standard supervised learning steps: one to regress onto target values for a value function, and another to regress onto weighted target actions for the policy. 
  
   ​ ​
  
  
  
  
  
  :curly_loop: [PARAMETER-BASED VALUE FUNCTIONS](https://openreview.net/pdf?id=tV6oBfuyLTQ) :+1:  ​
  
  Parameter-Based Value Functions (PBVFs) whose inputs include the policy parameters. 
  
  :curly_loop: [Reinforcement Learning without Ground-Truth State](https://arxiv.org/pdf/1905.07866.pdf) :+1: 
  
  relabeling the original goal with the achieved goal to obtain positive rewards  
  
  :curly_loop: [Ecological Reinforcement Learning](https://arxiv.org/pdf/2006.12478.pdf) :+1: 
  
  :curly_loop: [Control Frequency Adaptation via Action Persistence in Batch Reinforcement Learning](https://icml.cc/virtual/2020/poster/6146) :+1:   ​
  
  :curly_loop: [Taylor Expansion Policy Optimization](http://proceedings.mlr.press/v119/tang20d/tang20d.pdf) :+1: :boom: :volcano: :droplet:  ​
  
  a policy optimization formalism that generalizes prior work (e.g., TRPO) as a firstorder special case. We also show that Taylor expansions intimately relate to off-policy evaluation. 
  
  :curly_loop: [Policy Information Capacity: Information-Theoretic Measure for Task Complexity in Deep Reinforcement Learning](https://arxiv.org/pdf/2103.12726.pdf) :+1:  ​
  
  Policy Information Capacity: Information-Theoretic Measure for Task Complexity in Deep Reinforcement Learning. 
  
  :curly_loop: [Deep Reinforcement Learning with Robust and Smooth Policy](http://proceedings.mlr.press/v119/shen20b/shen20b.pdf) :+1:  
  
  the policy is trained with smoothness-inducing regularization. Such regularization effectively constrains the search space, and enforces smoothness in the learned policy. 
  
  :curly_loop: [If MaxEnt RL is the Answer, What is the Question? ](https://arxiv.org/pdf/1910.01913.pdf) :+1:  
  
  :curly_loop: [Maximum Entropy RL (Provably) Solves Some Robust RL Problems](https://arxiv.org/pdf/2103.06257.pdf) 
  
  
  
  
  
  
  
  :curly_loop: [Regularized Policies are Reward Robust](http://proceedings.mlr.press/v130/husain21a/husain21a.pdf) :fire: :droplet:  ​
  
  we find that the optimal policy found by a regularized objective is precisely an optimal policy of a reinforcement learning problem under a worst-case adversarial reward. 
  
  :curly_loop: [Reinforcement Learning as One Big Sequence Modeling Problem](https://people.eecs.berkeley.edu/~janner/trajectory-transformer/files/trajectory-transformer.pdf) :+1: :fire: :droplet:  ​ ​ ​
  
  Addressing RL as a sequence modeling problem significantly simplifies a range of design decisions: we no longer require separate behavior policy constraints, as is common in prior work on offline model-free RL, and we no longer require ensembles or other epistemic uncertainty estimators, as is common in prior work on model-based RL. 
  
  :curly_loop: [On-Policy Deep Reinforcement Learning for the Average-Reward Criterion](https://arxiv.org/pdf/2106.07329.pdf) :+1: :fire: 
  
  By addressing the average-reward criterion directly, we then derive a novel bound which depends on the average divergence between the two policies and Kemeny’s constant. 
  
  :curly_loop: [Average-Reward Reinforcement Learning with Trust Region Methods](https://arxiv.org/pdf/2106.03442.pdf) :+1:  :fire: 
  
  Firstly, we develop a unified trust region theory with discounted and average criteria. With the average criterion, a novel performance bound within the trust region is derived with the Perturbation Analysis (PA) theory. Secondly, we propose a practical algorithm named Average Policy Optimization (APO), which improves the value estimation with a novel technique named Average Value Constraint. 
  
  :curly_loop: [Trust Region Policy Optimization](https://arxiv.org/pdf/1502.05477.pdf) :+1:  :fire: :boom:  ​ ​
  
  :curly_loop: [Benchmarking Deep Reinforcement Learning for Continuous Control](https://arxiv.org/pdf/1604.06778.pdf) :+1: :fire:  ​ ​
  
  :curly_loop: [P3O: Policy-on Policy-off Policy Optimization](http://proceedings.mlr.press/v115/fakoor20a/fakoor20a.pdf) :fire: 
  
  This paper develops a simple alg. named P3O that interleaves offpolicy updates with on-policy updates.  
  
  
  
  
  
  
  
   ​ ​ ​
  
  
  
   ​ ​
  
  
  
   ​
  
   ​
  
   ​ ​
  
  
  
  
  
  
  
   ​
  
  



<a name="anchor-irl"></a>   

:volcano: IRL 

+ [Inverse RL & Apprenticeship Learning](https://thegradient.pub/learning-from-humans-what-is-inverse-reinforcement-learning/#:~:text=Inverse%20reinforcement%20learning%20(IRL)%2C,the%20task%20of%20autonomous%20driving.), PPT-levine([1](http://rail.eecs.berkeley.edu/deeprlcourse-fa17/f17docs/lecture_12_irl.pdf):+1: [2](https://people.eecs.berkeley.edu/~pabbeel/cs287-fa12/slides/inverseRL.pdf)), Medium([1](https://towardsdatascience.com/inverse-reinforcement-learning-6453b7cdc90d) [2](https://medium.com/@jonathan_hui/rl-inverse-reinforcement-learning-56c739acfb5a)), 

  :curly_loop: [Apprenticeship Learning via Inverse Reinforcement Learning](http://people.eecs.berkeley.edu/~russell/classes/cs294/s11/readings/Abbeel+Ng:2004.pdf) :+1:   [Maximum Entropy Inverse Reinforcement Learning](https://www.aaai.org/Papers/AAAI/2008/AAAI08-227.pdf)   [Maximum Entropy Deep Inverse Reinforcement Learning](https://arxiv.org/pdf/1507.04888.pdf)   

  :curly_loop:  [Guided Cost Learning: Deep Inverse Optimal Control via Policy Optimization](https://arxiv.org/pdf/1603.00448.pdf) :fire: :+1:  

  :curly_loop: [A Connection Between Generative Adversarial Networks, Inverse Reinforcement Learning, and Energy-Based Models](https://arxiv.org/pdf/1611.03852.pdf) :volcano: :sweat_drops: :sweat_drops:   [zhihu](https://zhuanlan.zhihu.com/p/72691529) :+1:  ​

  :curly_loop: [Generative Adversarial Imitation Learning](https://arxiv.org/pdf/1606.03476.pdf) :fire: :volcano: :boom: :sweat_drops:  [zhihu](https://zhuanlan.zhihu.com/p/60327435) :droplet:  ​

  IRL is a dual of an occupancy measure matching problem; The induced optimal policy is the primal optimum. 

  :curly_loop: [LEARNING ROBUST REWARDS WITH ADVERSARIAL INVERSE REINFORCEMENT LEARNING](https://arxiv.org/pdf/1710.11248.pdf) :fire::volcano: :boom: :sweat_drops: 

  Part of the challenge is that IRL is an ill-defined problem, since there are many optimal policies that can explain a set of demonstrations, and many rewards that can explain an optimal policy. The maximum entropy (MaxEnt) IRL framework introduced by Ziebart et al. (2008) handles the former ambiguity, but the latter ambiguity means that IRL algorithms have difficulty distinguishing **the true reward functions from those shaped by the environment dynamics** (THE REWARD AMBIGUITY PROBLEM).  -- **DISENTANGLING REWARDS FROM DYNAMICS.** 

  :curly_loop: [ADVERSARIAL IMITATION VIA VARIATIONAL INVERSE REINFORCEMENT LEARNING](https://arxiv.org/pdf/1809.06404.pdf) :+1: :fire: :droplet: 

  Our method simultaneously learns empowerment through variational information maximization along with the reward and policy under the adversarial learning formulation.  

  :curly_loop: [A Divergence Minimization Perspective on Imitation Learning Methods](http://proceedings.mlr.press/v100/ghasemipour20a/ghasemipour20a.pdf) :sweat_drops: :+1: :volcano:  ​ ​

  State-Marginal Matching. we present a unified probabilistic perspective on IL algorithms based on divergence minimization. 

  :curly_loop: [f-IRL: Inverse Reinforcement Learning via State Marginal Matching](https://arxiv.org/pdf/2011.04709.pdf) :sweat_drops: 

  :curly_loop: [Imitation Learning as f-Divergence Minimization](https://arxiv.org/pdf/1905.12888.pdf) :sweat_drops:  ​

  :curly_loop: [Offline Imitation Learning with a Misspecified Simulator](https://proceedings.neurips.cc/paper/2020/file/60cb558c40e4f18479664069d9642d5a-Paper.pdf) :+1:  ​

  learn pi in the condition of a few expert demonstrations and a simulator with misspecified dynamics. 

  :curly_loop: [Inverse Constrained Reinforcement Learning](https://arxiv.org/pdf/2011.09999.pdf) :fire:  :boom:  

  The main task (“do this”) is often quite easy to encode in the form of a simple nominal reward function. In this work, we focus on learning the constraint part (“do not do that”) from provided expert demonstrations and using it in conjunction with the nominal reward function to train RL agents. 

  

  

  

   ​ 

  :curly_loop: [UNDERSTANDING THE RELATION BETWEEN MAXIMUM-ENTROPY INVERSE REINFORCEMENT LEARNING AND BEHAVIOUR CLONING](https://openreview.net/pdf?id=rkeXrIIt_4) 

  :curly_loop: [Disagreement-Regularized Imitation Learning](https://openreview.net/forum?id=rkgbYyHtwB) 

  :curly_loop: [Intrinsic Reward Driven Imitation Learning via Generative Model](https://arxiv.org/pdf/2006.15061.pdf) :+1: :fire: 

  Combines a backward action encoding and a forward dynamics model into one generative solution. Moreover, our model generates a family of intrinsic rewards, enabling the imitation agent to do samplingbased self-supervised exploration in the environment.  Outperform the expert.  

  :curly_loop: [REGULARIZED INVERSE REINFORCEMENT LEARNING](https://openreview.net/pdf?id=HgLO8yalfwc) :sweat_drops: 

  :curly_loop: [Variational Inverse Control with Events: A General Framework for Data-Driven Reward Definition](https://proceedings.neurips.cc/paper/2018/file/c9319967c038f9b923068dabdf60cfe3-Paper.pdf) :volcano: variational inverse control with events (**VICE**), which generalizes inverse reinforcement learning methods  :volcano: :droplet:  ​ ​

  :curly_loop: [Meta-Inverse Reinforcement Learning with Probabilistic Context Variables](https://arxiv.org/pdf/1909.09314.pdf) :droplet: 

  we propose a deep latent variable model that is capable of learning rewards from demonstrations of distinct but related tasks in an unsupervised way. Critically, our model can infer rewards for new, structurally-similar tasks from a single demonstration.  

  :curly_loop: [Domain Adaptive Imitation Learning](https://arxiv.org/pdf/1910.00105.pdf) :fire: :+1: :volcano: 

  In the alignment step we execute a novel unsupervised MDP alignment algorithm, GAMA, to learn state and action correspondences from unpaired, unaligned demonstrations. In the adaptation step we leverage the correspondences to zero-shot imitate tasks across domains. 

  :curly_loop: [ADAIL: Adaptive Adversarial Imitation Learning](https://arxiv.org/pdf/2008.12647.pdf) :+1: :fire: :volcano: 

  the discriminator may either simply **use the embodiment or dynamics to infer whether it is evaluating expert behavior**, and as a consequence fails to provide a meaningful reward signal. we condition our policy on a learned dynamics embedding and we employ a domain-adversarial loss to learn a dynamics-invariant discriminator.   

  :curly_loop: [Generative Adversarial Imitation from Observation](https://arxiv.org/pdf/1807.06158.pdf) :sweat_drops: :+1: :fire: :volcano:  ​ ​ ​

  From a high-level perspective, in imitation from observation, the goal is to enable the agent to extract what the task is by observing some state sequences.  GAIfO 

  :curly_loop: [An Imitation from Observation Approach to Transfer Learning with Dynamics Mismatch](https://papers.nips.cc/paper/2020/file/28f248e9279ac845995c4e9f8af35c2b-Paper.pdf) :+1: :fire: :volcano:  ​

  learning the grounded action transformation can be seen as an IfO problem; GARAT: learn an action transformation policy for transfer learning with dynamics mismatch.     we focus on the paradigm of simulator grounding, which modifies the source environment’s dynamics to more closely match the target environment dynamics using a relatively small amount of target environment data. 

  :curly_loop: [STATE ALIGNMENT-BASED IMITATION LEARNING](https://openreview.net/pdf?id=rylrdxHFDr) :+1: :fire:  ​

  Consider an imitation learning problem that the imitator and the expert have different dynamics models. The state alignment comes from both local and global perspectives and we combine them into a reinforcement learning framework by a regularized policy update objective. ifo 

  :curly_loop: [Strictly Batch Imitation Learning by Energy-based Distribution Matching](https://proceedings.neurips.cc//paper/2020/file/524f141e189d2a00968c3d48cadd4159-Paper.pdf) :fire: :boom: :sweat_drops:  ​

   ​By identifying parameterizations of the (discriminative) model of a policy with the (generative) energy function for state distributions, EDM yields a simple but effective solution that equivalently minimizes a divergence between the occupancy measure for the demonstrator and a model thereof for the imitator. 

  :curly_loop: [SQIL: Imitation Learning via Reinforcement Learning with Sparse Rewards](https://arxiv.org/pdf/1905.11108.pdf) :+1: :fire: :volcano:  ​

  SQIL is equivalent to a variant of behavioral cloning (BC) that uses regularization to overcome state distribution shift. 

  :curly_loop: [IQ-Learn: Inverse soft-Q Learning for Imitation](https://arxiv.org/pdf/2106.12142.pdf) :+1: :fire: :volcano: :droplet: 

  We introduce a method for dynamics-aware IL which avoids adversarial training by learning a single Q-function, implicitly representing both reward and policy.  

  :curly_loop: [Boosted and Reward-regularized Classification for Apprenticeship Learning](https://www.cristal.univ-lille.fr/~pietquin/pdf/AAMAS_2014_BPMGOP.pdf) :fire:  ​ ​

  MultiClass Classification and the Large Margin Approach. 

  :curly_loop: [IMITATION LEARNING VIA OFF-POLICY DISTRIBUTION MATCHING](https://arxiv.org/pdf/1912.05032.pdf) :+1: :fire: :boom:  :volcano:  ​

  These prior distribution matching approaches possess two limitations (On-policy; Separate RL optimization).  ---> OFF-POLICY FORMULATION OF THE KL-DIVERGENCE. ---> VALUEDICE: IMITATION LEARNING WITH IMPLICIT REWARDS. (OPE) 

  :curly_loop: [Imitation Learning from Observations by Minimizing Inverse Dynamics Disagreement](https://papers.nips.cc/paper/2019/file/ed3d2c21991e3bef5e069713af9fa6ca-Paper.pdf) :+1: :fire: :boom:  ​

  the gap between LfD and LfO actually lies in the disagreement of inverse dynamics models between the imitator and the expert, if following the modeling approach of GAIL.  ifo  IDDM 

  :curly_loop: [Off-Policy Imitation Learning from Observations](https://arxiv.org/pdf/2102.13185.pdf) :volcano: :sweat_drops: :fire:  :boom:  ​

  OPOLO (Off POlicy Learning from Observations)!  ifo // lfo  // ope // mode-covering (Forward Distribution Matching) // mode-seeking // dice // LfD // LfO  ​

+ Adding Noise 

  :curly_loop: [Learning from Suboptimal Demonstration via Self-Supervised Reward Regression](https://arxiv.org/pdf/2010.11723.pdf) :+1: :fire:  

  Recent attempts to learn from sub-optimal demonstration leverage pairwise rankings and following the Luce-Shepard rule. However, we show these approaches make incorrect assumptions and thus suffer from brittle, degraded performance. We overcome these limitations in developing a novel approach that **bootstraps off suboptimal demonstrations to synthesize optimality-parameterized data** to train an idealized reward function.  
  
  :curly_loop: [Robust Imitation Learning from Noisy Demonstrations](https://arxiv.org/pdf/2010.10181.pdf) :fire:  :volcano: 
  
  In this paper, we first theoretically show that robust imitation learning can be achieved by optimizing a classification risk with a symmetric loss. Based on this theoretical finding, we then propose a new imitation learning method that optimizes the classification risk by effectively combining pseudo-labeling with co-training. 
  
  :curly_loop: [Imitation Learning from Imperfect Demonstration](http://proceedings.mlr.press/v97/wu19a/wu19a.pdf) :fire: :volcano: :+1:  ​
  
  a novel approach that utilizes confidence scores, which describe the quality of demonstrations. two-step importance weighting imitation learning (2IWIL) and generative adversarial imitation learning with imperfect demonstration and confidence (IC-GAIL), based on the idea of reweighting. 
  
  :curly_loop: [Variational Imitation Learning with Diverse-quality Demonstrations](http://proceedings.mlr.press/v119/tangkaratt20a/tangkaratt20a.pdf) :fire: :droplet: 
  
  We show that simple quality-estimation approaches might fail due to compounding error, and fix this issue by jointly estimating both the quality and reward using a variational approach. 
  
   ​ ​
  
   ​




+ Goal-relabeling & Self-imitation 

  :curly_loop: [Rewriting History with Inverse RL: Hindsight Inference for Policy Improvement](https://arxiv.org/pdf/2002.11089v1.pdf) 

  MaxEnt RL and MaxEnt inverse RL optimize **the same multi-task RL objective** with respect to trajectories and tasks, respectively. 

  :curly_loop: [Hindsight](https://zhuanlan.zhihu.com/p/191639584)    [Curriculum-guided Hindsight Experience Replay](https://papers.nips.cc/paper/9425-curriculum-guided-hindsight-experience-replay.pdf)    [COMPETITIVE EXPERIENCE REPLAY](https://arxiv.org/pdf/1902.00528.pdf)    [Energy-Based Hindsight Experience Prioritization](https://arxiv.org/pdf/1810.01363.pdf)    [DHER: HINDSIGHT EXPERIENCE REPLAY FOR DYNAMIC GOALS](https://openreview.net/pdf?id=Byf5-30qFX)    
  
  :curly_loop: [Exploration via Hindsight Goal Generation](http://papers.nips.cc/paper/9502-exploration-via-hindsight-goal-generation.pdf) :+1:  :fire:  ​
  
  a novel algorithmic framework that generates valuable hindsight goals which are easy for an agent to achieve in the short term and are also potential for guiding the agent to reach the actual goal in the long term.  
  
  :curly_loop: [CURIOUS: Intrinsically Motivated Modular Multi-Goal Reinforcement Learning](https://arxiv.org/pdf/1810.06284.pdf) :+1:  ​
  
  This paper proposes CURIOUS, an algorithm that leverages 1) a modular Universal Value Function Approximator with hindsight learning to achieve a diversity of goals of different kinds within a unique policy and 2) an automated curriculum learning mechanism that biases the attention of the agent towards goals maximizing the absolute learning progress.  
  
  :curly_loop: [Hindsight Generative Adversarial Imitation Learning](https://arxiv.org/pdf/1903.07854.pdf) :fire: 
  
  achieving imitation learning satisfying no need of demonstrations.  [see self-imitation learning] 
  
  :curly_loop: [MHER: Model-based Hindsight Experience Replay](https://arxiv.org/pdf/2107.00306.pdf) :+1: 
  
  Replacing original goals with virtual goals generated from interaction with a trained dynamics model. 
  
  :curly_loop: [Policy Continuation with Hindsight Inverse Dynamics](https://papers.nips.cc/paper/2019/file/3891b14b5d8cce2fdd8dcdb4ded28f6d-Paper.pdf) :+1: :fire:  ​ ​
  
  This approach learns from Hindsight Inverse Dynamics based on Hindsight Experience Replay.  
  
  
  
   ​
  
   ​
  
+ Imitation Learning (See Upper) 

  :curly_loop: [To Follow or not to Follow: Selective Imitation Learning from Observations](https://arxiv.org/pdf/1912.07670.pdf) :+1:  ​

  imitating every step in the demonstration often becomes infeasible when the learner and its environment are different from the demonstration. 

+ reward function 

  :curly_loop: [QUANTIFYING DIFFERENCES IN REWARD FUNCTIONS](https://openreview.net/pdf?id=LwEQnp6CYev) :volcano: :sweat_drops:  ​ ​

  we introduce the Equivalent-Policy Invariant Comparison (EPIC) distance to quantify the difference between two reward functions directly, **without training a policy**. We prove EPIC is invariant on an equivalence class of reward functions that always induce the same optimal policy. 



<a name="anchor-marl"></a>   

:volcano: MARL 

+ MARL https://cloud.tencent.com/developer/article/1618396 

+ A Survey on Transfer Learning for Multiagent Reinforcement Learning Systems :+1: :sweat_drops: 

+ INTRINSIC REWARD 

  :curly_loop: [Hierarchical Cooperative Multi-Agent Reinforcement Learning with Skill Discovery](https://arxiv.org/pdf/1912.03558.pdf) :fire: :+1:  ​ ​

  The set of low-level skills emerges from an intrinsic reward that solely promotes the decodability of latent skill variables from the trajectory of a low-level skill, without the need for hand-crafted rewards for each skill.  

  :curly_loop: [The Emergence of Individuality in Multi-Agent Reinforcement Learning](https://arxiv.org/pdf/2006.05842.pdf) :fire: :fire: :+1: 

  EOI learns a probabilistic classifier that predicts a probability distribution over agents given their observation and gives each agent an intrinsic reward of being correctly predicted by the classifier. 

  :curly_loop: [A Maximum Mutual Information Framework for Multi-Agent Reinforcement Learning](https://arxiv.org/pdf/2006.02732.pdf) :+1: :droplet:  ​ ​
  
  introducing a latent variable to induce nonzero mutual information between actions. 
  
+ Learning Latent Representations

  :curly_loop: [Learning Latent Representations to Influence Multi-Agent Interaction](https://arxiv.org/pdf/2011.06619.pdf) :+1:  ​

  We propose a reinforcement learningbased framework for learning latent representations of an agent’s policy, where the ego agent identifies the relationship between its behavior and the other agent’s future strategy. The ego agent then leverages these latent dynamics to influence the other agent, purposely guiding them towards policies suitable for co-adaptation. 
  
+ communicative partially-observable stochastic game (Comm-POSG) 



<a name="anchor-constrainedrl"></a>  

:o: Constrained RL 

:curly_loop: [A Unified View of Entropy-Regularized Markov Decision Processes](https://arxiv.org/pdf/1705.07798.pdf) :fire: :droplet:  ​

using the conditional entropy of the joint state-action distributions as regularization yields a dual optimization problem closely resembling the Bellman optimality equations 

:curly_loop: [A Theory of Regularized Markov Decision Processes](https://arxiv.org/pdf/1901.11275.pdf) :+1::volcano: :boom: :droplet:    

We have introduced a general theory of regularized MDPs, where the usual Bellman evaluation operator is modified by either a fixed convex function or a Bregman divergence between consecutive policies. We shown how many (variations of) existing algorithms could be derived from this general algorithmic scheme, and also analyzed and discussed the related propagation of errors. 

:curly_loop: [Constrained Policy Optimization](https://arxiv.org/pdf/1705.10528.pdf) :+1:  :fire:  :fire:  :volcano:  ​

We propose Constrained Policy Optimization (CPO), the first general-purpose policy search algorithm for constrained reinforcement learning with guarantees for near-constraint satisfaction at each iteration. 

:curly_loop: [Reward Constrained Policy Optimization](https://arxiv.org/pdf/1805.11074.pdf) :+1: :fire:  ​ ​

we present a novel multi-timescale approach for constrained policy optimization, called ‘Reward Constrained Policy Optimization’ (RCPO), which uses an alternative penalty signal to guide the policy towards a constraint satisfying one. 

:curly_loop: [PROJECTION-BASED CONSTRAINED POLICY OPTIMIZATION](https://arxiv.org/pdf/2010.03152.pdf) :+1: :fire:  ​ ​

the first step performs a local reward improvement update, while the second step reconciles any constraint violation by projecting the policy back onto the constraint set. 

:curly_loop: [First Order Constrained Optimization in Policy Space](https://proceedings.neurips.cc//paper/2020/file/af5d5ef24881f3c3049a7b9bfe74d58b-Paper.pdf) :fire: :+1:  

Using data generated from the current policy, FOCOPS first finds the optimal update policy by solving a constrained optimization problem in the nonparameterized policy space. FOCOPS then projects the update policy back into the parametric policy space. 

:curly_loop: [Reinforcement Learning with Convex Constraints](https://arxiv.org/pdf/1906.09323.pdf) :fire: :volcano: :droplet:

we propose an algorithmic scheme that can handle a wide class of constraints in RL tasks, specifically, any constraints that require expected values of some vector measurements (such as the use of an action) to lie in a convex set.  

:curly_loop: [Batch Policy Learning under Constraints](https://arxiv.org/pdf/1903.08738.pdf) :volcano: :droplet:  ​ ​

propose a flexible meta-algorithm that admits any batch reinforcement learning and online learning procedure as subroutines. 

:curly_loop: [A Primal-Dual Approach to Constrained Markov Decision Processes](https://arxiv.org/pdf/2101.10895.pdf) :volcano: :droplet:  

 :curly_loop: [Reward is enough for convex MDPs](https://arxiv.org/pdf/2106.00661.pdf) :fire: :volcano: :boom: :droplet:  ​

It is easy to see that Convex MDPs in which goals are expressed as convex functions of stationary distributions cannot, in general, be formulated in this manner (maximising a cumulative reward).  

 ​ ​

+ Density constrained

  :curly_loop: [DENSITY CONSTRAINED REINFORCEMENT LEARNING](https://openreview.net/pdf?id=jMc7DlflrMC) :+1:  :volcano:  ​

  We prove the duality between the density function and Q function in CRL and use it to develop an effective primal-dual algorithm to solve density constrained reinforcement learning problems. 





<a name="anchor-optimization"></a>  

:o: Optimization 

+ Contrastive Divergence (CD) 

  :curly_loop: [Training Products of Experts by Minimizing Contrastive Divergence](http://www.cs.toronto.edu/~fritz/absps/tr00-004.pdf) :fire: :+1:    [Notes](https://www.robots.ox.ac.uk/~ojw/files/NotesOnCD.pdf) :+1:  ​

  C: contrastive = perceivable difference(s) 

  D: divergence = general trend of such differences (over epochs) 

  :curly_loop: [A Contrastive Divergence for Combining Variational Inference and MCMC](https://arxiv.org/pdf/1905.04062.pdf) :droplet:  ​

  :curly_loop: [CONTRASTIVE DIVERGENCE LEARNING IS A TIME REVERSAL ADVERSARIAL GAME](https://openreview.net/pdf?id=MLSvqIHRidA) :fire:  :droplet: 

  Specifically, we show that CD is an adversarial learning procedure, where a discriminator attempts to classify whether a Markov chain generated from the model has been time-reversed. 

+ DISTRIBUTIONALLY ROBUST OPTIMIZATION (DRO) 

  :curly_loop: [MODELING THE SECOND PLAYER IN DISTRIBUTIONALLY ROBUST OPTIMIZATION](https://openreview.net/pdf?id=ZDnzZrTqU9N) :+1: :fire:  ​ ​

  we argue instead for the use of neural generative models to characterize the worst-case distribution, allowing for more flexible and problem-specific selection of *the uncertainty set*. 
  
  :curly_loop: [Wasserstein Distributionally Robust Optimization: Theory and Applications in Machine Learning](https://arxiv.org/pdf/1908.08729.pdf) 

+ Distribution shift; Robust; 

  :curly_loop: [Rethinking Importance Weighting for Deep Learning under Distribution Shift](https://arxiv.org/pdf/2006.04662.pdf) :confused:  ​

  :curly_loop: [Variational Inference based on Robust Divergences](http://proceedings.mlr.press/v84/futami18a/futami18a.pdf) :+1: :droplet: 

  Maximum Likelihood Estimation and Its Robust Variants. density power divergence; the β-divergence. γ-divergence; 

+ others 

  :curly_loop: [Structured Prediction with Partial Labelling through the Infimum Loss](http://proceedings.mlr.press/v119/cabannnes20a/cabannnes20a.pdf) :+1: :droplet:  ​ ​
  
  :curly_loop: [Bridging the Gap Between f-GANs and Wasserstein GANs](https://arxiv.org/pdf/1910.09779.pdf) :+1: :fire:  :volcano: ​​ 
  
  we propose an new training objective where we additionally optimize over a set of importance weights over the generated samples. By suitably constraining the feasible set of importance weights, we obtain a family of objectives which includes and generalizes the original f-GAN and WGAN objectives. 
  
  :curly_loop: [f-GAN: Training Generative Neural Samplers using Variational Divergence Minimization](https://papers.nips.cc/paper/2016/file/cedebb6e872f539bef8c3f919874e9d7-Paper.pdf) :+1: :fire:  ​ ​
  
  :curly_loop: [On Symmetric Losses for Learning from Corrupted Labels](https://arxiv.org/pdf/1901.09314.pdf) :fire: :droplet: 
  
   using a symmetric loss is advantageous in the balanced error rate (BER) minimization and area under the receiver operating characteristic curve (AUC) maximization from corrupted labels. 
  
  :curly_loop: [A Symmetric Loss Perspective of Reliable Machine Learning](https://arxiv.org/pdf/2101.01366.pdf) :+1: :droplet: :fire: ​
  
  a symmetric loss can yield robust classification from corrupted labels in balanced error rate (BER) minimization and area under the receiver operating characteristic curve (AUC) maximization. 
  
  :curly_loop: [Connecting Generative Adversarial Networks and Actor-Critic Methods](https://arxiv.org/pdf/1610.01945.pdf) :+1:  ​
  
  GANs can be seen as a modified actor-critic method with blind actors (stateless) in stateless MDPs. 
  
  :curly_loop: [An Image is Worth More Than a Thousand Words: Towards Disentanglement in the Wild](https://arxiv.org/pdf/2106.15610.pdf) :+1: :volcano:  
  
  we propose a method for disentangling a set of factors which are only partially labeled, as well as separating the complementary set of residual factors that are never explicitly specified. 
  
   ​
  
   ​
  
   ​ ​






### Others 

+ Gaussian Precess, Kernel Method, [EM](https://zhuanlan.zhihu.com/p/54823479), [Conditional Neural Process](https://zhuanlan.zhihu.com/p/142260457), [Neural Process](https://zhuanlan.zhihu.com/p/70226367),  (Deep Mind, ICML2018) :+1: ​
+ [Weak Duality](https://people.eecs.berkeley.edu/~elghaoui/Teaching/EE227A/lecture7.pdf), [Fenchel-Legendre Duality](https://zhuanlan.zhihu.com/p/34236792), [Convex-Optimization](https://glooow1024.github.io/categories/Convex-Optimization/), [Convex-Optimization - bilibili](https://www.bilibili.com/video/BV1Jt411p7jE?p=20&spm_id_from=pageDriver),  
+ [Online Convex Optimization](https://zhuanlan.zhihu.com/p/346763047), [ONLINE LEARNING](https://parameterfree.com/lecture-notes-on-online-learning/), 
+ [Total variation distance](http://people.csail.mit.edu/jayadev/teaching/ece6980f16/scribing/26-aug-16.pdf), 
+ [Ising model](https://zhuanlan.zhihu.com/p/163706800), Gibbs distribution, [VAEBM](https://openreview.net/pdf?id=5m3SEczOV8L), 
+ [f-GAN](https://kexue.fm/archives/5977), [GAN-OP](https://zhuanlan.zhihu.com/p/50488424), [ODE: GAN](https://zhuanlan.zhihu.com/p/65953336), 
+ [Wasserstein Distance](Wasserstein Distance), [Statistical Aspects of Wasserstein Distances](https://arxiv.org/pdf/1806.05500.pdf), [Optimal Transport and Wasserstein Distance](http://www.stat.cmu.edu/~larry/=sml/Opt.pdf), [Metrics for GAN](An empirical study on evaluation metrics of generative adversarial networks), [Metrics for GAN zhihu](https://zhuanlan.zhihu.com/p/99375611), [MMD: Maximum Mean Discrepancy](https://www.zhihu.com/question/288185961), 
+ [MARKOV-LIPSCHITZ DEEP LEARNING](https://arxiv.org/pdf/2006.08256.pdf), 
+ [Rainbow](https://arxiv.org/pdf/1710.02298.pdf) :sweat_drops: ,  ​
+ [VC dimensition](https://zhuanlan.zhihu.com/p/41109051), 
+ [BALD](https://arxiv.org/pdf/1112.5745.pdf), 



---

---

### Blogs & Corp. & Legends 

[OpenAI Spinning Up](https://spinningup.openai.com/en/latest/), [OpenAI Blog](https://openai.com/blog/), [OpenAI Baselines](https://github.com/openai/baselines), [DeepMind](https://deepmind.com/blog?category=research), [BAIR](https://bair.berkeley.edu/blog/), [Stanford AI Lab](https://ai.stanford.edu/blog/), 

[Lil'Log](https://lilianweng.github.io/lil-log/), [Andrej Karpathy blog](http://karpathy.github.io/), [The Gradient](https://thegradient.pub/), [RAIL - course - RL](http://rail.eecs.berkeley.edu/deeprlcourse-fa19/), [RAIL -  cs285](https://www.youtube.com/playlist?list=PL_iWQOsE6TfURIIhCrlt-wj9ByIVpbfGc), [inFERENCe](https://www.inference.vc/), 

[covariant](http://covariant.ai/),  [RL_theory_book](https://rltheorybook.github.io/), 

UCB: [Tuomas Haarnoja](https://scholar.google.com/citations?hl=en&user=VT7peyEAAAAJ),  [Pieter Abbeel](https://scholar.google.com/citations?user=vtwH6GkAAAAJ&hl=en&oi=sra), [Sergey Levine](https://scholar.google.com/citations?user=8R35rCwAAAAJ&hl=en),  [Abhishek Gupta ](https://people.eecs.berkeley.edu/~abhigupta/), [Coline Devin](https://people.eecs.berkeley.edu/~coline/), [YuXuan (Andrew) Liu](https://yuxuanliu.com/), [Rein Houthooft](https://scholar.google.com/citations?user=HBztuGIAAAAJ&hl=en), [Glen Berseth](https://scholar.google.com/citations?hl=en&user=-WZcuuwAAAAJ&view_op=list_works&sortby=pubdate), 

UCSD: [Xiaolong Wang](https://scholar.google.com.sg/citations?hl=en&user=Y8O9N_0AAAAJ&sortby=pubdate&view_op=list_works&citft=1&email_for_op=liujinxin%40westlake.edu.cn&gmla=AJsN-F79NyYa7yONVJDI6gta02XaqE24ZGaLjgMRYiKHJ-wf2Sb4Y-ZqHrtaAGQPSWWphueUEd9d5l47a06Z1sWq91OSww8miQ), 

CMU: [Benjamin Eysenbach](https://scholar.google.com/citations?hl=en&user=DRnOvU8AAAAJ&view_op=list_works&sortby=pubdate), [Ruslan Salakhutdinov](https://scholar.google.com/citations?hl=en&user=ITZ1e7MAAAAJ&view_op=list_works&sortby=pubdate), 

Standord: [Chelsea Finn](https://scholar.google.com/citations?user=vfPE6hgAAAAJ&hl=en), 

NYU: [Rob Fergus](https://scholar.google.com/citations?user=GgQ9GEkAAAAJ&hl=en&oi=sra), 

MIT: [Bhairav Mehta](https://scholar.google.com/citations?hl=en&user=uPtOmHcAAAAJ),  [Leslie Kaelbling](https://scholar.google.com/citations?hl=en&user=IcasIiwAAAAJ&view_op=list_works&sortby=pubdate), [Joseph J. Lim](https://scholar.google.com/citations?hl=zh-CN&user=jTnQTBoAAAAJ&view_op=list_works&sortby=pubdate), 

Caltech: [Joseph Marino](https://joelouismarino.github.io/), [Yisong Yue](https://scholar.google.com/citations?hl=en&user=tEk4qo8AAAAJ&view_op=list_works&sortby=pubdate) [Homepage](http://www.yisongyue.com/about.php), 

DeepMind: [David Silver](https://scholar.google.com/citations?user=-8DNE4UAAAAJ&hl=en), [Yee Whye Teh](https://scholar.google.com/citations?user=y-nUzMwAAAAJ&hl=en) [[Homepage]](https://www.stats.ox.ac.uk/~teh/), [Alexandre Galashov](https://scholar.google.com/citations?user=kIpoNtcAAAAJ&hl=en&oi=sra), [Leonard Hasenclever](https://leonard-hasenclever.github.io/) [[GS]](https://scholar.google.com/citations?user=dD-3S4QAAAAJ&hl=en&oi=sra), [Siddhant M. Jayakumar](https://scholar.google.com/citations?user=rJUAY8QAAAAJ&hl=en&oi=sra), [Zhongwen Xu](https://scholar.google.com/citations?hl=en&user=T4xuHn8AAAAJ&view_op=list_works&sortby=pubdate), [Markus Wulfmeier](https://scholar.google.de/citations?hl=en&user=YCO3WQsAAAAJ&view_op=list_works&sortby=pubdate) [[HomePage]](https://markusrw.github.io/), [Wojciech Zaremba](https://scholar.google.com/citations?hl=en&user=XCZpOcAAAAAJ&view_op=list_works&sortby=pubdate), [Aviral Kumar](https://scholar.google.ca/citations?hl=en&user=zBUwaGkAAAAJ&sortby=pubdate&view_op=list_works&citft=1&email_for_op=liujinxin%40westlake.edu.cn&gmla=AJsN-F5E6ErpTneaGZx0cFbO3J7y-pEg7TpQXU2LTHXXoDUX79vsrOzPiGg55PiqYlz0GVVk5kJT8orQHvsGwW5WF7RSg-9ryv5Xo-L0rpHKJOuBiuL-dfE), 

Google: [Ian Fischer](https://scholar.google.com/citations?hl=en&user=Z63Zf_0AAAAJ&view_op=list_works&sortby=pubdate), [Danijar Hafner](https://scholar.google.de/citations?hl=en&user=VINmGpYAAAAJ&view_op=list_works&sortby=pubdate) [[Homepage]](https://danijar.com/), [Ofir Nachum](https://scholar.google.com/citations?hl=en&user=C-ZlBWMAAAAJ&sortby=pubdate&view_op=list_works&citft=1&citft=3&email_for_op=liujinxin%40westlake.edu.cn&gmla=AJsN-F6bB1Pjv8yoTSFnbtB3GJE8dXTxX4wK1GnOvBUvWhOt8ZBNxojCh223i5_AvQ347yNG-MLSVENT3s-8UCe4DIDgvLNNG8kvQNxMjH7_VCrX6-P0FVQ), [Yinlam Chow](https://scholar.google.com/citations?hl=en&user=BFlpS-8AAAAJ&sortby=pubdate&view_op=list_works&citft=1&email_for_op=liujinxin%40westlake.edu.cn&gmla=AJsN-F7Ht8XHXMlvXRq2vMXdWh8tAT298ToP-ONtMyacd1uEqMWgiWBqT9SRimdl-c-xcemDY324kkrnfR9nfDbaq8sso-KZ0A), [Shixiang Shane Gu](https://scholar.google.com/citations?hl=en&user=B8wslVsAAAAJ&view_op=list_works&sortby=pubdate), 

Montreal: [Anirudh Goyal](https://scholar.google.com/citations?hl=en&user=krrh6OUAAAAJ&view_op=list_works&sortby=pubdate) [Homepage](https://anirudh9119.github.io/), 

Toronto: [Jimmy Ba](https://scholar.google.com/citations?hl=en&user=ymzxRhAAAAAJ&view_op=list_works&sortby=pubdate); 

Columbia: [Yunhao (Robin) Tang](https://robintyh1.github.io/), 

OpenAI: 

THU:  [Chongjie Zhang](https://scholar.google.com/citations?user=LjxqXycAAAAJ&hl=en) [[Homepage]](http://people.iiis.tsinghua.edu.cn/~zhang/), [Yi Wu](https://scholar.google.com/citations?hl=en&user=dusV5HMAAAAJ&view_op=list_works&sortby=pubdate), [Mingsheng Long](https://scholar.google.com/citations?user=_MjXpXkAAAAJ) [[Homepage]](http://ise.thss.tsinghua.edu.cn/~mlong/), 

PKU: [Zongqing Lu](https://scholar.google.com/citations?user=k3IFtTYAAAAJ&hl=en), 

NJU: [Yang Yu](https://scholar.google.com/citations?user=PG2lDSwAAAAJ&hl=en), 

TJU: [Jianye Hao](https://scholar.google.com/citations?user=FCJVUYgAAAAJ&hl=en), 

HIT: [PR&IS research center](http://pr-ai.hit.edu.cn/main.htm), 

Salesforce : [Alexander Trott](https://scholar.google.com/citations?hl=en&user=rB4bvV0AAAAJ&view_op=list_works&sortby=pubdate), 

Flowers Lab (INRIA): [Cédric Colas](https://scholar.google.fr/citations?hl=fr&user=VBz8gZ4AAAAJ&view_op=list_works&sortby=pubdate), 