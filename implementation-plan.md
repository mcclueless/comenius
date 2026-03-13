# Implementation Plan: "Improv(e) Your Study Start!" Website

**Project:** One-pager promotional website for Comenius Senior Fellow Grant project  
**Client:** Dr. Annika Nübold (FPN, Maastricht University)  
**Deadline:** Mid-March 2026 (before final report submission)  
**Created:** 9 March 2026

---

## 1. Project Overview

A static one-pager website promoting the "Improv(e) Your Study Start!" mobile app—a tool teaching improvisation exercises to build resilience in first-year psychology students. The website serves as documentation for the NRO Comenius Senior Fellow grant and makes project outcomes publicly available.

### Technical Requirements
- **Static site** (HTML/CSS/JS only, no backend)
- **UM house style** compliant
- **Self-hosted** on UM infrastructure (no recurring fees)
- **Responsive** design for mobile/tablet/desktop
- **Minimal dependencies** for long-term maintainability

### Recommended Stack
- HTML5 + CSS3 (vanilla or Tailwind CSS for rapid styling)
- Minimal JavaScript (smooth scrolling, mobile menu)
- No framework needed—simple static pages

---

## 2. UM House Style Guidelines

### Brand Colors
| Color | Hex | Usage |
|-------|-----|-------|
| **UM Dark Blue** | `#003366` (approx.) | Primary text, headers, logo |
| **Orange-Red** | (accent) | CTAs, highlights |
| **Bright Blue** | `#00A2DB` | Secondary accent |
| **White** | `#FFFFFF` | Backgrounds |

### Typography
- Sans-serif fonts (system fonts or UM-approved webfonts)
- Clear hierarchy with bold headers

### Logo Guidelines
- Use official UM logo (two triangles + wordmark)
- Logo preferably in UM dark blue or black
- Minimum width: 30mm equivalent
- White/light background preferred
- Do not separate image brand from word brand

### FPN House Style Contact
For official assets and approval:  
**Thom Frijns** – FPN House Style Coordinator  
📧 thom.frijns@maastrichtuniversity.nl

---

## 3. Page Structure & Content Outline

### Section 1: Hero / Header
**Purpose:** Immediate project identification and app download CTA

**Content:**
- UM logo (header)
- App name: "Improv(e) Your Study Start!"
- Tagline: "Building resilience through improvisation for first-year students"
- App Store / Google Play download buttons
- Hero image: Students engaged in improv exercise OR app screenshots

**Visual Placeholders:**
- [ ] `hero-bg.jpg` - Students in workshop setting (1920×1080)
- [ ] `app-mockup.png` - Phone displaying app UI (800×1600)
- [ ] `app-store-badge.svg` - Apple App Store
- [ ] `play-store-badge.svg` - Google Play Store

---

### Section 2: About the Project
**Purpose:** Explain the "why" and context

**Content:**
```
What is "Improv(e) Your Study Start!"?

Starting university can be overwhelming. Our app uses evidence-based 
improvisation exercises to help first-year psychology students build 
resilience, reduce stress, and develop adaptive thinking skills.

Developed at the Faculty of Psychology and Neuroscience at Maastricht 
University, this project combines psychological research with creative 
practice to support student wellbeing from day one.
```

**Key Points to Include:**
- Target audience: first-year psychology students
- Problem addressed: transition stress, uncertainty, performance anxiety
- Solution: improv-based resilience training via mobile app
- Evidence-based approach

**Visual Placeholders:**
- [ ] `about-illustration.svg` - Abstract illustration of growth/resilience

---

### Section 3: App Features
**Purpose:** Showcase what the app offers

**Content Structure:**
```
How It Works

📱 Daily Exercises
   Short improv exercises you can do anywhere, 
   designed for busy student schedules.

🎯 Personalized Progress
   Track your resilience journey with 
   reflections and stats.

🧠 Science-Based Methods
   Every exercise is grounded in psychological 
   research on stress and adaptation.

🤝 Community Challenges
   Connect with fellow students through 
   shared challenges and experiences.
```

**Visual Placeholders:**
- [ ] Feature icons (4–6 SVG icons)
- [ ] `app-screenshots/` folder with 3–4 app screens

---

### Section 4: The Science / Research
**Purpose:** Establish credibility and academic foundation

**Content:**
```
The Research Behind the App

Improvisation training has been shown to enhance psychological 
flexibility, reduce anxiety, and improve adaptive responses to 
uncertainty—key skills for navigating university life.

Our approach combines:
• Applied improvisation techniques
• Self-regulation and reflection methods
• Micro-learning principles for sustained engagement

[Link to relevant publications or working papers if available]
```

**Visual Placeholders:**
- [ ] `research-diagram.svg` - Methodology visualization
- [ ] Research citations/DOIs (if published)

---

### Section 5: The Team
**Purpose:** Introduce project members and establish expertise

**Team Members:**

| Name | Role | Affiliation |
|------|------|-------------|
| **Dr. Annika Nübold** | Project Lead / Senior Fellow | Associate Professor, Work & Organizational Psychology, FPN |
| **Dr. Eliza de Sousa Fernandes Perna** | Team Member | [Role/Department TBC] |
| **Dr. Alicia Walkowiak** | Team Member | [Role/Department TBC] |
| **Dr. Herco Fonteijn** | Team Member | [Role/Department TBC] |
| **Fabian Brüggemann** | Team Member | [Role/Department TBC] |

