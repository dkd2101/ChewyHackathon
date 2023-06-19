# Vet Finder

## Why'd we make this?
This project was completed as a part of [Chewy's 2023 Diversity Hackathon](https://www.builtinboston.com/job/operations/2023-chewy-boston-diversity-hackathon/107313). Teams were tasked to design, build, and present a solution for Chewy users to be able to find local veterinarian clinics nearby and filter clinics by specific criteria such as programs clinics participate in, specialties, animals they treat, etc within a 24 hour. 

## What was our process?
Our team focused heavily on delivering a user experience that would be simple and fast. We went through a few user stories and decided that when looking for a vet, most users may be out without access to a computer. Users may be out walking their dog and run into a emergency or just want to be able to quickly find a vet while away at work. Therefore we wanted to focus on a mobile web-app that would allow users to filter through the provided clinics and find the one that suits them best. 

Our team started with a low fidelity Figma mockup that determined we wanted three endpoints, Searching, Displaying, and Filtering. We decided that we would use React.js and Javascript for our development with CSS and HTML front-end. Our team split up into back-end and front-end teams with our front-end team coming up with a design and developing the CSS and the back-end working on searching the JSON file and connecting to the Google Maps API. 

## What did I learn?
I focused primarily on the backend as well as the front-end and back end connectivity. The time limit as well as the need to create a presentation made us focus our scope and proritize heavily focusing on one feature at a time before moving on. I was able to develop the endpoints, create the searching logic, and connect the front end and back end. I also tried to get the Google Maps API connected with our app but unfortunately was not able to solve the issues in time. We also ran into issues regarding our yarn development versions that taught me to make sure we are all synced up prior to moving forward with our project. Understanding our data is also imperative because I had a bug that prevented me from fitering with our search bar because I made the assumption that names would be unique but that wasn't the case and I had to create a more unique identifier.
