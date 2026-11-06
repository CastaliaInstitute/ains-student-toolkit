# Course Integration Plan

This toolkit is the shared reference for common student workflows across AINS courses. Course pages remain authoritative for course-specific requirements, activities, and submission rules.

## Linking standard

1. Add a short **Student tool help** link near the start of each course home page or syllabus, pointing to the toolkit’s student entry page.
2. At first important use of a tool term in a module, link the term to the relevant tutorial or glossary anchor. Avoid linking every repeated instance; use the first-use rule so links remain helpful rather than distracting.
3. At each lab launch, link “Open in Colab” to the specific notebook and link “Colab” to the central Colab guide. State whether Google sign-in is needed and how to save a copy.
4. At GitHub invitation, repository, branch, commit, or pull request instructions, link the corresponding glossary entry and the GitHub tutorial. State whether sign-in and course access are required.
5. At Codespaces instructions, link the Codespaces guide and explain the course-specific reason to use it.
6. At errors or setup instructions, link to Troubleshooting. Include the exact help information students should report.
7. Do not create course-file links that point to another repository’s relative file. Link to the published toolkit page or stable GitHub `blob/main` URL.

## Recommended snippets

Course landing page:

> **New to the course tools?** Start with the [AINS Student Toolkit](https://github.com/CastaliaInstitute/ains-student-toolkit/blob/main/index.md). You can read course pages in a browser; use Colab, GitHub, or Codespaces only as the activity instructions require.

Colab lab:

> **Tool help:** [Colab setup and saving your work](https://github.com/CastaliaInstitute/ains-student-toolkit/blob/main/tutorials/colab.md) · [Notebook glossary](https://github.com/CastaliaInstitute/ains-student-toolkit/blob/main/glossary/README.md#jupyter-notebook).

GitHub assignment:

> **Tool help:** [GitHub accounts and course access](https://github.com/CastaliaInstitute/ains-student-toolkit/blob/main/tutorials/github.md) · [Troubleshooting](https://github.com/CastaliaInstitute/ains-student-toolkit/blob/main/tutorials/troubleshooting.md).

## Keyword link map

| First-use keyword in a course | Link target |
|---|---|
| Python, variable, function, library | `glossary/README.md#python`, `#variable`, `#function`, `#library` |
| Notebook, cell, runtime | `glossary/README.md#jupyter-notebook`, `#cell`, `#runtime` |
| Colab | `tutorials/colab.md` and `glossary/README.md#colab` |
| Git, GitHub, repository | `tutorials/github.md` and matching glossary anchors |
| Branch, commit, pull request | `tutorials/github.md` and matching glossary anchors |
| Codespaces | `tutorials/codespaces.md` and `glossary/README.md#codespaces` |
| Model, dataset, feature, baseline, synthetic data | matching anchors in `glossary/README.md` |
| LLM, generative AI, prompt, machine learning | matching anchors in `glossary/README.md` |

## Rollout sequence

- **Pass 1 — Core courses:** add the course-entry link to AINS6001–AINS6009. Prioritize the opening modules of AINS6001 and the Python-intensive AINS6007.
- **Pass 2 — Specializations:** add the same entry link to AINS6100–AINS6102, AINS6200–AINS6202, and AINS6300–AINS6302.
- **Pass 3 — Context links:** add first-use links at actual tool instructions and technical terms; avoid mass-linking every repeated word.
- **Pass 4 — Keep current:** review tool screenshots and interface names each term; accept corrections through course support or repository issues.

## Repository checklist

For each course repository, update only the public student-facing home/introduction and relevant student module pages. Keep instructor-only notes, solutions, grading decisions, and course-specific submission policies in their existing locations. Where a repository already has a setup guide, link to the shared toolkit for common fundamentals and retain only course-specific details locally.
