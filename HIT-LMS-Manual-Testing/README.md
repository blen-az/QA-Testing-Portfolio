# HIT LMS – Manual Testing Report

**Candidate:** Blen Asaye  
**Role:** Manual QA Tester  
**Date:** Feb 10, 2026  
**Project Type:** Manual Testing Assessment  

## 1. Project Overview

This project contains a manual testing report for the HIT Learning Management System (LMS) staging environment.

The testing focused on validating core platform features including:
- User Registration
- Login & Authentication
- Course Browsing
- Course Enrollment
- Instructor Course Management
- Mobile Responsiveness
- Negative Test Cases
- Basic Security Checks

The goal was to ensure the platform behaves correctly under normal user workflows, edge cases, and UI interactions.

Some features such as course completion and certificate generation could not be fully validated because the staging environment contained placeholder content.

## 2. Testing Scope

End-to-end manual testing was performed using realistic user workflows.

The following areas were tested:
- Learner registration and authentication
- Instructor registration and course management
- Course discovery and enrollment
- UI and responsiveness on mobile devices
- Error handling and validation
- Security access controls

Features that could not be validated:
- Course completion
- Progress tracking
- Certificate generation

These features were blocked due to placeholder data in the staging environment.

## 3. Testing Environment

### Functional Testing
- **Device:** Laptop
- **Browser:** Google Chrome

### Mobile Testing
- **Device:** iPhone
- **Browser:** Safari

### Test Environment
- **Environment:** HIT LMS Staging
- **Base URL:** [https://hit-lms-frontend-production-ncfb4.ondigitalocean.app](https://hit-lms-frontend-production-ncfb4.ondigitalocean.app)
- **Instructor Registration URL:** [https://hit-lms-frontend-production-ncfb4.ondigitalocean.app/instructor/register](https://hit-lms-frontend-production-ncfb4.ondigitalocean.app/instructor/register)
- **Test OTP Code:** 123456

## 4. Test Artifacts

For detailed test coverage and defect tracking, please refer to the following artifacts in this repository:

- **[Test-Cases.md](./Test-Cases.md)**: Comprehensive suite of functional, UI, and edge-case test cases organized by module.
- **[Bug-Reports.md](./Bug-Reports.md)**: Detailed defect descriptions, severity/priority mappings, and steps to reproduce.
- **[Screenshots](./Screenshots/)**: Visual evidence of discovered issues and test evidence.

## 5. Conclusion

The HIT LMS platform demonstrates stable core functionality for registration, login, course browsing, enrollment, and instructor management.

However, several features remain untestable in the staging environment due to placeholder content, including course completion and UI edge cases representing missing data. Given the "Open" bugs regarding UX flow and duplicate icons, minor refinement will improve the overall platform presentation.
