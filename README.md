# CraftHackathon2023_DrKlini

# Introduction 

DrKlini is a mobile application that efficiently assigns patients to medical facilities in Hungary based on their case priority. By seamlessly integrating an AI chatbot and a dynamic booking system, high-priority patients with conditions like pleurisy or acute myocardial infarction (heart attack) receive prompt attention and care.


#  Services

**Medical Chatbot with categorization functionality**

LLM chatbots: link to ADA chatbot

Our application utilizes the powerful ADA chatbot to effectively gather key symptoms from patients and accurately categorize their case as high, medium, or low priority. This categorization plays a crucial role in dispatching patients to the appropriate medical facility at the right time. Following the chatbot conversation, users are provided with self-action recommendations and/or redirected to the booking system. In urgent situations, the system promptly alerts the user to seek emergency medical assistance. 

**Dynamic Booking system**

# Data Source

The DrKlini project leverages the EESZT database as the primary data source. This eliminates the need for extensive data collection efforts. The application extracts relevant information such as medical records, prescriptions, prospective controls, as well as data pertaining to the distribution of medical equipment and the capacity of healthcare facilities in Hungary.

# Dispatching Process

We have named the dispatching process "Delta," which operates based on the label output. The label categorization of a patient's case (high, medium, or low priority) determines the appropriate dispatching action. Please refer to the following diagram for an overview of the Delta process:

![Dispatching Process](https://github.com/DorraJaouad/CraftHackathon2023_DrKlini/assets/84044328/173a0362-e6c9-4baa-a47f-5b5ef37a5808)

# Post Booking

After a successful booking, we offer an exciting feature to the patient:

**Location Guide: Menetrendek**

This feature provides a convenient location guide for patients. It assists them in finding the necessary information related to schedules, routes, and transportation options.


**Clinical Interaction**

a- Pharmacy ( stock checking ) 

b- Diagnostic Tests 

Once the doctor examines the patient and prescribes an exploration to do , it will be recorded in the patient's record hence rendered on the app.
Patients can book diagnostic tests directly through the application. Additionally, they have the option to review their past diagnostic results. This empowers patients to stay informed about their health status and track their progress.

c-  Medical Checkup 
The application provides information on previous medical checkups, including the dates of those checkups. Patients can also view upcoming checkup dates to stay proactive about their healthcare.

**Medical records**

patients can view additional characteristics such as chronic illnesses, smoking habits, and past bone injuries. This enables patients to have a comprehensive overview of their medical history and make more informed healthcare decisions.

# Current solutions in the market

The most potential market adverse to our application is the EEESZT application. We can say that DrKlini is a better version of EEESZT as it provides the AI medical Chatbot with a dynamic booking system to accommodate the emergency of patient cases. The waiting time will be substantially less by efficiently striking a balance between the extent of urgency and the medical machine's availability.

# Future ideas 

With such immense data on the demand distribution captured by the AI model and via the user interaction with the app, statistics can be aggregated to guide the reallocation of medical amenities throughout Hungary. Nevertheless,