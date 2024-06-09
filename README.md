# AI Chat Application

This project is a ReactJS web application that allows users to chat with an AI model and provide feedback at each stage of the conversation. Users can like/dislike AI model's answers, give a rating out of 5, and provide subjective feedback. The application also supports saving and revisiting past conversations, as well as viewing and filtering feedback points across conversations.

## How to Start the Service and Use the Application

1. Clone this repository to your local machine.
2. Navigate to the project directory in your terminal.
3. Install dependencies using `npm install` or `yarn install`.
4. Run the application using `npm start` or `yarn start`.
5. Access the application in your browser at [http://localhost:3000](http://localhost:3000).

## Reasoning Behind Technical Choices

### Libraries Used:
- **ReactJS**: Chosen for building user interfaces with reusable components and managing state efficiently.
- **Material-UI**: Used for UI components and theming to achieve a modern and responsive design.
- **React Router**: Implemented for routing between different views and managing application navigation.
- **React Hook Form**: Utilized for form handling and validation to improve user experience.
- **React Icons**: Included for easy integration of icon components throughout the application.
- **React Toastify**: Added for displaying notifications to the user for actions such as liking/disliking and submitting feedback.
- **Mock Service Worker (MSW)**: Employed for mocking API requests and responses during development and testing.

### Reasoning Behind Design Choices

#### UI/UX Design:
- **Clean and Minimalistic**: Prioritized simplicity and clarity in design to enhance user experience and readability.
- **Responsive Layout**: Implemented a responsive design to ensure compatibility and usability across various devices and screen sizes.
- **Color Scheme**: Selected a neutral color palette with contrasting accents to maintain readability and visual hierarchy.
- **Floating Buttons**: Implemented floating thumbs-up and thumbs-down buttons for liking/disliking AI responses, providing intuitive feedback options.

## Trade-offs and Future Considerations

- **Dark Mode**: While dark mode is a desirable feature for user customization, it was left out due to time constraints. However, it can be implemented in future iterations to enhance accessibility and user preference.
- **Real-time Chat**: Implementing real-time chat functionality with WebSocket or a similar technology could provide a more dynamic user experience. This was left out for simplicity in the initial version but could be considered for future enhancements.
- **Localization**: Supporting multiple languages for the UI text could improve accessibility and user reach. This was not implemented in the current version but can be added in future iterations.
- **Automated Testing**: Although the codebase is modular and testable, comprehensive automated testing (unit tests, integration tests) was not included in the initial version due to time constraints. Adding tests would improve code quality and maintainability.

## Additional Notes

- The application was developed with a focus on code readability, modularity, and extensibility to facilitate future enhancements and maintainability.
- UI/UX design choices were made with usability and accessibility in mind, aiming to provide a seamless and intuitive user experience.
- Feedback and suggestions for improvement are welcome and can be addressed in future iterations of the application.
