This project is a practical lab where I practice how to move old applications to the cloud. 
The main idea here is taking "legacy" apps (the ones that run on old local servers) and migrate them to Google Cloud Platform using a modern approach.


I focused on Re-platforming strategy, so instead of just moving VMs, I worked on containerizing the workloads.What is this for?Basically, it simulates a real world scenario where a company wants to stop managing physical hardware.


I used this repo to test:How to dockerize a legacy app and run it on GKE (Google Kubernetes Engine).
Setting up Cloud SQL for the database part so you dont have to manage backups manually.Managing hybrid cloud stuff with Anthos to keep things conected.Tech StackCloud: Google Cloud (GCP).Orchestration: Kubernetes (GKE).Database: Cloud SQL & Memorystore.IaC: A bit of Terraform for some resources.
