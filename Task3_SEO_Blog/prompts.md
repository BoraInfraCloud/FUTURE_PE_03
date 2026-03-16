# 📋 Task 3 — SEO Blog & Content Cluster Prompt System
## AI SEO Blog & Content Cluster Generator for Business Websites
**Intern:** Bora Karthik | **CIN:** FIT/MAR26/PE2027 | **Track:** Prompt Engineering (PE)
**Repository:** FUTURE_PE_03 | **Tool Used:** Claude AI
**Business:** HealthFirst Clinic — Multi-Specialty Outpatient Clinic, Vijayawada

---

## 🧠 Prompt Architecture: SILO-X Framework

All SEO prompts follow the **SILO-X Framework** — a professional SEO content engineering structure used at top digital marketing agencies:

| Layer | What It Does |
|-------|-------------|
| **S** — Seed Keyword | Defines the primary keyword with search intent before any content is written |
| **I** — Intent Mapping | Maps user intent (informational / navigational / transactional / local) |
| **L** — Long-form Structure | Engineers H1–H3 hierarchy for maximum crawlability and readability |
| **O** — Optimisation Rules | Sets keyword density, LSI terms, meta data, and internal linking rules |
| **X** — eXecution Format | Specifies word count, tone, CTA placement, and content cluster connections |

**Why content clusters?** Google ranks topic authority, not just individual pages. A content cluster links one pillar page to multiple supporting blog posts — building topical authority that drives consistent organic traffic for the business.

---

## 🔷 PROMPT 1 — System Context Prompt
> **Purpose:** Run FIRST. Sets the expert SEO content strategist persona with MNC-grade operating rules.

```
You are SEOContent-Pro, a senior SEO content strategist and medical
content writer with 12+ years of experience creating search-ranking
blog content for healthcare businesses across India.

You have built SEO content clusters for Apollo Hospitals, Practo,
and 1mg that rank on Google Page 1 for high-intent medical keywords.

OPERATING RULES:
1. Every blog post must target ONE primary keyword — never two.
2. Primary keyword must appear in: H1, first 100 words, one H2,
   meta title, meta description, and conclusion.
3. Use LSI (Latent Semantic Indexing) keywords naturally throughout —
   never force them.
4. Readability standard: Class 8 level. Short sentences. No jargon.
   If a patient would not understand it, rewrite it.
5. Every blog post must have: Hook intro, H1-H3 structure, FAQ section
   (minimum 4 questions), meta title, meta description, and CTA.
6. Forbidden: keyword stuffing, thin content under 800 words,
   medical claims without context, fear-based language.
7. Local SEO rule: Mention "Vijayawada" naturally 3-5 times per post.
8. Every post must end with an internal link suggestion and CTA
   pointing to the HealthFirst Clinic appointment booking page.
9. Content cluster rule: Each supporting post must link back to the
   pillar page AND to one other supporting post.
```

---

## 🟢 PROMPT 2 — Business & SEO Brief
> **Purpose:** Passed after system prompt. Defines the business, target keywords, and content goals.

```
BUSINESS PROFILE:
  Name            : HealthFirst Clinic
  Type            : Multi-Specialty Outpatient Clinic
  Location        : Vijayawada, Andhra Pradesh, India
  Target Patients : Families, working professionals, seniors (ages 25-65)
  Website Goal    : Rank on Google Page 1 for local healthcare searches
  Conversion Goal : Drive appointment bookings from organic search traffic

PRIMARY SEO TARGET:
  Pillar Keyword  : "best clinic in Vijayawada"
  Search Intent   : Transactional + Local (patient ready to book)
  Monthly Volume  : High — competitive local healthcare keyword

CONTENT CLUSTER KEYWORDS (Supporting Posts):
  Post 1: "when to see a general physician Vijayawada"
  Post 2: "heart health tips Vijayawada cardiologist"
  Post 3: "child vaccination schedule India 2024"
  Post 4: "knee pain treatment Vijayawada orthopedic"

BRAND VOICE FOR BLOG:
  Tone      : Helpful, trustworthy, educational — like a knowledgeable friend
  Language  : Simple English, no medical jargon, patient-first perspective
  Avoid     : Scare tactics, disease-heavy language, promotional over-sell

INTERNAL LINKING STRATEGY:
  All 4 supporting posts → link to Pillar Page (best clinic Vijayawada)
  Post 1 ↔ Post 2 (related: general health + heart health)
  Post 3 ↔ Post 4 (related: child care + bone/joint care)
```

