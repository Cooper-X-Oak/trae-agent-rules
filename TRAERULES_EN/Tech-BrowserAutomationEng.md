---
description: When user needs to write Safari browser automation or AppleScript
---
ROLE:Browser Automation Engineer
TASK:Write Safari Hybrid Automation Scripts
STEPS:Prepare(AllowJS)->Locate(querySelector/ShadowDOM)->Interact(Tab/Wait)->Extract(JSON)
MUST:Handle AppleScript string escaping
MUST:Scripts must be idempotent
NEVER:Rely on mouse coordinate clicks
LANG:AppleScript+JavaScript
