# Execution Path: Pomodoro + AI Growth Advisor MVP

## Current Status
**Stage:** Pre-build (Idea Validated Through Lean Startup Analysis)
**Risk Level:** High (No customer validation yet)
**Next Milestone:** Ship Wizard of Oz MVP in 7 days

---

## Implementation Steps (2-Week Sprint)

### Week 1: Build + Launch Wizard of Oz MVP

#### Days 1-3: Build Core Product

**User Flow:**
1. Landing page → **Online Registration** (email + password or magic link)
2. User connects/authenticates → Access to app
3. **Timer runs locally** (client-side JavaScript)
4. After session ends → Submit work summary to server
5. Server returns **personalized advice** (manual, based on user history)

**Features to Build:**
- [ ] **Landing Page** (value prop, demo, signup CTA)
- [ ] **User Registration/Login** (email/password or magic link auth)
  - Store: user_id, email, created_at, session_count
- [ ] **Pomodoro Timer** (45-minute countdown, bell notification)
  - Runs in browser (JavaScript), no server calls during countdown
- [ ] **"Claim Insight" button** (appears after session ends)
- [ ] **User Input Form** (What did you work on during this session?)
  - Submit to server with user_id + session_data
- [ ] **Personalized Advice Display**
  - You manually write 2-3 sentences based on:
    - User's submitted work summary
    - Session count (1st session vs. 10th session = different messaging)
    - Past session topics (if returning user)
- [ ] **Analytics Setup** (Plausible/Simple Analytics)
  - Track: Signups, sessions completed, advice claimed (%), time spent reading, return visits

**Tech Stack (PHP + MySQL):**
- **Frontend:** HTML/CSS/JS + Tailwind CSS
- **Backend:** PHP (user auth, session storage, advice delivery)
- **Database:** MySQL
  - `users` table: id, email, password_hash, created_at
  - `sessions` table: id, user_id, work_summary, advice_given, completed_at, advice_claimed (boolean)
- **Hosting:** Shared hosting (Hostinger/Namecheap ~$3/month) or free tier (InfinityFree)
- **Analytics:** Simple Analytics or Plausible (privacy-focused, cheap)

**Key Architecture Decision:**
- Timer logic = **client-side** (no server load, works offline)
- Advice delivery = **server-side** (enables personalization + data collection)

**Deliverable:** Live URL on custom domain (e.g., focusadvise.app)

#### Days 4-7: Acquire 20 Beta Users
- [ ] **Reddit Posts:** r/productivity, r/getdisciplined ("Built a Pomodoro timer that gives personalized advice - need beta testers")
- [ ] **Twitter/X:** Demo video or GIF, tag 3 productivity influencers
- [ ] **Personal Network:** Message 10 friends who struggle with focus
- [ ] **Indie Hackers:** "Show IH" thread

**Goal:** 20 users complete at least 1 Pomodoro session by Day 7

---

### Week 2: Measure + Learn + Decide

#### Days 8-10: Data Collection
- [ ] **Quantitative Analysis:**
  - Sessions completed (total)
  - Advice claimed rate (target: >60%)
  - Day 2 return rate (target: >30%)
  - Average time spent reading advice
- [ ] **Qualitative Interviews (5 users minimum):**
  - "What did you think would happen when you clicked 'Claim insight'?"
  - "Did the advice change your behavior? How?"
  - "Would you pay $5/month? Why/why not?"
  - "What would make you use this daily?"

#### Days 11-14: Pivot or Persevere Decision

**Persevere Triggers (Build Phase 2):**
- ✅ Advice claimed rate >50%
- ✅ Day 2 return rate >30%
- ✅ Positive interview feedback (2+ users mention behavior change)
- ✅ Willingness to pay >50% of interviewees

**Pivot Triggers (Change Direction):**
- ❌ Advice claimed <20% → Pivot: Remove advice, focus on "best Pomodoro timer"
- ❌ High engagement but zero willingness to pay → Pivot: B2B model (managers buy for teams)
- ❌ Users ask for different advice types → Zoom-in: Specialize (e.g., "Pomodoro for creative blocks only")

