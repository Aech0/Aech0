<div align="center">

# Vansh Narwani

**Software Engineer II · Unstitched (The One Click Designer) · Mumbai**

Sole architect of a generative-AI platform serving thousands of users — six production engines, eight AI providers, 15+ models — and of the One Click Auto dealer-marketing line.

[![Portfolio](https://img.shields.io/badge/vanshnarwani.com-E84A00?style=flat-square&logo=googlechrome&logoColor=white)](https://vanshnarwani.com/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vansh-narwani-464b9b217/)
[![Email](https://img.shields.io/badge/vanshnarwani10@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:vanshnarwani10@gmail.com)

</div>

---

## What I build

I build the unglamorous machinery behind glamorous products: AI pipelines, render farms, marketplaces, and apps that hold up when real users hit them.

Two years ago I was the only developer at Unstitched. I shipped the entire video-template platform alone, then designed the company's generative-AI product end to end and was promoted to own it.

Alongside that, I build products for clients as a freelancer: a creator-brand marketplace, a subscription learning app, a field-operations portal, and a D2C store. Each one built solo, from brief to production.

## Right now

**OCD AI Studio** — the generative-AI platform behind [theoneclickdesigner.com](https://theoneclickdesigner.com/)

- **6 isolated engines** on 7 SQS queues, a JSON workflow runner with tiered parallel steps, per-tier DynamoDB checkpoints, per-branch fault isolation
- **8 AI providers** (OpenAI, Anthropic, Google, BytePlus, Kling, Runway, Freepik, Ideogram) behind one adapter contract with per-template model routing
- **Agentic generation pipelines**: a vision analyser and LLM planner fanning out to up to 10 parallel generators, turning one or two product photos into 8-image marketplace listing sets in about 2 minutes, 4-image packs in 25s, and 1080p product videos in ~139s
- **LLM-as-judge quality layer**: 5-dimension scoring on every output, in-engine QC regeneration, one-click AI Improvement
- **Scaled for concurrent users**: worker pools, job leases with heartbeat and auto-refunding reapers, a distributed per-model rate gate
- **Zero-code authoring**: new AI products ship as DynamoDB config, built and tested by non-engineers

**One Click Auto** — B2B dealer marketing for carmakers

- **Volvo** portal live in 7 days: 4 languages, 4 formats, client-side canvas baking, a 13-step guided tour, **live Facebook Graph API publishing with insights**
- **Tata Motors** wizard with Devanagari transliteration and AE video rendering
- **Maruti Suzuki** platform architecture for **5,000+ dealers**: HO / Agency / Dealer roles, approval state machine, KMS-encrypted content, WhatsApp Cloud API

**Freelance** — sole engineer and technical owner, using an AI-assisted Claude Code workflow

- **[Overdue](https://overdue.in/)**: creator-brand marketplace shipped in 10 weeks. Versioned pricing engine with zero constants in code, guarded deal state machine, double-entry escrow ledger. Cleared Meta App Review and Google OAuth verification first time
- **E Sikshya**: subscription learning app for Android and iOS. 154-chapter syllabus, RevenueCat billing with order-guarded webhooks, AES-256-GCM encrypted offline lessons
- **Kreed Sahayak**: approval and onboarding portal for ~760 field staff across 8 roles, built in a month for a repeat client. Config-driven state machine, append-only event log, 1,100+ tests

## Selected work

| Project | What it is | Stack |
|---|---|---|
| [OCD AI Studio](https://theoneclickdesigner.com/) | Multi-engine generative-AI platform, thousands of users | Node.js · SQS · DynamoDB · OpenAI · Claude · Gemini |
| [One Click Auto](https://theoneclickdesigner.com/volvo-demo) | Dealer-marketing line: Volvo portal live in 7 days, Maruti architecture for 5,000+ dealers | React · Facebook Graph API · WhatsApp Cloud API · Lambda |
| [Overdue](https://overdue.in/) | Creator-brand marketplace with pricing engine and escrow ledger, live | Next.js 16 · Express 5 · PostgreSQL · Prisma · AWS |
| E Sikshya | Subscription EdTech app for Android and iOS, private client build | React Native · Expo · AWS Lambda · DynamoDB · RevenueCat |
| Kreed Sahayak | Approval portal for ~760 field staff, private client build | TypeScript · DynamoDB · CloudFront · Lambda |
| [Render Pipeline](https://theoneclickdesigner.com/) | 500+ After Effects templates rendered on demand, 0.86s LCP storefront | Lambda · SQS · AE CLI · S3 · Three.js |
| [Glinte](https://glinte.in/) | D2C e-commerce brand, built solo, live and taking orders | React · Node.js · Razorpay · Shiprocket |

## Experience

**Software Engineer II** · Unstitched — The One Click Designer · 2025 → now
Own the generative-AI platform and the One Click Auto dealer line end to end. Architecture, scaling, quality, and security: led the response to a live extortion attempt and a 31-item hardening program that closed an admin-key bypass across 33 routes and an OTP account-takeover. Mentored 4 interns, converted one to full-time.

**Junior Developer** · Unstitched — The One Click Designer · Aug 2024 → 2025
Sole developer of the core platform: 500+ AE templates, distributed render pipeline, Node.js/Express API on Lambda under 85ms average, Razorpay billing, SES and Mailchimp automation.

**Freelance Full-Stack Engineer** · Independent · 2024 → now
Four products for three clients, each built solo alongside the day job: Overdue, E Sikshya, Kreed Sahayak for a repeat client, and Glinte.

**Web Development Intern** · Maekra (2024) · Kysi Global (2023)
Led both companies' primary website builds end to end.

## Stack

**Generative AI**
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic_Claude-191919?style=flat-square&logo=anthropic&logoColor=white)
![Gemini](https://img.shields.io/badge/Google_Gemini-4285F4?style=flat-square&logo=googlegemini&logoColor=white)
![Multi-agent](https://img.shields.io/badge/Multi--agent_LLMs-2E9EF7?style=flat-square)
![LLM-as-judge](https://img.shields.io/badge/LLM--as--judge-2E9EF7?style=flat-square)
![Model routing](https://img.shields.io/badge/Model_routing-2E9EF7?style=flat-square)

**Backend & Cloud**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![AWS Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white)
![SQS](https://img.shields.io/badge/SQS-FF4F8B?style=flat-square&logo=amazonsqs&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white)
![S3](https://img.shields.io/badge/S3-569A31?style=flat-square&logo=amazons3&logoColor=white)
![EC2](https://img.shields.io/badge/EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white)
![CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F8B?style=flat-square&logo=amazoncloudwatch&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

**Frontend & Mobile**
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white)
![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=flat-square&logo=greensock&logoColor=black)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

**Security, Payments & Ops**
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![WAF](https://img.shields.io/badge/WAF_·_CSP_·_OWASP-232F3E?style=flat-square)
![Rate limiting](https://img.shields.io/badge/Distributed_rate_limiting-232F3E?style=flat-square)
![PM2](https://img.shields.io/badge/PM2-2B037A?style=flat-square&logo=pm2&logoColor=white)
![Razorpay](https://img.shields.io/badge/Razorpay-0C2451?style=flat-square&logo=razorpay&logoColor=white)
![RevenueCat](https://img.shields.io/badge/RevenueCat-F25A5A?style=flat-square)
![Facebook Graph API](https://img.shields.io/badge/Facebook_Graph_API-0866FF?style=flat-square&logo=facebook&logoColor=white)
![WhatsApp](https://img.shields.io/badge/WhatsApp_Cloud_API-25D366?style=flat-square&logo=whatsapp&logoColor=white)

---

<div align="center">

Mumbai, India · Taking on select freelance projects alongside my role at Unstitched · [vanshnarwani.com](https://vanshnarwani.com/)

</div>
