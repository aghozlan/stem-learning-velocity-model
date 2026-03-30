# stem-learning-velocity-model
statistical simulation and visualization of how Generative AI impacts the trajectory of student learning in complex sciences.
# The AI-Assisted Classroom: Modeling Student Learning Velocity

## Overview
This repository contains the R-based statistical simulation and visualization code for modeling the impact of Generative AI on student learning trajectories in complex STEM subjects (like Physics and advanced Mathematics). 

Rather than viewing student performance through a traditional normal distribution, this project models learning as **velocity** over time. It visualizes the emerging multi-modal distribution of student outcomes based on their interaction with AI tools.

## The Statistical Narrative
The core visualization—a Diverging Trajectory Plot—is built on a simulated dataset representing a single academic semester. It models three distinct student cohorts:

1. **The Accelerators (High AI Access + Guided Prompting):** Models exponential conceptual gains. Students use AI as a Socratic tutor, resulting in a higher "escape velocity" in complex problem-solving.
2. **The Baseline (Traditional Methods):** Models consistent, linear, but slower growth based on standard curriculum progression.
3. **The Over-Reliant (High AI Access + Unguided Usage):** Models an early illusion of competence (rapid spike) followed by a severe plateau or drop when facing conceptual hurdles that cannot be simply copy-pasted.

## Project Structure
* `/scripts/01_simulate_data.R`: R script utilizing statistical distributions with controlled variance to generate the theoretical student cohort dataset.
* `/scripts/02_visualize_trajectories.R`: The `ggplot2` architecture used to map the data, create the confidence intervals, and shade the "digital divide" gap.
* `/outputs/`: High-resolution renders of the final visualization.

## Tools & Libraries Used
* **Language:** R
* **Libraries:** `tidyverse`, `ggplot2`, `ggtext` (for advanced typographic control), `geomtextpath` (for aligned trajectory labeling).

## Let's Connect
I am an Applied Statistician and Educator passionate about data-driven storytelling, AI integration in education, and building clear visualizations for complex problems. 

* [Connect with me on LinkedIn](https://www.linkedin.com/in/ahmad-ghozlan81)
