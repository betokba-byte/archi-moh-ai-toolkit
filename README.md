# 🏗️ archi-moh-ai-toolkit — AI-Powered Quantity Takeoff (QTO) for AutoCAD

> **Status:** 🚧 Active Development (Work in Progress)  
> **Built for:** Architects, Civil Engineers, and Quantity Surveyors  
> **Powered by:** Claude AI & AutoCAD Automation

## 📌 Overview
**archi-moh-ai-toolkit** is an open-source toolkit designed to bridge the gap between Artificial Intelligence and the Architecture, Engineering, and Construction (AEC) industry. 

Extracting Bills of Quantities (BOQ) and performing Quantity Takeoffs (QTO) inside AutoCAD is traditionally a repetitive, manual, and error-prone process. Starting with automated QTO, this toolkit leverages **Claude** to understand CAD entities, layer structures, and block attributes—automating quantity extraction directly from DWG drawings into structured estimation sheets.

## 🎯 Why This Project Matters
While AI has rapidly transformed software development, the AEC and CAD ecosystems remain heavily underserved. Built by an architect and engineer rather than a traditional software developer, **archi-moh-ai-toolkit** focuses on solving real-world site and office bottlenecks—turning hours of manual CAD measurement into an intelligent, automated workflow.

## ✨ Planned Features & Architecture
* **Automated Entity & Block Extraction:** Intelligently parse layers, polylines, areas, lengths, and block counts directly from AutoCAD.
* **Natural Language QTO Queries:** Ask Claude to calculate specific engineering quantities (e.g., *"Calculate total linear meters of piping on Layer X and group by diameter"*).
* **Structured BOQ Export:** Generate clean, ready-to-use tables (CSV / Excel) formatted for construction cost estimation.
* **Domain-Aware Validation:** Flag missing attributes, unclosed polylines, or overlapping geometry before finalizing quantities.

## 🗺️ Development Roadmap
- [x] Problem definition & CAD workflow mapping
- [x] Core architecture & AutoCAD integration setup
- [ ] Natural language parsing & Claude API / MCP integration
- [ ] Automated export to structured Bill of Quantities (BOQ) formats
- [ ] Public v0.1 release & documentation for AEC professionals

## 🤝 Contributing & Feedback
This project is built in the open for the architectural and engineering community. Contributions, architectural workflow suggestions, and issue reports are warmly welcome as development progresses toward v0.1.

## 📄 License
Open-source under the [MIT License](LICENSE).
