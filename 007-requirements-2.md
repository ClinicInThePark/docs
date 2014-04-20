# Requirements Document - What This Software Must Do

Team Clinic in the Park 

Eric Acampora, Eddie Duong, Ka Lun Lee, Hugo Polanco

## Functional Requirements

### Database

+ Create a database to store visitor information.
+ Tracks which stations are attended by each visitor, and makes this information available to visitors on an individual basis.
+ Provides each visitor with specialized documentation based on which stations were attended. For example, if a visitor attended the dental station and the blood testing station, special documents (maintained by Clinic in the Park) regarding those stations should be made accessible to the visitor in a final report.
+ Data placed in the database needs to be made available to Clinic in the Park to conduct statistical analysis. For example, up until now, stations have tracked the number of visitors that have been serviced using simple counting devices. This data is then manually recorded on paper when someone goes around to each booth at the end of the day. We need to efficiently record this same data in the database, and make it available in such a way that Clinic in the Park can continue these statistical analyses.
+ Need to track visitors without revealing identity.
+ Allows for recording of specific medical information, depending on particular details and any agreement that Clinic in the Park and their participating organizations come to.
 

### Website Management
+ Provide a box on the website for users to subscribe to the Clinic in the Park emails (flyers, newsletters, etc).
+ Add a checklist that provides information for each particular station that is available.
+ Create portal to interact with database and allow visitors and staff to access using account system.
+ Potentially create way for staff to manage database through the website. This may end up being separate from website.
+ Some kind of calendar that efficiently shows users the Clinic in the Park schedule. Needs to look nice.


## Non-Functional Requirements
+ Needs to be easily-maintainable going into the future.
+ If tracking personal medical information, needs to be accessibile to providers at other healthcare establishments.
+ Must be HIPAA-compliant and in line with privacy and other security concerns.
+ Usability needs to be focused on visitors and providers that attend Clinic in the Park event.
+ Needs to be portable, as the primary setting (in which data will be recorded) is outdoors at OC Great Park.
+ Must be able to quickly and easily backup information.
+ Needs to be reliable and efficient.

## Assumptions

If outdoors at OC Great Park, the user will:

+ have a functioning, portable device with networking capability and/or Internet access. 
+ have decent understanding of how to operate that device.

In other settings, the user will:

+  have access to a functional device with Internet access.
+  have decent understanding of how to operate that device.
+  have some sort of login credentials to access the system.
