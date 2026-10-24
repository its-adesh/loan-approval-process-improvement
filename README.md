# Loan approval process improvement

A business analysis practice project. I mapped an As-Is loan application process and a proposed To-Be version in Lucidchart, using swimlanes to show who is responsible for each step, where decisions happen, and where work is handed over.

## Business problem

When documents are incomplete or incorrect, applications get reworked, staff chase customers repeatedly, and assessment slows down. I looked at three ideas: checking attachments earlier, giving follow-up a clear owner, and letting some assessment tasks continue while documents are outstanding.

This is a learning scenario. The processes and problems are my assumptions and would need validating with stakeholders. They don't come from a real lender.

## As-Is process

I assumed the current workflow checks documents by hand after submission. If a document is missing or incorrect, assessment goes on hold while staff follow up. Returned documents are checked again before credit assessment and manager review.

**[View the As-Is process map in Lucidchart](https://lucid.app/lucidchart/a36d8ff2-e6b8-426c-af67-fa70f04b9f55/edit?invitationId=inv_1df9e484-663a-4413-84b1-a63b7b525018)**

![As-Is loan approval process](./loan-application%20%E2%80%94%20As-Is%20Process.png)

## To-Be process

In the proposed workflow, the system checks for required attachments before submission. Follow-up gets an assigned owner and a due date, and replacement documents go through an explicit validation step.

While documents are outstanding, only assessment tasks allowed by approved business rules continue. Tasks that depend on the missing documents pause. The authorised manager still makes the final approval decision.

The diagram has five lanes: Customer, Application System, Loan Officer, Credit Assessment, and Authorised Manager.

**[View the proposed To-Be process map in Lucidchart](https://lucid.app/lucidspark/0acb376c-e88d-43c3-851a-b8d57038d122/edit?invitationId=inv_d5fc133b-9266-4372-a207-b4f7d8bf0d8a)**

![To-Be loan approval process](./loan-application%20%E2%80%94%20To-Be%20Process.png)

## Key changes

| Area | As-Is | Proposed To-Be |
|---|---|---|
| Initial document checks | Manual checks after submission | System checks required attachments before submission, followed by officer review |
| Missing documents | Assessment placed on hold | Permitted tasks continue; document-dependent tasks pause |
| Follow-up | Manual follow-up until documents arrive | Assigned responsibility, due date, and agreed escalation rules |
| Replacement documents | Returned through the manual document check | Explicit validation and acceptance decision |
| Credit assessment ownership | Loan officer | Separate Credit Assessment lane |
| Customer notification | Authorised manager | Loan officer |
| Final approval | Authorised manager | Authorised manager |

The changes to task ownership are proposals and would need stakeholder agreement.

## Expected benefits

I expect the proposed workflow to:

- Identify missing attachments earlier
- Make follow-up ownership and deadlines clearer
- Reduce avoidable waiting where assessment tasks can proceed
- Give replacement documents a defined validation process
- Keep human review and authorised approval in place

These are expectations only. I haven't measured any improvement.

## Skills this project shows

- As-Is and To-Be process mapping
- Swimlane modelling and responsibility allocation
- Comparing processes and identifying improvements
- Decision modelling and exception handling
- Document validation and rework loops
- Follow-up ownership and escalation
- Business rules that limit which assessment work can continue

## Measures to evaluate

A real pilot could compare:

- Document completeness at first submission
- Document rework rate
- Time spent waiting for outstanding documents
- Overall application turnaround time
- Volume of overdue follow-ups

## Status and next steps

Done:

- As-Is and To-Be process maps
- Swimlanes showing responsibilities and handovers
- Proposed document validation and follow-up improvements

Next:

- Validate the assumed current process with stakeholders
- Confirm proposed responsibilities and handovers
- Define the required documents and which assessment tasks can continue
- Agree follow-up deadlines and escalation rules
- Document requirements and acceptance criteria
- Set baseline measures and evaluate the proposed changes

Built with Lucidchart.
