---
title: AI-DaaS
subtitle: Deploy and scale AI/ML models in production on Kubernetes (K8s)
description: Deploy and scale AI/ML models in production on Kubernetes (K8s)
layout: product
image: /img/daas-design.jpg
features:
    - label: Leverages Kubernetes to provide reliable and scalable deployment services
      icon: fa-circle
    - label: Automated deployment system for AI/ML models including traditional data mining and deep learning models
      icon: fa-circle
    - label: Deploys pipelines with features engineering and prediction transformations instead of just model
      icon: fa-circle
    - label: Supports On-Premise or on Cloud Kubernetes environments
      icon: fa-circle
redirect_from: 
    - /products/ai-daas
---
<h4>Deploy pipelines, not just models.</h4>
<div class="columns">
  <div class="column is-8">
    <p>
      The following diagram shows the common flows of training and prediction in a data analytics project. The training phase consists of features engineering (data transformation -> features extraction & pre-processing) and model training, the prediction phase should contain the same features engineering and model prediction with optional prediction transformation. Deploying just the model part of the workflow is not enough, the entire pipeline must be deployed.
    </p>
  </div>
  <div class="column is-4 has-text-centered">
    <figure class="image">
      <img src="/img/training-prediction-flow.jpg" alt="" />
    </figure>
  </div>
</div>
<h4>Built on Function-as-a-Service</h4>
<div class="columns">
  <div class="column is-8">
    <p>
      Although there are already pipeline frameworks, like Scikit-learn, and SparkML pipeline, the pipeline could not cover all stages, the data scientist always needs to write extra code out of it.
    </p>
    <p>
      AI-DaaS is built on the Function-as-a-Service framework, you can generate the custom scoring script that has already included the model itself prediction with ease, then add your custom pre-processing & post-processing functions to finish the entire pipeline. At last, AI-DaaS can provide REST APIs for the entire pipeline automatically.
    </p>
  </div>
  <div class="column is-4 has-text-centered">
    <figure class="image">
      <img src="/img/daas-custom-scoring.jpg" alt="" />
    </figure>
  </div>
</div>
<h4>Open-standard and open source</h4>
<div class="columns">
  <div class="column is-8">
    <p>
      AI-DaaS can deploy your AI & ML solutions into production at scale on Kubernetes, which provides highly reliable and scalable AI model deployment services. AI-DaaS can support major open standard and open-source models: PMML, Scikit-learn, XGBoost, LightGBM, SparkML; ONNX, Keras, TensorFlow, PyTorch, MXNet, and even custom models. One-click to deploy them using the DaaS client library, you can visit DaaS-Client for details, there are several example notebooks for your reference.
    </p>
  </div>
  <div class="column is-4 has-text-centered">
    <figure class="image">
      <img src="/img/daas-models.jpg" alt="" />
    </figure>
  </div>
</div>
<div class="buttons is-centered">
  <a href="/about" class="button is-info">Request Demo</a>
</div>

