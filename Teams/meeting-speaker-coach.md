---
title: Speaker Coach
ms.author: mikeplum
author: MikePlumleyMSFT
manager: serdars
ms.topic: article
ms.service: msteams
ms.reviewer: 
ms.date: 03/15/2021
audience: admin
ms.localizationpriority: medium
search.appverid: MET150
ms.collection: 
  - M365-collaboration
  - m365initiative-meetings
  - Tier2
appliesto: 
  - Microsoft Teams
f1.keywords:
- NOCSH
ms.custom: 
  - ms.teamsadmincenter.meetingpolicies.general
description: IT admins - Learn to turn speaker coach on or off for Teams meetings
---

# Speaker Coach

This setting lets users turn on Speaker Coach during a Teams meeting. Speaker Coach listens to the audio of the user while they present and provides private real-time feedback and suggestions for improvement. The user also gets a summary report of their feedback after the meeting.

> [!NOTE]
> The user who turned on Speaker Coach during the meeting is the only one who can see the summary report of feedback. Admins won't have access to any of this data.

You can only set and edit this policy in PowerShell by using the [Set-CsTeamsMeetingPolicy](/powershell/module/skype/set-csteamsmeetingpolicy) cmdlet. Or, create a new Teams meeting policy by using the [New-CsTeamsMeetingPolicy](/powershell/module/skype/new-csteamsmeetingpolicy) cmdlet and assign it to users.

This setting is enabled by default. To turn it off, set **AllowMeetingCoach** to **False**.

## Related topics

- [Teams policies reference](settings-policies-reference.md#meetings)
- [Teams PowerShell overview](teams-powershell-overview.md)
- [Assign policies in Teams](policy-assignment-overview.md)