## Welcome To ( সহজ সরল সিম্পল ) Assignment - 4 


---
# 📅 Deadline For 60 marks: 23th February, 2026 (11:59 pm ⏱️)
# 📅 Deadline For 50 marks: 24th February, 2026 (11:59 pm ⏱️)
# 📅 Deadline For 30 marks: Any time after 24th February.


# Main Requirements

## Design Part

## Dashboard
- Website name and Create a dashboard like figma 
- The section should be responsive for mobile devices. It is totally up to you. 

## Available Jobs Section
- A title on the left side, jobs count on the right side 
- 3 different tab  below the section title 
- Minimum 8 cards with:
	- companyName
	- position
	- location
	- type
	- salary
	- description
	- 2 buttons: Interview, Rejected
- By default all the jobs data will show on All tab, and the Interview, Rejected tab will show “No jobs Available” message with a subtitle below and an icon/image on the above

- The section should be responsive for mobile devices. It is totally up to you.

--- 

## Functionalities Part
- Clicking on Interview button on the card 
    - will add the data on Interview tab 
    - add the status as Interview.
    - Will increase the the count of interview in Dashboard 

- Clicking on Rejected button on the card 
    - will add the data on Rejected tab 
    - add the status as Rejected.
    - Will increase the the count of Rejected in Dashboard

- Enable toggle between Interview and rejected button(you can select Rejected button after clicking on Interview, and Interview button after clicking on Rejected button). It will change the tab and dashboard count also. It will show tab wise jobs count on the right.

---

# Challenges Requirements
- Clicking on the delete button will remove that card from the UI, and the count will be deducted from the dashboard card and the main section.
- No lorem ipsum text on your website. At least 8 meaningful commits in your project.  

- Create a readme file and answer this question on your own. Don’t copy-paste from Google or any AI chatbot. 


## Answers to Questions

### 1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
getElementById select one element using its different id.  
getElementsByClassName selects multiple element that share the same class name and returns a live HTML collection.  
querySelector select the first element that matche a CSS selector.  
querySelectorAll selects all matching element.

### 2. How do you create and insert a new element into the DOM?
we create document.createelement().then we can add content by using innertext or html nd then insert it into the DOM using appendchild an all method.

### 3. What is Event Bubbling? And how does it work?
Event bubbling is a process where an event starts from the target element and moves up to its parent elements.
For example, if we click a button inside a div, the click event first triggers on the button and then moves up to the div and then the body.

### 4. What is Event Delegation in JavaScript? Why is it useful?
Event delegation is a technique where we attach an event listener to a parent element instead of multiple child elements.
It works because of event bubbling.
It is useful because it improves performance and works even for dynamically added elements.

### 5. What is the difference between preventDefault() and stopPropagation() methods?
preventDefault() stops the default browser behavior (for example, stopping a form from submitting).
stopPropagation() stops the event from moving up to parent elements during bubbling.

---


**Technology Stack:**
- HTML
- CSS (Vanilla/Tailwind/DaisyUI)
- JavaScript (Vanilla)


--- 

## What to submit: 

1. GitHub Repository Link: 
2. Live Site Link: 
