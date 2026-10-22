# DATABRICKS-INTEGRATION


📁 1. Core Code & Artifacts

• Databricks Notebooks (.py, .sql, .scala, .ipynb): The primary data pipelines, machine learning experiments, or ETL tasks. When synced via Databricks Repos, these are typically saved as standard source files containing Databricks text-based syntax headers.
• Shared Source Code Modules (/src): Pure Python modules or utility files. Modern Databricks allows importing custom Python files directly into notebooks if they live in the same Git repo.
• Configuration Files (/config): Environment-specific setups (JSON, YAML, or .ini files) holding cluster parameters, storage path mappings, or database connection configurations (excluding secrets).
