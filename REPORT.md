# Voxgig SDK Task Report

**Author:** Sujal Parmar


## Introduction

For this task, I used the Voxgig SDK Generator to create an open-source SDK for the Resend API and published it to my GitHub account under the MIT License.

I selected Resend because it provides a public API and I did not find an existing Resend SDK in the Voxgig SDK repository list.

## What I Did

- Created a public GitHub repository.
- Generated a TypeScript SDK using the Voxgig SDK Generator.
- Generated the SDK from the Resend OpenAPI specification.
- Reviewed the generated project structure and documentation.
- Fixed Git merge conflicts that appeared during the setup process.
- Published the generated SDK to GitHub.

## Experience Using the SDK Generator

The overall setup process was straightforward. Most of the project structure, documentation, and SDK code were generated automatically, which significantly reduced the amount of manual work required.

One thing I liked was that the generated repository already included documentation, licensing information, build files, and a clear project structure. This made the generated SDK feel close to a usable open-source project from the start.

The entity-based approach was also interesting because it presents the API through entities rather than requiring direct interaction with raw endpoints.

## Issues Encountered

During the process, I ran into a few minor issues:


1. I encountered merge conflicts in the README and LICENSE files and had to resolve them manually.
2. Some generated entity names were quite long because they were based directly on names from the OpenAPI specification.

None of these issues prevented completion of the task, but they required a little manual cleanup.

## Conclusion

The SDK was generated successfully and published as an open-source project on GitHub. Overall, the experience was positive and the generator made it possible to create a working SDK with relatively little manual effort.

Thank you for the opportunity to try the Voxgig SDK Generator.