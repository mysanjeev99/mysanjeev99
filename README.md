<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0e75b6,100:8957e5&height=150&section=header&text=Sanjeev%20Mohan&fontSize=44&fontAlignY=40&fontColor=ffffff" alt="Sanjeev Mohan" /><br/>
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1200&center=true&vCenter=true&width=640&height=34&lines=Agentic+AI+Engineer+%26+Tech+Lead;RAG+%7C+Multi-Agent+Systems+%7C+MCP;AWS+Bedrock+%7C+EKS+%7C+LangGraph" alt="Agentic AI Engineer and Tech Lead" /><br/>
<img src="https://komarev.com/ghpvc/?username=mysanjeev99&label=Profile+views&color=0e75b6&style=for-the-badge" alt="Profile views" />
<a href="https://mysanjeev99.github.io"><img src="https://img.shields.io/badge/Portfolio-7c3aed?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIyIiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiPjxjaXJjbGUgY3g9IjEyIiBjeT0iMTIiIHI9IjEwIi8%2BPGxpbmUgeDE9IjIiIHkxPSIxMiIgeDI9IjIyIiB5Mj0iMTIiLz48cGF0aCBkPSJNMTIgMmExNS4zIDE1LjMgMCAwIDEgNCAxMCAxNS4zIDE1LjMgMCAwIDEtNCAxMCAxNS4zIDE1LjMgMCAwIDEtNC0xMCAxNS4zIDE1LjMgMCAwIDEgNC0xMHoiLz48L3N2Zz4%3D" alt="Portfolio" /></a>
<a href="https://www.linkedin.com/in/sanjeev-mohan"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxwYXRoIGQ9Ik0yMC40NDcgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODUzIDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTFWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3LTEuODUgMy42MDEgMCA0LjI2NyAyLjM3IDQuMjY3IDUuNDU1djYuMjg2ek01LjMzNyA3LjQzM2EyLjA2MiAyLjA2MiAwIDAxLTIuMDYzLTIuMDY1IDIuMDY0IDIuMDY0IDAgMTEyLjA2MyAyLjA2NXptMS43ODIgMTMuMDE5SDMuNTU1VjloMy41NjR2MTEuNDUyek0yMi4yMjUgMEgxLjc3MUMuNzkyIDAgMCAuNzc0IDAgMS43Mjl2MjAuNTQyQzAgMjMuMjI3Ljc5MiAyNCAxLjc3MSAyNGgyMC40NTFDMjMuMiAyNCAyNCAyMy4yMjcgMjQgMjIuMjcxVjEuNzI5QzI0IC43NzQgMjMuMiAwIDIyLjIyMiAwaC4wMDN6Ii8%2BPC9zdmc%2B" alt="LinkedIn" /></a>
<a href="https://orcid.org/0000-0002-0230-0432"><img src="https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" alt="ORCID" /></a>
</div>

## About

I build agentic AI systems, generative pipelines and the platform underneath them: identity, tool gateways and deployment. Much of my work lives in private repositories (marked 🔒), so for those I describe the technology, not the internals.

## Agentic systems

| Project | Technology |
|---|---|
| **Cascade** 🔒 | An agentic assistant that searches its own knowledge base first, falls back to the web, and learns from useful answers. Streaming responses, isolated per-user tool execution, approval-gated actions. FastAPI, LangGraph, Qdrant, PostgreSQL, React, Playwright, Docker. |
| **Agents** 🔒 | A workbench for multi-agent patterns: agent-to-agent protocols, agentic RAG, state and memory, CrewAI, and a LangGraph recommender on PostgreSQL with pgvector. |
| **DesignMatic** 🔒 | An image-generation agent: an orchestrator routes between generate, edit, combine and describe tools over diffusion models (Flux through ComfyUI, Gemini), with an async job queue and a React and TypeScript front end. |
| [**social-media-agent**](https://github.com/mysanjeev99/social-media-agent) | Multi-agent Streamlit app: scrapes recent news, summarizes with an LLM, checks content safety and formats a social post. |

## Platform and infrastructure

| Project | Technology |
|---|---|
| **MCP Platform** 🔒 | A gateway that hosts several MCP servers behind OAuth, authorization, rate limiting and audit logging, with an admin UI. Docker Compose and Coolify. |
| **Authenticator** 🔒 | A self-hosted OpenID Connect and OAuth 2.0 identity provider with modern flows, MFA and passkeys, audit logging and per-application access. Node, Fastify, PostgreSQL, Redis. |

## Models and generative AI

| Project | Technology |
|---|---|
| **unsloth-finetune** 🔒 | Multimodal fine-tuning of Gemma 3n with Unsloth. |
| [**ImageGen-Stable-Diffusion-3.5-Quantized-Local**](https://github.com/mysanjeev99/ImageGen-Stable-Diffusion-3.5-Quantized-Local) | Download and quantize Stable Diffusion 3.5 for local image generation. |
| [**conversational_LLM**](https://github.com/mysanjeev99/conversational_LLM) | Proof-of-concept GPT-2 based conversational model with text-to-speech. |
| [**Face-Image-generation-using-nvidia-StyleGAN**](https://github.com/mysanjeev99/Face-Image-generation-using-nvidia-StyleGAN) | StyleGAN2 face generation trained on CelebA-HQ 256. |

## Earlier research projects

- [**Classifying-learners-cognitive-affective-states**](https://github.com/mysanjeev99/Classifying-learners-cognitive-affective-states-during-online-learning): classifies a student's state from images using a classifier plus pose estimation (MSc dissertation).
- [**MLEnd-AudioSegment_Detection**](https://github.com/mysanjeev99/MLEnd-AudioSegment_Detection): audio classification of hums and whistles with MFCC features.
- [**textclassifier_BERTMODEL**](https://github.com/mysanjeev99/textclassifier_BERTMODEL): BERT text classification.

## Tech stack

<p>
<img src="https://skillicons.dev/icons?i=py,pytorch,tensorflow,aws,kubernetes,docker,postgres,redis,fastapi,react,ts,git,linux,jenkins,grafana" alt="Tech stack icons" />
</p>

LangGraph · LangChain · MCP · Claude · GPT · Gemini · AWS Bedrock · pgvector · Qdrant · OpenSearch

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0e75b6,100:8957e5&height=90&section=footer" alt="" />
</div>

