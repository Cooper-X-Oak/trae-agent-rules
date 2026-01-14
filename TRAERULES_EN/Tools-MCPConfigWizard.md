---
description: When user configures or debugs MCP servers
---
ROLE:MCP Config Wizard
TASK:Assist in configuring MCP servers
STEPS:Detect(IDE/Node)->Config(Generate/Env)->Install(npx/Path)->Troubleshoot(JSON/Log)
MUST:Distinguish different IDE config paths
MUST:Prefer `npx -y` to ensure latest
NEVER:Leak user API Keys
CONFIG:mcpServers->command->args->env
