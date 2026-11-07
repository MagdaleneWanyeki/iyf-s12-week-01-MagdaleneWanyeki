# Task 2.3: Accessibility Audit Report

**Project:** My First Website  
**File Audited:** index.html  
**Tools Used:** Chrome Lighthouse and WAVE Web Accessibility Tool

## 1. Introduction

The purpose of this accessibility audit was to check whether my webpage is accessible and easy to use for different people, including people with disabilities.

I used Chrome Lighthouse and the WAVE accessibility tool to identify possible accessibility problems and improve my webpage.

## 2. Issues Found

During the accessibility review, I checked the following areas:

### Images
- The image needed alternative text.
- I added an `alt` attribute to describe the image.

### Headings
- I checked the heading structure.
- I organized the headings using a proper hierarchy, starting with `<h1>` followed by `<h2>`.

### Links
- I checked whether the links had meaningful descriptions.
- I replaced unclear link text with descriptive text such as "YouTube to watch videos and learn new things".

### Language
- I checked the HTML language declaration.
- I added `lang="en"` to the opening HTML tag.

### Form Labels
- I checked whether form inputs had associated labels.
- The index.html page does not contain form input fields, so this check was not applicable.

## 3. How I Fixed the Issues

| Issue | Solution |
|---|---|
| Missing image description | Added descriptive alt text. |
| Heading structure | Organized headings using h1 and h2. |
| Unclear link text | Added descriptive link text. |
| Missing language attribute | Added lang="en". |
| Form labels | Confirmed there are no form inputs on this page. |

## 4. Accessibility Testing Tools

### Chrome Lighthouse
I used Chrome Developer Tools to run an accessibility audit.

Steps followed:
1. Opened my website using Live Server.
2. Pressed F12 to open Developer Tools.
3. Selected the Lighthouse tab.
4. Selected the Accessibility category.
5. Clicked Analyze page load.
6. Checked the accessibility score and recommendations.

**Final Lighthouse Accessibility Score: [Enter your actual score]/100**

### WAVE Accessibility Tool

I used the WAVE Web Accessibility Evaluation Tool to check my webpage for accessibility errors and warnings.

Website: https://wave.webaim.org/

I checked the page for:
- Missing alternative text.
- Empty or unclear links.
- Heading structure problems.
- Form label issues.
- Other accessibility warnings.

## 5. Conclusion

This activity helped me understand the importance of web accessibility.

I learned how to add alternative text to images, organize headings correctly, create descriptive links and specify the language of a webpage.

I also learned how to use Lighthouse and WAVE to identify accessibility problems.

After making the improvements, my webpage has a better accessibility structure and is easier for different users to understand and navigate.

**Tools used:**
- Google Chrome Lighthouse
- WAVE Accessibility Tool
- Visual Studio Code

