# first-milestone-project
 ---

 ## Table of Contents

 1. Project Overview
 2. Goals and User Needs
 3. User Stories
 4. Information Architecture
 5. Content Strategy
 6. Design Decisions
 7. Wireframes 
 8. Responsiveness and Accessibility 
 9. Technologies Used
 10. Bugs and Fixes
 11. Testing 
 12. Future Improvements and Additional Features
 13. Credits and Disclaimer

---

## 1. Project Overview

This project is a responsive mobile-first website designed for an english-speaking full spectrum doula in Berlin, named Evita Varela.
The website aims to provide clear information about services, build trust through storytelling and testimonials, and make it easy for users to get in touch.
The business goal is to increase the doulas clientbase.

The project was created as part of a coding sourse at Code Institute and focuses on thoughful UX decisions, accessibility, and clean front end implementation.

---

## 2. Goals and User Needs

The primary goals of the project are:
- To present the information clearly and calmly, especially for users navigating pregnancy, birth and postpartum recovery or fertility challenges
- To ensure users can easily find key information on mobile devices
- To create an emotionally suportive and trustworthy visual tone
- To provide a simple and accessible way to contact the doula

The target users are pregnant women, partners, and individuals experiencing fertility challenges who are seeking support in English in Berlin.

---

## 3. User Stories

The following user stories were used to guide the design:

### User Story 1: Understanding the Service
   
As a pregnant or trying-to-conceive person in Berlin, I want to quickly understand what a full-spectrum doula offers, so I can decide if this support fits my needs.

#### Acceptance Criteria
- Homepage clearly states “Full-Spectrum Doula in Berlin”
- Services summarized above the fold
- Simple, non-medical language used in the text
- No more than 2 clicks to the detailed service pages

#### Tasks
- Write a clear homepage headline: “English-Speaking Full-Spectrum Doula in Berlin”
- Draft a 1–2 sentence subheadline explaining what full-spectrum doula care is
- Design an above-the-fold hero section with headline, subheadline, and primary CTA
- Create a short “What I Offer” summary section (max 80–100 words)
- Ensure links from homepage to service details are reachable in max 2 clicks
- Test homepage comprehension with a 5-second test (can the user explain services?)

### User Story 2: English-Speaking & Expat Focus

As an English-speaking expat, I want the site to feel designed for internationals, so I feel supported navigating pregnancy in Germany.

#### Acceptance Criteria
- Website fully in English
- References to Berlin/German healthcare context
- Inclusive language (non-gendered where appropriate)
- Avoid assumptions about nationality or family structure

#### Tasks
- Set site language to English only (no mixed-language parts)
- Control final text for assumptions about nationality, gender, or family structure
- Replace gendered terms with inclusive language where appropriate
- Add subtle references to Berlin/German healthcare context in the text
- Review tone for warmth, clarity, and cultural neutrality
- Validate the text with an “international audience” lens (no local jargon)

### User Story 3: Clear Service Breakdown

As a client at a specific pregnancy stage, I want services clearly separated by prenatal, birth, and postpartum care, so I can easily find what applies to me.

#### Acceptance Criteria
- Dedicated page or section per service
- Each includes: what’s included, duration, emotional benefits
- Gentle call-to-action per service

#### Tasks
- Define four service categories: Prenatal Care, Birth Support, Postpartum Care, Fertility & Emotional Support
- Create a Services landing page with short intros for each category
- Design individual service sections or subpages
- For each service, write: What’s included, Emotional/experiential benefits, Who it’s for
- Add a gentle, service-specific CTA to each section
- Check that users can identify their relevant service within 10 seconds

### User Story 4: Fertility & Emotional Support

As someone experiencing fertility struggles or loss, I want counseling services presented with sensitivity, so I feel safe exploring this option.

#### Acceptance Criteria
- Separate, discreet section/page
- Soft visual design (no triggering imagery)
- Language validated by trauma-informed principles
- No pricing shown upfront (optional inquiry instead)

#### Tasks
- Create a separate Fertility & Emotional Support section/page
- Write a trauma-informed, non-salesy text (avoid urgency or pressure)
- Review language for potential triggers and revise accordingly
- Select soft, neutral visuals (no pregnancy/baby imagery)
- Remove or avoid upfront pricing on this service
- Add a low-pressure CTA (e.g. “Reach out when you’re ready”)

### User Story 5: Healthcare System Context

As someone unfamiliar with German maternity care, I want to understand how doula support works alongside doctors and midwives, so I feel confident choosing this service.

#### Acceptance Criteria
- Explanation of doula vs. midwife vs. doctor
- Mentions hospitals, home births, birth centers in Berlin
- Reassures collaboration (not replacement)

#### Tasks
- Write a short explanation of how doula support fits alongside: Midwives, Doctors, Hospitals
- Integrate this content into: Home page (brief reassurance), Birth Support service section
- Add bullet points clarifying what a doula does and does not do
- Ensure that the text emphasizes collaboration, not replacement

### User Story 6: Trust & Personal Connection

