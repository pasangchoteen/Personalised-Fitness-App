# Personalized Fitness App

## Overview
The Personalized Fitness App aims to provide users with tailored workout plans and nutrition guidance based on their individual fitness goals. This project includes detailed use case and context diagrams that outline the system's functionality and interactions with external entities.

## Diagrams Included
1. **Use Case Diagram**: A visual representation of the interactions between users, fitness trainers, nutritionists, smart devices, and the system, highlighting various use cases such as user registration, workout plan generation, and feedback submission.
2. **Context Diagram**: An overview of the system's boundaries and interactions with external entities, illustrating data flows between users, the system, and other components.

## Project Structure
- **Diagrams**
  - `context_diagram.png`: Contains the context diagram.
  - `use_case_diagram.png`: Contains the use case diagram.

## Context Diagram
![Context Diagram](Diagrams%20of%20PFA/ContextDiagram.png)
### Description
The context diagram illustrates the Personalized Fitness App's interactions with external entities, defining its boundaries and data flow.

### External Entities
- **Users:** Input training programs, log workouts, and nutrition; receive personalized plans and notifications.
- **Fitness Trainers:** Provide input on client progress and access user reports.
- **Nutritionists:** Input meal plans, provide feedback on diets, and access user reports.
- **Smart Devices:** Send real-time data on user activities and sync workout information.

### Interactions
- **Users to App:** Log workouts and nutrition; receive personalized workout and nutritional plans.
- **App to Users:** Provides real-time notifications about fitness goals and alerts.
- **Fitness Trainers to App:** Input training programs and access user workout reports.
- **Nutritionists to App:** Input meal plans and access user diet reports, providing feedback for improvements.
- **Smart Devices to App:** Sync data for real-time tracking of user activities.

## Use Case Diagram
![Use Case Diagram](Diagrams%20of%20PFA/UseCase.png)
### Description
The use case diagram outlines the app's functionality by showing interactions between users, fitness trainers, nutritionists, smart devices, and the system.

### Actors
- **User:** Manages personal fitness and nutrition.
- **Fitness Trainer:** Provides guidance on workout techniques and program adjustments.
- **Nutritionist:** Offers dietary recommendations.
- **Smart Device:** Syncs data and tracks user workouts.

### Use Cases
1. **User Registration:** Users create accounts; can recover passwords (extend).
2. **Create Fitness Profile:** Users input goals and metrics.
3. **Generate Workout Plan:** Custom plans are created; includes nutrition recommendations.
4. **Log Workout:** Users log their workouts and track their progress.
5. **Track Progress:** Users monitor their progress and receive notifications.
6. **Receive Recommendations:** Nutritionists provide dietary suggestions based on user data.
7. **Input Meal Plan:** Users can enter their meal plans and nutritional info.
8. **Sync Data:** Smart devices sync workout data; includes options for manual entry.
9. **Provide Feedback:** Users give feedback on their plans and trainers.

### Relationships
- **Include:** 
  - Generating workout plans includes adding nutritional info.
- **Extend:** 
  - Password recovery extends user registration.
  - Syncing data may extend to display errors if issues occur.
  - Logging workouts extends to provide manual entry options if automatic tracking fails.
  - Progress notifications may extend if users meet specific milestones.
  - Request for additional insights extends for far more detailed feedback.

## Conclusion
These diagrams collectively depict the Personalized Fitness App's environment and user interactions, aiding in requirements gathering and development planning.

## Features
- Personalized workout plans based on user input.
- Guidance from nutritionists and fitness trainers.
- Integration with smart devices for tracking progress and syncing data.

## Future Work
This project serves as a foundational step toward developing the app. Future enhancements may include:
- Building the application based on the defined use cases.
- Implementing user stories and acceptance criteria into the development process.

## Contributing
Contributions are welcome! If you have ideas or suggestions for features, feel free to create an issue or submit a pull request.

## License
This project is licensed under the MIT License.

## Contact
For any inquiries, please contact [Pasang Choteen Sherpa](mailto:pasangchoteensherpacs@gmail.com).
