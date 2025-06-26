# farSeer2

Farseer
Building and Deploying a Highly Available Agentic System with Log-Reading Capabilities

Purpose
Prompt Engineering
The system prompt of an LLM allows you to define the context of the agent's role. For this project, we selected a basic response structure to streamline the user experience. The full system prompt is in /farseer/backend/routes.py:

Error Analysis
Source of Error
Suggestion to Fix
Supported Logs
Web Server
System
Application
Docker Containers
Event
Optimization
Cost
xAI 'grok-beta' avg request: ~$0.0483

Backend Application
The app can be structured better to support expanding capabilities for the agent. An example of this is by moving the LLM API calls to a separate module, in case other APIs are introduced.

The app can use a model that performs better against prompt injections.
