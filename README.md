# Awesome Form Builder 📝✨

<p align="center">
  <img src="assets/banner.svg" alt="Awesome Form Builder Banner" width="100%">
</p>

<p align="center">
  <strong>Curated Directory of Top Form Builder SaaS Platforms, Survey Logic Engines & Open-Source Form Frameworks</strong>
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Form-Builder/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Form-Builder?style=social&color=white" alt="GitHub Stars"></a>
  <a href="https://github.com/sindresorhus/awesome"><img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" alt="Awesome"></a>
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs Welcome">
  <img src="https://img.shields.io/badge/License-CC0_1.0-blue.svg" alt="License">
</p>

---

## 📌 Overview & Scope

The modern **Form Builder ecosystem** powers online data capture across businesses, from lead generation and checkout flows to internal surveys, onboarding funnels, and enterprise workflows. 

Whether you are seeking:
- 🚀 **High-converting no-code SaaS builders** with native payment processing, advanced CRM integrations, and HIPAA/GDPR compliance.
- 💻 **Developer-first open-source libraries** to embed customizable drag-and-drop form designers directly into React, Vue, Angular, or Next.js apps.
- 🛡️ **Self-hosted and privacy-first form backends** to retain complete database ownership without SaaS lock-in or recurring monthly quotas.

This guide provides a comprehensive, benchmarked comparison of both hosted commercial platforms and self-hosted open-source software (FOSS).

---

## 📈 Sector Overview & Market Dynamics

> 💡 **Market Size & Valuation**: The global online form builder and survey software market was valued at approximately **$9.5 billion in 2023** and is projected to expand at an estimated CAGR of **14.2%** to reach over **$24.8 billion by 2030**, accelerated by digital workflow automation and omnichannel customer data collection.
>
> 🌐 **Market Structure**: The sector is **moderately fragmented**: while massive incumbents (Alphabet/Google Forms, Shopify, and SurveyMonkey/Symphony Technology Group) dominate baseline free and broad survey volume, high fragmentation persists in niche verticals (conversational forms like Typeform, privacy/minimalism like Tally, and developer-embedded headless form engines).

---

## 📑 Table of Contents

