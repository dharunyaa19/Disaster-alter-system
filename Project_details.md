# Disaster Alert System

## Project Title
Disaster Alert System

## Problem Statement
Natural disasters such as floods, earthquakes, cyclones, and heavy rainfall can cause significant damage to life and property. Many people do not receive timely warnings, which increases the risk during emergencies. A system is needed to provide quick and reliable disaster alerts to help people take preventive actions.

## Project Objective
The main objective of this project is to provide timely disaster alerts and emergency notifications to users. The system helps people stay informed about potential disasters and supports better preparedness and safety measures.

## Project Description
The Disaster Alert System is a Python-based application designed to monitor disaster-related information and notify users about potential threats. The system provides alerts for disasters such as floods, earthquakes, cyclones, and heavy rainfall. By delivering early warnings, the application helps users take necessary precautions and reduce risks during emergency situations.

## Features
- Real-time disaster monitoring
- Early warning notifications
- User-friendly interface
- Fast information delivery
- Emergency preparedness support

## Scope of the Project
- Monitor disaster-related information
- Generate alert notifications
- Display warning messages to users
- Improve public awareness and safety

## Software Requirements
- Python 3.x
- Visual Studio Code
- Tkinter
- SQLite Database

## Hardware Requirements
- Computer/Laptop
- Internet Connection
- Minimum 4 GB RAM

## Modules List
1. User Management Module
2. Disaster Monitoring Module
3. Alert Generation Module
4. Notification Module
5. Report Management Module

## Model List
1. User Model
2. Disaster Model
3. Alert Model
4. Notification Model
5. Report Model

## Table List

### User Table
| Field Name | Data Type |
|------------|-----------|
| user_id | Integer |
| name | Varchar |
| email | Varchar |
| phone | Varchar |

### Disaster Table
| Field Name | Data Type |
|------------|-----------|
| disaster_id | Integer |
| disaster_type | Varchar |
| location | Varchar |
| severity | Varchar |
| date | Date |

### Alert Table
| Field Name | Data Type |
|------------|-----------|
| alert_id | Integer |
| disaster_id | Integer |
| message | Text |
| alert_time | DateTime |

### Notification Table
| Field Name | Data Type |
|------------|-----------|
| notification_id | Integer |
| user_id | Integer |
| alert_id | Integer |
| status | Varchar |

### Report Table
| Field Name | Data Type |
|------------|-----------|
| report_id | Integer |
| disaster_id | Integer |
| description | Text |
| created_date | Date |

## Expected Outcome
The system will provide early disaster warnings and emergency alerts, helping users take safety measures and reduce the impact of disasters.

## Conclusion
The Disaster Alert System improves disaster preparedness by providing timely alerts and important information to users. It contributes to public safety and effective emergency response.
