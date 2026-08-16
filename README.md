# weatherlake-azure
Serverless data lakehouse on Azure - ingests NOAA/Open-Meteo weather data via scheduled GitHub Actions (OIDC, no stored secrets), transforms through a bronze/silver/gold DuckDB pipeline, and provisions dev/staging/prod environments with Terraform. Built for near-zero cost with manual-dispatchdeploys and teardown safeguards.
