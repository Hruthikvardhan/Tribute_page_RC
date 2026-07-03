# 🧪 Manual Testing Document
## Project: Ram Charan — The Global Icon Tribute Page

**Document Version:** 1.0
**Date:** July 2026
**Author:** Hruthik
**Type:** Manual Testing
**Status:** ✅ All Tests Passed

---

## TESTING APPROACH

Since this is a pure frontend static project, we used:

```
Manual Testing → Test every feature by hand
Cross Browser  → Chrome, Firefox, Edge
Responsive     → Desktop, Tablet, Mobile sizes
Visual         → Check all animations and effects
```

---

## 1. PRE-TESTING CHECKLIST

Before starting tests, verify these:

| Check | Status |
|---|---|
| index.html saved | ✅ |
| rc.jpg in same folder | ✅ |
| rc-portrait.jpg in same folder | ✅ |
| Internet connection (for Google Fonts) | ✅ |
| Browser cache cleared | ✅ |

---

## 2. PAGE LOAD TESTS

| # | Test | Expected Result | Actual Result | Pass/Fail |
|---|---|---|---|---|
| PL-01 | Open index.html in Chrome | Page loads without errors | Loads correctly | ✅ Pass |
| PL-02 | Check browser console | No red errors in console | No errors | ✅ Pass |
| PL-03 | Check favicon in tab | RC gold icon visible | Shows correctly | ✅ Pass |
| PL-04 | Check page title in tab | "Ram Charan — The Global Icon" | Shows correctly | ✅ Pass |
| PL-05 | Check Google Fonts loaded | Cinzel font visible in navbar | Fonts loaded | ✅ Pass |
| PL-06 | Check hero loads | RAM CHARAN text visible | Visible | ✅ Pass |
| PL-07 | Check hero photo | RC background photo visible | Visible | ✅ Pass |
| PL-08 | Check particles | Gold dots floating up | Animating | ✅ Pass |

---

## 3. NAVBAR TESTS — Desktop

| # | Test | Expected Result | Actual Result | Pass/Fail |
|---|---|---|---|---|
| NB-01 | Navbar visible on load | RC + nav links visible | Visible | ✅ Pass |
| NB-02 | Navbar position on scroll | Stays fixed at top | Fixed correctly | ✅ Pass |
| NB-03 | Navbar background on scroll | Dark glass effect after 60px | Applies correctly | ✅ Pass |
| NB-04 | Hover on About link | Gold color + underline slides in | Works | ✅ Pass |
| NB-05 | Hover on Filmography link | Gold color + underline slides in | Works | ✅ Pass |
| NB-06 | Hover on Dialogues link | Gold color + underline slides in | Works | ✅ Pass |
| NB-07 | Hover on Awards link | Gold color + underline slides in | Works | ✅ Pass |
| NB-08 | Hover on Legacy link | Gold color + underline slides in | Works | ✅ Pass |
| NB-09 | Click RC brand logo | Scrolls to top (home) | Works | ✅ Pass |
| NB-10 | Active link on scroll | Current section link turns gold | Works | ✅ Pass |

---

## 4. NAVBAR TESTS — Mobile (Hamburger)

| # | Test | Expected Result | Actual Result | Pass/Fail |
|---|---|---|---|---|
| HB-01 | Resize to 375px width | Hamburger ☰ appears | Appears | ✅ Pass |
| HB-02 | Desktop nav on mobile | Nav links hidden | Hidden correctly | ✅ Pass |
| HB-03 | Click hamburger | Full screen menu opens | Opens | ✅ Pass |
| HB-04 | Hamburger animation | ☰ animates to ✕ | Animates | ✅ Pass |
| HB-05 | Menu background | Dark blur overlay | Shows correctly | ✅ Pass |
| HB-06 | Menu links visible | All 5 links centered | Visible | ✅ Pass |
| HB-07 | Hover menu link | Link turns gold with glow | Works | ✅ Pass |
| HB-08 | Click About in menu | Menu closes + scrolls to About | Works | ✅ Pass |
| HB-09 | Click Filmography in menu | Menu closes + scrolls to Timeline | Works | ✅ Pass |
| HB-10 | Press Escape key | Menu closes | Works | ✅ Pass |
| HB-11 | Close menu (✕ to ☰) | Animates back to hamburger | Animates | ✅ Pass |
| HB-12 | Body scroll when menu open | Body scroll locked | Locked correctly | ✅ Pass |

---

## 5. HERO SECTION TESTS

