# Social Assistance Exam Lab

A responsive Traditional Chinese exam-practice website based on the uploaded 144-page lecture PDF **「單元8 社會救助政策與法規」**.

## Project branch

- Branch: `social-assistance-exam-lab`
- Main app: `index.html`
- No build system, packages, database, API key, or server required.

## Features

- Topic filters: poverty concepts and measurement, Children's Future Education and Development Account, low-/middle-low-income eligibility, and Social Assistance Act.
- Standard practice and Nightmare Mode.
- Randomised question order, immediate marking, explanations, and lecture page references.
- Local progress, accuracy and wrong-answer review.
- Add custom four-option questions from the site itself, including category, correct answer, explanation, and source page.
- Export and import custom questions as JSON to back up or transfer the expanding bank.
- Custom questions immediately join the selectable practice bank; completing one session does not close the question bank.

## Run locally

Open `index.html` in a browser. No build step or dependencies are required.

## Deploy with GitHub Pages

1. Open repository Settings → Pages.
2. Select **Deploy from a branch**.
3. Choose `social-assistance-exam-lab` and `/(root)`, then Save.
4. Wait for GitHub Pages to publish the site.

## Source and accuracy

Questions are practice rewrites and scenario applications based on the user-provided lecture PDF. They are not represented as official examination questions. Explanations cite lecture page numbers. Where the lecture contains year-specific amounts, dates, or legal descriptions, the website treats the lecture as the exam source and flags that current official rules should be checked before practical use.

## Storage note

Progress and custom questions use the browser's localStorage. Use **匯出題庫 JSON** regularly to keep a portable backup; local data is not automatically synchronised across devices or browsers.
