```mermaid
graph TD
    A[bike-sales-data-cleaning/] --> B[data/]
    B --> B1[raw/ <br/> # Original dataset (uncleaned CSV)]
    B --> B2[cleaned/ <br/> # Final cleaned dataset]

    A --> C[notebooks/]
    C --> C1[01_exploration.ipynb <br/> # Initial data exploration]
    C --> C2[02_cleaning.ipynb <br/> # Detailed cleaning steps]

    A --> D[scripts/]
    D --> D1[cleaning.py <br/> # Python script for cleaning process]

    A --> E[README.md <br/> # Project documentation]
    A --> F[requirements.txt <br/> # List of dependencies]
