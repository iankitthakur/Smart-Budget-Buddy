# Smart Budget Buddy -- AWS Bedrock Agent Project

## Overview

Smart Budget Buddy is a friendly, student‑focused financial literacy
agent built using **AWS Bedrock Agents**. Its purpose is to help
students create simple budgets, understand their spending, and develop
healthy money habits --- all while ensuring safety, fairness, and
responsible AI behavior.

This project demonstrates the agent setup, guardrail configuration,
evaluation tests, and reflections on performance.

------------------------------------------------------------------------

## 1. Agent Details

**Agent Name:** Smart-Budget-Buddy\
**Created By:** Ankit Thakur

**Agent Purpose:**\
A supportive assistant that helps students with: - Basic budgeting\
- Saving strategies\
- Allowance planning\
- Simple financial literacy concepts

It avoids complex investment, legal, or unsafe financial topics and
redirects users responsibly.

------------------------------------------------------------------------

## 2. Guardrail Configuration

The project includes guardrails designed to: - Block harmful, unethical,
illegal, or offensive content\
- Prevent the agent from giving financial, legal, or professional
investment advice\
- Maintain an inclusive, respectful, and student‑friendly tone\
- Ensure responses stay within safe and appropriate boundaries

------------------------------------------------------------------------

## 3. Agent Builder Setup

The Smart Budget Buddy was configured in the AWS Bedrock Agent Builder
with: - Clear agent instructions\
- Defined safety guardrails\
- Testing via conversation evaluations\
- Screenshots demonstrating configuration screens

------------------------------------------------------------------------

## 4. Evaluation Conversations

### ✔ Successful Use Case

A student asked for help creating a simple monthly budget.\
Smart Budget Buddy responded: - Clearly\
- Politely\
- Within scope\
- Using easy‑to‑understand explanations\
- Avoiding unsafe suggestions

### ⚠ Edge Case 1 -- Investment Advice Request

**Test:** User requested specific investment strategies.\
**Result:**\
The agent refused, clarified its limitations, and recommended consulting
a financial professional.

### ⚠ Edge Case 2 -- Offensive / Illegal Request

**Test:** User sent harmful or unethical language and requests.\
**Result:**\
The agent blocked unsafe content, responded politely, and encouraged
respectful communication.

------------------------------------------------------------------------

## 5. Reflection

### What Worked Well

-   Explanations were simple and friendly\
-   The agent stayed within its safe boundaries\
-   Guardrails effectively blocked unsafe requests\
-   Responses were suitable for students

### Improvements for the Future

-   Add support for more complex financial scenarios\
-   Enable memory to personalize advice\
-   Expand budgeting templates and examples

### Responsible AI Principles Followed

-   **Fairness:** Unbiased, student‑friendly advice\
-   **Transparency:** Clear boundaries on what the agent can and cannot
    do\
-   **Safety:** Strong guardrails to prevent harmful outputs\
-   **Privacy:** Avoids collecting personal information

------------------------------------------------------------------------

## Conclusion

This project showcases the design, safety practices, and evaluation of a
responsible financial‑literacy agent using AWS Bedrock. Smart Budget
Buddy provides a safe and positive learning experience for students
while demonstrating responsible, guardrail‑driven AI design.
