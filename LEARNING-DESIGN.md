# Learning-design rationale

The project combines several study experiences around one intention: help the learner understand what they are practising, then make it easier to return to it. The structure visible in the private implementation supports this rationale; it is not evidence of independently measured learning gains.

## 1. Keep an explanation close to the question

Moving between a quiz and a long book creates friction. Each lookup interrupts the session and makes it easy to focus only on finding the expected answer. The browser side panel addresses that interruption by explaining visible Moodle practice material alongside the task.

This does not remove the reference source. It changes how the learner reaches it: the assistant retrieves relevant material and presents an explanation with source information, rather than asking the learner to manually repeat the lookup every time.

## 2. Offer several routes into understanding

A learner might be stuck on one word, a sentence, a diagram or a whole topic. Those are different requests. The project therefore includes separate controls for terminology, topic/page queries and selected passages, as well as question explanations.

A useful explanation should address the concept behind the question rather than merely repeat the correct option. The design also considers related terminology and alternatives where supporting material is available. That capability still depends on retrieval quality and correct interpretation of the sources.

## 3. Distinguish evidence from confidence

An answer exposed by Moodle's review markup has a different status from an AI recommendation based on reference material. Neither justifies pretending that all uncertainty has disappeared. The interface makes these distinctions visible and supports an insufficient-evidence response.

The important learning habit is to know why an answer is supported and where to check it. A smooth explanation alone should not be mistaken for validation of a technical claim.

## 4. Let mobile access support the study habit

The mobile-friendly app makes practice available beyond a desktop study session. Theory questions, explanations, alphabet recall and radio activities are organised for phone use rather than presented only as a browser-extension feature.

The project includes PWA caching support. That helps with access to previously loaded practice content, but offline availability and current source retrieval are different things. The public overview does not claim that network-dependent AI features operate offline or that every browser-side feature is also implemented on a phone.

## 5. Practise radio language as recall and context

The phonetic alphabet and radio terminology need more than passive reading. Their practice interfaces ask for an answer, allow checking and provide correction. Standard-phrase practice also includes contextual prompts and hints.

The wider radio area includes phraseology practice and guided study of a radio-route dialogue. This connects wording with its role in a conversation. Those features are study activities, not a claim of validated voice recognition, live air-traffic simulation or operational clearance training.

## 6. Use structure when a topic needs sustained work

The separate Aircraft General Knowledge learning system adds structured lessons, topic sessions, review of mistakes and progress indicators. It is one substantial component of the project, rather than the definition of the whole project.

Coverage, recent accuracy and longer-term recall answer different questions. Progress indicators are intended to help decide what to revisit; they are not proof of competence, permission to fly or a substitute for instructor assessment.

## 7. Evaluate the components separately

The project spans reference retrieval, explanation, input extraction, practice generation, answer checking, mobile presentation and saved progress. A successful check of one area does not validate the others.

The full local suite passed on 5 November 2026, including explanation flows, mobile checks, alphabet and radio-practice tests. The separate learning-system checks passed too. Provider-facing tests use controlled local responses. A fresh live deployment review, broader device testing, instructor review and measurement of learning outcomes remain separate work.

## Public portfolio boundary

This page explains the learning decisions and trade-offs. It does not reproduce textbook passages, quiz content, radio-training material, prompts, scoring rules, configuration or executable files. The implementation and study resources remain private.

[Back to the project overview](README.md)
