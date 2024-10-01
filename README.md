![Grop](https://socialify.git.ci/julioaranajr/Groq_LangChain_Conversational_Chatbot/image?description=1&font=Source%20Code%20Pro&forks=1&issues=1&language=1&name=1&owner=1&pattern=Solid&pulls=1&stargazers=1&theme=Dark)

To get started with Groq using Python, you can follow these steps:

## Step 1: Install the Groq Python library

You can install the Groq Python library using pip:

```bash
pip install -r requirements.txt
```

## Step 2: Set up your API Key

Create a Free API key here: [Groq Console - Keys](https://console.groq.com/keys)

Set it as an environment variable (easy way but not recommended):

```bash
export GROQ_API_KEY=<your-api-key-here>
```

Is highly recommended to use a `.env` file to store your API key. To do this, you can use the `python-dotenv` library:

```bash
pip install python-dotenv
```

Create a `.env` file in the root of your project and add your API key:

```bash
GROQ_API_KEY=<your-api-key-here>
```

To protect your `.env` file, add it to your `.gitignore` file:

```bash
echo .env >> .gitignore
```

also you need to include the /venv folder in the .gitignore file

```bash
echo venv/ >> .gitignore
```

## Step 3: Run the example

You can run the example by executing the following command:

```bash
python main.py
```

## Step 4: Enjoy!

You can now start using Groq in your Python projects! 🚀

## Step 5: Learn more

You can learn more about Groq by visiting the official documentation: [Groq Documentation](https://docs.groq.com/)

Happy coding! 🎉
