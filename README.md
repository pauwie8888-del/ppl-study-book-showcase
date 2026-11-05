# PPL Study Assistant — Theory, Moodle Explanations and Radio Practice

A personal aviation learning project that brings explanations, practice and revision closer to the moment they are needed. It includes a browser study assistant, a mobile-friendly practice app and a structured Aircraft General Knowledge learning system.

This is an information-only portfolio. The application, study materials, books and question banks remain private.

## The problem I wanted to solve

A chapter quiz tells me whether I chose the expected answer, but it does not necessarily explain the concept, an unfamiliar term or why an alternative answer is wrong. Looking up each point manually interrupts studying. Studying only at a computer also makes it harder to use short opportunities for revision.

The project addresses both problems: explanations beside the material I am working on, and practice that is easy to access on a phone. Chapter questions are one part of that wider learning experience.

## What the project includes

| Area | What it does | Where it is implemented |
|---|---|---|
| Terminology and concept explanations | Explains aviation keywords and concepts in simpler language | Browser study side panel |
| Ask the book | Accepts a topic, section, sentence or page reference and provides a study explanation with references | Browser study side panel |
| Selected-text explanations | Lets the learner load a book page and ask for an explanation of a selected passage | Browser study side panel |
| Moodle answer explanations | Reads the visible practice question and options, looks for relevant reference material and explains the answer within the study interface, without requiring a separate manual book lookup | Browser extension on supported Moodle practice/review pages |
| Diagram-based study | Includes a path for studying visible question images with AI assistance | Browser extension; image clarity and provider availability matter |
| Mobile theory revision | Offers chapter-based questions, explanations and progress review in a phone-friendly interface | Mobile web app/PWA |
| Aviation phonetic alphabet | Provides recall practice, answer checking and correction | Browser side panel and mobile app |
| Radio terminology and standard phrases | Provides recall exercises with feedback, hints and review | Browser side panel and mobile app |
| Radio phraseology and guided study | Includes a dedicated phraseology practice view and a mobile guided radio-route study area with explanations | Browser practice view and mobile app; content differs between surfaces |
| Structured learning and revision | Combines lessons, topic practice, spaced review, a mistake log and progress indicators | Separate Aircraft General Knowledge study system |

The private project also contains a separate local PDF question-answering exploration. Its presence is not treated as proof that it is part of the verified browser or mobile experience.

## Why I designed it this way

**Reduce the interruption between a question and understanding it.** The side panel keeps the explanation near the Moodle practice task. The source material is still consulted by the system; the learner does not have to repeatedly leave the question to search through the book manually.

**Support more than finding the correct letter.** Terminology, topic and selected-text explanations provide ways to understand the underlying idea. This matters when the difficulty is wording rather than the entire topic.

**Make revision practical away from the desk.** The mobile interface supports short theory and radio-practice sessions. Cached practice content can support offline use after it has been loaded; AI-assisted explanations and fresh source retrieval can still require network access.

**Use different practice for different skills.** Reading a concept, recognising a correct answer, recalling alphabet words and producing a radio phrase are different learning tasks. The project gives them distinct study activities rather than treating them all as the same chapter quiz.

**Keep uncertainty visible.** A Moodle review answer key, a source-supported recommendation and insufficient evidence are different statuses. A confident explanation is not automatically an independently verified answer.

[Read the detailed learning-design rationale](LEARNING-DESIGN.md)

## What was checked

On 5 November 2026, the full local project test command passed. It includes extension extraction and explanation-flow checks, keyword/topic/selected-text controls, source-retrieval and refusal cases, mobile app checks, phonetic alphabet practice, standard radio words and phraseology practice. Provider-facing tests use controlled local responses; this is not a new paid AI test or a live Moodle/browser-session test.

The separate Aircraft General Knowledge content-structure check also passed, alongside 32 learning-logic tests. Those checks cover areas such as review scheduling, progress rules, practice selection and saved-state handling.

The review inspected the browser implementation, mobile interface and service worker, radio-practice modules, learning game, tests and hosting documentation. It did not verify a fresh mobile deployment or every device/browser combination. Passing structural and logic checks does not establish that every teaching explanation is correct.

## Scope and limits

The project supports personal theory revision and radio study. It is not an official textbook, certified course, live-exam tool or operational flight reference. The inspected implementation covers more than Aircraft General Knowledge, including Principles of Flight practice and radio study; it does not establish complete, equally tested coverage of every PPL subject.

Source access, Moodle page structure, image quality and AI-provider availability can affect explanations. Instructor review and appropriate authoritative references remain important. No exam pass rate or measured improvement in retention is claimed. Third-party textbooks and training materials remain the property of their respective owners.

## What is public

Only this project description and its design rationale are published. No textbooks, PDFs, lessons, question text, answer keys, diagrams, application downloads, source code, prompts or personal progress data are included. The public descriptions can be copied or saved; the working study system is not distributed here.
