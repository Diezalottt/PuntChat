## PuntChat

This project introduces "Reese Istor," a sophisticated AI interface equipped with comprehensive knowledge in power electronics theory and design. It leverages the powerful capabilities of OpenAI's language models to address inquiries related to various power applications, offering expert advice on design principles, theoretical understanding, troubleshooting techniques, safety protocols, and keeping abreast of the latest technological developments.

## Getting Started

Prepare your local environment to use Reese Istor by performing the following steps:

    Confirm that Python is installed on your computer; if not, download and install it from the Python official website.
    https://www.python.org/downloads/

    Acquire the project's codebase by cloning its GitHub repository.

    `git clone [todo]`

    In the project directory, establish a virtual environment using the command python -m venv venv.

    `python -m venv venv`

    Activate the virtual environment (.\venv\Scripts\activate on Windows or source venv/bin/activate on Unix-based systems).

    Windows
    `.\venv\Scripts\activate`

    Unix
    `venv/bin/activate`

    Install necessary dependencies with pip install -r requirements.txt.

    `pip install -r requirements.txt`

    Obtain your personal OpenAI API key by creating an account at OpenAI API and follow their setup process.
    https://openai.com/blog/openai-api

    Configuring the Environment Variable

    Once you've obtained your OpenAI API key, set it as an environment variable:
    Windows:

    `set OPENAI_API_KEY=your-api-key`

    Mac/Linux:

    `export OPENAI_API_KEY=your-api-key`

To make this variable permanently available, you can include it in your .bashrc or .zshrc file. Or change the line that calls for the key in puntchat.py.

Change it from
`openai.api_key = os.getenv("OPENAI_API_KEY")`

to
`openai.api_key = ("YOUR_API_KEY")`

The AI assistant can be changed by changing the assistant ID to the desired chatbot.
`assistant_id = "asst_N1P9Wv5HOiJRJKAekqs4dVP7"`

Future functionality may allow for switching between multiple AI assistants.

## Usage

Once the environment is prepared and the API key is in place, start the application with python puntchat.py from your terminal.
`python puntchat.py`

Here's what using Reese Istor will look like:

`Ask Reese Istor a question about power electronics (or type 'exit' to quit):`

Just pose your query regarding power electronics to receive informed counsel from Reese Istor.

## Contributing

Contributions are encouraged and greatly appreciated. To contribute, fork the repository, implement your modifications, and open a pull request. Your efforts will help enhance the capabilities offered by Reese Istor or any other AI assistant.

## License

This project adheres to the MIT License, which permits you to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the software. For more details, see the LICENSE file provided with the code or consult Choose a License.
https://choosealicense.com/licenses/mit/

This version of the README.md reflects the changes in the assistant's instructions, highlighting its role as an authority figure in power electronics and its use of reference materials to provide knowledge-based assistance.
