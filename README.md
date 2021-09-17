# Holberton Smiling School

## Description

This project implements a design from scratch using HTML and Bootstrap as much as possible. Additional personalized styling is added using pure CSS. This project duplicates the visual design of a fully functional website consisting of 3 pages that can be seen as 3 separate Figma designer files.

The Homepage is found [here](https://www.figma.com/file/QYQqMYbdpAHL5xTclwJKSI/Homepage?node-id=0%3A1).

The Pricing page is found [here](https://www.figma.com/file/KLAI53jdYpfFNEy0O79ymB/Pricing?node-id=0%3A1).

The Courses page is found [here](https://www.figma.com/file/ivg3abH1HLmMayBgjGg1Qf/Courses?node-id=0%3A1).

Each page contains links to the other two pages via a working navigation bar.

## Examples

Full desktop, tablet, and mobile examples for all 3 pages are shown here:

![Final result](https://github.com/RLewis11769/holberton-smiling-school/blob/main/usage/Overview.jpg)

The design of most sections is visible in the images previusly provided. However, a detailed look at the interactive dropdown menu on the Courses is shown here:

![Final result](https://github.com/RLewis11769/holberton-smiling-school/blob/main/usage/CoursesDropdown.jpg)

## Installation

### 1. Install
Clone the repository into your system with the command:

```
git@github.com:RLewis11769/holberton-headphones.git
```

### 2. Open
Install "Live Server" or another server preview extension, run it, and navigate to the open port.

### 3. View
Holberton SmilingSchool is now ready to view. See below for details.

## Structure

### CSS

#### Styling Unavailable via Bootstrap
- All pages use the same CSS file that contains as little CSS as possible
    - File:
        - styles.css

### Homepage

#### 0. Create the header/hero
- Navigation menu with hamburger icon and banner including "awards" section
	- Files:
		- 0-homepage.html

#### 1. Create the "carousel of quotes" section
- Simple single-item carousel with horizontal card
	- Files:
		- 1-homepage.html

#### 2. Create the "most popular tutorials" section
- Multi-item carousel with different number of cards based on size
	- Files:
		- 2-homepage.html

#### 3. Create the "free membership" section
- Similar to "awards" section in header/hero but with different number of columns on tablet and mobile
	- Files:
		- 3-homepage.html

#### 4. Create the "latest videos" section
- Copy and modify existing "most popular tutorials" section
	- Files:
		- 4-homepage.html

#### 5. Create footer
- Complete the homepage page
	- Files:
		- homepage.html

### Pricing

#### 0. Create the header/hero
- Copy and modify navigation menu with hamburger icon and banner from homepage, not including "awards" section
	- Files:
		- 0-pricing.html

#### 1. Create "prices grid" section
- 3 columns regardless of row width
	- Files:
		- 1-pricing.html

#### 2. Create "carousel of quotes" section
- Copy "carousel of quotes" from homepage
	- Files:
		- 2-pricing.html

#### 3. Create "FAQ grid" section
- Similar to "awards section" in header/hero with simple cards
	- Files:
		- 3-pricing.html

#### 4. Create footer
- Complete the pricing page
	- Files:
		- pricing.html

### Courses

#### 0. Create the header/hero
- Copy and modify navigation menu with hamburger icon and banner from homepage, not including "awards" section
	- Files:
		- 0-courses.html

#### 1. Create "search filters" section
- Simple dropdown as stand-in for filters
    - No need for dynamic values - only static content
	- Files:
		- 1-courses.html

#### 2. Create "result" section
- Grid that works no matter the number of cards
    - Test with odd and even number of cards
	- Files:
		- 2-courses.html

#### Create footer
- Complete the courses page
	- Files:
		- courses.html

## Project Rules

- You won’t have a lot of instruction, so you are free to implement it the way that you want. The objective is simple: Create a fully functional web page that looks the same as the designer file.
- Your styles.css must be as small as you can. You must use Bootstrap classes as much as you can

## Project Advice

- You will need: JQuery, Bootstrap CSS/JSS (links/scripts provided)
- If your computer has missing fonts, you can find them here: [source-sans-pro](https://www.fontsquirrel.com/fonts/source-sans-pro) and [Spin-Cycle-OT](https://www.fontsquirrel.com/fonts/Spin-Cycle-OT)

## Features

- 
- An attempt was made at accessability. No Axe issues except "Elements must have sufficient color contrast" which is a design element I have no control over.
- I personally think it's very cleanly written and laid out :)

## Bugs

- 

## Credit

This webpage was designed by Nicolas Philippot, UI/UX designer. This HTML/Bootstrap replica was implemented by Rachel Lewis.
