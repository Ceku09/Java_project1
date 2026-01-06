# Java_project1

🍀 Spring Boot Greeting Application

A simple Spring Boot MVC application that demonstrates how to build a dynamic web page using Spring MVC and Thymeleaf.
The application accepts a request parameter from the user and displays a personalized greeting message rendered in an HTML view.

🚀 Technology Stack
	•	Java
	•	Spring Boot
	•	Spring MVC
	•	Thymeleaf
	•	Maven

🎯 Project Purpose

This project is designed to demonstrate the following core Spring Boot concepts:
	•	Creating web controllers using @Controller
	•	Handling HTTP request parameters with @RequestParam
	•	Passing data to the view using the Model object
	•	Rendering dynamic HTML pages with Thymeleaf
	•	Exposing a web endpoint at /greeting

🔗 API Endpoint

GET /greeting

The endpoint accepts an optional name query parameter.

Examples
	•	/greeting?name=Cihan
Output: Hello, Cihan
<img width="1920" height="1043" alt="Ekran Alıntısı2" src="https://github.com/user-attachments/assets/6d4aff63-9a2e-4bac-8eff-f4d47bd9153d" />

	•	/greeting?name= or /greeting
Output: Hello, Vistula!
<img width="1920" height="1040" alt="Ekran Alıntısı" src="https://github.com/user-attachments/assets/bb5b39a7-5a3b-4a56-b706-9c65d17d9d4b" />

