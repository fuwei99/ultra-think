<div align="center">
<h1>Deep Think</h1>

![GitHub deployments](https://img.shields.io/github/deployments/u14app/gemini-next-chat/Production)
![GitHub Release](https://img.shields.io/github/v/release/lilingfengdev/deep-think)
![Docker Image Size](https://img.shields.io/docker/image-size/xiangfa/deep-research/latest)

[![License: MIT](https://img.shields.io/badge/License-MIT-default.svg)](https://opensource.org/licenses/MIT)

[![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white)](https://ai.google.dev/)
[![Next](https://img.shields.io/badge/Next.js-111111?style=flat&logo=nextdotjs&logoColor=white)](https://nextjs.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![shadcn/ui](https://img.shields.io/badge/shadcn/ui-111111?style=flat&logo=shadcnui&logoColor=white)](https://ui.shadcn.com/)

[![Vercel](https://img.shields.io/badge/Vercel-111111?style=flat&logo=vercel&logoColor=white)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fu14app%2Fdeep-research&project-name=deep-research&repository-name=deep-research)
[![Cloudflare](https://img.shields.io/badge/Cloudflare-F69652?style=flat&logo=cloudflare&logoColor=white)](./docs/How-to-deploy-to-Cloudflare-Pages.md)
[![PWA](https://img.shields.io/badge/PWA-blue?style=flat&logo=pwa&logoColor=white)](https://research.u14.app/)

[![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/lilingfengdev/deep-think)

</div>

# Automated DeepThink API

An automated reasoning engine designed to solve complex problems through a structured, iterative process. This project packages a sophisticated "thought process" into a simple-to-use API, inspired by methodologies capable of tackling challenges like IMO problems.

## Core Workflow

The engine employs a multi-step workflow to ensure robust and well-refined solutions:

1.  **Deconstruct:** The initial problem is broken down into smaller, manageable sub-problems.
2.  **Reason:** An initial solution or line of thought is generated for the sub-problem.
3.  **Critique:** The generated solution is critically evaluated to identify flaws, inconsistencies, or areas for improvement.
4.  **Optimize:** The solution is refined and improved based on the critique.
5.  **Iterate:** The Reason-Critique-Optimize cycle is repeated multiple times to progressively enhance the quality of the output.
6.  **Validation:** The solution passes through several internal checks to verify its correctness and coherence.
7.  **Consolidate:** The final, validated answers for all sub-problems are synthesized into a comprehensive final response.

## Features

-   **Bring Your Own Key (BYOK):** Easily integrate your own API keys.
-   **Multi-Provider Support:** Compatible with a wide range of major LLM providers:
    -   GPT
    -   DeepSeek
    -   Gemini
    -   Grok
    -   Claude
    -   Hugging Face
-   **General-Purpose Optimization:** While inspired by complex academic problems, the workflow is optimized for adaptability across various general-purpose tasks.
-   **API-Based:** Simple to integrate into your own applications and services.

## Acknowledgements

This project is based on the principles and architectures found in:
-   [u14app/deep-research](https://github.com/u14app/deep-research)
-   [lyang36/IMO25](https://github.com/lyang36/IMO25)



