# SailPoint IIQ - Identity Lifecycle Automation (JML)

## Overview
This project demonstrates the implementation of Identity Lifecycle Management (Joiner-Mover-Leaver) using SailPoint IdentityIQ concepts. It simulates how users are onboarded, assigned roles, provisioned access, and deprovisioned when they leave the organization.

## Features
- Automated Joiner process (user onboarding)
- Role-based access assignment using rules
- Provisioning simulation to Active Directory
- Automated Leaver process (access revocation)

## Components
- Workflow (XML-based simulation)
- BeanShell Rule for dynamic role assignment
- Sample user data for testing lifecycle events

## Tech Stack
- SailPoint IdentityIQ (conceptual implementation)
- BeanShell scripting
- XML workflows

## Workflow Explanation
1. New user is created in the system
2. Role is assigned based on department using rules
3. Account is provisioned (simulated)
4. Access is revoked when user exits

## Note
This is a simulated project created for learning and demonstration purposes.
