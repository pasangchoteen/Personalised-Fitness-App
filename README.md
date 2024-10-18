# Personalized Fitness App

## Overview
The Personalized Fitness App aims to provide users with tailored workout plans and nutrition guidance based on their individual fitness goals. This project includes detailed use case and context diagrams that outline the system's functionality and interactions with external entities.

## Diagrams Included
1. **Use Case Diagram**: Visual representation of the interactions between users and the system, highlighting various use cases such as user registration, workout plan generation, and feedback submission.
2. **Context Diagram**: Overview of the system's boundaries and interactions with external entities, illustrating data flows between users, the system, and other components.

## Context Diagram

### Description
The context diagram illustrates the Personalized Fitness App's interactions with external entities, defining its boundaries and data flow.

### External Entities
- **User**: Inputs fitness goals, receives personalized plans, and provides feedback.
- **Nutritionist**: Sends dietary recommendations and receives user updates.
- **Fitness Tracker Device**: Sends workout data for progress tracking.

### Interactions
- **User to App**: Submits goals and receives plans.
- **App to User**: Delivers workout plans and progress updates.
- **Nutritionist to App**: Updates nutritional plans.
- **Fitness Tracker to App**: Sends workout data.

## Use Case Diagram

### Description
The use case diagram outlines the app's functionality by showing interactions between users and the system.

### Actors
- **User**: Manages personal fitness and nutrition.
- **Nutritionist**: Provides dietary guidance.
- **Admin**: Oversees app content and feedback.

### Use Cases
1. **User Registration**: Users create accounts; can recover passwords (extend).
2. **Create Fitness Profile**: Users input goals and metrics.
3. **Generate Workout Plan**: Custom plans are created; includes nutrition recommendations.
4. **Track Progress**: Users log workouts and monitor progress.
5. **Receive Feedback**: Users provide feedback to refine plans.
6. **Join Challenges**: Users participate in fitness challenges for motivation.
7. **Nutrition Update**: Nutritionists adjust dietary plans based on feedback.

### Relationships
- **Include**: Generating workout plans includes nutrition recommendations.
- **Extend**: Password recovery extends user registration.

## Features
- Personalized workout plans based on user input.
- Community challenges to enhance user engagement.
- Feedback mechanism for continuous improvement.

## Future Work
This project serves as a foundational step towards developing the app. Future enhancements may include:
- Building the application based on the defined use cases.
- Implementing user stories and acceptance criteria into the development process.

## Contributing
Contributions are welcome! If you have ideas or suggestions for features, feel free to create an issue or submit a pull request.

## License
This project is licensed under the MIT License.

## Contact
For any inquiries, please contact [Pasang Choteen Sherpa](mailto:pasangchoteensherpacs@gmail.com).
