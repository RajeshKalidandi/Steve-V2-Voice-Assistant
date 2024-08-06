# Steve - The Voice Assistant

## Overview

Steve is a voice assistant program designed to assist users with various tasks and provide responses to questions. It operates through voice commands and can perform specific actions or answer queries based on the user's input. This program uses several modules to process voice input and generate appropriate responses.

## Features

- **Voice Activation:** Detects voice commands and activates the assistant.
- **Voice Responses:** Provides spoken feedback based on user commands.
- **Command Execution:** Recognizes specific commands such as turning on the TV.
- **Question Answering:** Responds to questions by querying a predefined question-answer module.
- **General Responses:** Handles general queries using an AI-based response system.

## Patent Information

This project is patented under the following details:

- **Patent Title:** Steve - The Voice Assistant
- **Application No.:** 202341006671 A
- **Filing Date:** 02/02/2023
- **Publication Date:** 10/02/2023
- **International Classification:** G10L0015220000, G10L0015260000, G06F0003160000, G10L0015080000, G10L0015000000
- **Applicants:** Malla Reddy Engineering College
- **Inventors:** 
  - KALIDANDI RAJESH
  - SHAIK YAKUSHA
  - KATTA RAJESH
  - GUDLANARVA MANITEJA
  - THAKUR MANMOHAN SINGH
  - SHAIK SANA FATHIMA
  - BONAGIRI SANJANA
  - Dr. MANYAM THAILE
  - Dr. KRISHNA KISHORE DATTI
  - Dr. JASTI LAVANYA
- **Abstract:** 
  Steve leverages Python to create a voice assistant capable of performing various tasks, including sending emails, searching the web, playing music, and more, through voice commands. The assistant uses speech recognition technology to convert speech into text, facilitating hands-free operation and task automation.

## Modules

- **`Brain.AIBrain`:** Contains the `ReplyBrain` class for generating general responses to user queries.
- **`Brain.Qna`:** Contains the `QuestionsAnswer` class for handling specific questions and providing answers.
- **`Body.Listen`:** Contains the `MicExecution` class for capturing and processing voice input.
- **`Body.Speak`:** Contains the `Speak` class for providing spoken responses.
- **`Features.Clap`:** Contains the `Tester` class for detecting claps as a trigger to start the assistant.

## Installation

1. Ensure you have Python 3.x installed.
2. Install the required dependencies (if any) using `pip`.

## Usage

1. **Run the Script:** Execute the `Main.py` script to start Steve.
    ```bash
    python Main.py
    ```

2. **Interaction:** Steve will greet you and wait for voice commands. Speak commands like "turn on the TV" or ask questions starting with "what is" or "where is".

3. **Clap Detection:** The assistant can be activated by clapping, which is detected by the `ClapDetect` function.

## Code Explanation

- **`MainExecution`:** This function starts the assistant, listens for voice commands, and processes them. It distinguishes between specific commands and general queries, responding accordingly.
- **`ClapDetect`:** This function detects a clap to activate the voice assistant and then invokes the `MainExecution` function.

## Contributing

Feel free to contribute to the project by submitting issues or pull requests. Your contributions are welcome!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or support, please contact kalidandiirajesh@gmail.com.
