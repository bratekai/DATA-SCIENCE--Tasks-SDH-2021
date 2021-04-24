1. Case
- case_id - the ID of the infection case
- province - Special City / Metropolitan City / Province(-do
- city - City(-si) / Country (-gun) / District (-gu)
- group - TRUE: group infection / FALSE: not group
- infection_case - the infection case (the name of group or other cases)
- confirmed - the accumulated number of the confirmed
- latitude - the latitude of the group (WGS84)
- longitude - the longitude of the group (WGS84)

2. PatientInfo
- patient_id - the ID of the patient
- sex
- age
- country
- province
- city
- infection_case - the case of infection
- infected_by - the ID of who infected the patient
- contact_number - the number of contacts with people
- symptom_onset - the date of symptom onset

3. Policy
- policy_id
- country - the country that implemented the policy
- type
- gov_policy
- detail
- start_date
- end_date

4. Region
- code - the code of the region
- province
- city
- latitude
- lognitude
- elementary_school_count
- kindergarten_count
- university_count
- academy_ratio - the ratio of academies
- elderly_population - the ratio of the elderly population

5. SearchTrend - Trend data of the keywords searched in NAVER which is one of the largest portals in South Korea. 
Following columns shows the search volume of each word.
- date
- cold
- flu
- pneumonia
- corononavirus

6. Time - Data on number of tests and people released/deceased

7. TimeAge - Time series data of COVID-19 status in terms of the age in South Korea

8. TimeGender - Time series data of COVID-19 status in terms of gender in South Korea

9. TimeProvince - Time series data of COVID-19 status in terms of the Province in South Korea

10. Weather - Data of the weather in the regions of South Korea


