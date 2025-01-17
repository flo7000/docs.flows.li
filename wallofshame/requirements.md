---
title: requirements
layout: home
#nav_exclude: true
nav_order: 2
#has_children: true
parent: wall of shame
---
# Requirements
This is a *bare-minimum* template to create a Jekyll site that uses the [Just the Docs] theme. You can easily set the created site to be published on [GitHub Pages] – the [README] file explains how to do that, along with other details.

## Infrastructure

### Azure Services

### Asset Management

### Office Ressources

----
## Permissions

### EntraID or Defender Roles 
You need one of the following EntraID / Defender roles to be able to run a query in the Advanced Hunting Portal:

- Global Administrator (EntraID)
- **Security Administrator (EntraID)** - recommended
- Security Operator (EntraID)
- Microsoft Defender for Endpoint Administrator (Defender)

### Rights for automation account

----
## PowerShell Modules

|**Module Name**                    | **Purpose**                                    | **Version** |
|:--------------------------------|:--------------------------------------------|:---------|
| Microsoft.Graph.Planner        | creating MS Planner Tasks with MsGraph API | 2.25.0  |
| Microsoft.Graph.Authentication | authenticating in MsGraph                  | 2.25.0  |
| Microsoft.Graph.Security       | run Advanced Hunting Queries with MsGraph  | 2.25.0  |
| Az.Accounts                    | login with Managed Identity                | 2.15.0  |
| AzTable                        | managing Storage Account Tables            | 2.1.0   |