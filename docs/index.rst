===========================================
Welcome to Ianvs documentation!
===========================================

Ianvs is a distributed synergy AI benchmarking project incubated in KubeEdge SIG AI. According to the landing challenge survey 2022 in KubeEdge SIG AI, 
when it comes to the landing of distributed synergy AI projects, developers suffer from the lack of support on related datasets and algorithms; 
while end users are lost in the sea of mismatched solutions. 
That limits the wide application of related techniques and hinders a prosperous ecosystem of distributed synergy AI. 

Confronted with these challenges, Ianvs aims to test the performance of distributed synergy AI solutions following recognized standards, 
in order to facilitate more efficient and effective development. More detailedly, Ianvs prepares not only test cases with datasets and corresponding algorithms, 
but also benchmarking tools including simulation and hyper-parameter searching. 
Ianvs also reveals best practices for developers and end users with presentation tools including leaderboards and test reports. 

The scope of Ianvs is mainly two folds. 

First, Ianvs aims to provide end-to-end benchmark toolkits across devices, edge nodes, and cloud nodes based on typical distributed-synergy AI paradigms and applications. 
- Tools to manage test environment. For example, it would be necessary to support the CRUD (Create, Read, Update, and Delete) actions in test environments. Elements of such test environments include algorithm-wise and system-wise configuration.  
- Tools to control test cases. Typical examples include paradigm templates, simulation tools, and hyper-parameter-based assistant tools.
- Tools to manage benchmark presentation, e.g., leaderboard and test report generation. 

Second, Ianvs also cooperates with other organizations or communities, e.g., in KubeEdge SIG AI, to establish comprehensive benchmarks and developed related applications, which can include but are not limited to 
- Dataset collection, re-organization, and publication
- Formalized specifications, e.g., standards 
- Holding competitions or coding events, e.g., open source promotion plan
- Maintaining solution leaderboards or certifications for commercial usage 

Start your journey on Ianvs with the following links: 

.. toctree::
    :maxdepth: 1
    :caption: Introduction

    Introduction to Ianvs <distributed-synergy-ai-benchmarking>
    guides/quick-start

.. toctree::
    :maxdepth: 1
    :caption: GUIDEs

    guides/how-to-install-ianvs
    guides/how-to-test-algorithms
    guides/how-to-build-simulation-env


.. toctree::
    :maxdepth: 1
    :caption: SCENARIOs
    
    Industrial Defect Detection: PCB-AoI <proposals/scenarios/industrial-defect-detection/pcb-aoi>
    Cloud Edge Collaborative inference for LLM: Ianvs-MMLU-5-shot <proposals/scenarios/cloud-edge-collaborative-inference-for-llm/mmlu-5-shot>
    Cloud Robotics Lifelong Learning <proposals/scenarios/cloud-robotics-lifelong-learning-dataset/cloud-robotics>
    
.. toctree::
    :maxdepth: 1
    :titlesonly:
    :glob:
    :caption: ALGORITHMs

    Single Task Learning: FPN <proposals/algorithms/single-task-learning/fpn>
    Incremental Learning: BasicIL-FPN <proposals/algorithms/incremental-learning/basicIL-fpn>
    Lifelong Learning: RFNet <proposals/algorithms/lifelong-learning/Cloud-Robotic AI Benchmarking for Edge-cloud Collaborative Lifelong Learning>
    Joint Inference : Query-Routing <proposals/algorithms/joint-inference/query-routing>

.. toctree::
    :maxdepth: 1
    :titlesonly:
    :glob:
    :caption: USER INTERFACE

    How to Config Algorithm <user_interface/how-to-config-algorithm>
    How to Config TestEnv <user_interface/how-to-config-testenv>
    How to Config Benchmarkingjob <user_interface/how-to-config-benchmarkingjob>
    How to Use Ianvs Command Line <user_interface/how-to-use-ianvs-command-line>

.. toctree::
    :maxdepth: 1
    :titlesonly:
    :glob:
    :caption: Stories

    Leaderboard: Joint Inference Learning on Ianvs-MMLU-5-shot <leaderboards/leaderboard-in-cloud-edge-collaborative-inference-for-llm/leaderboard-of-cloud-edge-collaborative-inference-for-llm>
    Leaderboard: Single Task Learning on PCB-AoI <leaderboards/leaderboard-in-industrial-defect-detection-of-PCB-AoI/leaderboard-of-single-task-learning>
    Leaderboard: Incremental Learning on PCB-AoI <leaderboards/leaderboard-in-industrial-defect-detection-of-PCB-AoI/leaderboard-of-incremental-learning>
    Leaderboard: Lifelong Learning on Cloud-Robotics <leaderboards/leaderboard-in-semantic-segmentation-of-Cloud-Robotics/leaderboard-of-lifelong-learning>
    Leaderboard: Edge-Cloud Collaboration on Cloud-Robotics <leaderboards/leaderboard-in-semantic-segmentation-of-Cloud-Robotics/leaderboard-of-SAM-based-Edge-Cloud-Collaboration>
    Test Report: Joint Inference Learning on Ianvs-MMLU-5-shot <proposals/test-reports/testing-joint-inference-learning-in-cloud-edge-collaborative-inference-for-llm-scenario-with-ianvs-mmlu-5-shot-dataset>
    Test Report: Single Task Learning on PCB-AoI <proposals/test-reports/testing-single-task-learning-in-industrial-defect-detection-with-pcb-aoi>
    Test Report: Incremental Learning on PCB-AoI <proposals/test-reports/testing-incremental-learning-in-industrial-defect-detection-with-pcb-aoi>

.. toctree::
    :maxdepth: 1
    :caption: Contribution

    guides/how-to-contribute-test-environments
    guides/how-to-contribute-algorithms
    guides/how-to-contribute-leaderboards-or-test-reports
    guides/how-to-contribute-documentation

.. toctree::
    :maxdepth: 1
    :caption: ROADMAP

    roadmap


RELATED LINKs
=============

.. mdinclude:: related-link.md

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
