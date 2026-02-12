# Chained Evolution - Site Updates
## February 11, 2026

---

## Changes Made

### 1. ✅ Removed Wearables References
**Files updated:** `index.html`, `services.html`

- Removed "wearable integration" from About section on homepage
- Removed "wearable device integration" from Digital Health service
- Updated service description to focus on InBody and Fit3D only

---

### 2. ✅ Added General Company Statement
**File:** `about.html`

Added new "Who We Are" section before individual bios:
- Describes Chained Evolution as Waltham's premier boutique fitness studio
- Explains the data-driven approach
- Sets context before introducing Audrey and Charles

---

### 3. ✅ Added Technology FAQ Section
**File:** `faq.html`

New "Our Technology" section explaining:
- **What is InBody 570?** — Medical-grade body composition analyzer, measures muscle/fat/water distribution
- **What is Fit3D?** — 3D body scanner with visual avatar and measurements
- **Why use both?** — Complete picture: inside (InBody) + outside (Fit3D)
- **What makes Chained Evolution different?** — We measure, others guess. Small studio by design.

---

### 4. ✅ Added Individual Bookable Services
**File:** `services.html`

New "À La Carte" section with:
| Service | Price |
|---------|-------|
| InBody Scan | $10 |
| Fit3D Scan | $15 |
| Combo Scan Package | $20 |
| Drop-In Class | $25 |

---

### 5. ✅ Added Supplements/Shop Section
**File:** `services.html`

New section linking to https://chainedevolution.com/shop/ with:
- Protein powders and bars
- Pre-workout and recovery
- Vitamins and wellness
- Chained Evolution apparel
- Training accessories

---

### 6. ✅ Added Video Section (Placeholders)
**File:** `index.html`

New "See Us In Action" section with placeholder slots for:
- Training Session Video
- InBody/Fit3D Demo
- Group Class Highlights

*Ready for actual video embeds when content is available*

---

## Needs Charles's Input

### ⚠️ Boxing in Group Classes
Currently, Boxing is listed as a Group Class option:
- Boxing
- Strength & Conditioning
- High-Intensity Circuit Training

**Question for Charles:** Should Boxing remain as a group class offering, or should it be modified/removed?

---

## Items 3 & 4 Not Showing - Investigation

The services grid on the homepage shows all 4 services:
1. Personal Training
2. Body Composition Analysis (renamed from Digital Health)
3. Nutrition Coaching
4. Group Classes

If items 3 & 4 aren't displaying, possible causes:
- **CSS issue** — Check if `.service-card:nth-child(3)` or `(4)` have display issues
- **JavaScript animation** — reveal-up animation might be failing
- **Browser cache** — Hard refresh (Cmd+Shift+R)
- **Viewport issue** — Grid might need adjustment for certain screen sizes

**Recommendation:** Clear cache and test. If still not showing, check browser console for JS errors.

---

## Files Changed

| File | Changes |
|------|---------|
| `index.html` | Removed wearables, added video section |
| `about.html` | Added "Who We Are" general company section |
| `services.html` | Removed wearables, added individual services, added shop section |
| `faq.html` | Added Technology FAQ section |

---

## To Deploy

```bash
cd /tmp/chained-evolution
git add -A
git commit -m "Site updates: remove wearables, add FAQ, individual services, shop, video section"
git push
```

---

## Still To Do (Requires Content)

- [ ] Fill in Audrey's bio
- [ ] Fill in Charles's bio  
- [ ] Add actual video content
- [ ] Confirm boxing in group classes (Charles)
- [ ] Review pricing for individual services
- [ ] Add product images for shop section (optional)

---

*Updates by C&L Strategy — cl-strategy.com*
