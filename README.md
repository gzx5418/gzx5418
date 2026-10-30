# Hi, I'm gzx5418

I work on AI applications, intelligent agents, and practical software tools.

## Selected Projects

- **[Lvyan Legal Agent](https://github.com/gzx5418/lvyan-legal-agent)** — A legal agent runtime built with LangGraph, combining a multi-step workflow with hybrid retrieval and document processing.
- **[Elder Care App](https://github.com/gzx5418/elder-care-app)** — An Android app featuring a voice assistant, fraud detection, reminders, and calendar integration.
- **[Lvyan Law Text](https://github.com/gzx5418/lvyan-lawtext)** — A collection of Chinese legal texts used as a data source for the Lvyan agent.

## Open Source Contributions

### clawd-on-desk — Windows Launch Bug Diagnosis

- Reported and diagnosed a Windows launch failure (`0x800700c1 / ERROR_BAD_EXE_FORMAT`).
- Traced the failure to `findClaudeCmd()` selecting an npm-generated POSIX shell script instead of the Windows `.cmd` shim.
- Provided reproduction details, source-level analysis, and a proposed fix.
- The maintainer confirmed the issue and merged a fix that addressed both command selection and the terminal launch path.

[Issue #435](https://github.com/rullerzhou-afk/clawd-on-desk/issues/435) · [Maintainer's merged fix #438](https://github.com/rullerzhou-afk/clawd-on-desk/pull/438)
