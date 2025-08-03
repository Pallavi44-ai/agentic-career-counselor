# Agentic Career Counseling Companion

### Capstone Project for the IBM SkillsBuild Program

**Presented by: Pallavi L - CMR University, Computer Science & Engineering**

---

## 1. Problem Statement

Students frequently struggle to make informed career decisions due to a fragmented landscape of guidance, a lack of deep self-awareness of their own strengths, and the rapidly changing nature of the job market.

Traditional career counseling is often difficult to scale, lacks personalization, and cannot provide real-time insights based on current industry trends. This gap results in missed opportunities, skill mismatches, and potential underemployment, preventing students from reaching their full potential in a future-ready career.

---

## 2. Proposed Solution

The proposed system is an **Agentic Career Counseling Companion**, an intelligent AI agent built on IBM watsonx.ai. It is designed to provide personalized, dynamic, and scalable career guidance. The solution consists of the following components:

*   **Student Profile Analysis:** The agent processes user inputs regarding academic performance, interests, and skills.
*   **Real-time Data Retrieval:** It utilizes external tools to access live labor market data, including job roles and required skills.
*   **Agentic AI Core:** An agentic system using a foundation model autonomously reasons, plans, and uses its tools to formulate comprehensive advice.
*   **User Interaction:** A conversational interface allows students to ask natural language questions and receive detailed, actionable guidance.

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

The system successfully functions as a dynamic career counselor. When prompted, the agent autonomously uses its search tools to research the query and provides a structured, evidence-based recommendation with sourced links.

**Example Interaction:**

*A user asks for the top skills needed for a career in sustainable energy technology.*

![Result Screenshot 1](./images/result-screenshot-1.png)

*The agent continues its detailed response, providing further skills and resources.*

![Result Screenshot 2](./images/result-screenshot-2.png)

---

## 5. Future Scope

*   **Enhanced Personalization:** Integrate with university systems to securely access a student's academic records for more deeply personalized advice.
*   **Expanded Toolset:** Add tools that can connect to specific job portals like LinkedIn or Indeed for live job application links.
*   **Proactive Notifications:** Develop a system where the agent can proactively alert students to new internship opportunities or relevant workshops based on their profile.
*   **Multi-language Support:** Expand the agent's capabilities to offer guidance in multiple languages to support a more diverse student population.

---

## 6. IBM Certifications

This project was developed as part of the IBM SkillsBuild program, and the following certifications were completed during the coursework.

| Certificate | Image |
| :--- | :---: |
| **Getting Started with Artificial Intelligence** | ![AI Certificate](./images/certificate-ai.png) |
| **Journey to Cloud: Envisioning Your Solution** | ![Cloud Certificate](./images/certificate-cloud.png) |
| **Lab: Retrieval Augmented Generation with LangChain** | ![RAG Certificate](./images/certificate-rag.png) |
