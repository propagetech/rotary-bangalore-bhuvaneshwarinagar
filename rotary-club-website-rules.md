# Rotary Club Website Rules

> **Purpose:** This document is a build, content, design, review, and governance standard for the official website of **Rotary Club of Bangalore Bhuvaneshwarinagar** (replace the name only after the club confirms its exact official name).
>
> **Status:** Working implementation guide. It must be reviewed and approved by the Club President, Club Secretary, and the relevant District Public Image / Brand lead before launch.
>
> **Important:** This guide supports Rotary brand compliance but does not replace current guidance in the Rotary Brand Center, Rotary Code of Policies, trademark rules, local law, or district instructions. When they conflict, the current official Rotary guidance prevails.

---

## 1. Core operating rule

The website must clearly represent one specific local Rotary club. It must never imply that it is the official website of Rotary International, Rotary India, all Rotary clubs in Bengaluru, or a Rotary district unless the club has written authority to make that representation.

**Approved identity pattern**

- `Rotary Club of Bangalore Bhuvaneshwarinagar`
- `A local Rotary club serving Bengaluru, Karnataka, India`

**Not approved without written authority**

- `Rotary Bangalore`
- `Rotary Bengaluru`
- `Rotary India`
- `Official Rotary Bangalore Website`
- Any wording that implies citywide, statewide, national, district, or Rotary International representation.

The club must keep an internal record of:

- The exact official/chartered club name
- Club district number and district website
- Club board approval for the website
- Domain registrant/owner and renewal date
- At least two club-office-holder administrator accounts
- Hosting, DNS, email, analytics, form, and payment-system access owners
- The named person responsible for content review and updates

---

## 2. Domain and ownership rules

### 2.1 Domain name

The domain must identify the specific club. Do not use `Rotary` alone or in a generic name.

**Preferred patterns**

- `rotaryclubofbengalurubhuvaneshwarinagar.org`
- `rotaryclub-bhuvaneshwarinagar.org`
- `rcbhuvaneshwarinagar.org` — only if the abbreviation is approved and the full club name is prominent on the site

**Avoid**

- `rotarybangalore.org`
- `rotarybengaluru.org`
- `rotaryindia.org`
- `rotaryservice.org`
- `rotaryimpact.org`
- Domains that omit the club/district/zone identifier or could mislead visitors about organisational authority

`.org` is preferred for the public club site. A defensive `.in` registration may be useful, but it should redirect to the canonical domain.

### 2.2 Account ownership

- The domain registrar account must be controlled by the club, not solely by a developer, vendor, current president, or individual member.
- Enable MFA on the domain registrar, hosting, CMS, email, and payment accounts.
- Give administrator access to at least two approved club office holders.
- Use a club-owned email address for accounts where possible.
- Document renewal dates, vendor credentials, backups, and recovery contacts in a secure club-owned record.
- Renew the domain for multiple years where practical and enable auto-renewal.
- The web vendor must hand over all source files, CMS credentials, design assets, analytics access, and backups when their engagement ends.

---

## 3. Logo and trademark rules

### 3.1 Official logo only

- Use the official club logo generated or obtained through the **Rotary Brand Center**.
- The logo must identify the specific club, district, zone, or other authorised Rotary entity.
- Use the complete approved Rotary Masterbrand Signature and club identifier as supplied; do not reconstruct it manually.
- Keep the approved logo as a master vector/SVG or high-resolution original in a club asset library.
- Use the approved club logo in the website header and footer.

### 3.2 Never alter the logo

Do not:

- Use the Rotary wheel alone as the club’s primary website logo
- Redraw, trace, stretch, rotate, crop, recolour, outline, shadow, animate, or distort the official logo
- Place the logo on a low-contrast, busy, or unreadable background
- Add taglines, project names, sponsor names, decorative elements, or extra wording to the official signature
- Replace official Rotary typography with a lookalike in the logo
- Make an unofficial combined logo with another organisation, sponsor, event, or campaign
- Use old or downloaded logos from unknown sources when an official current asset is available

### 3.3 Logo placement and spacing

- Use one primary club logo in the header; do not repeat competing Rotary marks in the same header.
- Keep adequate clear space around the logo, following the current Brand Center rule for the selected asset.
- Keep the logo fully visible at all responsive widths.
- Link the header logo to the home page.
- Place the club logo or a correct small-format approved version in the footer.
- Do not use a logo merely as decoration; it must serve identification.

