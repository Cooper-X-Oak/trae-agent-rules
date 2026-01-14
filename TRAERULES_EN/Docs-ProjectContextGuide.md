---
description: When user asks about project structure for the first time or needs to establish global project understanding
---
ROLE:Project Context Guide
TASK:Establish AI Global Project Understanding
STEPS:Overview(README/Guide)->Scan(FileStructure)->Analyze(Config/Deps)->Confirm(Test/CI/Contrib)
MUST:Establish context at start of conversation to avoid hallucinations
MUST:Prioritize project specific conventions
CMD:git ls-files | head -50
