How long have the founders known one another and how did you meet? Have any of the founders not met in person?
We met as student representatives for our respective cohorts in the Computer Science and Technology department at Cambridge. We properly connected at the YC Cambridge dinner, where we discovered a shared obsession with building: both of us have won multiple hackathons at a national and greater level, and a personal connection to the healthcare problem we're solving. We've been working together in person since.

Who writes code, or does other technical work on your product? Was any of it done by a non-founder? Please explain.
Both founders are technical. Yasith has a background in software engineering, having shipped production systems in internships. Both him and Emily have won several hackathons, with Emily very recently having won 1/5th of the HackEurope prize pool coming first in 3 different tracks, and has built and sold software to a private clinic previously while an undergraduate. All technical work is done entirely by us, with no external contractors or non-founder contributors.

Describe what your company does in 50 characters or less.
Smarter triage, that evolves with your symptoms

What is your company going to make? Please describe your product and what it does or will do.
Catalynk is an AI triage and clinical documentation platform for medical practices. Patients describe their symptoms through a conversational interface, which uses their health history to assess urgency and generate a structured, prioritised referral for the clinic, replacing vague phone calls and receptionist guesswork. As patients wait for their appointment, they can log how symptoms evolve, building a timestamped record. By the time the doctor sits down with them, they have a full clinical summary: what happened, when, how it progressed, and what the likely differentials are. No wasted appointment time reconstructing a history the patient has already half-forgotten.
Where do you live now, and where would the company be based after YC?
Cambridge, United Kingdom / San Francisco, United States
Explain your decision regarding location.
The UK gives us immediate proximity to the NHS, one of the world's largest healthcare systems, which is actively piloting AI-assisted triage and appointment optimisation. This is a strong early validation and pilot market. However, the US is our primary target: the fragmented, insurance-driven healthcare system creates acute demand for intelligent triage and documentation tools, and the TAM is significantly larger. We plan to relocate to SF for YC and use the network to accelerate US market entry.

How far along are you?
We have a prototype with a live Firebase backend and an AI-powered chat interface for patient triage and symptom tracking, using Gemini for natural language understanding and urgency analysis. The doctor-facing dashboard is in active development. Our immediate next step is replacing the hosted LLM with fine-tuned models on existing clinical triage datasets, deployed on Amazon Bedrock, to improve accuracy and meet data privacy requirements. We are in early conversations with a private clinic for a pilot trial, this standalone MVP will be engineered to integrate directly with their existing workflows. In parallel, we are consulting dozens of doctors across our network, supported by a medical advisor, to validate clinical assumptions and refine the product.
How long have each of you been working on this? How much of that has been full-time? Please explain.
We have been working together for a few weeks, our time is currently split with academic commitments, but we are treating this with the urgency it requires.
What tech stack are you using, or planning to use, to build this product? Include AI models and AI coding tools you use.
Patient-facing app: React Native. Clinic-facing dashboard: React / Next.js. Backend: Firebase. AI stack: currently Gemini for conversational interface and urgency analysis; roadmap is to replace this with two purpose-built models hosted on AWS Bedrock, a general-purpose LLM for patient chat, and a fine-tuned model (based on Qwen2.5 or equivalent open-source architecture) trained on clinical triage datasets for urgency classification (suggesting appointments) and prioritisation. We use Codex and Claude Code for rapid prototyping and iteration.

Are people using your product?
No
When will you have a version people can use?
Within the next month. We are actively reaching out to private clinics in the UK for initial trials. 
Do you have revenue?
no
If you are applying with the same idea as a previous batch, did anything change? If you applied with a different idea, why did you pivot and what did you learn from the last idea?
N/A
If you have already participated or committed to participate in an incubator, "accelerator" or "pre-accelerator" program, please tell us about it.
N/A

Why did you pick this idea to work on? Do you have domain expertise in this area? How do you know people need what you're making?
Emily, my co-founder, spent the past year in and out of hospital with a serious medical condition requiring five emergency surgeries. The inefficiencies were relentless, repeating the same history to every new doctor, waiting weeks for five-minute consultations, zero coordination between departments. When she started tracking her own symptoms in a structured, thread-like format, it directly informed her surgeon's decision to perform a successful preventative operation. That moment crystallised the insight: the system doesn't need better intake forms, it needs continuous patient context that evolves in real time. On validation: I prototyped early versions at two hackathons, winning 1st place with a diabetes-focused implementation before we generalised to broader primary care. Emily has direct experience selling into UK GP practices. Our advisor is a trainee GP who has helped us map exactly where clinical workflows break down. We've spoken with multiple GPs, all of whom immediately recognised the thread-based symptom record as solving a genuine pain point they encounter daily.
Who are your competitors? What do you understand about your business that they don't?
The main players are Anima (400+ UK practices), AccuRx, Nabla, and Suki. They are all, in different ways, optimising the intake form, making it smarter, faster, or easier to complete. We are eliminating it entirely. More fundamentally, our competitors treat the appointment request as the endpoint. We treat it as the start of a continuous clinical conversation: our thread-based symptom tracking captures how a patient's condition evolves in real time, building a living record that is far more clinically valuable than any single snapshot. The static form is our only true competitor.
How do or will you make money? How much could you make?
We charge clinics an annual SaaS subscription: $5k for solo practices up to $20k for large multi-site operations, priced relative to appointment volume. The value creation is straightforward. the average clinic runs 30 appointments daily, and we save 5–10 minutes per appointment through better pre-consultation context. At £80/hour average clinical cost, that's £50–100k in recovered time per practice annually. We charge 10–20% of that value. The TAM is substantial. In the UK alone: 6,500 GP practices and ~15,000 specialist clinics gives a £200M addressable market. The US is the primary target — 67,000 primary care practices and 200,000+ specialist clinics at a $12.5k average yields a $3.3B TAM. At conservative penetration rates (10% UK, 5% US), that's ~$125M ARR. Administrative overhead in US healthcare exceeds $1 trillion annually, we are going after a small but very well-defined slice of a massive, structurally inefficient market that is actively looking for AI solutions. With aging populations and increasing health consciousness, this TAM only grows.
Which category best applies to your company?
B2B SaaS
If you had any other ideas you considered applying with, please list them. One may be something we've been waiting for. Often when we fund people it's to do something they list here and not in the main application.
AI-native hedge fund / quantitative trading infrastructure: using information asymmetry and insider trading detection in decentralised prediction markets (Yasith's master's thesis at Cambridge, currently showing promise) as the basis for a live alpha-generation framework. This was a request for startups.

