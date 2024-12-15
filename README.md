# Web Clip
This application explores an implementation of AI using OpenAI's `gpt-4o-mini`
model, which provides a summary of a given webpage.

The `summarize` function receives a URL input from the user and returns a summary of the content that lives on that website page.

## How to run application locally

1. Clone repository by running `git clone https://github.com/tk1ng/web_clip.git` from within the directory where you wish this application to live
2. `cd` into the **web_clip** git repository
3. Prior to installing the dependencies for this application, it is a good practice to configure a virtual environment for Python projects to ensure that the development environment is clean and conflict free development environment. It also helps to prevent creating conflicts from installing packages globally.

    - To create a virtual environment:
    1. Run following command from terminal:
        `python<version> -m venv <virtual-environment-name>`

    2. Activate env:
    `source <virtual-environment-name>/bin/activate`
4. run the following command:
`pip install -r ./requirements.txt`
This command installs all of the required dependencies that are documented in the **requirements.txt** file

5. Final step is running the program using the following command:
`python3 <path to file>`
