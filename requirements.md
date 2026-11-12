# Requirements

## Functional requirements (what the system must DO)
FR1: The system shall require employers to specify internship start availability as an exact date, a date range, or flexible before publishing a listing.
FR2: The system shall require employers to specify accepted internship duration as a fixed number of months, a minimum and maximum range, or negotiable before publishing a listing.
FR3: The system shall allow students to enter their required internship start date and duration.
FR4: The system shall classify each listing as “Matches”, “Does not match”, or “Needs confirmation” by applying placement compatibility rules.
FR5: The system shall display the reason for each listing’s compatibility classification.
FR6: The system shall allow students to filter listings by compatibility classification.

## Non-functional requirements (how the system must PERFORM)
NFR1: Performance: The system shall display filtered results within 2 seconds for at least 95% of searches when tested with 1,000 listings and 20 concurrent users.
NFR2: Security: The system shall reject all attempts to update a listing’s placement details by unauthenticated users or employers who do not own that listing.
NFR3: Usability: The system shall enable at least 4 out of 5 student participants to enter their placement requirements and identify a matching listing within 3 minutes without assistance during usability testing.
