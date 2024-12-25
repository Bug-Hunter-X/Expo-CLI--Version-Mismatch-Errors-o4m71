# Expo CLI Version Mismatch Errors

This repository demonstrates a common issue encountered when using the Expo CLI: version mismatches between the CLI itself and the project's dependencies.

## Problem

The core problem arises from inconsistencies between the version of the `expo` package (and related dependencies) in your `package.json` and the version of the Expo CLI installed on your system.

This can lead to various errors, ranging from build failures to runtime crashes.

## Solution

The solution usually involves either updating the Expo CLI to the latest version or modifying your project's `package.json` to align with a compatible set of dependencies. This repository provides examples of both approaches.

## Setup

Clone the repository and navigate to the project directory.

Run `npm install` to install the necessary dependencies.

You can then run the test commands found within the `expoBug.js` file to observe the error and the solution provided in `expoBugSolution.js`.