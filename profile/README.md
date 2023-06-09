## Welcome to Hack23! 👋

We are an organization dedicated to the development of secure open-source software applications and tools. Our mission is to enhance transparency and security in the digital world.

## About Hack23 ℹ️

Hack23 is led by [James Pether Sörling](https://www.linkedin.com/in/jamessorling/), an experienced technology professional with expertise in information security and delivery of secure cloud systems. He is a strong advocate for transparency in organizations and is committed to ensuring the security and reliability of our open-source projects through the use of industry best practices such as [OpenSSF](https://openssf.org/) and [CII Best Practices](https://bestpractices.coreinfrastructure.org/).

James has given talks at various forums, including [Javaforum Göteborg](https://www.youtube.com/watch?v=A_hq2Y03d6I), where he discussed how to secure your development pipeline with static and dynamic application security tests, as well as software composition analysis using Sonarqube. He was also a guest on the [Shift Left Like A Boss](https://www.youtube.com/watch?v=aYwSd1Wu28Q&ab_channel=Soluble/) security podcast, where he discussed open-source tools that can make high-velocity development more secure.

Visit our [Website](https://hack23.com/)

Connect with James on [LinkedIn](https://www.linkedin.com/in/jamessorling/)

## Press Coverage 📰

Hack23 and its projects have been featured in various media outlets:

- [Computer Sweden](https://computersweden.idg.se/2.2683/1.229120/tekniken-som-avslojar-politikerna) - This article highlights the innovative use of technology in revealing the activities of politicians.
- [Riksdag och Departement](http://web.archive.org/web/20090527045800/http:/www.rod.se/Artikelarkiv/2009/CIA-haller-koll-pa-riksdagsledamoterna/) - A Swedish publication that discusses the role of Citizen Intelligence Agency in monitoring politicians.
- [Expressen](https://www.expressen.se/ledare/eric-erfors/eric-erfors-skolkaren-sahlin/) - An opinion piece that addresses the issue of political absenteeism.
- [National Democratic Institute: Strengthening Parliamentary Accountability, Citizen Engagement and Access to Information](https://www.ndi.org/sites/default/files/governance-parliamentary-monitoring-organizations-survey-september-2011.pdf) - A comprehensive survey report that underscores the importance of parliamentary monitoring organizations in Sweden.

## Our Projects 🛠️

### [Citizen Intelligence Agency](https://github.com/Hack23/cia)

The Citizen Intelligence Agency is a volunteer-driven, open-source intelligence (OSINT) project that provides a neutral and comprehensive dashboard focusing on political activity in Sweden. The platform offers valuable insights into financial performance, risk metrics, and political trends, and features a ranking system for objective comparison of politicians based on performance.

Data Sources:

- [Swedish Parliament Open Data](http://data.riksdagen.se/): This comprehensive database provides a wealth of information related to the Swedish Parliament. It includes data on parliamentary members, committees, and documents, offering a deep dive into the workings of Sweden's legislative body.
- [Swedish Election Authority](http://www.val.se/): This authoritative source provides detailed information on election processes, results, and political parties in Sweden.
- [World Bank Open Data](https://data.worldbank.org/): This global database contains a vast array of development data, including economic indicators and demographic information. It's a valuable resource for understanding global trends and comparing Sweden's performance on various metrics with other countries.
- [Swedish National Financial Management Authority (ESV) Public Sector Information (PSI) Data](https://www.esv.se/): This data source offers in-depth information on government finances, economic trends, and public sector operations in Sweden. It's a crucial resource for anyone interested in understanding the financial workings of the Swedish government.

Explore our [Citizen Intelligence Agency's Architecture Overview](https://github.com/Hack23/cia/blob/master/documentation/architecture-overview.md), where you can dive into the detailed structure of our project. This page provides a comprehensive look at our project's system context, its various components, and the deployment strategy. It also includes guides for developers and database administrators, making it a valuable resource for understanding the mechanics of our work.

### [Sonar-CloudFormation-Plugin](https://github.com/Hack23/sonar-cloudformation-plugin)

The Sonar-CloudFormation-Plugin is a plugin for [SonarQube](https://www.sonarqube.org/) that allows users to analyze [CloudFormation](https://aws.amazon.com/cloudformation/) templates written in YAML or JSON. The plugin uses the SonarQube API to perform code analysis on the templates and generate detailed reports on best practices, potential security issues, and other code quality metrics. The plugin integrates with [cfn-nag](https://github.com/stelligent/cfn_nag) and [Checkov](https://www.checkov.io/) to provide additional security checks based on the [CWE](https://cwe.mitre.org/), [NIST 800-53](https://www.nist.gov/), and [ISO 27001](https://www.iso.org/standard/54534.html) standards.

### [Lambda in Private VPC](https://github.com/Hack23/lambda-in-private-vpc)

The Lambda in Private VPC is a proof-of-concept (POC) showcasing a multi-region active/active site leveraging Resilience Hub policy compliance and runbooks to facilitate rapid recovery from failures.

Concepts:
Learn more about AWS Resilience Hub concepts and understand the key terms and principles involved in building resilient applications [here](https://docs.aws.amazon.com/resilience-hub/latest/userguide/concepts-terms.html).

Runbooks:
- [DynamoDB Runbook](https://docs.aws.amazon.com/systems-manager-automation-runbooks/latest/userguide/automation-ref-ddb.html) - Automates the management of DynamoDB tables and indexes.
- [Lambda Runbook](https://docs.aws.amazon.com/systems-manager-automation-runbooks/latest/userguide/automation-ref-lam.html) - Helps manage Lambda functions, layers, and aliases.
- [Application Bridge Runbook](https://docs.aws.amazon.com/systems-manager-automation-runbooks/latest/userguide/automation-ref-abp.html) - Supports management of Amazon App Runner services and custom domains.
- [IAM Runbook](https://docs.aws.amazon.com/systems-manager-automation-runbooks/latest/userguide/automation-ref-iam.html) - Facilitates IAM user, group, role, and policy managem

## Get Involved 

We welcome contributions from the community! If you're interested in contributing, check out our repositories and feel free to submit issues or pull requests. Let's work together to make the digital world more secure and transparent!

## Contact Us 📫

For more information about Hack23, our projects, or if you have any questions, please feel free to contact us.
