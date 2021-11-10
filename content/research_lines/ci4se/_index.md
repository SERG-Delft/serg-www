---
title: Computational Intelligence for Software Engineering
name: CI4SE
subtitle: How can Computational Intelligence techniques automate software testing and other complex software development tasks?

menu:
  main:
    parent: Research Lines

responsible_authors:
  - Annibale Panichella

collaborators:
  - Andrea Arcuri, Kristiania University College, Norvegia
  - Gordon Fraser, University of Passau, Germany
  - Vincent Hellendoorn, UC Davis, USA
  - Fitsum Kifetew, Fondazione Bruno Kessler, Italy
  - Cynthia Liem - Delft University of technology
  - Sebastiano Panichella, Zurich University of Applied Sciences, Switzerland
  - Anand Ashok Sawant, UC Davis, USA
  - Paolo Tonella, Universita’ della Svizzera Italiana, Switzerland
  - SVV Lab - Interdisciplinary Centre for Security, Reliability and Trust, University of Luxemburg

funding:
  - European Commission
  - ING
  - Ripple
---

The development, maintenance, and testing of large software products involve many activities that are complex, expensive, and error-prone. For example, complex systems (e.g., autonomous cars) are typically built as a composition of features that tend to interact and impact one another’s behavior in unknown ways. Therefore, detecting feature interaction failures with manual testing becomes infeasible and too expensive when the number and the complexity of the features increase.

There are many tribes of AI, namely Symbolists, Evolutionists, Bayesians, Kernel Conservatives, Connectionists). In the CISE Lab, we focus on applying **Computational Intelligence** (CI) to automate expensive development activities since more development automation would require fewer human resources. One of the most common ways to make such automation is the **Search-Based Software Engineering** (SBSE), which reformulates traditional software engineering tasks as search (optimization) problems. Then, **CI algorithms** (e.g., genetic algorithms, genetic programming, simulated annealing) are used to automate the process of discovering (e.g., detecting software defects) and building optimal solutions (e.g., software fixes).

SBSE is not only an academic research area, but it is achieving significant uptake in many industrial sectors. For example, **Facebook** uses multi-objective solvers to automatically design system-level test cases for mobile apps [\[1\]](https://link.springer.com/chapter/10.1007/978-3-319-99241-9_1); Google uses multi-objective solvers for regression testing [\[2\]](http://sebase.cs.ucl.ac.uk/fileadmin/crest/sebasepaper/YooNH11_01.pdf). SSBSE techniques has been also applied in the automotive domain (**IEE S.A.** [\[3\]](https://pure.tudelft.nl/portal/files/45811366/paperASE18N2016pdf.pdf)), in satellite domain (**SES S.A.** [\[4\]](https://pure.tudelft.nl/admin/files/47344874/main.pdf)) and security testing.

At the Computational Intelligence Lab, our research topics include but are not limited to the following research topics:

* **Testing for Blockchain**: Security of blockchain applications is highly critical. Our goal is to develop novel automated testing techniques that scale to the complexity of blockchain-based systems. **Related project**: [RIPPLE](https://ubri.ripple.com)
    
* **Test Case Generation**: Developing tools that automatically synthetize (generate) test cases with high code coverage (e.g., branch coverage) and that reveal faults or trigger crashes. Related projects include [Botsing](https://github.com/STAMP-project/botsing) for crash replication and [EvoSQL](https://github.com/SERG-Delft/evosql) for testing SQL queries. We also actively contribute to the [EvoSuite](https://github.com/EvoSuite/evosuite) framework for unit-level testing [\[5\]](https://apanichella.github.io/publication/ieee-tse2018b/), [\[6\]](https://apanichella.github.io/publication/ssbse2018b/), [\[7\]](https://apanichella.github.io/publication/infsof2018b/).
    
* **AI-based Penetration Testing**: Enterprise web systems use different protection layers (e.g., input sanitization, Web Application Firewalls) against malicious attacks (**code injection**). Since cyber-attacks are increasingly sophisticated, these protection layers become complex and difficult to maintain and test manually. We develop penetration testing tools that use **machine learning** (ML) techniques to identify and predict malicious string patterns that are more likely to violate the security layers. For example, we use SBSE in combination with ML to test [\[8\]](http://orbilu.uni.lu/handle/10993/34224) Vulnerable Web Application Firewalls (WAFs) and the input validation and sanitization procedures in front-end web applications [\[9\]](https://apanichella.github.io/publication/ieee-tse2018a/). **Related project**: [AI4Fintech](https://icai.ai/ai-for-fintech-lab/)
    
* **Testing Autonomous Cars**: Self-driving cars, and in general automotive systems, are feature-based systems where different units of functionalities (features) work together. To test these complex systems in an automated fashion, we use ML, and SSBSE to find test scenarios (simulation settings) that violate system requirements, hence leading to software failures [\[10\]](https://apanichella.github.io/publication/ase2018/).
    
* **Automated Program Repair**: Patching defective code is a human-intensive activity. The goal of this line for research is to develop techniques that can automatically generate correct patches boggy code without causing software regression. The most common techniques for program repair include evolutionary algorithms and machine learning (see, for example [Repairing Firewall](https://ieeexplore.ieee.org/document/8109099/), and [Self-driving cars](https://orbilu.uni.lu/bitstream/10993/43281/1/paper-CR.pdf)).
    
* **Test Amplification**: The effort and time spent by developers in software testing activities lead to extensive test suites. However, these test suites are not adequate to fulfill all of the testing criteria. In Test Amplification, we aim to improve the existing test suites by utilizing the knowledge already available in these tests. To achieve this goal, we use AI and machine learning techniques to develop fully automated tools that detect and collect the available knowledge (e.g., input data domains and object usages) from the manually-written tests and use these acquired pieces of intelligence to generate new test suites. As an example of our previous works on this topic, we have designed and implemented a strategy called behavioral model seeding. More information about this technique is available [here](https://stamp-project.github.io/botsing/pages/modelseeding.html).
    
