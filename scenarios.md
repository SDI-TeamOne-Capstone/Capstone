Overview - Rex (Sharon to share screen with current spreadsheet - initially show the login page for the app, then on *queue switch to the spreadsheet)

The 225 ADS is a 24/7 WA ANG unit that serves as the command and control authority for the active air-defense of the western US. They have an operations floor that runs a panama schedule over a 2 week cycle (12 hour shifts that repeat on a 2-3-2 cadence) and must also include transitions between day/night cycles.  Each full crew has a minimum number of positions that must be filled and those positions require unique qualifications for the individual sitting in that position.

*Currently a spreadsheet is used to track the crew schedule. It is a heavily manual process and anytime there is a change/conflict, there are ripple effects that must also be manually accounted for. Even the 2 week panama cadence must be manually created for each cycle.

The spreadsheet lives on an outdated version of Sharepoint and can only be modified by one user at a time, and then must be checked back in before anyone else can edit or view the changes. Only those with read/write access to the schedule can make changes, so providing inputs relies on email, phone calls, texts, etc, poviding little accountabilty for positive confirmation of changes.

This MVP addresses some of the major pain points uncovered during the interviews with the crew schedulers, as well as inputs from those on the team that have lived the panama schedule as part of the 225 ADG.

The scenario is presented from the different personas that are involved with creating and using the ops schedule.  The main focus was on the schedulers, who are responsible for making sure there is a 2 month schedule in place for each of the sections that make up the crew.  Other personas are the flight supervisors and individual crew members that have unique requirements that can be accomplished by the scheduler, but should be delegated accordingly.

1. Section Scheduler’s Viewpoint:

It is the first day of the 56-day crew schedule cycle, and the Crew Scheduler autogenerated the scheduler. The C2 Section Scheduler, Lt. Nico DiAngelo, reviews the schedule to ensure that there are no conflicts.
- Things to demonstrate
  1. Brandon (Scheduler) - Login as scheduler (*name user2 password)✔️  *Brandon
  2. Brandon - generation of panama schedule to autofill the crews (*trigger push the "easy" build schedule button)✔️ 
  3. Sharon - creation of a conflict that impacts the autogenerated schedule (*This will be the first person on the schedule )✔️  user3 password *Sharon
  4. Sharon - notification alert of a conflict (should also send to the impacted crew member) (*manually go to notifications)✔️ 
  5. Brandon - re-run the autogeneration to remove the conflict (*trigger push the "easy" build schedule button)✔️ 
  6. notification to newly added crew member that they will fill the new schedule (NOT WORKING YET - IN FUTURE RELEASE)



2. Individual Crew Member’s Viewpoint:
- Things to demonstrate
  1. Dameon - Login as Crew member (*need user4 password)✔️  Dameon show that USERS is not available in header
  2. Dameon - view their individual schedule for the 14-day period (*need to sort on name - Dameon)
  3. Dameon - create a conflict (manually enter the conflict) for the first TT 
  4. Dameon - show any conflicts they have already added (*stretch to show current conflicts for the user - Sharon)✔️  
  5. Brandon - show the notification of the conflict and reschedule as user2



3. Crew/Section Lead Viewpoint:
- Things to demonstrate:
  1. Rex - Login as Supervisor (*name/login for supervisor password )✔️ Rex user3 password
  2. Rex - Add/update a user (*add a new user into training - that will not solve the crew schedule, then update an existing crew in training to valid qual to resolve schedule conflict) -(NEED - 2 names/quals that need to be used for the scenario)
  3. View the entire day's schedule for the section(s) (*stretch for a filter to allow this - Dameon)
  4. *See the quals/certs of the crew members to understand the capability of the crew to manage Crew Resource Management (Dameon)
  
NOT COVERED IN THESE SCENARIOS?
- 
  

