# 🚀 Special Topic in Data Engineering Portfolio

Welcome to my repository documenting my practical work, data pipelines, and assignments completed using modern big data technologies in my Special Topic in Data Engineering course.

---

## 📂 Repository Architecture & Project Breakdown

### 🔹 Course Project: Recoverable Assets (RA) & Inventory Risk Management (IRM)
* **General Summary:** A group project focused on moving away from manual spreadsheet tracking to automated data pipelines on Microsoft Azure. Using a Medallion architecture (Bronze, Silver, Gold, and Curated layers), we cleaned and transformed manufacturing data. This allowed us to automatically monitor surplus stock, find expired paint materials, and catch stockout risks before they affect production.
* **Core Deliverables:**
  * Azure Data Factory pipelines and Databricks notebooks for data movement.
  * PySpark data cleaning scripts formatting raw data into structured star schemas.
  * Azure Synapse SQL views hooked up to a central Power BI dashboard.

### 🔹 Class Exercises: Technical Tutorials & Cloud Labs
* **General Summary:** A series of hands-on tutorials practicing cloud data management, containerization tools, artificial intelligence algorithms, and automated ingestion lines.
* **Core Deliverables:**
  * **Tutorial 1 (Microsoft Azure Cloud Workflows):** Building a complete data pipeline starting from an on-premises database all the way to a Power BI dashboard using Azure Data Factory and Databricks.
  * **Tutorial 2 (Apache Spark & Containerization):** Running local environments using Docker Compose to process a massive 2.2 GB dataset with PySpark and saving it in optimized Parquet files.
  * **Tutorial 3 (AI Algorithm - Image Classification):** Coding an Artificial Neural Network (ANN) and Convolutional Neural Network (CNN) in Python on Google Colab to classify images from the CIFAR-10 dataset.
  * **Tutorial 4 (Claude & AI-Assisted Pipelines):** Building a chat-based data pipeline with Nexla's AI agent to pull live weather API data and load it cleanly into a Snowflake data warehouse without manual coding.

---

## 💡 Academic Reflection

This course has completely changed my perspective on managing data. Before this class, I only worked with small, static data files on my local computer. Moving to big data tools like Apache Spark and cloud platforms like Microsoft Azure showed me how to engineer pipelines that can easily process massive datasets without crashing.

I learned how to solve real data bottlenecks, such as managing network connections inside Docker containers, reducing file sizes with Parquet formats, and organizing clean Medallion data architectures. This experience helped me grow from simple coding to thinking like a data systems engineer. I now feel much more confident in my ability to build automated pipelines that turn messy data streams into clean, reliable business insights.
