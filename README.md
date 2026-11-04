# Rhetorix Official Website  
The official platform for **Rhetorix**, a youth-led initiative founded in 2025 to uplift India’s overlooked expressive disciplines, including public speaking, debates, group discussions, elocution, and cultural articulation.  
This website powers **Prastavana Conclave**, the premier committee-based debating competition hosted at Prelude Public School, Agra.

- https://rhetorix.in
- https://rhetorix-ddda0.web.app/ (if rhetorix.in doesn't work)

# This Repository

This repository contains the source code of the Rhetorix website as it existed before **Prastavana Conclave 2.0**, with a particular focus on the delegate registration form and its backend logic. The multi-step form handled applicant information, committee preferences, conditional registration requirements, fee calculation, and payment submission. It integrated **Cloudinary** for uploading and managing payment proof images and **Firebase Firestore** for storing registration data. The implementation connected these services to create a registration workflow in which uploaded payment documents and submitted delegate information were handled by their respective services. This repository preserves the earlier implementation of the website and documents the registration system used during that period. 

Since then, the website has been updated, the following sections were added or updated: 
- Magazine
- Founder's Desk
- Events
- Highlights

and the Form section has been removed, as well the pop-up. 

The site is also being transitioned from a SPA to an MPA, some functional pages currently are:
- https://rhetorix.in/magazine.html
- https://rhetorix.in/mission.html

# Prastavana Conclave 2.0 Form Logic

![Diagram explaining the form logic](Prastavana%20Conclave%20Registration%20Logic.png)
