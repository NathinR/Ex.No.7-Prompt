# **Ex. No: 7 – Prompt-Based Application using ChatGPT**

## **Aim**

To develop a prompt-based application using ChatGPT - To demonstrate how to create a prompt-based application to organize daily tasks, showing the progression from simple to more advanced prompt designs and their corresponding outputs.

---

## **AI Tools Required**

* ChatGPT (GPT-5 / GPT-4)
* OpenAI Playground (optional)
* Python (for API integration – optional)
* Visual Studio Code / Any Text Editor
* Google Colab / Jupyter Notebook (for simulation)
* Internet Browser

---

## **Introduction**

Prompt-based applications use **Large Language Models (LLMs)** to respond intelligently to natural language inputs. These models are trained on vast datasets and can generate human-like responses, perform reasoning, and adapt based on user input.
By designing **structured prompts**, we can turn ChatGPT into a virtual assistant capable of managing tasks, scheduling events, offering wellness tips, and answering general queries — much like a personal productivity companion.

In this experiment, the focus is to design, develop, and test various prompts to simulate **a multifunctional personal productivity assistant**, starting from simple reminders to advanced adaptive systems.

---

## **Concept Overview**

| Concept                        | Description                                                                                        |
| ------------------------------ | -------------------------------------------------------------------------------------------------- |
| **LLM (Large Language Model)** | An AI system that understands and generates human language.                                        |
| **Prompt Engineering**         | The art of crafting instructions to guide AI outputs.                                              |
| **Context Awareness**          | The ability of AI to understand past interactions.                                                 |
| **Memory Simulation**          | Mimicking user preference retention through dynamic prompts.                                       |
| **Practical Application**      | Using ChatGPT to automate real-life tasks like scheduling, wellness monitoring, or study planning. |

---

## **Explanation**

Prompt:

> "Design a personal productivity assistant that can help manage daily tasks, schedule reminders, suggest wellness tips, and answer general queries. The assistant should interact using natural language and be adaptable to the user’s changing preferences over time."

---

## **Procedure**

1. **Define the core requirements of a personal productivity assistant.**
2. **Identify and construct appropriate prompts** for each task using an LLM (e.g., ChatGPT).
3. **Simulate natural user interaction** through a simple interface or command-line system.
4. **Collect feedback or inputs** from users and adapt responses accordingly.
5. *(Optional)* **Integrate basic memory** to simulate preference adaptation.

---

## **Core Requirements**

A personal productivity assistant must:

* Understand natural language input.
* Manage daily schedules and tasks.
* Offer reminders and notifications.
* Generate personalized wellness advice.
* Maintain adaptability and user personalization.

---

## **Phase 1 – Simple Prompt Interaction**

### **Prompt Example 1: Basic Reminder**

```
Remind me to attend my AI class at 10 AM tomorrow.
```

**Output:**

> "Sure! I’ll remind you to attend your AI class at 10 AM tomorrow."

### **Prompt Example 2: Adding Priority**

```
Remind me to finish the cybersecurity project by 5 PM, mark it as high priority.
```

**Output:**

> "Got it! I’ve marked your cybersecurity project as a high-priority task for 5 PM."

---

## **Phase 2 – Intermediate Level Prompts**

### **Prompt Example 3: Study Time Scheduler**

```
Create a 5-day study plan for Cybersecurity, Java, and Data Structures. Include breaks.
```

**Output:**

> Generates a structured 5-day schedule with 2-hour sessions, small breaks, and revision tips.

### **Prompt Example 4: Task Breakdown**

```
Break down my final-year project on AI Music Steganography into weekly tasks.
```

**Output:**

> Week 1 – Literature Review
> Week 2 – Dataset Collection
> Week 3 – Model Training
> Week 4 – Testing
> Week 5 – Documentation

---

## **Phase 3 – Advanced Contextual Prompts**

### **Prompt Example 5: Intelligent Scheduler**

```
You are my productivity assistant 'Nova'. Create my daily plan with tasks, study, meals, and relaxation. Keep it balanced.
```

**Output:**

> * 8 AM – Breakfast & Morning Routine
> * 9 AM – Attend Cybersecurity Lecture
> * 12 PM – Lunch + Meditation (10 mins)
> * 2 PM – Project Development
> * 6 PM – Walk & Relax
> * 8 PM – Study: Java + DSA
> * Quote of the Day: “Success is built by consistency.”

---

## **Phase 4 – Adaptive Memory Simulation**

### **Prompt Example 6: User Preferences**

```
Remember I prefer to work in the morning and take breaks every 90 minutes.
```

**Output:**

> "Got it! I’ll schedule your main work tasks in the morning and include short breaks every 90 minutes."

Now, future prompts adapt accordingly.

---

## **Functional Modules**

| Module               | Description                                   | Example Prompt                                 |
| -------------------- | --------------------------------------------- | ---------------------------------------------- |
| **Task Manager**     | Add, edit, and track daily to-dos.            | “Add ‘Buy groceries’ for 5 PM.”                |
| **Smart Scheduler**  | Manage overlapping events.                    | “Plan a schedule around my 2 PM meeting.”      |
| **Wellness Advisor** | Suggests hydration, posture, and rest breaks. | “Suggest health tips for long study sessions.” |
| **Budget Planner**   | Allocates expenses.                           | “Plan a ₹10,000 monthly budget.”               |
| **Travel Planner**   | Plans trips with itineraries.                 | “Plan a 3-day trip to Kerala.”                 |

