# AI Trading System

A professional academic project focused on the design of an intelligent investment support system that combines multi-agent analysis, adaptive memory, probabilistic decision logic, and an interactive interface for structured financial reasoning.

**Authors:** Daniel Rodríguez Calderón, Pablo Maestro Fernández  
**Project Type:** Academic / Portfolio Showcase  
**Status:** Private core implementation, public conceptual presentation

## Overview

This repository presents the conceptual design, interface, and system architecture of an AI-driven trading and investment analysis platform. The project was developed to explore how autonomous analytical modules can collaborate to generate structured financial insights through a unified decision workflow.

The system brings together several complementary layers: user profiling, market interpretation, evaluator reasoning, risk analysis, recommendation logic, and decision support visualization. The goal is not to expose the private production code, but to document the design approach, the architecture, and the user-facing dashboard in a clear and professional way.

## Objective

The project was created to study how an intelligent financial system can combine parallel agent reasoning, adaptive memory, and structured decision processes in a single environment. It aims to transform complex market information into readable, organized, and explainable outputs for the user.

In practical terms, the system was designed to:

- Organize financial analysis into specialized modules.
- Combine qualitative and quantitative reasoning.
- Incorporate user profiling into the interpretation of recommendations.
- Support structured decision-making through an interactive dashboard.
- Present financial outputs in a way that is more interpretable than raw technical signals alone.

## System Architecture

The platform follows a modular architecture in which an interactive front-end communicates with a graph-based orchestration layer that coordinates several specialized analytical components. Each component contributes a different perspective to the final output shown in the dashboard.

![Architecture Diagram](images/arquitecture.png)

## Architecture Explanation

The overall system is organized around the following conceptual blocks:

- **Interactive Interface:** A Gradio-based front-end used to present the analysis flow and the final outputs to the user.
- **Graph / Orchestration Layer:** A coordination structure that routes information across the different modules and consolidates their outputs.
- **Specialized Agents:** Distinct analytical components responsible for profiling, evaluation, risk interpretation, recommendation reasoning, and complementary financial analysis.
- **Adaptive Memory:** Internal persistence mechanisms intended to retain selected historical context and improve continuity across analytical cycles.
- **Decision Support Logic:** A structured reasoning layer designed to support investment interpretation using state-based or probabilistic decision processes.

## Key Design Principles

The project was guided by several technical and presentation principles:

- **Modularity:** Each analytical responsibility is isolated in a separate component.
- **Explainability:** Outputs are designed to be interpretable rather than opaque.
- **Scalability of reasoning:** New analytical blocks can be incorporated without redesigning the whole system.
- **User-centered presentation:** The dashboard is intended to make complex information readable and structured.
- **Separation of public and private layers:** The public repository documents the work without exposing the sensitive implementation details.

## Technology Stack

The private implementation of the project is based on a Python-centered workflow for agent coordination, financial analysis, and interface rendering. The public repository focuses on the conceptual presentation rather than on shipping the underlying source code.

Main technologies and concepts used in the project include:

- Python
- Gradio
- Multi-agent reasoning
- Graph-based workflow orchestration
- Adaptive memory design
- Financial analytics and recommendation support
- Version control with Git and GitHub

## Dashboard Gallery

### Dashboard View 
![Gradio App Screenshot 01](images/dashboard1.png)
![Gradio App Screenshot 02](images/dashboard2.png)
![Gradio App Screenshot 03](images/dashboard3.png)
![Gradio App Screenshot 04](images/dashboard4.png)
![Gradio App Screenshot 05](images/dashboard5.png)
![Gradio App Screenshot 06](images/dashboard6.png)
![Gradio App Screenshot 07](images/dashboard7.png)
![Gradio App Screenshot 08](images/dashboard8.png)
![Gradio App Screenshot 09](images/dashboard9.png)
![Gradio App Screenshot 10](images/dashboard10.png)
![Gradio App Screenshot 11](images/dashboard11.png)
![Gradio App Screenshot 12](images/dashboard12.png)
![Gradio App Screenshot 13](images/dashboard13.png)
![Gradio App Screenshot 14](images/dashboard14.png)
![Gradio App Screenshot 15](images/dashboard15.png)
![Gradio App Screenshot 16](images/dashboard16.png)

## What This Repository Includes

This public version is intended as a professional showcase of the project. It is designed to communicate the quality of the work, the structure of the system, and the visual interface without publishing the private implementation.

This repository may include:

- High-level project description
- Architecture overview
- Interface screenshots
- Conceptual explanation of the analytical workflow
- Public documentation for academic or portfolio purposes

## What This Repository Does Not Include

To preserve the private implementation and the most sensitive technical assets, this repository does not expose:

- The full source code
- Internal agent logic
- Memory files or generated histories
- Private execution workflows
- Deployment credentials or operational configuration
- Proprietary implementation details of the decision pipeline

## Repository Purpose

This repository is intended to document the ideas, architecture, and interface design of the project in a portfolio-friendly format. It functions as a public-facing technical presentation of the work rather than as a distributable software package.

## License

This repository is shared for presentation and academic portfolio purposes. Review the `LICENSE` file for the applicable usage terms.
