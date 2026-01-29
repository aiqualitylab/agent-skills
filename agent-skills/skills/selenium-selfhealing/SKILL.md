---
name: Selenium Self-Healing
version: 1.0.0
description: AI-powered self-healing Selenium tests with automatic locator recovery
author: AI Quality Lab
tags: [selenium, self-healing, testing, mcp, automation]
---

# Selenium Self-Healing Skill

## Overview
Create robust Selenium tests that automatically recover from locator failures using AI-powered element detection.

## Capabilities
- Generate Selenium tests from natural language
- Auto-heal broken locators (ID, CSS, XPath, text, attributes)
- MCP server integration for real-time healing
- Supports Java, C#, Python, JavaScript

## Usage Examples

### Generate a Test
```
Create a Selenium test:
- Open login page
- Enter username and password
- Click submit
- Verify dashboard loads
```

### Heal Broken Locator
```
The button locator "//button[@id='submit']" is failing.
Find alternative locators for this element.
```

## Installation
```bash
skills install aiqualitylab/selenium-selfhealing
```

## Links
- [MCP Server Repo](https://github.com/aiqualitylab/selenium-selfhealing-mcp)
- [Author](https://aiqualityengineer.com)