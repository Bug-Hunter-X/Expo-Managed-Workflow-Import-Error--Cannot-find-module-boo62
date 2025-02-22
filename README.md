# Expo Managed Workflow Import Error: Cannot find module

This repository demonstrates a common issue in Expo's managed workflow: encountering vague 'Cannot find module' errors when importing modules.  The problem often stems from incompatibilities between the imported library and Expo's environment. This repo shows how to identify and resolve these issues. 

## Bug
The `bug.js` file demonstrates a scenario where an attempt to import a module (in this case, a hypothetical module 'uncommon-module') fails due to incompatibility with the Expo managed workflow.  The error message is typically unhelpful.

## Solution
The `bugSolution.js` file provides a solution. This might involve using a compatible alternative module, adjusting the import path, checking and installing dependencies, or configuring the module to work correctly within the Expo environment.  It highlights best practices for importing modules within Expo's managed workflow, ensuring compatibility and reducing the likelihood of encountering similar issues.