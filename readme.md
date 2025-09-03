# Welcome to the MuleSoft Local Learning Course

This repository contains a series of self-paced learning modules designed to guide you from a complete beginner to a confident MuleSoft developer. The entire course is designed to be run on your local Windows machine without any required cloud services.

## What To Do If You Get Stuck

It is normal to get stuck! Programming and integration involve a lot of problem-solving. When you run into an error, do not get discouraged. Follow these steps:

1.  **Read The Error Message:** The answer is almost always in the red text in the Anypoint Studio console. Look for key phrases like `Element ... could not be found`, `Address already in use`, or `Invalid input`.
2.  **Check the Session's Troubleshooting Section:** Each session file has a `TROUBLESHOOTING` section with hints for common problems in that lab.
3.  **Ask the AI Tutor for Help:** Simply type **"NEEDS HELP"**. The tutor is designed to guide you with questions to help you find the solution yourself, which is the best way to learn.
4.  **Use the "Further Learning" Keywords:** Search YouTube for the keywords listed in the session file. Watching someone else explain the concept can often provide a breakthrough.

## How to Use This Course

This course is designed to be used interactively with an AI assistant who will act as your personal tutor. To get the most out of this experience, follow this workflow:

1.  **Start with Session 0:** Begin your journey with the first file, `docs/00-Setup your laptop.md`. This session is critical for setting up your local development environment. The tutor will guide you through each installation and configuration step.
2.  **Follow the Tutor, One Step at a Time:** For each session, the AI tutor will present the instructions from the session file one step at a time. Read each instruction carefully. Your job is to perform the action described, whether it's a command in PowerShell or a series of clicks in a user interface.
3.  **Provide "Evidence" and Wait for the "Gate":** After you perform a step, the tutor will ask you to provide "evidence" of your work. This might be a screenshot of your screen or the text output from a command. You must provide this evidence and wait for the tutor to confirm you've done it correctly before you move on. This "pause-and-verify" gate is the most important part of the learning process.
4.  **Use the Q&A Sessions:** After successfully completing a session, open the corresponding Q&A file (e.g., `docs/01.1-Session 1 Q&A.md`). Take a moment to think about the questions and answer them for yourself. This will solidify what you've learned. More importantly, it's your opportunity to ask the tutor any questions you have. No question is too small!
5.  **Repeat for All Sessions:** Continue this process for all sessions to build your skills progressively from the ground up.

## Course Overview

The course is broken down into **Sessions**. Each session is a self-contained lab that builds upon the skills learned in the previous one. The course is designed to be guided by an AI tutor (like me!).

The sessions follow a consistent structure:
1.  **Session File (`docs/XX-Session X.md`):** This file contains the core instructions for the lab. It outlines the goals, the steps to be taken, and the expected outcomes.
2.  **Q&A File (`docs/XX.1-Session X Q&A.md`):** Following each lab, you'll find a Q&A file. This is your opportunity to solidify your understanding. It contains a series of questions that review the key concepts from the lab.

### Course Structure

*   **Session 0: Setup Your Laptop:** Before you can write any code, this session guides you through installing all the necessary tools: Java, Maven, Anypoint Studio, and Postman.
*   **Session 1: Hello Mule:** Your first Mule application! You'll learn the basics of creating a simple HTTP API that returns a message.
*   **Session 2: Design-First with RAML:** Learn the power of the "design-first" approach by defining an API with RAML before writing any code.
*   **Session 3: Transforming Data with DataWeave:** A core skill in integration. You'll learn to read a CSV file and transform it into JSON using MuleSoft's powerful DataWeave language.
*   **Session 4: Error Handling & Logging:** Make your applications robust. This session covers how to handle errors gracefully and how to create structured, useful logs.
*   **Session 5: Configuration & Packaging:** Learn how to manage environment-specific settings using properties files and how to package your application for deployment.
*   **Session 6: Basic API Security:** Protect your APIs by implementing simple API key validation and rate limiting.
*   **Session 7: Mini-Project - The Orders API:** A capstone project where you'll combine all the skills you've learned to build a functional API that can create and retrieve orders.

## A Note on Troubleshooting

The most important skill you can learn as a developer is how to troubleshoot. Errors are not failures; they are opportunities to learn. This course is designed to help you build a "troubleshooting mindset."

When you hit an error, remember:
- **Don't Panic:** Every developer, from beginner to senior, sees errors every single day.
- **Read the Log:** The console log is your best friend. It will almost always contain a message that tells you the file, the line, and the reason for the error. Learning to scan through the logs for keywords is a superpower.
- **Use the Tutor:** When you tell the AI tutor "NEEDS HELP", it won't just give you the answer. It will ask you questions to guide you to the answer. This is intentional. The goal is not just to fix the error, but to teach you *how* to fix the error. Embrace this process!

Ready to get started? Begin with `docs/00-Setup your laptop.md`!
