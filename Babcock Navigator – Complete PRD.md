# PRODUCT REQUIREMENTS DOCUMENT
## 1. Project Overview
### Project Name                                  
             Babcock University Campus Navigation System
### Project Type                              
                 Campus Navigation Platform
### Course                                               
      BU-209 Backend Engineering 
### Project Description    
   Babcock Navigator is a digital campus navigation system designed to help students locate buildings,lecture halls,hostels and other within Babcock University.It provides an interactive campus map and location search using GPS or manual starting-point selection.
### Purpose                                              
   We want to develop this system because we want students to have easy access moving from one place to the other within the campus.This is as a result of various reports of students going late for classes due to this reason. This is why we want the students to have access to a standard map that will allow them navigate through the school campus easily.
### Intended Users                                          
   -Newly Admitted Students
-Returning Students   
      -Campus Students
      # PRODUCT REQUIREMENTS DOCUMENT
## 1. Project Overview
### Project Name                                  
             Babcock University Campus Navigation System
### Project Type                              
                 Campus Navigation Platform
### Course                                               
      BU-209 Backend Engineering 
### Project Description    
   Babcock Navigator is a digital campus navigation system designed to help students locate buildings,lecture halls,hostels and other within Babcock University.It provides an interactive campus map and location search using GPS or manual starting-point selection.
### Purpose                                              
   We want to develop this system because we want students to have easy access moving from one place to the other within the campus.This is as a result of various reports of students going late for classes due to this reason. This is why we want the students to have access to a standard map that will allow them navigate through the school campus easily.
### Intended Users                                          
   -Newly Admitted Students
-Returning Students   
      -Campus Students
      ## 2. Problem Statement
### Background of the Problem    
   Students find it hard to locate lecture venues and get late to classes in the process. Some new students when they resume don't know their way around the campus and end up getting lost .Some visiting parents find it hard to locate their children's halls of residence and causes inconvenience.Students who are not familiar with the campus environment are solely dependent on asking people for direction and sometimes they might end up asking someone who is not familiar with their location directions.
### The Main Problem
   Students and visitors find it hard to navigate around Babcock University, especially when trying to locate unfamiliar buildings and structures. Without a reliable campus navigation platform, they will solely depend on other people for directions or even spend more time searching for locations. This creates a need for a digital map that provides clear information and directions to important places within the university.
### Who Experiences the Problem?       
   -Newly Admitted students   
         -Campus visitors                      
                         -Returning students
### Current methods of Solving the Problem      
   Currently,students who are unfamiliar with places ask for directions from people like SOP's ,lecturers,staff members,and fellow students. Others use signboards to identify locations . However, these are not reliable methods.
   # PRODUCT REQUIREMENTS DOCUMENT (PRD)
## Product Name: Babcock Navigator
**Team:** Byte Force

## 3. Business Objectives

The primary objective of Babcock Navigator is to make campus navigation easier for students by providing a digital platform for locating buildings and facilities within Babcock University.

Based on the student survey, 9 out of 11 respondents expressed interest in a digital campus navigation platform. The objectives below are designed to address the navigation difficulties and user needs identified in the research.

| ID | Business Objective | Success Metric | Proposed Target |
|---|---|---|---|
| BO-1 | Make campus buildings easier to locate | Percentage of users who successfully find their intended destinations using the platform | 85% success rate during pilot testing |
| BO-2 | Reduce dependence on asking people for directions | Percentage of users who report less dependence on other people for directions | 40% reduction during pilot testing |
| BO-3 | Provide an interactive campus map | Number of major campus buildings and facilities available on the map | At least 90% of verified target locations |
| BO-4 | Improve access to lecture hall directions | Percentage of users who successfully obtain directions to their selected lecture halls | 90% success rate |
| BO-5 | Provide convenient location search | Percentage of location searches that return relevant results | 90% successful searches |
| BO-6 | Support different starting-location preferences | Availability of GPS detection and manual starting-location selection | Both options available in the first release |
| BO-7 | Improve student satisfaction with campus navigation | Percentage of tested users who give positive feedback about the platform | 80% positive feedback |
## 4. Target Users
### Primary Users           
   -Newly admitted students                           
            -Returning students                      
                      -Direct Entry students
### Secondary Users                   
   -Parents and guardians visiting the university        
         -Visitors and guests                           
                -Newly employed staff members
