## Google Cloud Platform Servies

The List of Google Cloud services (GCP) and How to work on them.

### Compute Engine [Virtual Machines, Disks, and Network]

An IaaS service that provides virtual machines (VMs) hosted on Google’s infrastructure. Competitor services include Amazon Elastic Compute Cloud, and on-premises equivalents such as OpenStack.

### App Engine [Managed Application Platform]

A PaaS service for building web applications and mobile backends using container instances preconfigured with one of several available runtimes, each of which include a set of standard App Engine libraries. Competitor services include Amazon Elastic Beanstalk and Microsoft Azure Web Sites.

### Container Engine [Managed Kubernetes / Containers]
Cluster management and orchestration system for coordinating Docker containers. It is based on the open source Kubernetes project.
Container Registry [Private Container Registry & Storage] Private Docker repository hosted on Google’s infrastructure.
### Cloud Functions [Severless Microservices]
An event-based, asynchronous compute solution that allows you to create microservices (small, single-purpose functions) that respond to cloud events without requiring an explicitly managed server or a runtime environment. Google Cloud Functions has been in Alpha since February 2016.
### Cloud Pub/Sub [Distributed Real-time Messaging] 
A fully-managed real-time messaging service for sending and receiving messages between independent applications.
### Cloud Endpoints Frameworks for App Engine [Cloud API Gateway] 
Used to create RESTful services from your code and make them accessible to iOS, Android, and Javascript clients using App Engine. Formerly Cloud Endpoints.
## Storage and Databases
Cloud Storage [Object & File Storage and Serving] A unified object storage service, offering a spectrum of storage options including geo-redundant (low-latency, high QPS content serving to users distributed across geographic regions), regional (for workloads in a particular region), nearline (for data accessed less than once a month), and coldline (for data accessed less than once a year.) Competitor services include Amazon Simple Storage Service (geo-redundant / regional) and Amazon Glacier (coldline).
Cloud SQL [Managed MySQL] A fully-managed MySQL database service for hosting relational MySQL databases on Google’s infrastructure.
Bigtable [HBase Compatible NoSQL] A high performance NoSQL Big Data database service, designed to support very large workloads at consistent low latency and high throughput rates. Google uses Bigtable internally to power services including Search and Gmail.
Cloud Datastore [Distributed Hierarchical Key/Value Storage] A NoSQL schemaless database for storing non-relational data. It’s an alternative to Bigtable when ACID transactions are required, or the data stored is highly structured.
Cloud Spanner A managed globally distributed relational database with ACID transactions, strong consistency, SQL semantics, horizontal scaling, and high availability.
Persistent Disk [VM-Attachable Disks] A service that provides SSD and HDD storage that can be attached to instances running in either Compute Engine or Container Engine.
Cloud Source Repositories [Hosted Private Git Repositories] Private Git repositories hosted on GCP; they are currently in beta.
Big Data
BigQuery [Serverless Data Warehousing & Analytics] Serverless, fully managed, petabyte scale data warehouse and analytics platform, used to store and query Big Data using SQL.
Cloud Dataflow [Managed Data Processing] A fully-managed real-time data processing service for batch and streaming Big Data processing, supporting ETL, batch computation, and continuous computation.
Dataproc [Managed Spark & Hadoop] Managed Apache Hadoop, Apache Spark, Apache Pig, and Apache Hive service used to process large datasets.
Cloud Datalab [Data Visualization and Exploration] An interactive tool for large-scale data exploration, analysis, and visualization built on Jupyter (formerly IPython). It supports data analysis using BigQuery, Compute Engine, and Cloud Storage using Python, SQL, and JavaScript. Cloud Datalab is in open Beta.
Google Genomics [Managed Genomics Platform] An API to store, process, explore and share genomics data using the standards defined by the Global Alliance for Genomics and Health. That includes support for managing datasets, reads and variants; searching and slicing; and setting access control for sharing.
Machine Learning
Cloud Machine Learning [Machine Learning with TensorFlow] A managed service for building machine learning models using the TensorFlow framework.
The Cloud Vision API [Image Recognition and Classification] A REST API that can be used to understand the content of an image into categories, detect individual objects and faces within images, and find and read printed words contained within images¹.
The Cloud Speech API [Convert Speech to Text] A REST API that can be used to convert audio to text. The API recognizes over 80 languages and variants. The Google Cloud Speech API is currently in open Beta.
The Natural Language API [Text Parsing and Analysis] A REST API that can be used to parse the structure and meaning of text. It can extract information including the people, places, events, and sentiment within a provided text. The Google Cloud Natural Language API is currently in open Beta.
The Translate API [Language Detection and Translation] A REST API that can be used to translate an arbitrary language string into any supported language. Language identification is available for cases where the source language is unknown.
Networking
Google Cloud Virtual Network [Software Defined Network] A set of Google-managed networking capabilities, including granular IP address range selection, routes, firewalls, Virtual Private Network (VPN) and Cloud Router for provisioning your GCP resources, connecting them to each other and isolating them from one another in a Virtual Private Cloud (VPC).
Cloud Load Balancing [Multi-region Load Distribution] A service that load-balances and auto-scales GCP compute resources in single or multiple regions behind a single anycast IP².
Cloud CDN [Content Delivery Network] Uses Google’s globally distributed edge points of presence to cache HTTP(S) load-balanced content close to users.
Google Cloud Interconnect [Peer with GCP] Allows GCP customers to connect to Google via higher availability and/or lower latency connections than their existing Internet connections.
Cloud DNS [Programmable Domain Name Service] A managed authoritative Domain Name System (DNS) service running on the same infrastructure as Google. Cloud DNS translates requests for domain names into IP addresses and offers a UI, command-line interface, and API for publishing and managing millions of DNS zones and resource records.
Identity and Security
Google Cloud IAM [Identity & Access Management] Lets administrators authorize who can take action on specific resources, along with built-in auditing ³.
Cloud Resource Manager [Cloud Project Metadata Management] A service for programmatically managing the resource containers (such as Organizations and Projects) used to group and hierarchically organize GCP resources⁴.
Cloud Security Scanner [App Engine Security Scanner] A web security scanner for common vulnerabilities in App Engine applications, including cross-site-scripting (XSS), Flash injection, mixed content (HTTP in HTTPS), and outdated / insecure libraries.
Google Cloud Platform Management Services
Stackdriver [Cloud Monitoring, Logging & Diagnostics] Provides monitoring, logging, and diagnostics for applications built on cloud infrastructure including GCP and AWS. Stackdriver provides metrics, dashboards, alerting, log management, reporting, and tracing capabilities.
Deployment Manager [Template-based Infrastructure Deployment] An infrastructure automation and management service that allows you to define templates to deploy a variety of GCP services, including Cloud Storage, Compute Engine, and Cloud SQL.⁵
Cloud Shell [Browser-Based Terminal/CLI] Command-line access to cloud resources from within a browser, without having to install the Google Cloud SDK or other tools on your system⁶.
The Google Cloud Billing API [Programatic GCP Billing Management] Programmatically managed billing for your GCP projects⁷.
