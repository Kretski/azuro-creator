🚀 AZURO Creator
AI that discovers physical & mathematical laws from your data — not just predictions

AZURO Creator is a local AI tool that automatically extracts interpretable equations from input-output datasets (CSV).
Instead of training black-box models, it generates human-readable mathematical hypotheses, evaluates their accuracy (R²), and suggests real-world insights.

Upload data → get the formula.
Exploring neuro-symbolic ideas in practice: an offline tool that uses ML diagnostics to guide symbolic equation discovery.

Quick raw console demo on partially synthetic data:

https://youtu.be/ozjpEiNSDKc

Result: recovers y = x₁² (x₁ ≤ 5) / y = x₁·sin(x₃) (x₁ > 5) – completely local, cloud-free.

Early prototype testing whether ML behavioral priors can effectively constrain symbolic search.

Thoughts from the group:
- A viable direction for neuro-symbolic AI?
- Biggest challenges you see in hybrid ML-symbolic pipelines?
- Any similar approaches you’ve seen/tested?

Repository: https://github.com/Kretski/azuro-creator

Open for feedback!
🧠 What Makes It Different

Most ML tools give you predictions.
AZURO gives you the law behind the data.

Typical ML	AZURO Creator
Black-box models	Clear mathematical equations
Requires cloud/GPU	Fully offline & local
Hard to interpret	Human-readable formulas
Focus on accuracy	Accuracy + understanding
✨ Main Advantages

🖥 100% Local & Offline – no cloud, no internet, no API keys

🔢 Interpretable Formulas – discover real mathematical relationships![bandicam 2026-01-28 09-57-48-084](https://github.com/user-attachments/assets/ce726d93-5214-41d1-b235-03e66fac5897)
![bandicam 2026-01-28 09-58-36-157](https://github.com/user-attachments/assets/4f27123f-3235-4930-a25d-65ab651695e2)
![bandicam 2026-01-28 09-58-25-633](https://github.com/user-attachments/assets/25f199dc-8381-4caa-89fb-0e3312a28741)
![bandicam 2026-01-28 09-57-59-822](https://github.com/user-attachments/assets/03f46eff-b7d9-4299-92cb-9043814cd594)


📊 Clean Result Tables – compare hypotheses and predictions easily

🎯 Accuracy Evaluation (R²) – rank discovered laws by performance

🧪 Calibration Mode – validate system on known examples

⚡ Standalone Windows .exe – single file, no installation

⚙️ How It Works (Quick Demo)

Download the latest .exe from Releases

Launch the application

Open your browser at: http://127.0.0.1:5000

Load an example dataset or upload your CSV

Click Discover Law

View:

Top mathematical hypotheses

Predictions

R² accuracy scores

🎯 Ideal For

Researchers working with experimental data

Engineering students and simulation analysis

Scientists looking for symbolic relationships

Analysts who need explainable models

Anyone curious about data → equation discovery

🖼 Interface Preview








🔬 Core Idea

AZURO Creator bridges the gap between data-driven AI and scientific law discovery, bringing symbolic reasoning back into practical data analysis — directly on your machine.
🌌 Vision

AZURO Creator is built on a simple but powerful idea:

AI should not only predict — it should help discover the laws behind the data.

While most modern AI systems focus on black-box prediction, AZURO explores a different direction:
turning data into interpretable mathematical structure.

The long-term vision goes beyond a single application.

🔬 From Data → Laws

AZURO aims to bridge the gap between:

Data-driven AI

Scientific modeling

Symbolic reasoning

Instead of producing opaque models, the goal is to enable automated discovery of equations that describe real-world systems — from experimental measurements to engineered processes.

⚙️ Toward Symbolic AI for Engineering

Future development targets:

Discovery of multi-variable and dynamic system relationships

Constraint-aware equation search (physics-informed discovery)

Support for engineering diagrams, system structures, and model priors

Use in system identification and simulation model extraction

AZURO is moving toward becoming an AI assistant for modeling physical and technical systems, not just a data analysis tool.

🤖 Beyond Software — Toward Edge & Hardware

Interpretable laws have a unique advantage over neural models:

They can run anywhere.

Symbolic models discovered by AZURO can be translated into:

Lightweight embedded code

DSP algorithms

Control systems

FPGA/ASIC implementations

This opens a path toward symbolic edge AI, where discovered physical relationships become part of real-time systems and hardware.

🧠 AI-Assisted Scientific Discovery

AZURO represents a step toward a broader idea:

AI as a tool for hypothesis generation and scientific insight.

By helping uncover candidate laws from data, systems like AZURO could accelerate research cycles, support experimental analysis, and assist in exploring complex systems where explicit models are unknown.

🎯 Long-Term Direction

AZURO Creator explores a shift from:

Pattern recognition → Rule discovery
Prediction → Understanding
Models → Laws

The vision is to build technology that helps transform raw data into structured knowledge — usable in software, engineering systems, and eventually hardware itself.
📄 License

MIT License


