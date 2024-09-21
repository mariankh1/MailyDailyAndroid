# MailyDaily

Welcome to MailyDaily! 🌟 Your AI-powered email assistant that helps you manage your unread emails with ease.

**Please use [Version 1 as current working branch](https://github.com/mariankh1/MailyDailyAndroid/tree/version1)**

## Features

- **Google Sign-In**: Allows users to log in with their Gmail account. ✅
- **Email Fetching**: Retrieve unread emails from the user's inbox.✅
- **Email Summarization**: Fetches unread emails and provides a summary. ✅
- **Actionable Recommendations**: Generates actionable items from email content. ✅
- **Sign-In with other email clients**: Allows users to log in with accounts from various email clients.❌
- **Modern Conversational UI**: User-friendly interface with profile display and action buttons. ❌
- **Email Notifications**: Notify users of new unread emails / every morning or on set time . ❌
- **Voice Assistant Integration**: Allow users to interact with the app using voice commands. ❌
- **Settings Screen**: Manage app settings and preferences. ❌

## Technologies Used

- **Kotlin**: Programming language used for Android development.
- **Jetpack Compose**: UI toolkit for building native Android UIs.
- **Firebase**: Authentication and backend services.
- **Hugging Face API**: For generating email summaries and recommendations using the **Mistralai/Mistral-Nemo-Instruct-2407** model.

## Screenshots of Current Progress

![Summary Screen](https://github.com/mariankh1/MailyDailyAndroid/tree/version1/docs/assets/screenshots/1.png)  
*Summary of emails and recommended actions.*

![Email Card](https://github.com/mariankh1/MailyDailyAndroid/tree/version1/docs/assets/screenshots/2.png)  
*Example of the emails and how the actions are rendered.*

## Getting Started

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/mailydaily.git
    ```
2. **Setup Firebase**: Follow the instructions in `firebase-setup.md` to configure Firebase for your project.
3. **Configure the API**: You’ll need a Hugging Face API key. Update your project with this key to interact with the model.
4. **Run the App**: Open the project in Android Studio and run it on an emulator or device.

## Contributing

Feel free to contribute to the project by submitting issues or pull requests. We welcome all contributions! Here's what we need to implement:

- **Email Fetching**: Retrieve unread emails from the user's inbox. 
- **Email Notifications**: Notify users of new unread emails. 
- **Voice Assistant Integration**: Allow users to interact with the app using voice commands. 
- **Settings Screen**: Manage app settings and preferences. 

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Hugging Face](https://huggingface.co) for the amazing AI models, particularly the **Mistralai/Mistral-Nemo-Instruct-2407** model used for summarization and recommendations.
- [Firebase](https://firebase.google.com) for backend services.

---

&copy; 2024 MailyDaily. All rights reserved.
