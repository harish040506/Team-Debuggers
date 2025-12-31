# Team-Debuggers
Repository for AI-VERSE Hackathon (Anokha - 2026)

# Career Compass – Agentic AI Career Readiness Platform

**Track:** Agentic AI  
**Category:** Career Intelligence & Decision Support  
**Status:** Idea + Partial Implementation  

---

## 1. Overview

Career Compass is an AI-driven career readiness and diagnosis platform designed for final-year students and early-career professionals preparing for technical roles.

Instead of providing generic career advice or isolated test scores, Career Compass uses a comparison-based evaluation approach. The system benchmarks a user’s profile against profiles of candidates who actually get selected and surfaces hidden gaps that traditional tools fail to reveal.

The platform follows an Agentic AI paradigm, where the system continuously understands the user’s profile, reasons over skills and role requirements, plans improvement actions, and provides actionable feedback.

---

## 2. Problem Statement

Hiring today operates as a black box.

Many candidates meet job requirements and perform reasonably well in tests, yet face repeated rejections without clear feedback. Existing platforms focus on resume scoring or aptitude tests but fail to explain how candidates compare against real competition.

The core problem is the lack of comparative insight in career evaluation.

---

## 3. Core Insight

Rejection is relative, not absolute.

Candidates are evaluated against other candidates, not in isolation. Without understanding this comparison, users cannot identify the real gaps blocking their selection.

Career Compass explicitly models this comparison.

---

## 4. Our Approach

### Digital Twin vs Ghost Twin Framework

- **Digital Twin:**  
  A structured representation of the user’s profile, including skills, education, role preferences, and assessment performance.

- **Ghost Twin:**  
  An aggregated representation derived from profiles of candidates who have successfully cleared hiring processes.

By comparing these two representations, the system identifies skill gaps, role-readiness mismatches, and hidden deficiencies that are not visible in standalone evaluations.

---

## 5. Dataset Utilized

The project uses the **Entity Recognition in Resumes** dataset from Kaggle (JSON format).

The dataset includes labeled resume entities such as:
- Skills  
- Designation / Role  
- Education details  
- Experience and company mentions  
- Location and contact metadata  

This enables structured resume parsing and comparative profile construction.

---

## 6. System Capabilities

- AI-based resume analysis for skill extraction  
- Digital Twin–based career gap diagnosis  
- Role-specific guidance and resume tailoring  
- 3-level adaptive skill assessment framework  
- Level-based feedback with targeted improvement suggestions  
- AI-powered mock interview module for communication evaluation  

The LLM component is used for reasoning and explanation, not as the core decision logic.

---

## 7. Agentic AI Alignment

Career Compass follows a Think → Plan → Act loop:

- **Think:** Analyze user profile and assessment outcomes  
- **Plan:** Identify gaps and decide next evaluation steps  
- **Act:** Deliver assessments, feedback, and readiness guidance  

This enables adaptive behavior instead of static responses.

---

## 8. Current Implementation Status

This project is partially implemented.

Completed and in-progress components include:
- Resume parsing and entity extraction logic  
- Assessment flow design with level-based progression  
- UI mockups and prototype user journey  
- Initial backend logic and architecture setup  

Screenshots and demo visuals are included for reference.

---

## 9. Planned Enhancements

- Full Digital Twin vs Ghost Twin comparative scoring  
- Success Probability estimation based on benchmark gaps  
- Expanded interview evaluation and feedback loop  
- Iterative improvement tracking across attempts  

---

## 10. Why This Solution is Different

Career Compass differs from existing platforms by:
- Explaining rejection in a comparative context  
- Using real selection benchmarks instead of generic advice  
- Focusing on diagnosis before guidance  
- Treating career readiness as an evolving, adaptive process  

---

## 11. Conclusion

Career Compass aims to transform career preparation from guesswork into an explainable, data-driven process. By modeling both the candidate and the competition, the system provides clarity where existing tools fall short.

This project demonstrates a structured application of Agentic AI for real-world decision support.

