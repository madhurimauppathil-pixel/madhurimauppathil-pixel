<div align="center">

# Madhurima Mani

**Applied Machine Learning • NLP • AI Reliability & Trust • Cloud-Native Systems**

B.Sc. Computer Science — University of West London
Focus: Natural Language Processing, Predictive Modelling, AI Media Forensics

</div>

---

## Overview

 My core focus is natural language processing and AI reliability: how confidently a model should trust its own output, and how that output should be evaluated for accuracy and trustworthiness before it reaches a user. I extend that same thinking into predictive modelling and cloud-deployed applications, with an emphasis on shipping things that actually run in production.

I'm currently gaining hands-on experience across concurrent internships in AI, machine learning, and cloud computing, alongside academic research into deepfake detection and digital media trust.

What draws me to this space is the gap between a model that works in a demo and one people can actually rely on — that gap runs through most of my project work, from confidence scoring in classification systems to evaluating whether deepfake detection tools are reliable enough for real-world use.

---
## Research & Focus Areas

- Natural Language Processing
- Predictive Modelling & Forecasting
- Generative AI & LLM-integrated systems
- AI-Generated Media Detection (deepfake forensics)
- Cloud-Native Application Deployment

---

## Research

### Investigating the Impact of Deepfake Technology on Digital Media Trust and the Role of Detection Tools

*University of West London — Research Project Proposal*

**Author:** Madhurima Mani

This proposal examines whether AI-based deepfake detection tools can restore public trust in digital media, addressing a gap between two previously separate bodies of research: deepfake generation/detection accuracy and empirical trust erosion.

**Key Contributions**

- Identifies an unaddressed research gap: no existing empirical study connects *access to detection tools* with *restored trust in media*, despite separate literatures on deepfake creation, detection accuracy, and trust erosion.
- Traces the evolution of deepfake generation from GAN-based synthesis (Goodfellow et al., 2014) to diffusion models (Rombach et al., 2022), which lowered the compute barrier to producing high-quality synthetic media.
- Synthesises empirical trust research — including Vaccari & Chadwick's (2020) 2,500-respondent UK study showing that even disclaimer-labelled deepfakes measurably reduce trust in authentic video evidence.
- Proposes a mixed-methods design combining a controlled user-trust study with a technical detection benchmark built on the DFDC evaluation framework (Dolhansky et al., 2020) — a combination absent from current literature.

**Critical Gaps in Existing Research**

- No studies empirically link detection-tool access to restored trust in media
- CNN-based detectors generalise poorly to unseen GAN architectures (Rössler et al., 2019)
- Human and AI detection accuracy remain unreliable in real-world conditions (Groh et al., 2020)
- Existing commercial tools (Microsoft Video Authenticator, Deepware, Sensity AI) are untested for their effect on end-user trust, as distinct from raw detection accuracy

**Proposed Methodology:** pre/post-exposure trust survey (following Vaccari & Chadwick, 2020) combined with detection benchmarking on FaceForensics++ and DFDC datasets, evaluated for accuracy, false-positive rate, and processing speed.

**Companion implementation:** [deepfake-detector-benchmark](https://github.com/madhurimauppathil-pixel/deepfake-detector-benchmark) — the completed technical half of this proposal, benchmarking 3 pretrained detectors with real measured accuracy, false-positive rate, and latency.

---

## Selected Projects

### Lexara — Real-Time Sentiment Analysis Engine

- Classifies text as Positive, Negative, or Neutral in real time using TF-IDF vectorisation with Logistic Regression and Naïve Bayes
- Surfaces model confidence via softmax probability distributions rather than a bare label — an early version of the "how much should this output be trusted" question that runs through the deepfake research above
- Includes an interactive 3D globe visualisation that reacts to sentiment
- Evaluated using Precision, Recall, and F1 Score

### Clarix — NLP Support Ticket Classifier

- Automatically classifies support tickets across 6 categories
- Processed and labelled a dataset of 600 tickets for training and evaluation
- Built as an end-to-end NLP workflow from raw text to deployed classification — the same text-understanding problem underlying automated content and media classification at scale

### InsightFlow — Sales Forecasting Dashboard

**R² = 0.600**

- Forecasts sales trends using Linear Regression
- Interactive dashboard for exploring predictions against historical data

### ARIA — Generative AI Chatbot

- LLM-integrated conversational agent with automatic intent recognition (Help, Pricing, Support)
- Maintains full conversation context across a session
- Smart fallback escalates to a human when model confidence is low — a design principle (knowing when *not* to trust an AI output) directly relevant to the detection-tool reliability question in the research above
- Embeddable widget, deployed live on GitHub Pages

### Medical Expert System

- Rule-based forward-chaining inference engine for symptom-based diagnosis
- Supports manual input and interview-style symptom collection
- Confidence scoring and critical alert detection for high-risk cases

### CloudBus — International Transit Booking System

- Cloud-based bus pass booking platform with tamper-proof, cloud-verified QR boarding passes
- Real-time seat availability across international routes
- Secure payment flow with price-lock guarantee and auto-scaling infrastructure dashboard

### GeneView — DNA Sequence Viewer

- Research-grade genomics platform for visualising DNA sequences, detecting mutations, and annotating exon regions, built on BioPython and the NCBI Gene Database
- Gene library with clinical annotations (BRCA1, TP53, EGFR, KRAS, MECP2) including chromosome location, protein function, and known pathogenic variants sourced from ClinVar/LOVD
- Sequence comparison engine that classifies mutations as transitions or transversions
- Upload and analyse custom FASTA/CSV sequences, or search the NCBI database directly

---

## Technical Expertise

**Machine Learning & AI**
Python · Scikit-learn · TensorFlow · NLP · LLM Integration

**Web & Application Development**
Django · JavaScript · HTML5 · Full-Stack Development

**Cloud & Infrastructure**
Cloud Computing · GitHub Pages Deployment

**Design & UX**
UI/UX Design · Technical Content Writing

---

## Academic Background

**B.Sc. Computer Science**
University of West London (2024 - 2027)
Rak Branch Campus 

---

## Current Work

## Current Work

Actively seeking AI/ML Engineer, Data Scientist, and Machine Learning graduate opportunities for 2026. Currently building hands-on experience through concurrent internships in AI, machine learning, and cloud computing, alongside academic research into the impact of deepfake technology on digital media trust and the effectiveness of AI-powered detection tools.

---

## Contact

- LinkedIn: https://www.linkedin.com/in/madhurima-mani-503512366/
- Email: madhurimauppathil@gmail.com

*Open to graduate roles, research collaborations, and internship opportunities.*

## Tech Stack

![Python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=ffdd54)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-013243?style=flat&logo=numpy&logoColor=white)
![Django](https://img.shields.io/badge/django-%23092E20.svg?style=flat&logo=django&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=flat&logo=javascript&logoColor=%23F7DF1E)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-1572B6?style=flat&logo=css3&logoColor=white)
![C](https://img.shields.io/badge/c-A8B9CC?style=flat&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/c++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=flat&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VSCode-007ACC?style=flat&logo=visual-studio-code&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1?style=flat&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/mongodb-47A248?style=flat&logo=mongodb&logoColor=white)
![Firebase](https://img.shields.io/badge/firebase-FFCA28?style=flat&logo=firebase&logoColor=black)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Google Cloud](https://img.shields.io/badge/GoogleCloud-4285F4?style=flat&logo=googlecloud&logoColor=white)
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=flat&logo=figma&logoColor=white)
![Canva](https://img.shields.io/badge/Canva-00C4CC?style=flat&logo=canva&logoColor=white)
