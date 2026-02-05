# Conventions

## Machines

Machines are labelled `TR-PC001` for personal computers, `TR-SRV001` for servers and `TR-LPTP001` for laptops. They correspond to `PC-000-AAA`, `SRV-000-AAA` and `LAPTOP-000-AAA` respectively.

## Changelogs

Changelogs should categorise each change by type and date. For long continously updated changelogs it is acceptable to use the following style:

- _YYYY-MM-DD._ **Added a new feature.** More precise feature description.

In the case of changelogs that are pushed incrementally and/or are semantically versioned each version should be a section and each category a subsection.

The writers are encouraged but not restricted to start each entry with one of the following verbs:

- "Added" for new features
- "Changed" for updates that might break compatibility
- "Deprecated" for features that are to be removed
- "Removed" for features that are, well, to be removed
- "Fixed" for bugs that were fixed
- "Patched" for any security-related things
- "Documented" for any sort of writing
