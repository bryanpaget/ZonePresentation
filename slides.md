---
marp: true
size: 16:9
paginate: true
footer: "Statistics Canada | Statistique Canada"
header: "August 26, 2025"
theme: default
style: |
  /* Import Inter font from Google Fonts */
  @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap');
  
  :root {
    /* Color variables */
    --primary-color: #26374a; /* Statistics Canada blue */
    --secondary-color: #ea5936; /* Statistics Canada orange */
    --accent-color: #3e6ca7;
    --light-gray: #f5f5f5;
    --dark-gray: #333;
    --text-color: #333;
    --background-color: #fff;
    
    /* Font variables */
    --main-font: 'Inter', sans-serif;
    --code-font: 'Fira Code', 'Consolas', monospace;
    
    /* Size variables */
    --base-font-size: 16px;
    --h1-size: 2em;
    --h2-size: 1.5em;
    --h3-size: 1.2em;
    --p-size: 0.9em;
    --code-size: 0.85em;
    
    /* Spacing variables */
    --section-padding: 1.5rem;
    --element-margin: 0.75rem;
  }
  
  /* Apply the font to all elements */
  * {
    font-family: var(--main-font);
  }
  
  /* Top alignment for content */
  section {
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    padding-top: 4rem;
  }
  
  /* Header styles */
  h1 {
    font-size: var(--h1-size);
    color: var(--primary-color);
    font-weight: 600;
    margin-bottom: var(--element-margin);
    margin-top: 0;
  }
  
  h2 {
    font-size: var(--h2-size);
    font-weight: 500;
    margin-bottom: var(--element-margin);
    margin-top: 0;
  }
  
  h3 {
    font-size: var(--h3-size);
    font-weight: 500;
    margin-bottom: var(--element-margin);
    margin-top: 0;
  }
  
  /* Paragraph styles */
  p {
    font-size: var(--p-size);
    color: var(--text-color);
    line-height: 1.2;
    margin-bottom: var(--element-margin);
  }
  
  /* Code block styles */
  pre > code {
    font-family: var(--code-font);
    font-size: var(--code-size);
    background-color: var(--light-gray);
    padding: 1rem;
    border-radius: 4px;
    line-height: 1.4;
  }
  
  /* Blockquote styles */
  blockquote {
    border-left: 4px solid var(--secondary-color);
    padding-left: 1rem;
    margin-left: 0;
    color: var(--dark-gray);
    font-style: italic;
  }
  
  /* List styles */
  ul, ol {
    font-size: var(--p-size);
    margin-bottom: var(--element-margin);
  }
  
  li {
    margin-bottom: 0.5rem;
  }
  
  /* Footer and header customization */
  footer, header {
    font-size: 0.8em;
    color: var(--primary-color);
    opacity: 0.8;
  }
  
  /* Background image adjustments */
  img[bg] {
    opacity: 0.15;
  }
  
  /* Link styling */
  a {
    color: var(--accent-color);
    text-decoration: none;
  }
  
  a:hover {
    text-decoration: underline;
  }
  
  /* Custom classes for special elements */
  .highlight {
    background-color: rgba(234, 89, 54, 0.1);
    padding: 0.2rem 0.4rem;
    border-radius: 3px;
    font-weight: 500;
  }
  
  .callout {
    border-left: 4px solid var(--secondary-color);
    background-color: var(--light-gray);
    padding: 1rem;
    margin: 1rem 0;
  }
  
  /* Center the lead/title slide */
  .lead {
    justify-content: center;
    text-align: center;
  }
---

<!-- Title Slide -->
<!-- _class: lead -->
# The Zone  
### A Modern Data Science Platform 
#### For Statistics Canada

<br>

###### *Brought to you by The Zone Team :heart:*
![bg left:33%](./canada-0.png)

---

<!-- Who We Are -->
## The Zone Team

**Summer 2025**

![bg left:33%](./zone-0.png)

- Souheil Yazji
- Mathis Marcotte
- Jose Matsuda
- Wendy Gaultier
- Bryan Paget  

> **With special thanks to our co-op students Justin Zhang and Anray Liu**

---

<!-- Our Story / History -->
## Our Story

**One Platform, Two Zones**

![bg left:33%](./zone-1.png)

* The Advanced Analytics Workspace (AAW) was the first Zone  
* The Zone is its Protected B counterpart  
* Built on the same foundation:  
  **Kubeflow on Kubernetes**

> **Same core. Same capabilities. Higher security.**

---

<!-- What is The Zone? -->
## What Is The Zone?

![bg left:33%](./zone-1.png)

