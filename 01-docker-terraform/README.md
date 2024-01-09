Introduction
Docker + Postgres
•	Introduction to docker
o	Why do we need Docker
o	Creating a simple "data pipeline" in Docker
•	Postgres
o	Running Postgres locally with Docker
o	Using pgcli for connecting to the database
o	Exploring the NY Taxi dataset
o	Ingesting the data into the database
•	PGAdmin
o	The pgAdmin tool
o	Docker networks
•	Ingestion script to docker
o	Converting the Jupyter notebook to a Python script
o	Parametrizing the script with argparse
o	Dockerizing the ingestion script
•	Running PGAdmin and Postgres with docker
o	Why do we need Docker-compose
o	Docker-compose YAML file
o	Running multiple containers with docker-compose up
•	SQL
o	Adding the Zones table
o	Inner joins
o	Basic data quality checks
o	Left, Right and Outer joins
o	Group by
•	Optional: If you have some problems with docker networking 
o	Docker networks
o	Port forwarding to the host environment
o	Communicating between containers in the network
o	.dockerignore file
•	Optional: If you are willing to do the steps from "Ingesting NY Taxi Data to Postgres" till "Running Postgres and pgAdmin with Docker-Compose" with 
GCP + Terraform
•	Introduction to GCP (Google Cloud Platform)
•	Introduction to Terraform Concepts - Overview
•	Terraform Basice - Simple one file Terraform Deployment
•	Terraform Continued - Terraform Deployment with a Variables File
•	Configuring terraform and GCP SDK on Windows
Environment setup
For the course you'll need:
•	Python 3 (e.g. installed with Anaconda)
•	Google Cloud SDK
•	Docker with docker-compose
•	Terraform
If you have problems setting up the env, you can check these videos
o	Generating SSH keys
o	Creating a virtual machine on GCP
o	Connecting to the VM with SSH
o	Installing Anaconda
o	Installing Docker
o	Creating SSH config file
o	Accessing the remote machine with VS Code and SSH remote
o	Installing docker-compose
o	Installing pgcli
o	Port-forwarding with VS code: connecting to pgAdmin and Jupyter from the local computer
o	Installing Terraform
o	Using sftp for putting the credentials to the remote machine
o	Shutting down and removing the instance

