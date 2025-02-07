# Radiation Therapy Decision Support (RTDS)

RTDS aims to streamline the process of and reduce the time it takes to create a radiation therapy treatment plan.
This project was created by Trent Benedick and contributed to by myself and the team at the USC Image Processing and Informatics Laboratory.
Unfortunately, the repository is private and cannot be shared.

## Tech Stack

Python, Django, MySQL, Docker

## How does it work?

It uses a similarity heuristic to compare a current planning case to historical case data.
Using the similarity metric, the app will sort all historical cases by proximity to the current planning case and show the most similar cases.
Radiologists can then take these plans and use them as reference when planning the treatment for the patient.

All case data is anonymized and stored in a MySQL database hosted on Docker.
The user interface is HTML5/CSS3 web-based and is powered by a Django framework backend.
The similarity heuristic is calculated in a Python backend.
