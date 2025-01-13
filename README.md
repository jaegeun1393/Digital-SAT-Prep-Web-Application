# Problem Vault Prep Platform
<div align="center">
  <img src="https://github.com/jaegeun1393/Digital-SAT-Prep-Web-Application/blob/main/Screenshot%202025-01-13%20005644.png">
</div>

<div align="center">

  ![Build](https://img.shields.io/badge/Build-Complete-green)
  ![Front-end](https://img.shields.io/badge/Front--end-React%20%2B%20Vite-lightblue)
  ![Back-end](https://img.shields.io/badge/Back--end-Nodejs%20%2B%20Socket%20%2B%20PM2%20%2B%20Azure-yellowgreen)
  [![Link](https://img.shields.io/badge/Link-sat.mmtprep.com-blue)](https://pvault.mmtprep.com/)
[![Design](https://img.shields.io/badge/Design-Figma-purple)](https://www.figma.com/design/G31dlUNZl9FQuMkDKBZo9O/Quiz-24-Template?node-id=0-1&t=TiISj7hKd0ZkNqTj-1)

</div>


## Short Description
Welcome to our Digital SAT platform, designed to let students take the test on any device. Our main focus is a tutoring system that connects students with teachers to enhance their study time. We've developed a GPT-4-based system on Azure that grades AP exam Free Response Questions (FRQs) according to various rules and cases. By carefully adjusting the token size, we deliver high-quality answers and scoring with fewer tokens. Leveraging our existing Node.js server and Azure's API, we've expanded our capabilities to offer users a more stable and comprehensive service.

### Technology Stack
- **Front-end:** React + Vite.js
  <div align="center">
  <img src="https://github.com/jaegeun1393/MMTPrep_Tutoring/blob/main/1708033784779.png">
</div>

- **Back-end:** Node.js with Azure
<div align="center">
  <img src="https://github.com/jaegeun1393/Digital-SAT-Prep-Web-Application/blob/main/back-end.png">
</div>


## Core Features
- SAT, SAT10, SAT 89, and ACT platform support
- Custom test creation
- Test result analysis tab
- Class registration
- Note taking
- Same test environment as the official SAT

---

## **SAT, SAT10, SAT 89, and ACT Platform Support**
<div align="center">
  <img src="https://github.com/jaegeun1393/Digital-SAT-Prep-Web-Application/blob/main/Screenshot%202024-11-03%20205052.png">
</div>

Our website supports multiple test sets and generates random questions following the formats provided by the Digital SAT Bluebook. By utilizing hashmaps, we've focused on achieving rapid data loading—even with a massive number of problems or lengthy texts. This means there's virtually no latency when accessing any of the over 80,000 LaTeX-rendered questions on our platform, all without any visual glitches in rendering.

## **Custom Test Creation**
<div align="center">
  <img src="https://github.com/jaegeun1393/Digital-SAT-Prep-Web-Application/blob/main/Screenshot%202024-11-03%20212157.png">
</div>
<div align="center">
  <img src="https://github.com/jaegeun1393/Digital-SAT-Prep-Web-Application/blob/main/Screenshot%202024-11-03%20212147.png">
</div>

By saving user quiz and test data, the website provides tools to create custom tests. If there is a specific topic the user wants to focus on, they can create their own test to enhance their understanding of that topic. It supports various platforms such as SAT, SAT89, SAT10, and ACT.

## **Test Result Analysis Tab**
<div align="center">
  <img src="https://github.com/jaegeun1393/Digital-SAT-Prep-Web-Application/blob/main/Screenshot%202024-11-03%20212635.png">
</div>

This feature provides a final report that analyzes the user's strengths and weaknesses along with overall average SAT scores. It offers performance analysis data to help users develop a personalized study path. The analysis tab also includes visual data representations, such as bar and circle graphs, for an intuitive understanding of progress.

## **Class Registration**
<div align="center">
  <img src="https://github.com/jaegeun1393/Digital-SAT-Prep-Web-Application/blob/main/Screenshot%202024-11-03%20213252.png">
</div>

As mentioned in the introduction, this platform focuses on tutoring, allowing tutors to create SAT classes, assign homework, and monitor student progress. When a student needs a teacher's support, this feature provides the analysis data to facilitate effective tutoring sessions.

## **Note Taking**
<div align="center">
  <img src="https://github.com/jaegeun1393/Digital-SAT-Prep-Web-Application/blob/main/Screenshot%202024-11-03%20212820.png">
</div>

When a teacher is demonstrating how to solve a problem step-by-step, this feature allows for easy note-taking and replaying of the process. This helps students review the solution methods at their own pace. Notes can also be shared publicly to assist other users.

## **Same Test Environment**
<div align="center">
  <img src="https://github.com/jaegeun1393/Digital-SAT-Prep-Web-Application/blob/main/Screenshot%202024-11-03%20212905.png">
</div>

The platform provides the same UI as the official Digital SAT. Features such as the timer, section descriptions, calculator, and references match the official SAT app, ensuring that students won't feel a gap between practicing for the SAT and taking the actual test.

## **Additionally...**
<div align="center">
  <img src="https://github.com/jaegeun1393/Digital-SAT-Prep-Web-Application/blob/main/Screenshot%202024-11-03%20205027.png">
</div>

Additionally, this project started with the goal of creating a web platform to accompany the SAT book developed by MMTPrep. The math topics, study materials, and practice problems presented in the SAT book are designed to align seamlessly with this digital SAT platform, providing a cohesive study experience.

