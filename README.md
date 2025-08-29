
```markdown
# Knative & OpenShift Serverless Labs

This repository contains hands-on labs, guides, and resources to learn and practice **Knative** and **OpenShift Serverless**.  
It covers core concepts such as Serving, Eventing, traffic splitting, and deploying serverless workloads using OpenShift Pipelines.

---

## 📂 Repository Contents

### 🔹 Labs & Guides
- **Create Api resource from CLI** (`Create Api resource from cli.docx`)  
  Step-by-step guide to create Knative API resources using the CLI.

- **Event Source API** (`Event source api.docx`)  
  Introduction to Knative Event Sources and how to configure them.

- **OpenShift Developer Sandbox** (`Openshift developer sandbox.docx`)  
  Setup and usage of Red Hat OpenShift Developer Sandbox for serverless workloads.

- **Ping Source** (`Ping source.docx`)  
  Example of using Knative PingSource to generate events on a schedule.

- **Serverless API** (`Serverless api.docx`)  
  Working with Serverless APIs on OpenShift.

- **Serverless Service Deployment via OpenShift Pipeline**  
  (`Serverless service deployed by OpenShift Pipeline.docx`)  
  Automating serverless deployment with OpenShift Pipelines.

- **Serving Lab 1** (`Serving lab1.docx`)  
  Lab covering Knative Serving basics – deploying and managing services.

- **Traffic Splitting in Knative** (`knserving traffic split.txt`)  
  Example of splitting traffic between revisions using `kn` CLI.

### 🔹 CLI & Commands
- **kn CLI Serving Commands** (`kn cli serving.txt`)  
  Useful commands for managing Knative Serving resources.

- **API Resource Event Lab** (`api-resource-event-lab.txt`)  
  Example lab for event-driven API resources.

### 🔹 Presentations & Reference
- **Serverless.pptx**  
  Slide deck introducing Serverless concepts and labs.  

- **Knative API Server** (`knative api server.pdf`)  
  PDF reference on Knative API Server concepts.

---

## 🚀 Prerequisites
To follow the labs, you’ll need:
- Access to [OpenShift Developer Sandbox](https://developers.redhat.com/developer-sandbox) (or an OpenShift cluster with Serverless Operator installed).
- `kn` CLI installed ([Knative CLI installation guide](https://knative.dev/docs/client/install-kn/)).
- `kubectl` or `oc` CLI configured for your cluster.

---

## 📘 Lab Flow (Suggested Order)
1. OpenShift Developer Sandbox setup  
2. Knative Serving basics (`Serving lab1.docx`, `kn cli serving.txt`)  
3. Creating API resources (`Create Api resource from cli.docx`)  
4. Eventing with sources (`Event source api.docx`, `Ping source.docx`)  
5. Deploying via Pipelines (`Serverless service deployed by OpenShift Pipeline.docx`)  
6. Traffic management (`knserving traffic split.txt`)  
7. Reference and deep dives (`Serverless api.docx`, `knative api server.pdf`)  


```

Would you like me to also add **badges and visuals** (like an OpenShift/Knative logo and GitHub shields for stars/forks/watchers), so the README looks more professional?