**Visual Placeholders:**
- [ ] `team/nubold.jpg` - Professional headshot (400×400)
- [ ] `team/perna.jpg`
- [ ] `team/walkowiak.jpg`
- [ ] `team/fonteijn.jpg`
- [ ] `team/bruggemann.jpg`

**Note:** Request photos and brief bios from Dr. Nübold

---

### Section 6: Resources / For Developers
**Purpose:** Fulfill Comenius requirement for public availability of materials

**Content:**
```
Open Resources

In line with Comenius program principles, we share our project 
materials with the academic community.

📂 For Researchers & Educators
   [Link to methodology documentation / research outputs]

💻 For Developers
   Interested in the technical implementation? 
   Contact us for access to technical documentation.

   Contact: a.nubold@maastrichtuniversity.nl
```

**Notes:**
- Clarify with Annika: What can be shared? (Code on GitLab? Contentful exports?)
- May need to host code separately or provide on request

---

### Section 7: Funding & Attribution
**Purpose:** Proper acknowledgment of NRO Comenius grant (REQUIRED)

**Content:**
```
Funding

This project was made possible by a Comenius Senior Fellow grant 
from the Dutch Research Council (NWO), administered through the 
Nationaal Regieorgaan Onderwijsonderzoek (NRO).

The Comenius program supports innovative educational projects in 
Dutch higher education.
```

**Required Elements:**
- [ ] NRO logo (official version from NRO/NWO)
- [ ] NWO logo (if required by grant terms)
- [ ] Grant reference/project number (obtain from Dr. Nübold)
- [ ] Link to Comenius program: https://www.nro.nl/en/researchprogrammes/comenius-programme

**⚠️ ACTION REQUIRED:** 
Verify exact attribution requirements with grant documentation. NRO typically requires:
1. NRO logo displayed
2. Text acknowledgment
3. Optional: Project number citation

---

### Section 8: Footer
**Content:**
- UM logo
- FPN (Faculty of Psychology and Neuroscience) mention
- Contact email: a.nubold@maastrichtuniversity.nl
- © 2026 Maastricht University
- Privacy statement link (UM standard)
- Links: NRO | ComeniusNetwerk | FPN

---

## 4. Technical Implementation

### File Structure
```
comenius-website/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── main.js (minimal: smooth scroll, mobile menu)
├── images/
│   ├── um-logo.svg
│   ├── nro-logo.svg
│   ├── hero-bg.jpg
│   ├── app-mockup.png
│   ├── icons/
│   └── team/
├── docs/
│   └── (any downloadable resources)
└── README.md
```

### Hosting Options (UM Infrastructure)
1. **FPN web space** – Check with FPN IT
2. **UM-hosted GitLab Pages** – If available
3. **Static hosting via UM IT** – Coordinate with Bernd

### Accessibility Requirements
- WCAG 2.1 AA compliance
- Alt text for all images
- Keyboard navigation
- Sufficient color contrast

---

## 5. Assets Needed

### From Client (Dr. Nübold)
- [ ] Team member photos (professional headshots)
- [ ] Team member bios (1-2 sentences each)
- [ ] App screenshots (3–4 key screens)
- [ ] App Store / Play Store links
- [ ] Grant project number for attribution
- [ ] Any research publications to cite
- [ ] Clarification on open-source code sharing

### From UM/FPN
- [ ] Official UM logo files (SVG preferred)
- [ ] FPN logo if needed
- [ ] House style asset kit (request from Thom Frijns)

### From NRO
- [ ] Official NRO logo for grantees
- [ ] NWO logo if required
- [ ] Attribution text requirements

### To Create
- [ ] Hero background image (stock or commissioned)
- [ ] Feature icons (can use icon library)
- [ ] App mockup frame (device frame for screenshots)
- [ ] Placeholder graphics

---

## 6. Timeline

| Phase | Tasks | Deadline |
|-------|-------|----------|
| **Week 1** | Content collection, asset gathering | 10–14 Mar |
| **Week 2** | Design & development | 14–18 Mar |
| **Review** | Client feedback | 18–19 Mar |
| **Launch** | Deploy & test | 19–20 Mar |

**Buffer:** 2-3 days before mid-March deadline

---

## 7. Open Questions for Client

1. **App Store Links:** Are the apps live? What are the download URLs?
2. **Code Sharing:** What technical materials can be made public? GitLab access? Contentful exports?
3. **Team Details:** Can you provide photos and short bios for all team members?
4. **Research Outputs:** Any publications or working papers to reference?
5. **Grant Number:** What is the NRO project reference number?
6. **Domain:** Will this be hosted at a specific UM subdomain?

---

## 8. Development Notes

### Keep It Simple
Per Bernd's instructions:
- No backend required
- No advanced frontend frameworks
- Static HTML/CSS/JS is sufficient
- Goal: demonstrate project completion to funders

### Content Editability
Annika asked about making text changes herself:
- Option A: Provide HTML with clear comments for text sections
- Option B: Use a simple static site generator (11ty, Hugo) with Markdown content
- Option C: Train on direct HTML editing

Recommended: **Option A** for this scope—clean HTML with documented sections.

---

## 9. Next Steps

1. ✅ Implementation plan created
2. ⏳ Send questions to Dr. Nübold
3. ⏳ Request assets from FPN house style coordinator
4. ⏳ Obtain NRO attribution requirements
5. ⏳ Begin HTML/CSS development once content received

---

*Document prepared by Digital Innovation Team, Marketing & Communication, Maastricht University*
