🚀 Project Title & Tagline
=========================
**Quiz Master** 🤔
_A fun and interactive quiz game built with Python and Tkinter_

📖 Description
--------------
The Quiz Master project is a simple yet engaging quiz game that tests your knowledge in various categories. The game is built using Python and utilizes the Tkinter library for creating a graphical user interface. With a clean and intuitive design, the game is easy to play and navigate. The quiz questions are fetched from the Open Trivia DB API, ensuring a diverse range of questions to keep you entertained.

The game is designed to be user-friendly, with a simple and intuitive interface that allows players to easily navigate through the quiz. The game also keeps track of the player's score, providing a fun and competitive experience. With its interactive and engaging design, the Quiz Master project is perfect for anyone looking to test their knowledge and have fun while doing it.

The project consists of several key components, including the quiz brain, question model, and user interface. The quiz brain is responsible for managing the quiz questions and keeping track of the player's score. The question model represents a single quiz question, with attributes for the question text and answer. The user interface is built using Tkinter and provides a clean and intuitive design for playing the quiz game.

✨ Features
--------
The following are some of the key features of the Quiz Master project:
* **Interactive Quiz Game**: The game is designed to be interactive, with a simple and intuitive interface that allows players to easily navigate through the quiz.
* **Diverse Range of Questions**: The quiz questions are fetched from the Open Trivia DB API, ensuring a diverse range of questions to keep you entertained.
* **Score Tracking**: The game keeps track of the player's score, providing a fun and competitive experience.
* **Clean and Intuitive Design**: The game has a clean and intuitive design, making it easy to play and navigate.
* **User-Friendly Interface**: The game has a user-friendly interface, with clear and concise instructions for playing the quiz.
* **Error Handling**: The game includes error handling to ensure that it can recover from any errors that may occur during gameplay.
* **Customizable**: The game is customizable, allowing you to easily add or remove quiz questions.
* **Open-Source**: The game is open-source, allowing you to view and modify the source code.

🧰 Tech Stack Table
-------------------
| Technology | Description |
| --- | --- |
| **Frontend** | Tkinter |
| **Backend** | Python |
| **API** | Open Trivia DB API |
| **Tools** | requests, html |

📁 Project Structure
---------------------
The project consists of the following folders and files:
* **data.py**: This file contains the code for fetching quiz questions from the Open Trivia DB API.
* **question_model.py**: This file contains the code for representing a single quiz question.
* **quiz_brain.py**: This file contains the code for managing the quiz questions and keeping track of the player's score.
* **ui.py**: This file contains the code for building the graphical user interface.
* **main.py**: This file contains the code for running the quiz game.

Here is a brief explanation of each folder and file:
* **data**: This folder contains the code for fetching quiz questions from the Open Trivia DB API.
* **models**: This folder contains the code for representing a single quiz question.
* **quiz**: This folder contains the code for managing the quiz questions and keeping track of the player's score.
* **ui**: This folder contains the code for building the graphical user interface.

⚙️ How to Run
--------------
To run the quiz game, follow these steps:
1. **Setup**: Clone the repository and navigate to the project folder.
2. **Environment**: Install the required dependencies by running `pip install -r requirements.txt`.
3. **Build**: Run the game by executing `python main.py`.
4. **Deploy**: The game can be deployed on any platform that supports Python and Tkinter.

🧪 Testing Instructions
---------------------
To test the quiz game, follow these steps:
1. **Run the Game**: Run the game by executing `python main.py`.
2. **Play the Game**: Play the game and test its functionality.
3. **Test Error Handling**: Test the game's error handling by simulating errors during gameplay.

📸 Screenshots
--------------
Here are some screenshots of the quiz game:
<img width="434" height="665" alt="image" src="https://github.com/user-attachments/assets/9d8d0064-628f-4260-824f-22f83c69d417" />


📦 API Reference
----------------
The quiz game uses the Open Trivia DB API to fetch quiz questions. The API has the following endpoints:
* **GET /api.php**: Fetches a list of quiz questions.

Here is an example of how to use the API:
```python
import requests

parameters = {
    "amount": 10,
    "type": "boolean"
}

response = requests.get("https://opentdb.com/api.php", params=parameters)
```