---

## 🔵 PROMPT 3 — Pillar Page Blog Prompt
> **Purpose:** Generates the main pillar page — the cornerstone SEO content that all supporting posts link back to.

```
ROLE + CONTEXT: [System Prompt + Business Brief loaded above]

TASK — Generate a complete Pillar Page blog post:

  PRIMARY KEYWORD: "best clinic in Vijayawada"
  TARGET WORD COUNT: 1200-1500 words
  SEARCH INTENT: Transactional + Local
  GOAL: Rank on Google Page 1, convert readers to appointment bookings

  REQUIRED STRUCTURE:

  [META DATA]
    - Meta Title: 55-60 characters, include keyword + city
    - Meta Description: 150-160 characters, include keyword + CTA
    - URL Slug: short, keyword-rich

  [BLOG STRUCTURE]
    H1: Include primary keyword naturally (not forced)
    
    INTRO (100-150 words):
    - Hook: Start with a patient scenario or surprising stat
    - Include primary keyword in first 100 words
    - Preview what the post covers
    
    H2: Why Choosing the Right Clinic Matters in Vijayawada
    - 150-200 words
    - Include 2-3 LSI keywords naturally
    
    H2: What to Look for in a Multi-Specialty Clinic
    - 150-200 words
    - Subtopics as H3s: Qualified Specialists, Same-Day Appointments,
      Transparent Pricing, In-House Diagnostics
    
    H2: Why HealthFirst Clinic Stands Out in Vijayawada
    - 150-200 words
    - Highlight USPs naturally (not like an advertisement)
    - Mention 15+ doctors, 10,000+ patients, since 2015
    
    H2: Specialties Available at HealthFirst Clinic
    - List all 6 departments with 1-sentence descriptions
    - Each with H3 subheading
    
    H2: What Patients Say (Social Proof Section)
    - 2-3 fictional but realistic patient testimonials
    - Include names, brief situation, outcome
    
    FAQ SECTION (H2: Frequently Asked Questions)
    - Minimum 5 FAQs targeting voice search and featured snippets
    - Format: Question as H3, Answer in 40-60 words
    
    CONCLUSION (80-100 words):
    - Summarise key points
    - Include primary keyword once
    - Strong CTA to book appointment

  [INTERNAL LINKING]
    - Suggest 4 internal links to supporting posts
    - Show anchor text for each

  [SEO CHECKLIST]
    After the post, show a checklist confirming:
    ✓ Keyword in H1, first 100 words, meta title, meta description
    ✓ Word count target met
    ✓ FAQ section included
    ✓ Local SEO (Vijayawada mentioned 3-5 times)
    ✓ CTA included
```

---

## 🟡 PROMPT 4 — Supporting Blog Posts Prompt
> **Purpose:** Generates all 4 supporting cluster posts that link back to the pillar page.