| # | Test | Expected Result | Actual Result | Pass/Fail |
|---|---|---|---|---|
| HR-01 | Hero fills full screen | 100vh height | Full screen | ✅ Pass |
| HR-02 | Eyebrow text visible | "BORN TO RULE THE SCREEN" in red | Visible | ✅ Pass |
| HR-03 | RAM CHARAN gold gradient | Gold shimmer text | Shows correctly | ✅ Pass |
| HR-04 | Tagline visible | Actor · Entrepreneur · Global Icon | Visible | ✅ Pass |
| HR-05 | GLOBAL ICON in red | That word in crimson | Shows correctly | ✅ Pass |
| HR-06 | Diamond divider visible | ── ◆ ── golden line | Visible | ✅ Pass |
| HR-07 | Stats visible | 18+, 20+, 1, ∞ | All visible | ✅ Pass |
| HR-08 | Counter animation | Numbers count up from 0 | Counts up | ✅ Pass |
| HR-09 | Scroll indicator visible | SCROLL + bouncing arrow | Visible | ✅ Pass |
| HR-10 | Scroll indicator bounce | Arrow bounces up down | Bouncing | ✅ Pass |
| HR-11 | Click scroll indicator | Smoothly scrolls to About | Works | ✅ Pass |
| HR-12 | Hero animations on load | Elements fade in with delay | All animate | ✅ Pass |
| HR-13 | Horizontal lines | Two subtle lines across hero | Visible | ✅ Pass |
| HR-14 | Particles floating | Gold dots float upward | Animating | ✅ Pass |

---

## 6. ABOUT SECTION TESTS

| # | Test | Expected Result | Actual Result | Pass/Fail |
|---|---|---|---|---|
| AB-01 | Section title | "THE MAN. THE LEGEND." in gold | Visible | ✅ Pass |
| AB-02 | Section subtitle | Italic subtitle below title | Visible | ✅ Pass |
| AB-03 | Portrait photo visible | RC portrait in card | Shows | ✅ Pass |
| AB-04 | Portrait card shape | Tall portrait 3:4 ratio | Correct shape | ✅ Pass |
| AB-05 | Glowing border | Red-gold pulsing border animation | Animating | ✅ Pass |
| AB-06 | Caption below photo | "Ram Charan Teja · Born 1985" | Visible | ✅ Pass |
| AB-07 | Bio heading gold | "Konidela Ram Charan Teja" in gold | Correct | ✅ Pass |
| AB-08 | Strong text brighter | Bold words appear brighter | Correct | ✅ Pass |
| AB-09 | Facts grid 2 columns | 6 facts in 2×3 grid | Correct | ✅ Pass |
| AB-10 | Hover on fact card | Border brightens | Works | ✅ Pass |
| AB-11 | Scroll reveal | Section fades in on scroll | Works | ✅ Pass |

---

## 7. TIMELINE SECTION TESTS

| # | Test | Expected Result | Actual Result | Pass/Fail |
|---|---|---|---|---|
| TL-01 | Section title visible | "BLOCKBUSTER JOURNEY" | Visible | ✅ Pass |
| TL-02 | Spine line visible | Vertical red-gold line | Visible | ✅ Pass |
| TL-03 | Chirutha card — left side | Odd item on left | Correct | ✅ Pass |
| TL-04 | Magadheera card — right side | Even item on right | Correct | ✅ Pass |
| TL-05 | Zigzag pattern all items | Alternates left-right | Correct | ✅ Pass |
| TL-06 | Dots on spine | Red dot with gold border | Visible | ✅ Pass |
| TL-07 | Hover card | Lifts up + gold border + glow | Works | ✅ Pass |
| TL-08 | Hover dot change | Dot turns gold on hover | Works | ✅ Pass |
| TL-09 | Year in red | Year displayed in crimson | Correct | ✅ Pass |
| TL-10 | Movie name in gold | Movie title in gold | Correct | ✅ Pass |
| TL-11 | Badge pill shape | Rounded badge at bottom | Shows | ✅ Pass |
| TL-12 | All 8 films visible | Chirutha to Peddi | All visible | ✅ Pass |
| TL-13 | Scroll reveal stagger | Cards appear with delay | Works | ✅ Pass |

---

## 8. QUOTES SECTION TESTS

