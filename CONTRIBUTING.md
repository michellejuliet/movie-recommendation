# CONTRIBUTING

First off, thanks for taking the time to contribute! 

All types of contributions are encouraged and valued. See the [Table of Contents](#table-of-contents) for different ways to help and details about how this project handles them. Please make sure to read the relevant section before making your contribution. It will make it a lot easier for us maintainers and smooth out the experience for all involved. The community looks forward to your contributions. 

> And if you like the project, but just don't have time to contribute, that's fine. There are other easy ways to support the project and show your appreciation, which we would also be very happy about:
> - Star the project
> - Tweet about it
> - Refer this project in your project's readme
> - Mention the project at local meetups and tell your friends/colleagues


## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [I Have a Question](#i-have-a-question)
- [I Want To Contribute](#i-want-to-contribute)
- [Reporting Bugs](#reporting-bugs)
- [Suggesting Enhancements](#suggesting-enhancements)
- [Your First Code Contribution](#your-first-code-contribution)
- [Improving The Documentation](#improving-the-documentation)
- [Styleguides](#styleguides)
- [Commit Messages](#commit-messages)
- [Join The Project Team](#join-the-project-team)


## Code of Conduct

This project and everyone participating in it is governed by the
[CONTRIBUTING.md Code of Conduct](blob/main/CONTRIBUTING.md).
By participating, you are expected to uphold this code. Please report unacceptable behavior
to <>.


## I Have a Question

> If you want to ask a question, we assume that you have read the available [Documentation]().

Before you ask a question, it is best to search for existing [Issues](/issues) that might help you. In case you have found a suitable issue and still need clarification, you can write your question in this issue. It is also advisable to search the internet for answers first.

If you then still feel the need to ask a question and need clarification, we recommend the following:

- Open an [Issue](/issues/new).
- Provide as much context as you can about what you're running into.
- Provide project and platform versions (nodejs, npm, etc), depending on what seems relevant.

We will then take care of the issue as soon as possible.



## I Want To Contribute

> ### Legal Notice 
> When contributing to this project, you must agree that you have authored 100% of the content, that you have the necessary rights to the content and that the content you contribute may be provided under the project license.

### Reporting Bugs


#### Before Submitting a Bug Report

A good bug report shouldn't leave others needing to chase you up for more information. Therefore, we ask you to investigate carefully, collect information and describe the issue in detail in your report. Please complete the following steps in advance to help us fix any potential bug as fast as possible.

- Make sure that you are using the latest version.
- Determine if your bug is really a bug and not an error on your side e.g. using incompatible environment components/versions (Make sure that you have read the [documentation](). If you are looking for support, you might want to check [this section](#i-have-a-question)).
- To see if other users have experienced (and potentially already solved) the same issue you are having, check if there is not already a bug report existing for your bug or error in the [bug tracker](issues?q=label%3Abug).
- Also make sure to search the internet (including Stack Overflow) to see if users outside of the GitHub community have discussed the issue.
- Collect information about the bug:
- Stack trace (Traceback)
- OS, Platform and Version (Windows, Linux, macOS, x86, ARM)
- Version of the interpreter, compiler, SDK, runtime environment, package manager, depending on what seems relevant.
- Possibly your input and the output
- Can you reliably reproduce the issue? And can you also reproduce it with older versions?


#### How Do I Submit a Good Bug Report?

> You must never report security related issues, vulnerabilities or bugs including sensitive information to the issue tracker, or elsewhere in public. Instead sensitive bugs must be sent by email to <>.


We use GitHub issues to track bugs and errors. If you run into an issue with the project:

- Open an [Issue](/issues/new). (Since we can't be sure at this point whether it is a bug or not, we ask you not to talk about a bug yet and not to label the issue.)
- Explain the behavior you would expect and the actual behavior.
- Please provide as much context as possible and describe the *reproduction steps* that someone else can follow to recreate the issue on their own. This usually includes your code. For good bug reports you should isolate the problem and create a reduced test case.
- Provide the information you collected in the previous section.

Once it's filed:

- The project team will label the issue accordingly.
- A team member will try to reproduce the issue with your provided steps. If there are no reproduction steps or no obvious way to reproduce the issue, the team will ask you for those steps and mark the issue as `needs-repro`. Bugs with the `needs-repro` tag will not be addressed until they are reproduced.
- If the team is able to reproduce the issue, it will be marked `needs-fix`, as well as possibly other tags (such as `critical`), and the issue will be left to be [implemented by someone](#your-first-code-contribution).




### Suggesting Enhancements

This section guides you through submitting an enhancement suggestion for CONTRIBUTING.md, **including completely new features and minor improvements to existing functionality**. Following these guidelines will help maintainers and the community to understand your suggestion and find related suggestions.


#### Before Submitting an Enhancement

- Make sure that you are using the latest version.
- Read the [documentation]() carefully and find out if the functionality is already covered, maybe by an individual configuration.
- Perform a [search](/issues) to see if the enhancement has already been suggested. If it has, add a comment to the existing issue instead of opening a new one.
- Find out whether your idea fits with the scope and aims of the project. It's up to you to make a strong case to convince the project's developers of the merits of this feature. Keep in mind that we want features that will be useful to the majority of our users and not just a small subset. If you're just targeting a minority of users, consider writing an add-on/plugin library.


#### How Do I Submit a Good Enhancement Suggestion?

Enhancement suggestions are tracked as [GitHub issues](/issues).

- Use a **clear and descriptive title** for the issue to identify the suggestion.
- Provide a **step-by-step description of the suggested enhancement** in as many details as possible.
- **Describe the current behavior** and **explain which behavior you expected to see instead** and why. At this point you can also tell which alternatives do not work for you.
- You may want to **include screenshots and animated GIFs** which help you demonstrate the steps or point out the part which the suggestion is related to. You can use [this tool](https://www.cockos.com/licecap/) to record GIFs on macOS and Windows, and [this tool](https://github.com/colinkeenan/silentcast) or [this tool](https://github.com/GNOME/byzanz) on Linux. 
- **Explain why this enhancement would be useful** to most CONTRIBUTING.md users. You may also want to point out the other projects that solved it better and which could serve as inspiration.



### Your First Code Contribution

Thanks for wanting to contribute! Here’s a clear, low-friction path to make your first contribution successful.

1. Find something to work on
Look for issues labeled good first issue or help wanted.
If nothing exists, check issues for small bugs or documentation tasks you can tackle.

2. Claim the issue
Leave a short comment on the issue: “I’d like to work on this” and mention your GitHub handle. This avoids duplicate work.

3. Fork → Clone → Setup
```
# fork repo on GitHub, then:
git clone https://github.com/<your-username>/movie-recommendation.git
cd movie-recommendation
# follow README for install
pip install -r requirements.txt   # Python repo
# or for server repo:
npm install
```

4. Create a feature branch
Branch names should be descriptive and follow the pattern:
```
<type>/<short-description>-<issue-number>
# examples:
feat/add-recommendation-endpoint-42
fix/readme-typo-17
```
```
git checkout -b feat/add-recommendation-endpoint-42
```

5. Make small, focused changes
One logical change per PR.
Write tests for behavior changes (unit / integration) and ensure existing tests pass.
Run linters/formatters before committing.

6. Run tests & linters
Examples:
```
# Python
pytest
flake8

# Node/TS
npm test
npm run lint
```

7. Commit & push
Follow the Commit Messages rules below. Push your branch:
```
git push origin feat/add-recommendation-endpoint-42
```

8. Open a Pull Request
Base: `main` (or `develop` if the repo uses it).
Title: short + references issue (`#42`).
Body: describe what you changed, why, and how to test. Link the issue: `Fixes #42` if applicable.
Add screenshots or sample output for UI / notebook changes.

9. Respond to review
Address comments with small commits or force-push a rebased branch (`git rebase`) if requested.
Keep the conversation polite and focused.

10. After merge
Pull latest `main` locally and delete your branch:
```
git checkout main
git pull upstream main
git branch -d feat/add-recommendation-endpoint-42
git push origin --delete feat/add-recommendation-endpoint-42
```

### Improving The Documentation
Good documentation reduces friction massively. Here’s how contributors can help and what to expect.

**Areas to improve**
- README examples (how to run, minimal example, expected outputs)
- `NOTES.md` or `USAGE.md` for complex flows (data prep, training, serving)
- Inline code comments & docstrings
- Notebook cleanup: remove sensitive/hardcoded paths, add a top “Run this first” block
- Add or improve `CONTRIBUTING.md` (you’re reading it 😉)
- Add architecture diagrams (e.g., `docs/diagrams/`)

**Documentation standards**
- Keep docs in Markdown (.md). Use short paragraphs, bullet lists, and code blocks.
- Include a short “Getting started” section with:
    - Environment setup
    - How to run tests
    - How to train / run model
    - How to serve model locally
- Add reproducible examples: commands that copy/paste and run.

**Doc PR checklist (use in PR description)**
- [ ] README updated (if needed)
- [ ] Examples tested locally
- [ ] Notebooks runnable from project root (relative paths)
- [ ] No personal/local absolute paths or secrets
- [ ] Added/updated `requirements.txt` or `package.json` if new deps

**Doc formatting & tooling**
- Prefer lightweight diagrams (draw.io, mermaid). Store diagram sources (if any).
- If documentation grows, consider `mkdocs` or Sphinx for a docs site later.

## Styleguides
Consistency is key. Below are the recommended style rules for both repositories (ML and server).

**Python (ML repo)**
- Formatting: *Black* (opinionated formatter)
```
pip install black
black .
```
- Imports: *isort* for sorted imports.
```
pip install isort
isort .
```
- Linting: *flake8* or *pylint* for static checks.
```
pip install flake8
flake8 .
```
- Type hints: Use mypy optionally for critical modules.
- Docstrings: Google style or NumPy style. Keep consistent.
- Tests: pytest with fixtures and clear assertions.
- Jupyter notebooks: keep one cleaned notebook per analysis; use nbstripout to strip outputs when committing or include cleared outputs.

**TypeScript / Node (server repo)**
- Formatting: Prettier (publish configuration in `.prettierrc`).
- Linting: ESLint with TypeScript rules enabled.
- Typing: `strict` mode in `tsconfig.json` recommended.
- Code style: follow Airbnb/Google-ish rules adapted to project (document exceptions).
- Tests: Jest (unit tests) and supertest (endpoint tests).

**Naming & structure conventions**
- File names: `snake_case` for Python modules, `kebab-case` or `camelCase` for JS/TS files as your existing style prefers — be consistent.
- Branch names: see “Your First Code Contribution.”
- Configuration: store secrets in environment variables and provide `.env.example`.

**Automated checks (recommended)**
- Configure CI (GitHub Actions) to run:
    - Linter
    - Formatter check
    - Tests
    - Basic static analysis

### Commit Messages
We use Conventional Commits. This makes changelogs and automation easier.
**Format**
```
<type>(<scope>): <short summary>

<body>          # optional, more explanation, wrap at ~72 chars
<footer>        # optional, reference issues: Closes #42
```

**Types (common)**
- `feat`: a new feature
- `fix`: a bug fix
- `docs`: documentation only changes
- `style`: formatting, missing semi-colons, etc (no code changes)
- `refactor`: code change that neither fixes a bug nor adds a feature
- `perf`: performance improvement
- `test`: adding or fixing tests
- `chore`: build process or auxiliary tool changes

**Examples**
```
feat(recommender): add content-based recommend function

Adds a simple TF-IDF genre similarity-based recommender. This
is intended as a baseline until collaborative filtering is integrated.

Closes #73
```

```
fix(readme): correct dataset instructions

Clarified how to download and place MovieLens datasets in /data/raw.
```

```
docs(contributing): add contributing checklist
```

**Best practices**
- Keep subject line ≤ 72 characters.
- Use imperative mood: “Add”, “Fix”, “Update”.
- Use the body to explain why (not just what).
- Reference issues in the footer (Closes #12, Refs #36).
- Sign commits if project requires DCO (--signoff).

**Squash vs. preserve history**
- Small PRs: keep atomic commits.
- If requested by maintainers, squash into one meaningful commit before merge.
- Use git rebase -i to clean up local history before pushing.