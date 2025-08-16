### What are sovereign agents
Sovereign agents are extension of a sovereign individual, expanding his capabilities and augmenting his intelect. 

### Why agents 
Currently primary modality of how people interact with any "AI" is by requesting things from it. But this is merely a crutch compared to the endless amount of things an semi-autonomous agent could do for you. Imagine an assistant that reminds you of your appointments, helps you orchestrate other agents, provides you daily briefings about important things you might care about (personalized to your interests and concerns), follows latest research about things that worry you and remembers things for you. Sovereign agent can be your companion in any quest you might take upon yourself. 


### Why sovereign agents
- technology advancements and state of the world has brought us to a point where it is possible and also needed to build them
- pushing the boundries of possible and advancing the frontier of AI and human capabilities 
- creating a free(er) market for compute and data and escape the big tech surveillance bubble
- enabling private individuals keep their privacy while benefit from advancemnets in technology
- demonstrate the superior technological advancements of distributed technologies and open networks

### Guiding principles for sovereign agents are:
- they preserve the individuals privacy
- they support the individuals goals
- they save the individuals time
- they enhance the individuals productivity
- they enable the individuals sovereignity
- 

### How sovereign agents operate
Sovereign agent(SovAgnt) is a guard dog for its owner's attention and time. Proactively gathering and processing infromation on behalf of its owner, filtering out and summarizing the relevant and discarding the noise. And push the relevant to the owner instead of waiting for the owner to figure out it needs it. 

Sovereign Agent can be thought of as a personal assistant knowing all your quirks, executing your will and making sure you're on top of everything needed. It should improve your life, not provide just another gadget to play with.

### (some) Functions of sovereign agents
#### Personal Assistant
- email and other communication filtering, acting as a narrow executive assistant, drafting responses 
- perform tasks like research,simple copywriting, reminding and scheduling appointments
- working memory of your affairs
- keep notes
#### Work Orchestration
- orchestrate other agents
- stay on top of projects
- 
#### Knowledge 
- daily summaries based on interests (podcasts, blogs, rss feeds, nostr)
- access your knowledge base (and other knowledge bases available)

### Building blocks for Sovereign Agents
#### Nostr
Using nostr as default backbone of the SovAgnt makes it easily expandable and interoperable. It uses nostr for its core, utilizing it both for coorination and communication. It also makes it easily 
#### ContextVM
ContexVM enables tool calling and access to data through MCP. It utilizes nostr for discovery and coordination, meaning its very simple to have multiple computers running services and connect to it asynchronously. It gives it the ability to spin 

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
- most of holons can be implemented as standalone [ContextVM](https://www.contextvm.org/), thus immediately useful and could actually provide revenue to users running them
- by embracing distributed tools  sovereign agents instantly get all the abilities of all tools the marketplaces provide 


#### focusing upfront on making the participation of other interested parties as smooth as possible
- extensive documentation and development tooling to enable rapid experimentation
- ensuring minimal non-breakable communication standards between holons to prevent breaking changes and friction in the process by using nostr as internal coordination mechanism for the SovAgnt 
  
#### embracing our weakness
- sovereign agents are not a commercial product but an implementation proposal of distributed agents for sovereign individuals and thus don't care about controling every aspect of the experience but instead embracing chaos
- horizontal distribution and interoperability can far outweight lack of vertical integaration on the long run
- open systems tend to win over closed ones given enough time to catch up on technological advancements


For comments, issues or ideas go to [repository](https://github.com/aljazceru/sovereign-agents) or ping me on [nostr.](https://nostr.at/aljaz@nostr.si)
