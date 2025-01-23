# Southbridge Public Schools Tasks

**Task 1 : Data Visualization and Observation Task**

Benchmark Performance Levels:

Blue goal = Core support; Negligible risk

- (nearly all students in this range score at or above the 40th percentile rank on criterion measure)

Green range = Core support; Minimal risk

- (about 80% of students who score at or above the 40th percentile rank on criterion measure fall in this range or above)

Yellow range = Strategic support; Some risk

- (about 80% of students who score below the 40th percentile on criterion measure fall in this range or below)

Red range = Intensive support; At risk

- (about 80% of students who score below the 20th percentile on criterion measure fall in this range)

**Task 2: Error Troubleshooting Task**

**ERRORS**

1. ERROR 1: EPIMS9400 - The field WA08 must contain a valid assignment code. It cannot be blank or null.

   - Rudd, Paul (WA08 is missing)
   - Joy Randolph, Da'Vine (WA08 is missing)
   - Gomez, Selena (WA08 is missing)
   - Martin, Steve (WA08 is missing)
   - Streep, Meryl (WA08 is missing)
   - Lynch, Jane (WA08 is missing)

2. ERROR 2 - Missing Schedule Term Column

3. ERROR 3 - Missing Gradebook Access Column

4. ERROR 4 - EPIMS6750 - The co-teaching assignment must be between 2 and 4.

   - Since Martin, Steve is the co-teacher and co-teaching assignment will be only one. This will trigger the error.

5. ERROR 5: EPIMS6770
   - Since only one Co-Teacher (Martin, Steve) is listed in the dataset, the EPIMS6770 error is triggered. The rule specifies that if Co-Teachers are reported, there must be more than one. Reporting just one Co-Teacher for a class violates this rule.