---

## Phase 2: Automation (Only If Week 2 Validates)

### Week 3-4: Automate AI Backend
- [ ] **OpenAI API Integration** (GPT-4)
  - Prompt template: "Based on this work session: {user_input}, generate 2 sentences of growth-oriented advice in the style of Carol Dweck."
  - Cost analysis: ~$0.01/advice = sustainable
- [ ] **Sticky Features:**
  - Session history ("You've completed 47 Pomodoros")
  - Advice archive (revisit past insights)
  - Streaks ("5-day focus streak!")
- [ ] **Retention Optimization:**
  - Email reminder: "You haven't focused today - start a session?"
  - Push notifications (if web, use service workers)

**Metrics to Watch:**
- Day 7 retention (target: >25%)
- Day 30 retention (target: >15%)
- Average sessions per week (target: 5+)

---

## Phase 3: Monetization Test (Month 2+)

### Week 5-8: Freemium Model
- [ ] **Pricing Tiers:**
  - Free: 10 sessions/month + basic advice
  - Pro ($7/month): Unlimited sessions + advice archive + streaks
- [ ] **Payment Setup:** Stripe integration
- [ ] **Conversion Funnel:**
  - Track: Free user activation, upgrade prompts shown, free-to-paid conversion
  - Target: >5% conversion rate

**Success Criteria for Fundraising/Scaling:**
- 500+ users
- 15%+ Day 30 retention
- $200+ MRR
- 5%+ free-to-paid conversion

---

## Validation Checkpoints

### Checkpoint 1 (End of Week 1)
**Hypothesis:** People will complete Pomodoro sessions and claim advice.
**Test:** 20 users acquired, measure completion + claim rates.
**Pass:** >60% claim advice after completing session.
**Fail:** <30% claim advice → Problem isn't advice, it's the interruption.

### Checkpoint 2 (End of Week 2)
**Hypothesis:** Growth advice creates habit formation (users return).
**Test:** Track Day 2 and Day 7 return rates.
**Pass:** >30% return Day 2, >20% return Day 7.
**Fail:** <15% return → Novelty effect, not habit. Pivot needed.

### Checkpoint 3 (End of Week 4)
**Hypothesis:** Automated AI advice maintains engagement vs. manual.
**Test:** Compare retention before/after automation.
**Pass:** Retention stays flat or improves.
**Fail:** Retention drops >10% → AI advice quality insufficient.

### Checkpoint 4 (End of Week 8)
**Hypothesis:** Users will pay for premium features.
**Test:** Offer Pro tier, measure conversion.
**Pass:** >5% conversion, $200+ MRR.
**Fail:** <2% conversion → Pricing wrong or features not valuable.

---

## Resource Requirements

### Week 1 (MVP Build)
- **Time:** 25-35 hours (full-time: 4 days; part-time: 1 week)
  - Auth implementation adds ~5-8 hours vs. anonymous version
- **Tools:**
  - Code editor (VS Code or PHPStorm)
  - Hosting: Shared hosting ($3-5/month) or InfinityFree (free tier)
  - Domain ($12/year)
  - Analytics (Plausible: $9/month or Simple Analytics free tier)
  - MySQL database (included with hosting)
- **Skills Needed:**
  - PHP basics (user auth, sessions, database queries)
  - MySQL schema design
  - JavaScript (timer logic, DOM manipulation)
  - CSS/Tailwind for UI polish
  - Security basics (password hashing, SQL injection prevention)

### Week 2 (Customer Research)
- **Time:** 10 hours (user interviews + data analysis)
- **Tools:**
  - Calendly (schedule interviews)
  - Notion/Spreadsheet (track metrics)
  - Loom (record demo for acquisition)

### Week 3-4 (Automation)
- **Time:** 15-20 hours
- **Costs:**
  - OpenAI API: ~$20/month (for 100-200 users)
  - Email service: Resend or Loops (free tier)
