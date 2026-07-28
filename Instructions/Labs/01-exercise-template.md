---
lab:
    title: 'Delegate work with Microsoft Copilot Cowork.'
    description: 'Hands-on lab guide for end-to-end testing of all eight Microsoft Copilot Cowork scenarios — from prompt to confirmed result.'
    duration: 120 minutes
    level: L300
    islab: true
    status: 'in-development' 
    targetDate: 2026-07-31 
---
<!--
Edit the metadata above to manage the list of exercises in the home page of the GitHub site that gets generated.
You can delete the module and edit index.md in the root of the repo to customize the display so that only the exercises are listed
To enable GitHub page publishing, edit the Page settings for the repo and publish from the main branch
-->

# Exercise title <Delegate work with Microsoft Copilot Cowork>

In this exercise you will run end-to-end testing of all eight Microsoft Copilot Cowork scenarios — from prompt to confirmed result.

This exercise should take approximately **120** minutes to complete. <!-- update with estimated duration -->

## Before you start

<!--
Add steps to get the learner to the starting point" for the exercise. This might be cloning the repo and running a script or performing some manual steps.

Only include this section if its necessary to do some pre-exercise setup AND the same setup steps are required for self-paced (on Learn) and managed (in hosted ILT lab profiles) scenarios. Otherwise delete this section.
If self-paced /ILT-specific setup steps are required, include them in the Learn "Exercise" unit from where they open this exercise and in the Skillable lab profile instructions before this markdown file is imported.

Do not include requirements for getting an Azure (or other) subscription (write the exercise on the assumption the learner has a functioning lab environment - this section is only for exercise-specific steps to get to a starting point)

If there are complex setup steps that apply to ALL of the exercises in the repo (for example, installing and configuring client-side tools), create a separate 00-setup.md file with instructions.
 -->

Before you can start this exercise, you will need to...

1. Login to https://admin.microsoft.com a the Admin with the credentials provided
1. Navigate to **Copilot** > **Overview**
1. etc.

## Task 1:  Run a Read-Only Briefing

First, you need to ...

1. Navigate to https://copilot.microsoft.com and login as Megan Bowen with the credentials provided. 
1. Select the **Cowork** tab at the top left of the navigation menu.
1. Select **+ New Task**. 
1. In the chat box, select **+** > **Add work context** .
1. Select the **Files** tab. 
1. Select **Portfolio Status (current, post-decision).xlsx**.
1. In the chat box, select the **+** button > **Add work context** .
1. Select the **Files** tab. 
1. Select **Summit Evidence Pack (outline).docx**.
1. In the chat box, select the **+** button > **Add work context**
1. Select the **Files** tab. 
1. Select **Beacon GA Hold - Decision Memo.docx**.
1. In the chat box, select the **+** button > **Add work context**
1. Select the **Emails** tab.
1. Select **Your weekly PIM digest for Contoso (ID: 19df7e7f-0b0b-4925-bd5e=b38d28fd8eb0)**.
1. In the chat box, select the **+** button > **Add work context**
1. Select the **Emails** tab.
1. Select **Passkeys by default and retirement of Microsoft-provided SMS and voice authentication**.
1. In the chat box, select the **+** button > **Add work context**
1. Select the **Emails** tab.
1. Select **Microsoft Entra ID Protection Weekly Digest**.
1. In the chat box, select the **+** button > **Add work context**
1. Select the **Chats** tab.
1. Select **Nestor, Patti**.
1. In the chat box, select the **+** button > **Add work context**
1. Select the **Chats** tab.
1. Select **Allan, Diego, Isaiah**.
1. In the chat box, select the **+** button > **Add work context**
1. Select the **Chats** tab.
1. Select **Alex, Allan, Diego**.
1. In the prompt field, copy and paste the following prompt:
   Give me a read-only briefing of where things stand right now. Look at my selected emails, Teams chats, my calendar for the next three days, and my open tasks. Don’t send or change anything — just tell me what needs my attention, what I might have missed, and what’s coming up. Group it as “Needs a decision,” “FYI,” and “Upcoming.
