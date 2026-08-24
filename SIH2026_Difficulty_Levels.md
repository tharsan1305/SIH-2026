# SIH 2026 — Problem Statements by Difficulty Level (Easy / Medium / Difficult)

**Purpose:** Helps students quickly filter problem statements based on their team's skill level, time available, and hardware access.  
**Source:** Official SIH 2026 problem list (226 PS) + independent feasibility analysis (not an official SIH rating).

**How difficulty was judged:**
- 🟢 **Easy** — mostly software, open/public data available, standard tech stack (web/app/dashboard/basic ML), buildable by a student team in the hackathon timeframe.
- 🟡 **Medium** — needs solid ML/domain knowledge, harder data access, or moderate hardware/integration work — doable with scope reduction.
- 🔴 **Difficult** — requires specialized domain expertise, restricted/defense data, custom hardware/fabrication, advanced research-level AI, or safety-critical engineering.

⚪ = AICTE "Student Innovation" open slots (no fixed problem — difficulty depends on what the team proposes).

---

## 🟢 EASY (Best for beginners / first-time SIH teams)

| PS No. | Type | Organization | Title | Why Easy |
|---|---|---|---|---|
| SIH26028 | Software | Ministry of Railways | Dynamic Forecast of ETA for Coaching Trains | Public train-data patterns, standard time-series problem |
| SIH26035 | Software | Consumer Affairs | Test Report Generation for NAWI | Rule-based report generator, no complex AI needed |
| SIH26036 | Software | Consumer Affairs | Online Verification System for Weighing Instruments | Standard CRUD/verification web app |
| SIH26043 | Software | Govt of Jharkhand | Crowdsource Societal Challenges Platform | Generic civic-tech web app |
| SIH26044 | Software | Ministry of Ayush | Academia-Industry Collaboration Portal | Standard portal/matching app |
| SIH26047 | Software | Ministry of Ayush | Patient Case-Taking Software | Form-driven EMR-style app |
| SIH26063 | Software | MoES | Polar Science Outreach & Media Portal | Content/CMS-style website |
| SIH26075 | Software | MoES | Capacity Connect LMS Portal | Standard LMS (Moodle-style) build |
| SIH26076 | Software | MoES | Personalized Mausam App Homepage | Simple personalization/ranking logic |
| SIH26089 | Software | Ministry of Cooperation | Cooperative Gig Services Platform | Standard marketplace app (Uber/UrbanClap pattern) |
| SIH26092 | Software | MoSJE | AI-Driven Scheme Matching for Entrepreneurs | Rule-based/simple recommendation engine |
| SIH26095 | Software | MoSJE | Smart Real-Time Monitoring & Inspection App | Standard field-inspection mobile app |
| SIH26099 | Software | Petroleum & Natural Gas | Material Code Standardization | Deterministic data-cleaning/MDM problem |
| SIH26103 | Software | MoSPI | Web-based Project-Monitoring Platform | Standard dashboard/PMIS app |
| SIH26107 | Software | Consumer Affairs | AI Assistant for Indian Standards/BIS | RAG chatbot — well-documented pattern |
| SIH26108 | Software | Consumer Affairs | AI Recommendation Engine for IS Standards | RAG/search-based, standard build |
| SIH26116 | Software | Autodesk | Urban Mixed-Use Design (Autodesk Revit) | Tool-based design challenge, no heavy backend AI |
| SIH26131 | Software | Govt of Maharashtra | Crop Disease/Pest Detection | Well-documented CV problem, public datasets (PlantVillage etc.) |
| SIH26132 | Software | Govt of Maharashtra | Market Linkage & Price Discovery for Farmers | Standard marketplace/price-comparison app |
| SIH26152 | Software | NTRO | Social Media Analytics | Standard NLP/sentiment-analysis pipeline |
| SIH26162 | Software | NTRO | Industrial Fire Detection (NASA FIRMS/OSM) | Public dataset (NASA FIRMS) + simple CV/alerting |
| SIH26173 | Software | ISRO | Multilingual TTS/STT (iTantra) | Bhashini/AI4Bharat open models available |
| SIH26188 | Software | MHA | Fake Identity & Document Screening | Off-the-shelf OCR + face-match libraries |
| SIH26031 | Software | Consumer Affairs | Quality Assessment/Grading of Onions | Standard CV classification task |
| SIH26042 | Software | Govt of Jharkhand | Vernacular Pedagogy & Real-Time Translation | Bhashini APIs directly usable |
| SIH26056 | Software | MoSPI | Real-time Airfare Price Index (Web Scraping) | Straightforward scraping + indexing pipeline |
| SIH26124 | Software | BEL | AI Urban Intelligence via Transit Fleet | Standard GPS/mobility-data dashboard |
| SIH26134 | Software | Govt of Maharashtra | Aligning Skill Programs with Industry | Dashboard/gap-analysis app |
| SIH26135 | Software | Govt of Maharashtra | Employment Outcomes Tracking | Standard analytics dashboard |
| SIH26090 | Software | MoSJE | Market Linkage for Marginalized Artisans | Standard e-commerce/cataloging app |
| SIH26091 | Software | MoSJE | Business Advisory for Rural Micro-Entrepreneurs | Chatbot/advisory app, low complexity |
| SIH26198 | Software | AICTE | Student Innovation (Transportation theme) | ⚪ Open — pick an easy angle |
| SIH26206 | Software | AICTE | Student Innovation (Disaster Mgmt theme) | ⚪ Open — pick an easy angle |

