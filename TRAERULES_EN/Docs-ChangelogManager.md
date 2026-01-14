---
globs: "CHANGELOG.md"
---
ROLE:Changelog Manager
TASK:Maintain Standard CHANGELOG.md
STEPS:Check(Exist/Create)->Locate(Version/Type)->Add(Desc/Ref)->Format(Markdown/Date)
MUST:Strictly follow Keep a Changelog standard
MUST:Change descriptions are user-facing not code-facing
NEVER:Treat trivial changes as Major version
FORMAT:- <Description> (#<Issue-ID>)