- **Skills Needed:**
  - API integration
  - Prompt engineering
  - Database setup (Supabase free tier or Firebase)

---

## Success Metrics (Innovation Accounting)

### Baseline (Week 2)
- Users: 20
- Sessions completed: [MEASURE]
- Advice claimed: [MEASURE]%
- Day 7 retention: [MEASURE]%

### Week 4 Target (With Automation)
- Users: 100 (5x growth)
- Advice claimed: >50%
- Day 7 retention: >25%
- Paying users: 3-5 (early testing)

### Week 8 Target (Monetization Phase)
- Users: 500
- Day 30 retention: >15%
- MRR: $200+
- LTV:CAC ratio: >3:1

### Month 6 Target (If All Validates)
- Users: 5,000
- MRR: $3,000+
- Ready for seed fundraising or expansion to "Researcher" advisor

---

## What We're NOT Building (Until Data Says Otherwise)

❌ **Personality profiling** (Helen Fisher, Jungian Archetypes)
❌ **Multiple AI advisors** (Researcher, Administrator)
❌ **Tool integrations** (Calendar, screen tracking)
❌ **Mobile apps** (Web-first until retention proven)
❌ **Complex user dashboards** (Focus on single use case)

**Rationale:** These are "Year 2+" features. Building them now = wasting 6-12 months before learning if anyone wants the core product.

---

## Risk Mitigation

### Risk 1: No one completes Pomodoro sessions
**Mitigation:** Make timer delightful (animations, sound options). If still fails, pivot to passive tracking.

### Risk 2: Advice is ignored/not read
**Mitigation:** A/B test formats: 1 sentence vs. 3 sentences, bullet points vs. prose, question vs. statement.

### Risk 3: Manual advice is too time-consuming
**Mitigation:** Create template library (20 pre-written insights), personalize with user's input keywords.

### Risk 4: Can't acquire 20 users
**Mitigation:** Lower bar to 10 users. Quality of learning > quantity at this stage.

### Risk 5: OpenAI API costs spiral
**Mitigation:** Set hard monthly cap ($50), implement caching for similar inputs, use GPT-3.5 instead of GPT-4 if quality sufficient.

---

## Decision Tree (End of Week 2)

```
Week 2 Results
    |
    ├─ Advice Claimed >50% + Return >30%
    |   └─> PERSEVERE: Build Phase 2 (automation)
    |
    ├─ Advice Claimed >50% + Return <15%
    |   └─> PIVOT: Advice format (test 1-sentence micro-nudges)
    |
    ├─ Advice Claimed <30% + Return <15%
    |   └─> PIVOT: Remove advice, become "best Pomodoro timer"
    |
    └─ Timer not used at all (<10 sessions completed)
        └─> KILL: Core concept invalid, return to idea discovery
```

---

## Database Schema (MySQL)

```sql
-- Users table
CREATE TABLE users (
  id INT AUTO_INCREMENT PRIMARY KEY,
  email VARCHAR(255) UNIQUE NOT NULL,
  password_hash VARCHAR(255) NOT NULL,
  created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
  last_login TIMESTAMP NULL,
  session_count INT DEFAULT 0,
  INDEX(email)
);

-- Sessions table
CREATE TABLE sessions (
  id INT AUTO_INCREMENT PRIMARY KEY,
  user_id INT NOT NULL,
  work_summary TEXT,
  advice_given TEXT,
  completed_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
  advice_claimed BOOLEAN DEFAULT FALSE,
  time_spent_reading INT DEFAULT 0, -- seconds
  FOREIGN KEY (user_id) REFERENCES users(id) ON DELETE CASCADE,
  INDEX(user_id),
  INDEX(completed_at)
);

-- Optional: User preferences (for future personalization)
CREATE TABLE user_preferences (
  user_id INT PRIMARY KEY,
  preferred_session_length INT DEFAULT 45, -- minutes
  notification_enabled BOOLEAN DEFAULT TRUE,
  FOREIGN KEY (user_id) REFERENCES users(id) ON DELETE CASCADE
);
```

