# Awesome Kedro [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome#readme) 

<div align="center"><img width="500" src="kedro_icon_no-type_whitebg.svg" alt="kedro logo"></div>

> An opinionated Python framework for creating reproducible, maintainable and modular data science code.

## Contents

- [Plugins](#plugins)
- [Blog posts](#blog-posts)
- [Videos](#videos)
  - [Intros](#intros)
  - [Howtos](#howtos)
- [Support](#support)

## [Plugins](https://kedro.readthedocs.io/en/stable/07_extend_kedro/05_plugins.html)

- [find-kedro](https://github.com/WaylonWalker/find-kedro) - Automatically construct pipelines using pytest style pattern matching.
- [kedro-accelerator](https://github.com/deepyaman/kedro-accelerator/) - Speeds up pipelines by parallelizing I/O in the background.
- [kedro-airflow](https://pypi.org/project/kedro-airflow/) - Makes it easy to deploy Kedro projects to Airflow.
- [kedro-airflow-k8s](https://github.com/getindata/kedro-airflow-k8s) - Enables running a Kedro pipeline with Airflow on a Kubernetes cluster.
- [kedro-argo](https://pypi.org/project/kedro-argo/) - Converts Kedro pipelines to Argo pipelines.
- [kedro-auto-catalog](https://github.com/WaylonWalker/kedro-auto-catalog) - A configurable replacement for kedro catalog create that allows you to create default dataset types other than `MemoryDataset`.
- [kedro-azureml](https://github.com/getindata/kedro-azureml) - Enables running a Kedro pipeline with Azure ML Pipelines service.
- [kedro-dataframe-dropin](https://github.com/mzjp2/kedro-dataframe-dropin) - Lets you swap out pandas datasets for modin or RAPIDs equivalents for specialised use to speed up your workflows (e.g on GPUs).
- [kedro-datasets](https://github.com/kedro-org/kedro-plugins/tree/main/kedro-datasets) - A collection of Kedro data connectors.
- [kedro-docker](https://pypi.org/project/kedro-docker/) - Makes it easy to package Kedro projects with Docker.
- [kedro-dolt](https://www.dolthub.com/blog/2021-06-16-kedro-dolt-plugin/) - Allows you to expand the data versioning abilities of data scientists and engineers
- [kedro-great](https://github.com/tamsanh/kedro-great) - The easiest way to integrate Kedro and Great Expectations.
- [kedro-grpc-server](https://pypi.org/project/kedro-grpc-server/) - Creates a gRPC server for your kedro pipelines.
- [kedro-kubeflow](https://github.com/getindata/kedro-kubeflow) - Lets you run and schedule pipelines on Kubernetes clusters using Kubeflow Pipelines.
- [kedro-mlflow](https://pypi.org/project/kedro-mlflow/) - Allows usage of MLFlow in Kedro projects.
- [kedro-neptune](https://github.com/neptune-ai/kedro-neptune) - Integration of Kedro with Neptune.ai.
- [kedro-pandas-profiling](https://pypi.org/project/kedro-pandas-profiling/) - "Profiles" data in the catalog.
- [kedro-partitioned](https://github.com/ProjetaAi/kedro-partitioned) - Extends the functionality on processing partitioned data.
- [kedro-sagemaker](https://github.com/getindata/kedro-sagemaker) - Enables running a Kedro pipeline with Amazon SageMaker service.
- [kedro-static-viz](https://github.com/WaylonWalker/kedro-static-viz) - Generates a static Kedro-Viz site (HTML, CSS, JS)
- [kedro-viz](https://pypi.org/project/kedro-viz/) - Helps visualise Kedro data and analytics pipelines.
- [kedro-vertexai](https://github.com/getindata/kedro-vertexai) - Enables running a Kedro pipeline with Vertex AI Pipelines service.
- [kedro-wings](https://pypi.org/project/kedro-wings/) - Automatically creates catalog entries to simplify Kedro pipeline writing.- [more-kedro](https://pypi.org/project/more-kedro/) - (Hook) library for on the fly typing and validation of parameter dictionaries and default value backed data loading.
- [steel-toes](https://pypi.org/project/steel-toes/) - Prevent changing downstream catalog data on your teammates while developing in parallel.

For more:
- [kedro-plugin](https://github.com/topics/kedro-plugin) topic on GitHub

## Blog posts
- [how-to-inject-secrets-into-your-kedro-configuration](https://kedrozerotohero.com/programming-patterns/how-to-inject-secrets-into-your-kedro-configuration)
- [define-data-catalog-using-python](https://kedrozerotohero.com/experiments/define-data-catalog-using-python)
- [kedro-in-scripts](https://waylonwalker.com/kedro-in-scripts/) - Getting started with Kedro in a single script
- [kedro-silence](https://waylonwalker.com/kedro-silence/) - Setting all kedro logs for clean output
- [pipeline-registry](https://waylonwalker.com/kedro-pipeline-registry/) - Converting from hooks.py to pipeline_registry, what you need to know.
- [minimal-pipeline](https://waylonwalker.com/minimal-kedro-pipeline/) - The minimal pipeline package (just pipeline no catalog or runner)
- [kedro-pickle](https://waylonwalker.com/kedro-pickle/) - How to use Kedro when your data is not a table.
- [reasons-to-kedro](https://waylonwalker.com/reasons-to-kedro/) - Reasons to consider using Kedro.
- [whats-new-in-kedro-166](https://waylonwalker.com/whats-new-in-kedro-0166/) - What's new in Kedro 0.16.6
- [whats-new-in-kedro-164](https://waylonwalker.com/whats-new-in-kedro-0164/) - What's new in Kedro 0.16.4
- [graceful-catalog](https://waylonwalker.com/graceful-kedro-catalog/) - Gracefully adopt the Kedro catalog in a non-Kedro project
- [kedro-catalog-search](https://waylonwalker.com/kedro-catalog-search/) - How to find entries in your Kedro catalog
- [Kedro (Python template for production-quality ML data pipelines)](https://wilsonmar.github.io/kedro/)
- [kedro-inputs](https://waylonwalker.com/kedro-inputs/) - How Kedro handles your inputs
- [kedro-preflight-hook](https://waylonwalker.com/creating-the-kedro-preflight-hook/) - Creating the kedro-preflight hook
- [Enhance your kedro experiences with these tips](https://towardsdatascience.com/enhance-your-kedro-experiences-with-these-tips-3036c3b7564)
- [Kedro: The Best Python Framework for Data Science!!](https://jlgjosue.medium.com/kedro-the-best-python-framework-for-data-science-fda6d8503646)
- [kedro-in-6-months](https://towardsdatascience.com/kedro-6-months-in-138c27aed13b)
- [Kedro hands-on](https://towardsdatascience.com/kedro-hands-on-build-your-own-demographics-atlas-pt-2-building-footprints-classification-8c48060e5c1a) Build your own demographics atlas. Pt. 2: building footprints classification
- [The latest and greatest in Kedro — We’re growing our community](https://quantumblack.medium.com/the-latest-and-greatest-in-kedro-were-growing-our-community-c868825b0cb4)
- [Kedro-Airflow 0.4.0 — Orchestrating Kedro Pipelines with Airflow](https://medium.com/quantumblack/kedro-airflow-0-4-0-orchestrating-kedro-pipelines-with-airflow-23fb1283f24d)
- [Unboxing Kedro 0.17.0 and Kedro-Viz 3.8.0 🎁](https://medium.com/quantumblack/unboxing-kedro-0-17-0-and-kedro-viz-3-8-0-dfdbdb024289)
- [Beyond the Notebook and into the Data Science Framework Revolution](https://medium.com/quantumblack/beyond-the-notebook-and-into-the-data-science-framework-revolution-a7fd364ab9c4)
- [Element AI uses Kedro to apply research and develop enterprise AI models](https://medium.com/quantumblack/element-ai-uses-kedro-to-apply-research-and-develop-enterprise-ai-models-bbbf2e3ff722)
- [Introducing Kedro Hooks](https://medium.com/quantumblack/introducing-kedro-hooks-fd5bc4c03ff5)
- [New in Kedro this Month!](https://medium.com/quantumblack/new-in-kedro-this-month-991a1fb50cb4)
- [Getting Started with Kedro](https://medium.com/quantumblack/getting-started-with-kedro-67edcc316f6a)
- [Introducing Kedro](https://medium.com/quantumblack/introducing-kedro-the-open-source-library-for-production-ready-machine-learning-code-d1c6d26ce2cf) - The Open Source Library for Production-Ready Machine Learning Code
- [Kedro: A New Tool For Data Science](https://towardsdatascience.com/kedro-prepare-to-pimp-your-pipeline-f8f68c263466)
- [Deploying and Versioning Data Pipelines at Scale](https://medium.com/quantumblack/deploying-and-versioning-data-pipelines-at-scale-942b1d81b5f5)

For more:
- [#kedro](https://dev.to/t/kedro) tag on dev.to

## Videos

### Intros

- [What is Kedro? Why is it useful? A Non-Technical Intro to Kedro](https://www.youtube.com/watch?v=dAtZiyQeN8Y) - An intro for management people.

### Howtos

- [Refactor your Jupyter notebooks using Kedro](https://www.youtube.com/watch?v=qClSGY6B0r0)
- [Introduction to Kedro training with Joel Schwarzmann](https://www.youtube.com/watch?v=NU7LmDZGb6E)
- [Creating Shared Catalogs for your Kedro Projects on GitHub](https://www.youtube.com/watch?v=GwSj64Uqnhk)
- [Deployable REST Enabled Data Pipelines with Flask, Docker, Kedro](https://www.youtube.com/watch?v=z7MIq-B4hPA)
- [How to begin writing tests for your Pipelines](https://www.youtube.com/watch?v=3pF0lZfmvOM)
- [How To Customize Your Kedro CLI Options](https://www.youtube.com/watch?v=euuXz6RLKVE)
- [How to Get/Write Data from/to a SQL Database](https://www.youtube.com/watch?v=24_Acr0oLaQ) - Use `pandas.SQLTableDataSet` or `pandas.SQLQueryDataSet`.
- [How to Lazily Evaluate Chunks of a Big Pandas DataFrame](https://www.youtube.com/watch?v=cbZ4cxCtLZc)
- [How to Setup PySpark for your Kedro Pipeline](https://www.youtube.com/watch?v=vYBMpPZep6E)
- [Kedro Great: Use Great Expectations with Ease!](https://www.youtube.com/watch?v=VY_AO0__oIE) - Show how to use kedro-great to e.g. validate data container meta data (columns, etc.).

For more:
- [@kedro-python on YouTube](https://www.youtube.com/@kedro-python)

### News

- [Kedro Community Update - April 2023](https://www.youtube.com/watch?v=ACwLKx8TEXc) - Kedro 0.18.7, new `OmegaConfigLoader`, experiment tracking in Kedro Viz, improvements in Databricks workflow, and more.
- [Let's look at Kedro 0.17.0!](https://www.youtube.com/watch?v=AVX31IVbpoE)
- [Kedro 0.16.0 was just Released!](https://www.youtube.com/watch?v=HxU6SL14jc4) - Release notes (features) of Kedro 0.16.0 explained.

## Support

- [GitHub Discussions](https://github.com/kedro-org/kedro/discussions/)
- [Stackoverflow (tag:kedro)](https://stackoverflow.com/questions/tagged/kedro)
- [Slack](https://kedro-org.slack.com/) ([invite link](https://slack.kedro.org))
