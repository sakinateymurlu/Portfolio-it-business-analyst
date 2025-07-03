# 💼 Sakina Teymurlu – IT Business Analyst Portfolio Case

## 🧩 Case Title:
*Balance Visibility Toggle Feature*  
Simulated case study based on real customer interaction from the banking sector.

---

## 🔍 Context:
While working in customer service at a bank, a client asked if it was possible to hide their card balance when opening the mobile app in public.  
This sparked the idea to create a real-world inspired business analysis case.

---

## 👤 Role:
- Requirement gathering from client feedback  
- Writing User Story and Acceptance Criteria  
- Structuring documentation and sprint planning  
- Simulating Jira-based task setup  
- BI collaboration simulation  
- SQL usage for usage analysis

---

## 🧠 Problem Statement:
Customers may feel uncomfortable when their card balance is instantly visible upon opening the mobile banking app in public.  
This can lead to unintentional data exposure and weakens user experience.

---

## ✅ Proposed Solution:
Add a toggle feature on the home screen that allows users to hide or show their balance.  
The toggle should remember the user's choice and default to that in the future.

---

## ✍️ User Story:

*EN:*  
As a mobile banking user,  
I want to be able to hide my card balance on the home screen,  
So that I can protect my financial privacy in public environments.

*AZ:*  
Mən bank müştərisi kimi,  
mobil tətbiqə daxil olarkən kartdakı balansımın ekranda görünməsini gizlətmək istəyirəm,  
belə ki, ətrafımda kənar şəxs olarsa, balansımın dərhal görünməsini istəmirəm.

---

## 🎯 Acceptance Criteria:

| # | Acceptance Condition |
|---|-----------------------|
| 1 | "Hide/Show Balance" toggle appears on the home screen |
| 2 | Toggle activates/deactivates by user tap |
| 3 | When hidden, balance is masked as "**" |
| 4 | User's selection is saved in profile preferences |
| 5 | Selected state applies every time app is opened |

---

## 🛠️ Simulated Jira Task

- *Title:* Balance Hide Feature  
- *Type:* User Story  
- *Priority:* Medium  
- *Label:* mobile, security  
- *Assignee:* Frontend Developer  
- *Sprint:* Sprint 3 – UI Enhancements  
- *Story Points:* 3

---

## 💡 SQL Usage Example

```sql
SELECT user_id, COUNT(*) as usage_count
FROM balance_hide_logs
WHERE action = 'hide'
GROUP BY user_id
ORDER BY usage_count DESC;

![User Story Screenshot](user-story-example.png)
