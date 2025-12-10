| Data Variable               | Type (Quant/Qual)          | Unit/Scale                          | Frequency of Collection           | Tool/App                         |
|-----------------------------|-----------------------------|--------------------------------------|-----------------------------------|----------------------------------|
| Attendance_Status (Target) | Qualitative (Binary)        | Show / No-Show                       | Per appointment                   | Clinic Schedule Sheet            |
| Appointment_Start_Time_24h | Qualitative (Ordinal)       | Time                                 | Per appointment                   | Clinic Schedule Sheet            |
| Appointment_End_Time_24h   | Qualitative (Ordinal)       | Time                                 | Per appointment                   | Clinic Schedule Sheet            |
| Duration_Minutes           | Quantitative                | Minutes                              | Per appointment                   | Derived from schedule            |
| Day_of_the_Week            | Qualitative (Nominal)       | Monday–Sunday                        | Per appointment                   | Derived from date                |
| Service_Type               | Qualitative (Nominal)       | OT / ST                              | Per appointment                   | Clinic Schedule Sheet            |
| Has_Down_Payment           | Qualitative (Binary)        | Yes / No                             | Per appointment                   | Clinic Schedule Sheet            |
| Down_Payment_Amount        | Quantitative                | PHP                                  | Per appointment                   | Clinic Billing Sheet             |
| Payment_Status             | Qualitative                 | Updated / Arrears                    | Per appointment                   | Clinic Billing Sheet             |
| Payment_Method             | Qualitative (Nominal)       | Cash / GCash / Bank                  | Per appointment                   | Clinic Billing Sheet             |
| Age                        | Quantitative                | Years                                 | Once; updated yearly              | Client Information Sheet         |
| Age_Group                  | Qualitative (Ordinal)       | Toddler / Pre-school / School-age    | Once; updated yearly              | Derived from Birthdate           |
| Gender                     | Qualitative (Nominal)       | Male / Female                        | Once                              | Client Information Sheet         |
| Diagnosis                  | Qualitative (Nominal)       | ASD, GDD, Speech Delay, etc.         | Once; updates as needed           | Client Information Sheet         |
| Distance_km                | Quantitative                | Kilometers                           | Once; address changes             | Derived via mapping              |
| Distance                   | Qualitative (Ordinal)       | Near / Moderate / Far                | Once; address changes             | Derived from Distance_km         |
| Is_Holiday                 | Qualitative (Binary)        | Yes / No                             | Daily                             | PH Government Holiday Calendar   |
| Holiday_Type               | Qualitative (Nominal)       | Regular / Special / Long Weekend     | Daily                             | PH Government Calendar           |
| Is_Typhoon_Risk            | Qualitative (Binary)        | Yes / No                             | Daily                             | PAGASA Advisories                |
| Typhoon_Signal_Level       | Qualitative (Ordinal)       | Signal 0–5                           | Daily                             | PAGASA Signals                   |
| Is_Rainy_Season            | Qualitative (Binary)        | Yes / No                             | Monthly                           | PH Climate Classification         |
| Prev_Cancel                | Qualitative (Binary)        | Yes / No                             | Per appointment                   | Derived from history             |
| Lead_Time_Days             | Quantitative                | Days between booking & appointment   | Per appointment                   | Derived from booking logs        |
| Reminder_Sent              | Qualitative (Binary)        | Yes / No                             | Per appointment                   | SMS logs                         |
| Reminder_Time_Lag          | Quantitative                | Hours before appointment             | Per appointment                   | Derived from reminder logs       |
