# Assignment 4 — User Stories and Use Cases

## Team Members

- Nailah Sall
- Rashi Loni
- Bhavya Pant
- Wade Phillips
- Collin Barret
- Preya Patel

---

# Stakeholder Map

## Primary Stakeholders

- **Young adults:** Use the application to improve their financial literacy, understand their financial situations, develop healthy financial habits, and make informed spending and budgeting decisions.

## Secondary Stakeholders

- **Financial content administrators:** Maintain and update financial education information so that users receive accurate and relevant financial guidance.

## Hidden Stakeholders

- **Users with accessibility needs:** Need to access financial education, budgeting information, and financial coaching through assistive technologies so that they can independently use the application.
- **Privacy and security stakeholders:** Need users' financial information and AI coaching conversations to be handled according to applicable privacy and security requirements.

---

# User Stories

## US-01 — Primary

**As a young adult, I want to track my income and expenses, so that I can understand where my money is going and make more informed spending decisions.**

## US-02 — Primary

**As a young adult, I want to receive guidance about financial situations I encounter, so that I can understand my options before making financial decisions.**

## US-03 — Primary

**As a young adult, I want to track my financial habits over time, so that I can identify spending behaviors that I should maintain or change.**

## US-04 — Secondary

**As a financial content administrator, I want to update financial education information, so that users receive accurate and relevant financial guidance.**

## US-05 — Hidden

**As a user with accessibility needs, I want financial information and coaching responses to be accessible using assistive technologies, so that I can independently access the same financial resources as other users.**

---

# INVEST Self-Check

| Story | Independent | Negotiable | Valuable | Estimable | Small | Testable |
|---|---|---|---|---|---|---|
| US-01 | Yes | Yes | Yes | Yes | Yes | Yes |
| US-02 | Yes | Yes | Yes | Yes | Yes | Yes |
| US-03 | Yes | Yes | Yes | Yes | Yes | Yes |
| US-04 | Yes | Yes | Yes | Yes | Yes | Yes |
| US-05 | Yes | Yes | Yes | Yes | Yes | Yes |

---

# Use Cases

## UC-01 — Receive Financial Guidance

**Story:** US-02

**Primary Actor:** Young adult

**Secondary Actor:** AI financial coach

### Preconditions

1. The young adult has access to the application.
2. The AI financial coaching service is available.
3. The young adult has provided enough information about the financial situation for the system to provide relevant guidance.

### Main Success Flow

1. **Young adult:** Describes a financial situation or question to the AI financial coach.
2. **System:** Analyzes the information provided and identifies the financial topic or situation.
3. **Young adult:** Provides any additional information requested by the system.
4. **System:** Generates financial guidance based on the information provided.
5. **Young adult:** Reviews the guidance and available options.
6. **System:** Explains the relevant financial considerations and provides the guidance to the young adult.
7. **Young adult:** Uses the information to make an informed financial decision.
8. **System:** Records the completed coaching interaction so the young adult can refer back to it later.

### Alternate Flow

**A1. Additional information is needed**

1. The young adult provides an incomplete description of the financial situation.
2. The system identifies the missing information.
3. The system asks the young adult for the specific information needed.
4. The young adult provides the requested information.
5. The system continues with the main success flow.

### Exception Flow

**E1. AI financial coach is unavailable**

1. The young adult submits a financial question.
2. The system determines that the AI financial coaching service is unavailable.
3. The system does not provide AI-generated financial guidance.
4. The system informs the young adult that the coaching service is temporarily unavailable.

### Postcondition

The young adult receives financial guidance based on the information provided, or the system clearly indicates that guidance could not be generated if an exception occurs.

---

# Acceptance Criteria

## AC-01.1 — Main Success Flow

**Given** the young adult has access to the application and the AI financial coaching service is available,

**When** the young adult submits a financial question with the information required to understand the situation,

**Then** the system shall provide a response containing financial guidance relevant to the submitted situation.

## AC-01.2 — Exception Flow

**Given** the AI financial coaching service is unavailable,

**When** the young adult submits a financial question,

**Then** the system shall not display AI-generated guidance and shall display a message indicating that the coaching service is unavailable.

---

# Elicitation Techniques

The following elicitation techniques can be used to identify and validate stakeholder needs:

1. **Interviews:** Ask young adults about their current budgeting habits, financial challenges, financial goals, and situations where they are unsure how to manage their money.

2. **Competitive analysis:** Review existing financial education, budgeting, and financial coaching applications to identify common user needs, existing solutions, and gaps that the proposed application could address.

These techniques will help the team validate the user stories and ensure that the requirements reflect actual stakeholder needs rather than specific implementation or interface choices.