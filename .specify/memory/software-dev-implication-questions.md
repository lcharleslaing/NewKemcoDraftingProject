# Software Development Implication Questions

## Purpose
This file captures questions and insights gathered during workflow documentation that will inform future software development efforts.

## Questions by Workflow Step

### Step 1: Job Assignment Review in Microsoft Planner
**Date Captured**: [Current Date]
**Person**: Lee Laing
**Department**: Engineering (Drafter Designer III)

#### Technical Questions
- How could we automate the job information extraction from Planner to eliminate paper-based recording?
- Could we integrate Planner data directly with D365 to create a seamless job tracking system?
- What APIs are available for Microsoft Planner to pull job assignment data programmatically?

#### Integration Questions
- How does the current paper-based information transfer to the next step in the workflow?
- Could we create a digital job card that automatically populates with Planner data?
- What would be needed to integrate Planner notifications with other drafting software?

#### User Experience Questions
- Would a dashboard view of all assigned jobs improve efficiency over the current filter system?
- Could we implement a "job details" popup that shows all relevant information without switching between apps?
- How could we reduce the manual data entry while maintaining the current workflow structure?

#### Data Flow Questions
- What happens to the paper-recorded information after it's used in the next step?
- Could we create a digital job tracking system that follows the job through all workflow steps?
- How could we ensure data consistency between Planner and other systems in the workflow?

#### Software Tool Integration Questions
- Could we integrate Planner data with AutoCAD/Inventor to pre-populate project information?
- What would be needed to create a unified job management interface across Teams, Planner, and D365?
- How could we implement automated job status updates back to Planner from drafting software?

---

### Step 2: Job Folder Navigation and KOM File Access
**Date Captured**: [Current Date]
**Person**: Lee Laing
**Department**: Engineering (Drafter Designer III)

#### Technical Questions
- How could we create a standardized customer naming convention to eliminate search variations?
- Could we implement a job search interface that searches across all customer name variations automatically?
- What would be needed to create a centralized job folder management system that auto-creates folders when jobs are assigned?

#### Integration Questions
- How could we integrate the KOM file data directly into drafting software to eliminate manual data entry?
- Could we create a job dashboard that shows all relevant KOM data without opening Excel files?
- What would be needed to sync KOM file changes automatically with printed references?

#### User Experience Questions
- Could we implement a "favorite jobs" or "recent jobs" feature to speed up navigation?
- How could we create a job folder preview that shows folder contents without opening each folder?
- Would a job status indicator help identify which jobs are ready for drafting work?

#### Data Flow Questions
- How could we automate the job folder creation process when jobs are assigned in Planner?
- Could we create a job data extraction tool that pulls all relevant information from KOM files?
- What would be needed to maintain data consistency between KOM files and job folder structures?

#### Software Tool Integration Questions
- Could we integrate AutoCAD with the job folder system to auto-populate project information?
- How could we create a network performance monitoring tool to identify optimal times for file access?
- What would be needed to implement a job file caching system to improve access speeds?

#### Network Performance Questions
- Could we implement a local caching system for frequently accessed KOM files?
- How could we optimize the network drive structure to reduce search times?
- What would be needed to create a job file synchronization system that works offline?

---

### Step 3: Sales Proposal Review and Equipment Specification Validation
**Date Captured**: [Current Date]
**Person**: Lee Laing
**Department**: Engineering (Drafter Designer III)

#### Technical Questions
- How could we create an automated proposal document versioning system that clearly identifies the most current document?
- Could we implement a document comparison tool that highlights differences between KOM files and proposals?
- What would be needed to create a standardized proposal naming convention across all sales team members?

#### Integration Questions
- How could we integrate proposal data directly into the drafting workflow to eliminate manual comparison?
- Could we create a unified specification database that combines KOM and proposal information?
- What would be needed to automatically flag discrepancies between sales and engineering specifications?

#### User Experience Questions
- Could we implement a proposal document preview that shows key specifications without opening the full document?
- How could we create a document search interface that finds proposals by job number, customer, or date?
- Would a specification comparison dashboard help identify discrepancies more efficiently?

#### Data Flow Questions
- How could we automate the proposal document organization and filing process?
- Could we create a document versioning system that tracks all proposal revisions automatically?
- What would be needed to maintain data consistency between KOM files and proposal documents?

#### Software Tool Integration Questions
- Could we integrate Adobe PDF with the job folder system to enable direct specification extraction?
- How could we create a document management system that works with both Word and PDF proposals?
- What would be needed to implement automated document printing and organization?

#### Document Management Questions
- Could we create a temporary job folder system that automatically organizes all job-related documents?
- How could we implement a document tagging system that identifies document types and versions?
- What would be needed to create a document archive system that maintains historical versions?

