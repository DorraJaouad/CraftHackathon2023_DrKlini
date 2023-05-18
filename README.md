# CraftHackathon2023_DrKlini

# Introduction 

DrKlini is a mobile application that efficiently assigns patients to medical facilities in Hungary based on their case priority. By seamlessly integrating an AI chatbot and a dynamic booking system, high-priority patients with conditions like pleurisy or acute myocardial infarction (heart attack) receive prompt attention and care.


#  Services

**Medical Chatbot with categorization functionality**

LLM chatbots: link to ADA chatbot

Our application utilizes the powerful ADA chatbot to effectively gather key symptoms from patients and accurately categorize their case as high, medium, or low priority. This categorization plays a crucial role in dispatching patients to the appropriate medical facility at the right time. Following the chatbot conversation, users are provided with self-action recommendations and/or redirected to the booking system. In urgent situations, the system promptly alerts the user to seek emergency medical assistance. 

**dynamic Booking system**

a- Data source
The Database: the project won't need an excessive workload on the data collection. It will link EESZT database and extracts the needed information such as medical records, prescriptions and prospected controls  and also the data related to the medical equipments distribution and healthcare amenities capacities in Hungary.

b- The Dispatching process
We call this process Delta and it depends on the label output
<img width="3923" alt="Untitled (1)" src="https://github.com/DorraJaouad/CraftHackathon2023_DrKlini/assets/84044328/173a0362-e6c9-4baa-a47f-5b5ef37a5808">

c- Post booking 
We provide a cool feature to the patient upon booking information
The location guide: Menetrendek [ UI Screen ]

**Clinical Interaction**

a- Pharmacy ( stock checking ) 
b- Diagnostic Tests ( Booking not yet done diagnostic, Reviewing past diagnostics ) 
c-  Medical Checkup 
( previous dates, next checkups) 

**Medical records with dates**
The patient will have access to the past medical explorations such as CT and blood test. He will see other charachteristics such as chronic illness, smoking habits, bone injury ..

# Current solutions in the market

The most potential market adverse to our application is the EEESZT application. We can say that DrKlini is a better version of EEESZT as it provides the AI medical Chatbot with a dynamic booking system to accommodate the emergency of patient cases. The waiting time will be substantially less by efficiently striking a balance between the extent of urgency and the medical machine's availability.

# Future ideas 

With such immense data on the demand distribution captured by the AI model and via the user interaction with the app, statistics can be aggregated to guide the reallocation of medical amenities throughout Hungary. Nevertheless,
