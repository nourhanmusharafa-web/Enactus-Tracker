# Enactus-Tracker
Web app for tracking Enactus Team members’ progress. Record Sunday session checklists and notes, view monthly progress, and generate feedback reports. Built with HTML/JavaScript and Supabase.


## Features

### Members
- [ ] Add, rename and delete members
- [ ] Store each member's email for sending feedback
- [ ] Sidebar showing each member's latest monthly score
- [ ] "Next member" button to move through the team quickly

### Sunday sessions
- [ ] Previous/next Sunday buttons and a date picker that snaps to the Sunday before
- [ ] Checklist with a tick and a note for every criterion
- [ ] General note for the whole session
- [ ] "Absent this session" toggle (left out of the percentages)
- [ ] Clear a session

### Criteria
- **Class A (Delivery):** tonality, recall, pace, body language, eye contact, written and spoken English, presenting under pressure and improvising
- **Class B (Character):** discipline, receptiveness to feedback, kindness and respect toward other members
- [ ] Editable: rename, add and remove criteria and groups

### Progress
- [ ] Monthly progress for each member
- [ ] Overall score by month, with a trend
- [ ] Each criterion by month
- [ ] Timeline of all notes

### Feedback reports
- [ ] Report for a chosen month or the whole season
- [ ] Strengths and focus areas
- [ ] All notes listed by date
- [ ] Closing note from the coach
- [ ] Download, copy as text, or email a report
- [ ] Download reports for all members at once

### Data and access
- [ ] Login, so only authorised users can view and edit data
- [ ] Data stored in a Supabase (PostgreSQL) database
- [ ] Works on any device through its own link
- [ ] Export all data

## Tech stack
- HTML, CSS and JavaScript
- Supabase (database and authentication)

- Extra Page
- ## English progress tracker (Language)

Same Sunday-session idea as the Presentation Team tracker, for English students.

### Students
- [ ] Add, rename and remove students, with an email for sending reports
- [ ] Sidebar showing each student's latest monthly score
- [ ] "Next student" button

### Sunday sessions
- [ ] Previous/next Sunday buttons and a date picker that snaps to the Sunday before
- [ ] Skills checklist with a tick and a note for each skill
- [ ] General note for the session (optional)
- [ ] "Absent this session" toggle (left out of the percentages)
- [ ] Clear a session

### Skills checklist
- [ ] Default skills: pronunciation, grammar accuracy, vocabulary range, fluency and confidence, listening comprehension, homework completed
- [ ] Editable: add, rename and remove skills

### Progress
- [ ] Summary tiles: sessions attended and missed, attendance %, latest month's score
- [ ] Line chart of the overall score by month
- [ ] Each skill by month, with a colour-shaded table and ▲ ▼ trend arrows
- [ ] Notes timeline

### Progress reports
- [ ] Report for any date range, this month, or the whole period
- [ ] Strengths (80% or more), most improved, and focus areas (50% or less)
- [ ] Month-by-month table and all notes
- [ ] Closing note from the teacher at the bottom
- [ ] Email, copy as text, or download a report
- [ ] Download reports for all students at once
