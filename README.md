# TaskMaster

**TaskMaster** is a mobile application powered by React Native designed to elevate productivity and organization levels through a secure and intuitive task management system. Leveraging biometric authentication, real-time location services, and image attachment capabilities for tasks, TaskMaster transcends conventional task management to aid in streamlining daily activities more effectively and securely.

## Key Features

- **Biometric Authentication**: Secure access to tasks utilizing Expo's `LocalAuthentication`.
- **Real-Time Location Services**: Integration of Expo's `Location` API to append real-time location data to tasks, adding meaningful context.
- **Image Attachments**: Capability to enrich task details by attaching images via Expo's `ImagePicker`.
- **Seamless Navigation**: Utilization of React Navigation for smooth transitions across various screens within the app.

## Getting Started

Follow these instructions to get a local copy of the project up and running for development and testing purposes.

### Prerequisites

- Node.js
- npm or Yarn
- Expo CLI

### Setup

1. Clone the repository:

    ```sh
    git clone https://github.com/<your-username>/TaskMaster.git
    ```

2. Navigate to the project directory:

    ```sh
    cd TaskMaster
    ```

3. Install dependencies:

    Using npm:

    ```sh
    npm install
    ```

    Or using Yarn:

    ```sh
    yarn
    ```

4. Launch the development server:

    ```sh
    expo start
    ```

    This action will open the Expo Developer Tools in your default web browser, enabling you to run the app on an iOS or Android simulator, or directly on your physical device via the Expo Go app.

## Usage Guide

- Securely access your task list using your device's biometric features.
- Effortlessly create, modify, and oversee your daily tasks.
- Enhance tasks with images and location tags for additional context.
- Navigate the app smoothly thanks to an intuitive UI design.

## Future Plans

- **Cloud Synchronization**: To enable task syncing across various devices.
- **Collaborative Tasks**: To introduce functionalities for task sharing and management with others.
- **Custom Reminders**: To allow setting personalized reminders for tasks based on time and location.
- **UI Personalization**: To provide theme choices and custom icons for a more tailored experience.

## Contributing

Your contributions are essential for the open-source community, facilitating an environment rich in learning, inspiration, and creation. We welcome any contributions you might have.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgments

- A big thank you to React Native and Expo for providing the frameworks and tools that made this app possible.
- React Navigation for its role in managing in-app navigation.
- The entire community of contributors and users of TaskMaster for their continuous support and feedback.
