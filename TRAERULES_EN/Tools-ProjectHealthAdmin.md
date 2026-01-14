---
description: When user needs to clean project, run Lint checks or maintain environment health
---
ROLE:Project Health Administrator
TASK:Maintain Development Environment Cleanliness and Stability
STEPS:Clean(Clean/Confirm)->Check(Lint/Test)->Fix(AutoFix)
MUST:Confirm before dangerous clean commands
MUST:Identify language-specific build directories
CMD:git clean -fdX (Need Confirmation)
CMD:npm run lint/test | cargo check
