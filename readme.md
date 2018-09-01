# Coder Academy Website Internship Project

## Intern:

Ali Asgari

aamining@gmail.com

Actual preparation duration: 5 days

Actual code development: 15 days

Technology: Ruby, Ruby on Rails, JavaScript, jQuery

## Main Project Object:

Major problem identified when the website administrators extract the number of
attendees,

considering the dates, courses and venues.

There is confusion in server side (admin –side) when obtaining information.

Solution plan: Develop a simple page to show and obtain accurate data in a
glance.

Code Process and Achievements:

```
1- Developed a seeds file for database to meet the following Course, Intake,
 Booking and Attendees combinations:
Course available – No Intakes – No Booking
Course available, Intake available – No Booking
Course available, Intake available – One Booking
Course available, Intake available – Two and more booking for one course and
same intake.


2- Developed a new page to extract and show accurate data from all mentioned
combinations. The new page is developed as figure 1, including three main data
tables from top:
Review Booking
Intake Booking Review Courses / Intakes

The logic behind these tables is to provide a quick view of movement and changes
, considering all Objects as Courses, Intakes, Booking and Attendees.
```

New Page (Review) Features:

```
1- Access to new page as the REVIEW page from old admin menu.
Just one orange reset filter button.

2- Two new groups of filters, providing filtering by range of dates and title
specifications. Based on the date range filters do not need more to dashboard
page.

3- Links to old detail pages related to new three tables.
e.g. The small blue buttons in the Booking review table you can find the booking
details or delete a booking.

4- In the Intake Booking Review table, the blue small button is linked to the
old intake page. This is just one button when an intake had been allocated to a
course. Two more buttons will appear as the Edit and Delete if there is not any
intake for course.
Also the green ticked signs are referring to course with intake(s) which had
been booked. And the red sign is referred to course with intake(s) but have no
bookings yet.

5- This blue pencil button links to the old Course page to edit or create a new
course. Also the admin can delete a course by pressing the blue bin button.

6- At the bottom of the new Review page, the admin can find the total number of
attendees in a selected (filtered) range.

7- Shows all 3 tables for Bookings, Intakes, and Course in one whole page.

```


<img width=100% heigh=100% alt="new page" src="https://github.com/aamining/coder-academy-website-readme/blob/master/Coder%20Academy1.jpg">
