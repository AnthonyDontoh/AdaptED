# AdaptED
### Transforming Lecture Content into Accessible Learning, Powered by AI

**NSBE 2026 Annual Convention | AI Impact-A-Thon | Sponsored by Honeywell**

**Live Demo:** https://adapted-nsbe.netlify.app

---

## The Problem

In higher education, lecture content is delivered in a single fixed format. This assumes every student processes information the same way.

Students with cognitive disabilities such as ADHD, learning disabilities, and mental health conditions often struggle not because they cannot learn the material, but because the format of instruction does not match how they process information.

At the same time, current accessibility systems require students to:
- Identify their disability to a campus office
- Request accommodations individually each semester
- Navigate multiple separate tools
- Hope their professor cooperates

This places the entire burden of accessibility on the student rather than the learning environment.

According to a Disability Resources for Students advisor at the University of Memphis, mental health conditions represent approximately 29% of students served by campus disability offices, followed by ADHD and learning disabilities as the next largest groups. These students are underserved not because solutions do not exist, but because no unified, frictionless tool exists to serve them.

---

## The Solution

**AdaptED** is an AI-powered web tool that automatically transforms lecture content into multiple accessible formats, eliminating the need for students to self-advocate or know their diagnosis.

A student simply:
1. Uploads a lecture file (PDF, DOCX, or TXT) or pastes text
2. Answers 2 simple context questions about their learning moment
3. Receives 4 accessible output formats simultaneously

No account. No diagnosis. No friction.

---

## Features

- **File Upload** - Accepts PDF, Word (.docx), and plain text files
- **Plain Language Summary** - Simplified, jargon-free summary of lecture content
- **Key Bullet Points** - Most important ideas in short digestible points
- **Core Concepts** - Key terms defined in simple one-sentence definitions
- **Quiz Questions** - Retention questions to test understanding
- **PDF Download** - Clean formatted document the student keeps
- **Text-to-Speech Audio** - Reads content aloud for students with reading difficulties
- **Screen Reader Compatible** - Built with accessible HTML throughout

---

## The Framework

AdaptED is built on **Universal Design for Learning (UDL)** - the academic framework that says educational content should be delivered in multiple formats so every learner can access it.

The core argument: AI can operationalize UDL automatically, removing the burden from both professors and students.

| Without AdaptED | With AdaptED |
|---|---|
| Student must self-identify disability | Zero self-identification required |
| Navigate 3 or more separate tools | One unified tool, one workflow |
| Request accommodations each semester | Accessible content generated instantly |
| Content never adapts to the student | Content adapts automatically |

---

## Tech Stack

| Component | Technology |
|---|---|
| Frontend | HTML, CSS, JavaScript (single file, no framework) |
| AI Model | Llama 3.3 70B via Groq API |
| PDF Parsing | PDF.js (Mozilla) |
| Hosting | Netlify |
| Framework | Universal Design for Learning (UDL) |

---

## Target Users

College students in higher education with:
- ADHD
- Learning disabilities (dyslexia, processing disorders)
- Mental health conditions (depression, anxiety, cognitive fog)

---

## How to Run Locally

1. Clone this repository
2. Open `index.html` in any modern browser
3. Get a free Groq API key at console.groq.com
4. Enter your key in the app and start transforming content

No installation. No dependencies. No build step required.

---

## Research Foundation

This project was developed following primary user research conducted with a Disability Resources for Students advisor at the University of Memphis. Key insights from that interview directly shaped the design:

- No diagnostic framing - the tool never asks users to identify a disability
- Content transformation not content exploration - differentiated from general AI tools
- Passive accessibility - screen reader compatibility built in via clean HTML
- Cognitive accessibility focus - grounded in the most common disability populations served by campus DRS offices

---

## Competition

**Event:** NSBE 2026 Annual Convention, Baltimore MD, March 18-22 2026

**Competition:** Innovation Technology AI Impact-A-Thon, Sponsored by Honeywell

**Theme:** Accessible by Design, Powered by AI

---

## Team

University of Memphis NSBE Chapter

---

*Accessible by Design. Powered by AI.*
