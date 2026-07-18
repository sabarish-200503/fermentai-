                                         FermentAI
                               Fermentation Decision Support System
                      [ Bioprocess Engineering ]  [ MIT License ]  [ HTML + CSS + JS ]

AI-powered knowledge-based expert system for fermentation process optimization and fault diagnosis in bioreactor operations.

 Live Demo: https://yourusername.github.io/fermentai

About
FermentAI is a web-based decision support tool built as a  research project in Bioprocess Engineering. It helps researchers and students make fast, expert-level    decisions during bioreactor operations — without needing a specialist present.

The system uses a Knowledge-Based Expert System (KBES) approach, where bioprocess engineering principles are encoded as rules to provide real-time recommendations.

Why it matters:
• Fermentation parameters (pH, temperature, DO) directly impact product yield
• Delays in fault detection can ruin entire batches worth thousands of dollars
• Junior researchers often lack experience to troubleshoot complex problems quickly
• FermentAI bridges this gap with instant, structured, science-backed guidance

- Features
1. Parameter Advisor
• Choose from 6 fermentation organisms with pre-loaded optimal ranges
• Adjust Temperature, pH, Dissolved Oxygen, and Agitation via interactive sliders
• Live status badges: Optimal / Low / High per parameter
• Instant optimization report with parameter score

2. Fault Troubleshooter
Diagnose 10 common fermentation problems:
• Excessive foam formation
• pH dropping too fast / rising unexpectedly
• Dissolved oxygen (DO) crash near zero
• Low or stalled cell growth
• Culture contamination suspected
• High viscosity or mixing issues
• Low product yield
• Temperature control failure
• Cell lysis or death observed

Each diagnosis includes:
• Root cause analysis
• Step-by-step immediate corrective actions
• Prevention tips for next run
• Criteria for when to abort the run

3. Organisms Supported

Organism	Type	Temp Range	pH Range	DO Range
E. coli	Aerobic bacterial	35–39°C	6.8–7.5	20–80%
S. cerevisiae	Yeast fermentation	28–32°C	4.5–6.5	10–60%
Lactobacillus sp.	Lactic acid	35–40°C	5.5–7.0	0–20%
Aspergillus niger	Fungal	28–35°C	3.5–6.0	30–80%
CHO cells	Mammalian culture	36–38°C	7.0–7.4	30–60%
Bacillus subtilis	Aerobic bacterial	35–40°C	6.5–7.5	20–70%

🛠️ Tech Stack

Layer	Technology	Purpose
Structure	HTML5	Page layout and content
Styling	CSS3	Responsive design, animations
Logic	Vanilla JavaScript	Expert system engine, UI interactions
AI Engine	Rule-based knowledge base	Organism-specific recommendations
Fonts	DM Sans + DM Serif Display	Typography (Google Fonts)
Icons	Font Awesome 6	UI icons
Hosting	GitHub Pages	Free web hosting

Zero external dependencies — no Node.js, no npm, no frameworks. Pure HTML/CSS/JS.

📁 Project Structure
fermentai/
├── index.html     ← Complete web application (HTML + CSS + JS + knowledge base)
├── README.md      ← Project documentation
└── LICENSE        ← MIT License

 Knowledge Base References

Reference	Used For
Bailey & Ollis — Biochemical Engineering Fundamentals, McGraw-Hill	Growth conditions, enzyme kinetics
Shuler & Kargi — Bioprocess Engineering: Basic Concepts, Prentice Hall	Process parameters, bioreactor design
Doran — Bioprocess Engineering Principles, Academic Press	Mass transfer, dissolved oxygen, mixing
Stanbury et al. — Principles of Fermentation Technology	Troubleshooting, contamination control
Schmidt (2005) — Optimization of industrial fermentation, Appl Microbiol Biotechnol	Scale-up and optimization strategies

 Academic Context

Field	Detail
Project Title	Development of a Knowledge-Based Decision Support System for Fermentation Process Optimization and Fault Diagnosis
Domain	Bioprocess Engineering — Fermentation & Bioreactors
Approach	Knowledge-Based Expert System (KBES)

🔮 Future Work
• 📊 Growth kinetics calculator (Monod model — µmax, Ks, yield)
• 📄 PDF report generator for each analysis session
• 📈 CSV data upload and fermentation trend analysis
• 🤖 Live AI integration (Claude / GPT API) for dynamic answers
• 📱 Progressive Web App (PWA) — installable on mobile without App Store
• 🔗 OPC-UA / MQTT real bioreactor sensor data integration
• 🧬 Expanded organism database (Pichia pastoris, Streptomyces, insect cells)


👨‍🔬 Author

Sabarish.G
B.tech Biotechnology 
📧 [your.email@university.ac.in]
🔗 GitHub: https://github.com/yourusername

🙏 Acknowledgements

• Anthropic Claude — AI assistance in development

🚀 How to Use
Option 1 — Run Locally (No Internet Needed)
• Step 1: Download or clone this repository
• Step 2: Double-click index.html — opens in Chrome, Edge, or Firefox
• Step 3: Use the tool immediately — zero setup required

Option 2 — Live Web Version
Visit: https://yourusername.github.io/fermentai

Option 3 — Clone via Git
git clone https://github.com/yourusername/fermentai.git

 License
This project is licensed under the MIT License — free to use, modify, and distribute with attribution.

MIT License — Copyright (c) 2025 [Your Full Name]
Permission is hereby granted, free of charge, to any person obtaining a copy of this software to deal in the Software without restriction, including rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies — subject to the above copyright notice being included in all copies.

                                              Built with ❤️ for the Bioprocess Engineering community
                                                  ⭐ Star this repo on GitHub if it helped you!
