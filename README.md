# IAAUrban

IAAUrban is a static website project designed to present and publish academic events related to urban climate resilience and urban weather intelligence. The repository contains two annual workshop pages that introduce the event background, agenda, speakers, venue information, and supporting reports and map content.

## Project Overview

This project focuses on the following areas:

- Urban climate resilience and adaptation
- Urban weather and climate modelling
- Cloud computing and AI for urban environments
- Collaboration between academic research and policy/practice communities

The project is supported by UKRI IAA Starter Fund, the UoM-CUHK Joint Research Fund, and relevant partner organizations. It aims to bring together researchers, practitioners, and stakeholders to discuss climate and weather challenges in urban environments and explore practical solutions.

## Repository Structure

```text
IAAUrban/
├── 2025.html                # 2025 urban climate resilience workshop page
├── 2026.html                # 2026 Urban Weather Intelligence in the Cloud page
├── src/
│   ├── map.html             # Leaflet-based map showing the event location
│   ├── manu_white.png       # Institution logo
│   ├── u360.webp            # Institution logo
│   ├── mcca_white.png       # Institution logo
│   ├── cuhk_white.png       # Institution logo
├── SummaryReport.pdf        # Workshop summary report
├── Urban Weather Intelligence in the Cloud Workshop.pdf
├── README.md                # Project documentation
└── .gitignore
```

## Page Descriptions

### 2025.html

The 2025 page highlights:

- Urban Climate Resilience Workshop
- Event date and venue
- Workshop objectives and background
- Agenda highlights
- Partner organizations and funding information

### 2026.html

The 2026 page focuses on:

- Urban Weather Intelligence in the Cloud
- Collaboration between urban weather modelling and cloud computing
- AI-driven urban weather and climate assessment/adaptation
- Speakers and workshop themes

### src/map.html

This file is a Leaflet-based map page used to mark the event location, such as The University of Manchester, and is embedded in the website.

## Tech Stack

This project is a pure front-end static website built using:

- HTML
- CSS
- JavaScript
- Leaflet for map display

There is no complex front-end build pipeline or framework dependency.

## Local Preview

You can open the HTML files directly in a browser, or run a local static server:

```bash
cd /path/to/IAAUrban
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

To view specific pages directly:

- http://localhost:8000/2025.html
- http://localhost:8000/2026.html

## Use Cases

- Academic conference and workshop landing pages
- Urban climate and weather research communication
- Research project promotion and collaboration outreach
- Event information and report distribution

## Maintenance Notes

- To update event information, modify the relevant text directly in the corresponding HTML file.
- To replace logos or images, add new assets under the src directory and update the image paths in the page.
- To add more workshop pages, follow the same static HTML structure used in the existing files.

## License

This repository does not currently declare a specific open-source license. Any reuse or redistribution of the content should be checked against the relevant institutional and partner usage requirements.

## Note

This project is more of an academic event and research showcase website than a traditional software engineering project. Its emphasis is on content presentation, information organization, and visual communication, making it suitable for lightweight deployment of academic events and city climate-related workshops.