### User Description                                   
   **Newly Admitted Students:*                         
           Students unfamiliar with the campus layout and need help locating lecture halls, halls of residence and other facilities                                                     **Returning Students:*                                        
 Students who may needd directions to unfamiliar buildings, offices and facilities                                  
       **Visitors and Guests:*                                  
      People visiting the university who need assistance locating specific departments,offices or event venues.
      # PRODUCT REQUIREMENTS DOCUMENT (PRD)
## Product Name: Babcock Navigator
**Team:** Byte Force

## 5. Stakeholders

| Stakeholder | Interest in Babcock Navigator |
|---|---|
| Students | Primary users who need an easier way to locate administrative buildings, lecture halls, hostels and other campus facilities. |
| University Management | Interested in improving campus accessibility and making university facilities easier for students to locate. |
| Campus ICT Department | Interested in the technical infrastructure, system integration, maintenance and technical support required for the platform. |
| Facilities Management | Responsible for providing and verifying information about university buildings and facilities. |
| Security Personnel | Can assist in identifying campus landmarks, accessible routes and important locations within the university. |
| Byte Force Development Team | Responsible for designing, developing, testing and maintaining the Babcock Navigator platform. |
## 6. User Stories 
### Newly Admitted Students                  
 -As a new student,I want to search for lecture halls so I can find my classes easily
-As a new student, I want to view a map for the university so I can understand the campus layout
-As a new student,I want to locate halls and cafeteria so that I can access important facilities
### Returning Students   
 -As a returning student,I want to search for unfamiliar buildings so I can find them without asking people
-As a returning student,I want to view directions to different locations so thatI can save time
### Visitors and Guests     
 -As a visitor ,I want to search for university buildings and event venues so as to locate them easily
-As a visitor, I want to view directions to my destination so that I can navigatethe campus confidently
# PRODUCT REQUIREMENTS DOCUMENT (PRD)
## Product Name: Babcock Navigator
**Team:** Byte Force

## 7. Functional Requirements

1. **Interactive Campus Map:** The platform should provide an interactive map showing buildings, facilities and important landmarks within Babcock University. This addresses the interactive map preference expressed by 6 respondents.

2. **Location Search:** Users should be able to search for buildings and facilities by name, making it easier to locate unfamiliar places. Four respondents specifically selected this feature in the survey.

3. **Directions to Lecture Halls:** The system should provide directions to selected lecture halls to help students locate their classrooms more easily. Five respondents requested this feature.

4. **Administrative Building Navigation:** The platform should allow users to search for and navigate to administrative buildings, which were the most frequently identified difficult locations in the survey.

5. **GPS Location Detection:** The system should detect the user's current geographical location when GPS is enabled and permission has been granted.

6. **Manual Starting-Location Selection:** Users should be able to select their starting location manually when GPS is unavailable, inaccurate or not preferred.

7. **Destination Selection:** Users should be able to select their desired destination through the search function or directly from the interactive map.

8. **Navigation Directions:** The system should generate directions from the selected starting point to the destination using a supported mapping and routing service.

9. **Halls of Residence Guide:** The system should provide information and directions to available halls of residence. This feature was selected by 3 respondents.

10. **Important Campus Landmarks:** The platform should identify important campus landmarks to help students recognize locations and navigate around the university. Three respondents selected this feature.

11. **Location Categories:** Campus locations should be organized into categories such as administrative buildings, lecture halls, halls of residence and other facilities.

12. **Distance Estimation:** The system should display the estimated distance between the user's starting location and selected destination.

13. **Colour-Coded Buildings:** The map should use different colours to distinguish between categories of buildings and facilities, reflecting an additional suggestion from the survey.

14. **Location Management:** Authorized administrators should be able to add, update and remove campus location information to maintain accurate records.

15. **GPS Failure Handling:** The system should display an appropriate message when GPS detection fails and allow users to select their starting location manually.
16. # PRODUCT REQUIREMENTS DOCUMENT (PRD)
## Product Name: Babcock Navigator
**Team:** Byte Force

## 8. Non-Functional Requirements

1. **Security:** The system should protect users' personal information and prevent unauthorized access to administrative functions.

2. **Usability:** The platform should have a simple and understandable interface that allows students to search for locations and obtain directions without difficulty.

3. **Performance:** The platform should load its main interface and retrieve location information within an acceptable time under normal network conditions.

4. **Reliability:** The system should provide consistent access to registered campus locations and navigation services whenever the platform is available.

5. **Compatibility:** The platform should support commonly used smartphones and modern web browsers, depending on the final deployment approach.