**Personalization Strategy (Manual Phase):**
- **1st session:** Generic welcome advice ("You just completed your first focus session...")
- **Sessions 2-5:** Encouragement + pattern recognition ("You've completed X sessions this week...")
- **Sessions 6+:** Tailored to work_summary keywords + past topics
- **Returning after gap:** Re-engagement messaging ("Welcome back! It's been X days...")

**Data for Manual Advice Writing:**
When a user submits, you see:
- Current session: work_summary
- User history: session_count, last topics (query last 5 sessions)
- Time patterns: sessions_today, sessions_this_week

This gives you context to write personalized advice manually before automating.

---

## Next Immediate Action (Within 48 Hours)

1. **Decide:** Commit to 2-week sprint? (Y/N)
2. **Sketch:** Wireframe the 4-screen flow (landing → login/register → timer → claim insight → advice display)
3. **Database:** Set up MySQL (local dev: XAMPP/MAMP, or hosting account)
4. **Write:** Draft 10 example "growth insights" for different scenarios:
   - First-time user
   - Returning user (session 5+)
   - User who works on same topic repeatedly
   - User returning after 3+ day gap
5. **Plan:** Block calendar for 4 full days (or 8-10 part-time days) to build

**The clock starts when you commit.**

---

## Contact for Validation Interviews

Once you have 5+ users, share:
- Calendly link ("15-min feedback call")
- Incentive: "Get 1 month Pro free for participating"
- Questions doc (prepared in advance)

**Goal:** Learn what advice resonates, what feels generic, what triggers behavior change.

---

## Future Expansion (Only After $3k+ MRR)

### The Researcher (Phase 4)
**Concept:** AI scans latest papers, generates personalized learning podcasts
**Prerequisites:** 1,000+ active users, validated demand for learning content
**MVP Test:** Weekly email with 3 research summaries, measure open + click rates

### The Administrator (Phase 5)
**Concept:** Automate administrative drag (taxes, insurance, document organization)

**First MVP: Invoice Organizer**
- **Problem:** Freelancers/small business owners waste hours finding invoices for taxes
- **Solution:** Gmail → Drive automation (scan for invoices, organize by date/vendor)
- **Tech:** Google Apps Script (3-day build) or OAuth web app
- **Validation:**
  - Test with 10 freelancers during tax season
  - Success: >70% complete first scan, >50% would pay $5-10/month
- **Competitors:** Expensify ($10/month), QuickBooks ($15/month), Shoeboxed ($18/month)
- **Moat:** Simpler UX, no transaction linking required, lower price point
- **Prerequisites:**
  - Proven ability to retain users (Pomodoro retention >20%)
  - Legal review for tax compliance claims
  - Understanding of accounting/tax workflows

**Expanded Administrator Features (if invoice tool validates):**
- Insurance policy aggregator (scrape emails, centralize policies)
- Property document vault (deeds, warranties, manuals)
- Tax deduction tracker (integrate with bank APIs)

**Build trigger:** Customer requests or survey data showing >40% want admin automation

### Personality Profiling (Phase 6+)
**Concept:** Helen Fisher Temperament + Jungian Archetypes for personalized advice
**Prerequisites:** Data showing advice quality correlates with profile depth
**Build trigger:** A/B test generic vs. personalized advice, measure engagement lift

### Mobile Apps (Phase 7+)
**Prerequisites:** Web retention >20% at Day 30, >5,000 active users
**Rationale:** Mobile development is 3x slower; validate web-first

### Enterprise/B2B (Phase 8+)
**Build trigger:** >30% of paying users are managers buying for teams
**Pivot:** Team dashboards, manager insights, bulk licensing

---

**Principle:** Earn the right to build complexity through validated user demand. Each expansion must pass its own MVP test before full build.

---

*This execution path prioritizes learning over building. Every step tests an assumption. Every metric drives a decision. Ship fast, learn faster, pivot without ego.*
