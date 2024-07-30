# About Data
Calls for Service to NYPD's 911 system This dataset documents entries into the NYPD 911 system, ICAD. The data is collected from the ICAD system which call takers and dispatchers use to communicate with callers and the NYPD. Each record represents an entry into the system. The data includes entries generated by members of the public as well as self-initiated entries by NYPD Members of Service. The data can be used for issues being responded to by the NYPD.

Link to Data -: https://catalog.data.gov/dataset/nypd-calls-for-service
# Some of the Analysis Performed on the Data
-- FOR COMPLETE ANALYSIS, CHECK THE NOTEBOOK PROVIDED

### Brooklyn had the highest count of events among the boroughs, followed closely by Manhattan.
<img width="172" alt="image" src="https://github.com/user-attachments/assets/cd6b2aec-9d7f-4a13-b2f1-43041a719413">

### The top NYPD precincts with the highest counts were 14, 75, 40, 44, and 52.
<img width="172" alt="image" src="https://github.com/user-attachments/assets/660e6a03-49e2-4f94-ab5c-2ccdc105bdb2">

### The distribution of events across different boroughs and NYPD precincts.
<img width="448" alt="image" src="https://github.com/user-attachments/assets/c038c06b-537f-416f-b06a-f329119a20b4">

### Event Distribution by Months.
<img width="570" alt="image" src="https://github.com/user-attachments/assets/375f4f1f-ed61-47e2-96ca-a15b0b99a155">

### Average response times based on the hour of the day and day of the week, utilizing timestamp data.
<img width="570" alt="image" src="https://github.com/user-attachments/assets/1618d394-6b68-45f0-a3cf-393ab3c8c7a9">
<img width="570" alt="image" src="https://github.com/user-attachments/assets/c86dc1ed-57e0-417a-b8dd-c40c90c997a6">

### Finding least and most occurred TYP_DESC(Events) month-wise.
<img width="390" alt="image" src="https://github.com/user-attachments/assets/954af0f3-259b-4850-9ad1-c2e968e180cd">
<img width="392" alt="image" src="https://github.com/user-attachments/assets/63f4ab06-15dd-4698-b8db-1d8c65bf19f1">

### Analyzed 
  average response times ('ADD_TS_DISP_TS') 
  
  resolution times ('DISP_TS_CLOSNG_TS') 
  
  total incident durations ('ADD_TS_CLOSNG_TS') 
  
  across different incident types ('TYP_DESC') and criticality levels ('CIP_JOBS').
  
<img width="890" alt="Screenshot 2024-07-29 at 7 32 43 PM" src="https://github.com/user-attachments/assets/6747d895-89a3-4952-883e-c67c36706a4e">

### Calculated the average of the response times for each 'TYP_DESC'(Event)
<img width="592" alt="Screenshot 2024-07-29 at 7 41 16 PM" src="https://github.com/user-attachments/assets/b891f872-cb25-48e4-9b6b-002406fc5f70">













