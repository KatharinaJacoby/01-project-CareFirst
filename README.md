Hamburg SafetyMamba Hybrid Prototype
> A human-centered machine learning model inspired by real-world ambulance system data,
aiming to support care, safety, and retention—rather than just logistics optimization.
■ Overview
This project explores an early-stage hybrid architecture combining clinical time series, contextual
features, and system-level stressors to model patient outcomes and staff-related risks. It is
**inspired by** research like the EPONA project, but follows a **more compassionate, patient- and
staff-centered approach**.
■ Motivation
Modern healthcare triage systems often prioritize efficiency metrics over human well-being. This
prototype asks:
compassion?*
*What would an ML model look like if its architecture were guided by values of care, caution, and
■ Features
- Hybrid neural model combining GRU and dense encoders
- Multi-task learning (crisis prediction, burnout risk, staff retention, etc.)
- Structured handling of both clinical and non-clinical data
- Transparent design with full debugging traces and fail→fix history
■ Status
- ■ Data preparation with synthetic and real Hamburg-like datasets
- ■ Initial model architecture complete
- ■ Forward pass verified
- ■ Training loop implemented and evaluated
- ■ Ongoing: Hyperparameter tuning, metrics dashboard, broader generalization
■ Structure
/notebooks ← Jupyter workflows (synthetic + real data)
/models ← Architecture + loss wrappers
/data ← Real/synthetic df generation
/utils ← Config, preprocessing, etc.
/outputs ← Logs, checkpoints, forward pass results
■ Community Notes
This project was initiated and developed by **Katharina**, with the support of AI tooling
(ChatGPT-4). It is shared in the spirit of openness and collaboration on Kaggle, HuggingFace, and
GitHub.
Contributions, questions, and thoughtful critique are welcome—especially those rooted in
human-centered design and system care.