| # | Test | Expected Result | Actual Result | Pass/Fail |
|---|---|---|---|---|
| QT-01 | Section title visible | "WORDS THAT ECHO" | Visible | ✅ Pass |
| QT-02 | Featured quote full width | RRR quote spans all columns | Correct | ✅ Pass |
| QT-03 | 4 quote cards visible | All 4 dialogues showing | Visible | ✅ Pass |
| QT-04 | Background quote mark | Faint giant " in background | Visible | ✅ Pass |
| QT-05 | Transliteration text | Telugu in English letters | Correct | ✅ Pass |
| QT-06 | Source with dash | "— RRR — Alluri..." | Correct | ✅ Pass |
| QT-07 | Hover card | Lifts 5px + gold glow | Works | ✅ Pass |
| QT-08 | Hover top bar | Red-gold bar appears at top | Works | ✅ Pass |
| QT-09 | Scroll reveal | Cards fade in on scroll | Works | ✅ Pass |

---

## 9. AWARDS SECTION TESTS

| # | Test | Expected Result | Actual Result | Pass/Fail |
|---|---|---|---|---|
| AW-01 | Section title visible | "HONOURS & GLORY" | Visible | ✅ Pass |
| AW-02 | 8 award cards visible | All awards showing | Visible | ✅ Pass |
| AW-03 | Emoji icons visible | 🏆 🎬 🌟 etc. | Showing | ✅ Pass |
| AW-04 | Award title in gold | Title text in gold | Correct | ✅ Pass |
| AW-05 | Year in crimson | Year in red text | Correct | ✅ Pass |
| AW-06 | Hover card | Lifts 3px + gold border | Works | ✅ Pass |
| AW-07 | Scroll reveal stagger | Cards appear with delays | Works | ✅ Pass |
| AW-08 | Icon glow effect | Emoji has gold glow | Visible | ✅ Pass |

---

## 10. LEGACY SECTION TESTS

| # | Test | Expected Result | Actual Result | Pass/Fail |
|---|---|---|---|---|
| LG-01 | Section title visible | "LEGACY & GLOBAL IMPACT" | Visible | ✅ Pass |
| LG-02 | Headline visible | "Beyond Tollywood. Beyond Borders." | Visible | ✅ Pass |
| LG-03 | "Beyond Borders" in red | That line in crimson | Correct | ✅ Pass |
| LG-04 | Milestone list | 6 bullet points visible | All visible | ✅ Pass |
| LG-05 | Red bullet dots | Small crimson dots | Visible | ✅ Pass |
| LG-06 | Stats panel visible | 4 stat boxes in grid | Visible | ✅ Pass |
| LG-07 | Stats gold gradient text | Numbers in gold gradient | Correct | ✅ Pass |
| LG-08 | Hover stat box | Border turns crimson + scale | Works | ✅ Pass |
| LG-09 | Oscar callout box | Full width, trophy icon + text | Visible | ✅ Pass |
| LG-10 | Scroll reveal | Elements fade in | Works | ✅ Pass |

---

## 11. FOOTER TESTS

| # | Test | Expected Result | Actual Result | Pass/Fail |
|---|---|---|---|---|
| FT-01 | Footer visible | All 3 columns showing | Visible | ✅ Pass |
| FT-02 | Brand name in gold | "Ram Charan" in gold display font | Correct | ✅ Pass |
| FT-03 | Quick links work | Clicking scrolls to section | Works | ✅ Pass |
| FT-04 | Wikipedia link | Opens Wikipedia in new tab | Works | ✅ Pass |
| FT-05 | IMDb link | Opens IMDb in new tab | Works | ✅ Pass |
| FT-06 | Instagram link | Opens Instagram in new tab | Works | ✅ Pass |
| FT-07 | Twitter link | Opens Twitter in new tab | Works | ✅ Pass |
| FT-08 | Hover footer link | Turns gold + shifts right | Works | ✅ Pass |
| FT-09 | Social circles | IG TW DB circular buttons | Visible | ✅ Pass |
| FT-10 | Hover social link | Gold border + glow | Works | ✅ Pass |
| FT-11 | Copyright text visible | 2026, red heart | Correct | ✅ Pass |
| FT-12 | Divider line | Top border visible | Correct | ✅ Pass |

---

## 12. RESPONSIVE TESTS

### Desktop (1440px)
| # | Test | Pass/Fail |
|---|---|---|
| RD-01 | Hero centered | ✅ Pass |
| RD-02 | About grid 2 columns | ✅ Pass |
| RD-03 | Timeline zigzag | ✅ Pass |
| RD-04 | Quotes 3 columns | ✅ Pass |
| RD-05 | Awards 3 columns | ✅ Pass |
| RD-06 | Legacy 2 columns | ✅ Pass |
| RD-07 | Footer 3 columns | ✅ Pass |

