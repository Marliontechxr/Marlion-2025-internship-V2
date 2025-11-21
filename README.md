We are marlion technologies an AI and XR company offering winter internship 2025 to students all over. The goal of this internship is to inculcate training to students in the following 4 cutting edge domains. 1. Immersive tech (AR/VR) 2. Full stack apps (web and mobile). 3. Agentic AI 4. Data science (AI and ML). We dont charge any fees for this internship. The last date for applying to this is 31 Nov 2025.(lets add a countdown timer) Internship commences on 2nd december. We are creating an AI powered student registration, onboarding, learning, progress tracking system that handles end to end operations from offer letter to internship completion certificate. The UX has to be reimagined for an AI first experience for all the features. 

This should be a turbo mono repo with separate student app with current Home Screen and admin app with separate pages both sharing the same source of truth from the convex backend. Also the auth will be handled by firebase and token will be passed to convex to validate user access. Both email and mobile otp feature with sso sign in

Currently just front end for some pages in student app has been done without maintaining turbo mono repo format we also have a couple of pages for admin app but convex backend is yet to be implemented and same goes for firebase aswell. We need to clean up the existing code I already like the visual aesthetic and this has to be preserved for the current pages and future pages we develop

The central theme for this winter internship is about building assistive technologies and IEP for neurodiverse children applying the above mentioned 4 tech streams. 

The duration of internship is upto the discretion of the student and can vary from 2 weeks to 12 weeks.

The office timings are between 10 am to 5 pm and all saturdays will be working days.

We are located in the following address (A-34, Kumarasamy Street, (Opp to Anusha Vidhyalaya matriculation school), Thirunagar 7th Stop, Madurai 625006. (https://maps.app.goo.gl/hKZZX8qByEnqpQqF9)

here are the screens we will have to create for this Mobile responsive PWA web app.

1. A home page with a hero section displaying the CTA message with 2 buttons underneath. Register now , explore topics. A countdown timer below this. Followed by a youtube video (Message from the CEO), then we introduce the theme for this winter internship 2025 and the 4 streams under which we offer it. For all the 4 streams we must have a collapsible interface that expands to show a video explaining what to expect when choosing that given stream. Lets have Login and register buttons on the top right corner aswell.

This will be followed by an Ask AI section where students can get answers to their queries (replacing the conventional FAQ). We will then have office location and contact information (social@marliontech.com. +919486734438) and a link to our corporate site to learn more about us. (https://www.marliontech.com/)

2. Register page shall have sign up with google and standard email/otp or mobile/otp. This shall be followed by a quick form collecting the following info. 1. student name. 2. college ( a dropdown with following options Thiagarajar college of engineering, kamaraj college of engineering, SRMmadurai college of engineering and technology, anna university regional campus (Ramanathapuram), others (please enter)3. year of study (dropdown) 4. department, 5. Internship stream choosen 6. internship start and finish date 7. Any other special requests. upon validating their mail otp or mobile otp and filing these details the user registration will be marked complete. 
3. AI interview dashboard :- After registration the user will be asked to complete a small 5 min interaction with AI. The AI will try to understand the student's passion to undergo this internship and their current level of exposure in acing it. The questions will test both technical acumen and psycological evaluation to see if the candidate is curious and passionate to learn new tech and can be a productive fit for this internship program. There should be a modern chat inteface that is unlike regular AI chatbots. We must show progress meter as the student answers the AI questions. This should be voice first system with a fallback to text based typing. There should be a progress indicator showing percentage complete and when fully complete the AI should generate a short summary of how it went (a score and quantified metric) and what will be the next steps. we must tell the students that their responses are now submitted and they should checkback in 24 hours to download the offerletter if selected.

4. Internship offer letter download: for the selected candidates we must display this page with rules and best practices to be followed during the internship and on clicking i agree should be able to download their offer letters. For candidates rejected in the initial screening we must show a regret message and their app experience ends there.

5. Main dashboard: once the offer letter is downloaded the student must be redirected to a main dashboard which will have the following features built into it. 1. Online bootcamp kit that would contain short video lectures addressing various frameworks and methods the student should be familiar with while coming for their first day of internship. This should have a layout similar to udemy with an AI chat panel built into it for students to get contextual answers to their queries while viewing these lectures. For each module completion there shall be a short AI interaction to test the user's understanding before progressing to the next step. (This similar to inital onboarding interview shall have a voice first with text fall back and we must not explicitly warn but ban user if they copy paste answers with a sarcastic message " we would rather work with the AI directly than collabrating with a human who would mindlessly copy paste AI generated responses" we will also have a link to submit an appeal if the user feels they were wrongly banned. 2. The dashboard will then contain a problem statement tab that will give a detailed brief of what the student is expected to work on with objectives end goals and tech stack with prerequisites. The student can also submit their own proposal by uploading a pdf and explaining their idea in a nutshell in the textbox and we will show the user a message saying they have to check back after 24 hours to see if their problem statement proposal was approved. 3.The next tab will be a project tracker (kanban) that will show the overall WBS milestones and timelines. The student can mark this checklist for review. The student shall also journal their everyday progress with provision to share attachments github url and a description of what was completed in that given day. 4. A help section with ai integration for logging blockers or any other feedbacks during the course of the internship. This dashboard will have a progress meter showing how much percentage of work is left to unlock their internship certificate. 

6. Download certificate and feedback: upon unlocking their completion status to 100 % the student can download a QR verifyable pdf certificate along with an AI summary of their journey at marlion and feedback and future directions.


This project will have a turbo monorepo structure. all the detailed given above for the student app. Now we will also have an admin app to run this whole process. both apps access the same source of truth as backend. 

For admin app we have login with email and password (no signup) followed by following features
t shall have the following features.

. dashboard to view list of registered students with activity logs
2. Student's video course completion performance and AI's evaluation of their submissions with filters for semantic search and sorting by marks, college etc.
3.CMS for course structure headings and respective uploads of video URL along with provisions to create an AI summary so that the AI can shoot questions or answer questions relavant to the uploaded video. 
4. Student selection process where they review the AI assessments and either select or reject the student which then gets published as results to the selected students along with mail.
5. Provision for uploading project problem statements and respective learning references and docs. 
6, provision to assign the selected students to any of the projects in the available project list
7. Provision to track everyday work progress and intervene with personal messages as and when required
8. Provision to make announcements and moderate community discussions.
9. provisions to remove any student from the internship based on lack of conduct or performance.
10. to verify student status such as certificate issued.,
11. To view student's feedbacks in table with semantic AI features.

build this entirely production ready with no hardcoded mock data stuffing
