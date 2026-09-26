# Openwork agent guide repository

`README.md` and `index.html` contain the guide; `_config.yml` provides site metadata. `.github/workflows/pages.yml` uploads the repository directly to GitHub Pages on main. It does not run Jekyll, install packages, or test the onboarding/API examples. There is no application manifest or declared build/test/lint/typecheck command.

Keep the rendered HTML and README instructions consistent, check changed links/anchors, and review example API paths and prerequisite explanations against primary sources when changing them. A standard local static preview (`python3 -m http.server 8000 --bind 127.0.0.1`) is optional; inspect the page for a visual change. Don't infer live API validity from static rendering.

Onboarding, wallet, task, and payment examples describe external operations. Reading or editing them does not authorize registration, skill installation, credential changes, task claims, or financial transactions. Use redacted examples; never insert real credentials or wallet secrets into this public guide. Pushing to main publishes the repository, so follow the task's publication boundary.

## Completing work

Carry the authorized change through the relevant checks and repair failures it causes. Make routine, reversible implementation choices using existing patterns; ask only when missing information, a material product decision, or an authorization boundary prevents the next step. Existing authorization remains valid within its scope. If blocked, name the exact action and missing prerequisite, retain concise evidence, and continue independent work.

Choose verification proportional to the change. For instructions or prose, inspect changed paths, links, and local instruction precedence and run `git diff --check -- <changed-paths>`; don't install dependencies or run the application solely for a prose edit. For behavior changes, exercise the affected behavior and applicable checks below, then broaden only for failures or unresolved risk. Report files changed, checks actually run and their results, commands only inspected, and remaining limitations. A build or source inspection alone does not prove runtime behavior. Continue through already-authorized follow-through; stop at explicit review checkpoints or boundaries requiring new authorization.
