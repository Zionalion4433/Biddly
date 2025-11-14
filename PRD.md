Here is a clean, investor-ready **PRD (Product Requirements Document)** for your AI-powered construction marketplace app.
This version is written in a polished, YC- and VC-friendly format that you can use for pitch decks, engineering scoping, or sending to a product team.

---

# **PRODUCT REQUIREMENTS DOCUMENT (PRD)**

### **Product Name: NailiT Scope™ (working title)**

### **Version 1.0**

---

# **1. Product Overview**

**NailiT Scope™** is an AI-powered marketplace platform designed to help home and business owners correctly scope their construction projects, set realistic budgets, and hire the right contractors with confidence.

The platform integrates construction industry expertise, AI-driven analysis, and marketplace functionality to:

* **Reduce the risk of homeowners hiring underqualified or unskilled contractors.**
* **Save contractors time by filtering out low-budget and unqualified leads.**
* **Provide clear, educational guidance to customers before they request quotes.**

By blending AI project scoping with transparent contractor bidding and skill-matching, NailiT Scope™ creates a more efficient, safe, and informed renovation ecosystem for both sides.

---

# **2. Problem Statement**

1. Homeowners often don’t understand construction terminology, realistic pricing, or which skills are required for their project.
2. Contractors lose time performing on-site quotes for customers with unrealistic budgets or unclear expectations.
3. Customers frequently hire the wrong contractors due to:

   * Not knowing what questions to ask
   * Not understanding necessary skill sets
   * Lack of proper scoping or budgeting
4. No existing platform provides **AI-powered scope analysis** + **budget realism scoring** + **contractor marketplace** in one flow.

---

# **3. Target Users**

### **Primary Users**

* **Homeowners & Business Owners**

  * Need education, realistic pricing expectations, and vetted contractors.

### **Secondary Users**

* **Licensed Contractors & Skilled Tradespeople**

  * Want pre-qualified, high-quality job leads
  * Want to showcase their skills and past work
  * Want to avoid unpaid or unproductive quote visits

---

# **4. Core Product Goals**

### For Homeowners:

* Understand what their project actually requires
* Receive a **general scope of work (GSOW)** breakdown using AI
* Upload photos/videos for better analysis
* Input a budget and receive a **Budget Realism Score** (Low → Medium → High likelihood of attracting skilled contractors)
* Receive recommended questions to ask contractors
* Match with qualified contractors and post jobs for bids

### For Contractors:

* Get pre-qualified leads with realistic budgets
* Showcase expertise through photos, videos, licenses, skills, and specializations
* Bid on jobs directly
* Avoid time-wasting site visits for underfunded projects

---

# **5. Key Features**

## **5.1 AI Project Analyzer**

**Inputs:**

* Homeowner description
* Photo/video uploads
* Budget
* Location & timeline
* Type of property (home vs commercial)

**Outputs:**

* General Scope of Work (GSOW)
* Expected price range based on local & national market data
* Skillsets required (e.g., framing, electrical, drywall, plumbing)
* Time estimate
* List of materials typically required
* Red flags (structural, code-related, moisture, etc.)
* A set of **smart questions** the homeowner should ask each contractor

---

## **5.2 Budget Realism Score**

A 5-level readiness meter:

1. **Very Unlikely** (Budget is far too low; skilled contractors unlikely)
2. **Unlikely**
3. **Possible**
4. **Likely**
5. **Highly Likely** (Budget matches or exceeds market rate)

Includes triggered alerts like:

> “Based on similar projects in your region, your budget of $2,000 has a **Low Likelihood** of attracting a skilled contractor. Typical scope ranges $6,500–$8,000.”

This stops homeowners from wasting contractors’ time and encourages transparency.

---

## **5.3 Marketplace & Bidding System**

* Homeowners can post jobs based on their AI-generated scope
* Contractors receive notifications and can bid
* Homeowners can:

  * Compare bids
  * View contractor portfolios
  * View licenses, insurance, years of experience
  * View reviews & skill badges
