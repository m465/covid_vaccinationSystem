The proposed system is designed to streamline and manage the vaccination process during the COVID-19 pandemic. It encompasses various modules to cater to different roles within the vaccination framework, ensuring a systematic and organized approach. Here's a brief overview of the key components:

1. **Super Admin:**
   - Manages user accounts through CRUD operations.

2. **Admin:**
   - Procures vaccines locally and internationally.
   - Oversees vaccine storage in government-owned warehouses.
   - Establishes vaccination centers nationwide.
   - Manages daily vaccine dispatch based on consumption.

3. **Doctor:**
   - Assigned to vaccination centers to assess citizens' vital stats.

4. **Front Desk Officer (FDO):**
   - Interacts with citizens at counters.
   - Verifies eligibility and assigns vaccination counters.

5. **Government Official:**
   - Accesses detailed reports and statistics related to the vaccination drive.

6. **Citizen:**
   - Registers via a sign-up page with personal details.
   - Checks eligibility criteria, receives confirmation upon successful registration.
   - Views vaccination history, including received vaccines and scheduled dates.

**Requirements:**
   - Emphasizes secure user authentication with unique credentials for each user type.
   - Manages vaccine information, warehouse details, and batch information for efficient tracking.
   - Implements a common parent class, "PERSON," for shared attributes among entities involving people.
   - Utilizes organized data storage through .csv or .txt files.

The system is designed to ensure data integrity, security, and efficiency throughout the entire vaccination process. Its modular structure allows for flexibility and scalability, adapting to the dynamic nature of vaccine distribution and citizen management during the pandemic.
