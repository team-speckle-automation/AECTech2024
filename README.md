# [Project Name Placeholder]
![Project Logo](path/to/logo.png)
## Project Overview
Project created for **AEC Tech Hackathon 2024** in New York.
This project aims to streamline model analysis and enhance feedback processes for AEC projects. By integrating Speckle, we provide stakeholders easy web-based access to 3D model analysis results that update in real-time.

This setup empowers non-technical stakeholders to review analysis outputs and provide feedback directly, without needing specialized software like Revit or Rhino.
### What Pain Points Are We Solving?
- **Collaborative Analysis**: Enable stakeholders to view and interact directly with the analysis results in 3D pushed to Speckle.
- **Automated Updates**: Changes made in Revit trigger updates on Speckle, automatically performing analyses via Speckle Automate.
- **Visual Feedback**: Provide intuitive, color-coded geometry in the Speckle viewer, streamlining feedback loops.
- **Flexible Analysis**: Integrates Karamba3D within Grasshopper for customizable structural analysis, adaptable for various project needs (e.g., structural, sustainability).
## Technologies & Tools
- **Speckle**: Data exchange platform for AEC projects.
- **Revit**: BIM software with Speckle connector.
- **Grasshopper**: Visual programming for parametric design.
- **Karamba3D**: Parametric engineering tool for FEA design.
## Getting Started :rocket:
### Prerequisites
   - **Speckle Account**: Required for accessing Speckle's platform.
   - **Speckle Revit Connector**: Enables models to be pushed from Revit to Speckle. [Speckle Manager](https://speckle.guide/#speckle-manager)
   - **Grasshopper Analysis Scripts**: Used for analyzing model updates and triggering automated analysis.
   - **Karamba3D**: Used for automated structural analysis.
### Setup Instructions
1. **Create a Speckle Project**: [Speckle Setup Guide](https://speckle.guide/workspaces/projects.html)
2. **Export Revit Model to Speckle**: Use the Speckle Revit **Connector** to send your model to Speckle.
  - Optionally, set up **Speckle Scheduler** to automate sending upon syncing/saving.
4. **Configure Analysis**: Set up Grasshopper with Karamba3D to run the desired analysis automatically when syncing/saving from Revit.
5. **View and Provide Feedback**: Go to your online Speckle project viewer to review results and leave feedback.
## :movie_camera: Demo
Below is a GIF walkthrough illustrating each step, from model sync to viewing analysis results.
![Demo](demo.gif)
[Speckle Project](https://speckle.systems/viewer)
[Presentation here](link_to_slides)
## :crystal_ball: Future Work
- **Power BI Integration**: Expand data visualization with Power BI dashboards.
- **Expanded Analysis Capabilities**: Extend Speckle Compute to support more complex analyses.
---
## :busts_in_silhouette: Team
   - **Agustina Aboy** [@agusaboy](https://github.com/agusaboy)
   - **Anik**
   - **Erika Santos** [@erikasantosrocha](https://github.com/erikasantosrocha)
   - **Julio Sarachaga** [@julillosamaral](https://github.com/ulillosamaral)
   - **Kent Pretorius** 
   - **Laszlo Andrasi**
   - **Nathan Terranova** [@nterranova](https://github.com/nterranova)
   - **Stephen Prendergast** [@sgcprender](https://github.com/sgcprender)
   - **Wade Vollink** [@Wizard-Wade](https://github.com/Wizard-Wade)

Proof We Were Here: [Photos from the Hackathon](https://github.com/team-speckle-automation/AECTech2024/tree/main/Assets/photos)
