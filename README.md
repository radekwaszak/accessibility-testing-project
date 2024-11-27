# Accessibility Testing Project for Recipe Dashboard  

This repository contains the documentation and results of an **Accessibility Testing Project** for the [Recipe Dashboard](https://broken-workshop.dequelabs.com/) website. The testing was conducted to evaluate the website's compliance with **WCAG 2.1 AA standards** and identify areas for improvement to enhance accessibility for all users.  

---

## Project Overview  

**Website Under Test**:  

[Recipe Dashboard](https://broken-workshop.dequelabs.com/)  

**Scope of Testing**:  

The project focuses on identifying accessibility issues through **manual testing** across key accessibility principles such as keyboard navigation, color contrast, ARIA roles, and screen reader compatibility.  

**Standards Followed**:  

- WCAG 2.1 AA  
- Accessibility best practices  

---

## Tests Conducted  

The following manual tests were conducted as part of the project:  

1. **Keyboard Navigation**  
2. **Color Contrast**  
3. **ARIA Roles and Landmarks**  
4. **Image Alt Text**  
5. **Forms and Input Labels**  
6. **Links and Buttons**  
7. **Screen Reader Compatibility**  
8. **Heading Structure**  

---

## Test Results  

| **Test Case**               | **Status**  | **Notes**                                                                 |  
|-----------------------------|-------------|---------------------------------------------------------------------------|  
| **Keyboard Navigation**      | FAILED      | Edit button not accessible with Enter/Space keys.                         |  
| **Color Contrast**           | FAILED      | Insufficient contrast for "Beginner" difficulty text. Contrast: 2.17.     |  
| **ARIA Roles and Landmarks** | FAILED      | Incorrect roles for some elements; dialog lacks ARIA attributes.            |  
| **Image Alt Text**           | FAILED      | Several images lack `alt` attributes.                                     |  
| **Forms and Input Labels**   | PASSED      | No issues found.                                                          |  
| **Links and Buttons**        | PASSED      | No issues found.                                                          |  
| **Screen Reader Compatibility** | FAILED  | No elements are announced by the screen reader.                           |  
| **Heading Structure**        | PASSED      | Logical and hierarchical heading structure observed.                      |  

---

## Repository Contents  

This repository includes the following files:  

- **Requirements Document**: Accessibility requirements for the Recipe Dashboard website (`1.requirements.md`).  
- **Test Plan**: A detailed test plan outlining the testing strategy and scope (`2.test-plan.md`). 
- **Test Cases Document**: A detailed list of test cases (`3.test-cases.md`)
- **Defect Reports**: Individual defect reports documenting the identified accessibility issues (`4.defect-reports.md`).  
- **Final Report**: A summary of findings, test results, and recommendations (`5.final-report.md`).  

---

## How to Use  

1. Clone this repository to your local machine:  
  
   ```
   git clone https://github.com/radekwaszak/accessibility-testing-project
   ```

2. Review the documentation files to understand the testing process and findings:

- `1.requirements.md` for the website's accessibility goals.
- `2.test-plan.md` for the overall strategy.
- `3.test-cases.md` for instructions on how to perform tests.
- `4.defect-reports.md` for detailed descriptions of each issue.
- `5.final-report.md` for a summary of the test results.

## Key Findings and Recommendations

The testing reveals critical accessibility issues that need to be addressed, including:

- Keyboard Accessibility: Fix buttons and ensure all interactive elements are operable using a keyboard.
- Color Contrast: Adjust the color scheme to meet WCAG contrast standards.
- ARIA Roles: Add appropriate ARIA roles and attributes for custom components.
- Alt Text for Images: Ensure all images have descriptive alt text.
- Screen Reader Compatibility: Fix compatibility issues to make the page readable by assistive technologies.

## Contact

If you have any questions or feedback regarding this project, feel free to reach out:

Email: [radoslawwaszak98@gmail.com]

GitHub: radekwaszak
