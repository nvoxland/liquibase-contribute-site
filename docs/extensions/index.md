---
title: Overview
---

# Extensions Overview

Liquibase is built with extensibility in mind. From generic changelog file handling to database-specific logic, 
almost every part of Liquibase can be customized and enhanced through the extension system. 
In fact, all standard functionality that ships as part of Liquibase is built using the same extension system.

## What can extensions do?

Here are some examples of what you can achieve through extensions:

- Modify behavior for specific databases
- Create custom change types and preconditions
- Create new commands or enhance existing commands with new logic

If you'd like to have a more comprehensive overview of the Extension API, 
refer to the [Extension Guides](guides/index.md) for code samples and guides that illustrate various Extension API usage.

## How to build extensions?

Building a good extension can take a lot of time and effort. 
Here is what each section of the API docs can help you with:

- [Your First Extension](your-first-extension.md) teaches fundamental concepts for building extensions with the Hello World sample.
- [Extension Anatomy](extension-anatomy.md) describes how extension code works together.
- [Extension Guides](guides/index.md) includes guides and code samples that explain specific usages of the API.
- [Best Practices](best-practices.md) showcases best practices for providing a great user experience with your extension.

## Looking for help?

If you have questions for extension development, try asking on:

- [Liquibase Forum](https://forum.liquibase.org){:target="_blank"} Great place to ask questions, discuss, and help other members of the community.
- [Liquibase Discord](https://discord.com/invite/9yBwMtj){:target="_blank"} For real time questions and discussion