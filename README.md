
# 📅 Absence Manager

The Absence Manager is a SharePoint-integrated application designed to streamline the process of submitting and approving absence requests within an organization.

---

## 🔍 Overview

The Absence Manager allows users to:
- Submit different types of absence requests (e.g., Vacation, Military Service, Sick Leave).
- Track the status of their own requests.
- Approve or reject requests assigned to them as approvers.

The app provides an intuitive and role-based interface where both requestors and approvers can easily manage leave workflows.

---

## 💡 Features

### 🏠 Home Dashboard
- View Vacation Days Left, Requests Sent, and Awaiting Approvals.
- Track all pending requests submitted by the user.
- See all requests pending the user's approval.

### ✅ Request Absences
- Users can submit a new absence request.
- Select Absence Type, From/To dates, Approver, and Deputy.
- Add optional comments for context.

### 📥 Approve Requests
- Approvers see a list of all requests awaiting their action.
- Requests are categorized by type and sorted by date.
- Click Decide to navigate to the decision screen.

### 📝 Approve/Reject Screen
- Approvers can enter comments and choose to Approve or Reject requests.
- Decision triggers a notification or update back to the requestor.

---

## 🛠 Data Source

The app is powered by SharePoint with two custom lists:

1. AbsenceTypes  
   - Stores types of absences (e.g., Vacation, Sick Leave, Military Service).

2. Requests  
   - Stores user-submitted requests including fields like:
     - Requestor
     - Approver
     - Absence Type
     - Start/End Dates
     - Comments
     - Status (Pending, Approved, Rejected)

---

## 📸 Screenshots

![Home Screen](https://github.com/user-attachments/assets/9244ffa7-a630-4079-9c17-a8cc32d6ab21)

![Request Absences Screen](https://github.com/user-attachments/assets/de1078c0-5783-404e-aa8a-3cf4317a48e8)

![Approve Requests Screen](https://github.com/user-attachments/assets/bbcc7577-01fe-48fb-8a33-12175354a0dd)

![Approve Details Screen](https://github.com/user-attachments/assets/550a5bed-6938-409e-8af7-dbfd3efa9c54)




