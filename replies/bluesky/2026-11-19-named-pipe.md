---
reply_to: https://bsky.app/profile/cookting.bsky.social/post/3n2foyxoth22d
follow: false
---

An MCP server is a process that advertises tools with JSON schemas over a transport (stdio or HTTP), plus auth and change notifications. A named pipe just moves bytes. The interesting part isn't the pipe, it's the contract: what the tool does, when to call it, and what it returns.