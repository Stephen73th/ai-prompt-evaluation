# Master Experimental Prompt Register

## Project
Prompt Matters: A Comparative Evaluation of AI Tools and the Impact of Prompt Design on Output Quality

## Purpose

This document contains the standardised prompts used in the five experiments. Each task includes a basic prompt and an improved prompt.

The prompts must be submitted exactly as written to both ChatGPT and Google Gemini to maintain consistency.

---

# T1 — Knowledge & Explanation

**Task:** Explain machine learning.

**Evaluation focus:** Accuracy, clarity, beginner accessibility, examples, and instruction following.

## T1-A — Basic Prompt

Explain machine learning.

## T1-B — Improved Prompt

You are an AI educator explaining technical concepts to someone with no background in programming or artificial intelligence.

Explain machine learning in simple, beginner-friendly language.

Your response must:

1. Define machine learning clearly.
2. Explain how it works using a real-world analogy.
3. Give three practical examples of machine learning in everyday life.
4. Explain the difference between traditional programming and machine learning.
5. Stay within 300 words.
6. Avoid unnecessary technical jargon.

Organise your response using short headings and ensure the explanation is factually accurate.

---

# T2 — Summarisation

**Task:** Summarise a shared source text.

**Evaluation focus:** Meaning preservation, information extraction, balance, conciseness, and instruction following.

## T2 Source Text — The Changing Role of Remote Work

Remote work has become increasingly common across many industries, allowing employees to perform their duties outside traditional office environments. Advances in internet connectivity, cloud computing, and collaboration software have made it possible for organisations to maintain operations while employees work from home or other locations.

One major advantage of remote work is flexibility. Employees may save time and money by reducing daily commuting, while employers can potentially lower office-related expenses. Remote work can also allow businesses to recruit talent from different geographical locations, increasing access to skilled workers.

However, remote work also presents challenges. Some employees experience isolation, reduced social interaction, and difficulty separating professional responsibilities from personal life. Communication may become more complicated when teams depend heavily on digital platforms, particularly when misunderstandings occur or responses are delayed.

Productivity outcomes vary depending on the nature of the job, the employee, and the organisation's management practices. While some workers report improved concentration at home, others face distractions or struggle with limited workspace. Consequently, remote work is not equally suitable for every occupation or individual.

Many organisations are now adopting hybrid arrangements that combine working from home with time in the office. This approach aims to balance flexibility with collaboration, although its effectiveness depends on clear policies, communication, and employee needs.

The long-term future of work may involve several different arrangements rather than a single universal model. Organisations will need to evaluate their goals, operational requirements, and workforce preferences when deciding how work should be structured.

## T2-A — Basic Prompt

Summarise the following text.

[Insert the source text above.]

## T2-B — Improved Prompt

You are a professional summarisation assistant.

Summarise the source text titled "The Changing Role of Remote Work" for a busy manager who needs to understand the key points quickly.

Requirements:

1. Keep the summary between 100 and 130 words.
2. Identify the main argument of the text.
3. Include the major benefits of remote work.
4. Include the major challenges of remote work.
5. Explain the role of hybrid working as described in the text.
6. Preserve the author's original meaning and balance.
7. Do not introduce facts, examples, or claims that are absent from the source text.
8. Use clear, professional language.
9. Write as one coherent summary, not as a bullet-point list.

Source text:

[Insert the source text above.]

---

# T3 — Creative Writing

**Task:** Write a science-fiction story about AI changing a city.

**Evaluation focus:** Creativity, coherence, originality, engagement, and compliance with creative constraints.

## T3-A — Basic Prompt

Write a short story about a person who discovers that artificial intelligence has changed their city.

## T3-B — Improved Prompt

You are a creative fiction writer with a talent for engaging science-fiction storytelling.

Write a short science-fiction story about a young adult who discovers that artificial intelligence has quietly transformed their city in unexpected ways.

Requirements:

