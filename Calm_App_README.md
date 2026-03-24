# Calm App — Product Design Sprint: SOS Stress Relief Feature

**Course:** MGMT 275 — Product Management in Tech Companies | UCLA Anderson School of Management  
**Team:** Sai Subramanian · Pranav Piedy · Shivathmika · Tiffany · Sophia

---

## Overview

This project is a product design sprint for [Calm](https://www.calm.com/), the leading meditation and mental wellness app. We identified a critical gap in Calm's product experience: **users in moments of acute stress don't think to open a wellness app**, and when they do, the path to relief is buried under too many options.

We designed, prototyped, and user-tested an **SOS Stress Relief feature** — a low-friction, science-backed intervention system that meets users at their moment of need and guides them from distress to calm in under 3 minutes.

---

## Problem Statement

Calm excels at long-term habit formation (meditation, sleep stories), but struggles with **short-term, acute stress relief**. When users are anxious, overwhelmed, or can't sleep, they default to dopamine-driven coping (doom-scrolling, YouTube) rather than opening Calm — because:

1. **High friction:** Existing breathing exercises and SOS content are buried 3–4 taps deep
2. **Low motivation:** Users in acute distress lack the cognitive bandwidth to navigate options
3. **No behavioral bridge:** There's nothing between "I'm stressed" and "do a 10-minute meditation"

---

## Our Approach

### Design Sprint Process

1. **User Journey Mapping** — Mapped end-to-end journeys for two core Jobs-To-Be-Done: "Help me fall asleep now" and "Help me feel less anxious now." Identified actions, needs, and pain points at each stage.

2. **Pain Point Prioritization** — Scored three candidate problem areas on feasibility, customer value, business viability, and usability. Short-term stress relief scored highest (8/10, 9/10, 9/10, 8/10).

3. **Competitive Analysis** — Evaluated Headspace (similar friction issues), Wysa/Woebot (niche but small audience), and real-world coping behaviors (Instagram, YouTube — dopamine-driven, ultimately counterproductive).

4. **Ideation & Solution Design** — Generated solutions across three layers: Access, Personalization, and Intervention. Converged on a three-component architecture.

5. **Prototyping & User Testing** — Built interactive prototype, conducted user interviews, and synthesized learnings.

---

## Proposed Solution: Three-Component Architecture

### 1. SOS Button (Access Layer)
A persistent, high-visibility button on Calm's home screen for immediate emotional support. Designed to eliminate navigation friction entirely. Extended entry points include a home screen widget and smartwatch triggers (elevated heart rate → proactive prompt).

### 2. DOSE Bridge (Transition Layer)
A neurochemically-informed transition that moves users from dopamine-seeking behavior toward emotional regulation:
- **Dopamine:** Safe stimulation (comedy clips, favorite songs)
- **Oxytocin:** Connection (messages/photos from loved ones)
- **Serotonin:** Regulation (guided prompts)
- **Endorphins:** Relief (physical micro-exercises)

*Note: Conceptualized but not built in prototype due to time constraints. Remains a key future iteration.*

### 3. Scientific Grounding (Intervention Layer)
Evidence-based breathing and CBT techniques following a three-stage structure:
1. **Release** — Discharge emotional intensity
2. **Regulation** — Stabilize via paced breathing (box breathing, 4-7-8, physiological sigh)
3. **Anchor** — Somatic or reflective closure

Users are routed based on emotional state selection (Frustrated, Anxious, Scared, Lonely, Overwhelmed, Low Self-Esteem, or "I don't know how I feel").

---

## Experiment Design & Success Metrics

| Metric | What It Measures |
|---|---|
| **Customer Acquisition** | Does short-term stress relief attract new users to Calm? |
| **Feature Discoverability** | Can users find the SOS button when stressed? |
| **Process Completion Rate** | Do users complete the full grounding flow? |
| **Habit Formation** | Do users return to SOS consistently during acute stress? |
| **Retention Impact** | Do SOS users show higher 30/60/90-day retention vs. non-users? |

---

## Key Findings from User Testing

- **Help-seeking is not instinctive.** Users don't naturally reach for a wellness app when stressed — they default to music or scrolling. This is a behavioral barrier, not just a UX problem.
- **SOS discoverability needs work.** The red color treatment felt "alarming" rather than reassuring. Placement lacked visual dominance on a content-dense home screen.
- **Emotion mapping creates friction.** Users struggled to categorize their feelings into preset options — validating our "I don't know" fallback pathway.
- **Interventions were emotionally effective.** Despite UX friction, breathing exercises and grounding techniques produced measurable stress reduction across all participants.
- **Users expect post-regulation continuity.** The journey felt incomplete after breathing — users wanted seamless transition to music, sleep stories, or reflective content.
- **Context matters.** The feature was perceived as more useful for nighttime decompression than high-pressure work stress — suggesting different trigger mechanisms for different contexts.

---

## Edge Cases Considered

- User in acute panic (can't label emotions) → "I don't know" pathway routes to generalized grounding
- Repeated use causing novelty decay → Content freshness strategy needed for DOSE Bridge
- Smartwatch false positives (elevated heart rate from exercise, not stress) → Contextual filtering required
- Users who abandon mid-flow → Checkpoint system to resume where they left off

---

## What We'd Do Differently

1. **Validate behavioral assumptions before building** — Test whether users actually open Calm when stressed before designing the in-app flow
2. **Lean harder on existing UX research** — Use established emergency/wellness UI patterns for SOS placement and color treatment
3. **Test the testing environment** — Run internal pilots to calibrate stress-induction setup before live sessions
4. **Stay macro** — We over-indexed on micro-interactions at the expense of the broader emotional journey
5. **Integrate AI as orchestration** — Use AI to detect emotional tone and dynamically personalize grounding pathways, not just as a static interface element

---

## Tools & Methods

- **Collaboration:** Mural (user journey mapping, ideation, clustering)
- **Frameworks:** Jobs-To-Be-Done, DOSE neurochemical model, CBT-based intervention design
- **Prioritization:** Feasibility × Customer Value × Business Viability × Usability scoring matrix
- **Prototyping:** Interactive app prototype with emotion-based routing
- **Research:** User interviews, competitive analysis, secondary research on stress intervention science

---

## Repository Contents

```
├── README.md                    ← This file
├── Group3_Final_Project_Report  ← Full design sprint report with appendix
├── Prototype/                   ← Interactive prototype files
└── User_Research/               ← Interview notes and video links
```

---

## Links

- [Product Sprint Working Board (Mural)](https://app.mural.co/t/dataing7514/m/dataing7514/1770342155914/2c074bd6e10850be67ccb7169b252c9fc463ca97)
- [User Interview Notes](https://docs.google.com/document/d/10N3TzKd4b4TZFH644k7YApb-B8WFuaqF7JuzOd2tOOg/edit)
- [User Interview Video](https://photos.app.goo.gl/e1pdBxJqbH18gLbe8)
