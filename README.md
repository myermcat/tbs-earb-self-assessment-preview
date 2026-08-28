# GC Enterprise Architecture self-assessment, preview

A working preview of the self-assessment tool for the Government of Canada Enterprise
Architecture framework. Open it here:

**https://myermcat.github.io/tbs-earb-self-assessment-preview/**

Departments score their own architecture against the framework, attach the evidence they
already hold, and produce a structured file. Assessors audit the few answers that do not add
up, and skip the rest.

## What you are looking at

One HTML file. There is no server, no database and no account. The page declares
`default-src 'none'; connect-src 'none'`, a browser rule that blocks every outbound request,
so nothing you type here reaches anyone. Answers are kept by your own browser and written to a
file when you choose to save one.

That means you can try it with real material at your own classification. Nothing you enter
leaves your machine.

## Status

A prototype, and the question set is a draft. Scores, thresholds and routing advice are not
approved by anyone and should not be used to make a decision about an initiative.

Source for the tool lives in a separate private repository. This one holds only the built
page.
