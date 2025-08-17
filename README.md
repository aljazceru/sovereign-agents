### What are Sovereign Agents
Sovereign Agents (SovAgents) are are extension of a sovereign individual, expanding his capabilities and augmenting his intelect. They act not as passive AI chatbots, waiting for your prompts, but as proactive, semi-autonomous companieions that orchestrat your digital life, filter noise and surface what matter most, all while preserving your privacy and sovereignity. 

A soverign agent is not just a tool - its a personal guard dog for your attention and time, continiously working for you, learning your preferences and helping you achieve your goals. 

### Why sovereign agents
- technology advancements and state of the world has brought us to a point where it is possible and also needed to build them
- creating a free(er) market for compute and data
- escape the big tech surveillance bubble and provide alternatives to people
- enabling private individuals keep their privacy while benefit from advancemnets in technology
- demonstrate the superior technological advancements of distributed technologies and open networks
- pushing the boundries of possible and advancing the frontier of AI and human capabilities 

### Guiding principles for sovereign agents are:
- preserve privacy
- support the individuals goals
- enable the individuals sovereignity
- save time
- enhance productivity

### How sovereign agents operate
Sovereign agent(SovAgnt) is a guard dog for its owner's attention and time. Proactively gathering and processing infromation on behalf of its owner, filtering out and summarizing the relevant and discarding the noise. And push the relevant to the owner instead of waiting for the owner to figure out it needs it. 

Sovereign Agent can be thought of as a personal assistant knowing all your quirks, executing your will and making sure you're on top of everything needed. It should improve your life, not provide just another gadget to play with.

### Core capabilities
#### Personal Assistant
- email and other communication filtering, acting as a narrow executive assistant, drafting responses 
- managing scheduling, reminders and appointments
- research and summarize topics of interest
- working memory of your tasks, notes and commitments
#### Work Orchestration
- orchestrate/handle other agents
- stay on top of projects
#### Knowledge 
- daily summaries based on interests (podcasts, blogs, rss feeds, nostr)
- access to personal and external knowledge base
#### Tools
- ContextVM/DVM integrations and MCP tool use gives infinite possibilities for what the agent can do
- Giving the agent a budget with which it can operate enables it to pay CVMs for extra functionality it doesn't have or expand it capabilities
- 

### Building blocks 
#### Nostr
 - Using nostr as default backbone of the SovAgnt makes it easily expandable and interoperable.
 - It uses nostr for its core, utilizing it both for coorination and communication, allowing easy scaling and redundancy by running CVMs on multiple machines you have or paying for them when yours are unavailable
 - Enables decentralization and market creation for services the agents consume
  
#### ContextVM
- [ContexVM](https://contextvm.org) enables tool calling and access to data through MCP.
- It utilizes nostr for discovery and coordination, meaning its very simple to have multiple computers running services and connect to it asynchronously.
- 
#### Model Context Protocol 
[MCP](https://docs.cursor.com/advanced/model-context-protocol) was developed by Anthropic and expands LLM's capabilities with tools. There is an implementation of using nostr as discovery mechanism for MCP called [ContextVM](https://www.contextvm.org/). This instantly gives the SovAgnt ability to access variety of tools. 

#### Confidential Computing
Confidential computing enables us to run sensitive operations on much more capable hardware than we own. This enables us to securely scale while not relying on big AI solutions for our AI needs. Providers like [privatemode.ai](https://privatemode.ai) make it easy to integrate confidential inference in SovAgnt and separate holons. Given the compatibility of api standards it is also easy to swap out between locally run models and using a confidential ai provider, or using remote inference for bigger tasks and local model for coordination. 


### Open and interoperable approach to building
- building in the open to attract as many people to the efforts as possible
- thinking about developer experience to make new contributions as simple as possible
- defining API contracts (where possiblle) to make integrations easy(ier)

### Why can't I just run everything locally
- you could, and it should be supported to prioritize local utilization of resources, but you likely won't be able to have the hardware resources or access to all information you'd like locally
- confidential computing and utilization of distributed compute with DVM's gives you the ability to access large amount of information, algorihtms and capabilities that you don't have locally
- distribution of workloads improves efficiency of second realm resource utilization and provides business opportunities for specialization

### Plan
#### implementing reusable building blocks using holon philosophy, making each of them usable by themselves and as a part of a larger system
- a lot of holons can be implemented as standalone [ContextVM](https://www.contextvm.org/), thus immediately useful and could actually provide revenue to users running them
- by embracing distributed tools sovereign agents instantly get all the abilities of all tools the marketplaces provide
- even if the user runs all of his own infrastructure he can still benefit by offering his access capacity to others

#### focusing upfront on making the participation of other interested parties as smooth as possible
- extensive documentation and development tooling to enable rapid experimentation
- ensuring minimal non-breakable communication standards between holons to prevent breaking changes and friction in the process by using nostr as internal coordination mechanism for the SovAgnt 
  


For comments, issues or ideas go to [repository](https://github.com/aljazceru/sovereign-agents) or ping me on [nostr.](https://nostr.at/aljaz@nostr.si)
