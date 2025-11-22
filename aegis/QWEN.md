# AEGIS Website - Project Context

## Project Overview
The AEGIS website is a static HTML-based website for the AEGIS benchmark, which stands for "Assessing Editing, Generation, Interpretation-Understanding for Super-intelligence". It is a research project focused on evaluating Unified Multimodal Models (UMMs) that covers visual understanding, generation, editing, and interleaved generation tasks. The website presents comprehensive information about the benchmark methodology, results, and findings.

The project consists of:
- A single-page HTML interface with Material Design components
- CSS styling for responsive design and layout
- JavaScript for interactive elements and functionality
- Academic content including abstract, methodology, experimental results, and findings
- Performance comparison tables of various UMMs (Unified Multimodal Models)

## Technologies Used
- HTML5
- CSS3
- JavaScript
- Material Design Components for Web
- jQuery (for some interactive functionality)

## Key Features
- Responsive design that works on different screen sizes
- Interactive navigation menu with smooth scrolling
- Performance comparison tables showing results across multiple models and task categories
- Academic citation information with copy functionality
- Visual elements showing the benchmark methodology and results

## File Structure
- `index.html` - Main HTML file containing all website content and structure
- `style.css` - CSS styling for layout and design elements
- `script.js` - JavaScript functionality for interactive elements
- `data/` - Contains images and data visualizations used in the website
  - `pipeline.png` - Image of the data construction and evaluation pipeline
  - `teaser.png` - Teaser image for the benchmark
  - `vis.png` - Visualization image

## Project Purpose
This website serves as a presentation platform for research on the AEGIS benchmark, which aims to:
1. Evaluate Unified Multimodal Models across multiple tasks simultaneously
2. Provide deterministic checklist-based evaluation (DCE) as an alternative to ambiguous scoring methods
3. Reveal world knowledge deficits in current UMMs
4. Analyze the impact of reasoning complexity on model performance

## Development Conventions
- The website is built as a single HTML page with all content contained in index.html
- Material Design components are used for UI elements
- Tables are used to present experimental results in an organized manner
- CSS variables are used for consistent theming
- Responsive design principles are implemented using media queries
- External dependencies include Material Design CSS/JS, Font Awesome icons, and MathJax for equations

## Building and Running
This is a static website that can be served directly from a web server or opened in a browser without any build process. Simply open `index.html` in a web browser or host it using any static web server.

## Academic Context
The AEGIS benchmark introduces:
- Deterministic Checklist-based Evaluation (DCE) protocol
- Assessment of 4 key capabilities: Understanding, Generation, Editing, and Interleaved Generation
- Evaluation across 21 topics and 6 reasoning types
- Focus on world knowledge capabilities of unified multimodal models