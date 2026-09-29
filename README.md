# Artificial Intelligence - Spring 1405 - SUT

Coursework for the undergraduate **Artificial Intelligence** course at Sharif University of Technology, Spring 1405 (2026).

- **Instructor:** [Arash Marioriyad](https://scholar.google.com/citations?user=WHz9vAYAAAAJ&hl=en)
- **Student:** Kasra Sheikhy
- **Institution:** Sharif University of Technology
- **Semester:** Spring 1405

This repository contains the submitted theoretical solutions, original question sheets when available, and practical Jupyter notebooks with their required datasets and helper modules. Generated files, virtual environments, duplicate archives, and editor metadata have been intentionally excluded.

## Assignments

| Assignment | Topics | Theoretical | Practical |
| --- | --- | --- | --- |
| [HW 1](assignments/hw01-search) | Uninformed, informed, and local search | Question + solution | - |
| [HW 2](assignments/hw02-csp-adversarial-search) | Constraint satisfaction and adversarial search | Solution | Tic-Tac-Toe, Nonogram CSP |
| [HW 3](assignments/hw03-probabilistic-models) | Bayesian networks and hidden Markov models | Question + solution | Financial MAP estimation, DNA HMM |
| [HW 4](assignments/hw04-machine-learning) | Machine-learning fundamentals | Question + solution | Decision trees, random forests, ML from scratch |
| [HW 5](assignments/hw05-reinforcement-learning) | MDPs and reinforcement learning | Question + solution + LaTeX source | MDP, Q-Learning, SARSA |

> The standalone theoretical question sheet for HW 2 was not present in the original course archive. Its submitted solution is preserved, while the practical prompts remain embedded in the notebooks.

## Repository layout

```text
assignments/
  hwXX-topic/
    theoretical/
      question.pdf
      solution.pdf
    practical/
      exercise-name/
        notebook.ipynb
        data-and-helper-files
```

## Running the notebooks

Use Python 3.10 or newer, preferably in a virtual environment:

```bash
python -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
jupyter lab
```

Open a notebook from its own directory so relative dataset and helper-module paths resolve correctly.

## Academic-use note

These materials are published as a personal course archive. If you are currently taking the course, follow your instructor's collaboration and academic-integrity policies and use the solutions only for review after attempting the problems yourself.

---

## فارسی

این مخزن آرشیو مرتب تمرین‌های درس **هوش مصنوعی** دانشگاه صنعتی شریف در بهار ۱۴۰۵ با تدریس [آرش ماری‌اوریاد](https://scholar.google.com/citations?user=WHz9vAYAAAAJ&hl=en) است. پاسخ‌های تئوری، صورت‌سؤال‌های موجود، نوت‌بوک‌های عملی و داده‌های لازم نگه‌داری شده‌اند و فایل‌های تکراری، محیط‌های مجازی و خروجی‌های موقت حذف شده‌اند.

