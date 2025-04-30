# Microsoft-Reactor2025
Repository for Microsoft Reactor2025 Hackathon

Sure! Here's a sample README document for your project involving an agent that automates references for Haaga-Helia University of Applied Sciences:

---
# Project Name

AIDtoReference

## Description

This project involves the development of an intelligent agent designed to automate the process of generating academic references for students and staff at Haaga-Helia University of Applied Sciences. The goal is to streamline the creation of bibliographic references across various citation styles (e.g., APA, MLA, Chicago), reducing manual workload, improving consistency, and enhancing academic productivity.

The agent is capable of parsing source information from various inputs (e.g., URLs, PDFs, or plain text) and generating formatted citations using Haaga Helia rules.

## Modifications

- Customized citation output to support Finnish and international academic standards.
- Integration with Haaga-Helia's authentication system for secure user access.
- Added support for importing metadata from national library APIs and Google Scholar.
- Extended citation style support to include European variations where applicable.
- Optimized UI for use within Moodle and other institutional LMS environments.

## Who Benefits

- **Students**: Simplifies the referencing process for assignments, theses, and projects, ensuring compliance with academic standards.
- **Faculty and Staff**: Reduces the time spent reviewing and correcting citation errors in student work.
- **Library Services**: Enhances the library’s ability to offer digital support for referencing and citation literacy.
- **IT Department**: Gains a modular, scalable tool that integrates with existing infrastructure and supports future enhancements.

## Technical Architecture Overview

- **Frontend**:  
  Built using React.js for dynamic user interaction and responsiveness, tailored for integration with Moodle and standalone use.

- **Backend**:  
  Developed in Python (FastAPI), handling citation processing, input parsing, and style formatting using the `citeproc-py` library.

- **Database**:  
  PostgreSQL stores user sessions, citation history, and customized preferences.

- **Integration Points**:  
  - National Library of Finland API for bibliographic metadata  
  - Google Books API for book data  
  - Moodle plugin for LMS embedding  
  - Haaga-Helia authentication (OAuth2)

- **Deployment**:  
  Docker-based containerized deployment hosted on Haaga-Helia’s cloud infrastructure with CI/CD via GitLab.

# Project Repository URL

# Project Demo Video

https://youtu.be/PHOsHp3ImrU?si=0pnT2D0Sed-kj8Dj
Team Members

mneang, Cath102, francinehtran
---

Let me know if you’d like this formatted for GitHub, or if you want a diagram included for the technical architecture.
