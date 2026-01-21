# Product requirements document  
## Developer focus planner and execution log

---

## 1. Product overview

This product is a focus first productivity tool designed for developers who want to plan their work honestly and execute with intent.

It is not a habit tracker, not a streak based app, and not an analytics heavy productivity system.

The core purpose is simple:
- plan your week
- focus deeply
- log what actually happened
- keep everything in one calm place

---

## 2. Target user

- individual developers
- students or professionals
- people who value deep work over gamification
- users who want honesty instead of motivation tricks

---

## 3. Core philosophy

- no streaks
- no badges
- no scores
- no pressure

The app reflects reality instead of trying to manipulate behavior.

---

## 4. Core concepts

### 4.1 Focus sessions

A focus session is a time based block of deep work.

Each focus session includes:
- activity type (for example: project, dsa, learning, custom)
- actual duration tracked by a timer
- optional notes
- timestamp and date

Sessions can be started at any time and in any quantity.

---

### 4.2 Weekly planning

Planning is done on a weekly basis.

For each day, the user can plan:
- focus sessions with optional minimum required duration
- basic todos or events (not time based)

Planned focus sessions contribute to daily evaluation.
Basic todos are only reminders and do not affect evaluation.

---

### 4.3 Editing rules

- future days can be edited freely
- current day planning can only be modified up to 40 percent
- past days cannot be edited

Execution is never blocked.
Only planning integrity is protected.

---

### 4.4 Completion logic

Daily completion is time based.

A day is considered honored if:
- the user completes more than 60 percent of the total scheduled focus time

No streaks are tracked.
Only numeric records are stored:
- planned focus time
- completed focus time

---

## 5. Focus session flow

### 5.1 Starting a session
- user opens the app
- user chooses to start a focus session
- user enters custom duration
- optional minimum time for success can be set
- focus session starts

---

### 5.2 During a session
- a dedicated focus page is shown
- notes are available on the focus page only
- timer never stops unless paused manually
- user can navigate to other pages
- a persistent timer indicator is visible in the header

---

### 5.3 Ending a session
- when the timer ends, the session is finalized
- user can add optional notes
- session is saved to the log
- focus page returns to default idle state

---

## 6. Video focus feature (v1)

- user can optionally attach a video to a focus session
- video is shown without recommendations or distractions
- no ads related features are added by the app
- video pauses if the focus session is paused
- video is only accessible inside the focus page

This feature is optional and minimal.

---

## 7. Activity log

- sessions are displayed in actual execution order
- no artificial reordering based on plans
- filtering by activity type is supported
- sessions can be viewed but not altered retroactively

---

## 8. Non goals

The product will not include:
- streaks
- gamification
- leaderboards
- social features
- heavy analytics dashboards
- backend or authentication

---

## 9. Future expansions (not v1)

- automated coding metrics (lines of code, hours, language wise)
- ide or browser extensions
- public accounts or syncing

These are explicitly out of scope for v1.

---

## 10. Definition of done

The product is considered complete when:
- weekly planning works correctly
- focus sessions persist across refresh
- daily completion logic is accurate
- editing constraints are enforced
- ui remains calm and distraction free
- codebase is clean and explainable
