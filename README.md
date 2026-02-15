# bikes-databricks-pipeline

# NOTES
These notebooks are part of a Databricks Medallion Architecture example. All credentials, paths, and data sources are mocked or abstracted for security reasons.

# Bikes - Databricks Medallion Pipeline (Bronze → Silver → Gold)

# Overview

Pipeline built in Databricks following the Medallion Architecture:

# • Bronze: raw ingestion
# • Silver: cleansing + transformations
# • Gold: business-ready tables/aggregations

# Tech Stack

• Databricks (Jobs, Notebooks)
• Spark / PySpark
• Delta Lake (Bronze/Silver/Gold)
• Data quality validation (example step)

# How to run (high level)
1. Configure your own storage and secrets
2. Run notebooks in order: Bronze → Silver → Gold
3. Trigger the job pipeline

Security note
This repository uses mock/sample data and does not expose:

• Workspace URLs
• Tokens/secrets
• Storage account names
• Subscription/tenant identifiers