### 3.4 Campaigns, projects and partners

- Project and event names must identify the club or district when Rotary is used in their name, unless a specific Rotary programme’s official naming rules say otherwise.
- Do not make a project appear to be a Rotary International programme unless it is formally one.
- Use partner/sponsor logos only with written permission and under a documented brand arrangement.
- Keep partner marks visually secondary to the club logo unless a formal agreement requires otherwise.
- Use official programme logos, including End Polio Now marks or Areas of Focus assets, only according to current Brand Center guidance.

---

## 4. Brand system rules

### 4.1 Source of truth

The current Rotary Brand Center is the definitive source for:

- Approved logos and graphics
- Rotary colours
- Typography
- Photography and video guidance
- Voice and messaging
- Areas of Focus icons
- Campaign assets
- Digital and social-media guidance

Do not rely on screenshots, old PDFs, Google Images, third-party templates, or a previously built website when official current assets are available.

### 4.2 Colour and typography

- Use current official Rotary brand colours and their approved digital values from the Brand Center.
- Use colour intentionally: high contrast for reading, consistent hierarchy for actions, and accessible states for links and controls.
- Do not use Rotary blue/yellow only as a decorative requirement at the cost of readability.
- Use the approved Rotary type system where licensing and web delivery permit. If it cannot be used, choose a clean, accessible web-safe fallback that does not imitate the official mark.
- Keep typography restrained: one display-heading style and one body style are normally sufficient.
- Do not use decorative fonts for running text, all-caps paragraphs, very light font weights, or image-only text.

### 4.3 Accessibility minimums

- Meet WCAG 2.2 AA as the implementation target.
- Maintain sufficient colour contrast for text, icons, form states, and buttons.
- Do not make colour the only way to communicate status, error, urgency, or category.
- Support keyboard navigation with a clearly visible focus state.
- Use semantic headings in sequence: one `h1`, followed by logical `h2` and `h3` sections.
- Provide meaningful `alt` text for informative images; use empty alt text for purely decorative images.
- Give every form control a visible label and understandable error message.
- Use descriptive link text: `Read the education project report` rather than `Click here`.
- Provide captions for video and transcripts for important audio/video content.
- Respect reduced-motion preferences; avoid autoplaying video, flashing, and excessive animation.
- Ensure mobile touch targets are comfortably sized and spaced.
- Test with keyboard-only navigation, screen reader basics, 200% browser zoom, narrow mobile widths, and slow mobile networks.

---

## 5. Information architecture and flow

### 5.1 Primary user journeys

The website must make it easy for a visitor to complete one of these tasks without hunting for information:

1. Understand what the club does
2. View real local projects and outcomes
3. Find a club meeting or make contact
4. Volunteer, partner, or refer a community need
5. Support a verified project or donate where authorised
6. See club leadership and governance information
7. Find Rotary International and district resources

### 5.2 Recommended top navigation

Keep top-level navigation to six or fewer meaningful choices:

- Home
- About Us
- Our Projects
- Get Involved
- News & Events
- Contact

Optional only if maintained:

- Donate / Support a Project
- Members Area — must be separate from public navigation and properly secured

Avoid mega menus, duplicate menu labels, long menu chains, and navigation that prioritises internal committee structures over public user needs.

### 5.3 Recommended home-page hierarchy

1. **Header** — official club logo, compact navigation, clear contact/join action
2. **Hero** — specific local statement of purpose, one relevant image, one primary call to action
3. **Proof of work** — 3–4 current project cards with real outcomes
4. **Why it matters** — local community need and how the club responds
5. **Featured project or impact story** — verified narrative with facts, date and partner credit
6. **Get involved** — volunteer, partner, attend, or support actions
7. **Upcoming event / club meeting** — only if current and publicly appropriate
8. **Trust and governance** — club identity, district connection, official contacts, partner acknowledgments where applicable
9. **Footer** — full club identity, contact, policy links, official Rotary/district links and disclaimer

### 5.4 Calls to action

