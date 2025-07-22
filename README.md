# NestJS Technical Assignment

## Description

This assignment will help in assessing your technical skills. From Typescript syntax to code structure, appropriate coding principles and design patterns, and last but not least proper and relevant test coverage.

## Project

An employee management software, nothing fancy it's just a simple API with a little bit of advanced features to showcase your skills😎 and knowledge of the NestJS framework.

## Stack/Tools

- NestJS v10
- Jest for tests
- PassportJS for authentication
- jsPDF(for pdf reports)
- excelJS(for excel reports)
- OpenApi
- TypeORM

## Features

- Full authentication system(Register, Login, Logout, Forgot password, Password reset)
- Employee CRUD, with minimum fields(names,email,employeeIdentifier,phoneNumber) all we care about is the thing to work
- Attendance management, record when an employee arrives at the office and when they leave
- Send email(using queues) to the employee when an attendance record is made
- Generate attendance report(pdf & excel) with daily attendance data
- Add a clear and concise readme that explains all the needed steps to deploy and run test of the project in a local environment
- Add github actions that run all tests on PR events
- Integrate with the OpenAI API (use ChatGPT to generate the emails sent to employees when the check in for attendance)
- The project should be containerized and running in docker

## Submission
- Share the link to your public github repository containing your code

**All features must be fully and properly tested!!!**
