# X-in-Flow
Cognitive Energy Tracker & Personalized Focus Agent

**Xin Flow** is a biohacker-style cognitive energy system designed for rational self-optimizers.  
It helps users **understand**, **optimize**, and **protect** their mental energy throughout the day —  
by analyzing physiological and behavioral signals, predicting peak focus periods, and guiding attention practices.

---

## ✨ Core Value

**X-in Flow** is your cognitive energy assistant, designed to:

- Maximize mindflow and deep focus
- Guide personalized focus training (breathing, stress relief, emotional control)
- Detect and reduce energy leakage (notifications, mental clutter)
- Track and visualize your mental energy in real time


---

## 👤 Target User

> 🧬 Rational self-optimizers who care about mental performance, body-mind rhythms, and long-term cognition density.

---

## 🧭 System Overview
```scss
 ┌───────────┐             ┌────────────┐
 │   LOOP A  │──────data──▶│   LOOP B    │─────tasks────▶LOOP C
 │  Sensing  │◀──feedback──│ Scoring AI  │◀────actions──│ Interventions │
 └───────────┘             └────────────┘               └──────────────┘

  (sleep / food / HR / caffeine / chat logs)   →   (focus · stamina · emotion) → (breath / coaching / filtering)
```


---

## 🧠 Agent Architecture

### 1. `AssessAgent`  
- **Passive sensing**:  
  - Sleep duration  
  - Heart rate variability  
  - App usage & screen time  
- **Active input**:  
  - Diet, caffeine, chat interaction logs  
- **Output**:  
  - Scoring on **Cognitive Energy**, **Physical Stamina**, **Emotional Stability**

---

### 2. `ShortGoalPredictionAgent`  
- Predict short-term mental performance goals  
- (Optional) incorporate long-term goals into planning

---

### 3. `PlanAgent`  
- Generate personalized **focus routines**  
    - Breathwork  
    - Mental cueing / affirmation  
    - Pressure resilience drills  
    - Emotional regulation  
- Detect & reduce **energy leaks**:  
    - Repetitive decisions  
    - Inbox/message overload  
    - Task switching

---

### 4. `TrackingAgent`  
- Detect **anomalies** and **spikes** (e.g. all-nighter, caffeine crash, mood dip)
- Trigger reflection or recovery protocol

---

## 🔭 Long-Term Goal

> Help users identify **Peak Hours** and **Energy Sinkholes**.  
> Build an intelligent assistant that **learns your rhythm** and guides you toward higher cognitive output density.

---

## 🛠 Tech Stack (TBD / WIP)

- LLM-based multi-agent planning (OpenAI + structured prompts)
- HealthKit / Google Fit API for data
- Lightweight React Native app (or Notion-style front-end for MVP)

---

## 📌 Status

- [ ] `AssessAgent` prototype (in progress)
- [ ] Daily energy log interface
- [ ] Prompt framework for focus planning
- [ ] Basic anomaly detector (TrackingAgent)

---

## 📄 License

Open-source for research and educational purposes.  
Inspired by behavioral science books like _Good Energy_, _The Inner Game of Tennis_, _Deep Work_, and _Atomic Habits_.


