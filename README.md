# Loan Management System

It’s   a system for a small  group. Every group  has a group leader and a group leader must have a unique identification number which associate him/her with his/her group. 
The groups are categorized in four categories as follows
1. Group of men only 
2. Group of women only
3. Group of both men and women
4. Group of youth only

The system should be able to say this group has a total of 50 members where by 26 are men and 24 are women this should apply to group of both men and women and groups of youth but for group of men only it should just display total saying total member of group is let say 29 the same to group of women only. The group should have initial capital, it can be money or it can be plantation or it can be livestock like hen or cow or goat.
The system should display: 
1. Registration date of the group and date the group was established.
2. Total numbers of members registered in the system.
3. Total number of female members in the system and total number of male members in the system.
4. Statistics by location.
5. If the group is active or inactive.
6. If the group has loan or has no loan, and if it has loan what is the status of it’s payment.

# Location of the group

The system should say this group is in certain region, then certain district, then division and up to village level, this should be a dependent select box, if you choose a region then the district should be displayed and so on, I have already created a database of this region to village level dependent select it’s just to implement it.
Every group should have a registration number of this format HW/ITL/MJ/CBO/72 the last part of the registration number will vary but the other part are constant, during group registration the system should fail to register if the registration number is already registered, the system should reply by custom message with red colour saying that number is already registered .
Each group must have at least one activity, sample activity are livestock keeping, agriculture, cultivation, farming there are many activities but these are just sample.

# The Loan Part

Admin should assign loan to the group which needs loan and the loan should come from the following part
1. Ministry
2. Government
3. Donors
4. District council
The amount of loan should be given to the group which needs that loan
The date in which the loan was assigned
The due date for the loan to be fully paid
 The interest is 10% of the original amount of the loan
The loan is coming from which parts

# On payment of the loan.

The loan must be paid in ten months or twelve months
The system should display original loan
The system should display the remaining amount
The system should display the due date for the loan
The system should calculate repayment schedules and shows the amount which must be paid by the group each month until the loan is finished.
Admin should enter returned amount and feed it to the specific group and debt should decrement.
Admin should be able to print statement showing repayment of any group he/she want to see
Admin should be able to generates reports also the reports should display the current date of report generation..
Admin should be able to generate exports
Also implement nice pagination like in your online quiz project.
Also please implement search, example admin might need to search for a certain group, he/she might search using group registration number or search by or search by group leader location and then do CRUD operation or print group details.
