# User-Facing Backlog - Freedom Rising USA Website

This document tracks all placeholder content and information needed from the site owners to complete the Freedom Rising USA website.

**Last Updated:** December 22, 2024

---

## Board of Directors Information

### President of the Board

- **Status:** 🔴 NEEDED
- **Current:** `[Board President - TBD]`
- **Required Information:**
  - Full name
  - LinkedIn profile URL
  - Professional headshot photo (circular crop preferred, 300x300px minimum)
- **Location:** `src/data/team/clarke-moyer.json`
- **Image:** `/public/Images/member1.webp` (placeholder)

### Vice President

- **Status:** 🔴 NEEDED
- **Current:** `[Board Vice President - TBD]`
- **Required Information:**
  - Full name
  - LinkedIn profile URL
  - Professional headshot photo (circular crop preferred, 300x300px minimum)
- **Location:** `src/data/team/chris-rae.json`
- **Image:** `/public/Images/member2.webp` (placeholder)

### Secretary

- **Status:** 🔴 NEEDED
- **Current:** `[Board Secretary - TBD]`
- **Required Information:**
  - Full name
  - LinkedIn profile URL
  - Professional headshot photo (circular crop preferred, 300x300px minimum)
- **Location:** `src/data/team/tyler-carlotto.json`
- **Image:** `/public/Images/member3.webp` (placeholder)

### Treasurer

- **Status:** 🔴 NEEDED
- **Current:** `[Board Treasurer - TBD]`
- **Required Information:**
  - Full name
  - LinkedIn profile URL
  - Professional headshot photo (circular crop preferred, 300x300px minimum)
- **Location:** `src/data/team/brennan-darling.json`
- **Image:** `/public/Images/member4.webp` (placeholder)

### Member at Large

- **Status:** 🟡 PARTIAL - Name and LinkedIn available
- **Current:** Clarke Moyer
- **LinkedIn:** https://www.linkedin.com/in/clarke-moyer/
- **Required Information:**
  - ✅ Name: Clarke Moyer
  - ✅ LinkedIn: https://www.linkedin.com/in/clarke-moyer/
  - 🔴 Confirm photo location (currently using member5.webp with red background)
