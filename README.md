# AutoReadMe
A prototype python function which utilises chatgpt to generate read me files. Soon to be released as a command line tool
Note - This readMe was generated from the function

# AutoReadMe.py

AutoReadMe.py is a Python script that utilizes the openai module to automatically generate a README file for a project. It simplifies the process of creating a README by summarizing the contents of the files in the current directory.

## Requirements

To run AutoReadMe.py, you need to have the following:

- Python: AutoReadMe.py is written in Python, so make sure you have Python installed on your system. You can download Python from the official Python website: https://www.python.org/downloads/

- openai module: AutoReadMe.py relies on the openai module to generate summarizations. To install the openai module, you can use pip, the package installer for Python. Run the following command in your terminal:
  ```
  pip install openai
  ```

- GPT-3.5-turbo API key: To use the GPT-3.5-turbo model for generating the README content, you will need a GPT-3.5-turbo API key from OpenAI. Once you have obtained your API key, you need to set it up in the AutoReadMe.py script. Open the AutoReadMe.py file in a text editor, locate the "API key setup" section, and replace the placeholder with your actual API key.

## How to Run AutoReadMe.py

To run AutoReadMe.py, follow these steps:

1. Make sure you have met the requirements mentioned above.

2. Open a terminal or command prompt and navigate to the directory where the AutoReadMe.py file is located.

3. Run the following command:
   ```
   python AutoReadMe.py
   ```
   This will generate a README file for the current directory.

4. The generated README file will be printed to the console. You can copy and save it to a file as needed.

## Examples

Here are a few examples to illustrate the usage of AutoReadMe.py:

Example 1: Generating README for the current directory
```
python AutoReadMe.py
```
This command will generate a README file for the files in the current directory and print it to the console.

Example 2: Generating README for a specific project directory
```
python AutoReadMe.py path/to/project
```
This command will generate a README file for the files in the "path/to/project" directory and print it to the console.

Example 3: Saving the generated README to a file
```
python AutoReadMe.py > README.md
```
This command will generate a README file for the current directory and save it to a file named README.md in the current directory.

These examples demonstrate the basic usage of AutoReadMe.py. Feel free to explore the script and modify it according to your specific project requirements.

Note: Depending on the size and complexity of the files in the directory, generating the README file may take some time. Please be patient while the script processes the files and generates the summarizations.
