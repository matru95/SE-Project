# Software Engineering Project

The	objective	of this	project	is to	apply	software engineering practices and being able to address new software engineering issues in a rigorous way.
The project includes two assignments:
1. The preparation of a Requirement Analysis and Specification Document (RASD).
2. The definition of the Design Document (DD) for the system considered in the previous point.

## The problem: Travlendar+
(adapted from: http://score-contest.org/2018/projects/travlendar.php)  
  
Many endeavors  require  scheduling meetings at  various locations all across a  city or a  region  (e.g., 
around  Lombardy),  whether  for  work  or  personal  reasons (e.g., meeting  the  CEO  of  a  partner company, going  to  the gym, taking children  to practice, etc.).  
The goal of  this project is  to create a calendar-based  application that:  
- automatically  computes  and  accounts  for  travel  time  between appointments  to make sure  that the user is not late  for appointments;
- supports  the user in his/her travels, for example by identifying the best mobility option  
(e.g., use the train from A to B and then the metro to C), buying public transportation  tickets, or by locating  the nearest bike of a bike  sharing system.  

Users can create meetings, and when meetings are created at locations  that are unreachable in the allotted  time, a warning is created. As mentioned,  the application should also suggest  travel means 
depending on the appointment (e.g., perhaps you bike to the office in the morning, but the bus is a 
better choice between a pair of afternoon meetings, and a car – either personal, or of a car-sharing 
system – is best to take children to practice) and the day (e.g., the app should suggest that you leave 
your home via car in the morning because meetings during a strike day will not be doable via public 
transportation;  it  could  also  take  into  account  the  weather  forecast,  and  avoid  biking  during  rainy 
days).  

Travlendar+ should  allow  users  to  define  various  kinds  of  user  preferences.  It  should  support  a 
multitude of travel means, including walking, biking (own or shared), public transportation (including 
taxis), driving (own or shared), etc. A particular user may globally activate or deactivate each  travel 
means (e.g., a user who cannot drive would deactivate driving). A user should also be able to provide 
reasonable constraints on different travel means (e.g., walking distances should be less than a given 
distance, or public transportation should not be used after a given time of day). Users should also be 
able, if they wish to, to select combinations of transportation means that minimize carbon footprint.  

Additional features could also be envisioned, for instance allowing a user to specify a flexible "lunch". 
For instance, a user could be able  to specify  that lunch must be possible every day between 11:30-
2:30, and it must be at least half an hour long, but the specific timing is flexible. The app would then 
be sure  to  reserve at least 30 minutes  for lunch each day. Similarly, other  types of breaks might be 
scheduled in a customizable way.  

Travlendar+ should also offer the possibility to arrange the trips of the user. For example, it should allow users to buy public transportation tickets when a bus or
the metro should be taken (but also the possibility that the user has a day/week/season pass could be considered), or it should locate the nearest car or bike of a vehicle sharing system if that is the means of transport of choice.