```
ROLE + CONTEXT: [System Prompt + Business Brief loaded above]

TASK — Generate 4 supporting blog posts for the content cluster.
Each post targets a different keyword and links back to the pillar page.

[POST 1] "When to See a General Physician in Vijayawada"
  Word Count : 800-1000 words
  Intent     : Informational (patient unsure if they need a doctor)
  Structure  :
    - Meta title + meta description
    - H1 with keyword
    - Intro: relatable scenario (ignoring symptoms)
    - H2: 7 Signs You Should See a Doctor Soon (H3 for each sign)
    - H2: Why Regular Check-ups Matter
    - H2: General Physician at HealthFirst Clinic, Vijayawada
    - FAQ: 4 questions
    - CTA + internal link to pillar page
    - Internal link to Post 2 (heart health)

[POST 2] "Heart Health Tips: When to See a Cardiologist in Vijayawada"
  Word Count : 900-1100 words
  Intent     : Informational + Local
  Structure  :
    - Meta title + meta description
    - H1 with keyword
    - Intro: heart disease stats in India (non-scary)
    - H2: 8 Warning Signs Your Heart Needs Attention (H3 each)
    - H2: Simple Daily Habits for a Healthy Heart
    - H2: Cardiology Services at HealthFirst Clinic, Vijayawada
    - FAQ: 4 questions
    - CTA + internal link to pillar page
    - Internal link to Post 1 (general physician)

[POST 3] "Child Vaccination Schedule in India 2024: A Parent's Guide"
  Word Count : 900-1100 words
  Intent     : Informational (parent researching child health)
  Structure  :
    - Meta title + meta description
    - H1 with keyword
    - Intro: why vaccination timing matters
    - H2: Complete Vaccination Schedule Birth to 5 Years (table format)
    - H2: Vaccines for School-Age Children (5-12 years)
    - H2: Where to Get Child Vaccinations in Vijayawada
    - FAQ: 4 questions about vaccines
    - CTA + internal link to pillar page
    - Internal link to Post 4 (orthopedics/child bone health)

[POST 4] "Knee Pain Treatment in Vijayawada: When to See an Orthopedic"
  Word Count : 900-1100 words
  Intent     : Informational + Local (patient with knee pain)
  Structure  :
    - Meta title + meta description
    - H1 with keyword
    - Intro: relatable scenario (knee pain affecting daily life)
    - H2: Common Causes of Knee Pain
    - H2: 6 Signs Your Knee Pain Needs Medical Attention (H3 each)
    - H2: Treatment Options — From Physio to Surgery
    - H2: Orthopedic Care at HealthFirst Clinic, Vijayawada
    - FAQ: 4 questions
    - CTA + internal link to pillar page
    - Internal link to Post 3 (child health)

FORMAT FOR ALL POSTS:
  - Show meta title + meta description first
  - Full H1-H3 structured blog post
  - FAQ section clearly labelled
  - Internal link suggestions with anchor text at the end
  - SEO checklist at the end of each post
```

---

## 🔴 PROMPT 5 — Content Cluster Map + Local SEO Prompt
> **Purpose:** Generates the complete content cluster map and local SEO optimisation checklist.

```
ROLE + CONTEXT: [System Prompt + Business Brief loaded above]

TASK — Generate two deliverables:

[DELIVERABLE 1] CONTENT CLUSTER MAP
  Create a visual text-based map showing:
  - Pillar Page at the centre
  - 4 Supporting Posts connected to it
  - Internal linking arrows between related posts
  - Primary keyword for each piece of content
  - Estimated monthly search volume category (High/Medium/Low)
  - Content type (Pillar / Supporting)
  Format as a clear ASCII diagram.

[DELIVERABLE 2] LOCAL SEO OPTIMISATION CHECKLIST
  Generate a 15-point local SEO checklist for HealthFirst Clinic:
  
  Cover these areas:
  - Google Business Profile optimisation (5 points)
  - On-page local SEO for blog content (5 points)
  - Local link building opportunities (3 points)
  - Schema markup recommendations (2 points)
  
  For each point provide:
  - What to do (action)
  - Why it matters (1 sentence)
  - Priority: High / Medium / Low

[DELIVERABLE 3] META DATA SUMMARY TABLE
  Create a table showing all 5 pieces of content:
  Columns: Post Title | Primary Keyword | Meta Title | 
           Meta Description | Target Word Count | Internal Links To
```

---

## ✅ BONUS: Content QA Prompt
> **Purpose:** Quality check all blog posts before publishing. Professional 10-point SEO and content audit.

```
TASK: Review all blog posts against these 10 SEO and content criteria.
Score each 1-10. Flag anything below 7 for revision.

QA CHECKLIST:
  [Q1]  Keyword placement: In H1, first 100 words, meta title, meta desc?
  [Q2]  Readability: Grade 8 level? Short sentences? No jargon?
  [Q3]  Word count: Meets minimum target for each post?
  [Q4]  Local SEO: Vijayawada mentioned naturally 3-5 times?
  [Q5]  FAQ section: Minimum 4 questions? Targets voice search?
  [Q6]  Internal linking: Links to pillar page + one other post?
  [Q7]  CTA: Clear appointment booking CTA at the end?
  [Q8]  Content value: Does this genuinely help the reader?
  [Q9]  Duplicate risk: Is this content unique, not generic?
  [Q10] E-E-A-T signals: Does content show Experience, Expertise,
        Authoritativeness, Trustworthiness?

OUTPUT: Score table + Overall Grade + Priority fixes
```

---

*Intern: Bora Karthik | CIN: FIT/MAR26/PE2027 | Future Interns PE Track*
