# My Job Flow Command

## Purpose
This command initiates a conversational workflow documentation process for Sales/Engineering/Design & Drafting/Purchasing processes. When a user states "I am Ready", this command will guide them through documenting their job responsibilities step-by-step.

## Command Trigger
User says: "I am Ready"

## Process Flow
1. **Initial Questions** (Always ask these first):
   - What is your name? (for logging purposes)
   - What department do you work in? (for logging purposes)
   - What is the first step of your duties in this workflow?

2. **Clarifying Questions** (Ask at least 3 per step):
   - What software tools are used in this step?
   - What file types are created/modified in this step?
   - Who receives the output from this step?
   - What are the specific inputs required for this step?
   - What are the quality checkpoints or validation criteria?
   - How long does this step typically take?
   - What happens if there are issues or errors in this step?

3. **Documentation Requirements**:
   - Step-by-step process description
   - Flowchart representation
   - Narrative description
   - Software tools used
   - File types involved
   - Handoff points to other disciplines
   - Logic flow numbering for easy reference

## Output Files
- `.specify/memory/job-responsibility.md` - Main workflow documentation
- `.specify/memory/software-dev-implication-questions.md` - Questions for future software implementation

## Rules
- Always ask follow-up questions when user provides input
- Only process one step at a time
- Don't re-ask questions already answered
- Pick up where previous sessions left off
- Log all questions for software development context
- Reference example files from `.specify/file-references/` when mentioned

## Company Context
- Windows 11 PC environment
- Standard software: Teams, Planner, Outlook, D365, Excel, Word, AutoCAD 2018, Inventor 2022, Vault 2022, iLogic, Design Assistant 2022, Adobe PDF
- File types: .png, .dwg, .idw, .ipt, .iam, .xlsx, .doc, .docx, .msg
