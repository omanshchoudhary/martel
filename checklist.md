# Developer focus planner – build checklist

---

## Phase 0: Project setup

- [ ] Create project folder
- [ ] Add index.html
- [ ] Add styles.css
- [ ] Add app.js
- [ ] Link css and js correctly
- [ ] Verify page loads without errors

---

## Phase 1: Base layout

- [ ] Create header container
- [ ] Add app title
- [ ] Reserve space for global timer indicator
- [ ] Create main content container
- [ ] Create basic navigation (plan / focus / log / settings)
- [ ] Ensure layout works on desktop and mobile

---

## Phase 2: Global state and persistence

- [ ] Create global state object
- [ ] Define week start date logic
- [ ] Add localStorage load function
- [ ] Add localStorage save function
- [ ] Verify state persists on refresh
- [ ] Console log state updates to confirm correctness

---

## Phase 3: Weekly planning

- [ ] Render current week (7 days)
- [ ] Add ability to select a day
- [ ] Add planned focus session input
- [ ] Add planned duration field
- [ ] Add optional minimum required time
- [ ] Add basic todo or event input
- [ ] Save plans to state
- [ ] Render planned sessions per day

---

## Phase 4: Editing rules

- [ ] Allow free editing for future days
- [ ] Detect current day
- [ ] Track number of edits for current day
- [ ] Enforce 40 percent edit limit
- [ ] Disable editing past days
- [ ] Show clear feedback when editing is blocked

---

## Phase 5: Focus session flow

- [ ] Create start focus session button
- [ ] Add custom duration input
- [ ] Add optional minimum success time input
- [ ] Start timer logic
- [ ] Implement pause and resume
- [ ] Prevent timer reset on navigation
- [ ] Persist running session on refresh

---

## Phase 6: Focus page

- [ ] Create dedicated focus page
- [ ] Display running timer clearly
- [ ] Add notes input (focus page only)
- [ ] Ensure notes update state correctly
- [ ] Keep ui calm and distraction free

---

## Phase 7: Global timer indicator

- [ ] Show timer in header when session is active
- [ ] Keep timer visible across all pages
- [ ] Ensure timer continues regardless of navigation
- [ ] Allow pause or end from indicator if needed

---

## Phase 8: Video focus feature

- [ ] Add optional video input (url or embed)
- [ ] Display video only on focus page
- [ ] Remove recommendations and distractions
- [ ] Sync video pause with focus pause
- [ ] Ensure video stops when session ends

---

## Phase 9: Ending a session

- [ ] Detect timer completion
- [ ] Allow optional notes before saving
- [ ] Save session to activity log
- [ ] Clear active session state
- [ ] Return focus page to idle state

---

## Phase 10: Activity log

- [ ] Render sessions in execution order
- [ ] Group sessions by date
- [ ] Show activity type and duration
- [ ] Show notes if present
- [ ] Add filter by activity type
- [ ] Prevent retroactive editing

---

## Phase 11: Daily evaluation logic

- [ ] Calculate total planned focus time per day
- [ ] Calculate total completed focus time per day
- [ ] Apply 60 percent completion rule
- [ ] Store numeric planned vs completed values
- [ ] Display daily status subtly (no streaks)

---

## Phase 12: Settings

- [ ] Add settings page
- [ ] Allow adjustment of default values
- [ ] Persist settings to localStorage
- [ ] Validate inputs

---

## Phase 13: Polish and closure

- [ ] Handle empty states gracefully
- [ ] Handle refresh during active session
- [ ] Fix edge case bugs
- [ ] Clean unused code
- [ ] Add comments where logic is non obvious
- [ ] Write README
- [ ] Take screenshots
- [ ] Deploy to vercel or netlify

---

## Phase 14: Frontend closure

- [ ] Vanilla js version fully complete
- [ ] No pending features
- [ ] Code is understandable after a break
- [ ] Ready for react rewrite