- Use one primary CTA per screen/section.
- Use clear action labels: `Volunteer with us`, `Share a community need`, `Attend a meeting`, `Support this project`, `Contact the club`.
- Do not use vague labels such as `Learn More` repeatedly when a more specific label is possible.
- Do not display a `Donate` CTA until the payment receiver, legal status, receipts, privacy process, fraud controls, and approval route are confirmed.
- Never use misleading urgency, countdown timers, guilt-driven copy, or unclear fundraising claims.

---

## 6. Content rules

### 6.1 Voice and tone

The site should sound:

- People-centred, optimistic, practical, inclusive, local, credible, and action-oriented
- Clear enough for a first-time visitor who knows nothing about Rotary
- Specific about local work rather than relying on slogans

Avoid language that is:

- Political, partisan, religiously promotional, discriminatory, patronising, or self-congratulatory
- Vague, inflated, or impossible to verify
- Written as if the club speaks for Rotary International
- Heavy with unexplained Rotary jargon such as `DG`, `TRF`, `RIP`, or `avenues of service`

Explain necessary Rotary terms in plain English.

### 6.2 Claim-evidence rule

Every material claim must be accurate, dated where relevant, and supportable by club records.

For every published project, record:

- Project name and purpose
- Location
- Club lead/contact
- Date or duration
- Partner organisations
- Funds/materials/volunteer effort, only when verified
- Verified outputs and outcomes
- Photograph, video, quote, and partner permissions
- Any follow-up or sustainability plan

**Use precise language**

- Preferred: `In August 2026, club volunteers supported a school-library drive at [school name], providing [verified number] books.`
- Avoid: `We transformed education for thousands of children.`

Do not publish unverified beneficiary counts, fundraising totals, awards, partner endorsements, government association claims, or global-impact statements.

### 6.3 Mandatory content checks

Before publishing a page, confirm:

- Is the club name correct?
- Is each date, count, location, person, title, and partner name accurate?
- Does the content identify the club’s actual role: organiser, funder, volunteer, facilitator, or partner?
- Are images and quotations authorised?
- Could any statement create a legal, medical, privacy, safety, or reputational risk?
- Does the page need an update date, expiry date, correction, or removal plan?

### 6.4 Leadership and member content

- Publish leadership names and roles only with the individual’s consent and confirmation from the club secretary.
- Prefer official club contact routes instead of personal phone numbers and personal email addresses.
- Do not publish home addresses, personal family details, member IDs, attendance data, internal minutes, or member-only documents.
- Review office-bearer pages at least once per Rotary year and remove outdated roles promptly.

### 6.5 Beneficiary, child and health content

- Obtain informed, written consent for identifiable photos, video, interviews, testimonials, and case studies.
- For children, obtain consent from a parent/legal guardian and comply with the event host/school’s policy.
- Do not disclose a child’s full name, school routine, exact location, medical details, family hardship details, or other information that could create risk.
- Do not publish patient information, diagnoses, prescriptions, medical records, or medical advice.
- For health camps, name the responsible qualified medical organisation/clinician where appropriate and state the scope carefully.
- Preserve dignity: never use distress, illness, disability, poverty, or disaster imagery to sensationalise a fundraising appeal.

### 6.6 Photos, video and media

- Use original club-owned media, Rotary-provided assets, licensed stock media, or partner media with recorded permission.
- Keep a media register showing source, owner, licence, consent status, date, subject/project, and expiry or restrictions.
- Use authentic, diverse, well-lit images showing respectful action and community partnership.
- Avoid generic handshake stock imagery as the main proof of projects.
- Compress images, serve responsive formats, provide descriptive alt text, and avoid very large hero images that slow mobile loading.
- Do not embed music/video that lacks a documented licence.

---

## 7. Fundraising, forms and privacy

### 7.1 Fundraising

Do not accept money on the website until the club has written approval of the fundraising approach and has confirmed:

- The legal entity that receives funds
- The bank/payment account owner
- The authorised project or fund
- Required tax/donation receipt process
- Donor acknowledgement process
- Financial review/reconciliation owner
- Refund, cancellation, and enquiry handling process
- Disclosure language for how funds will be used

Each donation page must state who receives the money, what it supports, whether a donation is restricted or unrestricted, the contact for questions, and the appropriate receipt/tax treatment. Do not imply tax deductibility unless verified for the donor’s jurisdiction and payment route.

### 7.2 Forms

