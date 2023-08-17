Leveraged a tech stack comprising Spring MVC, JSP, Hibernate, and HQL to proficiently manage data operations encompassing DDL, DML, and intricate joins.
Implemented dynamic front-end interactivity using jQuery DataTable for enhanced user experience.

Devised a comprehensive user authentication system, assigning distinct roles of "Maker" and "Checker" based on login credentials.
This role-based access control delineated distinct authority levels within the system.

Implemented a robust security mechanism by employing Bcrypt encryption to safeguard sensitive user data stored in the User Authority table.

Assumed the role of a "Maker" responsible for creating new records, which were subsequently stored in a designated temporary table.

Enacted the role of a "Checker" endowed with the authority to authorize, reject, or return records.
Validated and approved maker-generated records for further processing.

Developed a dedicated temporary table to house records created by the "Maker," ensuring a structured and organized data management approach.

Orchestrated a comprehensive set of functionalities for the "Checker," including the ability to authorize, reject, or send back records to the "Maker" for revision.

Established a master table exclusively dedicated to housing records that were successfully validated and authorized by the "Checker,"
thus ensuring the accuracy and integrity of the approved data.
