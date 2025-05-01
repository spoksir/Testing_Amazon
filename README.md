# Testing_Amazon
A project to test some Amazon features
<!-- PROJECT BADGES -->
<p align="center">
  <a href="https://github.com/spoksir/Testing_Amazon.git">
    <img src="https://img.shields.io/github/actions/workflow/status/spoksir/Testing_Amazon/ci.yml?branch=main" alt="CI status" />
  </a>
  <a href="https://www.cypress.io/">
    <img src="https://img.shields.io/badge/Cypress-Test%20Runner-04C38E?logo=cypress" alt="Cypress" />
  </a>
  <a href="LICENSE">
    <img src="https://img.shields.io/github/license/your-username/amazon-test-cases" alt="License" />
  </a>
</p>

# Amazon Test Cases

> A small project defining and automating end-to-end test cases for Amazon.es login and carousel features, ready to implement with Cypress.

---

<!-- DEMO ANIMATION -->
<p align="center">
  <img src="https://media.giphy.com/media/3oEjI6SIIHBdRxXI40/giphy.gif" alt="demo animation" width="600"/>
</p>

---

## 📖 Table of Contents

1. [About](#-about)  
2. [Test Cases](#-test-cases)  
3. [Getting Started](#-getting-started)  
   - [Prerequisites](#prerequisites)  
   - [Installation](#installation)  
4. [Running Tests](#-running-tests)  
5. [Project Structure](#-project-structure)  
6. [Contributing](#-contributing)  
7. [License](#-license)

---

## 📌 About

This repository contains manual and automated E2E test definitions against the Amazon.es website:

- **Login flow**  
- **Hero carousel** (manual scroll, auto-scroll, click-through)  

Phase 1: Test case documentation (this repo)  
Phase 2: Automated scripts in Cypress (coming soon!)

---

## ✅ Test Cases

| TC-ID       | Feature                   | Type                       | Description                             |
|-------------|---------------------------|----------------------------|-----------------------------------------|
| TC-01-001   | Hero Banner               | Functional System / E2E    | Scroll left & right to change slide     |
| TC-01-002   | Hero Banner               | Functional System / E2E    | Auto-scroll every 10–15s                |
| TC-01-003   | Hero Banner               | Functional System / E2E    | Click slide, verify landing page        |
| TC-02-001   | Login                     | Functional System / E2E    | Valid login (happy path)                |
| TC-02-002   | Login                     | Functional System / E2E    | Blank email error                       |
| TC-02-003   | Login                     | Functional System / E2E    | Non-existent account error              |
| TC-02-004   | Login                     | Functional System / E2E    | Invalid password error                  |
| TC-02-005   | Password Assistance       | Recovery Flow              | Assist page after too many failed tries |

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) ≥ 14.x  
- [npm](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/)  
- Internet connection  

### Installation

```bash
# Clone the repo
git clone https://github.com/spoksir/Testing_Amazon.git
cd amazon-test-cases

# Install dependencies
npm install
# or
yarn install
