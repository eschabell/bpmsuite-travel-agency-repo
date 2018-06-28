Update: June 2018 moved to [Gitlab](https://gitlab.com/eschabell/bpmsuite-travel-agency-repo).


JBoss BPM Suite Travel Agency Demo
==================================

Install the application into JBoss BPM Suite
--------------------------------------------

Note: JBoss BPM Suite (can be downloaded from https://access.redhat.com/) is already installed.

Before starting the installation add the loanOfficer role to the user which is used to login in Business Central.

1. Login to Business Central (ex. http://localhost:8080/business-central)
2. From the main meniu select `Authoring -> Administration`
3. From the secondary menu select `Repositories -> Clone repository`
4. Fill the Clone Repository form:
  - Repository Name - the name of the repository (created inside JBoss BPM Suite)
  - Organizational Unit - select a value from list
  - Git URL - https://github.com/jbossdemocentral/bpmsuite-travel-agency-repo.git 
  - Leave User Name and Password fields empty

Run the application
-------------------

1. From the main menu select `Authoring -> Project Authoring`
2. In `Project Explorer` select the `Organizational Unit` and then the `Repository` you created
3. From the secondary menu select `Tools -> Project Editor`
4. Push the `Build & Deploy` button (top-right corner) in order to build the application
5. From the main menu select `Process Management -> Process Definitions`
6. Start the rewards process
