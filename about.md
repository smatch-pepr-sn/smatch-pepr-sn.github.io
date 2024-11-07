---
layout: page
title: SMATCH
subtitle: Statistical and AI based Methods for Advanced Clinical Trials CHallenges in Digital Health
permalink: /
redirect_from:
  - /about/
  - /about.html
---

<img width="150" src="../assets/img/funding/france2030.png" style="float: right; margin-left: 30px; clear:both;"/>

SMATCH is a consortium (2023-2029) from the [PEPR Santé Numérique](https://www.inria.fr/fr/pepr-sante-numerique-projets) 
(project no. 22-PESN-0003) headed by INRIA-INSERM. It gathers researchers from 
different institutions on the development of 
*Statistical and AI based Methods for Advanced Clinical Trials CHallenges in Digital Health*.


# General Presentation

Health-related interventions and their evaluation have been revolutionized by advances 
in biotechnology and digitization and expectations are high. To support the acceleration 
of drug development and other medical interventions through the use of 
artificial intelligence (AI) and data from a variety of sources, there is a need 
for a clear understanding of the appropriateness of this use and for robust trial 
evaluation methods. The need to adapt the methods used and to propose robust 
innovative approaches to clinical trials is increasingly critical, and for example, 
the proliferation of new digital medical devices using AI alone requires specific 
methods to evaluate their ultimate impact on health.

The objective of the SMATCH project is therefore to develop and apply statistical 
and AI-based methods with the ultimate goal of accelerating the development of 
medical interventions (drugs and digital medical devices) during their 
evaluation in clinical trials based on the following assumptions: 

  1. The use of information generated in preclinical studies (animal studies, 
  organoids, in silico studies) combined with adaptive designs should help the 
  early phases of development;
  2. The integration of multi-source data including real-world and in silico data 
  should help to complete trials;
  3. Specific adaptive designs should be defined for the evaluation of digital 
  medical devices based on learning algorithms.

To this end, SMATCH is structuring its research around four operational workpackages:

  1. Research of new clinical trial methods and designs based on the translation 
  of research-based disease models from animals to humans;
  2. Development of new approaches for enriching clinical trials with multi-source 
  and multi-dimensional ancillary data;
  3. Development of next generation designs for clinical evaluation of digital 
  medical devices based on artificial intelligence algorithms;
  4. Evaluation with regulatory authorities and end-users of the regulatory impact 
  and feasibility of innovative methods for clinical trials proposed for widespread use.

<img width="85%" src="../assets/img/SMATCH_global.png" style="float: center; clear:both;"/>


The consortium is made up of **16 teams**, mainly from *Inria* and *Inserm* research 
centers recognized in this field, bringing a unique and complementary expertise 
in data sciences and AI applied to health problems and specifically to clinical 
trials. In addition, links with the regulatory bodies involved are already 
established within the consortium (e.g. HAS) and outside (e.g. EMA). Moreover, 
all methodological projects are applied to ongoing health studies in various fields.
Finally, many connections exist with the other axes of the PEPR Digital Health 
and more generally with the projects carried out within the framework of the 
digital health acceleration strategy. Thus, by providing innovative and adapted 
methodological tools that will have already been applied in a real context, we 
hope to participate in the acceleration of clinical research leading to major 
societal and economic impacts.

<img width="90%" src="../assets/img/SMATCH_map.png" style="float: center; clear:both;"/>

{% for post in site.wps %}
    {% include wps.html %}
{% endfor %}
