# WhatsApp Flutter Chat UI

This Flutter project is a basic implementation of a **WhatsApp-style chat interface**. It includes a simple chat screen where users can send and display messages. The design is inspired by popular messaging apps, with a familiar layout for ease of use.

### Screenshots 📸
Below are some screenshots of the current interface:

- **Chat Screen:** This shows a basic chat conversation with messages aligned properly for incoming and outgoing messages.
- ![image](https://github.com/user-attachments/assets/6d9c358f-0d0f-4816-a483-b71c165aa232)

### Features
- **Background Image**: The chat background uses a custom image (`BG.png`), providing a familiar feel like WhatsApp.
- **Incoming and Outgoing Messages**: Different styles for the messages, including distinct bubbles for incoming and outgoing messages.
- **Assets**: Includes image assets like profile pictures and background images for customization.

---

### How to Structure the Screens

You can follow this structure for creating a WhatsApp-like chat interface using Flutter:

#### 1. **Chat Screen**
This is the main chat interface that displays the conversation with a particular contact. You can structure it using:
- **App Bar**: Shows the contact's name, profile image, and options like calling, video chat, or settings.
- **Chat Bubbles**: These should represent the conversation. Flutter’s `ListView` can be used to display a series of message bubbles. 
  - **Outgoing Message** (sent by the user): Aligned to the right with a custom color/style.
  - **Incoming Message** (received from contact): Aligned to the left with a different color/style.
- **Text Input Field**: A bottom bar with a text field where the user can type a message and send it.

---

### Getting Started

To run this project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-repo/whatsapp-flutter-ui.git
    ```
    
2. **Navigate to the project directory**:
    ```bash
    cd whatsapp-flutter-ui
    ```
    
3. **Install dependencies**:
    ```bash
    flutter pub get
    ```
    
4. **Run the project**:
    ```bash
    flutter run
    ```

---

### Legal Notice ⚖️

This project is the intellectual property of **Adham** and is protected by **DMCA copyright law**.

### ❗ Unauthorized Use:
Any attempt to copy, distribute, or reproduce this project **without the author's permission** will result in legal action under the Digital Millennium Copyright Act (DMCA). Violators will be subject to civil penalties and potential legal action.

If you are interested in using this project or any part of it for educational or commercial purposes, you **must** request permission from the author.

---

### License 📄

This project is licensed under the MIT License. See the `LICENSE` file for more details.
