# Eain_Su
This system helps apartment roommates manage their shared life by tracking bills, tasks, and utilities especially tailored for Myanmar lifestyle 


1.	Project Overview

This mobile app helps apartment roommates manage their shared life by tracking bills, tasks, and utilities
— especially tailored for Myanmar lifestyle (e.g., electricity status, bill shared, taks).
Team: Ye Min Aung (Frontend – Flutter or React Native), Nway Pwint Phyu (Backend - Ruby on Rails)


2.	Functional Requirements
Phase 1 – MVP:
-	Apartment Group Creation: Create apartment and invite others.
-	Member Management: Add/remove members.
-	Manual Electricity Status: Set/view electricity status.
-	Task Assignment: Assign duties like cleaning or trash.
-	Bill Tracking: Track bills (electricity, water, internet).


Phase 2 – Smart Features:
-	Task Rotation: Weekly auto-assign.
-	Notifications: Push alerts for tasks, bills.
-	Expense Splitting: Calculate who owes whom.
-	Voting System: Vote on group decisions.
-	Notice Board: Apartment-wide announcements.


Phase 3 – Bonus Features:
-	IoT Electricity Check: Auto status via device.
-	Language Support: English ↔ Myanmar.
-	Roommate Trust Score: Review users.
-	Premium Features: Monetization with extra tools.
-	

3.	Non-Functional Requirements
-	Platform: Mobile (Flutter or React Native)
-	Backend: Ruby on Rails (REST API)
-	Database: MySQL
-	Hosting: Fly.io or Render (Rails), Firebase (notifications)
-	Authentication: JWT
-	Performance: Real-time or near real-time updates


4.	Entity Relationship Overview

Entities and relationships:

Apartment 1---* Users Apartment 1---* Tasks Apartment 1--* Bills
Apartment 1---1 ElectricityStatus Users *---* Bills (paid_by)
Users *---* Tasks (assigned_to)



5.	Future Ideas / Improvements
-	Upload images of bills
-	Generate monthly PDF reports
-	Apartment chat feature
-	Guest member roles
-	Integration with Myanmar utility APIs (if available)


EainSu — Full Feature List
Core Features (MVP)
-	Create apartment group & manage members
-	Assign & track cleaning, trash, and other tasks
-	Track bills: electricity, water, internet, others
-	Manual toggle of electricity status (online/offline) with history
-	Expense splitting & payment tracking among members


Bonus Features
-	Push notifications & reminders for tasks and bills
-	Group chat or comment section on bills/tasks
-	Voting/poll system for apartment decisions
-	History logs for bills, tasks, electricity status changes
-	Upload images of bills or receipts
-	Generate monthly expense & task reports (PDF or in-app)
-	Role-based access control (admin, member, guest)
-	Language toggle: English / Myanmar
-	Emergency contact or help button
-	Integration with Myanmar payment platforms (KBZ Pay, Wave Money, etc.)


Future Smart Features
-	IoT integration for automatic electricity status
-	Roommate trust/reputation score
-	Premium features for monetization
