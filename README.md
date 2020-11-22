# Workday-organizer
A calendar to help manage your daily tasks.

## The Project

Every employee needs a way to manage their tasks throughout the day. This is a very simple app to help the user organize the day ahead. The user simply inputs the task they have at a specific hour and presses "save". The task will remain, even if the page is reloaded.

## The Organizer Page

<div align="center">
    <img src="Assets\images\Screenshot1.png" alt="Organizer Screenshot">
    <p>-----------------------------------------------------------------------</p>
    <img src="Assets\images\Screenshot2.png" alt="Organizer Screenshot 2">
</div>

<a href="https://treyjewett.github.io/Workday-organizer/" target="_blank">Click here to view the Organizer!</a>

## Code Utilized

This project was constructed using BootStrap, jQuery, Moment.js, and CSS. All of the code was able to fit neatly within the HTML and CSS pages.

## What to Expect

When the Organizer is loaded:
- The user will see the title "Work Day Scheduler" as well as a short introduction sentence.
- The current date will be displayed under the title.
- Below the blue divider, blocks divided buy business hours in the day are displayed with placeholder text letting the user know where to input their tasks.
- After the user inputs the task needed for the day, they can click the blue save button and the event will remain even if the page is reloaded.
- If the user types over an existing event, the old event is replaced with the new one.
- The hour block change color depending on what time of day it is.
- If the time has passed that of the hour block, the expired block will be grayed out to signify the event has expired.
- The current hour is hilighted and attenting-grabbing so the user can find what time it is faster.
- Future time slots are colored green to show they are still available.

## Lessons Learned

This was the first project where we needed to pull a 3rd party API in for the page to interact with. It was interesting going though a different application's info sheet to figure out how to implemment it into my code. Local storage was different in this application than in previous. It was a good challenge to be able to save events trough refreshes and be able to over-write existing stored objects.