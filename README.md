# MARKETING CAMPAIGN PERSONALIZATION FOR CALIFORNIA ED-TECH COMPANY

## Problem Statement
Due to the decline of number of Test Taker during the past four years, The marketing team at  CALEARNFONIA Inc. need to change the strategy by requesting company data scientist to provide guideline to revisit the customer finding strategy to improve personalization in the marketing campaign of SAT and ACT e-learning course.

## Background of Ca**Learn**fornia.
**CALEARNFORNIA Inc.**, california-based education Technology startup company (EdTech), who offer the e-learning platform for more than 5 years, including ACT (American College Testing) and SAT (Scholastic Aptitude Test) Pre-exam e-learning platform. They hired Data Scientist to optimize marketing campaign by bringing data from California Department of Education to formulate strategic campaign for boosting revenue.

## Dataset

| Field # | Field Name            | Type      | Width | Description                                                                                                                                                                   | Dataset|
| ------- | --------------------- | --------- | ----- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------|
|  |
| 1       | CDS                   | Character | 14    | County/District/School Code                                                                                                                                                   | act_2019_ca |
| 2       | CCODE                 | Character | 2     | County Code                                                                                                                                                                   | act_2019_ca |
| 3       | CDCODE                | Character | 7     | District Code                                                                                                                                                                 | act_2019_ca |
| 4       | SCODE                 | Character | 7     | School Code                                                                                                                                                                   | act_2019_ca |
| 5       | RTYPE                 | Character | 1     | Record Type: C=County, D=District, S=School, X=State                                                                                                                          | act_2019_ca |
| 6       | SNAME                 | Character | 100   | School Name, N/A = County or District Level Record                                                                                                                            | act_2019_ca |
| 7       | DNAME                 | Character | 100   | District/LEA Name, N/A = County Level Record                                                                                                                                  | act_2019_ca |
| 8       | CNAME                 | Character | 15    | County Name                                                                                                                                                                   | act_2019_ca |
| 9       | ENROLL12              | Character | 7     | Enrollment of Grade 12                                                                                                                                                        | act_2019_ca |
| 10      | NUMTSTTAKR12          | Character | 7     | Number of Test Takers Grade 12                                                                                                                                                | act_2019_ca |
| 11      | NumERWBenchmark12     | Character | 7     | The number meeting the Evidence-Based Reading & Writing (ERW) benchmark established by the College Board based on the New 2016 SAT test format as of March 2016 for Grade 12. | act_2019_ca |
| 12      | PctERWBenchmark12     | Character | 7     | The percent of students who met or exceeded the benchmark for Evidence-Based Reading & Writing (ERW) test for Grade 12.                                                       | act_2019_ca |
| 13      | NumMathBenchmark12    | Character | 7     | The number of students who met or exceeded the benchmark for the New SAT Math test format as of March 2016 for Grade 12.                                                      | act_2019_ca |
| 14      | PctMathBenchmark12    | Character | 7     | The percent of students who met or exceeded the benchmark for SAT Math test for Grade 12.                                                                                     | act_2019_ca |
| 15      | ENROLL11              | Character | 7     | Enrollment of Grade 11                                                                                                                                                        | act_2019_ca |
| 16      | NUMTSTTAKR11          | Character | 7     | Number of Test Takers Grade 11                                                                                                                                                | act_2019_ca |
| 17      | NumERWBenchmark11     | Character | 7     | The number meeting the Evidence-Based Reading & Writing (ERW) benchmark established by the College Board based on the New 2016 SAT test format as of March 2016 for Grade 11. | act_2019_ca |
| 18      | PctERWBenchmark11     | Character | 7     | The percent of students who met or exceeded the benchmark for Evidence-Based Reading & Writing (ERW) test for Grade 11.                                                       | act_2019_ca |
| 19      | NumMathBenchmark11    | Character | 7     | The number of students who met or exceeded the benchmark for the New SAT Math test format as of March 2016 for Grade 11.                                                      | act_2019_ca |
| 20      | PctMathBenchmark11    | Character | 7     | The percent of students who met or exceeded the benchmark for SAT Math test for Grade 11.                                                                                     | act_2019_ca |
| 21      | TotNumBothBenchmark12 | Character | 7     | The total number of students who met the benchmark of both Evidence-Based Reading & Writing (ERW) and Math Grade 12.                                                          | act_2019_ca |
| 22      | PctBothBenchmark12    | Character | 7     | The percent of students who met the benchmark of both Evidence-Based Reading & Writing (ERW) and Math Grade 12.                                                               | act_2019_ca |
| 23      | TotNumBothBenchmark11 | Character | 7     | The total number of students who met the benchmark of both Evidence-Based Reading & Writing (ERW) and Math Grade 11.                                                          | act_2019_ca |
| 24      | PctBothBenchmark11    | Character | 7     | The percent of students who met the benchmark of both Evidence-Based Reading & Writing (ERW) and Math Grade 11.                                                               | act_2019_ca |
| 25      | Year                  | Character | 7     | The SAT test administration year: 2018-19                                                                                                                                     | act_2019_ca |
| 1  | CDS                   | Character | 14  | County/District/School Code                                                                                                                                                   | sat_2019_ca |
| 2  | CCODE                 | Character | 2   | County Code                                                                                                                                                                   | sat_2019_ca |
| 3  | CDCODE                | Character | 7   | District Code                                                                                                                                                                 | sat_2019_ca |
| 4  | SCODE                 | Character | 7   | School Code                                                                                                                                                                   | sat_2019_ca |
| 5  | RTYPE                 | Character | 1   | Record Type: C=County, D=District, S=School, X=State                                                                                                                          | sat_2019_ca |
| 6  | SNAME                 | Character | 100 | School Name, N/A = County or District Level Record                                                                                                                            | sat_2019_ca |
| 7  | DNAME                 | Character | 100 | District/LEA Name, N/A = County Level Record                                                                                                                                  | sat_2019_ca |
| 8  | CNAME                 | Character | 15  | County Name                                                                                                                                                                   | sat_2019_ca |
| 9  | ENROLL12              | Character | 7   | Enrollment of Grade 12                                                                                                                                                        | sat_2019_ca |
| 10 | NUMTSTTAKR12          | Character | 7   | Number of Test Takers Grade 12                                                                                                                                                | sat_2019_ca |
| 11 | NumERWBenchmark12     | Character | 7   | The number meeting the Evidence-Based Reading & Writing (ERW) benchmark established by the College Board based on the New 2016 SAT test format as of March 2016 for Grade 12. | sat_2019_ca |
| 12 | PctERWBenchmark12     | Character | 7   | The percent of students who met or exceeded the benchmark for Evidence-Based Reading & Writing (ERW) test for Grade 12.                                                       | sat_2019_ca |
| 13 | NumMathBenchmark12    | Character | 7   | The number of students who met or exceeded the benchmark for the New SAT Math test format as of March 2016 for Grade 12.                                                      | sat_2019_ca |
| 14 | PctMathBenchmark12    | Character | 7   | The percent of students who met or exceeded the benchmark for SAT Math test for Grade 12.                                                                                     | sat_2019_ca |
| 15 | ENROLL11              | Character | 7   | Enrollment of Grade 11                                                                                                                                                        | sat_2019_ca |
| 16 | NUMTSTTAKR11          | Character | 7   | Number of Test Takers Grade 11                                                                                                                                                | sat_2019_ca |
| 17 | NumERWBenchmark11     | Character | 7   | The number meeting the Evidence-Based Reading & Writing (ERW) benchmark established by the College Board based on the New 2016 SAT test format as of March 2016 for Grade 11. | sat_2019_ca |
| 18 | PctERWBenchmark11     | Character | 7   | The percent of students who met or exceeded the benchmark for Evidence-Based Reading & Writing (ERW) test for Grade 11.                                                       | sat_2019_ca |
| 19 | NumMathBenchmark11    | Character | 7   | The number of students who met or exceeded the benchmark for the New SAT Math test format as of March 2016 for Grade 11.                                                      | sat_2019_ca |
| 20 | PctMathBenchmark11    | Character | 7   | The percent of students who met or exceeded the benchmark for SAT Math test for Grade 11.                                                                                     | sat_2019_ca |
| 21 | TotNumBothBenchmark12 | Character | 7   | The total number of students who met the benchmark of both Evidence-Based Reading & Writing (ERW) and Math Grade 12.                                                          | sat_2019_ca |
| 22 | PctBothBenchmark12    | Character | 7   | The percent of students who met the benchmark of both Evidence-Based Reading & Writing (ERW) and Math Grade 12.                                                               | sat_2019_ca |
| 23 | TotNumBothBenchmark11 | Character | 7   | The total number of students who met the benchmark of both Evidence-Based Reading & Writing (ERW) and Math Grade 11.                                                          | sat_2019_ca |
| 24 | PctBothBenchmark11    | Character | 7   | The percent of students who met the benchmark of both Evidence-Based Reading & Writing (ERW) and Math Grade 11.                                                               | sat_2019_ca |
| 25 | Year                  | Character | 7   | The SAT test administration year: 2018-19                                                                                                                                     | sat_2019_ca |
| 1  | CDS                   | Character | 14  | County/District/School Code                                                                                                                                                   | sat17_ca,sat18_ca,sat20_ca |
| 2  | CCODE                 | Character | 2   | County Code                                                                                                                                                                   | sat17_ca,sat18_ca,sat20_ca |
| 3  | CDCODE                | Character | 7   | District Code                                                                                                                                                                 | sat17_ca,sat18_ca,sat20_ca |
| 4  | SCODE                 | Character | 7   | School Code                                                                                                                                                                   | sat17_ca,sat18_ca,sat20_ca |
| 5  | RTYPE                 | Character | 1   | Record Type: C=County, D=District, S=School, X=State                                                                                                                          | sat17_ca,sat18_ca,sat20_ca |
| 6  | SNAME                 | Character | 100 | School Name, N/A = County or District Level Record                                                                                                                            | sat17_ca,sat18_ca,sat20_ca |
| 7  | DNAME                 | Character | 100 | District/LEA Name, N/A = County Level Record                                                                                                                                  | sat17_ca,sat18_ca,sat20_ca |
| 8  | CNAME                 | Character | 15  | County Name                                                                                                                                                                   | sat17_ca,sat18_ca,sat20_ca |
| 9  | ENROLL12              | Character | 7   | Enrollment of Grade 12                                                                                                                                                        | sat17_ca,sat18_ca,sat20_ca |
| 10 | NUMTSTTAKR12          | Character | 7   | Number of Test Takers Grade 12                                                                                                                                                | sat17_ca,sat18_ca,sat20_ca |
| 11 | NumERWBenchmark12     | Character | 7   | The number meeting the Evidence-Based Reading & Writing (ERW) benchmark established by the College Board based on the New 2016 SAT test format as of March 2016 for Grade 12. | sat17_ca,sat18_ca,sat20_ca |
| 12 | PctERWBenchmark12     | Character | 7   | The percent of students who met or exceeded the benchmark for Evidence-Based Reading & Writing (ERW) test for Grade 12.                                                       | sat17_ca,sat18_ca,sat20_ca |
| 13 | NumMathBenchmark12    | Character | 7   | The number of students who met or exceeded the benchmark for the New SAT Math test format as of March 2016 for Grade 12.                                                      | sat17_ca,sat18_ca,sat20_ca |
| 14 | PctMathBenchmark12    | Character | 7   | The percent of students who met or exceeded the benchmark for SAT Math test for Grade 12.                                                                                     | sat17_ca,sat18_ca,sat20_ca |
| 15 | ENROLL11              | Character | 7   | Enrollment of Grade 11                                                                                                                                                        | sat17_ca,sat18_ca,sat20_ca |
| 16 | NUMTSTTAKR11          | Character | 7   | Number of Test Takers Grade 11                                                                                                                                                | sat17_ca,sat18_ca,sat20_ca |
| 17 | NumERWBenchmark11     | Character | 7   | The number meeting the Evidence-Based Reading & Writing (ERW) benchmark established by the College Board based on the New 2016 SAT test format as of March 2016 for Grade 11. | sat17_ca,sat18_ca,sat20_ca |
| 18 | PctERWBenchmark11     | Character | 7   | The percent of students who met or exceeded the benchmark for Evidence-Based Reading & Writing (ERW) test for Grade 11.                                                       | sat17_ca,sat18_ca,sat20_ca |
| 19 | NumMathBenchmark11    | Character | 7   | The number of students who met or exceeded the benchmark for the New SAT Math test format as of March 2016 for Grade 11.                                                      | sat17_ca,sat18_ca,sat20_ca |
| 20 | PctMathBenchmark11    | Character | 7   | The percent of students who met or exceeded the benchmark for SAT Math test for Grade 11.                                                                                     | sat17_ca,sat18_ca,sat20_ca |
| 21 | TotNumBothBenchmark12 | Character | 7   | The total number of students who met the benchmark of both Evidence-Based Reading & Writing (ERW) and Math Grade 12.                                                          | sat17_ca,sat18_ca,sat20_ca |
| 22 | PctBothBenchmark12    | Character | 7   | The percent of students who met the benchmark of both Evidence-Based Reading & Writing (ERW) and Math Grade 12.                                                               | sat17_ca,sat18_ca,sat20_ca |
| 23 | TotNumBothBenchmark11 | Character | 7   | The total number of students who met the benchmark of both Evidence-Based Reading & Writing (ERW) and Math Grade 11.                                                          | sat17_ca,sat18_ca,sat20_ca |
| 24 | PctBothBenchmark11    | Character | 7   | The percent of students who met the benchmark of both Evidence-Based Reading & Writing (ERW) and Math Grade 11.                                                               | sat17_ca,sat18_ca,sat20_ca |
| 25 | Year                  | Character | 7   | The SAT test administration year: 2019-20                                                                                                                                     | sat17_ca,sat18_ca,sat20_ca |
| 1 | California_County	| Character | 100 | The county Name in California | Personal_Income_per_capita |
| 2 | 2018 | Character | 100 | Number of Personal Income Per Capita in 2018 | Personal_Income_per_capita |
| 3 | 2019 | Character | 100 | Number of Personal Income Per Capita in 2019 | Personal_Income_per_capita |
| 4 | 2020 | Character | 100 | Number of Personal Income Per Capita in 2020 | Personal_Income_per_capita |