- Collect only data necessary for the stated purpose.
- Use a clear privacy notice beside every form submission button.
- Explain what happens after a person submits a contact, volunteer, event, partner, or donation enquiry.
- Do not collect sensitive personal, health, financial, Aadhaar, PAN, passport, or identity information through a basic contact form.
- Use spam protection that is usable and privacy-conscious.
- Send form notifications to a club-controlled mailbox with restricted access.
- Set retention/deletion rules for submitted enquiries and mailing lists.
- Obtain explicit consent before adding a person to a newsletter or marketing list.

### 7.3 Privacy and cookies

Publish, at minimum:

- Privacy policy
- Terms/website-use notice if appropriate
- Cookie notice/consent mechanism if non-essential cookies, analytics, ad pixels, or embedded third-party services are used
- Donation terms/refund policy if collecting payments
- Accessibility statement/contact method

The policy must identify the club/data controller, purpose of data collection, data recipients/tools, retention approach, contact address, and choices available to the visitor. Have legal counsel review compliance with applicable Indian privacy and consumer requirements before collecting personal data or payments at scale.

---

## 8. Technical and security rules

### 8.1 Minimum technical standard

- Enforce HTTPS site-wide and redirect HTTP to HTTPS.
- Use a current supported CMS/framework, theme, plugins, server runtime, and dependencies.
- Remove unused plugins, themes, libraries, user accounts, API keys, and scripts.
- Apply security updates promptly; define who is responsible and how frequently updates occur.
- Use strong unique passwords and MFA for privileged accounts.
- Use role-based access: editors should not receive server, DNS, financial, or administrator rights unless needed.
- Keep daily automated backups and test restoration periodically.
- Maintain a staging environment for major changes.
- Use a web application firewall/CDN where appropriate.
- Never store payment-card data or secrets in source code, forms, email, or public repositories.
- Use environment variables/secret management for keys.

### 8.2 Performance standard

- Prioritise mobile performance because most visitors may arrive on mobile networks.
- Optimise images; use modern formats and responsive sizes.
- Limit large carousels, autoplay video, excessive animation, heavy page builders, third-party trackers, and duplicate libraries.
- Lazy-load below-the-fold media.
- Maintain a lean, readable page structure and test on low-end phones/network throttling.
- Review Core Web Vitals and page-weight regressions after major changes.

### 8.3 SEO and sharing

- Give each page one unique, descriptive title and meta description.
- Use a meaningful page URL: `/projects/school-library-drive-2026/`, not `/page?id=23`.
- Use one `h1` per page and logical headings.
- Add canonical URLs, XML sitemap, robots controls, and structured data only when accurate.
- Use `Organization` / `LocalBusiness` structured data only if the chosen schema accurately represents the club; do not fabricate ratings, dates, addresses, or affiliations.
- Set a correct Open Graph image and title for sharing, using approved imagery and logo treatment.
- Do not keyword-stuff Rotary, Bengaluru, charity, donation, or volunteer terms.

---

## 9. Required pages and footer

### 9.1 Minimum public pages

1. Home
2. About the Club
3. Projects / Community Impact
4. Get Involved
5. News and Events
6. Contact
7. Privacy Policy
8. Accessibility / Feedback contact

Add only when genuinely supported and maintained:

- Donate / Support a Project
- Leadership
- Annual reports / financial information
- Media resources
- Member login

### 9.2 Footer requirements

The footer must include:

- Official club name
- City, state, country
- Club-controlled contact email and/or contact form link
- Links to Privacy Policy and accessibility feedback route
- Link to Rotary International and the applicable district, where confirmed
- Copyright year
- Clear entity disclaimer

**Recommended footer wording**

> © [YEAR] Rotary Club of Bangalore Bhuvaneshwarinagar. A local Rotary club serving Bengaluru, Karnataka, India.
>
> Rotary and the Rotary logo are trademarks of Rotary International and are used in accordance with applicable Rotary brand guidance.
>
> This website represents Rotary Club of Bangalore Bhuvaneshwarinagar. It does not represent Rotary International, Rotary India, or any other Rotary entity unless expressly stated.

Do not list the district number until it is verified by the club/district.

---

## 10. Governance and publishing workflow

### 10.1 Roles

Assign named people for these roles:

- **Website owner:** Club board-designated accountability owner
- **Content editor:** Prepares updates and maintains editorial calendar
- **Brand reviewer:** Confirms logo, name, visual identity, and Rotary alignment
- **Project verifier:** Confirms project facts, numbers, partners and permissions
- **Privacy/form owner:** Manages enquiries, consent, retention and responses
- **Technical administrator:** Controls hosting, security, backup and releases
- **Final publisher:** Has authority to publish after required review

One person may hold more than one role, but high-risk actions—domain/DNS, payment systems, and final public publication—should have a second reviewer where practical.

### 10.2 Publish checklist

Before any page goes live, complete this checklist:

- [ ] Club identity and title are correct
- [ ] Logo is official, current and unaltered
- [ ] Brand colours and typography follow the approved system
- [ ] All claims, dates, counts and partners are verified
- [ ] Photo/video/quote permissions are recorded
- [ ] No unnecessary personal or sensitive information is exposed
- [ ] Links, forms, email routes and phone numbers work
- [ ] Page works on mobile, desktop, keyboard and 200% zoom
- [ ] Images have correct alt text and are compressed
- [ ] Title, meta description and sharing image are accurate
- [ ] Privacy/cookie/payment requirements are met
- [ ] The content has a named owner and next review date
- [ ] Required reviewers have approved the version

### 10.3 Review cadence

- **Monthly:** Contact details, event dates, broken links, form inboxes, security updates
- **Quarterly:** Project facts, leadership content, analytics, performance, backups, user access
- **Annually / Rotary year change:** President/office-bearer details, strategic pages, logo/campaign assets, domain renewal, policies, permissions and full accessibility review
- **Immediately:** Remove incorrect, expired, unsafe, misleading, private, unapproved, or rights-infringing content

---

## 11. Content template: project page

Use this structure for every public project page:

1. **Project title:** Specific and plain-language
2. **Summary:** What the club did and why
3. **Location and date:** Accurate and public-safe
4. **Community need:** Evidence-led local context
5. **Club role:** Organised, funded, volunteered, partnered, facilitated, etc.
6. **Partners:** Only verified names/logos with permission
7. **What happened:** Clear activity description
8. **Verified impact:** Counts and outcomes with scope/date
9. **Media:** Consented images/video with captions and alt text
10. **Next steps:** Follow-up, maintenance, or future activity where applicable
11. **Get involved:** Relevant, authorised CTA
12. **Last reviewed:** Date and content owner

---

## 12. Prohibited or high-risk content

Do not publish without explicit written authorisation and appropriate review:

- Political endorsements, campaign material, party messaging, or lobbying claims
- Religious conversion or religiously promotional content
- Discriminatory, hateful, harassing, or exclusionary material
- Medical diagnosis, treatment claims, patient data, or unqualified health advice
- Financial promises, investment advice, loan solicitations, or unverified tax claims
- Names/photos/details of vulnerable people without informed consent
- Member passwords, private documents, internal discussions, minutes, ID numbers, or personal contact data
- Fundraising requests with unclear payment receiver or use of funds
- Copyrighted photos, music, video, text, fonts, templates or logos without rights
- Statements that claim Rotary International or district endorsement when none exists
- Information that creates security risk for children, events, facilities, partners, or members

---

## 13. Final approval gate

The site may go live only when all of the following are true:

- The Club President and Secretary confirm the official club identity and website authority.
- The relevant club/district public-image or brand reviewer has reviewed Rotary name/logo/asset use.
- The club controls the domain, hosting, DNS and administrator access.
- All public content has an accountable owner and documented evidence/permissions.
- Required privacy, form and payment safeguards are in place.
- Mobile, accessibility, security, performance and contact-flow checks have passed.
- A post-launch maintenance owner and review schedule are confirmed.

---

## Official references to check before launch

- Rotary Brand Center: `https://brandcenter.rotary.org/`
- Brand Center — Websites: `https://brandcenter.rotary.org/en-us/our-brand/promote-rotary/websites`
- Brand Center — Using the Rotary name: `https://brandcenter.rotary.org/en-us/help-and-faq/faq/using-the-rotary-name`
- Rotary International: `https://www.rotary.org/`

**Implementation note:** Before final visual design or launch, download the current official club-logo files and current brand specifications directly from the Rotary Brand Center, and obtain written confirmation from the club/district reviewer for any uncertainty about naming, logos, domains, campaigns, fundraising, or affiliations.