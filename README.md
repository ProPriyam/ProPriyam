# Hey, I'm Priyam

**SWE @ Microsoft** | **Ex-MLE @ Mercer|Mettl** | **Infra + AI/ML Builder**

[![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://github.com/ProPriyam)
[![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://github.com/ProPriyam)
[![Azure](https://img.shields.io/badge/-Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)](https://github.com/ProPriyam)
[![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)](https://github.com/ProPriyam)
[![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)](https://github.com/ProPriyam)
[![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)](https://github.com/ProPriyam)
[![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)](https://github.com/ProPriyam)

> I build things at the intersection of infrastructure and intelligence -- and random stuff too.

Currently engineering **Azure UltraDisk** at Microsoft. Before that, shipped ML systems at Mercer|Mettl mostly around speech detection across regions and accents.

---

## What I'm Building

- Mainly Ultradisk, which is the Azure's premium high performance offering for IO-sensitive, latency-sensitive workloads.
- Tinkering and Maintaining growing collection of random projects.
- Have a lot of private finance repos that I plan to public, one by one as they stop making money :(

---

## Projects

---

## The Lab -- Project Archive

> Projects I've built and documented. Old Stuff

<details>
<summary><b>Bookworm</b> -- Multi-Modal Book Recommendation Engine</summary>

<br/>

A personalized book recommendation tool that goes beyond ratings and genres. Uses **semantic search** across multiple modalities to answer questions like *"What are some books where the MC dies?"* or *"What are similar Agatha Christie books?"*

**Stack:** Python, Streamlit, VoyageAI, KNN caching

**How it works:**
- Combines the Book Crossing Dataset, CMU Book Summary corpus, and Google Books API
- Generates recommendation embeddings via VoyageAI for semantic similarity
- Supports author-based, plot-based, and genre-based discovery
- Database similarity KNN caching for fast, relevant results

> Started as a personal itch -- I just wanted a better book recommendation for myself. Turned into a proof-of-concept for multi-modal search in recommendation systems.

[View on GitHub](https://github.com/jacobp24/bookworm_rec)

</details>

<details>
<summary><b>ML Ransomware Detection</b> -- Catching Ransomware in Virtual Machines (NetApp)</summary>

<br/>

A two-phase ML detection system built for VMware environments. Monitors VM snapshot disk files for anomalies, then drills into file structure using heuristic and signature-based methods.

**Stack:** Python, scikit-learn, VMware VMDK parsing

**How it works:**
- **Phase 1:** Anomaly detection on VMDK snapshot files -- catches unusual patterns before encryption completes
- **Phase 2:** Deep file structure analysis with heuristic + signature-based methods
- Parses raw VMDK formats into feature-extractable representations
- Real-time monitoring capable of detecting ransomware as it happens

> Built during my time working with NetApp. The code is proprietary, but the methodology is reproducible. Designed for cloud environments where ransomware targets virtual machine disk storage.

</details>

<details>
<summary><b>Scientific Paper Data Extraction</b> -- Automated Time Series Pipeline from arXiv</summary>

<br/>

End-to-end pipeline that downloads scientific papers from arXiv, extracts figures, identifies line charts, and converts them into structured time series data. Minimal manual intervention.

**Stack:** Python, PDFFigures2, SVG processing

**Pipeline stages:**
1. `downloading_arxiv.py` -- Bulk paper fetch from arXiv
2. `filtering_pdfs.py` -- Relevance filtering
3. PDFFigures2 -- Figure and caption extraction
4. `crop2pdf.py` -- Precise document cropping
5. `isLine.py` -- Line chart classification
6. `pdf2svg.py` -- Format conversion
7. `svg2time_series.py` -- Final data extraction

> Researchers spend hours manually pulling data points from published charts. This pipeline does it automatically at scale.

[View on GitHub](https://github.com/ProPriyam/scientific-paper-extraction)

</details>

---

## Connect

[![Twitter](https://img.shields.io/badge/-@ProPriyam__-1DA1F2?style=flat-square&logo=twitter&logoColor=white)](https://twitter.com/ProPriyam_)
[![LinkedIn](https://img.shields.io/badge/-propriyam-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/propriyam)
[![Website](https://img.shields.io/badge/-propriyam.github.io-FF5722?style=flat-square&logo=googlechrome&logoColor=white)](https://propriyam.github.io)
[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/ProPriyam)

---

<sub>This profile is a living document. The projects folder grows as I build.</sub>
