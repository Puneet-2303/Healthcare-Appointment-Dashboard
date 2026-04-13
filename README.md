# Healthcare Appointment Dashboard — Power BI

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?logo=powerbi)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Domain](https://img.shields.io/badge/Domain-Healthcare%20Analytics-blue)
![AI](https://img.shields.io/badge/AI-Claude%20via%20MCP-purple)

## Project Overview

An interactive 3-page Power BI dashboard analysing 20,000 healthcare appointments. Features an embedded AI chatbot powered by Claude AI connected via MCP (Model Context Protocol), providing live insights directly inside the dashboard.

---

## Dashboard Pages

### 1. Overview
- 8 KPI cards: Total Appointments, Completed %, Cancellation Rate, No Show Rate, Active Doctors
- - Average Wait Time by Month (Area Chart)
  - - Appointments by Department and Status (Column Chart)
    - - Appointment by Time Slot (Clustered Column)
      - - Cancellations by Reason (Column Chart)
        - - Appointment Status split (Donut Chart)
         
          - ### 2. Doctors
          - - Top 10 Doctors by Appointment Volume (Bar Chart)
            - - No Show Rate by Doctor (Clustered Bar)
              - - Doctors by Status (Donut Chart)
                - - Pivot Table performance summary
                  - - 8 KPI cards including Cancellation Rate and Active Doctors
                   
                    - ### 3. Patients
                    - - 6 KPI cards: Total Patients, Avg Age, New vs Repeat Patients, Most Common Illness, Registered This Year
                      - - Patients by Age Group, Marital Status, Chronic Illness (Column Charts)
                        - - Patient Registration Trend (Line Chart)
                          - - Marital Status breakdown (Donut Chart)
                           
                            - ---

                            ## What Makes This Project Special

                            ### AI Chatbot inside Power BI
                            Embedded a live Claude AI chatbot directly into the dashboard using an HTML visual. The chatbot calls the Anthropic API and has your actual dashboard data baked in — users can ask questions without ever leaving Power BI.

                            ### MCP Integration
                            Used Model Context Protocol (MCP) to bridge Claude AI with Power BI Desktop, enabling live semantic model access and AI-powered analytics.

                            ### Advanced DAX Measures (32 total)
                            - Year-over-Year appointment comparison
                            - - Dynamic time slot grouping (SWITCH logic)
                              - - Average wait time using AVERAGEX + DATEDIFF
                                - - Dynamic illness descriptions using SELECTEDVALUE
                                  - - Age group segmentation with live DATEDIFF from TODAY()
                                   
                                    - ### Custom Visuals Used
                                    - Gantt Chart, Calendar Visual, Word Cloud, Charticulator, HTML Content Viewer, Power KPI Matrix, LLM Chart
                                   
                                    - ---

                                    ## Tools and Technologies

                                    | Tool | Purpose |
                                    |------|---------|
                                    | Power BI Desktop | Dashboard development |
                                    | DAX | 32 calculated KPIs and measures |
                                    | Power Query | Data transformation |
                                    | Claude AI (Anthropic) | Embedded AI chatbot |
                                    | MCP | AI to Power BI connection |
                                    | Custom Visuals | Enhanced interactivity |

                                    ---

                                    ## Files Included

                                    | File | Description |
                                    |------|-------------|
                                    | Healthcare_Appointment_Dashboard.pbix | Main Power BI file |
                                    | README.md | Project documentation |

                                    ---

                                    ## How to Use

                                    1. Download the .pbix file
                                    2. 2. Open in Power BI Desktop (free from Microsoft)
                                       3. 3. Navigate between Overview, Doctors, and Patients pages
                                          4. 4. Use the AI chatbot to ask questions about the data
                                             5. 5. Apply slicers and filters to explore interactively
                                               
                                                6. ---
                                               
                                                7. ## Author
                                               
                                                8. Puneet — Business Analysis Student
                                                9. LinkedIn: https://www.linkedin.com/in/puneetp06
                                                10. 
                                                ---

                                                ## License

                                                This project is for educational and portfolio purposes only.