- [📈 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [☁️ Top SaaS & Hosted Form Builders](#️-top-saas--hosted-form-builders)
- [🔓 Open-Source GitHub Projects & Libraries](#-open-source-github-projects--libraries)
  - [⭐ Open-Source Comparison by Star Count](#-open-source-comparison-by-star-count)
  - [📦 Deep Dive: Developer Libraries & Self-Hosted Solutions](#-deep-dive-developer-libraries--self-hosted-solutions)
- [🤝 How to Contribute](#-how-to-contribute)
- [⚖️ Disclaimer & Privacy Regulations](#️-disclaimer--privacy-regulations)

---

## ☁️ Top SaaS & Hosted Form Builders

The following table lists leading commercial and hosted form platforms, **ranked in descending order by company valuation / estimated revenue**.

| Rank | SaaS Platform 🏢 | Valuation / Revenue 💰 | Starting Paid Price 🏷️ | Free Tier Limits / Trial Limits 🎁 | Key Strengths & Workflows ⚡ |
|:---:|:---|:---|:---|:---|:---|
| 1 | **[Google Forms](https://forms.google.com/)** | **~$2.2 Trillion** market cap *(Alphabet)* | Free *(Google Workspace from $6.00/user/month)* | **100% Free Forever**: Unlimited forms, questions, and responses (uses Google Drive 15 GB shared storage quota) | Zero-friction setup, seamless Google Sheets sync, real-time collaboration, instant quizzes. |
| 2 | **[Shopify Forms](https://apps.shopify.com/shopify-forms)** | **~$110 Billion** market cap *(Shopify)* | Free *(Included with Shopify subscription starting at $39.00/month)* | **Free with any Shopify plan**: Unlimited lead capture forms, overlays, and inline popups | Direct Shopify admin integration, 200M+ Shop user autofill, discount codes, customer tags. |
| 3 | **[SurveyMonkey](https://www.surveymonkey.com/)** | **~$1.5 Billion** valuation *(STG / ~$450M annual revenue)* | **$25.00/month** *(billed annually at $300/year)* | **Free Forever Basic Plan**: Unlimited surveys, up to 10 questions/survey, and 25 responses viewed/survey | Industry-standard survey logic, statistical benchmarking, audience panels, advanced NPS metrics. |
| 4 | **[Typeform](https://www.typeform.com/)** | **~$935 Million** valuation *(Series C / ~$100M+ ARR)* | **$29.00/month** *(Basic tier, 100 responses/month)* | **Free Forever Plan**: Up to 3 forms, 10 questions per form, and 10 responses/month limit | Pioneer in conversational one-question-at-a-time UX, video embeds, branching logic, Zapier connectors. |
| 5 | **[Formstack](https://www.formstack.com/)** | **~$500 Million** valuation *(PSG / ~$70M+ ARR)* | **$50.00/month** *(billed annually; $59/mo monthly)* | **14-day Free Trial only**: Full access to trial tier (up to 5 forms and 100 submissions during trial period) | Enterprise workflow automation, HIPAA compliance, native e-signatures, document generation. |
| 6 | **[Jotform](https://www.jotform.com/)** | **~$200 Million** valuation *(Bootstrapped / ~$50M+ ARR)* | **$34.00/month** *(Bronze tier, 1,000 monthly submissions)* | **Free Forever Starter Plan**: 5 active forms, 100 monthly submissions, 100 MB upload storage, 10 payment submissions | 10,000+ templates, drag-and-drop table views, approval flows, PDF builders, HIPAA options. |
| 7 | **[Wufoo](https://www.wufoo.com/)** | **~$50 Million** valuation *(Part of SurveyMonkey/STG)* | **$19.00/month** *(billed annually; $14.08/mo)* | **Free Forever Plan**: Up to 5 forms, 10 fields per form, 100 submissions/month, and 1 admin user | Battle-tested form builder, integrated payment processing (Stripe, PayPal), custom confirmation logic. |
| 8 | **[Paperform](https://paperform.co/)** | **~$15 Million** valuation *(Bootstrapped / ~$5M ARR)* | **$24.00/month** *(Essentials tier, 1,000 submissions/month)* | **14-day Free Trial only**: Unlimited forms and features with test submissions during 14 days | Document-like visual form editing, complex calculations, booking & scheduling, Stepper workflow automations. |
| 9 | **[123FormBuilder](https://www.123formbuilder.com/)** | **~$10 Million** valuation *(Bootstrapped / ~$4M ARR)* | **$37.00/month** *(billed annually; $45/mo monthly)* | **Free Forever Basic Plan**: Up to 5 forms, 10 fields per form, and 100 submissions/month | Multi-language forms, compliance workflows, Salesforce/CRM integrations, file uploads. |
| 10 | **[Tally](https://tally.so/)** | **~$6 Million** valuation *(Bootstrapped / ~$1.5M ARR)* | **$29.00/month** *(Tally Pro or $290/year)* | **Generous Free Forever Plan**: Unlimited forms and unlimited submissions without paying (5% commission on payments) | Notion-like document experience, keyboard shortcuts, free conditional logic, custom domains on Pro. |

---

## 🔓 Open-Source GitHub Projects & Libraries

For engineering teams looking to retain control, embed builders into existing web applications, or deploy self-hosted form infrastructure.

### ⭐ Open-Source Comparison by Star Count

All repositories are sorted in descending order by GitHub stargazers count:

| Rank | Repository & Star Badge 🌟 | Primary Category 🏷️ | Stack / Technologies 🛠️ | Key Capabilities & Architecture 🚀 |
|:---:|:---|:---|:---|:---|
| 1 | **[Formbricks](https://github.com/formbricks/formbricks)** [![Stars](https://img.shields.io/github/stars/formbricks/formbricks?style=social&color=white)](https://github.com/formbricks/formbricks/stargazers) | Self-Hosted Survey Suite | Next.js, TypeScript, Tailwind, Prisma | Enterprise experience management platform, multi-channel micro-surveys, granular audience targeting, in-app popups, and self-hostable Docker container. |
| 2 | **[Formily](https://github.com/alibaba/formily)** [![Stars](https://img.shields.io/github/stars/alibaba/formily?style=social&color=white)](https://github.com/alibaba/formily/stargazers) | Form Framework & Builder | React, Vue 2/3, TypeScript, RxJS | Enterprise-grade dynamic form solution from Alibaba; JSON Schema-driven, state-machine driven reactive forms, extreme high-performance rendering. |
| 3 | **[HeyForm](https://github.com/heyform/heyform)** [![Stars](https://img.shields.io/github/stars/heyform/heyform?style=social&color=white)](https://github.com/heyform/heyform/stargazers) | Standalone Form Platform | Node.js, React, MongoDB, Redis | Turnkey open-source conversational form builder alternative to Typeform; drag-and-drop question builder, conditional jumps, webhook triggers. |
| 4 | **[OpnForm](https://github.com/OpnForm/OpnForm)** [![Stars](https://img.shields.io/github/stars/OpnForm/OpnForm?style=social&color=white)](https://github.com/OpnForm/OpnForm/stargazers) | Self-Hosted Form App | Laravel, Vue.js, Tailwind, MySQL | Beautiful self-hosted open-source alternative to Typeform and Jotform; custom domains, email notifications, webhooks, analytics, and password protection. |
| 5 | **[jQuery formBuilder](https://github.com/kevinchappell/formBuilder)** [![Stars](https://img.shields.io/github/stars/kevinchappell/formBuilder?style=social&color=white)](https://github.com/kevinchappell/formBuilder/stargazers) | Embedded Builder Plugin | JavaScript, jQuery | Battle-tested drag-and-drop form creator; serializes directly to JSON/XML, multilingual UI, extensible custom field registry. |
| 6 | **[shadcn Form Builder](https://github.com/shadcn-labs/form-builder)** [![Stars](https://img.shields.io/github/stars/shadcn-labs/form-builder?style=social&color=white)](https://github.com/shadcn-labs/form-builder/stargazers) | Component Generator | Next.js, React, shadcn/ui, Zod | Visual form designer that exports production-ready React Hook Form + Zod schema code directly utilizing shadcn/ui component standards. |
| 7 | **[OhMyForm](https://github.com/ohmyform/ohmyform)** [![Stars](https://img.shields.io/github/stars/ohmyform/ohmyform?style=social&color=white)](https://github.com/ohmyform/ohmyform/stargazers) | Self-Hosted Platform | Node.js, Vue.js, MongoDB | Community successor to TellForm; responsive mobile-friendly forms, multi-language support, custom webhooks, and analytics dashboard. |
| 8 | **[Uniforms](https://github.com/vazco/uniforms)** [![Stars](https://img.shields.io/github/stars/vazco/uniforms)](https://github.com/vazco/uniforms/stargazers) | Schema-to-Form Library | React, TypeScript, Zod, JSONSchema | Generates React forms automatically from any data schema (GraphQL, Zod, Yup, SimpleSchema); supports AntD, Bootstrap, Material-UI, and Semantic. |
| 9 | **[formio.js](https://github.com/formio/formio.js)** [![Stars](https://img.shields.io/github/stars/formio/formio.js?style=social&color=white)](https://github.com/formio/formio.js/stargazers) | Enterprise Form Engine | JavaScript, TypeScript, CSS3 | JSON-powered form renderer and visual drag-and-drop builder; powers complex enterprise portal architectures with dynamic conditional calculations. |
| 10 | **[Vueform](https://github.com/vueform/vueform)** [![Stars](https://img.shields.io/github/stars/vueform/vueform?style=social&color=white)](https://github.com/vueform/vueform/stargazers) | Vue Form Framework | Vue 3, TypeScript, Tailwind | Comprehensive form framework and drag-and-drop visual builder for Vue.js; 50+ element types, nested groups, multi-step wizards, and i18n support. |
| 11 | **[SurveyJS Creator](https://github.com/surveyjs/survey-creator)** [![Stars](https://img.shields.io/github/stars/surveyjs/survey-creator?style=social&color=white)](https://github.com/surveyjs/survey-creator/stargazers) | Embedded Survey Designer | React, Angular, Vue, TypeScript | Mature drag-and-drop survey and form designer component; comprehensive JSON schema output, condition editors, CSS theme customizer. |
| 12 | **[Forms.md](https://github.com/formsmd/formsmd)** [![Stars](https://img.shields.io/github/stars/formsmd/formsmd?style=social&color=white)](https://github.com/formsmd/formsmd/stargazers) | Headless Form Library | JavaScript, TypeScript, CSS | Developer-first multi-step form library replicating Typeform conversational UX with pure JavaScript/TypeScript; supports conditional jumps and RTL layouts. |
| 13 | **[Formcn](https://github.com/Alibey-10/formcn)** [![Stars](https://img.shields.io/github/stars/Alibey-10/formcn?style=social&color=white)](https://github.com/Alibey-10/formcn/stargazers) | UI Form Generator | React, TypeScript, Tailwind | Visual form builder specifically engineered for shadcn/ui components; features Formcn AI field scaffolding and clean copy-paste JSX output. |
| 14 | **[Nextcloud Forms](https://github.com/nextcloud/forms)** [![Stars](https://img.shields.io/github/stars/nextcloud/forms?style=social&color=white)](https://github.com/nextcloud/forms/stargazers) | Private Cloud App | PHP, Vue.js, Nextcloud API | Native form and survey app for self-hosted Nextcloud instances; strict on-premises data isolation, anonymous submission links, and CSV exports. |

---

### 📦 Deep Dive: Developer Libraries & Self-Hosted Solutions

#### 🛠️ Visual Embedded Builders (Component Libraries)
- **[SurveyJS Creator](https://github.com/surveyjs/survey-creator)**: The benchmark for embedding a complete graphical form editor inside an existing web application (React, Angular, Vue, Knockout). Form models serialize into clean JSON.
- **[Vueform](https://github.com/vueform/vueform)**: The definitive form framework for the Vue 3 ecosystem, featuring an interactive drag-and-drop designer and full Tailwind CSS styling control.
- **[kevinchappell/formBuilder](https://github.com/kevinchappell/formBuilder)**: Traditional yet rock-solid jQuery-based form designer ideal for legacy system modernization or straightforward web tools.
- **[formio.js](https://github.com/formio/formio.js)**: Robust front-end JavaScript engine for rendering and visually designing schema-driven forms with deep calculation rules.

#### ⚡ Code Generators & Schema-First Tools
- **[shadcn Form Builder](https://github.com/shadcn-labs/form-builder)** & **[Formcn](https://github.com/Alibey-10/formcn)**: Modern developer tools creating type-safe forms with React Hook Form, Zod, and shadcn/ui primitives.
- **[Formily](https://github.com/alibaba/formily)**: High-performance, schema-driven reactive form architecture crafted by Alibaba to handle highly complex form lifecycles.
- **[Uniforms](https://github.com/vazco/uniforms)**: Zero-effort schema-to-form generation compatible with Zod, JSON Schema, GraphQL, and popular UI kits.
- **[Forms.md](https://github.com/formsmd/formsmd)**: Lightweight, zero-dependency script for building multi-step conversational forms.

#### 🏡 Self-Hosted Turnkey SaaS Replacements
- **[Formbricks](https://github.com/formbricks/formbricks)**: Best-in-class open-source survey and feedback suite with modular in-app widgets and Dockerized self-hosting.
- **[HeyForm](https://github.com/heyform/heyform)**: Complete conversational form alternative to Typeform featuring standalone user authentication and webhook dispatching.
- **[OpnForm](https://github.com/OpnForm/OpnForm)**: Open-source Laravel/Vue web application designed for fast, elegant form creation with webhook and email support.
- **[Nextcloud Forms](https://github.com/nextcloud/forms)**: Zero-setup privacy-first questionnaire creator for internal organizations running on Nextcloud.

---

## 🤝 How to Contribute

Contributions to expand this list are warmly welcomed! 🙌

1. 🍴 **Fork** this repository.
2. 🌿 **Create a new branch** (`git checkout -b feature/add-new-form-tool`).
3. 📝 **Add your entry** following the tabular format above:
   - For SaaS tools: Include verified pricing, explicit free tier / trial terms, and corporate valuation/revenue estimates.
   - For Open-Source projects: Include active GitHub link, current star count badge (`style=social&color=white`), and core technical stack.
4. 🚀 **Commit your changes** (`git commit -m 'feat: Add [ToolName] to form builder list'`).
5. 📬 **Open a Pull Request** with a brief summary explaining the tool's uniqueness.

---

## ⚖️ Disclaimer & Privacy Regulations

- 🔍 **Community Maintained**: This directory is maintained for informational and educational purposes. Mentions do not imply commercial endorsement.
- 🔒 **Data Privacy & Compliance**: When collecting end-user personal information, ensure compliance with **GDPR**, **CCPA/CPRA**, and local privacy statutes. Payment processing must strictly adhere to **PCI DSS** standards, and healthcare intake workflows require **HIPAA-compliant** Business Associate Agreements (BAA).
- 📜 **Software Licensing**: Verify commercial licensing for open-source libraries before bundling them into commercial software distributions.

---

<p align="center">
  <sub>Maintained with ❤️ by the open-source community for developers, founders, and growth teams worldwide.</sub>
</p>
