# University of Manitoba Parking Portal

**A user-centric parking portal prototype — designed, developed & evaluated with human-computer interaction principles**

This project was created as part of a Human–Computer Interaction course to demonstrate user-centered design, heuristic evaluation, and interactive interface development. 
The Parking Portal enables students, staff, and visitors to explore parking options and visualizations for campus lots, with tailored experiences based on user roles.

---

## Project Overview

Campus parking at the University of Manitoba is complex and competitive — students and staff often struggle to secure spots and manage permits efficiently. This prototype addresses these challenges by:

* Presenting a **role-based parking dashboard** for *students, staff, and visitors*
* Demonstrating **clear visualization of available parking lots**
* Applying **UX heuristics** to optimize usability and navigation
* Prioritizing **accessibility, clarity, and interaction design**

> This is a *vertical prototype* focusing on core user experiences, not a production system.

---

## Key Features

### Role-Based Access

Different UI experiences based on user type:

| Role          | Access                 |
| ------------- | ---------------------- |
| Student       | Student + Visitor lots |
| Staff         | Staff + Visitor lots   |
| Guest/Visitor | Visitor lots only      |

> Sample credentials for evaluation/testing (provided in project materials)

---

### Parking Lot Visualization

Interactive exploration of select parking lots (e.g., N, Q, U, P, K, and Parkade), with metadata for each lot that reflects real-world considerations like availability and permit applicability.

---

## User-Centered Design Principles

This project applies:

* **Heuristic Evaluation** — ensuring intuitive navigation and task completion
* **Consistency & Standards** — aligning labels and UI flows with user expectations
* **Feedback & Error Prevention** — clear indicators for actions and transitions

These practices help transform a traditionally frustrating campus process into a learnable, predictable experience.

---

## Technologies

| Aspect    | Details                                          |
| --------- | ------------------------------------------------ |
| Front-end | HTML, CSS, JavaScript                            |
| Data      | Local JS for simulated parking information     |
| UX Focus  | User flows, interaction states, visual hierarchy |

---

## Getting Started

To run this prototype locally:

1. **Clone the repo**

   ```bash
   git clone https://github.com/JeromeDeGuz/UofManitoba-ParkingPortal.git
   cd UofManitoba-ParkingPortal
   ```
2. **Open in browser**
   Simply open `index.html` in a modern web browser.
3. **Explore UI**

   * Login as *student*, *staff*, or *visitor*
   * Navigate the lot interface
   * Observe UI behavior and user flows

*No backend or server is required.*

---

## Example User Credentials for Evaluation

| Role    | Email                    | Password |
| ------- | ------------------------ | -------- |
| Student | `student@myumanitoba.ca` | `1234`   |
| Staff   | `staff@myumanitoba.ca`   | `abcd`   |
