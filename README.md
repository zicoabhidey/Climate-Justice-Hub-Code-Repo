# Climate Justice Hub Code Repository

This repository contains the interactive web modules and geospatial visualizations developed during my internship for the Climate Justice Hub at the Center for the Humanities.

## 🔗 Live Implementation

The code in this repository is currently in action on the official project page: 👉 [Climate Justice Hub - Center for the Humanities](https://centerforthehumanities.org/project/climate-justice-hub/)

## 📂 Repository Structure

The project is organized in a modular format. Each folder represents a standalone webpage or a specific interactive component used within the hub:

- `Folder_Name_1/`: Specific Page, e.g., "Research Teams" -> parent_url+"/research-teams/"
- `Folder_Name_2/`: Specific Page, e.g., "Classes & Curriculums" -> parent_url+"/classes-and-curriculums/"

## 🛠️ Tech Stack

- **Leaflet.js**: Primary engine for interactive mapping, tile management, and GeoJSON data handling.
- **HTML5 Canvas**: Utilized for rendering high-performance data overlays and custom animations that require pixel-level manipulation.
- **Vanilla JavaScript (ES6+)**: Core logic for interactivity, data fetching, and state management.
- **CSS3**: Custom layouts and responsive design to ensure accessibility across all devices.

## 🚀 Key Technical Features

- **Interactive Geospatial Mapping**: Created multi-layered maps using Leaflet to visualize social vulnerability indices against climate risk factors.
- **High-Performance Overlays**: Implemented HTML5 Canvas layers to efficiently render large datasets that would typically slow down standard SVG-based map markers.
- **Data-Driven Storytelling**: Integrated narrative data into geographic interfaces, allowing users to explore humanistic stories within a scientific data framework.
- **Modular Architecture**: Built as self-contained web pages for easy integration into the Center's existing Content Management System (CMS).

## ⚙️ Requirements & Installation

This is a pure frontend repository. It does not require a `requirements.txt` or any backend server installation.

### Steps

1. Clone the repo:

```bash
git clone https://github.com/zicoabhidey/Climate-Justice-Hub-Code-Repo.git
```

2. Browse Locally

> **Important**: Because Leaflet often fetches data (GeoJSON/JSON) via AJAX, some browsers may block requests if you open files directly (`file://`). It is recommended to use a local server (like the Live Server extension in VS Code) for full functionality.

## 🏛️ Acknowledgments

This project was developed as part of an internship supporting the Climate Justice Hub initiative at the Center for the Humanities. I am grateful for the opportunity to have contributed to the Hub's mission by translating intricate environmental research into user-friendly, interactive digital platforms that serve both researchers and the general public.

**Zico Abhi Dey** - [GitHub Profile](https://github.com/zicoabhidey)
