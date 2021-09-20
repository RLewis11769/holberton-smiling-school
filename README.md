# Holberton Smiling School

## Description

This project implements a design from scratch using HTML and Bootstrap as much as possible. Additional customized styling is added using pure CSS. This project duplicates the visual design of a fully functional website consisting of 3 pages that can be seen as 3 separate Figma designer files.

The Homepage is found [here](https://www.figma.com/file/QYQqMYbdpAHL5xTclwJKSI/Homepage?node-id=0%3A1).

The Pricing page is found [here](https://www.figma.com/file/KLAI53jdYpfFNEy0O79ymB/Pricing?node-id=0%3A1).

The Courses page is found [here](https://www.figma.com/file/ivg3abH1HLmMayBgjGg1Qf/Courses?node-id=0%3A1).

Each page contains links to the other two pages via a working navigation bar.

## Examples

Full desktop and mobile examples for all 3 pages are shown here:

![Final result](https://github.com/RLewis11769/holberton-smiling-school/blob/main/usage/Overview.jpg)

A detailed look at the header, as seen on the homepage, is shown here:

![Final result](https://github.com/RLewis11769/holberton-smiling-school/blob/main/usage/Header.gif)

A detailed look at the interactive form on the courses page, including the dropdown menu, is shown here:

![Final result](https://github.com/RLewis11769/holberton-smiling-school/blob/main/usage/CoursesForm.gif)

## Installation

### 1. Install
Clone the repository into your system with the command:

```
git@github.com:RLewis11769/holberton-smiling-school.git
```

### 2. Open
Install "Live Server" or another server preview extension, run it, and navigate to the open port.

### 3. View
Holberton SmilingSchool is now ready to view. See below for details.

## Structure

### CSS

#### Custom Styling
- All pages use the same CSS file that contains as little CSS as possible
    - File:
        - styles.css

### Homepage

#### 0. Create the header/hero
- Navigation menu with hamburger icon and banner including "awards" section
	- File:
		- 0-homepage.html

#### 1. Create the "carousel of quotes" section
- Simple single-item carousel with horizontal card
	- File:
		- 1-homepage.html

#### 2. Create the "most popular tutorials" section
- Multi-item carousel with different number of cards based on size
	- File:
		- 2-homepage.html

#### 3. Create the "free membership" section
- Similar to "awards" section in header/hero but with different number of columns on tablet and mobile
	- File:
		- 3-homepage.html

#### 4. Create the "latest videos" section
- Copy and modify existing "most popular tutorials" section
	- File:
		- 4-homepage.html

#### 5. Create footer
- Complete the homepage page
	- File:
		- homepage.html

### Pricing

#### 6. Create the header/hero
- Copy and modify navigation menu with hamburger icon and banner from homepage, not including "awards" section
	- File:
		- 0-pricing.html

#### 7. Create "prices grid" section
- 3 columns regardless of row width
	- File:
		- 1-pricing.html

#### 8. Create "carousel of quotes" section
- Copy "carousel of quotes" from homepage
	- File:
		- 2-pricing.html

#### 9. Create "FAQ grid" section
- Similar to "awards section" in header/hero with simple cards
	- File:
		- 3-pricing.html

#### 10. Create footer
- Complete the pricing page
	- File:
		- pricing.html

### Courses

#### 11. Create the header/hero
- Copy and modify navigation menu with hamburger icon and banner from homepage, not including "awards" section
	- File:
		- 0-courses.html

#### 12. Create "search filters" section
- Simple dropdown as stand-in for filters
    - No need for dynamic values - only static content
	- File:
		- 1-courses.html

#### 13. Create "result" section
- Grid that works no matter the number of cards
    - Test with odd and even number of cards
	- File:
		- 2-courses.html

#### 14. Create footer
- Complete the courses page
	- File:
		- courses.html

## Project Rules

- You won’t have a lot of instruction, so you are free to implement it the way that you want. The objective is simple: Create a fully functional web page that looks the same as the designer file.
- Your styles.css must be as small as you can. You must use Bootstrap classes as much as you can.

## Project Advice

- You will need: JQuery, Bootstrap CSS/JSS (links/scripts provided)
- If your computer has missing fonts, you can find it here: [source-sans-pro](https://www.fontsquirrel.com/fonts/source-sans-pro)
- Images and holberton_school-icon font are included in zip found [here](https://intranet.hbtn.io/projects/1687)

## Features

- Pricing and courses pages include link back to homepage.
- An attempt was made at accessability. No Axe issues except "Elements must have sufficient color contrast" which is a design element I have no control over.
- I personally think it's very cleanly written and laid out :)

## Bugs

- These pages ideally look best at 1440px, 768px, and 375px as shown in the Figma designer file.
- Text size is not responsive.
- The background of headers does not match for homepage or pricing pages on mobile view.
- "Most popular tutorials" and "Latest tutorials" carousels are not multi-item carousels. They are single-item carousels with 2 cards each.
- Styling on "Most popular tutorials" and "Latest tutorials" carousels is a little off, most notably the "play" overlay and previous/next arrows.

## Credit

This webpage was designed by Nicolas Philippot, UI/UX designer. This HTML/Bootstrap replica was implemented by Rachel Lewis.
