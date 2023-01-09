[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/terrytangyuan/awesome-kubeflow) [![Twitter Follow](https://img.shields.io/twitter/follow/kubeflow?style=social)](https://twitter.com/kubeflow) [![Twitter Follow](https://img.shields.io/twitter/follow/TerryTangYuan?style=social)](https://twitter.com/TerryTangYuan)

# Awesome Kubeflow

🎉 [Kubeflow has applied to come a CNCF incubating project!](https://blog.kubeflow.org/kubeflow-applied-cncf-incubating/) Stay tuned!

A curated list of awesome projects and resources related to [Kubeflow](https://www.kubeflow.org/).

## What is Kubeflow?

The Kubeflow project is dedicated to making deployments of machine learning (ML) workflows on Kubernetes simple, portable and scalable.


## Table of Contents

<!-- MarkdownTOC depth=4 -->

  - [Ecosystem Projects](#ecosystem-projects)
  - [Books](#books)
  - [Blog Posts](#blog-posts)
  - [Videos](#videos)
  - [Community](#community)
  - [Acknowledgement](#acknowledgement)

<!-- /MarkdownTOC -->


<a name="ecosystem-projects" />

## Ecosystem Projects

Main projects in Kubeflow:

* [Kubeflow Main Repository](https://github.com/kubeflow/kubeflow) which provides the front-end to access major components of Kubeflow.
* [Katib](https://github.com/kubeflow/katib) is a Kubernetes-native project for automated machine learning (AutoML).
* [Pipelines](https://github.com/kubeflow/pipelines) is dedicated to making deployments of machine learning workflows on Kubernetes simple, portable, and scalable with Kubeflow.
* [Training Operator](https://github.com/kubeflow/training-operator) provides Kubernetes custom resources that makes it easy to run distributed or non-distributed TensorFlow/PyTorch/Apache MXNet/XGBoost/MPI jobs on Kubernetes.
* [Arena](https://github.com/kubeflow/arena) is a CLI for Kubeflow.
* [Fairing](https://github.com/kubeflow/fairing) is a Python SDK for building, training, and deploying ML models.


Other open source projects that use Argo:

* [Couler](https://github.com/couler-proj/couler) provides a unified interface for constructing and managing workflows on different workflow engines.
* [Kedro](https://github.com/quantumblacklabs/kedro) is an open-source Python framework for creating reproducible, maintainable and modular data science code.
* [Seldon](https://github.com/SeldonIO/seldon-core) is an MLOps framework to package, deploy, monitor and manage thousands of production machine learning models.
* [SQLFlow](https://github.com/sql-machine-learning/sqlflow) extends SQL to support AI and compiles the SQL program to a workflow that runs on Kubernetes.
* [MLRun](https://github.com/mlrun/mlrun) is an open MLOps platform for quickly building and managing continuous ML applications across their lifecycle.
* [Polyaxon](https://github.com/polyaxon/polyaxon) is a platform for building, training, and monitoring large scale deep learning applications.

<a name="books" />

## Books

* [Distributed Machine Learning Patterns](https://github.com/terrytangyuan/distributed-ml-patterns) teaches you how to take machine learning models from your personal laptop to large distributed clusters. You’ll explore key concepts and patterns behind successful distributed machine learning systems, and learn technologies like TensorFlow, Kubernetes, Kubeflow, and Argo Workflows with real-world scenarios and hands-on projects.
* [Continuous Machine Learning with Kubeflow](https://a.co/d/fT6sikP)
* [Kubeflow for Machine Learning: From Lab to Production](https://a.co/d/0cQbySP)
* [Kubeflow in Action: End-to-End Machine Learning](https://www.manning.com/books/kubeflow-in-action-book-cx)
* [Kubeflow Operations Guide: Managing Cloud and On-Premise Deployment](https://a.co/d/4R4CJOm)


<a name="blogs" />

## Blog Posts

Please check out the [official Kubeflow Project blog](https://blog.kubeflow.org/). Additional links:

* [Humans of Cloud Native: From Argo to Mentoring and Everything In Between](https://www.cncf.io/humans-of-cloud-native/yuan-tang-from-argo-to-mentoring-and-everything-in-between/)
* [GitOps for Kubeflow using Argo CD](https://v0-6.kubeflow.org/docs/use-cases/gitops-for-kubeflow/)
* [Kubeflow 1.0 - Cloud Native ML for Everyone](https://blog.kubeflow.org/releases/2020/03/02/kubeflow-1-0-cloud-native-ml-for-everyone.html)
* [Introduction to Kubeflow MPI Operator and Industry Adoption](https://terrytangyuan.github.io/2020/03/17/introduction-to-kubeflow-mpi-operator-and-industry-adoption/)
* [Kubeflow & Kale simplify building better ML Pipelines with automatic hyperparameter tuning](https://blog.kubeflow.org/integrations/2020/07/10/kubeflow-kale.html)
* [Kubeflow 1.1 improves ML Workflow Productivity, Isolation & Security, and GitOps](https://blog.kubeflow.org/release/official/2020/07/31/kubeflow-1.1-blog-post.html)
* [Data Science Meets Devops: MLOps with Jupyter, Git, & Kubernetes](https://blog.kubeflow.org/mlops/)
* [Record metadata on Kubeflow from Notebooks](https://blog.kubeflow.org/jupyter/2020/10/01/lineage.html)
* [Operationalize, Scale and Infuse Trust in AI Models using KFServing](https://blog.kubeflow.org/release/official/2021/03/08/kfserving-0.5.html)
* [Kubeflow Katib: Scalable, Portable and Cloud Native System for AutoML](https://blog.kubeflow.org/katib/)
* [Elastic Training with MPI Operator and Practice](https://blog.kubeflow.org/elastic%20training/operators/2021/03/15/elastic-training.html)
* [Kubeflow Continues to Move into Production](https://blog.kubeflow.org/kubeflow-continues-to-move-to-production)
* [The Kubeflow 1.3 software release streamlines ML workflows and simplifies ML platform operations](https://blog.kubeflow.org/kubeflow-1.3-release/)
* [Running Kubeflow at Intuit: Enmeshed in the service mesh](https://blog.kubeflow.org/running-kubeflow-at-intuit/)
* [KServe: The next generation of KFServing](https://blog.kubeflow.org/release/official/2021/09/27/kfserving-transition.html)
* [Kubeflow's 1.4 release lays the foundation for advanced ML metadata workflows](https://blog.kubeflow.org/kubeflow-1.4-release/)
* [Unified Training Operator release announcement](https://blog.kubeflow.org/unified-training-operator-1.3-release/)
* [Kubeflow v1.5 improves ML model accuracy, reduces infrastructure costs and optimizes MLOps](https://blog.kubeflow.org/kubeflow-1.5-release/)
* [Kubeflow v1.6 delivers support for Kubernetes v1.22 and introduces an alpha release of the Kubeflow Pipeline v2 functionality](https://blog.kubeflow.org/kubeflow-1.6-release/)
* [Kubeflow has applied to become a CNCF incubating project](https://blog.kubeflow.org/kubeflow-applied-cncf-incubating/)


<a name="videos" />

## Videos

* [Managing Thousands of Automatic Machine Learning Experiments with Argo and Katib](https://youtu.be/0jBNXZjQ01I)
* [Building AutoML Pipelines With Argo Workflows and Katib](https://youtu.be/d8o7fEd8l2g)
* [Hiding Kubernetes Complexity for ML Engineers Using Kubeflow](https://docs.google.com/presentation/d/1Fepo9TUgbsO7YpxenCq17Y9KKQU_VgqYjAVBFWAFIU4/edit?usp=sharing)
* [When Machine Learning Toolkit for Kubernetes Meets PaddlePaddle](https://github.com/terrytangyuan/public-talks/tree/main/talks/when-machine-learning-toolkit-for-kubernetes-meets-paddlepaddle-wave-summit-2021)
* [Bridging into Python Ecosystem with Cloud-Native Distributed Machine Learning Pipelines](https://github.com/terrytangyuan/public-talks/tree/main/talks/bridging-into-python-ecosystem-with-cloud-native-distributed-machine-learning-pipelines-argocon-2021)
* [Cloud Native AutoML with Argo Workflows and Katib](https://youtu.be/KjHqmS4gIxM?t=181)
* [Introducing Couler: Unified Interface for Constructing and Managing Workflows](https://github.com/terrytangyuan/public-talks/tree/main/talks/introducing-couler-unified-interface-for-constructing-and-managing-workflows-argo-workflows-community-meeting)
* [Machine Learning as Code: GitOps for ML with Kubeflow and ArgoCD](https://www.youtube.com/watch?v=VXrGp5er1ZE&t=0s&index=135&list=PLj6h78yzYM2PZf9eA7bhWnIh_mK1vyOfU)
* [Towards Cloud-Native Distributed Machine Learning Pipelines at Scale](https://github.com/terrytangyuan/public-talks/tree/main/talks/towards-cloud-native-distributed-machine-learning-pipelines-at-scale-pydata-global-2021)
* [AutoML and Training WG Summit 2021](https://youtube.com/playlist?list=PL2gwy7BdKoGd9HQBCz1iC7vyFVN7Wa9N2)
* [MLOps and AutoML in Cloud-Native Way with Kubeflow and Katib](https://youtu.be/33VJ6KNBBvU)
* [A Tour of Katib's new UI for Kubeflow 1.3](https://youtu.be/1DtjB_boWcQ)
* [New UI for Kubeflow components](https://youtu.be/OKqx3IS2_G4)
* [Using Pipelines in Katib](https://youtu.be/BszcHMkGLgc)
* [From Notebook to Kubeflow Pipelines with HP Tuning](https://youtu.be/QK0NxhyADpM)
* [Distributed Training and HPO Deep Dive](https://youtu.be/KJFOlhD3L1E)
* [Hyperparameter Tuning with Katib](https://youtu.be/nIKVlosDvrc)
* [Hyperparameter Tuning Using Kubeflow](https://youtu.be/OkAoiA6A2Ac)
* [Kubeflow Katib & Hyperparameter Tuning](https://youtu.be/1PKH_D6zjoM)
* [Neural Architecture Search System on Kubeflow](https://youtu.be/WAK37UW7spo)


<a name="community" />

## Community

* [Community Calendar](https://www.kubeflow.org/docs/about/community/#kubeflow-community-calendars)
* [Working Groups](https://github.com/kubeflow/community/blob/master/wg-list.md)
* [GitHub Organization](https://github.com/kubeflow)
* [Community Governance](https://github.com/kubeflow/community/blob/master/wgs/wg-governance.md)
* Community User Surveys ([2022](https://blog.kubeflow.org/kubeflow-user-survey-2022/))

Social media accounts:

* [LinkedIn](https://www.linkedin.com/company/kubeflow/)
* [Slack](https://www.kubeflow.org/docs/about/community/#kubeflow-slack)
* [Twitter](https://twitter.com/kubeflow)
* [Reddit](https://www.reddit.com/r/kubeflow/)


<a name="acknowledgement" />

## Acknowledgement

TBA
