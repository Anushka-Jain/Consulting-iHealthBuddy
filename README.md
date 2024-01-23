# Personal-Position-Paper-on-Consulting
A position paper is a distillation of your knowledge of topics and subject matter. A position paper adopts or argues for a particular view, position, stance or opinion on the subject matter. The personal position paper is a personal interpretation on selected salient points from a body of knowledge.

# iHealthBuddy - Process Improvement Plan under HSE
This will be used for scheduling appointments and retrieving electronic medical records. 
iHealthBuddy: proposed as a process improvement plan under HSE (which is the public healthcare service of Ireland).

Problem Statement:
Presently, for those relying on the public healthcare system, long waiting times for specialist appointments and elective surgery in hospitals remain an important source of patient dissatisfaction. In 2021, 165K people have been waiting for more than 18 months for an out-patient appointment. Apart from staffing shortages, another issue is the lack of integration between primary and secondary care providers which leads to the delay in diagnosis and treatment.

Platform Service:
Through this platform, we focus on providing 
1.	Access to electronic medical records.
2.	Appointment Scheduling
3.	Online referring of specialists by general practitioners or specialists 

These services will help :
1.	To provide patients with the option of choosing their own GP and specialists, making public health care more appealing. 
2.	Proper scheduling reduces patient wait time and frees up front desk employees.
3.	Bridging the gap between secondary and primary HealthCare will help us reduce the processing time.
4.	Furthermore, the government can use the customer data to track and make informed decisions about public health.

Web Application Views:
Our web application has 2 views: one that of the patient and another of the medical practitioner's view.To demonstrate the process flow, let's take the example of John Doe. He has suffered from a sore knee for some time, and his GP has referred him to a physiotherapist but he has unfortunately been involved in an accident. Now that John has been admitted to the hospital, they are unaware of the treatment he has received in the past. Using our portal, which simply requires a PPSN number for login, John will be able to share his medical history with the doctors at this hospital. By doing so, the hospital will be able to reduce the amount of time it takes to collect information from John's GP and physiotherapist. Additionally, under GDPR governance, all patient information will be shared only with medical practitioners to whom the patient has provided the consent for. Furthermore, our proposed process allows both general practitioners and medical experts to refer patients to other specialists. It then unlocks the referred specialist's profile on the patient's webpage, making it simple to schedule any consultation.

We have designed the sample landing page of iHealthBuddy using the Figma tool where users can search for doctors and healthcare facilities based on their location, specialty, and other criteria.

This diagram shows a high-level overview of process architecture. 
The user’s healthcare data will be extracted from the Irish public healthcare database that will be used further to store and manage on our cloud server.  Additionally, the cloud server data will store the history of medical records and medical practitioners’ information. The data and security layer will make sure to protect healthcare data from unauthorized access and ensure compliance with regulations such as GDPR. Only those general practitioners and specialists would be listed on our platform who are licensed and authorized healthcare providers. Patients can pay for their appointments and other healthcare services directly which makes the payment process more convenient and secure.

Lastly, the functionalities of the portal can be extended to provide:
1.	Online video consultations
2.	Online ordering and delivery of prescribed medicines
3.	Mobile App
4.	Reminders of Regular Health Screenings to facilitate preventive care among citizens
5.	And finally an AI chatbot to make it more interactive for the users.

