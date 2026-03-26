# Job-tracker
Job Tracker is a simple, interactive web application designed to help users track their job applications. Users can add, edit, delete, and search job entries with relevant details, including company, role, status and notes. The project emphasizes client-side persistence using localStorage, dynamic DOM manipulation and a clean, responsive UI

## Features
### 1. Add, Edit, and Delete Jobs
- Users can add new job entries with:
  - Company name  
  - Role/Position  
  - Status (Applied, Interview, Offer, Rejected)  
  - Notes  
- Jobs can be updated or removed with a single click.

### 2. Search Functionality
- Real-time search filters jobs by company or role  
- Implemented using JavaScript string matching:
```javascript
job.company.toLowerCase().includes(query) || job.role.toLowerCase().includes(query)

### 3. Persistent Storage
All job entries are saved in localStorage
Data persists after browser reload

### 4. UI/UX Design
Clean, modern, and responsive layout
Interactive elements (hover effects, buttons)
User-friendly form and table interface

### 5. Technologies Used
Languages: HTML, CSS, JavaScript (ES6)
Persistence: localStorage
Design: Flexbox, responsive CSS
Tools Used
VS Code – code editor
Live Server – run the app locally
Chrome  – debugging and inspecting UI
Git & GitHub – version control and repository management
