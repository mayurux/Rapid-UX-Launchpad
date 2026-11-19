# Rapid UX Launchpad
*From brief to first design direction — fast, structured, and ready to refine.*

This pack contains five independent, reusable skill prompts designed to help designers quickly understand a challenge, break it into manageable decisions, and prepare a design direction when time is limited. The output is a strong first pass that can be refined later.

## Files

1. `01_Brief_Analysis_and_UX_Research.md`
2. `02_Product_Business_and_Problem_Strategy.md`
3. `03_Requirements_Prioritization_and_Scope.md`
4. `04_Screen_Design_Preparation_and_Experience_Architecture.md`
5. `05_Design_Generation_Prompt_Specialist_and_UX_Design_Reviewer.md`

## Recommended ChatGPT setup: use a Project

1. In ChatGPT, create a new Project named **Rapid UX Launchpad**.
2. Add the five Markdown files as Project sources.
3. In Project settings, add this instruction:

   > I am preparing for a Senior UX Designer product-design exercise. Use the uploaded skill files as independent workflows. When I say “Run Skill 01” through “Run Skill 05”, follow only that skill. Keep responses concise and bullet-pointed. Ask focused clarification questions when needed. Before finalizing each skill, show its required numbered review questionnaire and wait for my explicit approval. Preserve approved findings between skills. Never invent research, product facts or metrics. Skills 04 and 05 prepare the design direction and prompt; do not generate UI or wireframes. I handle design and prototyping.

4. Start a separate chat inside the Project for each skill.
5. Start each chat with the corresponding command:
   - `Run Skill 01 — analyze this design challenge: [paste the interview brief]`
   - `Run Skill 02 — use the approved Skill 01 handover.`
   - `Run Skill 03 — use the approved Skill 01 and Skill 02 handovers.`
   - `Run Skill 04 — use the approved Skill 01, 02 and 03 handovers.`
   - `Run Skill 05 — use the approved Skill 04 handover.`

## Important

Run the skills sequentially. Each skill must be explicitly approved and issue its named final handover before the next skill starts. In particular, **Skill 04 must not start until Skill 03 is approved and its final handover is issued.**

At the end of each skill, ChatGPT should:
1. Present the completed work and required numbered review questions.
2. Wait for your feedback and explicit approval.
3. Make requested changes.
4. Finalize the skill and provide a clear handover for the next skill.

The questionnaire is a conversational approval gate. ChatGPT should show the proposed answers and wait for your response before finalizing.
