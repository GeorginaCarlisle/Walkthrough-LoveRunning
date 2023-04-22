![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

# Walkthrough - Love Running

This walkthrough project was completed as part of my Diploma in Full Stack Software Development with [Code Institute](https://codeinstitute.net/full-stack-software-development-diploma/). The focus of the walkthrough was to put into practice **HTML** and **CSS**.

Note: There is no live webpage of this project

***

## Description of the 'Love Running' page
This site gives details of the 'Love running club' for runners in Dublin, Ireland.

It has an eye-catching design, that includes: a hero image that appears to zoom in on the page loading and a gallery in order to attraction users.

The site is easy to navigate with clear and concise information. Potential runners are quickly introduced to reasons for joining the club, where and when the club meets and can fill in a form to sign-up.

Throughout the site maintains balance and consistency. This is maintianed through media queries to ensure a change in screensize does not impact user experience.

## Languages
- HTML
- CSS
- Markdown

## Tools and technologies
- Git hub
- Git
- VScode with the following extensions:
    - Markdown Preview Enhanced
    - Markdown Preview Github Styling
    - Live Server
- Font awesome

## Challenges

The following challenges were set/came up during the walkthrough. Each solution was completed independently and is my code, unless otherwise stated.

| Problem | Challenge | Solution |
| --- | --- | --- |
| Nav list items appear in reverse order in the header after float right applied. | Without changing the list order, items to be ordered correctly while still maintaing a float right position. | Remove float:right and instead menu text-align:right and menu li display:inline-block. Credit to Stackoverflow question [Float:right reverses order of spans](https://stackoverflow.com/questions/4224476/floatright-reverses-order-of-spans).|
| Following walkthrough responsive changes to the menu won't work as my menu is styled differently. | At screens less that 950px nav list items to be positioned under the love running logo. | Within the media query style #menu clear:left (to stop the browser bringing the list items up) and text-align:right (to create a better balance). |

## Credits

Credit for the vast majority of both the code and content of this project is given to [Code Institue](https://codeinstitute.net). Instruction was provided in the form of videos which I then implemented using the tools listed above.

There were however a number of challenges presented during the walkthrough where I was tasked with discovering how to code or style an element. In these instances the credit goes to myself unless otherwise stated in the challenge section above.

This README was completed independently with the following credits:

- CI logo by Code Institute.
- https://www.markdownguide.org was highly useful in learning basic markdown syntaxs.
