<img width="382" height="865" alt="image" src="https://github.com/user-attachments/assets/77189d4e-dd8c-43a2-8ce7-666499626f98" />




# 🐾 Animal Quiz App

A fun, interactive mobile application built with React Native. This app tests users' knowledge of animals by displaying images and asking them to identify the correct animal from a dropdown menu. It is designed to be simple, intuitive, and responsive across different device screens.

## Features

*   **Image-Based Questions:** Displays crisp, high-quality images of animals for the user to identify.
*   **Interactive Dropdowns:** Uses a customized Picker component to let users select their answers, including a built-in "Select an item..." placeholder to prevent accidental blank submissions.
*   **Real-Time Memory (State):** Uses React Native's `useState` to track and store the user's selected answers independently for every question.
*   **Instant Scoring:** Contains a built-in answer key that automatically grades the user's selections when they click "Submit".
*   **Alert Feedback:** Provides instant visual feedback by triggering a native pop-up alert displaying the user's final score.
*   **Scrollable Interface:** Wraps the entire layout in a `ScrollView`, guaranteeing that users on smaller screens can easily scroll down to see all questions and the submit button.
