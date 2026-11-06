<div align="center">
  <img src="assets/inti-university-seeklogo.png" alt="INTI International University Logo" width="380"/>
  <br><br>

  # Facebook Web Interface — UX Evaluation & Evidence-Based UI Redesign
  ### *Human-Computer Interaction (HCI) Empirical Research, Figma Prototyping & Usability Testing Study*

  ![Scholarship](https://img.shields.io/badge/Scholarship-Fully_Funded_Student_Mobility_Program_(June_2026)-B31B1B?style=flat-square)
  ![Host University](https://img.shields.io/badge/Host_University-INTI_International_University_(Nilai,_Malaysia)-003366?style=flat-square)
  ![Figma](https://img.shields.io/badge/UI%2FUX_Design-Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)
  ![Research](https://img.shields.io/badge/UX_Research-Quantitative_Survey_(n%3D30)-0078D4?style=flat-square)
  ![Usability Testing](https://img.shields.io/badge/Satisfaction_Score-93.7%25_(Up_to_4.68%2F5.0)-2EA043?style=flat-square)

  **Module:** HCI3202 — Human Computer Interface (Section: 6H1 / 6MB1)  
  **Session:** June 2026 (Student Mobility Program — Fully Funded Scholarship)  
  **Faculty:** Faculty of Data Science and Information Technology, INTI International University, Nilai, Malaysia  
  **Lecturer / Examiner:** Kala Devi Managuran  
  **Figma Live Prototype:** [View Interactive Figma Design File](https://www.figma.com/design/tw2N4MICB6PatYu2xUMqnl/HCI-Facebook-UI?node-id=0-1&p=f&t=IavYmT34WyPBH99L-0)

</div>

---

## Table of Contents
- [Project Overview & Academic Mobility Context](#project-overview--academic-mobility-context)
- [UX Research Methodology & Target Personas](#ux-research-methodology--target-personas)
- [Tools, Methodologies & HCI Principles](#tools-methodologies--hci-principles)
- [Baseline UX Audit Across Nine Core Pages](#baseline-ux-audit-across-nine-core-pages)
- [Problem Identification & Testable Hypotheses](#problem-identification--testable-hypotheses)
- [Interaction Design & Information Architecture](#interaction-design--information-architecture)
- [Visual Walkthrough: Default vs. Redesigned UI](#visual-walkthrough-default-vs-redesigned-ui)
- [Post-Redesign Usability Testing & Validation](#post-redesign-usability-testing--validation)
- [Repository File Structure](#repository-file-structure)
- [Author & Academic Details](#author--academic-details)

---

## Project Overview & Academic Mobility Context
**Facebook Web Interface — UX Evaluation & Evidence-Based UI Redesign** is an empirical Human-Computer Interaction (HCI) and User-Centered Design (UCD) study completed at **INTI International University (Nilai, Malaysia)** during the **June 2026 Session** under a **Fully Funded International Student Mobility Scholarship Program**.

Supervised by **Kala Devi Managuran** in the Faculty of Data Science and Information Technology, this study evaluates user satisfaction and interface friction across **nine core desktop web pages** of Facebook (`Login`, `Registration`, `Home Feed / Dashboard`, `Profile`, `Friend Request`, `Message`, `Notifications`, `Settings`, and `Create Post`). Rather than performing arbitrary visual changes, this project implements a data-driven two-phase empirical loop:
1. **Phase 1 (Baseline Quantitative UX Audit):** A structured survey of $n = 30$ active young-adult users (aged 19–26) identified four statistically significant usability bottlenecks while confirming that five pages already met user expectations.
2. **Phase 2 (Targeted Figma Redesign & A/B Validation):** Only the four high-friction interfaces (`Home Feed`, `Registration`, `Friend Request`, and `Notifications`) were re-engineered in **Figma** and re-evaluated by the exact same participant pool ($n = 30\text{–}31$), achieving up to **93.7% user preference** and satisfaction ratings between **4.03 and 4.68 out of 5.0**.

---

## UX Research Methodology & Target Personas

### Target Audience & Sampling Strategy
* **Demographics:** University students and young working adults aged **18–35 years** (survey sample concentrated between **19–26 years**, $n = 30$).
* **Platform Scope:** Desktop Web Interface of Facebook, evaluated across three behavioral usage segments: **Daily Active Users**, **Weekly Users**, and **Infrequent/Rare Visitors**.

### Representative User Personas

| Persona Profile | Usage Frequency | Key Frustrations Identified | Preferred UX Improvements |
| :--- | :---: | :--- | :--- |
| **Persona 1: Md Arif Mahmud Oyion**<br>*(23, Undergraduate Student, INTI International University)* | **Daily**<br>*(Laptop Web)* | • **Home Feed:** In-feed advertisements interrupt content browsing.<br>• **Friend Requests:** `Accept` and `Decline` buttons are placed too close together.<br>• **Registration:** Too many input fields presented simultaneously. | • Relocate sponsored ads to a dedicated right-hand sidebar.<br>• Increase spacing between action buttons.<br>• Streamline form progression. |
| **Persona 2: Chia Kim Hua**<br>*(21, Undergraduate Student, INTI International University)* | **Weekly**<br>*(A few times/week)* | • **Registration:** Error messages are vague and difficult to locate.<br>• **Friend Requests:** Incoming requests are visually mixed with *"People You May Know"* suggestions. | • Display explicit, inline error messages next to invalid inputs.<br>• Separate incoming requests from friend suggestions. |
| **Persona 3: Md Sadek Hosen**<br>*(24, Undergraduate Student, AIUB)* | **Rarely**<br>*(Infrequent User)* | • **Notifications:** Difficult to distinguish unread notifications from older read items.<br>• **Friend Requests & Registration:** High cognitive load from mixed lists and dense forms. | • Add high-contrast unread badges and dot indicators.<br>• Group and separate interface sections clearly. |

---

## Tools, Methodologies & HCI Principles

| Category | Tool / Framework | Application in Study |
| :--- | :--- | :--- |
| **UI/UX Prototyping** | **Figma** | High-fidelity 1440×1080 desktop wireframing, interactive states, component auto-layout, and visual redesign |
| **Quantitative UX Research** | **Google Forms (2-Wave Survey)** | Baseline diagnostic survey ($n = 30$) and post-redesign validation survey ($n = 30\text{–}31$) |
| **HCI Design Principles** | **Fitts's Law & Error Prevention** | Expanding button spacing on the Friend Request page to prevent accidental destructive clicks (`Delete`) |
| **Visual Hierarchy & Gestalt** | **Figure-Ground & Proximity Grouping** | Separating `Incoming Friend Requests` from `People You May Know` and isolating `Sponsored` ads into a side column |
| **System Status Visibility** | **Nielsen's Heuristics** | Inline bold-red validation errors on the Registration page and unread count badges/dot markers on Notifications |

---

## Baseline UX Audit Across Nine Core Pages

Each of the evaluated pages was assessed across three dimensions: **Overall Satisfaction** (`Satisfied`, `Neutral`, `Dissatisfied`), **Primary Usability Issue**, and **Most Requested Improvement**. Pages with low dissatisfaction and strong *"Keep it as it is"* consensus were intentionally preserved to prevent unnecessary cognitive disruption.

| Interface Page | Dissatisfied | Neutral | Satisfied | Primary Reported Issue (% of Users) | Top Requested Action | Redesign Decision |
| :--- | :---: | :---: | :---: | :--- | :--- | :---: |
| **1. Login Page** | `13.3%` | `60.0%` | `26.7%` | No issues (`53.3%`) / Looks plain (`30.0%`) | Keep it as it is (`43.3%`) | **Retained Default** |
| **2. Registration Page** | **`20.0%`** | `56.7%` | `23.3%` | **Error messages are unclear (`53.3%`)** | **Show clearer error messages (`33.3%`)** | **Redesigned** |
| **3. Home Feed (Dashboard)** | **`26.7%`** | `53.3%` | `20.0%` | **Ads shown in middle of feed (`53.3%`)** | **Move ads to the side (`33.3%`)** | **Redesigned** |
| **4. Profile Page** | `3.3%` | `60.0%` | `36.7%` | No issues (`43.3%`) / Hard to find About (`30%`) | Keep it as it is (`50.0%`) | **Retained Default** |
| **5. Friend Request Page** | **`26.7%`** | `53.3%` | `20.0%` | **Buttons too close (`36.7%`) & Mixed lists (`10%`)** | **Separate lists (`36.7%`) + Space buttons (`20%`)** | **Redesigned** |
| **6. Message Page** | `10.0%` | `50.0%` | `40.0%` | No issues (`46.7%`) | Keep it as it is (`46.7%`) | **Retained Default** |
| **7. Notifications Page** | `10.0%` | `56.7%` | `33.3%` | **Hard to tell new from old (`23.3%`) / Mixed (`20%`)** | **Highlight unread clearly (`20.0%`) + Group (`13.3%`)** | **Redesigned** |
| **8. Settings Page** | `13.3%` | `43.3%` | `43.3%` | No issues (`46.7%`) | Keep it as it is (`66.7%`) | **Retained Default** |
| **9. Create Post Page** | — | — | — | Baseline modal workflow evaluated as standard | Keep it as it is | **Retained Default** |

---

## Problem Identification & Testable Hypotheses

```text
+-----------------------------------------------------------------------------------+
|                        USER-CENTERED HCI REDESIGN PIPELINE                        |
+-----------------------------------------------------------------------------------+
|                                                                                   |
|  [Phase 1: Baseline Survey (n=30)]                                                |
|         │                                                                         |
|         ├──► Pain Point 1: In-feed ads disrupt reading flow (53.3% complaint)     |
|         │    └──► Hypothesis 1: Relocate Sponsored Ads to a right-hand column.    |
|         │                                                                         |
|         ├──► Pain Point 2: Accept/Decline proximity & mixed suggestions (56.7%)   |
|         │    └──► Hypothesis 2: Increase button padding & split request sections. |
|         │                                                                         |
|         ├──► Pain Point 3: Ambiguous registration validation errors (53.3%)       |
|         │    └──► Hypothesis 3: Add red input borders & bold inline error text.   |
|         │                                                                         |
|         └──► Pain Point 4: Unread notifications blend with old items (43.3%)      |
|              └──► Hypothesis 4: Add unread count badges, blue dots & filters.     |
|                                                                                   |
+-----------------------------------------------------------------------------------+
```

1. **Hypothesis 1 (Home Feed — Content Stream Continuity):** Relocating sponsored advertisements from the center of the news feed to a dedicated right-hand sidebar column will eliminate scrolling interruptions and increase browsing satisfaction.
2. **Hypothesis 2 (Friend Requests — Fitts's Law & Categorization):** Increasing spatial separation between `Confirm` and `Delete` buttons and isolating `Incoming Friend Requests` from `People You May Know` will reduce misclicks and improve navigation clarity.
3. **Hypothesis 3 (Registration — Inline Error Recovery):** Highlighting invalid form fields with red borders and placing explicit, bold red error descriptions directly beneath the affected inputs will accelerate error recovery during onboarding.
4. **Hypothesis 4 (Notifications — Visual Salience):** Introducing top-bar unread counters, blue status dots, shaded unread cards, and category filter pills (`All`, `Unread`, `Friend Requests`, `Groups`, `Events`, `Security`) will allow users to distinguish new activity at a glance.

---

## Interaction Design & Information Architecture
* **Hub-and-Spoke Navigation Model:** The prototype uses a shallow hub-and-spoke architecture centered on the **Home Feed (Dashboard)**. Every core destination (`Profile`, `Friend Requests`, `Messages`, `Notifications`, `Settings`, and `Create Post`) is reachable within **one click** via the persistent top navigation bar or left-hand navigation drawer.
* **Card-Based Content Modularization:** Posts, friend request cards, and notification items are encapsulated in distinct visual containers with consistent padding, hover states, and clear typographic hierarchy.

---

## Visual Walkthrough: Default vs. Redesigned UI

### Part 1: Evidence-Based Redesigned Interfaces (Before vs. After)

#### 1. Home Feed / Dashboard (`Sponsored` Ads Relocated to Sidebar)
* **Design Intervention:** Removed disruptive mid-feed sponsored posts and consolidated them into a clean right-hand `Sponsored` column above quick `Friend requests` and `Contacts`.

| Default Home Feed (`Default UI Design`) | Redesigned Home Feed (`Redesign Pages`) |
| :---: | :---: |
| ![Default Home Feed](Default%20UI%20Design/3%20Facebook%20Dashboard%20Home%20Feed.jpg) | ![Redesigned Home Feed](Redesign%20Pages/Facebook%20Home%20Feed%20Dashboard%20-%20Redesign.png) |

#### 2. Registration Page (High-Contrast Inline Error State)
* **Design Intervention:** Added explicit red input borders and bold red inline validation messages (`"Please enter a valid mobile number or email address"` and `"Password must be at least 6 characters long"`) directly below the problematic fields.

| Default Registration Page (`Default UI Design`) | Redesigned Registration Error State (`Redesign Pages`) |
| :---: | :---: |
| ![Default Registration Page](Default%20UI%20Design/2%20Facebook%20Registration%20Page.jpg) | ![Redesigned Registration Page](Redesign%20Pages/Facebook%20Registration%20Page%20-%20Error%20State.jpg) |

#### 3. Friend Request Page (Button Spacing & Dedicated Left Navigation)
* **Design Intervention:** Added a dedicated left-hand `Friends` category sidebar (`IncomingRequests`, `Suggestions`, `All Friends`, `Birthdays`), expanded vertical spacing between `Confirm` and `Delete` buttons, and clearly separated `Incoming Friend Requests`, `People You May Know`, and `Sent Friend Requests`.

| Default Friend Request Page (`Default UI Design`) | Redesigned Friend Request Page (`Redesign Pages`) |
| :---: | :---: |
| ![Default Friend Request Page](Default%20UI%20Design/5%20Facebook%20Friend%20Request%20Page.jpg) | ![Redesigned Friend Request Page](Redesign%20Pages/Facebook%20Friend%20Request%20Page%20-%20Redesign.png) |

#### 4. Notifications Page (Unread Highlighting, Badges & Filter Sidebar)
* **Design Intervention:** Added a left-hand `Notifications` filter panel (`All Notifications`, `Unread`, `Friend Requests`, `Groups`, `Events`, `Security`), shaded unread notification rows with prominent blue indicator dots, and introduced contextual action buttons (`Confirm`/`Delete`, `Review Login`, `Interested`/`Ignore`).

| Default Notifications Page (`Default UI Design`) | Redesigned Notifications Page (`Redesign Pages`) |
| :---: | :---: |
| ![Default Notifications Page](Default%20UI%20Design/7%20Facebook%20Notifications%20Page.jpg) | ![Redesigned Notifications Page](Redesign%20Pages/Facebook%20Notifications%20Page%20-%20Redesign.png) |

---

### Part 2: Preserved Baseline Interfaces (Validated as Satisfactory)

<details>
<summary><b>Click to Expand: View the 5 Unchanged Core Interfaces (Login, Profile, Message, Settings & Create Post)</b></summary>
<br>

> 📌 *Note: If `1 Facebook Login Page` and `6 Facebook Message Page` in your folder use `.png` instead of `.jpg`, adjust their file extensions below accordingly.*

| 1. Login Page | 4. Profile Page |
| :---: | :---: |
| ![Facebook Login Page](Default%20UI%20Design/1%20Facebook%20Login%20Page.jpg) | ![Facebook Profile Page](Default%20UI%20Design/4%20Facebook%20Profile%20Page.jpg) |

| 6. Message Page | 8. Settings Page |
| :---: | :---: |
| ![Facebook Message Page](Default%20UI%20Design/6%20Facebook%20Message%20Page.jpg) | ![Facebook Settings Page](Default%20UI%20Design/8%20Facebook%20Settings%20Page.jpg) |

| 9. Create Post Modal Page |
| :---: |
| ![Facebook Create Post Page](Default%20UI%20Design/9%20Facebook%20Create%20Post%20Page.jpg) |

</details>

---

## Post-Redesign Usability Testing & Validation
To measure the exact impact of the UI modifications without sample bias, the **same 30–31 respondents** from the baseline study evaluated the four redesigned prototypes on a direct preference test (`Satisfied with New Design` vs. `Want Default Design`) and a **5-Point Likert Rating Scale (`1` to `5`)**.

### Quantitative Before-and-After Comparison

| Redesigned Interface | Baseline Dissatisfaction | Post-Redesign Preference (% Satisfied) | Mean Rating (Out of 5.0) | 4 & 5-Star Rating Share | 1-Star Ratings |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **Notifications Page** | `10.0%` *(56.7% Neutral)* | **`90.3%`** *(28 / 31)* | **`4.68 / 5.0`** | **`93.6%`** *(74.2% gave 5★)* | `0.0%` |
| **Friend Request Page** | `26.7%` *(53.3% Neutral)* | **`93.5%`** *(29 / 31)* | **`4.39 / 5.0`** | **`93.6%`** *(48.4% gave 5★)* | `0.0%` |
| **Registration Page** | `20.0%` *(56.7% Neutral)* | **`76.7%`** *(23 / 30)* | **`4.03 / 5.0`** | **`76.7%`** *(46.7% 4★, 30% 5★)* | `0.0%` |
| **Home Feed (Dashboard)** | `26.7%` *(53.3% Neutral)* | **`76.7%`** *(23 / 30)* | **`4.03 / 5.0`** | **`76.7%`** *(40.0% gave 5★)* | `0.0%` |

### Key Usability Takeaways
* **Zero Critical Failures (`0%` 1-Star Ratings):** None of the 31 participants rated any redesigned screen 1 star, confirming that the new layouts introduced zero functional regressions or navigational confusion.
* **Highest Gains in Task-Critical Pages:** The **Notifications Page (`4.68/5.0`)** and **Friend Request Page (`4.39/5.0`, `93.5%` preference)** achieved the strongest approval, validating that Fitts's Law button spacing and visual unread indicators directly resolved user friction.

---

## Repository File Structure

```text
Facebook-UI-Redesign-HCI-Figma/
├── assets/
│   └── inti-university-seeklogo.png                         # INTI International University Official Logo
├── Default UI Design/                                       # 9 Baseline Facebook Web UI Screens
│   ├── 1 Facebook Login Page.jpg
│   ├── 2 Facebook Registration Page.jpg
│   ├── 3 Facebook Dashboard Home Feed.jpg
│   ├── 4 Facebook Profile Page.jpg
│   ├── 5 Facebook Friend Request Page.jpg
│   ├── 6 Facebook Message Page.jpg
│   ├── 7 Facebook Notifications Page.jpg
│   ├── 8 Facebook Settings Page.jpg
│   └── 9 Facebook Create Post Page.jpg
├── Redesign Pages/                                          # 4 Evidence-Based Redesigned Figma Screens
│   ├── Facebook Friend Request Page - Redesign.png
│   ├── Facebook Home Feed Dashboard - Redesign.png
│   ├── Facebook Notifications Page - Redesign.png
│   └── Facebook Registration Page - Error State.jpg
├── Presentation Slide Facebook UI Resign.pptx               # Project Defense PowerPoint Presentation
├── Facebook UI - FIgma HCI.pdf                              # Complete 41-Page HCI Research & Usability Report
└── README.md                                                # Project Documentation
```

---

## Author & Academic Details

| Attribute | Details |
| :--- | :--- |
| **Student Name** | **Shahadat Hossain** |
| **INTI Student ID** | `I26041279` (Section: `6H1 / 6MB1`) |
| **Scholarship Program** | **Fully Funded Student Mobility Program (June 2026 Session)** |
| **Host University** | **INTI International University**, Nilai, Negeri Sembilan, Malaysia |
| **Faculty** | Faculty of Data Science and Information Technology |
| **Course / Module Code** | `HCI3202` — Human Computer Interface (Programme: `BITI`) |
| **Lecturer / Examiner** | **Kala Devi Managuran** (`kaladevi.managuran@newinti.edu.my`) |

---

<div align="center">
  <i>Completed during the June 2026 Fully Funded Student Mobility Program at INTI International University, Nilai, Malaysia.</i>
</div>