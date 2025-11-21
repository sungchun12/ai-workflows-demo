# AI Workflows Demo

The purpose of this repo is to build a mental model and taste for building agentic workflows.

I noticed most tools to help you build workflows optimize for the getting started problem (ex: Lovebale, replit, base44) OR presume you're ready to get hands on with a full on python framework to build customer facing applications. Examples are too skewed for toys OR convoloted graphs with subagents. 

Most problems to be solved require a solution between these examples. This repo is an exploration within this gradient. 

There are lots of backoffice processes that are starting to value this gradient: TODO, add job links for the integration engineer roles.

Ultimately, this exploration is intended to answer these questions:

- Which way do I want to work given similar problems and complexity?
- How far can a prompt take me?
- How easily can I iterate and debug in the context of a specific approach?
- When does it make sense to build with complexity?

## Workflow Approaches
- Agent prompt only (create an image of the workflow)
- Configure agent with tools
- Agent for specific step, regular python steps for the rest
- Orchestrator with durable execution and scheduling

### Tools in use
- python
- pydantic-ai
- pydantic-evals
- crowdsourced prompt snippets 
- cursor
- git

### Constraints
- Open source only tools
- Must pass evaluations (unit/integration tests)

### Problem
You are an integration engineer tasked with automating every backoffice process under the sun. One particular problem is invoice processing received from various vendors using SFTP, vendor portals with logins, and emails of scanned invoices. Automatically processing them below a specific threshold, and then posting a journal entry to quickbooks. Simple on first impression, but I'm sure you can imagine how manual this is for lots of companies today.