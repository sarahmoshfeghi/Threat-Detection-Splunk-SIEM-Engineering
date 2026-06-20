# Threat-Detection-Splunk-SIEM-Engineering
since you are managing security agents like Tetragon and log collectors like Splunk UF, the next logical step is showing what you do with those logs. This repository demonstrates how to build detection engines and analytical models to catch attackers.
📁 What to include in the Git Repo:

    savedsearches.conf / macros.conf: Pre-built Splunk SPL (Search Processing Language) queries that parse incoming Linux logs or WAF data to track behavioral spikes.

    mltk_models/: Configuration scripts for the Splunk Machine Learning Toolkit (MLTK). You can include setup files for running a OneClassSVM or DensityFunction model to baseline normal web traffic and alert on malicious, automated security scanners.

    dashboards/: XML or JSON source code for a Splunk dashboard showing real-time security postures, tracking indicators like URI diversity anomalies, abnormal HTTP method counts, and elevated error rates.
