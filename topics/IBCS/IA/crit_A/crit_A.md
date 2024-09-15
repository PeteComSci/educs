---
title: "IA - Criterion A"
permalink: /topics/IBCS/IA/crit_A/
---

# Criterion A: Planning

Criterion A is the foundation of your Internal Assessment (IA). It involves careful planning and setting the stage for your entire project. This criterion requires you to define the problem your client is facing, explain your rationale for the chosen solution, and establish clear, measurable success criteria that will guide your development and evaluation processes.

## Key Components of Criterion A

### 1. **The Scenario**

**What It Is:**  
The scenario is a detailed description of the problem your client is experiencing. This section should demonstrate your deep understanding of the client’s needs and the specific context in which your solution will be used.

**How to Write It:**
- **Investigate a Real Situation:** Begin by thoroughly investigating the real-world situation your client is facing. Avoid deciding on a solution before fully understanding the client’s needs.
- **Meaningful Consultation:** Engage in meaningful consultation with your client (and advisor, if applicable) before deciding on a solution. The client’s input should drive your understanding of the problem and shape your scenario.
- **Describe the Scenario:** Clearly outline the current system or process that your client is using. Identify the limitations or problems that your solution will address.

**Example:**  
If your client is a small business owner struggling with managing inventory due to manual processes that lead to errors and lost sales, your scenario might describe the inefficiencies and challenges they face, setting the stage for your automated inventory management solution.

---

### 2. **Rationale for the Solution**

**What It Is:**  
The rationale explains why the solution you propose is the most effective way to address the problem identified in the scenario. It should also justify your choice of software or tools based on the specific needs of the client.

**How to Write It:**
- **Justify Your Solution:** Clearly explain why your proposed solution is the best fit for the client’s needs. Avoid generic explanations; instead, link your rationale directly to the problem.
- **Software and Tools Justification:** Justify your choice of software, programming languages, or tools by explaining how they are particularly well-suited to solving the client’s problem.

**Example:**  
If you choose a web-based application, justify it by explaining that the client needs remote access to the system, which a web application can provide. If you select Python for its data-handling capabilities, explain why these features are critical for your solution.

---

### 3. **Criteria for Success (CfS)**

**What It Is:**  
Success criteria are the benchmarks that define what your solution must achieve to be considered successful. These criteria should be specific, measurable, achievable, relevant, and testable (SMART).

**How to Write It:**
- **Developing Strong Criteria:** Create a list of 5 to 7 specific, measurable success criteria that fully describe a functional solution. These should cover all essential aspects of your solution.
- **Link to Client Needs:** Ensure each criterion is directly linked to the client’s needs as identified in the scenario. The criteria should be realistic and achievable within the project’s scope.

---

### 🎯 Creating Measurable and Testable Success Criteria
  
Success criteria are essential benchmarks that define what your solution must achieve to be considered successful. These criteria should be clear, specific, and easy to test, providing a solid foundation for the development and evaluation of your product.

#### **1. What Makes a Good Success Criterion?**

A strong success criterion is:
- **Specific:** It clearly defines what the solution must accomplish.
- **Measurable:** It includes a concrete way to verify that the criterion has been met.
- **Achievable:** It is realistic within the project's scope, considering your skills, time, and resources.
- **Relevant:** It directly relates to solving the client's problem.
- **Testable:** It can be easily tested without ambiguity or uncertainty.

#### **2. How to Write Success Criteria**

**Step 1: Identify Key Functionalities**
- Start by listing the core functionalities your solution must provide to address the client’s problem. These should directly relate to the needs identified in your scenario.

**Example:**  
If your client needs a way to manage inventory, a key functionality might be: "The system must allow users to add, edit, and delete inventory items through a user-friendly interface."

**Step 2: Make It Measurable and Testable**
- Ensure each criterion can be easily tested with clear pass/fail results. Avoid vague metrics like "improves efficiency" or percentages that may be hard to measure precisely.

**Example:**  
"The system must allow users to generate a report of all inventory items, categorized by product type, with a single click."

**Step 3: Ensure It’s Achievable and Relevant**
- Review each criterion to ensure it is something you can realistically achieve within the project’s scope and that it directly addresses the client’s needs.

**Example:**  
"The system should automatically save any changes to inventory items without requiring a page refresh."

**Step 4: Use Concrete Actions**
- Frame your criteria in terms of concrete actions that the system will perform. This makes them easier to test and less open to interpretation.

