# Grad Days: Machine Learning for Physicists, hands-on sessions

Lecture notes and notebooks for the hands-on sessions (11:30–12:30) of the four-day lecture series.
Each notebook runs on a CPU in a few minutes, no GPU needed.

| Day | Topic | Notes | Exercise | Solutions |
|-----|-------|-------|----------|-----------|
| 1 | Classifiers and the likelihood ratio | [PDF](Day1_Intro_and_Classifiers/Day1_notes_public.pdf) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SaschaDief/grad-days-ml-tutorials/blob/main/Day1_Intro_and_Classifiers/Day1_Tutorial_Exercise.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SaschaDief/grad-days-ml-tutorials/blob/main/Day1_Intro_and_Classifiers/Day1_Tutorial_Solutions.ipynb) |
| 2 | Generative models: normalizing flows, diffusion, conditional generation | [PDF](Day2_Generative_Models/Day2_notes_public.pdf) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SaschaDief/grad-days-ml-tutorials/blob/main/Day2_Generative_Models/Day2_Tutorial_Exercise.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SaschaDief/grad-days-ml-tutorials/blob/main/Day2_Generative_Models/Day2_Tutorial_Solutions.ipynb) |
| 3 | Weighted events, reweighting, and transformers | after the session | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SaschaDief/grad-days-ml-tutorials/blob/main/Day3_LikelihoodRatio_and_Transformers/Day3_Tutorial_Exercise.ipynb) | after the session |
| 4 | Learning uncertainties | | available on day 4 | |

Solutions and notes are added after each session.

The lecture notes draw heavily on *Modern Machine Learning for LHC Physicists* by T. Plehn, A. Butter, B. Dillon, T. Heimel, C. Krause, and R. Winterhalder, [arXiv:2211.01421](https://arxiv.org/abs/2211.01421). Each PDF states at the top which parts are taken from or adapted from it, and how generative AI was used in preparing it.

## How to run

**Google Colab (recommended).** Click the badge for the day. Colab opens the notebook directly from this repository.
To keep your changes, use *File → Save a copy in Drive* before you start editing.
Run the cells from top to bottom with `Shift+Enter`.

**Without a Google account.** Use Binder, which needs no account but takes a minute or two to start:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/SaschaDief/grad-days-ml-tutorials/main)

**Locally.** Install the packages in `requirements.txt` (`pip install -r requirements.txt`) and open the notebook with Jupyter.
