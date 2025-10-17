# Job Interview Guide Workshop

This folder contains materials for a job interview preparation workshop as part of the "Foundations of Machine Learning" course. The workshop helps students prepare for technical interviews with practice questions, mock sessions, and guidance on presenting ML projects.

## Contents

- `JobInterviewGuide_Workshop.ipynb` — The main Jupyter notebook containing:
  - Interview question walkthroughs (technical and behavioral)
  - Mock interview session templates
  - Example answers and tips for explaining ML projects
  - Suggested exercises and self-review checklist
- `JobInterviewLLMSession.ipynb` — A notebook demonstrating an LLM-powered mock interview session (if provided)

## Purpose

- Practice common machine learning interview questions and problem-solving approaches.
- Prepare clean verbal explanations of ML concepts and project decisions.
- Run mock interviews (with peers or automated tools) and capture feedback.

## Prerequisites

- Python 3.8+ and Jupyter Notebook/JupyterLab installed.
- Optional: Virtual environment recommended.

To create and activate a virtual environment on Windows PowerShell:

```powershell
python -m venv .venv; .\.venv\Scripts\Activate.ps1
```

If a `requirements.txt` exists in this folder, install the dependencies:

```powershell
pip install -r requirements.txt
```

## How to run

From the repository root, launch Jupyter Lab or Notebook and open `JobInterviewGuide_Workshop.ipynb`:

```powershell
jupyter lab
# or
jupyter notebook
```

For non-interactive execution or testing:

```powershell
jupyter nbconvert --to notebook --execute "JobInterviewGuide_Workshop\JobInterviewGuide_Workshop.ipynb" --output executed_job_interview.ipynb
```

## Tips for using the workshop

- Use the notebook as a script for mock interviews: read questions aloud, write answers, then compare to the example answers.
- Record your mock interview sessions and review for clarity, conciseness, and correct technical details.
- Customize the mock interview templates to match the roles you're applying for (data scientist, ML engineer, research scientist).

## Contribution

- Add new questions or update existing answer explanations via pull requests.
- If you add code examples or helper scripts, include short usage notes and update this README.

## License and citation

Materials were prepared for course use. Check with the course instructor for permission to redistribute or reuse outside the class.

---

If you want, I can:
- Add a `requirements.txt` to this folder (if notebooks need packages)
- Add a short PowerShell script to run the notebook and save outputs
- Convert key textual content into a printable PDF

Tell me which you'd like next.