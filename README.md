# Open Operator

What will it take to make a versatile computer use agent that can safely and effectively handle any task?

This is a collection of resources and ideas towards this goal.

## Overview of Tasks and Features

The Open Operator project aims to enable AI agents to perform a wide range of computer tasks across several key domains:

- **Development**: Code generation, project setup, version control
- **Data Management**: Processing, analysis, and synchronization
- **Automation**: Workflows, emails, customer support
- **Web Interaction**: Navigation, form filling, research
- **System Operations**: File management, software installation, monitoring

For a detailed breakdown of tasks and capabilities, see [capabilities.md](capabilities.md).

## Benchmarks

- [WebArena](benchmarks/webarena.md) is a realistic web environment for building autonomous agents.
- [OSWorld](benchmarks/osworld.md) is a scalable, real computer environment for multimodal agents that supports task setup, execution-based evaluation, and interactive learning across operating systems.

## Benchmark Results Summary

Latest benchmark results across major evaluation frameworks as of January 2025. Human performance on OSWorld: >72.36%.

| Model                                          | WebArena | OSWorld | Openness | Notes                            |
| ---------------------------------------------- | -------- | ------- | -------- | -------------------------------- |
| [OpenAI Operator](closed/openai-operator.md)   | 58.0%    | 38.0%   | Closed   | Best overall on both benchmarks  |
| [Jace.AI](closed/jace-ai.md)                   | 57.1%    | N/A     | Closed   | Action description + Screenshots |
| [ScribeAgent](closed/scribeagent.md)           | 53.0%    | N/A     | Closed   | Proprietary training data        |
| [ORCHESTRA](closed/orchestra.md)               | 52.1%    | N/A     | Closed   | By UNC x Ventus                  |
| [Learn-by-Interact](open/learn-by-interact.md) | 48.0%    | N/A     | Open     | Best open source on WebArena     |
| [AgentOccam-Judge](open/agentoccam-judge.md)   | 45.7%    | N/A     | Open     |                                  |
| [UI-TARS-72B-DPO](open/ui-tars.md)             | N/A      | 24.6%   | Open     | Best on OSWorld                  |
| [OSCAR](open/oscar.md)                         | N/A      | 24.5%   | Open     | Best screenshot-based model      |
| [Aguvis-72B](open/aguvis.md)                   | N/A      | 17.04%  | Open     | Multimodal approach              |
| [Aria-UI](closed/aria-ui.md)                   | N/A      | 15.15%  | Closed   | By HKU & Rhymes AI               |
| [OS-Atlas](open/os-atlas.md)                   | N/A      | 14.63%  | Open     | Multiple model sizes             |
| [SeeClick](open/seeclick.md)                   | N/A      | 9.21%   | Open     | Visual interaction focus         |

For detailed results and analysis, see the individual benchmark pages:

- [WebArena Benchmark](benchmarks/webarena.md)
- [OSWorld Benchmark](benchmarks/osworld.md)

## Current Solutions

### Closed Source Solutions

- [Anthropic Computer Use](closed/anthropic-computer-use.md): Claude AI's computer use capability
- [Gumloop](closed/gumloop.md): AI-powered automation platform with visual workflow builder
- [Lutra](closed/lutra.md): AI-driven workflow automation platform
- [OpenAI Operator](closed/openai-operator.md): Upcoming autonomous AI agent for computer tasks
- [Zapier](closed/zapier.md): No-code automation platform connecting various apps and services

### Open Source Solutions

- [n8n](open/n8n.md): Workflow automation platform with extensive integration options
- [OpenAdapt](open/openadapt.md): Generative process automation framework
- [OpenHands](open/openhands.md): AI-powered software development platform
- [OpenOperator](open/openoperator.md): The easiest way to control your browser
