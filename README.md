# AI Engineering Team Crew 🏗️🤖

A sophisticated, multi-agent AI system built with CrewAI that automates the full software development lifecycle. This crew takes high-level requirements and produces a complete, tested Python module with a functional Gradio UI, all through the collaboration of specialized AI agents.

## Overview

This application automates a professional software engineering workflow:
1.  **Engineering Lead:** Analyzes high-level requirements and creates a detailed technical design.
2.  **Backend Engineer:** Implements the design by writing clean, efficient Python code.
3.  **Frontend Engineer:** Creates a Gradio-based UI to demonstrate the backend functionality.
4.  **Test Engineer:** Writes comprehensive unit tests to ensure code quality and reliability.

It's designed for developers, product managers, and educators who want to rapidly prototype ideas or demonstrate complete technical solutions.

## Features

- **Full SDLC Automation:** Covers the entire software development process from design to testing.
- **Specialized AI Agents:** Each agent has a distinct role and expertise (design, coding, UI, testing).
- **Code Execution:** Backend and Test engineers can execute code in a safe Docker environment for validation.
- **Production-Ready Output:** Generates a complete Python package with main module, tests, and UI.
- **Multi-LLM Architecture:** Uses different LLMs optimized for each role (GPT-4o for design, Claude-3.7 for implementation).
- **Structured Configuration:** Uses YAML files for easy customization of agent behaviors and tasks.