- **Location:** `src/data/team/rebecca-cook.json`
- **Image:** `/public/Images/member5.webp` (has Clarke Moyer's photo with red background)

**Note:** Clarke Moyer is also listed as DPO (Data Protection Officer) in privacy policy and emergency contact in cookie policy.

---

## Testimonials

All testimonials need real quotes from actual parade supporters, volunteers, and community members.

### Testimonial 1 - Parade Supporter

- **Status:** 🔴 NEEDED
- **Current Author:** `[Parade Supporter Name - TBD]`
- **Current Quote:** Generic placeholder about community celebration
- **Required Information:**
  - Real name of parade supporter
  - Authentic testimonial quote about the parade experience
  - Optional: Location (e.g., "State College, PA")
- **Location:** `src/data/testimonials/testimonial-1.json`

### Testimonial 2 - Local Business Owner

- **Status:** 🔴 NEEDED
- **Current Author:** `[Local Business Owner - TBD]`
- **Current Quote:** Generic placeholder about business participation
- **Required Information:**
  - Real name and business name
  - Authentic testimonial quote about participating in the parade
  - Optional: Business type/industry
- **Location:** `src/data/testimonials/testimonial-2.json`

### Testimonial 3 - Parade Volunteer

- **Status:** 🔴 NEEDED
- **Current Author:** `[Parade Volunteer - TBD]`
- **Current Quote:** Generic placeholder about volunteering experience
- **Required Information:**
  - Real name of volunteer
  - Authentic testimonial quote about volunteer experience
  - Optional: Years of volunteering
- **Location:** `src/data/testimonials/testimonial-3.json`

### Hardcoded Testimonials in VoicesofGratitude Component

- **Status:** 🔴 NEEDED
- **Location:** `src/components/home-page/VoicesofGratitude/index.tsx`
- **Current:** 3 testimonials with "Name" placeholder and outdated Free For Charity references
- **Required Information:**
  - Real testimonials from parade participants
  - Author names
  - 5-star ratings (or actual ratings from supporters)

**Action Required:** Update hardcoded testimonials to reflect Freedom Rising USA mission

---

## Parade Statistics (Results Section)

### Annual Parade Impact Data

- **Status:** 🔴 NEEDED
- **Current Title:** `Parade Impact - [Year - TBD]`
- **Location:** `src/components/home-page/Results-2023/index.tsx`

**Required Statistics:**

1. **Year**
   - Which parade year these statistics represent (e.g., "2024", "2023")

2. **Parade Participants**
   - **Current:** `[TBD]`
   - **Need:** Number of floats, marching bands, organizations, etc. that participated

3. **Volunteer Hours**
   - **Current:** `[TBD]`
   - **Need:** Total volunteer hours contributed to organizing and running the parade

4. **Community Members in Attendance**
   - **Current:** `[TBD]`
   - **Need:** Estimated number of spectators/attendees

5. **Local Businesses Participating**
   - **Current:** `[TBD]`
   - **Need:** Number of local businesses that participated or sponsored

---

## Contact Information

### Phone Number

- **Status:** 🔴 NEEDED
- **Current:** `(814) 555-1234` (placeholder)
- **Required:** Real phone number for Freedom Rising USA
- **Locations:**
  - Footer: `src/components/footer/index.tsx`
  - FAQs: `src/data/faqs.ts`
  - Multiple policy pages

### Email Address

- **Status:** ✅ CONFIRMED
- **Current:** `info@freedomrisingusa.org`
- **Note:** This appears to be the official email and is appropriate

### Physical Address

- **Status:** 🟡 PARTIAL
- **Current:** `State College, PA 16803`
- **Note:** General location is appropriate, but may want to add street address if there's a physical office

---

## Forms and URLs

### Volunteer Form

- **Status:** 🔴 NEEDED
- **Current:** `#volunteer-form-placeholder` (dead link)
- **Required:** Actual URL to volunteer signup form
- **Location:** `src/components/home-page/Volunteer-with-Us/index.tsx`
- **Options:**
  - Google Forms
  - Microsoft Forms
  - Typeform
  - Custom form on website
  - Email signup

### Donation Form

- **Status:** 🔴 CRITICAL - Currently pointing to wrong organization
- **Current:** `https://www.zeffy.com/embed/donation-form/free-for-charity-endowment-fund`
- **Problem:** This is the Free For Charity donation form, NOT Freedom Rising USA
- **Required:** New Zeffy donation form URL for Freedom Rising USA
- **Location:** `src/components/home-page/SupportFreeForCharity/index.tsx`
- **Action:** Create new Zeffy account/form for Freedom Rising USA OR use different donation platform

---

## Branding Assets

### Organization Logo

- **Status:** 🟡 USING PLACEHOLDER
- **Current:** Using generic placeholder logo
- **Required:** Official Freedom Rising USA logo
- **Formats Needed:**
  - PNG with transparent background (for header)
  - SVG version (scalable, preferred)
  - High resolution version for print
- **Sizes:**
  - Header logo: recommend 200x80px or similar
  - Favicon: 32x32px, 16x16px
  - Open Graph image: 1200x630px

### Hero Image

- **Status:** 🟡 USING PLACEHOLDER
- **Current:** Generic placeholder image
- **Location:** `/public/Images/figma-hero-img.webp`
- **Recommendation:** Replace with parade-related image (e.g., previous parade photo, patriotic imagery, State College celebration)

### Other Images to Consider Replacing

1. `/public/Images/support-free-for-charity.webp` - Has "Free For Charity" in filename
2. `/public/Images/Volunteer-with-Us.webp` - Generic image, could be parade-specific
3. Team member placeholder photos (member1-5.webp)

---

## Policy Pages

### Effective Dates

- **Status:** 🔴 NEEDED
- **Current:** Most policies show `[TBD]` for effective date
- **Required:** Actual effective dates for all policies
- **Locations:**
  - `src/app/donation-policy/page.tsx`
  - `src/app/free-for-charity-donation-policy/page.tsx`
  - `src/app/privacy-policy/page.tsx`
  - `src/app/cookie-policy/page.tsx`
  - Others

### Free For Charity Donation Policy Page

- **Status:** 🟡 REVIEW NEEDED
- **Current:** Separate page exists at `/free-for-charity-donation-policy`
- **Question:** Is this page still needed? Or should it be removed/redirected?
- **Action Required:** Decision from site owners

---

## Priority Levels

### 🔴 CRITICAL (Blocks Launch)

1. **Donation Form URL** - Currently points to wrong organization!
2. **Board President Information** - Main leadership position
3. **Phone Number** - Primary contact method
4. **Volunteer Form URL** - Primary CTA is broken

### 🟡 HIGH PRIORITY (Needed Soon)

1. **All Board Member Information** - Complete team section
2. **Real Testimonials** - Build credibility
3. **Parade Statistics** - Demonstrate impact
4. **Organization Logo** - Professional branding

### 🟢 MEDIUM PRIORITY (Can Wait)

1. **Policy Effective Dates** - Legal requirement but can use temporary dates
2. **Hero and Section Images** - Functional but could be more on-brand
3. **Team Member Photos** - Using placeholders is acceptable short-term

---

## How to Update

### Board Members

1. Edit JSON file in `src/data/team/[member-name].json`
2. Replace image in `/public/Images/memberX.webp`
3. Update corresponding LinkedIn URL

### Testimonials

1. Edit JSON files in `src/data/testimonials/`
2. Update hardcoded testimonials in `src/components/home-page/VoicesofGratitude/index.tsx`

### Statistics

1. Edit `src/components/home-page/Results-2023/index.tsx`
2. Update year and all four metrics

### Contact Information

1. Footer: `src/components/footer/index.tsx`
2. FAQs: `src/data/faqs.ts`
3. Policy pages as needed

### Forms

1. Volunteer: `src/components/home-page/Volunteer-with-Us/index.tsx`
2. Donation: `src/components/home-page/SupportFreeForCharity/index.tsx`

### Images

1. Place new images in `/public/Images/`
2. Use .webp format for best performance
3. Optimize images before uploading

---

## Questions for Site Owners

1. **Board Structure:** Is the current board structure correct (President, VP, Secretary, Treasurer, Member at Large)?
2. **Clarke Moyer:** Confirm his role as Member at Large and if his current photo (member5.webp with red background) should be used?
3. **Free For Charity Donation Policy:** Should this page be removed, or does it serve a purpose?
4. **Donation Platform:** Will you use Zeffy for Freedom Rising USA donations, or another platform?
5. **Volunteer Platform:** What system will you use for volunteer signups?
6. **Logo:** Do you have a logo designed, or do you need one created?
7. **Previous Parade:** Do you have photos or statistics from previous parades to use?

---

## Technical Notes

- All changes require rebuilding the site with `npm run build`
- After updating, test locally with `npm run dev` before deploying
- Images should be optimized for web (WebP format recommended)
- Keep original high-resolution assets for future use
- Contact development team if you need help making changes

---

**Status Legend:**

- 🔴 NEEDED - Critical information required
- 🟡 PARTIAL - Some information available, more needed
- ✅ CONFIRMED - Information is complete and correct