* In-app messaging

---

## **5.4 Contractor Profiles (Thumbtack-style gallery)**

Contractors can upload:

* Photos of completed work
* Videos (before/after)
* Licenses & certifications
* Specialities (roofing, framing, tile, painting, etc.)
* Service area
* Minimum job size preference
* Starting hourly rate (optional)

---

## **5.5 Contractor Filters**

Homeowners can filter by:

* Skillset
* License type
* Minimum job size
* Years of experience
* Availability
* Distance

---

## **5.6 Customer Education Center**

Mini-modules explaining:

* “What does a real contractor quote include?”
* “Why skilled trades cost more”
* “How to avoid low-quality work”
* “How to prep your home for a quote visit”
* “Why budgets matter”

This educates homeowners before entering the marketplace.

---

# **6. User Flows**

## **6.1 Homeowner Flow**

1. Download or open app
2. Select “Analyze My Project”
3. Upload photos/video
4. Enter description and budget
5. AI generates project scope + estimated cost
6. Budget Realism Score appears
7. User selects “Find Contractors”
8. Contractors bid OR homeowner sends invites
9. User asks questions provided by AI
10. Messaging + hire contractor

---

## **6.2 Contractor Flow**

1. Create profile
2. Upload photos, videos, work history
3. Set minimum job size
4. Receive filtered leads
5. View AI-generated homeowner scope
6. Decide whether to bid
7. Submit bid and message homeowner

---

# **7. Technical Requirements**

### **AI Components**

* Vision model (for analyzing photos of construction problems)
* LLM for scope creation
* Budget estimation model (training on regional construction cost databases)
* Predictive model for contractor engagement likelihood

### **Backend**

* Secure photo/video storage
* Scalable bidding system
* Contractor verification services (ID, license lookup)
* Messaging system
* Review & rating engine

### **Frontend**

* Mobile-first web app + native apps
* Simple image uploader
* Dashboard for bids and comparisons
* Contractor portfolio pages

### **Integrations**

* Google Maps API
* Licensing look-up API (optional)
* Stripe for payments (future version for deposits or subscriptions)

---

# **8. Success Metrics (KPIs)**

### Homeowner-side:

* % of homeowners who complete AI project scope
* % of homeowners whose Budget Score improves over time
* Cost estimate accuracy vs real contractor bids

### Contractor-side:

* Reduction in wasted site visits
* Bid-to-job conversion rate
* Quality lead satisfaction score

### Marketplace:

* # of successful matches
* Time-to-first-bid
* Active contractors per region
* Subscription revenue (contractor premium profiles)

---

# **9. Monetization Model**

### **Phase 1 (MVP):**

* Free for homeowners
* Contractors pay subscription to receive higher-quality leads

### **Phase 2:**

* Marketplace fee per job
* Featured contractor placements
* AI-powered premium scopes for homeowners
* Contractor CRM & scheduling tools

---

# **10. Risks & Mitigations**

| Risk                                         | Mitigation                                     |
| -------------------------------------------- | ---------------------------------------------- |
| AI scopes being inaccurate                   | Human-in-the-loop validation for complex jobs  |
| Contractors avoiding platform                | Early adopter incentives + lead guarantees     |
| Homeowners still posting unrealistic budgets | Budget Score + education center                |
| Disputes over pricing or workmanship         | Clear disclaimers + mediation options (future) |

---

# **11. MVP Scope (What will launch first)**

**Included:**

* Project analyzer (text + photos)
* Budget Realism Score
* Contractor profiles
* Job posting + bidding
* Homeowner questions generator
* Messaging

**Not included in MVP:**

* Payments
* Contractor license verification API
* In-app contracts
* AI video analysis (later phase)

---

# **12. Future Features (V2-V5)**

* AI-generated 3D models/visuals of the project
* Permit requirement checker
* In-app scheduling + invoicing
* Fraud prevention & background checks
* Marketplace payments + escrow
* Skill-matching algorithm for contractors

---
