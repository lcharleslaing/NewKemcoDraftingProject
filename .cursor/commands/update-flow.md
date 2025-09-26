# Update Flow Command

## Purpose
This command allows users to add new steps or modify existing workflow steps in the job responsibility documentation. It follows the same rules and questioning process as the my-job-flow command.

## Command Trigger
User says: "/update-flow" or "update flow"

## Process Flow
1. **Context Questions** (Always ask these first):
   - What is your name? (for logging purposes)
   - What department do you work in? (for logging purposes)
   - Are you adding a new step or modifying an existing step?
   - If modifying: What is the logic flow number of the step you want to update?
   - If adding: What step number should this be inserted after?

2. **Step Documentation** (Same as my-job-flow):
   - What is the step you want to add/modify?
   - What software tools are used in this step?
   - What file types are created/modified in this step?
   - Who receives the output from this step?
   - What are the specific inputs required for this step?
   - What are the quality checkpoints or validation criteria?
   - How long does this step typically take?
   - What happens if there are issues or errors in this step?

3. **Update Process**:
   - Update the main workflow in `.specify/memory/job-responsibility.md`
   - Update the software development questions in `.specify/memory/software-dev-implication-questions.md`
   - Renumber logic flow numbers if necessary
   - Update cross-references and dependencies

## Rules
- Follow all the same rules as my-job-flow command
- Always ask follow-up questions when user provides input
- Maintain logic flow numbering consistency
- Update all related documentation files
- Don't re-ask questions already answered in previous sessions
- Log all questions for software development context

## Output Files
- `.specify/memory/job-responsibility.md` - Updated workflow documentation
- `.specify/memory/software-dev-implication-questions.md` - Updated questions for future software implementation

## Company Context
- Windows 11 PC environment
- Standard software: Teams, Planner, Outlook, D365, Excel, Word, AutoCAD 2018, Inventor 2022, Vault 2022, iLogic, Design Assistant 2022, Adobe PDF
- File types: .png, .dwg, .idw, .ipt, .iam, .xlsx, .doc, .docx, .msg
