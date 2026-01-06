# FitActive Gym Database Project
<img width="593" height="310" alt="image" src="https://github.com/user-attachments/assets/d7d4f68e-3ab1-4e15-a227-3374f8146221" />

---

## Project Overview

FitActive Gym is a modern fitness facility offering personalized training and diverse subscription packages. This database project models the gym’s operations, including:

- Members and their subscriptions  
- Trainers and their customized exercise routines  
- Teams for sports and their member participation  
- Payments and invoices  

The database allows the gym to manage memberships, routines, trainers, team sports, and payments efficiently.

---

## ER Diagram

The conceptual design of the database is represented in the **ER Diagram**:

<img width="676" height="758" alt="image" src="https://github.com/user-attachments/assets/20491ef4-5dcf-4fe7-b51f-6dbc929decba" />


**Entities include:** Member, Trainer, Routine, Exercise, Package, Team, Payment, and relationships among them.

---

## Relational Model

The database was implemented in SQL with the following tables:

- **Member** – stores member information  
- **Trainer** – stores trainer information  
- **Exercise** – catalog of exercises  
- **Routine** – customized exercise routines  
- **RoutineDetail** – links routines with exercises  
- **Package** – subscription packages  
- **MemberPackage** – links members to packages  
- **Team** – sports teams led by trainers  
- **TeamMember** – links members to teams  
- **Payment** – records member payments  

---

## Folder Structure

