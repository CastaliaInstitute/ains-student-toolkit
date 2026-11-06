# Course Integration Plan

This toolkit is the shared reference for common student workflows across AINS courses. Course pages remain authoritative for course-specific requirements, activities, and submission rules.

## Linking standard

1. Add a short **Student tool help** link near the start of each course home page or syllabus, pointing to the toolkit’s student entry page.
2. At first important use of a tool term in a module, link the term to the relevant tutorial or glossary anchor. Avoid linking every repeated instance; use the first-use rule so links remain helpful rather than distracting.
3. At each lab launch, link “Open in Colab” to the specific notebook and link “Colab” to the central Colab guide. State whether Google sign-in is needed and how to save a copy.
4. At GitHub invitation, repository, branch, commit, or pull request instructions, link the corresponding glossary entry and the GitHub tutorial. State whether sign-in and course access are required.
5. At Codespaces instructions, link the Codespaces guide and explain the course-specific reason to use it.
6. Where a course provides a Codespace, include the Copilot and Copilot Chat extensions in its devcontainer configuration and add repository instructions that help Copilot answer using that course's student-facing materials. Link students to the toolkit's [Copilot Chat guide](https://github.com/CastaliaInstitute/ains-student-toolkit/blob/main/tutorials/codespaces.md#ask-the-toolkit-with-copilot-chat). Installing extensions does not provide a Copilot entitlement or override organization policy.
7. At errors or setup instructions, link to Troubleshooting. Include the exact help information students should report.
8. Do not create course-file links that point to another repository’s relative file. Link to the published toolkit page or stable GitHub `blob/main` URL.

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
| Copilot, Copilot Chat | `tutorials/codespaces.md#ask-the-toolkit-with-copilot-chat` and `glossary/README.md#copilot-chat` |
| Model, dataset, feature, baseline, synthetic data | matching anchors in `glossary/README.md` |
| LLM, generative AI, prompt, machine learning | matching anchors in `glossary/README.md` |

## Rollout sequence

- **Pass 1 — Foundational and core courses:** add the course-entry link to AINS5001 and AINS6001–AINS6009. Prioritize the opening modules of AINS6001 and the Python-intensive AINS6007.
- **Pass 2 — Specializations:** add the same entry link to AINS6100–AINS6102, AINS6200–AINS6202, and AINS6300–AINS6302.
- **Pass 3 — Context links:** add first-use links at actual tool instructions and technical terms; avoid mass-linking every repeated word.
- **Pass 4 — Keep current:** review tool screenshots and interface names each term; accept corrections through course support or repository issues.

### Repository coverage

The rollout covers these 19 AINS course repositories:

- Foundational/bridge: [`AINS5001`](https://github.com/Aurnova/AINS5001) (AIMA5001/AINS5001 course materials).
- Core: [`ains-6001-foundations-of-artificial-intelligence`](https://github.com/CastaliaInstitute/ains-6001-foundations-of-artificial-intelligence), [`ains-6002-machine-learning-and-predictive-modeling`](https://github.com/CastaliaInstitute/ains-6002-machine-learning-and-predictive-modeling), [`ains-6003-deep-learning-and-neural-networks`](https://github.com/CastaliaInstitute/ains-6003-deep-learning-and-neural-networks), [`ains-6004-natural-language-processing`](https://github.com/CastaliaInstitute/ains-6004-natural-language-processing), [`ains-6005-ai-ethics-law-and-policy`](https://github.com/CastaliaInstitute/ains-6005-ai-ethics-law-and-policy), [`ains-6006-big-data-management-for-ai-applications`](https://github.com/CastaliaInstitute/ains-6006-big-data-management-for-ai-applications), [`ains-6007-applied-ai-programming-with-python`](https://github.com/CastaliaInstitute/ains-6007-applied-ai-programming-with-python), [`ains-6008-ai-project-management-and-deployment`](https://github.com/CastaliaInstitute/ains-6008-ai-project-management-and-deployment), [`ains-6009-capstone-project`](https://github.com/CastaliaInstitute/ains-6009-capstone-project).
- Healthcare: [`ains-6100-ai-in-medical-imaging`](https://github.com/CastaliaInstitute/ains-6100-ai-in-medical-imaging), [`ains-6101-predictive-analytics-in-population-health`](https://github.com/CastaliaInstitute/ains-6101-predictive-analytics-in-population-health), [`ains-6102-ai-for-clinical-decision-support`](https://github.com/CastaliaInstitute/ains-6102-ai-for-clinical-decision-support).
- Business: [`ains-6200-ai-for-marketing-and-customer-insights`](https://github.com/CastaliaInstitute/ains-6200-ai-for-marketing-and-customer-insights), [`ains-6201-automation-and-process-optimization`](https://github.com/CastaliaInstitute/ains-6201-automation-and-process-optimization), [`ains-6202-ai-strategy-for-executives`](https://github.com/CastaliaInstitute/ains-6202-ai-strategy-for-executives).
- Cybersecurity: [`ains-6300-ai-in-threat-detection`](https://github.com/CastaliaInstitute/ains-6300-ai-in-threat-detection), [`ains-6301-automated-response-systems`](https://github.com/CastaliaInstitute/ains-6301-automated-response-systems), [`ains-6302-ai-for-risk-assessment`](https://github.com/CastaliaInstitute/ains-6302-ai-for-risk-assessment).

Some courses also have public cohort clones or classroom starter templates in the Aurnova organization. When students enter through those delivery repositories, include the toolkit link there too or make sure it is inherited from the course template. Do not count each clone or module template as a separate course.

## Repository checklist

For each course repository, update only the public student-facing home/introduction and relevant student module pages. Keep instructor-only notes, solutions, grading decisions, and course-specific submission policies in their existing locations. Where a repository already has a setup guide, link to the shared toolkit for common fundamentals and retain only course-specific details locally. Add the Copilot extension and course-aware Copilot instructions only to repositories that offer a student Codespace; explain that access depends on the student's account and organization policy.
