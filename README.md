# NPM Near Personnell Management System
USAGE:
1-clone this repository git clone https://github.com/yusufcnr/npm.git
cd into the directory cd npm
2-install near-sdk-as npm install --dev near-sdk-as
3-start new project using framework npx asinit .

https://www.npmjs.com/package/near-sdk-as?activeTab=readme

This repo is for the project which needs to be submitted after completion of the Near Developer Cours on Patika.dev. 
We will be making a dapp on Near Blockchain which has following feature.

There will be some workers and their level will be different. 
They will have some parameters based on their level.
Basically there are 2 factor impacting the salary of a worker:
Title  and Experience. 
titles will be scored between 1-5 (worker, technician, engineer, sr. engineer, manager) and experience will be (number_of_year_worked / 3). basically you get 1 level higher in terms of experience.

At the end of the week (friday at 5:30 pm) all rewards will be distributed. 

There should be some company wallet. 
everyone should connect 

save a worker, give hime a title, set start date/time. 

manager can give some bonus. 


#Basic Diary Website:
Everyone can log in with his wallet and werite something. 
They can get paid based on how long they write or score they get from others. 
everyone has right to vote for asseys,


Add custom worker type using a function. 
enum Titles {
  Worker,
  Technician,
  Engineer,
  SrEngineer,
  Manager
  
}
function getTitle = Titles.Worker+1 //initial value is 0 so we need some value for it.


sign up for your company.
and add worker.
worker would have some title, experinece, startDate, isRetired
