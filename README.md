# Loan Approval Process Improvement

A business analysis practice project comparing the current loan approval workflow with a proposed improved process. The scenario assumes a standard loan application that requires supporting documents, a review step for completeness, a final credit assessment, and manager approval. I created the process maps in Lucidchart to explore the As-Is and To-Be operating models.

## Business problem

Incomplete or incorrect documents can create rework and delay assessment. This project explores earlier validation, clearer follow-up ownership, and controlled continuation of permitted assessment work so the application can move forward without unnecessary delays.

## Scenario assumptions

- A customer submits a loan application with supporting documents.
- Some documents may be missing, incomplete, or incorrect at first submission.
- An officer or assessor is responsible for checking document completeness and quality.
- Assessment work can continue only when the relevant business rules allow it.
- A manager reviews the final credit recommendation before approval.

## As-Is process

![As-Is loan approval process](loan-application%20-%20As-Is%20Process.png)

## To-Be process

![To-Be loan approval process](Loan%20Approval%20%E2%80%94%20To-Be%20Process.png)

## As-Is versus To-Be comparison

| Aspect | As-Is | To-Be |
| --- | --- | --- |
| Document validation | Checking occurs late or inconsistently; missing documents may be discovered during assessment. | Required attachments are checked before submission or immediately after receipt. |
| Follow-up ownership | Follow-up may be unclear, leading to delays and rework. | An owner and due date are assigned for missing or incorrect documents. |
| Assessment work | Work may continue even when required documents are missing. | Only permitted assessment tasks continue; blocked tasks are paused until required documents are received. |
| Escalation | Missing documents may wait too long before escalation. | Follow-up and escalation occur under agreed business rules and timeframes. |
| Manager approval | Final review is part of the flow but may not be coordinated with earlier validation changes. | The process supports a cleaner handoff to an authorised manager after validation and assessment are complete. |
| Customer communication | Customers may not receive timely guidance when documents are incomplete. | Customers are notified clearly when documents are missing or need replacement. |

## Proposed process

1. Check that required attachments are present before submission and show a missing-upload message where needed.
2. Review document completeness and correctness.
3. Flag outstanding documents and assign a follow-up owner and due date.
4. Continue only assessment tasks permitted by approved business rules; pause tasks that depend on missing documents.
5. Follow up and escalate under agreed rules, then validate replacement documents.
6. Complete the credit assessment and route the application to an authorised manager for review.
7. Notify the customer of approval or decline.

## Process map

[View the process map in Lucidchart (view only)](https://lucid.app/lucidspark/0acb376c-e88d-43c3-851a-b8d57038d122/edit)

Lucid sign-in and document access may be required. The images above can be viewed directly on GitHub.

## Business analysis skills demonstrated

- Process mapping and decision modelling
- Exception handling and document rework loops
- Follow-up ownership and escalation
- Business rules governing permitted assessment work
- Human review and customer communication

## Measures to evaluate

A real pilot could compare document completeness at first submission, document rework rate, time waiting for documents, overall application turnaround time, and overdue follow-up volume. No improvement has been measured.

## Status and next steps

This is a proposed learning scenario comparing the current and improved loan approval processes. Next steps are to validate the current process with stakeholders, confirm task permissions and escalation deadlines, and review ownership and handoff responsibilities.

**Tool:** Lucidchart
