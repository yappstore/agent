# agent


_Note this is still a work in progress._

### Features:

- **Local or Remote Inference:** API keys can be provided for all the major LLM providers. Alternatively, if you want to keep your data private you can opt to use your own LLM local model to power the agent.
- **Local Context Awareness:** The agent is aware of the different applications you have installed
- **Modular Problem Solving:** The agent can interpret your intent, and the agent can plan and carry out tasks given one or more of the installed applications (*Daemons*)
- **Search**: The agent can search for application listings within the marketplace that suit your needs and suggest them.
- **Insights**: The agent can read public comment sections for relevant questions and answers the user may have.
- **Text-to-Speech:** The agent can reply through synthesized speech
- **Speech-to-text:** The agent can reply through synthesized speech

This repository contains a modular component to be used within the [yappstore.ai](https://yappstore.ai) desktop application. 
This code is completely separated from the main desktop application and used as an external binary to enable AI features. 

In the interest of ransparency, this repository is open source and open to contributors. 
You are free to fork, copy and modify the code however you see fit - see licensing agreements for full details.

---

### Security Manifesto:

- The agent must NOT execute artbitrary shell commands on the user's behalf.
- The agent must NOT have direct access to the users filesystem. 
- The agent must NOT download applications without the user's approval.
- The agent must NOT run applications without the user's approval.
- The agent must NOT leave comments or replies on behalf of the user.
- The agent must NOT have access to or have the ability to divulge sensitive information.
- The agent must NOT have direct access to the users personal information


### Contribution

We are looking for contributors - see `CONTRIBUTION.md` for details on how to open a PR.


