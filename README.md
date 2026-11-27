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

<img width="3166" height="185" alt="diagram" src="https://github.com/user-attachments/assets/9af32f28-8e9f-4f75-9a51-d780c4b7fb42" />
<svg class="dark " xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3165.98 184.8" width="3165.98" height="184.8" id="mdf1272__root" data-diagram-type="flowchart">
  <style data-mercat-style="universal">.mercat text{font-family:'Google Sans',Roboto,Arial,sans-serif;fill:var(--m-text);dominant-baseline:central}.mercat .m-node .m-shape{fill:var(--m-node-fill);stroke:var(--m-node-stroke);stroke-width:1.5px}.mercat .m-edge .m-path{fill:none;stroke:var(--m-line);stroke-width:1.5px}.mercat .m-edge-label .m-pill-bg,.mercat .m-edge-label .m-shape{fill:var(--m-pill-bg);stroke:var(--m-pill-border);stroke-width:1px}.mercat .m-edge-label .m-label{fill:var(--m-text-sec)}.mercat .t-label{font-size:13px;font-weight:500}.mercat .t-edge{font-size:11px;font-weight:400}</style>
  <style data-mercat-style="theme-light">#mdf1272__root{--m-text:#1f1f1f;--m-text-sec:#797979;--m-line:#545454;--m-node-fill:#f8f9fa;--m-node-stroke:#747775;--m-pill-bg:#fbfbfb;--m-pill-border:#d7d7d7}</style>
  <style data-mercat-style="theme-dark">#mdf1272__root.dark{--m-text:#e3e3e3;--m-text-sec:#959595;--m-line:#bfbfbf;--m-node-fill:#2d2e30;--m-node-stroke:#8e918f;--m-pill-bg:#232323;--m-pill-border:#424242}</style>
  <style data-mercat-style="diagram">#mdf1272__root .m-s0 .m-shape,#mdf1272__root .m-s0 .m-path{fill:#2ea80f;stroke:#1f7a0a}#mdf1272__root .m-s1 .m-shape,#mdf1272__root .m-s1 .m-path{fill:#e8f5e9;stroke:#2ea80f}#mdf1272__root .m-s1 .m-label,#mdf1272__root .m-s1.m-label{fill:#1a1a1a}#mdf1272__root.dark .m-s0 .m-label,#mdf1272__root.dark .m-s0.m-label{fill:#1f1f1f}#mdf1272__root.dark .m-s1 .m-shape,#mdf1272__root.dark .m-s1 .m-path{fill:#264f29}#mdf1272__root.dark .m-s1 .m-label,#mdf1272__root.dark .m-s1.m-label{fill:#f1f1f1}</style>
  <g class="mercat mercat-flowchart" transform="translate(-35, -58.65)">
    <defs>
      <marker id="mdf1272__mk-arrow" refX="9.45" refY="3.4" markerWidth="10.8" markerHeight="6.8" markerUnits="userSpaceOnUse" orient="auto-start-reverse">
        <path d="M 0 0 L 10.8 3.4 L 0 6.8 Z" class="m-marker" fill="var(--m-line)" stroke="none"/>
      </marker>
    </defs>
    <g class="m-node m-edge" id="mdf1272__edge__A__B__0" data-role="connector">
      <path d="M 208.18 150 L 266.83 150" class="m-path" marker-end="url(#mdf1272__mk-arrow)"/>
    </g>
    <g class="m-node m-edge" id="mdf1272__edge__B__C__0" data-role="connector">
      <path d="M 361.57 108.8 L 361.57 98.8 Q 361.57 92.8, 367.57 92.8 L 484.96 92.8 Q 490.96 92.8, 490.96 98.8 L 490.96 102.8 Q 490.96 108.8, 496.96 108.8 L 590.52 108.8" class="m-path" marker-end="url(#mdf1272__mk-arrow)"/>
    </g>
    <g class="m-node m-edge" id="mdf1272__edge__C__D__0" data-role="connector">
      <path d="M 794.37 110 L 869.93 110" class="m-path" marker-end="url(#mdf1272__mk-arrow)"/>
    </g>
    <g class="m-node m-edge" id="mdf1272__edge__B__E__0" data-role="connector">
      <path d="M 361.57 191.2 L 361.57 201.2 Q 361.57 207.2, 367.57 207.2 L 484.96 207.2 Q 490.96 207.2, 490.96 201.2 L 490.96 197.2 Q 490.96 191.2, 496.96 191.2 L 573.61 191.2" class="m-path" marker-end="url(#mdf1272__mk-arrow)"/>
    </g>
    <g class="m-node m-edge" id="mdf1272__edge__D__F__0" data-role="connector">
      <path d="M 1116.46 110 L 1146.46 110 Q 1152.46 110, 1152.46 116 L 1152.46 144 Q 1152.46 150, 1158.46 150 L 1175.11 150" class="m-path" marker-end="url(#mdf1272__mk-arrow)"/>
    </g>
    <g class="m-node m-edge" id="mdf1272__edge__E__F__0" data-role="connector">
      <path d="M 811.28 190 L 1313.55 190 Q 1319.55 190, 1319.55 184 L 1319.55 169.8" class="m-path" marker-end="url(#mdf1272__mk-arrow)"/>
    </g>
    <g class="m-node m-edge" id="mdf1272__edge__F__G__0" data-role="connector">
      <path d="M 1397.09 150 L 1455.74 150" class="m-path" marker-end="url(#mdf1272__mk-arrow)"/>
    </g>
    <g class="m-node m-edge" id="mdf1272__edge__G__H__0" data-role="connector">
      <path d="M 1696.6 150 L 1755.25 150" class="m-path" marker-end="url(#mdf1272__mk-arrow)"/>
    </g>
    <g class="m-node m-edge" id="mdf1272__edge__H__I__0" data-role="connector">
      <path d="M 1976.61 145.7 L 2042.2 145.7 Q 2048.2 145.7, 2048.2 139.7 L 2048.2 116 Q 2048.2 110, 2054.2 110 L 2102.44 110" class="m-path" marker-end="url(#mdf1272__mk-arrow)"/>
    </g>
    <g class="m-node m-edge" id="mdf1272__edge__H__J__0" data-role="connector">
      <path d="M 1976.61 154.31 L 2038.61 154.31 Q 2044.61 154.31, 2044.61 160.31 L 2044.61 184 Q 2044.61 190, 2050.61 190 L 2095.26 190" class="m-path" marker-end="url(#mdf1272__mk-arrow)"/>
    </g>
    <g class="m-node m-edge" id="mdf1272__edge__J__F__0" data-role="connector">
      <path d="M 2199.65 208.45 L 2199.65 222.45 Q 2199.65 228.45, 2193.65 228.45 L 1260 228.45 Q 1254 228.45, 1254 222.45 L 1254 169.8" class="m-path" marker-end="url(#mdf1272__mk-arrow)"/>
    </g>
    <g class="m-node m-edge" id="mdf1272__edge__I__K__0" data-role="connector">
      <path d="M 2295.51 110 L 2361.34 110" class="m-path" marker-end="url(#mdf1272__mk-arrow)"/>
    </g>
    <g class="m-node m-edge" id="mdf1272__edge__K__L__0" data-role="connector">
      <path d="M 2598.84 110 L 2657.49 110" class="m-path" marker-end="url(#mdf1272__mk-arrow)"/>
    </g>
    <g class="m-node m-edge" id="mdf1272__edge__L__M__0" data-role="connector">
      <path d="M 2920.53 110 L 2979.18 110" class="m-path" marker-end="url(#mdf1272__mk-arrow)"/>
    </g>
    <g class="m-node m-node--stadium m-s0" id="mdf1272__node__A" data-role="vertex">
      <rect x="50" y="131.55" width="158.18" height="36.9" rx="18.45" ry="18.45" class="m-shape"/>
      <text x="129.09" y="150" class="m-label t-label" text-anchor="middle">Client Visits Website</text>
    </g>
    <g class="m-node m-node--diamond" id="mdf1272__node__B" data-role="vertex">
      <polygon points="361.57,108.8 454.96,150 361.57,191.2 268.18,150" class="m-shape"/>
      <text x="361.57" y="150" class="m-label t-label" text-anchor="middle">Knows Budget?</text>
    </g>
    <g class="m-node m-node--rect" id="mdf1272__node__C" data-role="vertex">
      <rect x="591.87" y="91.55" width="202.5" height="36.9" class="m-shape"/>
      <text x="693.12" y="110" class="m-label t-label" text-anchor="middle">Use Affordability Calculator</text>
    </g>
    <g class="m-node m-node--rect" id="mdf1272__node__E" data-role="vertex">
      <rect x="574.96" y="171.55" width="236.32" height="36.9" class="m-shape"/>
      <text x="693.12" y="190" class="m-label t-label" text-anchor="middle">Browse Services &amp; Bank Partners</text>
    </g>
    <g class="m-node m-node--rect" id="mdf1272__node__D" data-role="vertex">
      <rect x="871.28" y="91.55" width="245.18" height="36.9" class="m-shape"/>
      <text x="993.87" y="110" class="m-label t-label" text-anchor="middle">View Estimated Bond Qualification</text>
    </g>
    <g class="m-node m-node--rect" id="mdf1272__node__F" data-role="vertex">
      <rect x="1176.46" y="131.55" width="220.63" height="36.9" class="m-shape"/>
      <text x="1286.77" y="150" class="m-label t-label" text-anchor="middle">Upload Supporting Documents</text>
    </g>
    <g class="m-node m-node--rect" id="mdf1272__node__G" data-role="vertex">
      <rect x="1457.09" y="131.55" width="239.51" height="36.9" class="m-shape"/>
      <text x="1576.84" y="150" class="m-label t-label" text-anchor="middle">Browser Cookie Token Generated</text>
    </g>
    <g class="m-node m-node--rect" id="mdf1272__node__H" data-role="vertex">
      <rect x="1756.6" y="131.55" width="220.01" height="36.9" class="m-shape"/>
      <text x="1866.6" y="150" class="m-label t-label" text-anchor="middle">Malware Scan &amp; File Validation</text>
    </g>
    <g class="m-node m-node--cylinder m-s1" id="mdf1272__node__I" data-role="vertex">
      <path d="M 2103.79 97.09 L 2103.79 122.92 A 95.86 5.54 0 0 0 2295.51 122.92 L 2295.51 97.09 Z" class="m-shape"/>
      <ellipse cx="2199.65" cy="97.09" rx="95.86" ry="5.54" class="m-shape"/>
      <text x="2199.65" y="115.54" class="m-label t-label" text-anchor="middle">Stored in Azure File Share</text>
    </g>
    <g class="m-node m-node--rect" id="mdf1272__node__J" data-role="vertex">
      <rect x="2096.61" y="171.55" width="206.09" height="36.9" class="m-shape"/>
      <text x="2199.65" y="190" class="m-label t-label" text-anchor="middle">Display Clear Error Message</text>
    </g>
    <g class="m-node m-node--rect" id="mdf1272__node__K" data-role="vertex">
      <rect x="2362.69" y="91.55" width="236.15" height="36.9" class="m-shape"/>
      <text x="2480.77" y="110" class="m-label t-label" text-anchor="middle">Submit Enquiry via Contact Form</text>
    </g>
    <g class="m-node m-node--rect" id="mdf1272__node__L" data-role="vertex">
      <rect x="2658.84" y="91.55" width="261.69" height="36.9" class="m-shape"/>
      <text x="2789.69" y="110" class="m-label t-label" text-anchor="middle">Admin Notified via Web &amp; Mobile App</text>
    </g>
    <g class="m-node m-node--stadium m-s0" id="mdf1272__node__M" data-role="vertex">
      <rect x="2980.53" y="91.55" width="205.45" height="36.9" rx="18.45" ry="18.45" class="m-shape"/>
      <text x="3083.25" y="110" class="m-label t-label" text-anchor="middle">Bond Consultant Follows Up</text>
    </g>
    <g class="m-edge-label">
      <rect x="413.01" y="73.65" width="26.51" height="22.3" rx="11.15" ry="11.15" class="m-pill-bg"/>
      <text x="426.26" y="84.8" class="m-label t-edge" text-anchor="middle">No</text>
    </g>
    <g class="m-edge-label">
      <rect x="410.66" y="204.05" width="31.21" height="22.3" rx="11.15" ry="11.15" class="m-pill-bg"/>
      <text x="426.26" y="215.2" class="m-label t-edge" text-anchor="middle">Yes</text>
    </g>
    <g class="m-edge-label">
      <rect x="2006.77" y="129.01" width="37.43" height="22.3" rx="11.15" ry="11.15" class="m-pill-bg"/>
      <text x="2025.48" y="140.16" class="m-label t-edge" text-anchor="middle">Valid</text>
    </g>
    <g class="m-edge-label">
      <rect x="1980.61" y="155.16" width="44.98" height="22.3" rx="11.15" ry="11.15" class="m-pill-bg"/>
      <text x="2003.09" y="166.31" class="m-label t-edge" text-anchor="middle">Invalid</text>
    </g>
  </g>
</svg>


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
