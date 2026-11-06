# GitHub Codespaces Basics

GitHub Codespaces provides a development workspace in your browser. A course may use it when an activity needs a complete project, multiple files, a terminal, or Git.

The [AINS Student Toolkit repository](https://github.com/CastaliaInstitute/ains-student-toolkit) is configured to include the GitHub Copilot and Copilot Chat extensions in newly created Codespaces. This lets you ask questions about the tool guides and glossary while you work.

## Before opening a Codespace

- Confirm that the activity requires Codespaces. It is not needed just to read a course page or run a Colab-only lab.
- Sign in to the GitHub account that has access to the course repository.
- Check that the repository is the one named in your course instructions.

## Typical steps

1. Open the repository page.
2. Select **Code → Codespaces → Create codespace** (wording may vary by repository).
3. Wait for the workspace setup to finish.
4. Open the notebook or file named in the activity.
5. Save your work and follow the assignment’s submission steps. A Codespace does not submit work automatically.

## Ask the toolkit with Copilot Chat

1. [Create a Codespace for this toolkit](https://codespaces.new/CastaliaInstitute/ains-student-toolkit) or open the Codespace you already made.
2. Sign in to GitHub inside the Codespace if asked. In the Chat view, sign in to Copilot with the GitHub account that has Copilot access.
3. Select **Ask** mode so Copilot answers without editing files. If the Chat view is hidden, open it from the Activity Bar or the Command Palette.
4. Ask a focused question. To direct Copilot to the toolkit files, try:

   > `#codebase I am new to coding. Explain how to save my Colab notebook in plain language. Use this repository's guide, link the section you used, and do not edit any files.`

5. Check the linked guide or glossary entry in Copilot's response. Ask a follow-up if a step is unclear.

Copilot can answer about the content in the open toolkit workspace. For a question about a specific course's lesson, assignment, due date, grading, or private repository, open or attach that course material and follow its instructions. The toolkit does not define course policies.

### Access and limits

- Installing the extension in a Codespace does not grant a Copilot plan or override an organization policy. Sign in with an account that has Copilot access; [Copilot Free](https://docs.github.com/en/copilot/how-tos/manage-your-account/get-started-with-a-copilot-plan) is one current option with limited usage.
- Organization owners can control which Copilot features are available. If Chat is missing or unavailable, check the account and organization settings or contact course support.
- Codespaces use GitHub account authorization and compute allowance. A public repository can be read without signing in, but creating a Codespace requires a GitHub account.
- The repository's `.devcontainer/devcontainer.json` requests the Copilot extensions for new Codespaces. If you already have a Codespace, pull the configuration change and rebuild the container to apply it. See GitHub's guide to [using Copilot in Codespaces](https://docs.github.com/en/codespaces/reference/using-github-copilot-in-github-codespaces).

Copilot is useful for explanations and examples, but can make mistakes. Compare its answer with the linked course materials, and ask your instructor about course-specific requirements.

Codespaces usage may count against an account or organization allowance. Use it when assigned; use Colab for the guided notebook path when offered. If setup fails or the repository is unauthorized, see [GitHub basics](github.md) and [Troubleshooting](troubleshooting.md).
