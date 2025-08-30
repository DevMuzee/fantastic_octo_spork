```mermaid
graph TD
    A[📂 bike-sales-data-cleaning/] --> B[📂 data/];
    B --> B1[📄 raw/ 🗂️ Original dataset uncleaned ];
    B --> B2[📄 cleaned/ ✅ Final cleaned dataset];
    A --> C[📂 notebooks/];
    C --> C1[📓 01_exploration.ipynb 🔎 Initial data exploration];
    C --> C2[📓 02_cleaning.ipynb 🧹 Detailed cleaning steps];
    A --> D[📂 scripts/];
    D --> D1[⚙️ cleaning.py 🐍 Python script for cleaning process];
    A --> E[📜 README.md 📖 Project documentation];
    A --> F[📑 requirements.txt 📦 List of dependencies];