**Total Easy: ~31 PS** *(good starting shortlist for first-time teams)*

---

## 🟡 MEDIUM (Solid team with ML/data skills, 1–2 prior hackathons)

| PS No. | Type | Organization | Title | Why Medium |
|---|---|---|---|---|
| SIH26001 | Software | MDoNER | Landslide Risk Monitoring System (NER) | Needs real geospatial + ML, but public research exists to build on |
| SIH26013 | Software | Rural Development | Multi-source Geospatial Data Harmonization | GIS integration work, moderate complexity |
| SIH26068 | Software | MoES | WeatherGPT Conversational AI | LLM + weather-data integration, needs data-pipeline work |
| SIH26069 | Software | MoES | National Weather Big Data Platform | Needs to handle large-scale data engineering |
| SIH26071 | Software | MoES | Rainfall EWS + Inundation Prediction | Real ML modeling + hydrology domain knowledge |
| SIH26072 | Software | MoES | Thunderstorm/Lightning Nowcasting | Needs domain-specific ML, moderate data access |
| SIH26073 | Software | MoES | AWS Anomaly Detection (Weather Stations) | Standard anomaly-detection ML, doable with scope cut |
| SIH26083 | Software | MoES | Heatwave EWS + Thermal Stress Index | ML + domain formula work |
| SIH26085 | Software | MoES | Urban Flood Nowcasting | Needs drainage+rainfall data fusion |
| SIH26094 | Software | MoSJE | Mental Health Distress Prediction | Sensitive domain, needs careful NLP/ML |
| SIH26104 | Software | AICTE | Voice-Cloning Impersonation Detection | Needs audio ML pipeline, some competition exists |
| SIH26105 | Software | AICTE | Cyber Risk Quantification & Investment Optimization | Needs security + finance-modeling knowledge |
| SIH26106 | Software | AICTE | Email Threat Detection & Forensic Intelligence | Needs email-parsing + threat-intel integration |
| SIH26109 | Hardware | Fisheries/Animal Husbandry | Bovine Mastitis Prediction | ML + basic sensor integration |
| SIH26111 | Software | Fisheries/Animal Husbandry | Rapid Feed & Silage Quality Testing | Needs domain calibration + ML |
| SIH26120 | Software | Oil India Ltd | Digital Twin (Well-to-Surface Optimization) | Simulation + domain engineering knowledge |
| SIH26127 | Software | BEL | City-Wide ANPR & Traffic Analytics | CV pipeline at scale, multi-camera fusion |
| SIH26137 | Software | Egreen Quanta | Quantum-Inspired Traffic Route Optimization | Needs optimization-algorithm knowledge |
| SIH26138 | Software | Egreen Quanta | Quantum-Inspired Fuel/Fleet Optimization | Same — optimization heavy |
| SIH26145 | Software | NTRO | Cyber Threats in Unidirectional IP Traffic | Needs networking + security depth |
| SIH26150 | Software | NTRO | Multi-Vendor DVR/NVR Forensic Tool | Needs reverse-engineering of file formats |
| SIH26153 | Software | NTRO | AI Network Attack Forecasting | Needs network-traffic ML pipeline |
| SIH26156 | Software | NTRO | Universal Log Pre-processing Framework | Needs handling of heterogeneous log formats |
| SIH26157 | Software | NTRO | SOC Assessment Analytics Tool | Needs security-domain + analytics knowledge |
| SIH26165 | Software | Oil India Ltd | NLP Engine for SIF Precursors in Safety Reports | Domain-specific NLP, needs labeled data effort |
| SIH26167 | Software | ISRO | SatQuery AI (Vision-Language for Remote Sensing) | Needs VLM fine-tuning knowledge |
| SIH26182 | Software | MHA | Crypto Wallet Attribution to VASPs | Needs blockchain-analytics knowledge |
| SIH26183 | Software | MHA | Fraud-Linked Crypto Exchange Detection | Same domain, graph analytics needed |
| SIH26184 | Software | MHA | Predictive Analytics for Cybercrime Cash Withdrawal | Needs geo + fraud-pattern modeling |
| SIH26189 | Software | MHA | AI Criminal Network Analysis | Graph-analytics/NLP heavy |
| SIH26192 | Software | MHA | Flash Flood Prediction (Hilly Regions) | Multi-source data fusion, hydrology knowledge |
| SIH26037 | Software | MathWorks | Adaptive Path Planning for AVs (Indian Roads) | Robotics/autonomy algorithms |
| SIH26126 | Software | BEL | Vision-Based Autonomous Navigation (UGV) | CV + robotics integration |
| SIH26158 | Software | NTRO | Drone Video → 3D Model (Single Pass) | Photogrammetry pipeline, moderately complex |
| SIH26041 | Software | Govt of Jharkhand | AR-Based Vocational Training Simulator | AR/3D development skills needed |
| SIH26139 | Software | Egreen Quanta | Hybrid Quantum ML for Disease Detection | Needs quantum-ML library familiarity |
| SIH26178 | Hardware | Qualcomm | Resilient Env-Monitoring Network | IoT + edge-AI integration |
| SIH26180 | Hardware | Qualcomm | Field Smart-Farming Assistant | IoT + on-device ML |
| SIH26181 | Hardware | Qualcomm | Secure AI Personal Health Companion | Wearable integration + security layer |
| SIH26179 | Hardware | Qualcomm | AI Retail Intelligence Platform | Edge-AI + camera integration |

