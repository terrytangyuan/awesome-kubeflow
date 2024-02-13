[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/terrytangyuan/awesome-kubeflow) [![Twitter Follow](https://img.shields.io/twitter/follow/kubeflow?style=social)](https://twitter.com/kubeflow) [![LinkedIn](https://img.shields.io/badge/LinkedIn-Kubeflow-blue.svg?logo=linkedin)](https://www.linkedin.com/company/kubeflow/)

# Awesome Kubeflow

🔔 NEWS:
* [Kubeflow Project Steering Committee Announced](https://blog.kubeflow.org/election/2024/01/31/kubeflow-project-steering-committee-announced.html)
* The book [Distributed Machine Learning Patterns](https://bit.ly/2RKv8Zo) from Manning Publications (uses Kubeflow) is officially published!
* Kubeflow Summit is now a colocated event in KubeCon Europe 2024. [Register now!](https://events.linuxfoundation.org/kubecon-cloudnativecon-europe/co-located-events/kubeflow-summit/)
* 🎉 [Kubeflow is now an incubating project in CNCF!](https://www.cncf.io/blog/2023/07/25/kubeflow-brings-mlops-to-the-cncf-incubator/)

A curated list of awesome projects and resources related to [Kubeflow](https://www.kubeflow.org/).

<img align="center" src="https://raw.githubusercontent.com/kubeflow/website/master/static/images/logo.svg" alt="kubeflow" width="30%" height="30%">

## What is Kubeflow?

The Kubeflow project is dedicated to making deployments of machine learning (ML) workflows on Kubernetes simple, portable and scalable.


## Table of Contents

<!-- MarkdownTOC depth=4 -->

  - [Ecosystem Projects](#ecosystem-projects)
  - [Books](#books)
  - [Blog Posts](#blog-posts)
  - [Videos](#videos)
  - [Community](#community)
<!-- /MarkdownTOC -->


<a name="ecosystem-projects" />

## Ecosystem Projects

Main projects in Kubeflow:

* [Kubeflow Main Repository](https://github.com/kubeflow/kubeflow) which provides the front-end to access major components of Kubeflow.
* [Katib](https://github.com/kubeflow/katib) is a Kubernetes-native project for automated machine learning (AutoML).
* [Pipelines](https://github.com/kubeflow/pipelines) is dedicated to making deployments of machine learning workflows on Kubernetes simple, portable, and scalable with Kubeflow.
* [Training Operator](https://github.com/kubeflow/training-operator) provides Kubernetes custom resources that makes it easy to run distributed or non-distributed TensorFlow/PyTorch/Apache MXNet/XGBoost/MPI jobs on Kubernetes.
* [Arena](https://github.com/kubeflow/arena) is a CLI for Kubeflow.

Other open source projects that use or integrate with Kubeflow:

* [Argo Workflows](https://github.com/argoproj/argo-workflows) is a container-native workflow engine for orchestrating parallel jobs on Kubernetes. 
* [Couler](https://github.com/couler-proj/couler) provides a unified interface for constructing and managing workflows on different workflow engines.
* [deployKF](https://github.com/deployKF/deployKF) effortlessly integrates Kubeflow and leading MLOps tools on Kubernetes into open ML platforms.
* [Kale](https://github.com/kubeflow-kale/kale) is aims at simplifying the data science experience of deploying Kubeflow Pipelines workflows.
* [Kedro](https://github.com/quantumblacklabs/kedro) is an open-source Python framework for creating reproducible, maintainable and modular data science code.
* [KServe](https://github.com/kserve/kserve) is a standardized serverless ML inference platform on Kubernetes.
* [MLRun](https://github.com/mlrun/mlrun) is an open MLOps platform for quickly building and managing continuous ML applications across their lifecycle.
* [ModelDB](https://github.com/VertaAI/modeldb) is an open-source system to version machine learning models including their ingredients code, data, config, and environment and to track ML metadata across the model lifecycle.
* [Polyaxon](https://github.com/polyaxon/polyaxon) is a platform for building, training, and monitoring large scale deep learning applications.
* [Seldon](https://github.com/SeldonIO/seldon-core) is an MLOps framework to package, deploy, monitor and manage thousands of production machine learning models.
* [SQLFlow](https://github.com/sql-machine-learning/sqlflow) extends SQL to support AI and compiles the SQL program to a workflow that runs on Kubernetes.
* [ZenML](https://github.com/zenml-io/zenml) is a framework to build portable, production-ready MLOps pipelines.
* [Elyra](https://github.com/elyra-ai/elyra) is a set of AI-centric extensions to JupyterLab Notebooks, that contains a visual pipeline editor.
* [Pipeline Editor](https://github.com/Cloud-Pipelines/pipeline-editor) web app that allows the users to build and run Machine Learning pipelines using drag and drop. A VSCode extension can be found [here](https://marketplace.visualstudio.com/items?itemName=Cloud-pipelines.pipeline-editor-vscode).
* [WizStudio](https://wizstudio.litwizlabs.ai) is a web based tool that allows the users to build Kubeflow pipelines using drag and drop interface.
<a name="books" />

## Books

* [Continuous Machine Learning with Kubeflow](https://a.co/d/fT6sikP) introduces you to the modern machine learning infrastructure, which includes Kubernetes and the Kubeflow architecture. This book will explain the fundamentals of deploying various AI/ML use cases with TensorFlow training and serving with Kubernetes and how Kubernetes can help with specific projects from start to finish.
* [Distributed Machine Learning Patterns](https://github.com/terrytangyuan/distributed-ml-patterns) teaches you how to take machine learning models from your personal laptop to large distributed clusters. You’ll explore key concepts and patterns behind successful distributed machine learning systems, and learn technologies like TensorFlow, Kubernetes, Kubeflow, and Argo Workflows with real-world scenarios and hands-on projects.
* [Kubeflow for Machine Learning: From Lab to Production](https://a.co/d/0cQbySP) helps data scientists build production-grade machine learning implementations with Kubeflow and shows data engineers how to make models scalable and reliable.
* [Kubeflow in Action: End-to-End Machine Learning](https://www.manning.com/books/kubeflow-in-action-book-cx) is an authoritative hands-on guide to deploying machine learning to production using the Kubeflow MLOps platform.
* [Kubeflow Operations Guide: Managing Cloud and On-Premise Deployment](https://a.co/d/4R4CJOm) shows data scientists, data engineers, and platform architects how to plan and execute a Kubeflow project to make their Kubernetes workflows portable and scalable.


<a name="blogs" />

## Blog Posts

Please check out the [official Kubeflow Project blog](https://blog.kubeflow.org/). Additional blog posts:

* [Data Science Meets Devops: MLOps with Jupyter, Git, & Kubernetes](https://blog.kubeflow.org/mlops/)
* [Elastic Training with MPI Operator and Practice](https://blog.kubeflow.org/elastic%20training/operators/2021/03/15/elastic-training.html)
* [Enabling Kubeflow with Enterprise-Grade Auth for On-Premise Deployments](https://medium.com/kubeflow/enabling-kubeflow-with-enterprise-grade-auth-for-on-premise-deployments-ae7dd13a69e5)
* [GitOps for Kubeflow using Argo CD](https://v0-6.kubeflow.org/docs/use-cases/gitops-for-kubeflow/)
* [Hardening Kubeflow Security for Enterprise Environments](https://blogs.vmware.com/opensource/2023/06/20/hardening-kubeflow-security-for-enterprise-environments-2/)
* [Humans of Cloud Native: From Argo to Mentoring and Everything In Between](https://www.cncf.io/humans-of-cloud-native/yuan-tang-from-argo-to-mentoring-and-everything-in-between/)
* [Introduction to Kubeflow MPI Operator and Industry Adoption](https://terrytangyuan.github.io/2020/03/17/introduction-to-kubeflow-mpi-operator-and-industry-adoption/)
* [KServe: The Next Generation of KFServing](https://blog.kubeflow.org/release/official/2021/09/27/kfserving-transition.html)
* [Kubeflow & Kale Simplify Building Better ML Pipelines With Automatic Hyperparameter Tuning](https://blog.kubeflow.org/integrations/2020/07/10/kubeflow-kale.html)
* [Kubeflow’s 1.4 Release Lays the Foundation for Advanced ML Metadata Workflows](https://blog.kubeflow.org/kubeflow-1.4-release/)
* [Kubeflow 1.0 - Cloud Native ML for Everyone](https://blog.kubeflow.org/releases/2020/03/02/kubeflow-1-0-cloud-native-ml-for-everyone.html)
* [Kubeflow 1.1 Improves ML Workflow Productivity, Isolation & Security, and GitOps](https://blog.kubeflow.org/release/official/2020/07/31/kubeflow-1.1-blog-post.html)
* [Kubeflow Continues to Move into Production](https://blog.kubeflow.org/kubeflow-continues-to-move-to-production)
* [Kubeflow Has Applied To Become a CNCF Incubating Project](https://blog.kubeflow.org/kubeflow-applied-cncf-incubating/)
* [Kubeflow Katib: Scalable, Portable and Cloud Native System for AutoML](https://blog.kubeflow.org/katib/)
* [Kubeflow v1.5 Improves ML Model Accuracy, Reduces Infrastructure Costs and Optimizes MLOps](https://blog.kubeflow.org/kubeflow-1.5-release/)
* [Kubeflow v1.6 Delivers Support for Kubernetes v1.22 and Introduces an Alpha Release of the Kubeflow Pipeline v2 Functionality](https://blog.kubeflow.org/kubeflow-1.6-release/)
* [Kubeflow Welcomes Two Google Summer of Code Students](https://medium.com/kubeflow/kubeflow-welcomes-two-google-summer-of-code-students-6d4b49eb7763)
* [Kubeflow’s 2nd Doc Sprint: 10+ New Docs & Samples Ahead of Kubeflow 1.0](https://medium.com/kubeflow/kubeflow-doc-sprint-results-and-thanks-8953d17560ba)
* [Kubeflow is More Accessible than Ever](https://towardsdatascience.com/kubeflow-is-more-accessible-than-ever-with-minikf-33484d9cb26b)
* [Operationalize, Scale and Infuse Trust in AI Models using KFServing](https://blog.kubeflow.org/release/official/2021/03/08/kfserving-0.5.html)
* [Record Metadata on Kubeflow from Notebooks](https://blog.kubeflow.org/jupyter/2020/10/01/lineage.html)
* [Running Kubeflow at Intuit: Enmeshed in the Service Mesh](https://blog.kubeflow.org/running-kubeflow-at-intuit/)
* [Scalable and Cloud-Native Hyperparameter Tuning System](https://arxiv.org/abs/2006.02085)
* [The Kubeflow 1.3 Release Streamlines ML Workflows and Simplifies ML Platform Operations](https://blog.kubeflow.org/kubeflow-1.3-release/)
* [Unified Training Operator Release Announcement](https://blog.kubeflow.org/unified-training-operator-1.3-release/)

<a name="videos" />

## Videos

Please check out the [official Kubeflow YouTube channel](https://www.youtube.com/@Kubeflow).

### Kubeflow Summit talks playlist

* [Kubeflow Summit 2023](https://www.youtube.com/watch?v=_UlfF8hb_Ko&list=PL2gwy7BdKoGdrkYIWGeAdKi9ntfxq8FYt&index=1)
* [Community Meeting Recordings](https://youtube.com/playlist?list=PLmzRWLV1CK_ypvsQu10SGRmhf2S7mbYL5&si=Dgybdd5rLpl3farh)

### Additional videos

* [A 10 Minute Introduction to Kubeflow: Basics, Architecture & Components](https://youtu.be/G7zW1Wqym00)
* [Accelerate ML Model Development for Autonomous Vehicles in Aurora](https://youtu.be/cGWfeYUBPcg)
* [Accelerating Machine Learning App Development with Kubeflow Pipelines](https://youtu.be/TZ1lGrJLEZ0)
* [A Simple, NVIDIA-accelerated Kubeflow Pipeline](https://youtu.be/MdwANJnUFng)
* [A Tour of Katib's new UI for Kubeflow 1.3](https://youtu.be/1DtjB_boWcQ)
* [AutoML and Training WG Summit 2021](https://youtube.com/playlist?list=PL2gwy7BdKoGd9HQBCz1iC7vyFVN7Wa9N2)
* [Bridging into Python Ecosystem with Cloud-Native Distributed Machine Learning Pipelines](https://github.com/terrytangyuan/public-talks/tree/main/talks/bridging-into-python-ecosystem-with-cloud-native-distributed-machine-learning-pipelines-argocon-2021)
* [Building a Machine Learning Pipeline with Kubeflow](https://youtu.be/6wWdNg0GMV4)
* [Building and Managing a Centralized Kubeflow Platform at Spotify](https://youtu.be/m9XhsnNSMAI)
* [Building an ML Application Platform from the Ground Up](https://youtu.be/uNMH4JCUmR4)
* [Building AutoML Pipelines With Argo Workflows and Katib](https://youtu.be/d8o7fEd8l2g)
* [Building end-to-end ML workflows with Kubeflow Pipelines](https://youtu.be/90hPRXiBn4U)
* [Building Real Time Image Classification with Kubeflow Orchestrator](https://youtu.be/1OHMipvyzRU)
* [Building Together: Community in Kubeflow](https://youtu.be/EBH8thFYCyQ)
* [Charmed for Kubeflow: A Distribution for Everybody](https://youtu.be/alu5ZjPHxF4)
* [Cloud Native AutoML with Argo Workflows and Katib](https://youtu.be/KjHqmS4gIxM?t=181)
* [Converting Kaggle Competitions into Kubeflow Pipelines](https://youtu.be/cF-UPrTCvFE)
* [DGL Operator and Graph Training](https://youtu.be/hlrdWey0RKs)
* [Distributed Training and HPO Deep Dive](https://youtu.be/KJFOlhD3L1E)
* [Enterprise MLOps using Kubeflow with DKube](https://youtu.be/xmdpOrYaPDQ)
* [Experiment Tracking with Kubeflow](https://youtu.be/wpGjcSOibmE)
* [Feast: Feature Storage for Machine Learning](https://youtu.be/JNP1UxvSHO0)
* [From Notebook to Kubeflow Pipelines to KFServing: the Data Science Odyssey](https://youtu.be/VDINH5WkBhA)
* [From Notebook to Kubeflow Pipelines with HP Tuning](https://youtu.be/QK0NxhyADpM)
* [From Notebook to Kubeflow Pipelines with MiniKF & Kale](https://youtu.be/1fX9ZFWkvvs)
* [From Zero to Kubeflow](https://youtu.be/AF-WH967_s4)
* [Hiding Kubernetes Complexity for ML Engineers Using Kubeflow](https://docs.google.com/presentation/d/1Fepo9TUgbsO7YpxenCq17Y9KKQU_VgqYjAVBFWAFIU4/edit?usp=sharing)
* [Hyperparameter Tuning Using Kubeflow](https://youtu.be/OkAoiA6A2Ac)
* [Hyperparameter Tuning with Katib](https://youtu.be/nIKVlosDvrc)
* [Introducing Couler: Unified Interface for Constructing and Managing Workflows](https://github.com/terrytangyuan/public-talks/tree/main/talks/introducing-couler-unified-interface-for-constructing-and-managing-workflows-argo-workflows-community-meeting)
* [Katib and Training Operator](https://youtu.be/qDKSH_X68XE)
* [Katib User Journey](https://youtu.be/8nIhUx9rnOU)
* [KFServing: Enabling Serverless Workloads Across Model Frameworks](https://youtu.be/hGIvlFADMhU)
* [KServe: The State and Future of Cloud Native Model Serving](https://youtu.be/s6TDq8naG48)
* [Kubeflow & Alibaba Arena](https://youtu.be/eGaCv_3vnas)
* [Kubeflow & TFX](https://youtu.be/dm3IrSPiZ3Y)
* [Kubeflow 101 from Google Cloud](https://youtube.com/playlist?list=PLIivdWyY5sqLS4lN75RPDEyBgTro_YX7x)
* [Kubeflow: Machine Learning on Kubernetes](https://youtu.be/HBxyLnEzyhw)
* [Kubeflow and the ML Landscape](https://youtu.be/4i97ITih2Ow)
* [Kubeflow Experiments at LinkedIn](https://youtu.be/kExwqij11cg)
* [Kubeflow Fairing](https://youtu.be/SN70he8oFME)
* [Kubeflow for Enterprise – Samsung Case](https://youtu.be/6DTIRe0ih9c)
* [Kubeflow inference on knative](https://youtu.be/coL4O3Itz-c)
* [Kubeflow Katib & Hyperparameter Tuning](https://youtu.be/1PKH_D6zjoM)
* [Kubeflow Pipelines 2.0: Introduction & Roadmap](https://youtu.be/JiM69LyUvEM)
* [Kubeflow Universal Training Operator](https://youtu.be/fMXFbREG7Yg)
* [Kubeflow vs SageMaker in Machine Learning](https://www.youtube.com/watch?v=lugapU4nOww)
* [Machine Learning as Code: GitOps for ML with Kubeflow and ArgoCD](https://www.youtube.com/watch?v=VXrGp5er1ZE&t=0s&index=135&list=PLj6h78yzYM2PZf9eA7bhWnIh_mK1vyOfU)
* [Managing Thousands of Automatic Machine Learning Experiments with Argo and Katib](https://youtu.be/0jBNXZjQ01I)
* [MiniKF: The Fastest and Easiest Way to a Local Kubeflow](https://youtu.be/5S5gTsEdgoQ)
* [MLOps and AutoML in Cloud-Native Way with Kubeflow and Katib](https://youtu.be/33VJ6KNBBvU)
* [ModelDB: Open-source Model Management](https://youtu.be/7KMXQuh12VE)
* [Model Monitoring for Model Trained and Served on Kubeflow](https://youtu.be/xu-V13XbYCQ)
* [Multi-user Kubeflow Environments](https://youtu.be/4z6wB4O1R80)
* [Nested Workflows in Kubeflow Pipelines](https://youtu.be/1gf4VBH-DbA)
* [Neural Architecture Search System on Kubeflow](https://youtu.be/WAK37UW7spo)
* [New UI for Kubeflow components](https://youtu.be/OKqx3IS2_G4)
* [Orchestrating Apache Spark with Kubeflow on Kubernetes](https://youtu.be/8862JRDdpm8)
* [Paddle Operator and EDL Introduction](https://youtu.be/Hblh9HvVlxg)
* [Roblox User Story](https://youtu.be/GTbuI_Xepuo)
* [Serverless Magic for ML Orchestration using Kubeflow](https://youtu.be/2FU-VQizl0w)
* [Taming Your AI/ML Workloads with Kubeflow](https://youtu.be/B4soMk6AzOk)
* [Tour of New Katib UI](https://youtu.be/pk9ptAkR84k)
* [Towards Cloud-Native Distributed Machine Learning Pipelines at Scale](https://github.com/terrytangyuan/public-talks/tree/main/talks/towards-cloud-native-distributed-machine-learning-pipelines-at-scale-pydata-global-2021)
* [Training and Serving ML Model using Kubeflow](https://youtu.be/Xr_8ypMftFo)
* [Understanding the Earth: Machine Learning with Kubeflow Pipelines](https://youtu.be/lfuWyULSaR8)
* [Using Pipelines in Katib](https://youtu.be/BszcHMkGLgc)
* [When Machine Learning Toolkit for Kubernetes Meets PaddlePaddle](https://github.com/terrytangyuan/public-talks/tree/main/talks/when-machine-learning-toolkit-for-kubernetes-meets-paddlepaddle-wave-summit-2021)


<a name="community" />

## Community

* [Community Calendar](https://www.kubeflow.org/docs/about/community/#kubeflow-community-calendars)
* [Working Groups](https://github.com/kubeflow/community/blob/master/wg-list.md)
* [GitHub Organization](https://github.com/kubeflow)
* [Community Governance](https://github.com/kubeflow/community/blob/master/wgs/wg-governance.md)
* Community User Surveys ([2022](https://blog.kubeflow.org/kubeflow-user-survey-2022/), [2019 Fall](https://medium.com/kubeflow/kubeflow-community-user-survey-fall-2019-a84776c71743), [2019 Spring](https://medium.com/kubeflow/kubeflow-community-user-survey-spring-2019-44f86c794e67))

Social media accounts:

* [LinkedIn](https://www.linkedin.com/company/kubeflow/)
* [Slack](https://www.kubeflow.org/docs/about/community/#kubeflow-slack)
* [Twitter](https://twitter.com/kubeflow)
* [Reddit](https://www.reddit.com/r/kubeflow/)

**[⬆ back to top](#)**
