---
title: My Experience with the 2021 NASA Space Apps Hackathon
excerpt: I recently completed the 2021 NASA Space Apps Pasadena Hackathon.
date: '2021-10-24'
thumb_image: images/portfolio4.png
thumb_image_alt: A website with a map
image: images/portfolio4.png
image_alt: A website with a map
seo:
  title: My Experience with the 2021 NASA Space Apps Hackathon
  description: I recently completed the 2021 NASA Space Apps Pasadena Hackathon.
  extra:
    - name: 'og:type'
      value: article
      keyName: property
    - name: 'og:title'
      value: My Experience with the 2021 NASA Space Apps Hackathon
      keyName: property
    - name: 'og:description'
      value: I recently completed the 2021 NASA Space Apps Pasadena Hackathon.
      keyName: property
    - name: 'og:image'
      value: I recently completed the 2021 NASA Space Apps Pasadena Hackathon.
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: My Experience with the 2021 NASA Space Apps Hackathon
    - name: 'twitter:description'
      value: I recently completed the 2021 NASA Space Apps Pasadena Hackathon.
    - name: 'twitter:image'
      value: I recently completed the 2021 NASA Space Apps Pasadena Hackathon.
      relativeUrl: true
template: post
---

I recently completed the 2021 NASA Space Apps Pasadena Hackathon. https://spaceapps-pasadena.netlify.app/
Participants formed in teams of 2-6 and solve challenges submitted by NASA personnel over a 48-hour period.


My team chose the Leveraging AI/Machine learning for Plastic Marine Debris. https://2021.spaceappschallenge.org/challenges/statements/leveraging-aiml-for-plastic-marine-debris/details
Our task was to leverage geospatial technology and apply AI/ML capabilities to monitor, detect and quantify plastic marine debris.


I handled 90% of the frontend web app while the rest of the team handled the machine learning backend algorithm and API.
I used React Leaflet to create a map that could take in the endpoints from the backend and display them on a map.
Initially I used data from Tesla Superchargers to demonstrate how to use the map and used that data to assist with designing the endpoints that the rest of the team built for the API.

Towards the end of the challenge I ran into an issue where Netlify (the host for the frontend) wouldn't build the project anymore even though locally it was building fine.
I finally realized that it was treating warnings as actual errors due to a couple React components not being imported correctly.
I fixed that issue and it started to build online properly.


The final result can be seen here: https://lilo-plastic-map.netlify.app/ and our team came in **2nd place** for Pasadena and became a Global Nominee! 
You can find out more about our project here: https://2021.spaceappschallenge.org/challenges/statements/leveraging-aiml-for-plastic-marine-debris/teams/team-lilo/project

Here's an overview video of our project: https://www.youtube.com/watch?v=qMMHzbr-fyo 
