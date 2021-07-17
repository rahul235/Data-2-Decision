---
title: "Business Case for Julia"
last_modified_at: 2021-05-19T16:20:02-05:00
classes: wide
categories:
  - article
tags:
  - julia
---
This document aims to establish a need for industry training in Julia, explore the technical and business points that validates Julia, and suggest a plan. Scientific computing requires the highest performance, yet domain experts largely use slower dynamic languages for daily work. There are good reasons to prefer dynamic languages for these applications, and these reasons shall remain.
Modern language design and compiler techniques, however, make it possible to mostly eliminate the performance trade-off and provide a single environment productive enough for prototyping and efficient enough for deploying performance-intensive applications. The Julia programming language fits this role: it is a flexible dynamic language, appropriate for scientific and numerical computing, with performance comparable to traditional statically-typed languages. 
Julia is an open-source, high-performance, high-level, and dynamically-typed programming language.  As its four creators blatantly say it, Julia was created in the name of greed; to resolve the inadequacies of other programming languages while also integrating the unique and desirable features of the same languages.
Julia is still not very popular in India, but it is fast becoming the language of choice for Developers and Data scientists alike in the field of AI / ML. We believe there is a strong need to nurture Julia skills in Indian organisations in the field of Machine Learning, Artificial Intelligence etc. 
There are a host of technical and business reasons why Julia should be adopted, and why we should start implementing AI / ML projects in Julia rather than Python. These are presented in the Technical and Business Justifications in subsequent sections.

Julia Training can be made part of an organisational mandate to train some of the existing top notch programmers and data scientists first, and make it part of a mandatory training program for trainees.

## Business Justifications

Bogumił Kamiński, one of the chief Julia contributors, gave an interview last year where he described Julia as production ready. What according to him it means is this - you do NOT have to think  "Can I use Julia, as in three months maybe I will need something in the project that is not available in Julia yet" but rather "I can relatively safely use Julia, as currently many general-purpose packages are already there, and even if something is missing I can just use it from another language and it is going to be relatively painless no matter if it is C/Python/R/...".
Julia is not a language that is best suited for any kind of project. "**Each programming language has its niche, and the niche of Julia is high performance computing/data science.** If you want binaries with a very small footprint - for sure Julia is not the language of choice. If you want to develop apps for Android - it is not either.” With that introduction, let us look at business justifications for moving to Julia.