6. **Scalability:** The backend should support the addition of more campus buildings, facilities and users as the platform grows.

7. **Accuracy:** Building names, geographical coordinates and navigation information should be verified to reduce incorrect directions.

8. **Maintainability:** The backend should be organized in a way that allows developers to update location information, fix errors and introduce additional features easily.

9. **Availability:** The platform should remain accessible to students during normal operating conditions, with appropriate handling of planned maintenance and external service interruptions.

10. **Privacy:** The system should request permission before accessing users' GPS locations and should avoid collecting unnecessary personal location information.
11. ## 9. Scope and Priorities 
### InScope                                  
   The first version of the Campus Navigation System will include:                      
   - A digital map of Babcock University
   - Search functionality for campus buildings and facilities
   - Location information for lecture halls,hostels,cafeteria and administrative blocks
   - Direction from one campus location to another  
   - A simple and user-friendly interface
### Out of Scope            
   The first version will not include:          
-Real-time tracking of students
-Live traffic monitoring 
-Indoor navigation using advanced positioning technology
-Automatic voice-guided navigation
### Feature Priorities 
| Feature | Priority |                                      
|--- | -
| Campus map        | High                                                |
| Location search                  | High                                                    |
| Building information                                 | High                                                        |
| Directions between locations                                                     | Low                                                            |
| Voice Navigation                                                                                 | Low                                                               |
| Real-time tracking                                                                                                 | Low                                                                  |
### Minimum Viable Product (MVP) 
   The MVP will provide a basic digital campus map,a search feature for important university locations,information about selected buildings and simple directions between locations.
   # PRODUCT REQUIREMENTS DOCUMENT (PRD)
## Product Name: Babcock Navigator
**Team:** Byte Force

## 11. Assumptions and Open Questions

### 11.1 Assumptions

| # | Assumption | Impact if Wrong |
|---|---|---|
| 1 | Students will find a digital campus navigation platform useful, as indicated by the 9 positive responses in the survey. | Low student interest could reduce the platform's adoption and usefulness. |
| 2 | Students have access to smartphones or internet-enabled devices that can access the platform. | Students without compatible devices may have difficulty using the navigation service. |
| 3 | Students will be willing to use GPS location detection when they need automatic directions. | Users who decline location permission will have to rely on manual starting-location selection. |
| 4 | Students can identify their starting locations manually when GPS is unavailable. | Users may still experience difficulty navigating if they cannot identify their starting point. |
| 5 | Accurate information about Babcock University's buildings and facilities can be obtained. | Incomplete or incorrect location information could result in inaccurate navigation. |
| 6 | Administrative buildings, lecture halls and halls of residence can be identified and included in the campus map. | Some locations requested by students may be missing from the platform. |
| 7 | A suitable mapping and routing service will be available to support campus navigation. | The team may need to consider alternative mapping services or additional development work. |
| 8 | Students will have sufficient internet connectivity to access the map and navigation features. | Poor connectivity could affect map loading and navigation requests. |
| 9 | University management will permit the development team to collect and use relevant campus location information. | Restrictions could delay development and prevent the inclusion of certain locations. |
| 10 | Students will be comfortable using either a website or mobile application, as several respondents expressed flexibility in their preferred access method. | The selected platform may not meet the preferences of all users. |

### 11.2 Open Questions

| # | Open Question |
|---|---|
| 1 | Does Babcock University have an existing official digital campus map that the development team can access? |
| 2 | How will the team obtain and verify the geographical coordinates of campus buildings and facilities? |
| 3 | Which mapping service will be used to provide the interactive campus map and navigation directions? |
| 4 | Should the first version cover every campus building or focus on the most frequently requested locations? |
| 5 | Should the platform provide pedestrian directions only, or should it also support vehicle navigation? |
| 6 | How will the system handle situations where GPS signals are weak or inaccurate? |
| 7 | Should students be allowed to report missing buildings or incorrect location information? |
| 8 | Will students need to register or log in before accessing the navigation platform? |
| 9 | Should users be able to access previously loaded campus maps without an internet connection? |
| 10 | Who will be responsible for updating building locations and other campus information when changes occur? |
| 11 | Should the platform provide accessibility information for students with mobility difficulties? |
| 12 | Should the system use different colours to distinguish building categories, as suggested by one survey respondent? |

**Research Note:** The survey was completed by 11 respondents. The findings provide preliminary evidence of student navigation challenges and interest in a digital navigation platform. Further interviews and research involving students from additional academic levels and faculties will be necessary to validate these requirements.