---

### Step 4: Engineering Design and Release Document Review
**Date Captured**: [Current Date]
**Person**: Lee Laing
**Department**: Engineering (Drafter Designer III)

#### Technical Questions
- How could we create an automated document identification system that finds the correct "Engineering Design" and release documents?
- Could we implement a Vault integration that automatically checks for populated project folders?
- What would be needed to create a Copy Design automation tool that reduces manual intervention?

#### Integration Questions
- How could we integrate Vault project status with the job workflow to eliminate manual checking?
- Could we create a unified specification database that combines General Design, Releases, and KOM data?
- What would be needed to automate the Copy Design process when Vault folders are empty?

#### User Experience Questions
- Could we implement a project status dashboard that shows system drawing completion and Vault population status?
- How could we create a document comparison tool that highlights differences between specifications?
- Would a workflow notification system help identify when dependencies are ready for the next step?

#### Data Flow Questions
- How could we automate the verification process for system drawings and Vault population?
- Could we create a dependency tracking system that shows what's needed before proceeding?
- What would be needed to maintain data consistency between Engineering documents and Vault projects?

#### Software Tool Integration Questions
- Could we integrate Design Assistant 2022 with the job workflow to streamline Copy Design processes?
- How could we create a Vault monitoring system that tracks project folder population status?
- What would be needed to implement automated discrepancy detection between different specification sources?

#### Workflow Optimization Questions
- Could we create a parallel processing system that allows work to continue while waiting for dependencies?
- How could we implement a priority system that identifies which jobs can proceed based on available information?
- What would be needed to create a resource allocation system that optimizes Mike and Pete's workload?

---

---

## Progress Tracking for Step Clarification Process
**Last Updated**: [Current Date]
**Current Status**: PAUSED - Ready to resume at Step 6
**Steps Completed in Conversation**: 1-5 (Job Assignment, KOM File Access, Sales Proposal Review, Engineering Design Review, D365 Product Verification)
**Steps Remaining for Clarification**: 6-18
**Current Step Being Clarified**: Step 6 (Rename Inventor Drawings) - Questions asked, waiting for answers
**Next Steps After Resume**: Complete Step 6 clarification, then continue with Steps 7-18

## Resume Instructions
When resuming this conversation:
1. Continue with Step 6: Rename Inventor Drawings clarification questions
2. The 8 clarifying questions for Step 6 have been asked and are waiting for answers
3. After Step 6 is complete, continue with Step 7: Get/Checkout Inventor Drawings & Assemblies
4. Follow the same pattern: ask 3+ clarifying questions per step until all 18 steps are documented

### Step 5: D365 Product Verification
**Date Captured**: [Current Date]
**Person**: Lee Laing
**Department**: Engineering (Drafter Designer III)

#### Technical Questions
- How could we automate the BOM comparison between Inventor drawings and D365 to eliminate manual verification?
- Could we create a D365 integration that automatically creates missing parts/assemblies from Inventor data?
- What would be needed to implement real-time BOM synchronization between Inventor and D365?

#### Integration Questions
- How could we streamline the process of adding missing parts/assemblies to D365 before BOM creation?
- Could we create a bulk import system for new parts that reduces the 30-90 minute setup time?
- What would be needed to create a validation system that flags discrepancies before manual checking?

#### User Experience Questions
- Could we implement a dashboard that shows BOM comparison status between Inventor and D365?
- How could we create a "favorites" system that remembers frequently used D365 navigation paths?
- Would a BOM template system help speed up the creation of new project BOMs?

#### Data Flow Questions
- How could we automate the long lead time BOM creation process in D365?
- Could we create a system that pre-populates D365 with common parts based on job type?
- What would be needed to maintain data consistency between engineering specs and D365 BOMs?

#### Software Tool Integration Questions
- Could we integrate Inventor directly with D365 to eliminate the manual BOM entry process?
- How could we create a validation tool that checks part availability in D365 before drawing creation?
- What would be needed to implement automated part number generation that matches D365 conventions?

#### Process Optimization Questions
- Could we create a template system for common heater configurations to reduce setup time?
- How could we implement a checklist system that ensures all required parts are in D365 before starting?
- What would be needed to create a project status dashboard that shows BOM completion status?

---

## Recurring Themes
[Common questions or patterns that emerge across multiple steps]

## Technical Requirements Gathered
[Specific technical needs identified during workflow documentation]

## Integration Points Identified
[Key integration points between different software tools and processes]

## User Pain Points
[Challenges or inefficiencies identified in current processes]

## Future Development Priorities
[Based on workflow analysis, what should be prioritized for software development]