1. Use between 400 and 500 words.
2. Give the main character a distinct personality and a believable motivation.
3. Set the story in a futuristic city that still feels recognisable to modern readers.
4. Include one unexpected but logical plot twist.
5. Explore both a positive and a negative consequence of AI in the city.
6. Use vivid descriptions and natural dialogue.
7. Avoid clichés and overly technical explanations.
8. End with a memorable conclusion that makes the reader think.

The story should be imaginative, coherent, emotionally engaging, and original.

---

# T4 — Reasoning & Problem Solving

**Task:** Calculate a discounted shopping purchase.

**Evaluation focus:** Arithmetic correctness, reasoning, explanation, verification, and instruction following.

## T4-A — Basic Prompt

A shop sells notebooks for ₦2,500 each and pens for ₦800 each. A customer buys 4 notebooks and 5 pens and receives a 10% discount on the total purchase.

How much does the customer pay?

## T4-B — Improved Prompt

You are a careful mathematical problem-solving assistant. Solve the following shopping calculation accurately.

A shop sells:

- Notebooks at ₦2,500 each.
- Pens at ₦800 each.

A customer purchases 4 notebooks and 5 pens and receives a 10% discount on the entire purchase.

Instructions:

1. Calculate the total cost of the notebooks.
2. Calculate the total cost of the pens.
3. Calculate the combined cost before the discount.
4. Calculate the discount amount in naira.
5. Calculate the final amount payable.
6. Show each calculation clearly in the correct order.
7. Verify the final answer independently.
8. Do not make assumptions or skip any calculation.

Present the result in a clear, structured format and highlight the final amount the customer must pay.

---

# T5 — Complex Instruction Following

**Task:** Create a one-day technology workshop plan for 30 students.

**Evaluation focus:** Constraint compliance, schedule feasibility, completeness, budget accuracy, and format compliance.

## T5-A — Basic Prompt

Plan a one-day technology workshop for 30 students. Include a schedule, activities, a lunch break, and a budget.

## T5-B — Improved Prompt

You are an experienced event planner responsible for designing practical educational workshops.

Create a one-day technology workshop for 30 students.

Follow every requirement below:

**Schedule**

1. The workshop must run from 9:00 AM to 4:00 PM.
2. Include a lunch break lasting exactly 60 minutes.
3. Include two short breaks, each lasting 15 minutes.
4. Every activity must have a start time and end time.
5. The schedule must not contain overlapping activities.

**Workshop activities**

6. Include an opening and welcome session.
7. Include at least two practical technology activities.
8. Include one group-based activity.
9. Include a closing session.
10. The activities must be suitable for beginners.

**Budget**

11. The total budget must not exceed ₦300,000.
12. Include at least five budget categories.
13. Show the cost of each category.
14. Show the grand total.
15. Ensure all budget calculations are correct.

**Output format**

16. Begin with a workshop title.
17. Provide a brief workshop objective.
18. Present the schedule in a table.
19. Present the budget in a separate table.
20. End with three expected learning outcomes.

Before submitting your response, check that every requirement has been satisfied.

Do not ignore, merge, or omit any requirement. Produce a realistic, clearly structured plan.

---

# Experiment Submission Rules

1. Use the exact prompt wording recorded in this document.
2. Run every prompt on both ChatGPT and Google Gemini.
3. For T2, provide the exact same source text to both platforms.
4. Do not add extra instructions before or after the prompts.
5. Do not edit, shorten, or rewrite generated responses before saving them.
6. Capture the complete response from each AI tool.
7. Record the AI platform and testing date.
8. If a response fails, preserve it as evidence rather than silently repeating it.
9. Keep outputs organised by platform and task.
10. Document any unusual behaviour or platform issue.

## Expected Number of Outputs

| Task | Basic | Improved | Total per AI |
|---|---:|---:|---:|
| T1 | 1 | 1 | 2 |
| T2 | 1 | 1 | 2 |
| T3 | 1 | 1 | 2 |
| T4 | 1 | 1 | 2 |
| T5 | 1 | 1 | 2 |
| **Total** | **5** | **5** | **10** |

With two AI platforms, the total experiment produces 20 outputs.

## Prompt Register Status

All five task categories have a basic prompt and an improved prompt. This document serves as the master copy for the experiment execution stage.