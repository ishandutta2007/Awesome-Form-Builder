# Awesome-Form-Builder

# Top Form Builder Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Drag-and-Drop Form Creation, Survey Logic & Self-Hosted Form Infrastructure*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Form Builders**. These tools enable organizations to create forms, surveys, and data collection workflows without writing code—handling conditional logic, payment collection, file uploads, and integrations with CRMs, email marketing, and spreadsheets.

**Examples** include Shopify Forms, Typeform, Jotform, Formstack, Wufoo, Paperform, 123FormBuilder, SurveyMonkey, Google Forms, and Tally (the category leaders).

**Open-source emphasis**: Form Builder is a domain where open-source tooling is **fragmented but increasingly viable for developer-led projects**. **Forms.md** provides a developer-first, Typeform-style multi-step form library for React/JavaScript with conditional logic and no SaaS dependency . **SurveyJS** offers a mature open-source survey creator with drag-and-drop UI, conditional logic, and JSON-driven forms . **Vueform** provides a comprehensive Vue form framework with a builder . **Formcn** generates production-ready shadcn/ui forms from a visual builder . For Nextcloud users, **Nextcloud Forms** offers a simple self-hosted form and survey app . However, no open-source project matches the **turnkey SaaS experience** (hosted pages, email notifications, payment collection, analytics) of Typeform or Jotform out of the box—most are libraries or self-hosted apps requiring deployment and configuration.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Shopify Forms](https://apps.shopify.com/shopify-forms)**  
  Free Shopify app for lead capture; adds pop-up, overlay, or inline forms to collect emails, phone numbers, and custom metafields; supports discounts, translations, and Shop user integration (200M+ users) . Included with Shopify plans.

- **[Typeform](https://www.typeform.com/)**  
  Interactive form builder known for conversational, one-question-at-a-time forms; features conditional logic, video questions, payment collection, and 300+ integrations. Pricing: Basic $29/mo (100 responses), Plus $59/mo (1,000 responses), Growth $349/mo (10,000 responses) .

- **[Jotform](https://www.jotform.com/)**  
  Comprehensive form builder with 10,000+ templates, payment processing, file uploads, and conditional logic. Free tier: 5 forms, 100 monthly responses; paid plans from $34/mo (Bronze, 1,000 responses) to $99/mo (Gold, 10,000 responses) . HIPAA-compliant options available on higher tiers.

- **[Formstack](https://www.formstack.com/)**  
  Enterprise form and workflow platform with document generation, e-signatures, and approval workflows. Features drag-and-drop forms, conditional logic, and 118+ integrations . Pricing varies; free trial available.

- **[Wufoo](https://www.wufoo.com/)**  
  Established form builder (now part of SurveyMonkey) with drag-and-drop interface, payment integration, and reporting. Pricing from ~$19/mo.

- **[Paperform](https://paperform.co/)**  
  Form builder emphasizing design flexibility and "human-first" forms; features AI form creation from PDFs/images (2026), conditional logic, and 400+ app integrations via Stepper workflow engine . Pricing: free personal tier, paid plans for business.

- **[123FormBuilder](https://www.123formbuilder.com/)**  
  Form builder with templates for surveys, orders, and registrations; pricing from $37/mo; users note ease of use but consider pricing high for low-volume needs .

- **[SurveyMonkey](https://www.surveymonkey.com/)**  
  Survey-focused platform with form capabilities; free tier (10 questions/survey, limited responses), Standard from SGD 59/mo (1,000 responses), Premier from SGD 150/mo (40,000 responses/year) .

- **[Google Forms](https://forms.google.com/)**  
  Free form builder within Google Workspace; unlimited forms and questions, real-time response analysis, Google Sheets integration, and collaborative editing . Limited design customization compared to dedicated builders.

- **[Tally](https://tally.so/)**  
  Free-first form builder with unlimited forms and responses on the free tier; features conditional logic, payment collection, and a clean editor.

## Open-Source GitHub Projects

### Developer Libraries (Embedded Form Builders)

- **[Forms.md (formsmd)](https://github.com/formsmd/formsmd)**  
  Open-source, developer-first Typeform alternative (683 GitHub stars, npm package); builds multi-step forms programmatically with JavaScript/TypeScript, supporting conditional logic (`displayCondition`, `jumpCondition`), choice/text/email inputs, and progress indicators . **No SaaS dependency**—initialize with a container and post URL; style with CSS or use the RTL variant . **The closest open-source equivalent to Typeform's conversational multi-step UX**, but requires coding to define forms (not drag-and-drop).

- **[SurveyJS (survey-creator)](https://github.com/surveyjs/survey-creator)**  
  Scalable open-source survey software with a **drag-and-drop form builder UI**; generates JSON-driven forms with conditional logic, branching, CSS theme editor, and GUI for logic configuration . Integrates into JavaScript applications (React, Vue, Angular, Knockout) . **The most mature open-source form builder with a visual editor**, though it is a library to embed in your app rather than a standalone SaaS.

- **[Vueform](https://github.com/vueform/vueform)**  
  Open-source form framework for Vue with 1,449 GitHub stars; includes a **drag-and-drop builder** (`vueform/builder`, 684 stars) and comprehensive form components with validation, conditional logic, and multi-language support . **The standard open-source form solution for Vue applications.**

- **[Formcn](https://github.com/Alibey-10/formcn)**  
  Open-source form builder that generates **production-ready forms using shadcn/ui components**; features single/multi-step forms, AI-assisted field scaffolding ("Formcn AI"), and type-safe client/server validation with Tailwind CSS . **Modern stack** (React, shadcn/ui) for developers wanting a component-based form generator rather than a hosted builder.

### Self-Hosted Form Applications

- **[Nextcloud Forms](https://github.com/nextcloud/forms)**  
  Simple form and survey app for Nextcloud; creates forms within your self-hosted Nextcloud instance with basic question types, response collection, and sharing via link . **Integrated with Nextcloud's ecosystem**—best for organizations already using Nextcloud for file storage and collaboration.

### Additional Strong Open-Source Options

- **Formbricks** — Open-source survey and experience management platform (not in search results but widely known); self-hostable with conditional logic, targeting, and integrations. **Verify current status before adoption.**
- **OhMyForm** — Open-source form builder (successor to TellForm); self-hosted with drag-and-drop editor, conditional logic, and CSV export. **Check maintenance status.**
- **Laravel Form Builder** — PHP package for programmatic form generation in Laravel applications; not a drag-and-drop builder but a developer tool for structured form creation.
- **Uniforms (Vazco)** — React library for building forms from any schema (JSON Schema, GraphQL, Zod, etc.); developer-focused, no visual builder .

**Frameworks for building custom systems**: For **Typeform-style multi-step forms**, use **Forms.md** as a library . For **drag-and-drop building within a React/Vue app**, use **SurveyJS** or **Vueform** . For **shadcn/ui projects**, **Formcn** generates forms from a visual builder . For **Nextcloud users**, **Nextcloud Forms** provides a built-in self-hosted app . No open-source project provides a complete hosted SaaS experience with email notifications, payment collection, and analytics—those require assembly or commercial platforms.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Form builders handling user submissions must comply with privacy regulations (GDPR, CCPA) and data security best practices; forms collecting payment data require PCI DSS compliance, and forms collecting health data may require HIPAA compliance.
- **Open-source form builders are strongest as libraries**—Forms.md, SurveyJS, and Vueform provide production-grade form creation within applications . However, **no open-source project matches the turnkey SaaS experience** of Typeform or Jotform (hosted pages, email notifications, payment processing, analytics) out of the box. Organizations requiring a hosted form solution should evaluate commercial platforms or plan for self-hosted deployment with Nextcloud Forms or similar.
- Verify license terms for commercial use; Forms.md is an npm package (check license), SurveyJS is open-source (check repository), and Vueform is open-source.

---

**Made for developers, marketers, operations teams, and data collection practitioners.**  
Let's make form building more open, but with clear eyes about the hosted SaaS convenience gap that remains.
