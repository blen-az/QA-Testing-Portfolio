# 🧪 Test Cases

## 1. Learner Registration Test Cases
| TC ID | Feature | Steps | Test Data | Expected Result |
|-------|---------|-------|-----------|-----------------|
| TC_LR_01 | Valid Registration | Enter valid phone → submit → enter OTP | Phone: valid number, OTP: 123456 | Account successfully created and user logged in |
| TC_LR_02 | Invalid Phone Number | Enter fewer than required digits | Phone: 12345 | Validation error displayed |
| TC_LR_03 | Empty Phone Field | Submit form without phone number | None | Error message displayed |
| TC_LR_04 | Valid OTP Verification | Enter correct OTP | OTP: 123456 | Verification successful |
| TC_LR_05 | Invalid OTP | Enter incorrect OTP | OTP: 111111 | Error message displayed |
| TC_LR_06 | Resend OTP | Click resend OTP button | None | New OTP sent to user |

## 2. Login Module Test Cases
| TC ID | Scenario | Steps | Test Data | Expected Result |
|-------|----------|-------|-----------|-----------------|
| TC_LG_01 | Valid Login | Enter correct phone and password | Valid credentials | User successfully logged in |
| TC_LG_02 | Invalid Password | Enter correct phone and wrong password | Wrong password | Error message displayed |
| TC_LG_03 | Unregistered Phone | Enter phone number not registered | Unregistered phone | Login blocked |
| TC_LG_04 | Empty Phone Field | Submit without phone number | None | Validation error displayed |
| TC_LG_05 | Empty Password Field | Submit without password | None | Validation error displayed |
| TC_LG_06 | Password Visibility Toggle | Click show/hide password icon | Valid password | Password visibility toggled |
| TC_LG_07 | Session Persistence | Login then refresh browser | Valid login | User remains logged in |
| TC_LG_08 | Logout | Click logout button | Logged in user | User redirected to login page |
| TC_LG_09 | Back Button After Logout | Logout then click browser back button | None | Dashboard not accessible |
| TC_LG_10 | Network Failure During Login | Disable internet and attempt login | None | Network error message shown |

## 3. Course Browsing Test Cases
| TC ID | Feature | Steps | Expected Result |
|-------|---------|-------|-----------------|
| TC_CB_01 | View Course List | Navigate to Courses page | Course list displayed |
| TC_CB_02 | View Course Details | Click on a course | Course detail page opens |
| TC_CB_03 | Search Course | Enter keyword in search bar | Relevant courses displayed |
| TC_CB_04 | Filter Courses | Apply course filter | Filtered results shown |

## 4. Course Enrollment Test Cases
| TC ID | Feature | Steps | Expected Result |
|-------|---------|-------|-----------------|
| TC_EN_01 | Enroll in Course | Click Enroll button | Enrollment successful |
| TC_EN_02 | Prevent Re-Enrollment | Attempt to enroll again | Duplicate enrollment prevented |
| TC_EN_03 | Course Access | Open enrolled course | Course lessons accessible |
| TC_EN_04 | Full Course Enrollment | Try enrolling in full course | Enrollment blocked |
| TC_EN_05 | Invalid User Enrollment | Enroll with inactive account | Enrollment blocked |
| TC_EN_06 | Paid Course Enrollment | Enroll in paid course | Redirected to payment |
| TC_EN_07 | Enrollment Confirmation | Enroll in course | Confirmation message shown |

## 5. Instructor Module Test Cases
| TC ID | Feature | Steps | Expected Result |
|-------|---------|-------|-----------------|
| TC_IN_01 | Instructor Login | Login as instructor | Instructor dashboard displayed |
| TC_IN_02 | Create Course | Enter course details and save | Course successfully created |
| TC_IN_03 | Add Module | Add new module to course | Module saved |
| TC_IN_04 | Add Lesson | Add lesson to module | Lesson visible |
| TC_IN_05 | Publish Course | Publish created course | Course visible to learners |
| TC_IN_06 | Edit Course | Update course details | Changes saved successfully |
| TC_IN_07 | Delete Course | Attempt to delete course | System handles deletion properly |
| TC_IN_08 | View Enrolled Students | Open student list | List of enrolled students displayed |

## 6. Mobile Responsiveness Test Cases
| TC ID | Feature | Steps | Expected Result |
|-------|---------|-------|-----------------|
| TC_UI_01 | Layout | Open site on mobile device | UI elements properly aligned |
| TC_UI_02 | Button Interaction | Tap buttons | Buttons respond correctly |
| TC_UI_03 | Form Input | Enter data in forms | Keyboard functions correctly |
| TC_UI_04 | Orientation Change | Rotate device | UI adjusts correctly |
| TC_UI_05 | Scrolling | Scroll page | Smooth scrolling behavior |

## 7. Security Test Cases
| TC ID | Scenario | Steps | Expected Result |
|-------|----------|-------|-----------------|
| TC_SEC_01 | Unauthorized Dashboard Access | Open dashboard without login | Redirect to login page |
| TC_SEC_02 | Learner Accessing Instructor URL | Open instructor URL as learner | Access denied |
