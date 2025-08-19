### What are Sovereign Agents
Sovereign Agents (SovAgents) are an extension of a sovereign individual, expanding his capabilities and augmenting his intelect. They act not as passive AI chatbots, waiting for your prompts, but as proactive, semi-autonomous companions that orchestrate your digital life, filter noise and surface what matter most, all while preserving your privacy and sovereignity. 


### Why sovereign agents
- technology advancements and state of the world has brought us to a point where it is possible and also needed to build them
- creating a free(er) market for compute and data
- escape the big tech surveillance bubble and provide alternatives to people
- enabling private individuals keep their privacy while benefit from advancemnets in technology
- demonstrate the superior technological advancements of distributed technologies and open networks
- pushing the boundries of possible and advancing the frontier of AI and human capabilities
- bootstrap parallel economy

### Guiding principles for sovereign agents are:
- preserve privacy
- support the individuals goals
- enable the individuals sovereignity
- save time
- enhance productivity

### How sovereign agents operate
Sovereign agent can be thought about more as a hive than one particular process running somewhere. It is dynamically accessing compute and resources and engaging them on as needed basis. 


### Core capabilities
Core capabilities can be split into several groups, and each group can be further split into holons. 
#### Assistant 
- Handling communication, planning, working memory, commitments
#### Orchestration
- orchestrate/handle other agents
- stay on top of projects
#### Knowledge 
- daily summaries based on interests (podcasts, blogs, rss feeds, nostr)
- access to personal and external knowledge base
- research capabilities 
#### Tools
- ContextVM/DVM integrations and MCP tool use gives infinite possibilities for what the agent can do
- Giving the agent a budget with which it can operate enables it to pay CVMs for extra functionality it doesn't have or expand it capabilities

### Building blocks 
#### Nostr
 - Using nostr as default backbone of the SovAgnt makes it easily expandable and interoperable.
 - It uses nostr for its core, utilizing it both for coorination and communication, allowing easy scaling and redundancy by running CVMs on multiple machines you have or paying for them when yours are unavailable
 - Enables decentralization and market creation for services the agents consume
  
#### ContextVM / DVM
- [ContexVM](https://contextvm.org) enables tool calling and access to data through [MCP](https://docs.cursor.com/advanced/model-context-protocol).
- It utilizes nostr for discovery and coordination, meaning its very simple to have multiple computers running services and connect to it asynchronously

#### Confidential Computing
- Confidential computing enables us to run sensitive operations on much more capable hardware than we own. This enables us to securely scale while not relying on big AI solutions for our AI needs. Providers like [privatemode.ai](https://privatemode.ai) make it easy to integrate confidential inference in SovAgnt and separate holons. Given the compatibility of api standards it is also easy to swap out between locally run models and using a confidential ai provider, or using remote inference for bigger tasks and local model for coordination. Example of confidential llm inference combined with signal chat - 
#### implementing reusable building blocks using holon philosophy, making each of them usable by themselves and as a part of a larger system
- a lot of holons can be implemented as standalone [ContextVM](https://www.contextvm.org/), thus immediately useful and could actually provide revenue to users running them
- by embracing distributed tools sovereign agents instantly get all the abilities of all tools the marketplaces provides

### Why can't I just run everything locally
- you could, and it should be supported to prioritize local utilization of resources, but you likely won't be able to have the hardware resources or access to all information you'd like locally
- confidential computing and utilization of distributed compute with DVM's gives you the ability to access large amount of information, algorihtms and capabilities that you don't have locally
- distribution of workloads improves efficiency of second realm resource utilization and provides business opportunities for specialization
- distributed workload means that at some point we could have a digital organism paying for its services and, scaling itself up and down depending on needs and financial resources
- even if the user runs all of his own infrastructure he can still benefit by offering his access capacity to others

### Roadmap
#### 1. Create building blocks 
First we create the independent holons that are alraedy useful by themselves
a) data aggregators
b) transcribers
c) tts
d) research
#### 2. Integrate building blocks
Integrate building blocks into existing services to create demand in the market
a) using them in [private ai assistant](https://github.com/aljazceru/private-ai-assistant/)
b) package building blocks into popular self hosting platforms like start9, umbrel etc
#### 3. Create Sov Agent
Easily deployable minimal core utilizing remote confidential compute or local llms (or a combination of both) and whitenoise for communication
a) package for easy deployment to start9, umbrel
b) cloud hosted option as a service (confidential)
c) implement controls like whitelisting of providers, agents
#### 4. Swarm
Add swarm capabilities to the Sov Agent, giving it ability to brainstorm its way to a solution with the help or multiple other agents that it can hire
#### 5. Economy 
Make integrations of sovereign agents into any product as seamless as using openai api, making a bridge from outside to the nostr ecosystem. 
