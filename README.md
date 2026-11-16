# Issue forms for every Lexbridge repository

The one copy of the issue forms: Goal, Task, Feature, Bug, Idea, Decision and UAT. GitHub uses them in every
repository of the organisation that has no `.github/ISSUE_TEMPLATE` folder of its own, so no repository keeps a copy
and none can drift. Change a form here and every repository has the change.

GitHub reads these defaults only from a public repository, so this one is public. It holds the forms and nothing else:
no code, no names, no data.

Every form starts with the no-client-data rule, asks its summary question first (Trace shows the answer under the
title) and adds the issue to the Lexbridge Apps Project. Goal, Task and Feature require *Done when*. A Bug says how bad
it is and when it happened; a Decision gives the options, a recommendation, who decides and by when.

Each form says how to word the title:

| Form | Title |
|---|---|
| Goal | `Goal [number]: what will be true`. Each app counts its own goals; a goal keeps its number for good. |
| Task | Starts with a verb. |
| Feature | What the app will do or have. |
| Bug | What goes wrong. |
| Idea | The idea in a few words. |
| Decision | `Decide: the question?` Assigned to the person who decides, with a decide-by date. |
| UAT | `UAT: the app and the release`. |