**Total Medium: ~39 PS** *(good for teams with some ML/domain background)*

---

## 🔴 DIFFICULT (Advanced teams — deep domain expertise, hardware fabrication, or restricted data)

| PS No. | Type | Organization | Title | Why Difficult |
|---|---|---|---|---|
| SIH26025 | Hardware | Ministry of Coal | Real-Time Mine Subsidence Monitoring | Needs custom sensor hardware + InSAR-level modeling |
| SIH26029 | Hardware | Consumer Affairs | High-Current Short-Circuit Test System | Electrical safety-test rig fabrication |
| SIH26030 | Hardware | Consumer Affairs | Cable Specimen Preparation System | Precision lab-automation hardware |
| SIH26050 | Hardware | DRDO | Anti-Drone System (High-Altitude) | Restricted defense domain, hard fabrication |
| SIH26052 | Hardware | DRDO | Adaptive Noise Cancellation (Defence) | Signal-processing hardware, defense-grade |
| SIH26054 | Software | DRDO | Digital Twin for UAV Piston Engines | Aerospace-engineering domain expertise required |
| SIH26055 | Software | DRDO | Smart Scan Strategy for Electronic Warfare | Classified/restricted domain |
| SIH26058 | Hardware | MoES | SDR Sonar Transmitter for AUVs | RF + underwater acoustics hardware |
| SIH26065 | Hardware | MoES | Autonomous Ocean Observation Platform | Marine robotics, expensive fabrication |
| SIH26098 | Hardware | Ministry of Defence | Precision Guidance & Fuze for 155mm Shell | Munitions engineering — extremely restricted |
| SIH26112 | Hardware | Autodesk | Modular AMR Platform (Warehouse) | Full robotics-hardware build, costly BOM |
| SIH26113 | Hardware | Autodesk | Human Augmentation Tech (Rehab/Mobility) | Exoskeleton/biomech engineering |
| SIH26118 | Hardware | MRPL | H2S Exposure-Dosimeter Wristband | Chemical-sensor hardware, calibration-heavy |
| SIH26144 | Hardware | NTRO | Micro Barometer Infrasound Sensor | Precision-sensor fabrication |
| SIH26149 | Software | NTRO | Secure Data Erasure & File Recovery | Needs deep filesystem/low-level programming |
| SIH26151 | Software | NTRO | Dark Web Threat Actor De-anonymization | Advanced OSINT + Tor-network research |
| SIH26159 | Software | NTRO | SecureMailScope (Crypto Posture Assessment) | Deep cryptography protocol knowledge |
| SIH26160 | Software | NTRO | IPsec VPN Protocol Analyzer | Low-level protocol/packet analysis |
| SIH26164 | Software | NTRO | Enterprise Cryptographic Discovery Tool | Post-quantum crypto domain, enterprise-scale |
| SIH26166 | Software | ISRO | Chandrayaan-2 Image Correspondence | Advanced computer-vision research problem |
| SIH26169 | Software | ISRO | Virtual Camera Tracking (FSOC Terminal) | Optical-communication + tracking-systems expertise |
| SIH26171 | Software | ISRO | On-device Visual Perception for Browser Agents | Cutting-edge agentic-AI research |
| SIH26175 | Software | ISRO | DepthWizard (Single-View Height Estimation) | Advanced monocular-depth research |
| SIH26176 | Software | ISRO | ORCA Marine EcoSystem Reasoning (Agents) | Multi-agent AI research-level problem |
| SIH26185 | Hardware | MHA | Helmet-Mounted Conformal Antenna | RF/antenna-design engineering, defense-grade |
| SIH26049 | Hardware | DRDO | Equipment Reliability at High Altitude (Ladakh) | Extreme-environment materials engineering |
| SIH26007 | Hardware | Ministry of Steel | Mine Vehicle Safety in Fog/Low-Visibility | Sensor fusion + safety-critical systems |
| SIH26008 | Hardware | Ministry of Steel | Belt Joint Rupture Monitoring | Industrial-grade condition-monitoring hardware |
| SIH26010 | Hardware | Rural Development | Survey/Resurvey of Rural Agricultural Land | Large-scale field survey + GIS infra |
| SIH26026 | Hardware | Ministry of Railways | Quadruped/Handheld Narcotics Detection Device | Robotics + chemical-sensor integration |
| SIH26177 | Hardware | Qualcomm | Autonomous SAR Drone | Full autonomous-drone build, safety-critical |
| SIH26141 | Software | Egreen Quanta | Quantum-Inspired Cyber Threat Detection | Needs quantum-computing + crypto expertise |
| SIH26117 | Software | MRPL | Sovereign On-Prem Agentic AI Workbench | LLM infra + on-prem deployment engineering |