---

## **Detailed Prompt Examples**

### **1. Personal Budget Manager**

```
Help me plan a monthly budget for ₹15,000 split across essentials, transport, and entertainment.
```

**Output:**

> Essentials – ₹7000
> Transport – ₹3000
> Entertainment – ₹2000
> Savings – ₹3000

---

### **2. Travel Itinerary Planner**

```
Plan a 2-day trip to Ooty with scenic places and budget-friendly options.
```

**Output:**

> Day 1 – Botanical Garden, Ooty Lake, Doddabetta Peak
> Day 2 – Pykara Falls, Tea Factory Visit
> Budget: ₹4500 (Hotel + Food + Travel)

---

### **3. Project Task Breakdown**

```
Divide my cybersecurity capstone project into tasks with deadlines.
```

**Output:**

> Phase 1 – Requirement Analysis (3 days)
> Phase 2 – Implementation (10 days)
> Phase 3 – Testing (4 days)
> Phase 4 – Report (2 days)

---

### **4. Study Time Organizer**

```
Create a timetable for final exam preparation with 6 subjects.
```

**Output:**

> Generates daily slots with subject rotation and revision time.

---

## **Feature Highlights**

* **Conversational Interaction** – Uses natural language.
* **Adaptive Scheduling** – Learns from preferences.
* **Cross-domain Functionality** – Works across study, health, budget, and travel.
* **AI-driven Creativity** – Suggests motivational quotes and wellness tips.
* **Scalable Design** – Easy to extend with APIs or database.

---

## **Extended Application Scenarios**

### **A. Student Study Planner**

**Prompt:**

> “Make a 7-day schedule to study AI, DSA, and Python, considering I work part-time from 3 PM–6 PM.”

### **B. Fitness Tracker**

**Prompt:**

> “Design a weekly fitness routine for someone who studies full-time and works evenings.”

### **C. Mental Wellness Bot**

**Prompt:**

> “Check in daily with me about my stress levels and suggest relaxation activities.”

### **D. Team Project Manager**

**Prompt:**

> “Distribute project work among 3 team members and track completion weekly.”

### **E. Career Skill Builder**

**Prompt:**

> “Suggest a 10-day plan to learn ethical hacking with online resources.”

---

## **Advanced Prompt Engineering Techniques**

| Technique                      | Example                                       | Purpose                              |
| ------------------------------ | --------------------------------------------- | ------------------------------------ |
| **Role Assignment**            | “You are my digital productivity assistant.”  | Adds context and role clarity.       |
| **Few-Shot Prompting**         | Including 2–3 examples in prompt              | Increases accuracy and tone control. |
| **Chain-of-Thought Prompting** | “Think step-by-step to optimize my schedule.” | Improves reasoning in tasks.         |
| **Context Embedding**          | “Considering my previous schedule…”           | Simulates short-term memory.         |
| **Output Structuring**         | “Answer in table format.”                     | Improves readability.                |

---

## **Adaptive Output Design**

### **Before Optimization:**

> “Okay, I’ll remind you.”

### **After Prompt Engineering:**

> “I’ve added your reminder for 5 PM. You also have 2 pending tasks — would you like me to reschedule them?”

---

## **Benefits of the Application**

1. Enhances time management.
2. Simplifies personal organization.
3. Promotes healthy habits through AI reminders.
4. Demonstrates the versatility of LLMs.
5. Offers a base for more advanced virtual assistant systems.

---

## **Challenges Faced**

| Challenge         | Description                                                |
| ----------------- | ---------------------------------------------------------- |
| Context Retention | Memory resets after session ends.                          |
| Task Persistence  | LLM doesn’t store state unless integrated with a database. |
| Overfitting       | Excessive detail can make prompts confusing.               |
| Token Limits      | Long instructions may be truncated.                        |

---

## **Possible Enhancements**

1. Integrate real-time APIs (Calendar, Weather, Fitness Tracker).
2. Add local database (SQLite) for storing tasks.
3. Use voice-based input/output for natural conversation.
4. Implement UI using Flask or React.
5. Connect reminders with system notifications.

---

## **Expected Output**

| Feature                      | Description                                           |
| ---------------------------- | ----------------------------------------------------- |
| **Daily Task Manager**       | Accepts, prioritizes, and summarizes daily to-dos.    |
| **Smart Scheduler**          | Context-aware reminders and overlap detection.        |
| **Wellness Tips Generator**  | Suggests hydration and relaxation breaks.             |
| **Adaptive Learning**        | Adjusts based on user preferences and activity.       |
| **Budget & Travel Planning** | Assists with cost-effective and time-efficient plans. |

---

## **Result**

The lab exercise resulted in the creation of a prototype concept for a personal assistant powered by large language models. Students were able to:

* Understand how to tailor LLM prompts to real-life applications.
* Foster creativity by designing features suited to their personal or academic lives.
* Learn prompt engineering techniques for optimal interaction with AI tools.
* Experience the versatility and utility of generative AI in solving everyday problems.

---

## **Conclusion**

This experiment illustrates the potential of **prompt engineering** as a powerful skill in the AI era.
By developing structured and adaptive prompts, ChatGPT can act as a personalized digital assistant capable of improving human productivity and creativity.
Through this project, students gain practical exposure to **AI-human interaction**, **context-based design**, and **real-world problem-solving using LLMs**.

