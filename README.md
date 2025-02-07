# TODO
Change: https://github.com/danswer-ai/danswer/blob/main/backend/danswer/llm/custom_llm.py

Then: 
https://github.com/danswer-ai/danswer/blob/cc69ba03a6eaf45567804ff71d4f4904a7b06d68/deployment/docker_compose/env.prod.template#L11

GEN_AI_MODEL_PROVIDER=custom
GEN_AI_API_KEY=<your-model-server-api-key-or-leave-unset>
GEN_AI_API_ENDPOINT=<your-custom-model-endpoint-url>

Doc
https://docs.danswer.dev/gen_ai_configs/custom_server

<!-- DANSWER_METADATA={"link": "https://github.com/danswer-ai/danswer/blob/main/README.md"} -->

<h2 align="center">
<a href="https://www.danswer.ai/"> <img width="50%" src="https://github.com/danswer-owners/danswer/blob/1fabd9372d66cd54238847197c33f091a724803b/DanswerWithName.png?raw=true)" /></a>
</h2>

<p align="center">
<p align="center">Open Source Unified Search and Gen-AI Chat with your Docs.</p>

<p align="center">
<a href="https://docs.danswer.dev/" target="_blank">
    <img src="https://img.shields.io/badge/docs-view-blue" alt="Documentation">
</a>
<a href="https://join.slack.com/t/danswer/shared_invite/zt-2afut44lv-Rw3kSWu6_OmdAXRpCv80DQ" target="_blank">
    <img src="https://img.shields.io/badge/slack-join-blue.svg?logo=slack" alt="Slack">
</a>
<a href="https://discord.gg/TDJ59cGV2X" target="_blank">
    <img src="https://img.shields.io/badge/discord-join-blue.svg?logo=discord&logoColor=white" alt="Discord">
</a>
<a href="https://github.com/danswer-ai/danswer/blob/main/README.md" target="_blank">
    <img src="https://img.shields.io/static/v1?label=license&message=MIT&color=blue" alt="License">
</a>
</p>

<strong>[Danswer](https://www.danswer.ai/)</strong> lets you ask questions in natural language questions and get back
answers based on your team specific documents. Think ChatGPT if it had access to your team's unique
knowledge. Connects to all common workplace tools such as Slack, Google Drive, Confluence, etc.

Teams have used Danswer to:
- Speedup customer support and escalation turnaround time.
- Improve Engineering efficiency by making documentation and code changelogs easy to find.
- Let sales team get fuller context and faster in preparation for calls.
- Track customer requests and priorities for Product teams.
- Help teams self-serve IT, Onboarding, HR, etc.

<h3>Usage</h3>

Danswer Web App:

https://github.com/danswer-ai/danswer/assets/32520769/563be14c-9304-47b5-bf0a-9049c2b6f410


Or, plug Danswer into your existing Slack workflows (more integrations to come 😁):

https://github.com/danswer-ai/danswer/assets/25087905/3e19739b-d178-4371-9a38-011430bdec1b


For more details on the Admin UI to manage connectors and users, check out our 
<strong><a href="https://www.youtube.com/watch?v=geNzY1nbCnU">Full Video Demo</a></strong>!

## Deployment

Danswer can easily be run locally (even on a laptop) or deployed on a virtual machine with a single
`docker compose` command. Checkout our [docs](https://docs.danswer.dev/quickstart) to learn more.

We also have built-in support for deployment on Kubernetes. Files for that can be found [here](https://github.com/danswer-ai/danswer/tree/main/deployment/kubernetes).


## 💃 Main Features 
* Document Search + AI Answers for natural language queries.
* Connectors to all common workplace tools like Google Drive, Confluence, Slack, etc.
* Chat support (think ChatGPT but it has access to your private knowledge sources).
* Create custom AI Assistants with different prompts and backing knowledge sets.
* Slack integration to get answers and search results directly in Slack.


## Other Noteable Benefits of Danswer
* Best in class Hybrid Search across all sources (BM-25 + prefix aware embedding models).
* User Authentication with document level access management.
* Admin Dashboard to configure connectors, document-sets, access, etc.
* Custom deep learning models + learn from user feedback.
* Connect Danswer with LLM of your choice for a fully airgapped solution.
* Easy deployment and ability to host Danswer anywhere of your choosing.


## 🔌 Connectors
Efficiently pulls the latest changes from:
  * Slack
  * GitHub
  * Google Drive
  * Confluence
  * Jira
  * Zendesk
  * Gmail
  * Notion
  * Gong
  * Slab
  * Linear
  * Productboard
  * Guru
  * Bookstack
  * Document360
  * Sharepoint
  * Hubspot
  * Local Files
  * Websites
  * And more ...

## 🚧 Roadmap
* Organizational understanding.
* Ability to locate and suggest experts from your team.
* Code Search
* Structured Query Languages (SQL, Excel formulas, etc.)

## 💡 Contributing
Looking to contribute? Please check out the [Contribution Guide](CONTRIBUTING.md) for more details.
