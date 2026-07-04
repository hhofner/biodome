---
title: "Typesafety in a traditional frontend / backend application"
tags: ["vue", "development", "python"]
---

Typesafety from backend to frontend is important to a lot of developers, but often case, one
ends up in a situation were the backend and frontend are in separate languages, or on separate 
teams, or one does not simply control both sides of the application. To solve this, I have often
reached for OpenAPI SDK generators. Not only does the tool save a lot of time, I also find it to be an important
tool to maintain some sense of stability in the age of agentic AI.

## How It Works

When I mean OpenAPI SDK generators, I mean a tool that generates API call functions from an OpenAPI specification. 
There might be a few ones out there, but the most recent "Hey API" 