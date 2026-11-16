# DBA Diagnostic & Automation Toolkit

A curated collection of production-tested T-SQL, PostgreSQL, PowerShell, and Python scripts for database administration, high availability, and performance tuning across On-Premises and Azure environments.

## 📁 Repository Structure
* `/sql-server/performance` – Wait statistics, blocking chains, index health, and plan cache diagnostics.
* `/sql-server/always-on` – Always On Availability Group health, synchronization latency, and failover checks.
* `/postgresql/performance` – Table/index bloat checks, `pg_stat_statements` top queries, and autovacuum monitoring.
* `/automation/powershell` – PowerShell scripts for SQL Server maintenance, backups, and inventory audits.
* `/automation/python` – Python utilities for health checks, log parsing, and cross-platform DB tasks.

## ⚙️ Prerequisites
* **SQL Server:** SQL Server 2016+ / Azure SQL Managed Instance (`VIEW SERVER STATE` permissions).
* **PostgreSQL:** PostgreSQL 13+ with `pg_stat_statements` enabled (`pg_monitor` role).
* **Automation:** PowerShell 7+ (`dbatools` module) and Python 3.9+ (`psycopg2` / `pyodbc`).

## ⚠️ Usage Note
All diagnostic scripts are read-only unless explicitly labeled otherwise. Always review execution plans and validate in a non-production environment before running against production systems.
