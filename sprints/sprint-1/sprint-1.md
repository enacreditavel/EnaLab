# 📋 Sprint 1 Planning Document

**Sprint Name:** The Blueprint & The Web
**Duration:** 2 Weeks (10 Business Days)
**Sprint Goal:** Understand the Software Development Life Cycle (SDLC), learn how to define features (User Stories), and master the basics of Web Communication (HTTP/API) to prepare for Software Testing.

---

## 📅 Week 1: From Idea to Paper (SDLC & Requirements)

### The Lifecycle (SDLC)

**Focus:** Understanding where we are in the process. Agile vs. Waterfall.
**Study Material:** [Ciclo de Vida de Software](https://www.youtube.com/watch?v=DzqranCyk6w) | [Software Development Lifecycle](https://www.daniel-abella.com/quickref/engsoft/quick-ref-sdlc.pdf)

**Action Items:**

- [ ] Read about the 6 phases of SDLC (Planning, Analysis, Design, Implementation, Testing, Maintenance).
- [ ] Understand the difference between "Waterfall" (Traditional) and "Agile" (Scrum).
- [ ] **Deliverable:** Create a diagram (draw it or use a tool like Excalidraw) showing the SDLC cycle and post it in `#daily-checkin`.

### Requirements Analysis

**Focus:** Distinguishing what the system _does_ vs. how it _behaves_.
**Study Material:** [Requirements Analysis Videos](https://www.youtube.com/playlist?list=PLrwuZVDGMIGaQvR9pgoEvYyVkemL35fEy) | [Requirements Analysis](https://www.daniel-abella.com/quickref/engsoft/quick-ref-requisitos.pdf) |

**Action Items:**

- [ ] Learn the difference between **Functional Requirements** (FR) and **Non-Functional Requirements** (NFR).
- [ ] **Deliverable:** Choose a popular app (e.g., Instagram, WhatsApp, or Spotify). List 3 Functional Requirements (e.g., "User can login") and 2 Non-Functional Requirements (e.g., "System loads in under 2 seconds") for that app in a Markdown file.

### User Stories

**Focus:** Translating requirements into Agile language.
**Study Material:** [ÉPICOS, FUNCIONALIDADES E HISTÓRIAS DE USUÁRIO](https://www.youtube.com/watch?v=X1fvJaY6mUQ) | [REQUISITOS ÁGEIS - Como escrever histórias de usuário incríveis!](https://www.youtube.com/watch?v=yG6GUqrje1k) |

**Action Items:**

- [ ] Learn the standard format: _"As a [persona], I want to [action], so that [benefit]"_.
- [ ] **Deliverable:** Write 3 User Stories for the **EnaLab Wiki** project (the one you created in Sprint 0).
  - _Example:_ "As a Trainee, I want to view a list of study links, so that I can access materials quickly."

### Acceptance Criteria (Gherkin)

**Focus:** Defining "When is this task done?". Introduction to BDD.
**Study Material:** [DoR, DoD e Critério de Aceitação](https://www.youtube.com/watch?v=Bfk3lBWWoXg) | [Gherkin: o que é e como funciona?](https://www.youtube.com/watch?v=kC3rQkaLmVY)

**Action Items:**

- [ ] Take the User Stories from Day 3.
- [ ] Add **Acceptance Criteria** to them using the **Given / When / Then** format.
  - _Example:_ **Given** I am on the home page, **When** I click "Links", **Then** I should see a list of URLs.
- [ ] **Deliverable:** Update your User Stories file on GitHub with these criteria.

---

## 📅 Week 2: The Web & The Quality (HTTP & QA Intro)

### How the Web Works (HTTP Basics)

**Focus:** The language of the internet. Request and Response.
**Study Material:** [Conceitos Essenciais: O Básico de HTTP](https://www.youtube.com/watch?v=CXzbUwK6lc8&t=7s) | [HTTP Verbs](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Reference/Methods) | [HTTP Status Dog](https://http.dog/)

**Action Items:**

- [ ] Understand the Client-Server model.
- [ ] Learn the basic HTTP Verbs: **GET, POST, PUT, DELETE**.
- [ ] Learn the Status Codes: **200 (OK), 404 (Not Found), 500 (Server Error)**.
- [ ] **Deliverable:** Open the "Network" tab in your browser's Developer Tools (F12), refresh a page (like YouTube), and find a request with a `200` status code. Take a screenshot.

### API REST & JSON

**Focus:** Data exchange format.
**Study Material:** [Uma introdução para iniciantes em programação](https://www.youtube.com/watch?v=umaXYEbd5vA&t=900s) | [O QUE É JSON? | Conceito e Prática](https://www.youtube.com/watch?v=X6xHm016WTg)

**Action Items:**

- [ ] Understand what **JSON** is (Key-Value pairs).
- [ ] **Deliverable:** Write a JSON file representing a "User Profile" (Name, Age, Skills list, IsActive boolean). Validate it using a simplistic online JSON Validator.

### Introduction to Software Testing

**Focus:** Why do we test? Preventing bugs vs. Finding bugs.
**Study Material:** [Testes de Software para iniciantes](https://www.youtube.com/playlist?list=PLx6gdu4s3nkf4OcLZ--TgMCHr22H7TDCs) | [Testes de Software do Zero](https://www.youtube.com/playlist?list=PLf8x7B3nFTl3EouPsBoqgbatKti9liVyj)

**Action Items:**

- [ ] Learn the difference between **Manual Testing** vs. **Automated Testing**.
- [ ] Understand the "Testing Pyramid" (Unit -> Integration -> E2E).
- [ ] **Deliverable:** Explain in `#daily-checkin` why we shouldn't test _everything_ manually.

### Writing Test Cases

**Focus:** Documenting how to test a feature.
**Study Material:** [Como escrever casos de teste funcionais](https://www.youtube.com/watch?v=BMeOV1-senE) | [Como criar bug report como QA](https://www.youtube.com/watch?v=vFtTtWehR0w)

**Action Items:**

- [ ] Create a Test Case for the "Login Screen" of any website.
- [ ] Include: _Test ID, Description, Pre-conditions, Steps to Reproduce, Expected Result_.
- [ ] **Deliverable:** Create a file `login-test-case.md` in your repository.
