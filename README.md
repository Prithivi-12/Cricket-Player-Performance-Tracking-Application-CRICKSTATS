CRICKSTATS - Cricket Player Performance Tracking Application
CRICKSTATS is a Salesforce-based app for coaches, managers, and analysts to track cricket players' match-by-match performance, with automatic stats calculation and dashboards.
​

Features
 Custom objects for Players and Match Performances with fields like runs, wickets, catches, and team details.
​

 Master-Detail relationships linking performances to players for data integrity.
​

 Roll-up summaries auto-calculating totals (runs, wickets, 50s, 100s, averages).
​

 Interactive screen flow to filter players by team and view stats in a data table.
​

 Lightning App with tabs, reports, and dashboards for real-time analytics.
​

Tech Stack
 Backend: Salesforce custom objects, relationships, roll-up summaries, formula fields.
​

 Automation: Salesforce Flows.
​

 Frontend: Salesforce Lightning UI, tabs, and dashboards.
​

 Database: Salesforce Cloud.
​

Prerequisites
 Free Salesforce Developer account (sign up at developer.salesforce.com/signup).
​

 System Administrator profile access.
​

 Basic familiarity with Salesforce Setup (Object Manager, Flows).
​

Quick Setup
 Create a Salesforce Developer org as described in the documentation.
​

 Follow milestones: Create Player and Match Performance objects with specified fields and relationships.
​

 Add tabs, build the CRICKSTATS Lightning App, and configure roll-up summaries.
​

 Implement the Player Flow for team-based player stats viewing.
​

 Test by adding sample player data and match performances—stats update automatically.
​

 Detailed steps with screenshots are in Cricket-Player-Performance-Tracking-Application.pdf.
​

Usage
 Log into your Salesforce org and launch the CRICKSTATS App.
​

 Add players via Players tab (name, team, role, etc.).
​

 Record match stats in Match Performances tab (select player, enter runs/wickets).
​

 View auto-updated totals and averages on player records.
​

 Use Home page flow: Select team to see player stats table.
​

 Generate reports/dashboards for top scorers, team performance.
​

Testing
 Enter test data for 5-10 players and matches to verify roll-ups, flow, and reports work correctly.
​

Team
 PRITHIVIRAJ L: Developer account, fields, flows, documentation.
​

 ABISHEK D: Objects, layouts, validation.
​

 RAJA I: Tabs, navigation.
​

 HARIKARAN E: App, UI, automation.
​

 Institution: E.S ARTS AND SCIENCE CO-ED COLLEGE.
​

Future Enhancements
 Mobile integration, AI predictions, multi-league support.
​

License
 MIT License - feel free to fork, modify, and deploy to your Salesforce org.
​

For support: prithiviraj350@gmail.com.
​
