# 🏡 XL Bonds KZN — Home Loan Application & Management Platform

A multi-platform home loan management ecosystem developed as a final-year BCAD capstone project (Team *Midas Touch*) for a KwaZulu-Natal mortgage brokerage. The solution bridges the gap between first-time homebuyers, bond consultants, and multiple South African banking partners.

---

## 🎯 The Problem & Discovery
Applying for a home loan in South Africa involves complex paperwork, confusing affordability criteria, and slow back-and-forth communication between buyers, bond originators, and banks. 

Through direct stakeholder consultations with the brokerage director and analysis of local homebuyer pain points (first-time buyers, refinancers, and property investors in KZN), we identified three core needs:
1. **Frictionless Client Onboarding:** Allow prospective buyers to estimate bond affordability in ZAR and securely upload sensitive financial documents without mandatory account creation (using browser-token session tracking).
2. **POPIA-Compliant Security:** Protect sensitive personal and financial documents (Offers to Purchase, Deeds of Sale, Bank Statements, Title Deeds) via file validation, malware scanning, encryption, and strict audit logging.
3. **On-the-Go Admin Management:** Equip bond consultants with both a web dashboard and a companion mobile app to review submissions, manage website content, and respond to leads remotely.

---

## 🔍 My Role & Key Contributions
Working within a 6-member Agile team, I focused on **user research, problem-solving, systems analysis, business feasibility, and UI/UX design**:
* **Client Liaison & Requirements Discovery:** Authored the formal Client Agreement and translated weekly stakeholder consultations into actionable functional and non-functional requirements.
* **User Flow & UX Wireframing:** Mapped the end-to-end client journey and designed low-fidelity desktop wireframes to establish clear visual hierarchy, guided bond calculations, and POPIA-compliant document uploads.
* **High-Fidelity UI/UX Prototyping:** Co-designed interactive web and mobile prototypes in **Figma** and **Canva**, integrating the client's brand palette (`#2EA80F` Kelly Green, `#1F7A0A` Forest Green) with mobile responsiveness.
* **Domain Modelling:** Designed the core **Domain Model Diagram** (Draw.io), mapping relationships across 10 core business entities.
* **Cloud Cost & Scalability Analysis:** Modelled Microsoft Azure infrastructure running costs and operational feasibility across 100, 1,000, and 10,000+ user growth tiers.
* **Change Management Strategy:** Developed a stakeholder impact assessment and rollout blueprint using the **ADKAR framework** to ensure smooth adoption by internal bond consultants and external clients.

---

## 🎨 Design & Analysis Showcase

### 1. End-to-End Client User Flow
*Mapping how a prospective homebuyer moves from checking bond affordability to submitting POPIA-compliant documents via browser-token session tracking—removing registration friction while keeping consultant follow-ups seamless.*

**[DRAG & DROP YOUR USER FLOW DIAGRAM PNG HERE]**

---

### 2. Low-Fidelity Desktop Wireframes
*Early structural wireframes focusing on information architecture, South African National Credit Act (NCA) affordability inputs, and categorized document upload states before applying brand styling.*

**[DRAG & DROP YOUR 3-FRAME WIREFRAME PNG HERE]**

---

### 3. High-Fidelity Prototypes (Web & Admin Mobile App)
*Final visual designs incorporating the XL Bonds KZN brand palette (`#2EA80F` Kelly Green and `#1F7A0A` Forest Green), responsive layouts, and mobile consultant tools for reviewing applicant files on the go.*

**[DRAG & DROP YOUR HIGH-FIDELITY FIGMA SCREENSHOTS HERE]**

* 🔗 **[View Interactive Figma Prototype](#)** *(Replace `#` with your public Figma view-only link)*

---

### 4. Domain Model Diagram (Systems Analysis)
*Core analytical class model defining the 10 primary entities (`Client`, `LoanApplication`, `AffordabilityCalculation`, `UploadedDocument`, `ContactEnquiry`, `Testimonial`, `Consultant`, `BankPartner`, `LoanOffer`, `WebsiteAdmin`) and their business cardinalities.*

**[DRAG & DROP YOUR DOMAIN MODEL DIAGRAM PNG HERE]**

---

### 5. ADKAR Change Management & Rollout Blueprint
*Structured adoption plan addressing stakeholder resistance, client digital literacy, and a 3-phase admin training and handover schedule prior to launch.*

**[DRAG & DROP YOUR ADKAR DIAGRAM PNG HERE]**

---

## 🏗️ Technical & Cloud Architecture
* **Client Web Portal:** Interactive ZAR affordability calculator, browser-cookie token uploader, partnered bank showcase, client testimonials, and direct enquiry routing.
* **Admin Web & Mobile Suite:** Two-factor authenticated (2FA) dashboard for reviewing applications, accessing uploaded files on mobile, managing awards/tips/bank partners, and tracking audit logs.
* **Cloud & Security Stack:** Microsoft Azure (App Service, Azure SQL Database, Azure Blob/File Storage, Azure Key Vault, Azure Queue Service), SSL/TLS encryption, and POPIA compliance controls.

---

## 🛠️ Tools & Methodologies Used
* **Analysis & Modelling:** Draw.io, MS Visio, MS Project, UML, Domain Modelling, ADKAR Change Management
* **UI/UX Design:** Figma, Canva, User Journey Mapping, Wireframing, Interactive Prototyping
* **Cloud & DevOps:** Microsoft Azure, GitHub Actions CI/CD