**Example:**  
"Users must be able to reset their passwords by receiving a link via email, which leads them to a secure reset page."

#### **3. Linking Success Criteria to Your Test Plan**

Each success criterion should have a corresponding test in your test plan. This ensures that you have a clear method for verifying that your solution meets all the criteria.

**How to Do This:**
- **Create a Test Case for Each Criterion:** For each success criterion, design a test case that specifies the input, expected outcome, and how you will measure the result.
- **Document Your Tests:** In Criterion B and C, you will detail these tests and their outcomes. Keep track of your progress as you develop your solution, ensuring that each feature is tested against the relevant success criterion.

**Example Test Plan Entry:**

| Test Number | Success Criterion (Related Number)  | Input                                     | Expected Outcome                                   | Actual Outcome | Figure No. |
|-------------|-------------------------------------|-------------------------------------------|---------------------------------------------------|----------------|------------|
| 1           | 1. Add Inventory Item               | Input details for a new item: name, type, | New item appears in the inventory list immediately | Passed         | Fig. 1.1   |
|             |                                     | quantity                                  |                                                   |                |            |
| 2           | 2. Generate Inventory Report        | Click "Generate Report" button            | Report PDF downloads with all items categorized    | Passed         | Fig. 1.2   |
| 3           | 3. Password Reset Functionality     | Submit email on reset page                | Password reset link is sent to the user’s email    | Passed         | Fig. 1.3   |


#### **4. Monitoring and Adjusting Success Criteria**

As you develop your solution, revisit your success criteria regularly:
- **Prototype Testing:** As you create prototypes, test them against your success criteria to ensure you’re on the right track.
- **Adjustments:** If necessary, adjust your criteria as you gain more insight into the project’s complexity or receive feedback from your client.

---


**Why It’s Important:**  
Well-defined CfS are crucial because they guide your development process and are used to evaluate your solution in later stages (Criteria D and E). Inadequate or superficial CfS can lead to poor performance across multiple criteria.

---

### 4. **Evidence of Consultation**

**What It Is:**  
Meaningful consultation with your client (and advisor) is critical. This section shows that your planning is based on real client feedback and that your solution is tailored to their specific needs.

**How to Document It:**
- **Reference Consultations:** In your scenario and rationale, explicitly reference the feedback received during client consultations. This feedback should shape your understanding of the problem and the solution.
- **Include Evidence:** Attach detailed notes or a report from your client consultations in the appendix. Label this as "Client Consultation Notes" and refer to it in your Criterion A write-up.

**Example:**  
During your consultation, if the client emphasized the need for real-time data updates due to frequent stock level changes, mention how this feedback led you to prioritize real-time inventory management in your success criteria.

---

### **Linking to Other Criteria**

**Criterion A as the Foundation:**
- **Criterion B (Design):** Your success criteria will inform your design process, guiding the development of your solution’s architecture.
- **Criterion C (Development):** The rationale and success criteria will influence your choice of tools and techniques, ensuring that your development process aligns with the client’s needs.
- **Criterion D (Functionality and Extensibility):** In Criterion D, you will demonstrate how your solution meets the success criteria through functional testing and client feedback.
- **Criterion E (Evaluation):** Finally, in Criterion E, you will evaluate the effectiveness of your solution against the success criteria, incorporating client feedback to assess its success.

---

### **Presentation and Word Count**

- **Word Count:** Your write-up for Criterion A should be concise and to the point, with a recommended word count of fewer than 500 words (excluding the list of success criteria).
- **Formatting:** Use a consistent and professional format. All documents should be converted to PDF format before submission, and your Criterion A file should be named "Crit_A_Planning.pdf".

---

### 🔗 Links to Other Criteria

For more detailed information on the other criteria, please navigate to the corresponding pages:

- **[Criterion B: Solution Overview](/topics/IBCS/IA/crit_B/)**
- **[Criterion C: Development](#link-to-criterion-c-page)**
- **[Criterion D: Functionality and Extensibility](#link-to-criterion-d-page)**
- **[Criterion E: Evaluation](#link-to-criterion-e-page)**

---

By following these guidelines for Criterion A, you will create a strong foundation for your IA project, ensuring that your solution is well-planned, client-focused, and aligned with the IB standards. Remember, your success criteria are the backbone of your project—make sure they are specific, measurable, and directly linked to your client’s needs.
