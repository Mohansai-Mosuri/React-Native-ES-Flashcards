# React Native English-Spanish Flashcards

This repository contains the source code for a React Native application designed to help users learn Spanish vocabulary through an offline-first, personalized flashcard system.

## Project Description

The application provides a user-friendly interface for learning English-Spanish translations. Users can view flashcards, reveal the Spanish translation, and rate the difficulty of each word. The app stores vocabulary data locally, allowing for offline access. The app also features smooth transitions and color-coded difficulty ratings.

## Features

* **Offline Functionality:** Vocabulary data is stored locally using `AsyncStorage`, enabling access without an internet connection.
* **Personalized Flashcards:** Users can rate the difficulty of each word (Easy, Medium, Hard), allowing for personalized learning.
* **English-Spanish Translations:** Displays English words and their Spanish translations.
* **Phonetic Pronunciation:** Provides phonetic pronunciation for Spanish words.
* **Interactive Interface:** Includes "Show Answer" and "Hide Answer" buttons with smooth fade-in/fade-out transitions.
* **Difficulty Rating:** Users can rate the difficulty of each word, and the rating buttons change color for user feedback.
* **Spaced Repetition Logic:** The app stores the last reviewed timestamp and the difficulty of each word, which can be expanded to implement a spaced repetition algorithm.
* **Large Dataset:** Uses a `words.json` file containing a large collection of English-Spanish translations.

## Tools and Technologies Used

* **React Native:** A JavaScript framework for building cross-platform mobile applications.
* **React:** A JavaScript library for building user interfaces.
* **AsyncStorage:** React Native's built-in storage for local data persistence.
* **Animated:** React Native's animation library for smooth transitions.
* **JavaScript:** The primary programming language used.
* **JSON:** Used for storing vocabulary data in `words.json`.

## Setup and Installation

1.  **Prerequisites:**
    * Node.js and npm (or yarn) installed.
    * Expo CLI installed globally (`npm install -g expo-cli` or `yarn global add expo-cli`).

2.  **Clone the Repository:**
    ```bash
    git clone <YOUR_REPOSITORY_URL>
    cd React-Native-ES-Flashcards
    ```

3.  **Install Dependencies:**
    ```bash
    npm install
    # or
    yarn install
    ```

4.  **Run the Application:**
    ```bash
    expo start
    ```

5.  **Running on a Device/Simulator:**
    * **Physical Device:** Download the Expo Go app from the App Store (iOS) or Google Play Store (Android). Scan the QR code displayed in the Expo Developer Tools with the Expo Go app.
    * **Simulator/Emulator:** If you have Android Studio or Xcode set up, you can run the app in an emulator or simulator by clicking the appropriate button in the Expo Developer Tools.

## How to Use

1.  The application displays a list of English words.
2.  Tap the "Show Answer" button to reveal the Spanish translation and phonetic pronunciation.
3.  Rate the difficulty of the word by tapping "Easy," "Medium," or "Hard." The button will change color to indicate your rating.
4.  Tap the "Hide Answer" button to hide the translation.
5.  The app stores the difficulty rating and last reviewed timestamp for each word, allowing for personalized learning.

## Future Enhancements

* Implement a full spaced repetition algorithm to optimize learning.
* Add audio pronunciations for Spanish words.
* Expand the vocabulary dataset further.
* Add user progress tracking and statistics.
* Implement user accounts and synchronization.
* Add more language pairs.
* Improve the user interface and user experience.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
