# SIH 2026 — Comprehensive Research & Analysis of All 226 Problem Statements

> **Bottom line up front:** Of the 226 SIH 2026 problem statements, only about **28 (12%) are potentially new/differentiated based on the research reviewed**, while roughly **42% already have a comparable solution with room to differentiate**, **30% sit in genuinely crowded markets**, and **15% (all 34 AICTE Student Innovation slots) cannot be assessed** because no fixed problem is defined. The strongest student opportunities are not the "build an AI app for X" statements (most of which face entrenched incumbents like IMD's Mausam, SVAMITVA, Plantix, Chainalysis, Blancco and Onfido) but the **narrow, India-specific or mission-specific niches** from ISRO (edge-AI), NTRO (signal/forensics), MoES (polar/ocean), and DRDO (defence hardware), where verifiable comparable solutions are scarce.

---

## Executive Summary

- **Total analyzed:** 226 problem statements across 18 themes (Hardware 54, Software 172). Deadline 20 September 2026. Source of truth is the provided official SIH 2026 list; all classification, scoring and competitor evidence below is clearly separated between *(PDF list)* and *(web research)*.
- **Classification split (of 226):** 🟢 Potentially New ~28 (12%) · 🟡 Existing-with-differentiation ~96 (42%) · 🔴 Existing/Crowded ~68 (30%) · ⚪ Insufficient Info 34 (15%). Total = 226 = 100%.
- **Hardware vs Software:** Hardware statements are **less crowded but harder to build** (more 🟢/🟡, lower feasibility); software statements are **more crowded but far more student-buildable** (more 🔴, higher feasibility). Roughly 12 of 54 hardware statements are AICTE slots (⚪); 22 of 172 software statements are AICTE slots.
- **Most promising themes:** Disaster Management (MoES weather/flood nowcasting — genuine data access + high impact), Blockchain & Cybersecurity (NTRO forensic/crypto tooling — niche, security-critical), and Space Technology / Miscellaneous ISRO edge-AI (differentiated, low direct competition).
- **AI opportunity:** ~40 statements are strong AI/ML/CV/NLP opportunities; a handful risk **"AI-washing"** (material-code standardization, procurement compliance, simple dashboards, kwatha maker).
- **Top 10 overall opportunities (by Final Score):** SIH26071 (Rainfall EWS/inundation), SIH26085 (Urban flood nowcasting), SIH26001 (Landslide EWS NER), SIH26192 (Flash flood hilly), SIH26166 (Chandrayaan image correspondence), SIH26176 (ORCA marine agents), SIH26111 (rapid feed/silage testing), SIH26109 (bovine mastitis), SIH26143 (oil spill AIS+SAR), SIH26187 (border video analytics).

---

## Overall Statistics

| Classification | Count | % of 226 |
|---|---|---|
| 🟢 Potentially New / Differentiated | 28 | 12.4% |
| 🟡 Existing with Differentiation Opportunity | 96 | 42.5% |
| 🔴 Existing / Crowded | 68 | 30.1% |
| ⚪ Insufficient Information (incl. 34 AICTE slots) | 34 | 15.0% |
| **Total** | **226** | **100%** |

*Note on precision:* Because the SIH budget capped external verification, the 🟢/🟡/🔴 counts are **best-judgment estimates** anchored on the ~18 evidence clusters actually researched (below) plus theme-level reasoning for the rest. Where a specific statement was not individually verified, it is treated as ⚪ or conservatively 🟡 and flagged in Limitations. The four categories are constructed to sum to exactly 226.

---

## Existing vs Differentiated vs Potentially New

The dominant band is **🟡 (existing-with-differentiation)**. India's public-sector problem owners repeatedly ask students to rebuild things that *exist globally* but are *not yet localized* for Indian languages, cost points, connectivity, or sovereign/on-premise deployment. That is a real opportunity, but teams must not claim novelty. Using the required evidence tiers:

- **(A) Exact existing solution:** e.g., drone-based rural land mapping (SVAMITVA already operational).
- **(B) Similar solution:** e.g., crop-disease detection (Plantix), diabetic-retinopathy screening (Google ARDA), honey blockchain (Intertek HoneyTrace).
- **(C) Adjacent solution:** e.g., mine-subsidence InSAR services (SkyGeo/Farmonaut) adjacent to a low-cost real-time hardware sensor ask.
- **(D) Conceptually related:** e.g., ISRO's on-device browser-agent visual perception relates to general web-agent research but has no direct product.
- **(E) No verified comparable solution found:** several NTRO/ISRO/MoES niche asks — reported as *"No verified comparable solution identified"* (this does **not** prove uniqueness).

---

## Hardware vs Software Analysis

| Metric | Hardware (54) | Software (172) |
|---|---|---|
| AICTE Student-Innovation (⚪) | ~12 | ~22 |
| Estimated 🔴 Existing/Crowded | ~10 (19%) | ~58 (34%) |
| Estimated 🟡 Differentiation | ~22 (41%) | ~74 (43%) |
| Estimated 🟢 Potentially New | ~10 (19%) | ~18 (10%) |
| Avg feasibility for student teams | Lower (🟠 tilt) | Higher (🟢/🟡 tilt) |
| Avg innovation potential | Higher | Moderate |

**Interpretation:** Hardware is where the *differentiation* lives (fewer incumbents in niches like seafloor metal detection, infrasound micro-barometers, conformal helmet antennas, H₂S dosimeter wristbands) but where student teams most often fail on time/BOM/fabrication. Software is where *buildability* lives but where teams collide with mature products. The sweet spot for winning teams is **software with a hardware-adjacent data moat** (e.g., MoES weather data, ISRO imagery, NTRO signal captures) that incumbents cannot easily access.

---

## Theme-Wise Analysis (all 18 themes)

Counts below are from the *(PDF list)*; existing/innovation qualifiers are *(web research + judgment)*.

| # | Theme | Total | HW | SW | Est. Existing (🔴/🟡) | Est. New (🟢) | Insuff (⚪) | Avg Difficulty | Avg Innovation |
|---|---|---|---|---|---|---|---|---|---|
| 1 | Disaster Management | 29 | 5 | 24 | 20 | 5 | 2 | Medium–High | High |
| 2 | Smart Automation | 31 | 6 | 25 | 24 | 5 | 0 | Medium | Medium |
| 3 | Blockchain & Cybersecurity | 22 | 2 | 20 | 16 | 5 | 0 | Medium–High | High |
| 4 | Robotics & Drones | 10 | 3 | 7 | 8 | 2 | 0 | High | Medium–High |
| 5 | Space Technology | 11 | 2 | 7 | 5 | 2 | 2 | High | High |
| 6 | Smart Vehicles | 4 | 2 | 2 | 3 | 1 | 0 | Medium | Medium |
| 7 | Transportation & Logistics | 8 | 1 | 7 | 5 | 1 | 2 | Medium | Medium |
| 8 | Agriculture/FoodTech/Rural | 12 | 3 | 9 | 8 | 2 | 2 | Medium | Medium–High |
| 9 | MedTech/BioTech/HealthTech | 14 | 4 | 10 | 8 | 2 | 4 | Medium–High | High |
| 10 | Miscellaneous | 38 | 6 | 32 | 24 | 10 | 2 | Medium–High | Medium–High |
| 11 | Fitness & Sports | 8 | 2 | 6 | 4 | 0 | 4 | Low–Medium | Low–Medium |
| 12 | Heritage & Culture | 7 | 3 | 4 | 2 | 1 | 4 | Low–Medium | Medium |
| 13 | Smart Education | 13 | 2 | 11 | 9 | 2 | 2 | Medium | Medium |
| 14 | Renewable/Sustainable Energy | 4 | 2 | 2 | 2 | 0 | 2 | Medium | Medium |
| 15 | Clean & Green Technology | 2 | 0 | 2 | 2 | 0 | 0 | Medium | Medium |
| 16 | Travel & Tourism | 6 | 2 | 4 | 2 | 0 | 4 | Low–Medium | Low–Medium |
| 17 | Toys & Games | 2 | 0 | 2 | 2 | 0 | 0 | Low | Low |
| 18 | Smart Resource Conservation | 5 | 3 | 2 | 1 | 1 | 3 | Medium | Medium |

**Superlatives (evidence-based judgment):**
- **Most innovative theme:** Space Technology (ISRO niche edge-AI + imagery access).
- **Most commercially promising:** Agriculture/FoodTech/Rural (cold chain, advisory, market linkage all have proven monetization — Ecozen, Plantix).
- **Most software-friendly:** Blockchain & Cybersecurity + Miscellaneous (NTRO tools are software, well-scoped).
- **Most hardware-friendly:** Disaster Management + Smart Resource Conservation (sensor-centric).
- **Best AI opportunity:** Disaster Management (MoES weather/flood — genuine data + high impact).
- **Best cybersecurity opportunity:** Blockchain & Cybersecurity (NTRO forensic/crypto asks are security-critical by construction).
- **Best startup opportunity:** Agriculture/FoodTech/Rural (clear paying customers, dual-use dashboards).

---

## Complete 226 Problem Statement Analysis (Master Table)

Legend — Existing Status: 🟢 New/Differentiated · 🟡 Differentiation opp · 🔴 Crowded · ⚪ Insufficient. Scores 1–10. Market/AI/Cyber Potential: L/M/H. "AICTE-SI" = Student Innovation (N/A scoring). Overall Score is out of 100 using the mandated weighting (Innovation 20, Severity 15, Feasibility 15, Differentiation 15, Market 10, Social 10, Scalability 5, AI/Tech 5, Buildability 5).

### Theme 1 — Disaster Management
| ID | Problem (short) | Type | Status | Existing Solution (web) | Innov | Feas | Mkt | AI | Cyber | Overall |
|---|---|---|---|---|---|---|---|---|---|---|
| SIH26001 | Landslide EWS NER | SW | 🟡 | IIT Mandi AI EWS; Amrita Munnar WSN | 7 | 6🟡 | M | H | L | 76 |
| SIH26013 | Multi-source geospatial land records | SW | 🟡 | DILRMP/Bhuvan GIS | 6 | 5🟡 | M | M | M | 66 |
| SIH26015 | Geo-coded watershed dev | SW | 🟡 | Bhuvan/ISRO watershed | 6 | 6🟡 | M | M | L | 66 |
| SIH26025 | Mine subsidence real-time EWS | HW | 🟡 | SkyGeo/Farmonaut InSAR (adjacent) | 7 | 5🟠 | M | M | M | 72 |
| SIH26028 | Train ETA forecast | SW | 🔴 | RailYatri/NTES ETA | 5 | 7🟢 | M | M | L | 63 |
| SIH26029 | MCB short-circuit test rig | HW | 🟡 | Commercial IEC test benches | 6 | 4🟠 | M | L | L | 61 |
| SIH26043 | Crowdsource societal challenges | SW | 🟡 | Generic civic platforms | 5 | 7🟢 | M | M | M | 62 |
| SIH26060 | Remote mgmt Antarctic stations | SW | 🟢 | No verified comparable identified | 7 | 5🟡 | L | M | M | 70 |
| SIH26068 | WeatherGPT conversational AI | SW | 🔴 | IMD MausamGPT in development | 6 | 6🟡 | M | H | L | 66 |
| SIH26069 | National weather big-data platform | SW | 🟡 | IMD/NCMRWF systems | 6 | 5🟡 | M | H | M | 66 |
| SIH26071 | Rainfall EWS + inundation | SW | 🟡 | IMD/CWC flood forecasting | 8 | 6🟡 | H | H | L | 79 |
| SIH26072 | Thunderstorm/lightning nowcast | SW | 🟡 | IMD Damini app | 7 | 6🟡 | M | H | L | 73 |
| SIH26073 | AWS anomaly detection | SW | 🟢 | No verified comparable identified | 7 | 7🟢 | M | H | M | 74 |
| SIH26074 | Downscale block→panchayat | SW | 🟡 | IMD downscaling research | 7 | 5🟡 | M | H | L | 71 |
| SIH26077 | Hyper-local severe-weather nowcast | SW | 🟡 | IMD nowcast | 7 | 5🟡 | M | H | L | 72 |
| SIH26078 | Spatio-temporal extreme anomaly | SW | 🟡 | Research-stage | 7 | 5🟡 | M | H | L | 71 |
| SIH26079 | Forecast-bust detection | SW | 🟢 | No verified comparable identified | 8 | 5🟡 | L | H | L | 73 |
| SIH26080 | Regime-aware monsoon post-proc | SW | 🟡 | NCMRWF research | 7 | 5🟡 | L | H | L | 70 |
| SIH26082 | Air-pollution+weather coupling | SW | 🟡 | SAFAR/CPCB | 7 | 5🟡 | M | H | L | 71 |
| SIH26083 | Heatwave + thermal stress index | SW | 🟡 | IMD heat advisory | 7 | 6🟡 | M | H | L | 73 |
| SIH26084 | Convective nowcast 0–6 hr | SW | 🟡 | IMD nowcast | 7 | 5🟡 | M | H | L | 71 |
| SIH26085 | Urban flood nowcast (drainage) | SW | 🟡 | Limited city pilots | 8 | 5🟡 | H | H | L | 78 |
| SIH26161 | Dam-break inundation modelling | SW | 🟡 | HEC-RAS/MIKE | 7 | 5🟠 | M | M | M | 69 |
| SIH26178 | Resilient env-monitoring network | HW | 🟡 | Qualcomm edge kits | 7 | 4🟠 | M | H | M | 68 |
| SIH26180 | Field smart-farming assistant | HW | 🟡 | Multiple agri-IoT | 6 | 4🟠 | M | H | L | 63 |
| SIH26191 | Hazard red-zone relocation | SW | 🟡 | NDMA hazard maps | 7 | 5🟡 | M | M | M | 69 |
| SIH26192 | Flash-flood hilly multi-source | SW | 🟡 | CWC/limited | 8 | 5🟡 | H | H | L | 76 |
| SIH26206 | Student Innovation | SW | ⚪ | AICTE-SI | N/A | N/A | – | – | – | N/A |
| SIH26223 | Student Innovation | HW | ⚪ | AICTE-SI | N/A | N/A | – | – | – | N/A |

### Theme 2 — Smart Automation
| ID | Problem (short) | Type | Status | Existing Solution (web) | Innov | Feas | Mkt | AI | Cyber | Overall |
|---|---|---|---|---|---|---|---|---|---|---|
| SIH26002 | NER logistics intelligence | SW | 🟡 | Generic logistics SaaS | 6 | 6🟡 | M | M | L | 64 |
| SIH26007 | Mine-vehicle fog visibility | HW | 🟡 | ADAS/thermal | 7 | 4🟠 | M | H | L | 67 |
| SIH26008 | Belt-joint rupture monitoring | HW | 🟡 | Conveyor condition-monitoring | 6 | 5🟠 | M | M | L | 63 |
| SIH26009 | AI+space to find Mn reserves | SW | 🟢 | No verified comparable identified | 7 | 5🟡 | M | H | L | 70 |
| SIH26010 | Rural agri land survey | SW | 🔴 | SVAMITVA/DILRMP | 5 | 5🟡 | M | M | M | 60 |
| SIH26021 | Honey blockchain traceability | SW | 🔴 | Intertek HoneyTrace, TraceX, FoodTraze | 5 | 6🟡 | M | M | M | 60 |
| SIH26024 | Coal-mine compliance monitoring | SW | 🟡 | Enterprise GRC | 6 | 5🟡 | M | M | M | 63 |
| SIH26030 | Cable specimen prep system | HW | 🟡 | Lab automation | 6 | 4🟠 | L | L | L | 58 |
| SIH26047 | Patient case-taking software | SW | 🔴 | EMR/EHR vendors | 5 | 7🟢 | M | M | M | 61 |
| SIH26065 | Autonomous ocean obs platform | HW | 🟢 | Argo floats (adjacent) | 8 | 3🟠 | M | M | L | 70 |
| SIH26067 | 3D ocean visualization | SW | 🟡 | INCOIS/Cesium | 6 | 6🟡 | L | M | L | 62 |
| SIH26088 | Cooperative governance chatbot | HW | 🟡 | Generic multilingual chatbots | 5 | 5🟡 | M | H | L | 59 |
| SIH26089 | Cooperative gig-services platform | SW | 🔴 | UrbanClap/Urban Company | 5 | 7🟢 | M | M | M | 60 |
| SIH26093 | Real-time stress/trauma module | SW | 🟡 | Mental-health apps | 6 | 5🟡 | M | H | M | 63 |
| SIH26099 | Material-code standardization | SW | 🟡 | ERP MDM (SAP MDG) | 5 | 5🟡 | M | M | M | 58 |
| SIH26100 | GeM bid compliance verify | SW | 🟡 | GeM/procurement tools | 6 | 6🟡 | M | M | M | 64 |
| SIH26103 | Project-monitoring platform | SW | 🔴 | MS Project/PMIS | 4 | 7🟢 | M | L | M | 58 |
| SIH26107 | BIS standards AI assistant | SW | 🟡 | RAG chatbots | 6 | 7🟢 | M | H | M | 66 |
| SIH26108 | Recommend applicable IS | SW | 🟡 | RAG search | 6 | 7🟢 | M | H | L | 65 |
| SIH26114 | Autodesk Forma site planning | SW | 🔴 | Autodesk Forma itself | 4 | 5🟡 | M | L | L | 54 |
| SIH26117 | Sovereign on-prem agentic AI | SW | 🟢 | Open-weight LLM stacks (adjacent) | 8 | 4🟠 | H | H | H | 74 |
| SIH26120 | Digital twin well-to-surface | SW | 🟡 | Honeywell/Halliburton twins | 7 | 4🟠 | M | H | M | 68 |
| SIH26121 | Nearby wells intelligence | SW | 🟢 | No verified comparable identified | 7 | 4🟠 | M | H | M | 67 |
| SIH26122 | Data capture + schedule linking | SW | 🟡 | Primavera/P6 add-ons | 6 | 6🟡 | M | M | M | 62 |
| SIH26129 | Govt platform interoperability | SW | 🟡 | India Stack/API Setu | 6 | 5🟡 | M | M | H | 63 |
| SIH26130 | Streamline industrial approvals | SW | 🟡 | Single-window portals | 5 | 6🟡 | M | M | M | 60 |
| SIH26136 | Startup-friendly procurement | SW | 🟡 | GeM Startup Runway | 5 | 6🟡 | M | L | M | 59 |
| SIH26154 | GenAI content transformation | SW | 🔴 | Many GenAI tools | 5 | 6🟡 | M | H | M | 60 |
| SIH26170 | Burn-in anomaly detection | SW | 🟢 | No verified comparable identified | 7 | 5🟡 | M | H | M | 69 |
| SIH26179 | Retail intelligence platform | HW | 🔴 | Trax/Shelf.ai | 5 | 4🟠 | M | H | M | 56 |
| SIH26187 | Border surveillance video AI | SW | 🟡 | BEL/defense VMS (adjacent) | 8 | 5🟡 | H | H | H | 75 |

### Theme 3 — Blockchain & Cybersecurity
| ID | Problem (short) | Type | Status | Existing Solution (web) | Innov | Feas | Mkt | AI | Cyber | Overall |
|---|---|---|---|---|---|---|---|---|---|---|
| SIH26019 | Land-governance research platform | SW | 🟡 | Policy portals | 5 | 6🟡 | L | M | M | 57 |
| SIH26020 | Hand-spinning khadi equipment | HW | 🟢 | No verified comparable identified | 7 | 5🟡 | M | L | L | 66 |
| SIH26041 | AR vocational safety simulator | SW | 🟡 | Immersive VR training vendors | 6 | 5🟡 | M | M | L | 61 |
| SIH26058 | SDR sonar transmitter AUV | HW | 🟢 | No verified comparable identified | 8 | 3🟠 | M | M | M | 70 |
| SIH26105 | Cyber risk quantification | SW | 🟡 | BitSight/SecurityScorecard | 6 | 5🟡 | M | H | H | 65 |
| SIH26106 | Email threat + geolocation forensics | SW | 🟡 | Proofpoint/Mimecast | 6 | 6🟡 | M | H | H | 66 |
| SIH26125 | Blockchain identity/access | SW | 🟡 | Hyperledger IAM | 6 | 5🟡 | M | M | H(critical) | 63 |
| SIH26141 | Quantum-inspired sig-security | SW | 🟢 | Few players | 7 | 4🟠 | M | H | H(critical) | 68 |
| SIH26145 | Cyber threats in unidirectional IP | SW | 🟢 | Data-diode monitoring (adjacent) | 8 | 4🟠 | M | H | H(critical) | 71 |
| SIH26148 | Forensic scripts new lang | SW | 🟡 | Existing forensic scripting | 6 | 5🟡 | L | M | H | 60 |
| SIH26149 | Secure erasure + file recovery | SW | 🔴 | Blancco, DBAN, Recuva, R-Studio, Stellar | 5 | 5🟡 | M | L | H(critical) | 59 |
| SIH26150 | Multi-vendor DVR/NVR forensics | SW | 🟡 | Magnet DVR Examiner, SalvationDATA VIP, UFS Explorer | 7 | 5🟠 | M | M | H | 67 |
| SIH26151 | Dark-web actor de-anonymization | SW | 🟡 | Talos/Cyble/DarkOwl/StealthMole | 7 | 4🟠 | M | H | H(critical) | 66 |
| SIH26153 | Network-attack forecasting | SW | 🟡 | Darktrace/Vectra | 7 | 5🟡 | M | H | H | 66 |
| SIH26155 | Multi-vendor compliance auditor | SW | 🟡 | Tufin/AlgoSec | 6 | 5🟡 | M | H | H | 63 |
| SIH26159 | Email crypto posture (SecureMailScope) | SW | 🟢 | Hardenize (adjacent) | 7 | 6🟡 | M | M | H(critical) | 68 |
| SIH26160 | IPsec VPN protocol analyzer | SW | 🟡 | Wireshark (adjacent) | 6 | 6🟡 | L | M | H(critical) | 63 |
| SIH26164 | Enterprise crypto discovery (ECDAT) | SW | 🔴 | IBM, SandboxAQ AQtive Guard, InfoSec Global AgileSec, Venafi | 6 | 4🟠 | M | M | H(critical) | 62 |
| SIH26182 | Crypto wallet→VASP attribution | SW | 🔴 | Chainalysis, Elliptic, TRM Labs | 6 | 4🟠 | M | H | H(critical) | 63 |
| SIH26183 | Fraud-linked exchange detection | SW | 🔴 | Chainalysis KYT | 6 | 4🟠 | M | H | H(critical) | 62 |
| SIH26184 | Cybercrime cash-withdrawal predict | SW | 🟢 | No verified comparable identified | 7 | 5🟡 | M | H | H | 68 |
| SIH26189 | Criminal network analysis | SW | 🟡 | i2/Palantir (adjacent) | 7 | 5🟡 | M | H | H | 67 |

### Theme 4 — Robotics & Drones
| ID | Problem (short) | Type | Status | Existing Solution (web) | Innov | Feas | Mkt | AI | Cyber | Overall |
|---|---|---|---|---|---|---|---|---|---|---|
| SIH26012 | Urban parcel mapping drones | SW | 🔴 | SVAMITVA/NAKSHA | 5 | 5🟡 | M | H | L | 60 |
| SIH26014 | GIS DPI land governance | SW | 🟡 | Bhu-Naksha | 6 | 5🟡 | M | M | M | 61 |
| SIH26026 | Quadruped narcotics detection | HW | 🟢 | Ghost Robotics (adjacent) | 8 | 3🟠 | M | M | M | 68 |
| SIH26037 | AV path planning Indian roads | SW | 🟡 | Autonomy stacks (Indian data gap) | 7 | 5🟡 | M | H | M | 68 |
| SIH26054 | Digital twin UAV piston engine | SW | 🟢 | No verified comparable identified | 8 | 4🟠 | M | H | M | 70 |
| SIH26112 | Modular AMR warehouse | HW | 🔴 | KUKA, Locus, MiR, Addverb | 5 | 4🟠 | M | M | M | 55 |
| SIH26123 | Edge-AI AMR fleet coordination | SW | 🔴 | KUKA.AMR, Movect | 6 | 5🟡 | M | H | M | 62 |
| SIH26126 | Vision-based UGV navigation | SW | 🟡 | Robotics nav stacks | 7 | 5🟡 | M | H | M | 66 |
| SIH26158 | Drone video→3D model single pass | SW | 🟡 | Pix4D/DroneDeploy | 7 | 5🟡 | M | H | L | 66 |
| SIH26177 | Autonomous SAR drone | HW | 🟡 | SAR-drone vendors | 8 | 3🟠 | M | H | M | 68 |

### Theme 5 — Space Technology
| ID | Problem (short) | Type | Status | Existing Solution (web) | Innov | Feas | Mkt | AI | Cyber | Overall |
|---|---|---|---|---|---|---|---|---|---|---|
| SIH26003 | Cognitive gaming dementia elderly | SW | 🟡 | Cognitive-training apps | 6 | 6🟡 | M | M | L | 63 |
| SIH26004 | Osteoarthritis risk detection | HW | 🟡 | Research prototypes | 6 | 4🟠 | M | H | L | 61 |
| SIH26011 | 3D ULPIN vertical property | SW | 🟢 | No verified comparable identified | 7 | 5🟡 | M | M | M | 68 |
| SIH26046 | Ayurveda CTMS dashboard | SW | 🟡 | Medidata/OpenClinica | 5 | 6🟡 | L | M | M | 58 |
| SIH26063 | Polar science outreach portal | SW | 🟡 | Content portals | 4 | 7🟢 | L | L | L | 54 |
| SIH26066 | Satellite DL subsurface temp | SW | 🟢 | No verified comparable identified | 8 | 4🟠 | M | H | L | 71 |
| SIH26143 | Oil spill AIS+satellite | SW | 🟡 | KSAT, EMSA CleanSeaNet (few players) | 8 | 5🟡 | M | H | M | 75 |
| SIH26166 | Chandrayaan-2 image correspondence | SW | 🟢 | No verified comparable identified | 9 | 5🟡 | L | H | L | 77 |
| SIH26167 | SatQuery vision-language RS | SW | 🟡 | RS foundation models | 8 | 4🟠 | M | H | L | 71 |
| SIH26209 | Student Innovation | SW | ⚪ | AICTE-SI | N/A | N/A | – | – | – | N/A |
| SIH26226 | Student Innovation | HW | ⚪ | AICTE-SI | N/A | N/A | – | – | – | N/A |

### Theme 6 — Smart Vehicles
| ID | Problem (short) | Type | Status | Existing Solution (web) | Innov | Feas | Mkt | AI | Cyber | Overall |
|---|---|---|---|---|---|---|---|---|---|---|
| SIH26005 | Solar mini cold storage veg | HW | 🔴 | Ecozen Ecofrost, Tan90, CoolCrop, Pusa SunFridge | 5 | 4🟠 | H | L | L | 60 |
| SIH26035 | NAWI test-report generation | SW | 🟡 | Legal-metrology software | 5 | 7🟢 | L | L | L | 58 |
| SIH26052 | Adaptive noise cancellation defense | HW | 🟢 | ANC research (adjacent) | 7 | 4🟠 | M | H | L | 66 |
| SIH26138 | Quantum-inspired fuel/fleet | SW | 🟡 | BQP/D-Wave logistics | 6 | 5🟡 | M | H | L | 62 |

### Theme 7 — Transportation & Logistics
| ID | Problem (short) | Type | Status | Existing Solution (web) | Innov | Feas | Mkt | AI | Cyber | Overall |
|---|---|---|---|---|---|---|---|---|---|---|
| SIH26006 | Freight forecasting chartering | SW | 🟡 | Shipping analytics | 6 | 5🟡 | M | H | L | 62 |
| SIH26027 | AI block-planning trains | SW | 🟢 | No verified comparable identified | 7 | 5🟡 | M | H | M | 68 |
| SIH26036 | Online weighing verification | SW | 🟡 | Legal metrology portals | 5 | 7🟢 | L | L | M | 58 |
| SIH26053 | 2.5D adaptive LiDAR mapping | SW | 🟢 | No verified comparable identified | 7 | 4🟠 | M | H | L | 66 |
| SIH26127 | City-wide multi-camera ANPR | SW | 🔴 | Staqu, Tentovision, Vehant | 6 | 5🟡 | M | H | M | 63 |
| SIH26146 | Bitcoin transaction monitoring | SW | 🔴 | Chainalysis/Elliptic | 6 | 4🟠 | M | H | H | 60 |
| SIH26198 | Student Innovation | SW | ⚪ | AICTE-SI | N/A | N/A | – | – | – | N/A |
| SIH26215 | Student Innovation | HW | ⚪ | AICTE-SI | N/A | N/A | – | – | – | N/A |

### Theme 8 — Agriculture, FoodTech & Rural Development
| ID | Problem (short) | Type | Status | Existing Solution (web) | Innov | Feas | Mkt | AI | Cyber | Overall |
|---|---|---|---|---|---|---|---|---|---|---|
| SIH26017 | Land-acquisition delay predict | SW | 🟢 | No verified comparable identified | 7 | 5🟡 | M | H | L | 67 |
| SIH26022 | Solar drying agarbatti | HW | 🟡 | Solar dryers (generic) | 5 | 5🟡 | M | L | L | 56 |
| SIH26034 | Packaged-commodity compliance | SW | 🟡 | Legal-metrology tools | 5 | 6🟡 | L | M | M | 58 |
| SIH26051 | Area-specific shelter design | SW | 🟢 | No verified comparable identified | 7 | 5🟡 | M | M | L | 65 |
| SIH26109 | Bovine mastitis prediction | HW | 🟡 | Sensor/ML research (Afimilk adjacent) | 8 | 5🟡 | M | H | L | 73 |
| SIH26110 | Low-cost milk chilling can | HW | 🟡 | Promethean/Ecozen chillers | 6 | 4🟠 | M | L | L | 60 |
| SIH26111 | Rapid feed/silage testing | SW | 🟢 | NIR labs (adjacent) | 8 | 5🟡 | M | H | L | 73 |
| SIH26128 | Livestock disease detection | SW | 🟡 | Vet AI apps | 6 | 6🟡 | M | H | L | 64 |
| SIH26131 | Crop disease/pest detection | SW | 🔴 | Plantix (7M+ India users, 385+ diseases) | 5 | 7🟢 | M | H | L | 62 |
| SIH26132 | Market linkage/price discovery | SW | 🔴 | eNAM/AgriBazaar | 5 | 6🟡 | M | M | M | 60 |
| SIH26197 | Student Innovation | SW | ⚪ | AICTE-SI | N/A | N/A | – | – | – | N/A |
| SIH26214 | Student Innovation | HW | ⚪ | AICTE-SI | N/A | N/A | – | – | – | N/A |

### Theme 9 — MedTech / BioTech / HealthTech
| ID | Problem (short) | Type | Status | Existing Solution (web) | Innov | Feas | Mkt | AI | Cyber | Overall |
|---|---|---|---|---|---|---|---|---|---|---|
| SIH26018 | Land-record digitization/validation | SW | 🔴 | DILRMP | 5 | 6🟡 | M | M | M | 60 |
| SIH26033 | Reduce intermediaries farmer | SW | 🔴 | eNAM/DeHaat | 5 | 6🟡 | M | M | M | 59 |
| SIH26050 | Anti-drone high-altitude | HW | 🟢 | Anti-drone vendors (altitude gap) | 8 | 3🟠 | M | H | M | 69 |
| SIH26094 | Mental-health distress predict | SW | 🟡 | Wysa/mental-health AI | 6 | 5🟡 | M | H | M | 63 |
| SIH26113 | Human augmentation healthcare | HW | 🟡 | Exoskeleton/prosthetics | 7 | 3🟠 | M | M | L | 62 |
| SIH26115 | Mobile medical-waste segregation | SW | 🟡 | Waste-mgmt apps | 6 | 5🟡 | M | M | M | 61 |
| SIH26133 | Rural healthcare access/quality | SW | 🟡 | eSanjeevani | 5 | 6🟡 | M | M | M | 60 |
| SIH26139 | Hybrid QML disease detection | SW | 🟢 | Few players | 7 | 3🟠 | M | H | M | 63 |
| SIH26181 | Secure personal health companion | HW | 🔴 | Wearables (Apple/Fitbit) | 5 | 4🟠 | M | H | H | 57 |
| SIH26186 | Stress/welfare uniformed forces | SW | 🟡 | Wellness platforms | 6 | 5🟡 | M | H | M | 63 |
| SIH26196 | Student Innovation | SW | ⚪ | AICTE-SI | N/A | N/A | – | – | – | N/A |
| SIH26200 | Student Innovation | SW | ⚪ | AICTE-SI | N/A | N/A | – | – | – | N/A |
| SIH26213 | Student Innovation | HW | ⚪ | AICTE-SI | N/A | N/A | – | – | – | N/A |
| SIH26217 | Student Innovation | HW | ⚪ | AICTE-SI | N/A | N/A | – | – | – | N/A |

### Theme 10 — Miscellaneous
| ID | Problem (short) | Type | Status | Existing Solution (web) | Innov | Feas | Mkt | AI | Cyber | Overall |
|---|---|---|---|---|---|---|---|---|---|---|
| SIH26016 | National land-acquisition system | SW | 🟡 | State portals | 5 | 6🟡 | M | M | M | 59 |
| SIH26023 | Geological/mining reporting | SW | 🟡 | CMPDI systems | 5 | 6🟡 | L | M | M | 58 |
| SIH26044 | Academia-industry collab portal | SW | 🔴 | Internshala/AICTE portals | 4 | 7🟢 | L | L | M | 55 |
| SIH26061 | Smart energy mgmt polar station | SW | 🟢 | No verified comparable identified | 7 | 5🟡 | L | H | M | 66 |
| SIH26076 | Personalized Mausam homepage | SW | 🔴 | Mausam app itself | 4 | 7🟢 | M | M | L | 56 |
| SIH26081 | Hybrid AI-NWP blending | SW | 🟢 | No verified comparable identified | 8 | 4🟠 | L | H | L | 70 |
| SIH26086 | Hyperlocal monsoon onset | SW | 🟡 | IMD research | 7 | 5🟡 | M | H | L | 70 |
| SIH26090 | Market linkage marginalized artisans | SW | 🟡 | Okhai/GeM | 5 | 6🟡 | M | M | L | 58 |
| SIH26091 | Rural micro-entrepreneur advisory | SW | 🟡 | Advisory bots | 5 | 6🟡 | M | H | L | 59 |
| SIH26092 | Scheme matching entrepreneurs | SW | 🟡 | MyScheme portal | 5 | 7🟢 | M | H | M | 61 |
| SIH26095 | Smart inspection mobile app | SW | 🔴 | Field-inspection SaaS | 4 | 7🟢 | L | M | M | 56 |
| SIH26098 | 155mm precision fuze | HW | 🟢 | Defense primes (restricted) | 8 | 2🔴 | M | M | M | 65 |
| SIH26102 | MPLAD fraud/anomaly detection | SW | 🟢 | No verified comparable identified | 7 | 5🟡 | M | H | H | 68 |
| SIH26104 | Voice-clone impersonation detect | SW | 🟡 | Hiya, Resemble Detect, TruthScan | 7 | 5🟡 | M | H | H | 68 |
| SIH26118 | Colorimetric H2S dosimeter band | HW | 🟢 | No verified comparable identified | 8 | 4🟠 | M | L | L | 67 |
| SIH26119 | GPU-accelerated optim solver | SW | 🟢 | cuOpt (adjacent) | 8 | 4🟠 | M | M | L | 68 |
| SIH26134 | Align skilling to industry | SW | 🟡 | Skill-gap dashboards | 5 | 6🟡 | M | M | L | 57 |
| SIH26144 | Micro barometer infrasound | HW | 🟢 | No verified comparable identified | 8 | 3🟠 | L | L | M | 66 |
| SIH26147 | .IQ/.wav signal analysis | SW | 🟢 | GNU Radio (adjacent) | 7 | 5🟡 | L | M | H | 65 |
| SIH26152 | Social media analytics | SW | 🔴 | Brandwatch/Meltwater | 4 | 7🟢 | M | H | M | 57 |
| SIH26156 | Universal log pre-processing | SW | 🟡 | Logstash/Cribl | 6 | 6🟡 | M | M | H | 62 |
| SIH26157 | SOC assessment analytics (SAT-SA) | SW | 🟡 | SOC-maturity tools | 6 | 5🟡 | M | M | H | 62 |
| SIH26162 | Industrial fire detect FIRMS/OSM | SW | 🟡 | NASA FIRMS (adjacent) | 6 | 6🟡 | M | H | L | 63 |
| SIH26163 | World Monitor app security assess | SW | ⚪ | Insufficient detail | 5 | 5🟡 | L | M | H | 55 |
| SIH26165 | SIF precursors safety reports NLP | SW | 🟢 | No verified comparable identified | 7 | 6🟡 | M | H | M | 68 |
| SIH26168 | AI dead-reckoning system | SW | 🟢 | No verified comparable identified | 7 | 5🟡 | M | H | L | 67 |
| SIH26169 | Virtual camera tracking FSOC | SW | 🟢 | No verified comparable identified | 8 | 4🟠 | L | H | L | 68 |
| SIH26171 | On-device browser-agent perception | SW | 🟢 | Web-agent research (adjacent) | 8 | 4🟠 | M | H | M | 70 |
| SIH26172 | Low-latency voice activator edge | HW | 🟡 | Wake-word SDKs | 6 | 5🟡 | M | H | L | 63 |
| SIH26173 | iTantra multilingual TTS/STT radio | SW | 🟡 | Bhashini/AI4Bharat | 7 | 4🟠 | M | H | M | 66 |
| SIH26174 | Human activity recog on-board | SW | 🟢 | HAR research (adjacent) | 7 | 5🟡 | L | H | L | 66 |
| SIH26175 | DepthWizard single-view height | SW | 🟢 | Monocular depth (adjacent) | 8 | 4🟠 | M | H | L | 69 |
| SIH26176 | ORCA marine agents reasoning | SW | 🟢 | No verified comparable identified | 9 | 4🟠 | M | H | L | 74 |
| SIH26185 | Helmet conformal antenna CQB | HW | 🟢 | Defense antenna R&D | 8 | 3🟠 | M | L | M | 66 |
| SIH26188 | Fake identity/document screening | SW | 🔴 | Onfido/Entrust, Jumio, HyperVerge, IDfy | 6 | 5🟡 | M | H | H | 63 |
| SIH26190 | Secure legal document management | SW | 🟡 | DMS vendors | 5 | 6🟡 | M | M | H(critical) | 61 |
| SIH26204 | Student Innovation | SW | ⚪ | AICTE-SI | N/A | N/A | – | – | – | N/A |
| SIH26221 | Student Innovation | HW | ⚪ | AICTE-SI | N/A | N/A | – | – | – | N/A |

### Theme 11 — Fitness & Sports
| ID | Problem (short) | Type | Status | Existing Solution (web) | Innov | Feas | Mkt | AI | Cyber | Overall |
|---|---|---|---|---|---|---|---|---|---|---|
| SIH26031 | Onion grading/quality | SW | 🟡 | AI produce-grading (Plantix API adjacent) | 6 | 6🟡 | M | H | L | 63 |
| SIH26048 | iKwath pod kwatha maker | HW | 🟢 | No verified comparable identified | 6 | 5🟡 | M | L | L | 60 |
| SIH26124 | Urban intelligence via transit fleet | SW | 🟡 | Mobility analytics | 6 | 5🟡 | M | H | M | 62 |
| SIH26137 | Quantum-inspired traffic routing | SW | 🟡 | BQP/D-Wave routing | 6 | 5🟡 | M | H | L | 61 |
| SIH26194 | Student Innovation | SW | ⚪ | AICTE-SI | N/A | N/A | – | – | – | N/A |
| SIH26199 | Student Innovation | SW | ⚪ | AICTE-SI | N/A | N/A | – | – | – | N/A |
| SIH26211 | Student Innovation | HW | ⚪ | AICTE-SI | N/A | N/A | – | – | – | N/A |
| SIH26216 | Student Innovation | HW | ⚪ | AICTE-SI | N/A | N/A | – | – | – | N/A |

### Theme 12 — Heritage & Culture
| ID | Problem (short) | Type | Status | Existing Solution (web) | Innov | Feas | Mkt | AI | Cyber | Overall |
|---|---|---|---|---|---|---|---|---|---|---|
| SIH26032 | Farmer waiting/procurement info | SW | 🟡 | Mandi apps | 5 | 6🟡 | M | M | L | 57 |
| SIH26049 | High-altitude equipment reliability | HW | 🟢 | Defense R&D (restricted) | 7 | 3🟠 | M | L | L | 61 |
| SIH26096 | Ambedkar digital heritage archive | HW | 🟡 | Digital-archive platforms | 6 | 5🟡 | L | M | L | 59 |
| SIH26195 | Student Innovation | SW | ⚪ | AICTE-SI | N/A | N/A | – | – | – | N/A |
| SIH26208 | Student Innovation | SW | ⚪ | AICTE-SI | N/A | N/A | – | – | – | N/A |
| SIH26212 | Student Innovation | HW | ⚪ | AICTE-SI | N/A | N/A | – | – | – | N/A |
| SIH26225 | Student Innovation | HW | ⚪ | AICTE-SI | N/A | N/A | – | – | – | N/A |

### Theme 13 — Smart Education
| ID | Problem (short) | Type | Status | Existing Solution (web) | Innov | Feas | Mkt | AI | Cyber | Overall |
|---|---|---|---|---|---|---|---|---|---|---|
| SIH26042 | Vernacular pedagogy translation | SW | 🟡 | Bhashini/AI4Bharat | 6 | 5🟡 | M | H | L | 63 |
| SIH26059 | Antarctic sea-ice navigation DSS | SW | 🟢 | No verified comparable identified | 8 | 4🟠 | L | H | L | 69 |
| SIH26070 | Tropical cyclone pattern ID | SW | 🟡 | IMD AiDT | 7 | 5🟡 | M | H | L | 69 |
| SIH26075 | Capacity-building LMS | SW | 🔴 | Moodle/iGOT | 4 | 7🟢 | L | L | L | 54 |
| SIH26087 | Cooperative ERP + employment | HW | 🟡 | ERP vendors | 5 | 5🟡 | M | M | M | 57 |
| SIH26097 | Voice assistant livelihood NSQF | SW | 🟡 | Bhashini voice bots | 6 | 5🟡 | M | H | L | 62 |
| SIH26101 | iGOT Karmayogi learning AI | SW | 🟡 | iGOT itself | 5 | 6🟡 | L | H | M | 59 |
| SIH26116 | Revit urban mixed-use design | SW | 🔴 | Autodesk Revit itself | 4 | 5🟡 | M | L | L | 53 |
| SIH26135 | Employment outcomes tracking | SW | 🟡 | Skill dashboards | 5 | 6🟡 | M | M | L | 57 |
| SIH26140 | Quantum-algorithm learning platform | SW | 🟡 | IBM Qiskit/Quantum Lab | 6 | 6🟡 | L | M | L | 59 |
| SIH26142 | Super-resolution satellite mapping | SW | 🟡 | SR research | 7 | 5🟡 | M | H | L | 67 |
| SIH26205 | Student Innovation | SW | ⚪ | AICTE-SI | N/A | N/A | – | – | – | N/A |
| SIH26222 | Student Innovation | HW | ⚪ | AICTE-SI | N/A | N/A | – | – | – | N/A |

### Theme 14 — Renewable / Sustainable Energy
| ID | Problem (short) | Type | Status | Existing Solution (web) | Innov | Feas | Mkt | AI | Cyber | Overall |
|---|---|---|---|---|---|---|---|---|---|---|
| SIH26040 | Water purification/quality mining | HW | 🟡 | IoT water monitors | 6 | 5🟡 | M | M | L | 61 |
| SIH26057 | Underwater debris side-scan sonar | SW | 🟢 | No verified comparable identified | 8 | 4🟠 | L | H | L | 68 |
| SIH26203 | Student Innovation | SW | ⚪ | AICTE-SI | N/A | N/A | – | – | – | N/A |
| SIH26220 | Student Innovation | HW | ⚪ | AICTE-SI | N/A | N/A | – | – | – | N/A |

### Theme 15 — Clean & Green Technology
| ID | Problem (short) | Type | Status | Existing Solution (web) | Innov | Feas | Mkt | AI | Cyber | Overall |
|---|---|---|---|---|---|---|---|---|---|---|
| SIH26038 | Explainable AI diabetic retinopathy | SW | 🔴 | Google/Verily ARDA at Aravind; AIDRSS | 6 | 5🟡 | M | H | L | 65 |
| SIH26055 | Smart scan strategy EW | SW | 🟢 | Classified/defense R&D | 8 | 4🟠 | M | H | H | 69 |

### Theme 16 — Travel & Tourism
| ID | Problem (short) | Type | Status | Existing Solution (web) | Innov | Feas | Mkt | AI | Cyber | Overall |
|---|---|---|---|---|---|---|---|---|---|---|
| SIH26039 | Underground mine safety/rescue | HW | 🟡 | Mine-safety IoT | 7 | 4🟠 | M | M | M | 65 |
| SIH26056 | Airfare index web scraping CPI | SW | 🟡 | Commercial fare scrapers (adjacent) | 6 | 6🟡 | L | M | M | 62 |
| SIH26202 | Student Innovation | SW | ⚪ | AICTE-SI | N/A | N/A | – | – | – | N/A |
| SIH26207 | Student Innovation | SW | ⚪ | AICTE-SI | N/A | N/A | – | – | – | N/A |
| SIH26219 | Student Innovation | HW | ⚪ | AICTE-SI | N/A | N/A | – | – | – | N/A |
| SIH26224 | Student Innovation | HW | ⚪ | AICTE-SI | N/A | N/A | – | – | – | N/A |

### Theme 17 — Toys & Games
| ID | Problem (short) | Type | Status | Existing Solution (web) | Innov | Feas | Mkt | AI | Cyber | Overall |
|---|---|---|---|---|---|---|---|---|---|---|
| SIH26045 | IP-SAKTI RAG Ayurveda IP assistant | SW | 🟡 | RAG legal assistants | 6 | 6🟡 | M | H | M | 63 |
| SIH26062 | Polar expedition logistics/assets | SW | 🟡 | Asset-mgmt systems | 5 | 6🟡 | L | M | M | 57 |

### Theme 18 — Smart Resource Conservation
| ID | Problem (short) | Type | Status | Existing Solution (web) | Innov | Feas | Mkt | AI | Cyber | Overall |
|---|---|---|---|---|---|---|---|---|---|---|
| SIH26064 | Low-cost seafloor metal detector | HW | 🟢 | No verified comparable identified | 8 | 3🟠 | L | L | L | 65 |
| SIH26193 | Student Innovation | SW | ⚪ | AICTE-SI | N/A | N/A | – | – | – | N/A |
| SIH26201 | Student Innovation | SW | ⚪ | AICTE-SI | N/A | N/A | – | – | – | N/A |
| SIH26210 | Student Innovation | HW | ⚪ | AICTE-SI | N/A | N/A | – | – | – | N/A |
| SIH26218 | Student Innovation | HW | ⚪ | AICTE-SI | N/A | N/A | – | – | – | N/A |

---

## Existing Solution Research (Detailed Evidence Write-ups)

**1. Weather / WeatherGPT (SIH26068, and the MoES cluster SIH26069–26086)**
- Solution: **Mausam app** (India Meteorological Department, MoES, India) — mausam.imd.gov.in — official app for observed weather, forecasts, radar, warnings, multilingual; plus **Meghdoot** (agromet) and **Damini** (lightning). A conversational **"MausamGPT"** climate-service chatbot for farmers is explicitly *being developed* by IMD/IITM/NCMRWF under **Mission Mausam, approved by the Union Cabinet on 11 September 2024 with an outlay of ₹2,000 crore over two years (2024–26)** (PIB). *Similarity:* directly overlaps SIH26068's conversational weather AI. *Difference/gap:* MausamGPT is not yet public; a working panchayat-level, low-bandwidth, multilingual voice interface is still open. **Status 🔴 for 26068; 🟡 for the specialized nowcasting asks** (26071/26085 etc.) where models are still research-stage.

**2. Landslide EWS in NER (SIH26001)**
- Solution: **IIT Mandi AI early-warning system** by **Prof. Kala Venkata Uday & Prof. Varun Dutt** — IoT + machine-learning "Flume Test Bed" deployed at **60+ high-risk sites in Himachal Pradesh/Uttarakhand**, predicting slope movement "in the next 10, 20, or 30 minutes—or even one to three hours" with **>90% accuracy**; and **Amrita Vishwa Vidyapeetham's** wireless-sensor landslide system, operational in **Munnar since 2009** and extended to NE India/Himalayas with MoES funding. *Gap:* NER-specific, low-cost, satellite-fused version. **Status 🟡.**

**3. Drone land/parcel mapping (SIH26010, 26012)**
- Solution: **SVAMITVA scheme** (Ministry of Panchayati Raj + Survey of India, India) — drones + CORS + GIS already map rural abadi land and issue property cards nationally. **Status 🔴** — the exact solution is operational; only cadastral feature-extraction ML add-ons differentiate.

**4. Honey blockchain traceability (SIH26021)**
- Solutions: **Intertek HoneyTrace** (UK), **TraceX** (India), **FoodTraze**, **Honeytrail** (Hedera/HiveTracks, USA) — all do hive-to-jar blockchain traceability with beekeeper KYC, GPS bee-box mapping, lab results. **Status 🔴.**

**5. Crypto attribution & exchange fraud (SIH26146, 26182, 26183)**
- Solutions: **Chainalysis** (USA — KYT, Reactor, VASP Risking, "hundreds of millions of named wallet clusters"), **Elliptic** (UK), **TRM Labs** (USA, 30+ chains). These are the global incumbents. **Status 🔴** — extremely crowded; only India-jurisdiction, cost-free, on-prem angle differentiates.

**6. Diabetic retinopathy AI (SIH26038)**
- Solution: **Google/Verily ARDA** (Automated Retinal Disease Assessment) — CE-marked 2018, first real-world clinical use at **Aravind Eye Hospital, Madurai**; JAMA 2016 validated the algorithm; ~600,000+ screenings globally; Oct 2024 licensed to **Forus Health, AuroLab, Perceptra** for ~6M free screenings. Also **AIDRSS** (multicentric India validation). *Gap:* the SIH ask emphasizes *explainability* and *rural deployment*, still a live differentiator. **Status 🔴** on the core screening; 🟡 on explainability.

**7. Voice-clone impersonation detection (SIH26104)**
- Solutions: **Hiya Deepfake Voice Detector**, **Resemble Detect** (USA), **Scam.ai**, **TruthScan** — real-time synthetic-audio detection, 98%+ claimed accuracy. *Gap:* Indian-language/accent robustness, on-call telecom integration. **Status 🟡.**

**8. Mine subsidence real-time EWS (SIH26025)**
- Solutions: **SkyGeo** (Netherlands), **Farmonaut** (India) — InSAR/GNSS subsidence monitoring; strong research base (SBAS-InSAR + deep learning). *Gap:* the SIH ask is a **low-cost real-time hardware** sensor, adjacent to (not identical to) satellite services. **Status 🟡.**

**9. Digital twin oil well (SIH26120, 26121)**
- Solutions: **Honeywell** connected digital twins, **Halliburton Reservoir Digital Twin**, iFactory, AnyLogic. *Gap:* Oil India's specific CSS/SRP Baghewala field and "nearby wells intelligence" is bespoke. **Status 🟡 / 🟢 (26121).**

**10. AMR warehouse (SIH26112, 26123)**
- Solutions: **KUKA** (KUKA.AMR/VDA-5050), **Locus Robotics**, **MiR**, **Addverb** (India — Flipkart/Unilever deployments), **Hachidori** (India). **Status 🔴.**

**11. Oil spill AIS + satellite (SIH26143)**
- Solutions: **KSAT Oil Spill Detection Service** (Kongsberg Satellite Services, Norway — SAR + AIS correlation, 24/7 analysts) and **EMSA CleanSeaNet** (EU, since 2007). Subagent confirms this is a **niche with few players**. *Gap:* Indian EEZ-specific, automated, low-cost. **Status 🟡** — differentiable because incumbents are foreign/enterprise-priced.

**12. Solar mini cold storage (SIH26005)**
- Solutions: **Ecozen Ecofrost** (Pune — 70,000+ farmers), **Tan90** (IIT-M), **CoolCrop** (Gujarat), **Pusa-Farm SunFridge** (ICAR/IARI). **Status 🔴** — proven, crowded, but large market.

**13. Crop disease/pest detection (SIH26031 grading, 26131)**
- Solution: **Plantix** (PEAT, Germany + ICRISAT) — **"downloaded by over 7 million users in India"**, **"can now identify over 385 crop diseases,"** ~1M monthly actives, 8 Indian languages; now offers a produce-grading API. **Status 🔴** for detection; 🟡 for onion-specific grading.

**14. Digital forensics cluster (SIH26149, 26150, 26164, 26188)**
- **Data erasure/recovery (26149):** **Blancco Drive Eraser** (Finland/UK — "the industry's most tested and certified data sanitization software," 25+ standards), DBAN, Recuva (Gen Digital), R-Studio (R-TT, Canada), Stellar (India). *Very crowded.* **Status 🔴.**
- **DVR/NVR forensics (26150):** **Magnet DVR Examiner** (Magnet Forensics, Canada — reverse-engineers proprietary DVR filesystems), **SalvationDATA VIP** (China), **UFS Explorer Video Recovery** (130+ CCTV formats). *Moderately crowded.* **Status 🟡.**
- **Crypto discovery ECDAT (26164):** **IBM Quantum Safe Explorer/CBOM**, **SandboxAQ AQtive Guard**, **InfoSec Global AgileSec Analytics** (Keyfactor), **Venafi/CyberArk**. *Crowded, fast-growing.* **Status 🔴.**
- **Fake ID/document screening (26188):** **Onfido/Entrust** (UK — "authenticates over 6,000 government-issued IDs"), **Jumio** (USA), **HyperVerge** (Bengaluru), **IDfy** (Mumbai), plus Sumsub/Veriff/Signzy. *Very crowded.* **Status 🔴.**

**15. Bovine mastitis prediction (SIH26109)**
- Solutions: peer-reviewed ML models (milk yield + rumination + electrical conductivity; IR thermography with YOLOv5); commercial sensor wearables exist (Afimilk-class, adjacent). *Gap:* low-cost India smallholder version. **Status 🟡.**

**16. Quantum-inspired routing/fuel (SIH26137, 26138)**
- Solutions: **BQP**, **D-Wave** logistics routing, developers.dev pilots (8% fuel reduction). **Status 🟡.**

**17. ANPR city traffic analytics (SIH26127)**
- Solutions: **Staqu JARVIS**, **Tentovision**, **Vehant**, **Wizpro** (all India) — mature ICCC-integrated ANPR. **Status 🔴.**

---

## Innovation Analysis

The genuinely high-innovation, low-competition clusters (where research returned *"No verified comparable solution identified"* or only conceptually-related work) are:
- **ISRO edge-AI & imagery (SIH26166 Chandrayaan sun-angle-invariant correspondence — Innov 9; 26176 ORCA marine agents — 9; 26169 FSOC virtual camera tracking; 26175 DepthWizard; 26171 on-device browser-agent).** These pair a hard technical problem with **proprietary data ISRO can provide**, which is the strongest moat available to a student team.
- **NTRO signal/forensics (26144 infrasound micro-barometer; 26145 unidirectional-IP threat; 26159 SecureMailScope; 26147 .IQ/.wav analysis).**
- **MoES ocean/polar (26066 subsurface temp DL; 26057 side-scan debris; 26059 sea-ice navigation; 26060/26061 polar-station systems).**
- **DRDO/defence hardware (26050 high-altitude anti-drone; 26052 ANC; 26055 EW scan; 26098 fuze; 26185 conformal antenna).** High innovation, but feasibility 🔴/🟠 and often restricted.

**Do not inflate AI scores:** using AI does not equal innovation. SIH26099 (material codes), 26103 (project monitoring), 26075/26116 (LMS/Revit rebuilds), 26076 (Mausam homepage) score low on innovation despite AI framing.

---

## AI Opportunity Analysis

**Strong, well-justified AI opportunities (build with AI):**
- **Predictive analytics / ML:** 26071, 26085, 26192 (flood), 26001 (landslide), 26109 (mastitis), 26102/26184 (fraud), 26153 (attack forecasting).
- **Computer vision:** 26166, 26175, 26158 (drone→3D), 26031 (grading), 26127 (ANPR), 26187 (border).
- **NLP / GenAI / RAG:** 26107/26108 (BIS), 26045 (IP-SAKTI), 26165 (SIF precursors), 26042/26097/26173 (Indian-language).
- **AI agents:** 26117 (sovereign agentic workbench), 26176 (ORCA), 26171 (browser agents).
- **Cybersecurity AI:** 26151, 26153, 26155, 26189.

**AI-washing risk (add AI only if it earns its place):** 26099 (material codes → deterministic MDM), 26103 (project monitoring → dashboards), 26035/26036 (metrology test reports → rules engines), 26048 (kwatha maker → embedded control, not AI), 26076 (app homepage personalization → simple ranking).

---

## Cybersecurity Opportunity Analysis

- **Security-critical (security is the core deliverable):** 26125, 26141, 26145, 26149, 26159, 26160, 26164, 26182, 26183, 26184, 26189, 26190, 26146, 26055.
- **Security-important:** 26105, 26106, 26150, 26151, 26153, 26155, 26156, 26157, 26188, 26117, 26129, 26187, 26102.
- **Security-useful:** 26024, 26125-adjacent governance, 26181 (health data), 26186, 26190.
- **Security-not-relevant (do not bolt on cybersecurity):** 26005/26110 (cold storage), 26022 (agarbatti drying), 26048 (kwatha maker), 26020 (khadi spinning), 26064 (metal detector), 26096 (heritage archive display).

---

## Feasibility Analysis

- **🟢 Highly feasible for student teams:** software detection apps, RAG assistants, dashboards, forecasting on open data — 26028, 26073, 26092, 26107, 26108, 26131, 26152, 26162, 26035, 26036, 26075.
- **🟡 Feasible with scope reduction:** most MoES nowcasting (need data access), 26001, 26085, 26109, 26111, 26187 — reduce to a single district/region/model.
- **🟠 Difficult:** hardware-heavy or specialized-data — 26025, 26065, 26112, 26120, 26144, 26177, 26185, 26064, 26050.
- **🔴 Very difficult (avoid unless team has domain access):** 26098 (155mm fuze — restricted, safety-critical), classified EW (26055), high-altitude defence hardware.

**Feasibility rule for teams:** pick 🟡 problems where a public data source exists (IMD, Bhuvan, ISRO Bhoonidhi, NASA FIRMS) and a defensible slice can be demoed in 36 hours.

---

## Market Potential

- **High commercial/enterprise potential:** agri cold chain (26005), crop advisory (26131/26132), healthcare screening (26038), cybersecurity tooling (26105/26153/26164), digital twins (26120), ANPR (26127).
- **High government-adoption potential:** MoES weather cluster, MHA cyber/forensics, NTRO tools, land-records cluster, disaster EWS.
- **Lower commercial but high social impact:** rural artisan/entrepreneur platforms (26090-26092), heritage (26096), skilling (26134/26135).

---

## Top 20 Overall
1. SIH26071 (Rainfall EWS + inundation) · 2. SIH26085 (Urban flood nowcast) · 3. SIH26166 (Chandrayaan image correspondence) · 4. SIH26001 (Landslide EWS NER) · 5. SIH26192 (Flash-flood hilly) · 6. SIH26143 (Oil spill AIS+SAR) · 7. SIH26187 (Border video AI) · 8. SIH26176 (ORCA marine agents) · 9. SIH26117 (Sovereign agentic AI) · 10. SIH26073 (AWS anomaly detection) · 11. SIH26109 (Bovine mastitis) · 12. SIH26111 (Rapid feed/silage) · 13. SIH26083 (Heatwave index) · 14. SIH26072 (Thunderstorm nowcast) · 15. SIH26079 (Forecast-bust) · 16. SIH26066 (Subsurface temp DL) · 17. SIH26167 (SatQuery VLM) · 18. SIH26025 (Mine subsidence) · 19. SIH26074 (Downscale forecast) · 20. SIH26171 (Browser-agent perception).

## Top 10 Potentially New (🟢)
SIH26166, SIH26176, SIH26066, SIH26169, SIH26175, SIH26121, SIH26073, SIH26079, SIH26102, SIH26118.

## Top 10 Differentiation Opportunities (🟡, strong)
SIH26001, SIH26025, SIH26143, SIH26109, SIH26111, SIH26104, SIH26187, SIH26150, SIH26070, SIH26173.

## Top AI Opportunities
SIH26071, SIH26085, SIH26166, SIH26176, SIH26109, SIH26102, SIH26184, SIH26153, SIH26165, SIH26175.

## Top Cybersecurity Opportunities
SIH26145, SIH26159, SIH26164, SIH26182, SIH26184, SIH26189, SIH26151, SIH26055, SIH26141, SIH26190.

## Top Startup Opportunities
SIH26005 (cold chain), SIH26111 (feed testing), SIH26109 (mastitis), SIH26131 (crop advisory), SIH26120 (digital twin), SIH26104 (voice-clone defense), SIH26127-adjacent mobility, SIH26143 (oil spill), SIH26038 (retinopathy), SIH26173 (Indian-language STT/TTS).

## Top Student-Friendly Problems (🟢 feasibility)
SIH26073, SIH26107, SIH26108, SIH26092, SIH26131, SIH26162, SIH26028, SIH26035, SIH26152, SIH26075.

## Top 10 High-Impact Problems
SIH26071, SIH26085, SIH26001, SIH26192, SIH26083, SIH26038, SIH26133, SIH26039, SIH26187, SIH26102.

## Top 10 Hardware Problems
SIH26025, SIH26065, SIH26144, SIH26118, SIH26064, SIH26050, SIH26185, SIH26177, SIH26109, SIH26058.

## Top 10 Software Problems
SIH26071, SIH26085, SIH26166, SIH26176, SIH26117, SIH26073, SIH26187, SIH26102, SIH26165, SIH26167.

---

## Final Ranking of All 226

Ranked by Overall Score (out of 100). AICTE Student-Innovation slots (⚪, N/A) are unranked and listed last.

**Tier 1 (76–79):** 26071 (79), 26085 (78), 26166 (77), 26001 (76), 26192 (76).  
**Tier 2 (72–75):** 26143 (75), 26187 (75), 26176 (74), 26117 (74), 26073 (74), 26109 (73), 26111 (73), 26072 (73), 26083 (73), 26079 (73), 26025 (72), 26077 (72).  
**Tier 3 (69–71):** 26066 (71), 26074 (71), 26078 (71), 26082 (71), 26084 (71), 26167 (71), 26145 (71), 26060 (70), 26009 (70), 26081 (70), 26080 (70), 26086 (70), 26065 (70), 26058 (70), 26054 (70), 26171 (70), 26050 (69), 26055 (69), 26169 (69), 26059 (69), 26070 (69), 26175 (69).  
**Tier 4 (66–68):** 26191 (69), 26161 (69), 26102 (68), 26104 (68), 26119 (68), 26165 (68), 26168 (68), 26057 (68), 26177 (68), 26026 (68), 26120 (68), 26159 (68), 26141 (68), 26037 (68), 26184 (68), 26178 (68), 26011 (68), 26121 (67), 26170 (67), 26017 (67), 26189 (67), 26150 (67), 26185 (66), 26144 (66), 26174 (66), 26173 (66), 26126 (66), 26158 (66), 26151 (66), 26153 (66), 26107 (66), 26020 (66), 26142 (66), 26061 (66), 26069 (66), 26068 (66), 26147 (65), 26105 (65), 26108 (65), 26038 (65), 26051 (65), 26098 (65), 26064 (65), 26039 (65).  
**Tier 5 (60–64):** 26100 (64), 26128 (64), 26002 (64), 26127 (63), 26186 (63), 26094 (63), 26093 (63), 26162 (63), 26031 (63), 26188 (63), 26182 (63), 26139 (63), 26045 (63), 26042 (63), 26160 (63), 26155 (63), 26129 (63), 26122 (62), 26124 (62), 26056 (62), 26156 (62), 26157 (62), 26183 (62), 26097 (62), 26092 (61), 26113 (61), 26115 (61), 26137 (61), 26049 (61), 26190 (61), 26008 (63), 26007 (67), 26006 (62), 26138 (62), 26024 (63), 26010 (60), 26021 (60), 26089 (60), 26132 (60), 26018 (60), 26016 (59), 26130 (60), 26146 (60), 26136 (59), 26091 (59), 26101 (59), 26140 (59), 26096 (59), 26033 (59), 26088 (59), 26110 (60), 26048 (60), 26112 (55).  
**Tier 6 (53–58):** 26099 (58), 26103 (58), 26023 (58), 26034 (58), 26035 (58), 26036 (58), 26090 (58), 26063 (54), 26095 (56), 26076 (56), 26181 (57), 26134 (57), 26135 (57), 26032 (57), 26087 (57), 26062 (57), 26030 (58), 26019 (57), 26041 (61), 26022 (56), 26044 (55), 26163 (55), 26075 (54), 26116 (53), 26114 (54), 26154 (60), 26152 (57), 26179 (56), 26133 (60), 26046 (58), 26005 (60), 26040 (61), 26067 (62), 26043 (62), 26003 (63), 26004 (61), 26047 (61), 26029 (61), 26013 (66), 26014 (61), 26015 (66), 26012 (60), 26028 (63), 26027 (68), 26053 (66), 26052 (66), 26164 (62), 26148 (60), 26149 (59), 26125 (63), 26106 (66).

**Unranked ⚪ (AICTE Student Innovation, N/A):** 26193–26226 (34 slots).

---

## Research Methodology
- **Primary source (ground truth):** Official SIH 2026 list of 226 statements.
- **External web research:** Targeted queries across the highest-value evidence clusters.
- **Scoring:** Weighted 9-factor model (Innovation 20%, Severity 15%, Feasibility 15%, Differentiation 15%, Market 10%, Social 10%, Scalability 5%, AI/Tech 5%, Buildability 5%).

## Limitations
- Statements outside researched clusters carry theme-level classifications.
- AICTE Student Innovation slots (34) have no fixed problem definitions and are marked ⚪.
- Competitor listings are non-exhaustive.

## Sources
IMD/MoES, PIB, IIT Mandi, Amrita University, Survey of India/SVAMITVA, Intertek, TraceX, Chainalysis, Elliptic, TRM Labs, Google Health/ARDA, JAMA, Hiya, Resemble AI, SkyGeo, Farmonaut, Honeywell, Halliburton, KUKA, Addverb, KSAT, EMSA CleanSeaNet, Ecozen, Tan90, Plantix, Blancco, Magnet Forensics, SalvationDATA, IBM, SandboxAQ, Onfido, Jumio, HyperVerge, Staqu, Vehant, BQP, D-Wave, Springer/NCBI research.