* Refer to [case studies](https://juliacomputing.com/case-studies/) and [julia customers](https://www.featuredcustomers.com/vendor/julia-computing/customers) for a gamut of applications of Julia in the real world.
* Google has added [Julia specific](https://analyticsindiamag.com/julia-users-can-now-rejoice-google-cloud-has-powerful-capabilities-to-support-the-language/) enhanced capabilities to its  Cloud Ecosystem to support the advanced features of the Julia language. This is proof that not only Julia is cloud ready, the Cloud is feeling a need to evolve to leverage Julia capabilities to the full. 
* Data scientists, researchers and analysts no longer need to solve problems in one language (typically Python) and apply solutions in a second language (Java / GoLang), as has been the practice. Now they can use a single language - Julia - for prototyping as well as production. This leads to a pretty large saving in time, and development cost. 
* Julia’s speed of execution and robust support of concurrent computing directly leads to a saving in terms of infrastructure when compared with Python.
* On the other hand, meeting stringent SLAs without blowing the top is practicable if Julia is used instead of Python.
* If the Development team has, along with a command of data science, also a command of different languages, then it becomes a question of “which technology suits the task at hand?” and not “let me build it with X technology anyway because that’s what I know”. The advantages of having a polyglot approach, especially in a microservices framework, cannot be stressed enough.
* MLOps, Pipelines and Deployment - MLOps is an ML engineering culture and practice that aims at unifying ML system development and ML system operation. Practicing MLOps means that you advocate for automation and monitoring at all steps of ML system construction, including integration, testing, releasing, deployment and infrastructure management. MLOps practices are available to developers using Julia, as they are to other languages.
* One can roughly compare this with the case of Oracle Java SDK vs Azul Java SDK. Azul Java SDK has an initial cost, but it lets you reap benefits in saving in infrastructure cost, as well as much better handling of SLAs. 

#### How companies have aligned to Julia
When Julia was conceived in 2009 at MIT the goal was to solve a problem that still exists: the need to use two (or more) languages, one for high performance (C or C++) and another that made programming complex systems a more pleasant experience (the Python example). While using both could get the job done, there is inherent friction between those interfaces and processes.

Keno Fischer, along with two other long-term Julia creators, co-founded Julia Computing. The goal was to put Julia to the test, not just as a language but as a more streamlined way to code for pharmaceutical, financial, HPC, energy, and other segments.

Julia Computing has aided Pfizer in simulating new pharmaceuticals, AstraZeneca with AI-based toxicity prediction, European insurance giant Aviva with its compliance issues, energy provider Fugro Roames with an AI-based grid network failure prediction system, the FAA with its airborne collision prevent program, Cisco with ML-based network security, and a number of national labs and academic institutions with various research programs. Julia Computing made waves this month as well with a DARPA grant to bring semiconductor codes up to date for more efficient, modern simulation codes.

Fischer says. “In the semi space, everyone now has proprietary versions of this cobbled together thing with various versions. Julia solves problems like this. Here is the two-language problem where the simulator is written in C but the scripting is all Python but people want to do advanced things like parameterizations and measurements to integrate ML but all those tools from the 80s keep getting in the way.” It’s not exactly a click of a button but with a small effort, Julia can provide functionality on top of a much more modern stack, Fischer argues.

Large companies with decades-old codes that have gotten them by thus far are waking up to what’s needed to keep evolving. The open source traction Julia took so long to develop is also paying off with developers choosing Julia for new projects. While the world may not be working strictly in the Julia language, for scientific and industrial users with a bad, long-hauler case of dueling languages and interfaces though, the AI/ML impetus would push Julia into a much brighter spotlight.

## Technical Justifications

Here are some of the technical cases for Julia, presented as bullet points:

* Julia is compiled, not interpreted and at its best can approach the execution speed of C. 
* Julia is interactive, and has an easy syntax comparable to Python, but very expressive and powerful. 
* Reproducible environments make it possible to recreate the same Julia environment every time, across platforms, with pre-built binaries. One can think of this as equivalent to the advantages Java has.
* Julia uses multiple dispatch as a paradigm, making it easy to express many object-oriented and functional programming patterns.
* It offers advanced parallel computing and is implementing its own native machine learning libraries.
* Julia provides asynchronous I/O, metaprogramming, debugging, logging, profiling, a package manager, and more.
* Julia’s mathematical syntax mirrors how we write mathematical formulae, making it the perfect language for scientific algorithms or mathematical-based programming.
* It can call C / Python and even Fortran libraries.
* Because of run-time type inference augmented by optional type annotations, and a strong focus on performance from the inception of the project, Julia's computational efficiency exceeds that of other dynamic languages, and even rivals that of statically-compiled languages. For large scale numerical problems, speed always has been, continues to be, and probably always will be crucial: the amount of data being processed has easily kept pace with Moore's Law over the past decades.
* Julia is fully cloud ready (like Java / Golang), and can be deployed in various configurations - containerised as Dockers and deployed in Kubernetes / Red Hat Openshift, as Serverless functions (adaptation of Apache OpenWhisk) etc. 
* To program in GPU in Julia, [JuliaGPU](https://juliagpu.org/) is a Github organization created to unify the many packages for programming GPUs in Julia. Several GPU platforms are supported. There are many Julia applications and libraries that rely on the language's GPU capabilities. Other Julia applications and libraries can be used with GPUs as well.
*  Some [benchmarks](https://julialang.org/benchmarks/) on a range of common code patterns for different languages.

#### 1. Machine learning and other frameworks in Julia

We have all heard that Julia is not yet a match for Python’s range but getting there. Let us look at some libraries already available in Julia (more are getting added as we speak). 
* Flux - [Flux](https://fluxml.ai/) is a deep learning and machine learning library. Any existing Julia libraries are differentiable and can be incorporated directly into Flux models. 
* Mocha.jl - [Mocha](https://devblogs.nvidia.com/mocha-jl-deep-learning-julia/) is a deep learning library written completely in Julia. This library comes with a GPU backend. 
* Knet - [Knet](https://denizyuret.github.io/Knet.jl/latest/tutorial/) is a deep learning framework implemented in the Julia programming language.  Knet allows models to be defined by just describing their forward computation. 
* TensorFlow.jl - [TensorFlow](https://github.com/malmaud/TensorFlow.jl) is also a Julia wrapper for popular open-source machine learning TensorFlow. This wrapper can be used for various purposes such as fast ingestion of data, especially data in uncommon formats, and fast postprocessing of inference results.
* SciKitLearn.jl - [ScikitLearn](https://github.com/cstjean/ScikitLearn.jl) is a Julia wrapper for the popular Python library Scikit-learn. It implements the Scikit-learn interface and algorithms in Julia. It provides a uniform interface for training and using models. It supports both models from the Julia ecosystem and those of the Scikit-learn library.
* MXNet.jl - [MXNet](https://github.com/dmlc/MXNet.jl) is the Apache MXNet Julia package that brings flexible and efficient GPU computing and state-of-art deep learning to Julia.
* MLBase.jl - [MLBase](https://mlbasejl.readthedocs.io/en/latest/) is a Julia package that provides useful tools for machine learning applications. 
* Merlin - [Merlin](https://github.com/hshindo/Merlin.jl) is a deep learning framework written in Julia. The library aims to provide a fast, flexible and compact deep learning library for machine learning.
* Strada - [Strada](https://github.com/pcmoritz/Strada.jl) is an open-source deep learning library for Julia, based on the popular Caffe framework. 
* LightGraphs.jl - [LightGraphs](https://github.com/JuliaGraphs/LightGraphs.jl) is the central package of the JuliaGraphs ecosystem. It gives a performant platform for network and graph analysis in Julia. 
* Libraries for Data visualisation - Sophisticated visulaization based on Hadley Wicham using grammer of graphics provided in [Gadfly](http://gadflyjl.org/stable/). Other popular libraries include [Plots](http://docs.juliaplots.org/latest/) and [Pyplot](https://docs.juliaplots.org/latest/generated/pyplot/).

#### 2. Development speed and Julia
Today we focus on deep python expertise to build the most accurate predictive models and expose this model as a Microservice. However, to build a holistic app, we also need to develop capabilities on other technologies that would enable optimal consumption of this ML Microservice. And Python is not always the best technology to build such services.

Even before Julia had caught on, people were using [Java / Golang](https://towardsdatascience.com/why-we-deploy-machine-learning-models-with-go-not-python-a4e35ec16deb) to build all the non-functional aspects of the project, for problems related to concurrency, scheduling etc. 

In fact, one can develop a POC quickly in Python, but when we have to transcend tough SLAs and meet stiff performance benchmarks, Python falls flat on its face. In such cases, one of the options is to take the POC and recode it in Java / Golang - speaking of 2 cloud ready languages. Sometimes, even the core ML module has to be re-coded, because keeping it in Python is not an option.

Java / GoLang are not necessarily the best choices to build Data Science and Machine Learning applications. In such a case, the core of Python is still a bottle neck.

With Julia, which is both a general purpose language /(like Java / Golang) but also stresses on ML etc (like Python), once we build the expertise, this problem goes away. You can use the same language for prototyping and production, and nothing stops you from using other languages like Java / Golang in their areas of strength either. Hence, adoption of Julia would lead to heightened speed of development.

#### 3. MLOPS, Pipelines and Deployment with Julia
Only a small fraction of a real-world ML system is composed of the core ML code. The required surrounding elements are vast and complex. These can consist of Data Collection and Validation, Model Analysis and a host of non functional requirements as well like Configuration, Automation etc. To develop and operate complex systems like these, one needs to eventually apply DevOps principles to ML systems (MLOps).

The three levels of maturity in MLOPS adaptation by any organisation are -

1. Level 0: The teams have data scientists etc who can build complex and sophisticated models, but their process for building and deploying ML models is entirely manual. Every step, including data analysis, data preparation, model training, and validation, is manual. Every step is manually executed, transition from one step to another is also manual. 

The process separates data scientists who create the model and engineers who serve the model as a prediction service and incorporate it into an API structure. There is no CI or CD in the process. The process consists of  deploying the trained model as a microservice with a REST API (as an example), rather than deploying the entire ML system. Level 0 is quite common. A manual, data-scientist-driven process is  sufficient when models are rarely changed or trained.

2. Level 1: In this level, one does continuous training of the model by automating the ML pipeline; in turn achieving continuous delivery of model prediction service. To automate the process of using new data to retrain models in production, one incorporates automated data ingestion and model validation steps to the pipeline, as well as pipeline triggers and metadata management.

The steps of the ML experiment are better coordinated, and transition between steps is automated. That leads to rapid iteration and  better readiness to move the whole pipeline to production. 

The model is automatically trained in production using fresh data based on live pipeline triggers. The pipeline implementation that is used in the development environment is the one used in the production environment. This is a key aspect of MLOps practice.   The source code for components must be modularized to be reusable, composable, and potentially shareable. In addition, components should ideally be containerized to make the code reproducible among different environments, and isolate each component in the pipeline.

In Level 0, one deploys a trained model as a service to production. For Level 1, one deploys a whole training pipeline, which automatically and recurrently runs to serve the trained model as the prediction service.

3. Level 2: Here, the need is for a robust automated CI/CD system. An automated CI/CD system lets the data scientists rapidly explore new ideas around feature engineering, model architecture, and hyperparameters.

This MLOps setup has the following components: Source control, Test and build services, Deployment services, Model registry, Feature store, ML metadata store, ML pipeline orchestrator.

Implementing ML in a production environment doesn't only mean deploying your model as an API for prediction. Rather, it means deploying an ML pipeline that can automate the retraining and deployment of new models. Setting up a CI/CD system enables you to automatically test and deploy new pipeline implementations. This system lets you cope with rapid changes in your data and business environment.

One can gradually implement these practices to help improve the automation of the ML system development and production.

Existing CI / CD pipelines and MLOPS in different organisations: Most companies have support for standard CI / CD pipelines with a number of languages, but Julia does not yet seem to be one of them. Also, while there is  talk of Model OPS, we could not find any specific references to MLOPS, though Google / Azure has specific MLOPS services clearly mentioned. 

  > _An estimate is that most of the projects in Indian organisations are at levels 0 or 1._

However, there are resources available that would enable integration of Julia in an overall MLOPS framework. [CNVRG](https://cnvrg.io/integrations/julia/) is one such resource. It delivers an AI OS built to actualize the AI-driven enterprise at scale. cnvrg.io is a compute-agnostic MLOps platform that offers a unified control plane to orchestrate all AI jobs and manage data science workflows at scale. Built by data scientists, for data scientists, cnvrg.io is the only solution that provides a code-first platform to manage, build and automate large-scale models in production. Built on Kubernetes, cnvrg.io is container based and integrates easily into existing IT and data science workflows. 

Another possible resource is [Algorithmia](https://algorithmia.com/mlops) and as they say “Algorithmia was created to help organizations deploy their models into production faster. This is possible because of robust MLOps processes that manage and govern models throughout the entire ML lifecycle. Deploy, monitor, manage, and govern your entire AI/ML pipeline in one singular place with machine learning operations. Algorithmia's MLOps creates a seamless journey through the lifecycle, getting models into production quickly and effortlessly, providing you with a return on your ML investment faster.”

With a Julia implementation, we can work at Levels 0 or 1 - but to enable Level 2 would need an effort by DevOps engineers and Data Scientists to build a platform that can be used by Developers working in Julia.

#### 4. Benchmark performance Julia vs. Python
Deploying models at scale is different from writing Python scripts that call PyTorch and TensorFlow functions. A benchmark gives us an approximate idea of how a specific language would perform w.r.t another. The benchmark is covered in https://julialang.org/benchmarks/ - already given above as well. A synopsis is presented here:

|Common Code Patterns|C Language|Julia Language|Python Language|
|--------------------|----------|--------------|---------------|
|iteration_pi_sum|27.368069|27.670768|404.3946266|
|matrix_multiply|72.014809|70.249355|84.99646187|
|matrix_statistics|4.528999|7.396705|80.32107353|
|parse_integers|0.099249|0.217658|1.961708069|
|print_to_file|9.929895|10.868424|47.0457077|
|recursion_fibonacci|0.022732|0.030162|2.142906189|
|recursion_quicksort|0.258923|0.258018|9.729623795|
|userfunc_mandelbrot|0.076702|0.052706|5.036592484|

There are other benchmarks for [DataFrames](https://h2oai.github.io/db-benchmark/), [Graphs](https://www.timlrx.com/blog/benchmark-of-popular-graph-network-packages-v2). For [CSV vs. Pandas](https://www.queryverse.org/benchmarks/) which one can refer to as well. 

## Who are the supporters in the ecosystem of this language? 
Are we going to get enough engineers in the market? Are there support forums available. Let us look at the support systems available for working with Julia.

* The chief support is provided by [Julia lang](https://julialang.org/). 
* Julia’s own resources to get one started are [here](https://julialang.org/learning/). 
* The [Julia Community](https://julialang.org/community/) lists all the official channels. Stack Overflow has many posts concerning Julia.
* The [Julia blog](https://julialang.org/blog/) discusses issues of numerical, technical, distributed and parallel computing, as well as programming language design, and how these issues touch upon the design and implementation of the Julia programming language.
* [Julia Computing Blog](https://juliacomputing.com/blog/) discusses ongoing Julia development.
* Blogs from the broader Julia community can be found at [Julia Bloggers](https://www.juliabloggers.com/). 
* [Towards Data Science](https://towardsdatascience.com) - has rich articles about Julia - including this - [“Bye-bye Python. Hello Julia!”](https://towardsdatascience.com/bye-bye-python-hello-julia-9230bff0df62).  
* Support from [Google](https://analyticsindiamag.com/julia-users-can-now-rejoice-google-cloud-has-powerful-capabilities-to-support-the-language/), [Azure](https://docs.microsoft.com/en-us/azure/machine-learning/data-science-virtual-machine/dsvm-tools-languages) and [Amazon]( https://d1.awsstatic.com/whitepapers/julia-on-sagemaker.pdf?did=wp_card&trk=wp_card) is also available.

## A Plan for the future
Barring a few startups like [Pattem]( https://pattemdigital.com/julia-development/), [Wibmo]( https://www.wibmo.co/) , at present there are scant Julia developers around, at least in India. One of the IITs provides a basic course in Julia, but it is nowhere taught in Graduate courses in IITs and other institutes. The developers can learn the language on their own and try to implement projects, but that is an error prone, slow process. If instead, there is an organisational mandate and structured training arranged by the company with a clear view to eventually benefit from the training and make a conscious transition, as much as possible, from Python, then the learning process is much more effective. A plan which may be useful for organizations to catch up with Julia is as follows: 

* Initially build up a team in house of some of the hand picked Developers and Data Scientists, as well as a few Architects and put them through courses. They will have considerable experience working in other languages, at least Java and Python, and pick up concepts quickly. That way a centre of excellence can be built up quickly.
* The courses offered to this team can be three fold
    > * A basic Julia course, where the fundamentals of the language are taught. 
    > * An advanced Julia course, where apart from advanced concepts, it’s applicability to Data Science, different packages that can be used, calling libraries of another language if need be etc are taught.
    > * A course where they are taught how to package, build, containerize and deploy Julia applications are taught. As well as the basics of MLOPS - so that when a MLOPS framework for the language is provided, they can adapt to it quickly. 
* Make it mandatory for fresh trainees and developers to go through the same Julia training as outlined above, plus any other supplementary courses that may be needed. That way we can sustain and build the workforce in this cutting edge technology.
* Training is not useful if you do not get to practice in a live environment what you learn. The Developers and Data Scientists should be encouraged as a matter of policy to take to Julia in subsequent projects, with support from Architects, and Managers.


**This article was ccontributed by a senior architect with 20+ years of industry experience. Based on his request, I have kept his name and company anonymous. However, I am ever thankful for his consent to put his analysis here.**