1.  Send the prompt by selecting the white circle with the black up-arrow in the bottom-right corner.
1. **Outcome:** Cowork should produce the following:
       a. One chat briefing, organized into “Needs a decision,” “FYI,” and “Upcoming.”
       b. Content is drawn from the attached emails and Teams chat, as well as your calendar, and tasks.
       c. Nothing was sent or changed — no files produced. 


## Task 2: Reconstruct Your Week

1. Navigate to https://copilot.microsoft.com and login as Megan Bowen with the credentials provided. 
1. Select the **Cowork** tab at the top left of the navigation menu.
1. Select **+ New Task**. 
1. In the prompt field, copy and paste the following prompt:
      Draft my weekly update for my manager. Reconstruct what I did this week from my sent email, completed tasks, the meetings I led, and my Teams threads. Structure it as Accomplished / Questions & where I need help / Looking ahead — and ground “Looking ahead” in my actual upcoming calendar and open tasks. Match my writing voice. Leave it as a draft for me to review — don’t send it.
1. Send the prompt by selecting the white circle with the black up-arrow in the bottom-right corner.
1. **Outcome:** Cowork should produce the following:
       a. Three sections are present and that each “Accomplished” item ties back to a real artifact, thread, or meeting.
       
### Task 2.1: Put It on a Schedule

1. In the same conversation, paste the following prompt in the chat box:
       Run this every Friday at 3 PM and drop the draft for my review — never auto-send.
1. When prompted under **Which timezone should the Friday 3PM run use?**, select **Pacific (American/Los_Angeles)** > **Submit**.
1. Send the prompt by selecting the white circle with the black up-arrow in the bottom-right corner.
1. **Outcome:** Cowork should produce a prompt that begins with something like**Create recurring task?** followed by information regarding the weekly manager draft.
1. Select **Cancel**, as we will not be scheduling tasks in this live tenant. 

## Task 3: Triage your Inbox

1. Navigate to https://copilot.microsoft.com and login as Megan Bowen with the credentials provided. 
1. Select the **Cowork** tab at the top left of the navigation menu.
1. Select **+ New Task**.
1. In the prompt field, copy and paste the following prompt:
      Triage my inbox. Sort everything into “Waiting on me,” “FYI,” and “Can be delegated.” For each “Waiting on me” item, draft a contextual reply but hold it for my approval — don’t send anything. Create follow-up tasks for anything that needs tracking.
1. Send the prompt by selecting the white circle with the black up-arrow in the bottom-right corner.
1. **Outcome:** Cowork should produce the following:
   a. A response with your inbox sorted into three buckets.
   b. Held reply drafts exist for “Waiting on me” items — no sends. 

## Task 4: Create a Meeting-to-Momentum Loop

1. Navigate to https://copilot.microsoft.com and login as **Joni Sherman** with the credentials provided. 
1. Select the **Cowork** tab at the top left of the navigation menu.
1. Select **+ New Task**.
1. In the chat box, select the **+** button > **Add work context** .
1. Select the **Meetings** tab. 
1. Select **Weekly Project Sync**.
1. In the prompt field, copy and paste the following prompt:
   For this weekly project sync series, pull the recaps and open action items from the recent instances, keep a running decision log, and draft the agenda for the next meeting from the unfinished items and prior decisions. Save the log and the agenda to my files.
1. Send the prompt by selecting the white circle with the black up-arrow in the bottom-right corner.
1. **Outcome:** Cowork should produce the following:
   a. A decision-log doc (or a running log) and a next-agenda doc are saved to files. 
   b. The agenda reflects unfinished items and prior decisions.

   
### Task 4.1: Refresh After Each Meeting

1. In the same conversation, send a new prompt to automate the refresh:
   Refresh the decision log and the next agenda automatically after each meeting instance.
