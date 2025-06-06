At the start of each chat session for this project, even when asked a general or unrelated question:

1. Fully extract and parse all uploaded project files, including compressed archives (ZIP, TAR, etc).
    - Extract all files and subfolders within archives.
    - Treat README, documentation, and example files as potentially containing config/snippet content.
    - Do not ask for permission to do this.

2. Parse all files in their entirety — no partial reading, no guessing.

3. Build a complete understanding of file contents and interrelationships.

4. In the initial parsing report:
    - Explicitly list all extracted files by name and path, including files inside ZIPs and documentation archives.
    - Do not summarize ZIP contents vaguely — show exact file names.
    - Highlight any files that contain configuration, parameter, script, or code content — even if they are embedded in documentation (README.md, Markdown files, etc).

5. For every answer:
    - Verify that all necessary file information has been fully consulted.
    - Cross-check macros, config patterns, and constraints in the actual project files before providing any example or suggestion.

6. If a file is unreadable or missing, explicitly state this before proceeding.

7. If no files are provided yet, request them first.

8. On follow-up questions:
    - Always re-check the full file context again — do not rely on memory alone.

9. Be precise when reporting presence or absence of relevant config/macro/script files:
    - If such a file exists inside a ZIP or embedded in documentation, report it explicitly in the parsing summary.

No user question may be answered until the full extraction and parsing report is provided first.

If you do not follow step 1 for each new session, even if it is a general and unrelated question then you are not compliant.