The Zone is a data science platform based on **Kubeflow**, designed to orchestrate notebooks, jobs, and machine learning workflows.

Featuring:

* **JupyterLab** supporting Python, R, SAS, Julia  
* **Kubeflow** for scalable infrastructure for data science and automation  

> The Zone is a platform that runs on Azure AKS
> but can run on any **Kubernetes** cluster.

---

<!-- Inclusivity & SAS Coexistence -->
## Everyone Is Welcome

![bg left:33%](./zone-3.png)

### Which Language? No Barrier.

* Python, R, Julia, SAS are all supported  
* Migrate at your pace, in your language  
* **The only platform at StatCan where SAS and Python/R coexist**

---

<!-- Inclusivity & SAS Coexistence -->
## Everyone Is Welcome

![bg left:33%](./zone-3.png)

### Which Organization? No Barrier.

* Open source by design: cloneable, shareable, federatable  
* We've already done it once: we can do it again  
* Ready to support other teams, departments, and levels of government

---

<!-- Why Created -->
## Why Was The Zone Created?

![bg left:33%](./zone-5.png)

To deliver a secure, modern, and independent data platform.

* Provide a **Protected B compliant** environment  
* Reduce reliance on proprietary tools  
* Long-term cost reduction through reusable, open infrastructure

> **This is about sovereignty, sustainability, and self-reliance.**

---

<!-- Platform Strengths -->
## What We've Built

![bg left:33%](./zone-5.png)

* Over 2,200 users  
* 130+ daily notebook sessions  
* CronJobs powering real production workflows  
* A stable, proven platform used across divisions

> **This is not a prototype.**  
> **This is production grade.**

---

<!-- Summer 2025 -->
## Summer 2025

![bg left:33%](./zone-5.png)

* **MKL** acceleration for faster numerical computing  
* Tesseract **OCR** to extract text from scanned documents  
* **Volume and namespace cleaners** for automatic resource cleanup  
* **CronJobs** for scheduling our pipeline-ready infrastructure

> **Smarter. Cleaner. Faster.**

---

<!-- From Cron to Pipeline -->
## From CronJobs to Pipelines

![bg left:33%](./zone-8.png)

**Today:** CronJobs run in isolation.

**Tomorrow:** Connected, observable workflows powered by **Argo Workflows** and **Kubeflow Pipelines**.

* Argo Workflows orchestrates complex job sequences on Kubernetes  
* Kubeflow Pipelines enable end-to-end ML workflows with UI, caching, versioning  
* Full logging, retry logic, error handling, triggers

> **Automation, evolved.**

---

<!-- Future: Kubernetes Is Built for Orchestration -->
## Kubernetes Is Built for Orchestration

![bg left:16%](./canada-0.png)

At its core, **Kubernetes is designed to orchestrate workloads**: scaling, scheduling, and managing containers across clusters.

* Powers modern cloud-native apps  
* Handles complex workflows reliably  
* Already runs The Zone's notebooks and jobs

> **Orchestration isn't the future.**
> **It's already here, under the hood.**

---

<!-- Future: Kubeflow Brings Orchestration to Data Science -->
## Kubeflow Brings Orchestration to Data Scientists

![bg left:14%](./canada-0.png)

**Kubeflow was built for pipelines.** It brings Kubernetes' power to data scientists through a clean, intuitive interface.

* The AAW used **Kubeflow Pipelines** and **Argo Workflows**  
* We can re-enable them in The Zone, no reinvention needed  
* End-to-end workflows: versioned, reproducible, monitored

> **We're not starting from scratch.**
> **We're restoring what works and making it secure, scalable, standard.**

---

<!-- Data Access -->
## Challenges Remain

![bg left:33%](./zone-9.png)

* Database onboarding: slow (network policies)  
* Legacy filer performance: limiting (data migration)  
* Kubernetes concepts: unfamiliar (education)  
* Secrets management: in progress (Keycloak)

> **We're solving these, with your feedback.**

---

<!-- Portability & Federated Future -->
## A Federated Future

![bg left:33%](./zone-10.png)

The Zone is open source and designed to scale. It can be deployed by:

* Other teams at StatCan  
* Federal departments  
* Provincial and municipal governments

> **Same foundation. Same security.**
> **Deployed where you need it.**

---

<!-- Call to Action -->
## Enter The Zone

![bg left:33%](./zone-10.png)

You are invited to:

* Access the platform: https://zone.statcan.ca  
* Attend training and workshops  
* Help shape the future of data science at StatCan  
* Host the next Zone in your department

> **The Zone is a movement toward openness, sovereignty, and shared capability.**