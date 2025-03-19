# Validation Report

## Data Overview
- Total courses: 75
- Total course sections: 83
- Total student requests: 1259
- Total unique students: 156

## Issues
- Missing required course: Only 30/36 1st Year students requested BIB9
- Missing required course: Only 40/41 2nd Year students requested BIB10
- Courses with no requests: LIVEWELL, MATALG1MS, MATFUND, MATHPreALGH7, MATPreALG, MATTRAN
- Under-subscribed: ARTBND has only 19 requests for 40 spots
- Under-subscribed: ARTChor has only 16 requests for 40 spots
- Under-subscribed: ARTSTD1 has only 10 requests for 26 spots
- Under-subscribed: ARTSTD2 has only 11 requests for 26 spots
- Under-subscribed: DECHEM105 has only 2 requests for 26 spots
- Under-subscribed: DEENG101 has only 1 requests for 26 spots
- Over-subscribed: DEENG151 has 30 requests but 26 spots
- Under-subscribed: DEITCHG has only 2 requests for 26 spots
- Under-subscribed: DESOCIP has only 5 requests for 26 spots
- Under-subscribed: DESOCWCIV2 has only 4 requests for 26 spots
- Under-subscribed: ENG12WORLD has only 12 requests for 26 spots
- Under-subscribed: ENG12WORLDH has only 7 requests for 26 spots
- Under-subscribed: ENGSPCH has only 2 requests for 26 spots
- Under-subscribed: FAF has only 10 requests for 40 spots
- Under-subscribed: FINLIT has only 24 requests for 52 spots
- Under-subscribed: LANSP3 has only 10 requests for 26 spots
- No demand: LIVEWELL has 4 sections but 0 requests
- Under-subscribed: MATALG1 has only 8 requests for 26 spots
- Under-subscribed: MATALG1H has only 5 requests for 26 spots
- Over-subscribed: MATALG2H has 31 requests but 26 spots
- Under-subscribed: MATAPCALCAB has only 6 requests for 26 spots
- Under-subscribed: MATDESTATS has only 1 requests for 26 spots
- No demand: MATFUND has 1 sections but 0 requests
- Under-subscribed: MATHALGIII has only 11 requests for 26 spots
- No demand: MATHPreALGH7 has 1 sections but 0 requests
- Under-subscribed: MATHSTATSH has only 6 requests for 26 spots
- No demand: MATPreALG has 2 sections but 0 requests
- No demand: MATTRAN has 2 sections but 0 requests
- Under-subscribed: PEHealthHS has only 37 requests for 78 spots
- Under-subscribed: PEPF has only 9 requests for 26 spots
- Under-subscribed: SCIMABIO has only 10 requests for 26 spots
- Over-subscribed: SOC11 has 29 requests but 26 spots
- Under-subscribed: SOCIB has only 2 requests for 26 spots
- Under-subscribed: TECHADVROB has only 8 requests for 26 spots
- Over-subscribed: TECHDIGIT has 33 requests but 26 spots
- Under-subscribed: TECHYEAR has only 6 requests for 26 spots
- Under-subscribed: PERS has only 8 requests for 26 spots
- Under-subscribed: SCIPHYH has only 7 requests for 26 spots
- Over-subscribed: SOCMODUS has 4 requests but 0 spots
- Over-subscribed: TECHBRJR has 3 requests but 0 spots
- No demand: MATALG1MS has 2 sections but 0 requests
- Under-subscribed: APComp has only 6 requests for 20 spots
- Under-subscribed: ENGJOUR has only 1 requests for 26 spots
- Over-subscribed: SOCCONT has 5 requests but 0 spots
## Insights
- Identified 6 unique blocks from rules: 1A, 1B, 2A, 2B, 4A, 4B
- Total requests: 1259 (Required: 178, Requested: 963, Recommended: 118)
- Total unique students: 156
- 2nd Year: 41 students
- 1st Year: 36 students
- 3rd year: 42 students
- 4th Year: 37 students
- 1st Year - BIB9: 30/36 requested
- 2nd Year - BIB10: 40/41 requested
- 3rd Year - BIB11: 0/0 requested
- 4th Year - BIB12: 37/37 requested
- 6 courses have no student requests
- 7 courses are over-subscribed
- 31 courses are under-subscribed (less than 50% capacity)
- Total unique lecturers: 23
- Lecturers teach between 1 and 7 courses
- Total unique rooms: 20

## Rules Summary
- Rule 1: The  has N number of blocks - namely : ["1A","1B","2A","2B","3","4A","4B"]
- Rule 2: Blocks refer to fixed time periods or chunks of time during the  day when specific classes or activities are scheduled. Unlike traditional period-based systems (common in countries like India, where t...
- Rule 3: No teacher can be present twice in same block
- Rule 4: No student can be present twice in same block
- Rule 5: You need to assign student to section of the requested course in a particular block so that we 
maximize the number of resolutions of students requests received
- Rule 6: Students of different year can be assigned to same sections if they have requested for the same course 
- Rule 7: No sections should be overcrowded - distribute the course requested students almost equally across the available sections of that particular course
- Rule 8: "Required" > "Requested" > "Recommended", 
this is the order of priority of requests, treat it as P1, P2, P3 
- Rule 9: Available blocks & Unavailable blocks columns in Course list are exactly what they sound like, you can schedule sections of those courses only in one of the blocks available in `Available Blocks` list...
- Rule 10: Length / Course Length (1 = One Term, 2 = Full Year) / Credits determine if the course will run for the entire year or Half a year 
