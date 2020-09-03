# PHP-BookStore
The system deals with a small group.
Every group has a group leader and a group leader must have a unique identification number which associates the individual leader with their group. 
The groups are categorized in four categories: 
1)Men only group.
2)Women only group
3)A group comprising both men and women
4)Group of youth
The system should be able to state that a following group has a total of 50 members where by 26 are men and 24 are women this should apply to group of both men and women and groups of youth but for group of men only it should simply display total number of members, the same to group of women only.
The group should have initial capital, it can be money or it can be plantation or it can be livestock like hen or cow or goat. The system should display registration date of the group and date the group was established.
Furthermore, the system should display the total numbers of members registered in the system. The system should display total number of female members in the system and total number of men member in the system. The system should also display statistics by location for instance it should say this village has five groups, and total member in that five groups is 345 where by men are 200 and women are 145. 
It should display the numbers of groups registered in the system and if the group is active or inactive. Moreover, if the group has loan or has no loan, and if it has loan what is the status of its payment.

Location of the group
The system should say this group is in certain region, then certain district, then division and up to village level, this should be a dependent select box, if you choose a region then the district should be displayed and so on, I have already created a database of this region to village level dependent select it’s just to implement it.
Every group should have a registration number of this format HW/ITL/MJ/CBO/72 the last part of the registration number will vary but the other part are constant, during group registration the system should fail to register if the registration number is already registered, the system should reply by custom message with red colour saying that number is already registered .
Each group must have at least one activity, sample activity are livestock keeping, agriculture, cultivation, farming there are many activities but these are just sample.

The loan Part
Admin should assign loan to the group which need loan and the loan should come from the following part
1)ministry
2)government
3)Donors
4)District council
The amount of loan should be given to the group which need that loan
The date in which the loan was assigned
The due date for the loan to be fully paid
 The interest is 10% of the original amount of the loan
The loan is coming from which parts

On payment of the loan.
The loan must be paid in ten months or twelve months
The system should display original loan
The system should display the remaining amount
The system should display the due date for the loan
The system should calculate repayment schedules and shows the amount which must be paid by the group each month until the loan is finished.
Admin should enter returned amount and feed it to the specific group and debt should decrement.
Admin should be able to print statement showing repayment of any group he/she want to see
Admin should be able to generates reports also the reports should display the current date of report generation.
Admin should be able to generate exports
Also implement nice pagination like in your online quiz project.
Also please implement search, example admin might need to search for a certain group, he/she might search using group registration number or search by or search by group leader location and then do CRUD operation or print group details.
I have included a database of location which is dependent selection during registration of groups to help you, this will help to shows location of group from region level to village level.
