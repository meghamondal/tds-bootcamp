---
---

--- Before Day-3 ---
I already knew basic Python programming and had some experience using VS Code.
---

## Day-3 Checklist

- [x] I can run a Python script using `uv run script.py` without setting up a local virtual environment
- [x] I know where the temporary virtual environment is created when running the `uv add --script script.py pandas` command followed by `uv run script.py`
- [x] I can create a new Python project using `uv init` and understand what `pyproject.toml` is used for
- [x] I can add a dependency (e.g., `requests`) using `uv add` and see it reflected in the lockfile
- [x] I can create a traditional virtual environment using `uv venv` and know when to use it
- [x] I understand why installing packages globally with `pip install` is a bad habit
- [x] I can open a project in VS Code, select the correct Python interpreter, and run code from the integrated terminal
- [x] I know the difference between a `.py` script and a `.ipynb` notebook, and when to use each

--- After Day-3 ---
I learned how to manage Python projects using uv, work with virtual environments, handle dependencies through pyproject.toml, and choose between scripts and notebooks based on the task.
---

--- Feedback (Suggestions for the TDS Team) ---
The session made Python project setup and dependency management much easier to understand. The hands-on demonstration of uv commands and virtual environments was especially helpful.
---

---
---

Personal Notes:
Useful commands:
uv init
uv add requests
uv run script.py
uv venv

Remember:
- pyproject.toml stores project configuration.
- Virtual environments keep dependencies isolated.
- Use .py for scripts and .ipynb for exploratory analysis.