**Total Difficult: ~33 PS** *(only attempt with strong mentor support, prior domain experience, or serious hardware budget)*

---

## ⚪ AICTE "Student Innovation" Open Slots (34 total)

These have **no fixed problem** — difficulty entirely depends on what your team proposes. Use this list if you have your **own original idea** and want a flexible theme wrapper:

`SIH26193, SIH26194, SIH26195, SIH26196, SIH26197, SIH26198, SIH26199, SIH26200, SIH26201, SIH26202, SIH26203, SIH26204, SIH26205, SIH26206, SIH26207, SIH26208, SIH26209, SIH26210, SIH26211, SIH26212, SIH26213, SIH26214, SIH26215, SIH26216, SIH26217, SIH26218, SIH26219, SIH26220, SIH26221, SIH26222, SIH26223, SIH26224, SIH26225, SIH26226`

**Tip:** Pick the theme that best matches your team's strength, then scope your own idea at 🟢 Easy or 🟡 Medium difficulty — don't over-engineer an open slot.

---

## 📊 Quick Summary

| Difficulty | Count | Best For |
|---|---|---|
| 🟢 Easy | ~31 | First-time SIH teams, mostly-software backgrounds, 36–48 hr build |
| 🟡 Medium | ~39 | Teams with prior hackathon/ML experience |
| 🔴 Difficult | ~33 | Advanced teams, hardware access, domain mentors (defense/aerospace/crypto) |
| ⚪ Open (AICTE) | 34 | Teams with an original idea, flexible scoping |
| *(Remaining PS not yet tagged)* | ~89 | See full master list — will be added in next update |

---

**Disclaimer:** This difficulty classification is an **independent community-made assessment** to help students shortlist problem statements faster. It is **not an official SIH/AICTE rating**. Always cross-check the exact problem statement PDF on the official SIH portal before finalizing your submission.
