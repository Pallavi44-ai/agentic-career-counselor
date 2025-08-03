# Agentic Career Counseling Companion

### Capstone Project for the IBM SkillsBuild Program

**Presented by: Pallavi L - CMR University, Computer Science & Engineering**

---

## 1. Problem Statement

Students frequently struggle to make informed career decisions due to a fragmented landscape of guidance, a lack of deep self-awareness of their own strengths, and the rapidly changing nature of the job market.

Traditional career counseling is often difficult to scale, lacks personalization, and cannot provide real-time insights based on current industry trends. This gap results in missed opportunities, skill mismatches, and potential underemployment, preventing students from reaching their full potential in a future-ready career.

---

## 2. Proposed Solution

The proposed system is an **Agentic Career Counseling Companion**, an intelligent AI agent built on IBM watsonx.ai. It is designed to provide personalized, dynamic, and scalable career guidance. The agent analyzes a student's profile and uses live web search to access real-time labor market trends, job requirements, and necessary skills, delivering comprehensive and actionable advice.

[View the full Capstone Presentation here](./Capstone_Presentation.pdf)

---

## 3. Technology Stack

*   **Cloud Platform:** IBM Cloud
*   **AI Studio:** IBM watsonx.ai
*   **Foundation Model:** Mistral Large / IBM Granite
*   **Agent Framework:** LangGraph (via watsonx Agent Lab)
*   **Core Logic:** The agent's intelligence is defined by a detailed prompt and its ability to use external tools (Google Search, Wikipedia). The core logic is available in the [Jupyter Notebook](./agentic_career_counselor.ipynb).

---

## 4. Result and Output

The system successfully functions as a dynamic career counselor. When prompted, the agent autonomously uses its tools to research the query and provides a structured, evidence-based recommendation with sourced links.

**Example Interaction:**

![Result Screenshot](images/result-screenshot.png)

---

## 5. Future Scope

*   **Enhanced Personalization:** Integrate with university systems to securely access a student's academic records for more deeply personalized advice.
*   **Expanded Toolset:** Add tools that can connect to specific job portals like LinkedIn or Indeed for live job application links.
*   **Proactive Notifications:** Develop a system where the agent can proactively alert students to new internship opportunities or relevant workshops based on their profile.

---

## 6. IBM Certifications

This project was developed as part of the IBM SkillsBuild program.

| Certificate | Image |
| :--- | :---: |
| **Getting Started with AI** | ![AI Certificate](images/certificate-ai.png) |
| **Journey to Cloud** | ![Cloud Certificate](images/certificate-cloud.png) |
| **RAG Lab with LangChain** | ![RAG Certificate](images/certificate-rag.png) |
