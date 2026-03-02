# Project Auto-Remediate: Debugtionary

An AI-powered solution designed for autonomous diagnosis and remediation, acting as a crucial force multiplier by redirecting specialized talent toward critical, evolving threats.

---

## Inspiration
Frustrated by the inefficiency of repetitive tasks at the Tier 1 Help Desk, our aspiration in specialized cybersecurity fueled the creation of Project Auto-Remediate. We aimed to bridge the gap between manual troubleshooting and automated response.

## What it does
* **Intelligent Input:** Users can input any error code, error name, or faulty code snippet.
* **AI-Driven Analysis:** The platform provides a detailed explanation of possible issues and specific solutions for each.
* **Natural Language Troubleshooting:** If an error is unknown, a separate input box allows users to describe the technical issue in plain English to receive a full diagnosis and next steps.
* **Community Collaboration:** Features a dedicated chatroom where IT professionals can collaborate and share best practices.

## How we built it
* **Backend & Data:** Used Firebase to store and analyze real-world help desk data, providing a foundation for testing our diagnostic process.
* **NLP Engine:** Integrated the Gemini API for advanced Natural Language Processing to accurately identify and interpret technical issues.
* **Automation Layer:** Created a secure trigger mechanism to launch validated corrective scripts through remote management tools for immediate remediation.
* **Frontend:** Developed the interface using HTML and VS Code, connecting the front and back end for a seamless user experience.

## Challenges we ran into
This project was a significant learning curve for our team:
* **Firebase Architecture:** Navigating inexperience with Firebase, specifically regarding real-time state management.
* **Asynchronous Flow:** Designing an architecture to properly call the Gemini API and manage its asynchronous output without interrupting the user flow.
* **Trigger Mechanisms:** Researching how to use a database as a trigger mechanism for launching our corrective automation programs.

## Accomplishments that we're proud of
We are proud of building a fully functional project using a tech stack we had no prior experience in. This was achieved through extensive research and a collaborative building mindset.

## Built With
* Firebase (Database & Hosting)
* Gemini API (AI & NLP)
* HTML5
* VS Code

## Try it out
Visit the live project here: [debugtionary.web.app](https://debugtionary.web.app)
