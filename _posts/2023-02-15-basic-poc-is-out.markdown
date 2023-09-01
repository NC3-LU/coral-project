---
layout: post
title:  "First version of Fit4CSA is out"
date:   2023-02-15 15:06:54 +0200
publish-date: 2023-02-17 14:20:04 +0200
categories: community
tags: coralproject
author: ggh
toc: true
---

CORAL’s proof of concept has materialised in its first version, and it is called [Fit4CSA](https://fit4csa.nc3.lu/survey/). 

# Purpose of Fit4CSA
Fit4CSA is aimed to help any small or medium company (SME) who wishes to assess if its offered ICT process, ICT service or ICT application can be certified at a basic level in the context 
of the Cybersecurity Act. 


# Reliance on existing standards and good practices
Fit4CSA's 4 questionnaires are based on the following:
* for evaluating the security of a cloud-based service, Fit4CSA relies entire on the only (as of now) existing candidate assessment scheme for the basic-level certification  [EUCS](https://www.enisa.europa.eu/publications/eucs-cloud-service-scheme).
* for Web applications, Fit4CSA relies on good practices from OWASP’s Application Security Verification Standard 4.0.2 and OWASP's Web Security Testing Guide v4.2.
* for ICT processes, Fit4CSA is based on the standard ISO/IEC 21827:2008.
* for ICT products, Fit4CSA includes questions inspired from the candidate scheme EUCC, that the CORAL team judges to be pertinent for a basic-level of assurance. 

# CORAL's methodology 

Filling in one of Fit4CSA's questionnaires is the first step of the wider CORAL process, shown [here](/assets/images/Coral-flow.png). 

If the reached score is good enough (85% of the questions are answered well-enough), the user could move on to a new phase in which, instead of merely receiving a report with recommendations, they can register details about themselves and their company, and consequently opt to request an audit with an external company. The platform can offer a list of accredited auditors for the object of assessment of the questionnaire.

The purpose of the CORAL framework will be to keep track of the requested audits as well as of their outcomes. Should the outcome be positive, a basic-level certificate and its related data can both be managed via the CORAL prototype, using any official visual templates.

# Status and next development steps
As of now, the respondent can pick one of the 4 questionnaires, and fill it in an anonymous way. There are multiple questions presented, that can be either single or multiple choice. The survey can be stopped and, using a link that the user should save separately, can be picked up at any time. 
Once all questions are answered, the user will receive a score (projected onto a diagram of the dimensions of the assessment) and a set of recommendations that can be used to improve the state of cybersecurity of the assessed object. These recommendations are also presented in a downloadable report, that the user can save and examine offline.

In the following weeks we will be adding the user registration and auditor views to the prototype.

# Check out [Fit4CSA](https://fit4csa.nc3.lu/survey/)!
