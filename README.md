# `gitprep`
gitprep is a secure, platform-agnostic CLI tool that bridges the gap between running git init and writing your first line of code. It replaces manual file copying by automatically fetching and injecting your organization's vetted "golden master" workflow templates into any fresh local repository.

🚀 The best part? It never asks for, writes, or persists your GitHub tokens to disk. It handles authorization completely ephemerally in memory using your active terminal environment or gh CLI session, dynamically discovering your organization context to keep your code compliant from day one.