### Tablet (768px)
| # | Test | Pass/Fail |
|---|---|---|
| RT-01 | About grid adjusts | ✅ Pass |
| RT-02 | Legacy stacks to 1 column | ✅ Pass |
| RT-03 | Footer 2 columns | ✅ Pass |
| RT-04 | Nav still visible | ✅ Pass |

### Mobile (375px)
| # | Test | Pass/Fail |
|---|---|---|
| RM-01 | Hamburger shows | ✅ Pass |
| RM-02 | Desktop nav hidden | ✅ Pass |
| RM-03 | About stacks to 1 column | ✅ Pass |
| RM-04 | Portrait photo full width | ✅ Pass |
| RM-05 | Timeline single column | ✅ Pass |
| RM-06 | Timeline spine moves to left | ✅ Pass |
| RM-07 | Quotes stack vertically | ✅ Pass |
| RM-08 | Awards stack vertically | ✅ Pass |
| RM-09 | Footer single column | ✅ Pass |
| RM-10 | No horizontal scroll | ✅ Pass |
| RM-11 | Text readable — no overflow | ✅ Pass |
| RM-12 | RAM CHARAN text fits | ✅ Pass |

---

## 13. CROSS BROWSER TESTS

| Browser | Version | Page Loads | Layout OK | Animations | Fonts | Pass/Fail |
|---|---|---|---|---|---|---|
| Chrome | Latest | ✅ | ✅ | ✅ | ✅ | ✅ Pass |
| Edge | Latest | ✅ | ✅ | ✅ | ✅ | ✅ Pass |
| Firefox | Latest | ✅ | ✅ | ✅ | ✅ | ✅ Pass |
| Mobile Chrome | Latest | ✅ | ✅ | ✅ | ✅ | ✅ Pass |

---

## 14. PERFORMANCE CHECKS

| Check | Target | Actual | Pass/Fail |
|---|---|---|---|
| Hero image size | Under 500KB | ~280KB | ✅ Pass |
| Portrait image size | Under 300KB | ~120KB | ✅ Pass |
| No console errors | 0 errors | 0 errors | ✅ Pass |
| Scroll smooth | No janky scroll | Smooth | ✅ Pass |
| Animations smooth | No lag | Smooth | ✅ Pass |

---

## 15. ACCESSIBILITY CHECKS

| Check | Status |
|---|---|
| All images have alt text | ✅ Pass |
| Navbar has aria-label | ✅ Pass |
| Hamburger has aria-expanded | ✅ Pass |
| Sections have aria-labelledby | ✅ Pass |
| Lists have role="list" | ✅ Pass |
| Links open in new tab have rel="noopener" | ✅ Pass |
| Keyboard navigation works | ✅ Pass |
| Escape key closes mobile menu | ✅ Pass |

---

## 16. BUGS FOUND DURING TESTING

| # | Bug Description | Severity | Fixed | Fix Applied |
|---|---|---|---|---|
| BUG-01 | Timeline section closing tags missing | High | ✅ | Added missing div closing tags |
| BUG-02 | Hero photo too dominant (opacity issue) | Medium | ✅ | Adjusted gradient overlay values |
| BUG-03 | About portrait breaking card layout | High | ✅ | position:absolute + inset:0 on img |
| BUG-04 | Mobile portrait too tall at 650px | Medium | ✅ | Added min-height:420px in media query |

---

## 17. FINAL SIGN-OFF

| Section | Tested | Passed |
|---|---|---|
| Page Load | ✅ | ✅ |
| Navbar Desktop | ✅ | ✅ |
| Navbar Mobile | ✅ | ✅ |
| Hero Section | ✅ | ✅ |
| About Section | ✅ | ✅ |
| Timeline Section | ✅ | ✅ |
| Quotes Section | ✅ | ✅ |
| Awards Section | ✅ | ✅ |
| Legacy Section | ✅ | ✅ |
| Footer | ✅ | ✅ |
| Responsive 1440px | ✅ | ✅ |
| Responsive 768px | ✅ | ✅ |
| Responsive 375px | ✅ | ✅ |
| Cross Browser | ✅ | ✅ |
| Accessibility | ✅ | ✅ |
| Performance | ✅ | ✅ |

### ✅ ALL TESTS PASSED — READY FOR DEPLOYMENT

---

*Testing completed by: Hruthik | Ram Charan Tribute Project | July 2026*
