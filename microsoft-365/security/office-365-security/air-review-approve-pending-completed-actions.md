---
title: Review and manage remediation actions in Microsoft Defender for Office 365
keywords: AIR, autoIR, Microsoft Defender for Endpoint, automated, investigation, response, remediation, threats, advanced, threat, protection
f1.keywords:
- NOCSH
author: JoeDavies-MSFT
ms.author: josephd
manager: dansimp
audience: ITPro
ms.topic: how-to
ms.localizationpriority: medium
search.appverid:
- MET150
- MOE150
ms.collection:
- M365-security-compliance
- m365initiative-defender-office365
description: Learn about remediation actions in automated investigation and response capabilities in Microsoft Defender for Office 365 Plan 2.
ms.technology: mdo
ms.prod: m365-security
ms.date: 06/10/2021
---

# Review and manage remediation actions in Office 365

**Applies to**
- [Microsoft Defender for Office 365 plan 2](defender-for-office-365.md)

As automated investigations on email & collaboration content result in verdicts, such as *Malicious* or *Suspicious*, certain remediation actions are created. In Microsoft Defender for Office 365, remediation actions can include:

- Soft deleting email messages or clusters
- Turning off external mail forwarding

These remediation actions are not taken unless and until your security operations team approves them. We recommend reviewing and approving any pending actions as soon as possible so that your automated investigations complete in a timely manner. In some cases, you can reconsider submitted actions.  You need to be part of Search & purge role before taking any actions.

## Approve (or reject) pending actions
There are four different ways to find and take auto investigation actions:

- [Incident queue](https://security.microsoft.com/incidents)
- [Action center](https://security.microsoft.com/action-center/pending)
- Investigation itself (accessed via Incident or from an alert)
- [Investigation and remediation investigations queue](https://security.microsoft.com/airinvestigation)

## Incident queue

1. Open the <a href="https://go.microsoft.com/fwlink/p/?linkid=2077139" target="_blank">Microsoft 365 Defender portal</a> and sign in.
2. In the navigation pane, select **Incidents & alerts > Incidents**.
3. Select an incident name to open its summary page.
4. Select the **Evidence and Response** tab.
5. Select an item in the list. Its side pane opens.
6. In the side pane, take approve or reject actions.

## Investigation queue

1. Open the <a href="https://go.microsoft.com/fwlink/p/?linkid=2077139" target="_blank">Microsoft 365 Defender portal</a> and sign in.
2. Navigate from the alerts/incident page.
3. On the Investigation page, go to the **pending actions** tab.
4. Select an item in the list. Its side pane opens.
5. In the side pane, take approve or reject actions.

## Action center

1. Open the <a href="https://go.microsoft.com/fwlink/p/?linkid=2077139" target="_blank">Microsoft 365 Defender portal</a> and sign in.
2. In the navigation pane, select **Action center**.
3. On the **Pending** tab, review the list of actions that are awaiting approval.
   - Select **Open investigation page** to view more details about the investigation.
   - Select **Approve** to initiate a pending action.
   - Select **Reject** to prevent a pending action from being taken.

## Investigation and remediation investigations queue

1. Open the <a href="https://go.microsoft.com/fwlink/p/?linkid=2077139" target="_blank">Microsoft 365 Defender portal</a> and sign in.
2. Open pending investigations.
3. On the Investigation page, go to the **pending actions** tab.
4. Select an item in the list. Its side pane opens.
5. In the side pane, take approve or reject actions.

## Change or undo one remediation action

There are two different ways to reconsider submitted actions:

- Through the [unified action center](https://security.microsoft.com/action-center).
- Though the [Office action center](https://security.microsoft.com/threatincidents).

## Change or undo through the unified action center

1. Go to the [unified action center](https://security.microsoft.com/action-center) and sign in.
2. On the **History** tab, select an action that you want to change or undo.
3. In the pane on the right side of the screen, select the appropriate action (**move to inbox**, **move to junk**, **move to deleted items**, **soft delete**, or **hard delete**).

## Change or undo through the Office action center

1. Go to the [Office action center](https://security.microsoft.com/threatincidents) and sign in.
2. Select the appropriate remediation.
3. In the side pane, click on the mail submissions entry and wait for the list to load.
4. Wait for the Action button at the top to enable and select the Action button to change the action type.
5. This will create the appropriate actions.

## Next steps

- [Use Threat Explorer](threat-explorer.md)
- [Admin /Manual Actions](remediate-malicious-email-delivered-office-365.md)
- [How to report false positives/negatives in automated investigation and response capabilities](air-report-false-positives-negatives.md)

## See also

- [View details and results of an automated investigation in Office 365](air-view-investigation-results.md)
