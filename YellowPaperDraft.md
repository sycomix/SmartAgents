<p align = "center">
<img src="SmartAgentSquare@512.jpg"></p>
#Smart Agent
###Tech Stack Abstract for the Web3 Developer
######Pre-Beta | July 2023

# Overview
 => *Smart Contract is to Blockchain*, as *Smart Agent is to Generative AI.*

###What’s an Agent?
An agent is a specialized chatbot that acts on behalf of a person. 

###What’s a Smart Agent?
A Smart Agent is a standard agent that has been trained on the Prompt Rank algorithm, making it a tool to chat intelligently with all things web3.
###What’s the Prompt Rank algorithm?
At Google’s core, you’ll find the Pagerank algorithm.  At the Smart Agent core, you’ll find the Prompt Rank algorithm. Where Pagerank only shows the most relevant pages, Prompt Rank lets Smart Agents best understand smart contracts based on predetermined metrics.  These metrics include  transactions, network, centralization, (full list needed).

#####Dapp developers will be able to register and submit their contracts for consideration.  Once considered, a developer can choose to be included or resubmit.   
###Who is the end user?
Smart Agents let people talk to smart contracts with the confidence of Prompt Rank.  So, a new adopter of crypto will use their Smart Agent as a guide.  As they gain experience and become more comfortable, their Smart Agent will grow to be an assistant.

#####We see this project as the conduit to onboard the next billion crypto users. The Smart Agent will educate people on all relevant web3 topics and transact on their behalf.
1. It will be installable so important data is stored locally
2. It will transact securely via a wallet integrated into Chromium.



<h2>Smart Agent Footprint</h2>

<div align="center">
<a href="https://github.com/SmartAgentProtocol/SmartAgents">https://github.com/SmartAgentProtocol/SmartAgents</a><br>
<a href="https://www.smartagent.org/">https://www.smartagent.org/</a><br>
<a href="https://www.chatweb3.org/">https://www.chatweb3.org/</a><br>
<a href="https://www.promptrank.org/">https://www.promptrank.org/</a><br>
<a href="https://www.smartagency.ai/">https://www.smartagency.ai/</a><br>
<a href="https://app.ens.domains/smartagents.eth">https://app.ens.domains/smartagents.eth</a><br>
<a href="https://twitter.com/SmartAgentsOrg">https://twitter.com/SmartAgentsOrg</a><br>
<a href="https://discord.gg/b27kweYZ">https://discord.gg/b27kweYZ</a><br>
<a href="https://t.me/SmartAIAgents">https://t.me/SmartAIAgents</a><br>
</div>
##Technology
LangchainJS will be the structure used to create the Smart Agent template. It allows us to combine six global functions necessary for all Smart Agents.

1. Large Language Models (communication)
2. Native knowledge base using Prompt Rank  (intelligence)
3. Persistent memory of conversations, tasks, results, and updates (recall)
4. Chains of tasks (actions)
5. Data ingest, embedding and vector mapping (learning)
6. Guidelines for agent logic and behavior (logic and rules)

###Desktop install 
An install using ElectronJS gives us access to a local version of Chromium and Node running on a User’s machine.  This is being developed at https://github.com/betterbrand/SmartAgent-Install. 
###Wallets
The smart agent desktop app will include a Smart Agent wallet alongside Chromium or as part of the  Node backend.  The app will be packaged initially for Mac/PC/Linux.  React native or Flutter soon to follow for mo.

A Smart Agent chat plug-in to wallets will be a means to further the reach of Prompt Rank. 

###EVM Compatable
Using Solidity, this allows us to remain chain agnostic, anchoring agents in a familiar environmment.

###Repositories
    Main:   https://github.com/SmartAgentProtocol/SmartAgents
    Other:	https://github.com/hwchase17/langchainjs
        	https://github.com/betterbrand/SmartAgent-Install
	        https://github.com/vercel-labs/ai
	        https://github.com/electron/electron
###Beta Delivery

| Local Install |   API    |
| ----------- | ----------- |
|Chromium|Memory|
|Node|Embedding|
|Wallet|LLM|
||RPC|
||HTTP|
||Vercel|

###Vercel AI SDK
In order to focus on the local install’s wallet functionality, the AI will be served during Beta through Vercel’s AI SDK, which provides granular access to a number of services:

- KV Storage and Bandwidth
- Cache Revalidations, Reads, and Writes 
- KV Databases & Commands
- Postgres Written Data, Transfer, and Compute Time	
- Source Images
- Edge Function Execution Units and Middleware Invocations
- Serverless Function Execution Time
- Bandwidth
- Edge Config Reads and Writes
- Edge Config Reads
- Web Analytics Events
- Vercel Remote Caching

*Post Beta we will start moving these services to the local install in order to remove Internet based vulnerabilities.* 




###Workflow
1. User consults their Smart Agent, the Smart Agent prompts the user 
2. A conversation takes place, then actions are taken by the Smart Agent using credentials provided by the User.
3. The Smart Agent reports back to the User and remembers the context and content of each conversation.  

_Start – Smart Agent looks for intent_  
![Smart Agent looks for intent](Smart_Agent_Diagrams-StartingIntent.jpg)

_Intent is to Stake_
![Intent is to stake](Smart_Agent_Diagrams-StakingETH-1.jpg)

_Smart Contract Integration_
![Smart Agent Interaction](Smart_Agent_Diagrams-StakingIntent.jpg)

####Smart Agent Donations
For dapps outside the Prompt Rank algorithm, all financial transactions will add a 10% to the user.   
####Gasless Transactions
There will be a point in which we want to analyze our Smart Agents’ actions and performance in addition to collecting the SmartAgent.org donation.  To do this in a way that is beneficial to whomever manages a Smart Agent, we can cover the gas fees as a value-add to the transaction. 

When a web3 transaction is conducted with a Smart Agent, it first goes through a Smart Agent contract that verifies identity and intent.  A third party covering gas fees or internal Paymaster will be implemented to obfuscate the installation address and onboard users into new networks in the future.


###Languages & Protocols

Version 1.0 is going to be developed using the JS version of LangChain with a number of components


|Function|Beta API|
| ----------- | ----------- |
|LLM|LLAMA|
|Memory|Pinecone|
|Ingest & Embedding|Huggingface|
|Agent Architecture|Langchain|
|ML|OpenAI|
|Document Training & Testing|Botpress|



###Roadmap
- Beta v0.1
        - Installable
    - Able to complete 1 conversational command (Welcome, Stake eth, show result)
    - V 1.1
- Agent Dashboard
    - Change in new modules LLMs
    - Partial API
    - V1.1.5
    - Smart Agent Paymaster
- V 1.2
    - True Local and Open source
- V 1.3
 - TBD
⥥
- V2 and onward
    - Linux Distribution, 
    - FreedomTech Software Bundles for Mac/PC
    - Full Nodes
    - Light Clients
    - Chrome/Wallet extension
    - Embed into site


###Smart Agent Prompt Flow
![Smart Agent Prompt Flow](SA-Prompt-Flow-Prompt-Flow.jpg)