As a pregnant woman, I want to learn about the doula’s philosophy and background, so I can feel trust before making contact.

#### Acceptance Criteria
- “About” page with photo and personal tone
- Philosophy/values clearly stated
- Mentions training, experience, and approach

#### Tasks
- Design an About page with a prominent personal photo
- Write first-person introduction text with a warm, professional tone
- Add a section outlining philosophy and values
- Document training, experience, and certifications
- Avoid overly long biography; keep it human and approachable
- Add a soft CTA at the end (“Let’s talk”, “Get in touch”)

### User Story 7: Gentle Contact Experience

As a ready-to-reach-out client, I want an easy, calming way to make contact, so reaching out doesn’t feel stressful.

#### Acceptance Criteria
- Simple contact form (3–5 fields max)
- Clear next steps explained
- Option for free intro call
- Warm confirmation message after submission

#### Tasks
- Design a contact page with calming intro text
- Create a contact form with max 3–5 fields: Name, Email, Stage (optional), Message
- Design a warm confirmation message after submission
- Test form completion on mobile for ease and emotional load

### User Story 8: Easy and quick access to information on mobile
 
As a pregnant person browsing the website on my mobile phone, I want to quickly find the information I'm looking for, using a clear and simple navigation, so that I feel supported and not overwhelmed while exploring the doula's services.

#### Acceptance Criteria
- The navigation visible and intuitive to use
- The website is fully responsive across different screen sizes
- The layout is clear and cohesive

#### Tasks
- Apply responsive design principles using Bootstrap to make sure the website is responsive across devices
- Arrange the layout based on best practices ensuring all sections and pages are quickly and easily accessible
- Create a responsive navbar where the menu items collapse into a hamburger menu on smaller screens and the navigation remains usable when the page is scrolled

---

## 4. Information Architecture

The website uses a simple and clear structure with the following pages:
- Home
- About Me
- Services
- Contact

The information architecrture of the website was designed to prioritize clarity, emotional safety, and ease of navigation, especially for mobile users. Content is organised into a small number of clearly labelled pages to reduce cognitive load and help users quickly find the information most relevant to their needs.
The main navigation includes Home, About Me, Services and contact. Services-related information is grouped into four main categories that correspond to the service cards on the home page. This consistency allows users to form a clear and mental model as they move between the pages.
Long-form personal content, such as the doula's story and background, is placed on the About Me page and presented in a linear layout to support comfotrable reading. Credentials, languages, and testimonials are positioned after the personal narrative to reinforce trust without interrupting the emotional flow.
The contact page was designed with a simple primary goal: to enable the user to easily get in touch. On larger screens, additional text was used to balance the layout, while keeping the form as the main focus.
All pages are accessible from the main navigation on all screen sizes.
The footer was intentionally kept minimal, containing only social media links, to avoid distractions and keep the focus on the primary user journey.

---

## 5. Content Strategy

Due to the nature of doula work, content plays an integral role in this website. The written content is rich and was designed to create a sense of safety, trust, and emotional support, while remaining clear and informative. 
A calm, empathetic, and non-judgemental tone was chosen to reflect the sensitive topics of pregnancy, birth, postpartum care, and fertility challenges. Language was kept accessible, warm and human, intentionally avoiding overly clinical or promotional wording.
Content was prioritised based on user needs, with sensitive information presented clearly and personal storytelling used to build connection and credibility.
Testimonials and credentials were included selectively to reinforce trust without overwhelming the user.
Pages such as "Giving Birth in Berlin" were intntionally excluded to keep the site focused on the doula's services and personal approach rather than general information content. It was determined that such information, along with practical details about the collaboration and navigating the german healthcare system would be better and more concisely presented as part of a FAQs section, that could be incorporated to the website in the future.

---

## 6. Design Decisions

### Color palette

The color palette was chosen to evoke calm, warmth, and trust. Soft, neutural tones are combined with muted accents to support emotional safety.
Key colors include:
- Neutral tones for readability
- Warm pinks for emphasis and headings
- Soft green for balance and calm

### Typography

Two fonts were selected:
-  Merriweather for headings to convey warmth and trust
-  Source Sans 3 for body text to ensure readability across devices


### Imagery

Black and white images are used for service related sections to maintain consistency and calmness.
Color images are reserved exclusively for the doula herself to create a personal connection and convey warmth and joy.

---

## 7. Wireframes

Low-fidelity wireframes were created to define layout, content hierarchy, and user flow before development. They follow a mobile-first approach and demonstrate how the sections adapt across different screen sizes.

---

## 8. Responsiveness and Accessibility

The website was designed using a mobile-first approach which was developed with Bootstrap 5.

Accessibility considerations include:
- Clear navigation
- Readable font sizes
- Sufficient color contrast
- Visible form labels
- Distintive buttons and links

---

## 9. Technologies Used

The following technologies were used for the development of the website:
- HTML
- CSS
- Bootstrap5
- tldraw

---

## 10. Bugs and Fixes

---

## 11. Testing

---

## 12. Future Improvements and Additional Features

---

## 13. Credits and Disclaimer


















