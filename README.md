[![CC BY 4.0][cc-by-shield]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png

# Repository of the CDS presentation material for ISMB/ECCB 2026 — NIH/ODSS Track (July 13, 2026)

## About

This repository contains the material and information associated with our talk at ISMB/ECCB 2026, presented in the NIH/ODSS special track **"Social and Technical Infrastructure to Advance Health Research"**.

This is a full-day track hosted by the National Institutes of Health (NIH) that will explore the platforms, standards, policies, and communities that enable modern biomedical research. The session highlights NIH-funded efforts to build interoperable research ecosystems, advance FAIR data and metadata practices, promote data and software reuse, and support secure, scalable, and reproducible science. More details are available at https://www.iscb.org/ismb2026/scientific-programme/nih.

We are presenting the **Clinical Dataset Structure (CDS)**, a standardized framework for organizing multimodal clinical research data to be FAIR and AI-ready.

**Abstract**:

*Motivation*

Clinical studies collect rich multimodal data, such as surveys, wearables, and eye images. There is currently no consensus on how to structure that data into a consistently organized dataset in line with the FAIR principles. As a result, clinical datasets are hard to reuse, and datasets from different studies are not interoperable, which limits the ability to pool data across studies and particularly undermines the development of AI models.

*Methodology*

To address this challenge in the NIH Bridge2AI-supported AI Ready and Exploratory Atlas for Diabetes Insights (AI-READI) project, we developed the Clinical Dataset Structure (CDS). The CDS is a standardized framework for organizing clinical research data and metadata, developed by unifying and extending existing domain-specific standard structures (e.g., Brain Imaging Data Structure), metadata schemas (DataCite, ClinicalTrials.gov), and AI/ML-focused standards (Datasheet, Healthsheet).

*Key results*

The CDS recommends organizing multimodal clinical research datasets into one folder per data type, named according to a set convention, where applicable standard structure must then be followed within each folder. It also recommends including multiple metadata files at the root level in human-friendly (e.g., README, Healthsheet) and machine-friendly (e.g., dataset_description.json, study_description.json) formats that collectively capture over 80 metadata elements. The CDS specification is documented openly at cds-specification.readthedocs.io. The AI-READI dataset, which is structured following the CDS, has already been downloaded over 950 times and contributed to multiple publications, demonstrating real-world impact.

*Impact*

The impact of the CDS is already evident through the AI-READI dataset. We expect greater impact as adoption scales, a goal we are pursuing through community outreach and tooling development to lower implementation barriers. In this presentation, we will introduce the CDS, present its implementation in the AI-READI dataset, and explain how the community can adopt and build on it.


## Schedule

| Type | Date & Time | Authors | Session / Location | Details |
| ---- | ----------- | ------- | ------------------ | ------- |
| Talk | Monday July 13, 2026, 2:35–2:45 pm | Bhavesh Patel (presenter) et al. | NIH/ODSS Track, Session 2: Social and Technical Infrastructure to Advance Health Research | [NIH/ODSS program](https://www.iscb.org/ismb2026/scientific-programme/nih) / [ISMB 2026 website](https://www.iscb.org/ismb2026/home) |
| Panel | Monday July 13, 2026, 3:25–4:00 pm | Bhavesh Patel et al. | NIH/ODSS Track, Session 2 Panel | [NIH/ODSS program](https://www.iscb.org/ismb2026/scientific-programme/nih) / [ISMB 2026 website](https://www.iscb.org/ismb2026/home) |

## Meeting material

- `ISMB2026_Patel_CDS_talk.pdf`: slides of our talk. *(to be added closer to the event)*

## Resources

We list here major resources relevant to our talk.

| Description | Link |
| ----------- | ---- |
| CDS specification | https://cds-specification.readthedocs.io |
| AI-READI project | https://aireadi.org |
| AI-READI dataset | https://doi.org/10.60775/fairhub.3 |
| FAIR Data Innovations Hub | https://fairdataihub.org |
| ISMB 2026 NIH/ODSS track | https://www.iscb.org/ismb2026/scientific-programme/nih |
| ISMB 2026 event page (FAIR Data Innovations Hub) | https://fairdataihub.org/events/ISMB-2026 |

## License

The material in this repository is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

## Contact us

For submitting feedback or getting in touch either:
- Use the GitHub issues on this repository
- Email us: bpatel@calmi2.org
