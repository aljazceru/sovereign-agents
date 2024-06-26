### What are sovereign agents
Sovereign agents are extension of a sovereign individual, expanding his capabilities and augmenting his intelect. 

### Why agents 
Currently primary modality of how people interact with any "AI" is by requesting things from it. But this is merely a crutch compared to the spaceship an semi-autonomous agent could do for you. 

### Why sovereign agents
- technology advancements and state of the world has brought us to a point where it is possible and also needed to build them
- freedom technology for free people by free people
- pushing the boundries of possible and advancing the frontier
- creating a free(er) market for compute and data

### Guiding principles for sovereign agents are:
- they preserve the individuals privacy
- they support the individuals goals
- they save the individuals time
- they enhance the individuals productivity
- they enable the individuals sovereignity

### How sovereign agents operate
Sovereign agent could be a guard dog for its owner's attention and time, proactively gathering and processing infromation on behalf of its owner, filtering out and summarizing the relevant and discarding the noise. And push the relevant to the owner instead of waiting for the owner to figure out it needs it. 

Sovereign Agent can be thought of as a personal assistant knowing all your quirks, executing your will and making sure you're on top of everything needed. It should improve your life, not just provide another gadget to play with. 

### Functions that sovereign agents could do:
- news aggregation and preparation of daily summaries based on interests
- email and other communication filtering, automated responding acting as a narrow executive assistant
- perform simple tasks
  - web research
  - copywriting
  - market research
- write code (and execute it)
- autonomously perform tasks (at some point)

### Building blocks for Sovereign Agents
- convert text to speech
- convert speech to text
- text to image generation
- image to text recognition
- image manipulation
- conversational LLM
- personal context through RAG
- access to vast pools of information
- confidential computing
- open and interoperable approach to building

### Why can't I just run everything locally
- you could, and it should be supported to prioritize local utilization of resources, but you likely won't be able to have the hardware resources or access to all information you'd like locally
- confidential computing and utilization of distributed compute with DVM's gives you the ability to access large amount of information, algorihtms and capabilities that you don't have locally
- distribution of workloads improves efficiency of second realm resource utilization and provides business opportunities for specialization

### How do we build them
#### implementing reusable building blocks using holon philosophy, making each of them usable by themselves and as a part of a larger system
- most of holons can be implemented as standalone [data vending machines](https://www.data-vending-machines.org/), thus immediately useful and could actually provide revenue
- by embracing DVM's sovereign agents instantly get all the abilities of all DVMs out there (with the caveat that they are not confidential)
- easily reusable confidential computing playbooks and prepared containers for developers to start creating software that can run in enclaves
#### focusing upfront on making the participation of other interested parties as smooth as possible
- extensive documentation and development tooling to enable rapid experimentation
- ensuring minimal non-breakable communication standards between holons to prevent breaking changes and friction in the process
- making scratching your own its trivially simple
#### embracing our weakness
- sovereign agents are not a commercial product but an implementation proposal of distributed agents for sovereign individuals and thus don't care about controling every aspect of the experience but instead embracing chaos
- horizontal distribution and interoperability can far outweight lack of vertical integaration on the long run
- open systems tend to win over closed ones given enough time to catch up on technological advancements
#### currently identified obstacles 
- confidential computing is complex, with multiple competing architectures and implementation limitations (more research on that can be found at [ungovernable.tech](https://ungovernable.tech)
- limited availability of hardware, specifically high end GPUs that have secure enclave support but there are alternative approaches like extending [CPU TEEs on existing GPUs without hardware modifications](https://www.s3lab.io/paper/gevisor-socc23)

For comments, issues or ideas go to [Github repository](https://github.com/aljazceru/sovereign-agents).
