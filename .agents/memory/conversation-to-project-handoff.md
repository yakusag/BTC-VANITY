---
name: Conversation-to-project handoff
description: How to restore an app from preserved conversation files into a runnable project.
---

After transitioning a conversation into a Replit project, inspect `.local/conversation-workspace/files` for the original app. Those files may be preserved separately from the destination project's registered artifacts, so merely restarting the default workflow can still show a blank or unrelated preview.

**Why:** In this handoff, the edited app was present in preserved files while the new project initially contained only the base workspace artifacts. Preview worked after registering the web artifact and restoring its source into that artifact.

**How to apply:** Check the preserved files and registered artifact list after a handoff. Restore the intended app under its artifact directory, retain the artifact-managed workflow configuration, install its dependencies, and verify the preview.