1. If prompted **What should trigger the automatic refresh of the decision log and next agenda?**, select **Megan's recap email**, then select **Submit**.
1. In the **New routine** response prompt, ensure the **When** field is set to **I receive an email**.
1. Select **Activate routine**.
1. Send the prompt by selecting the white circle with the black up-arrow in the bottom-right corner.
1. **Outcome:** Cowork should respond with something similar to "the auto-refresh is set up and running". 

## Task 5: Get updated information from within your organization

1. Navigate to https://copilot.microsoft.com and login as **Joni Sherman** with the credentials provided. 
1. Select the **Cowork** tab at the top left of the navigation menu.
1. Select **+ New Task**.
1. In the prompt field, copy and paste the following prompt:
   I’ve been out for two weeks. Catch me up: what decisions were made, which threads moved, and what tasks came due while I was away. Build me a prioritized re-entry plan for my first day back, and draft catch-up replies for the threads that need me — hold them for my review.
1. Send the prompt by selecting the white circle with the black up-arrow in the bottom-right corner.
1. **Outcome:** Cowork should produce the following:
   a. A recap covering decisions, moved threads, and due tasks. 
   b. A prioritized re-entry plan for the first day back.
   c. Catch-up reply drafts held for review — no sends. 

## Task 6: Create a Project Dashboard

1. Navigate to https://copilot.microsoft.com and login as **Joni Sherman** with the credentials provided. 
1. Select the **Cowork** tab at the top left of the navigation menu.
1. Select **+ New Task**.
1. In the prompt field, copy and paste the following prompt:
  Build me a project status dashboard across my active projects. For each one, pull the status from the relevant threads, docs, and task lists, and lay it out as a table: Project / Status (Red-Amber-Green) / Blockers / Next milestone / Owner. Save it to my files.
1.  Send the prompt by selecting the white circle with the black up-arrow in the bottom-right corner.
1. **Outcome:** Cowork should produce the following:
   a. A saved five-column RAG status table across the active projects. 
   b. Each status is backed by real threads, docs, or tasks.

 ## Task 7: Create a Project Status Update on a Specific Topic

1. Navigate to https://copilot.microsoft.com and login as **Alex Wilbur** with the credentials provided. 
1. Select the **Cowork** tab at the top left of the navigation menu.
1. Select **+ New Task**.
1. In the prompt field, copy and paste the following prompt:
   Pull the source material for the Atlas Launch from my email, Teams, and files. Analyze the numbers in Excel, build a short PowerPoint readout of the findings, and export a one-page PDF brief. Save all three to my files.
1. Send the prompt by selecting the white circle with the black up-arrow in the bottom-right corner.
1. **Outcome:** Cowork should produce the following:
   a. Three artifacts saved: Excel + PowerPoint + PDF. 
   b. The deck and PDF are consistent with the Excel analysis.

## Task 8: Build-Your-Own Skill Challenges

1. Navigate to https://copilot.microsoft.com and login as **Alex Wilbur** with the credentials provided. 
1. Select the **Cowork** tab at the top left of the navigation menu.
1. Select **+ New Task**.
1. In the prompt field, copy and paste the following prompt:
  I'd like to build a skill that writes my status update regarding the Atlas Launch. 
1. Send the prompt by selecting the white circle with the black up-arrow in the bottom-right corner.
1. Work through the guided builder’s questions and save the skill to your library.
     > **Note**: Cowork may or may not ask guided questions prior to an output. If no builder questions are asked, proceed to the next step.
1. **Outcome:** Cowork should create and have the skill saved. The name of the skill may be similar to **atlas-launch-status**.

### Task 8.1: Trigger the Saved Skill

1. Select **+ New Task** at the top left of the navigation menu.
1. In the prompt field, copy and paste the following prompt:
   Write my Atlas status update for the weekly sync
1. Send the prompt by selecting the white circle with the black up-arrow in the bottom-right corner.
1. **Outcome:** Cowork should respond with a project status regarding the Atlas Launch. 

## Clean up

Now that you've finished the exercise, you should sign out of all accounts and close out ofall browsers.

END OF LAB.

