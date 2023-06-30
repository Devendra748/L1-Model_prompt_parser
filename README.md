# L1-Model_prompt_parser
## Direct API calls to OpenAI: 
The code snippet demonstrates a direct API call to OpenAI's Chat API using the OpenAI Python library.

## LangChain installation: 
The code installs the LangChain library using pip.
* pip install python-dotenv
* pip install openai
* pip install --upgrade langchain

## LangChain Model: 
The code snippet imports the ChatOpenAI class from langchain.chat_models and initializes a ChatOpenAI instance with specific parameters such as temperature and OpenAI API key.

## Prompt template: 
The code defines a prompt template using the ChatPromptTemplate class from langchain.prompts. The template includes placeholders for variables like style and text.

## Formatting the prompt template: 
The code uses the prompt_template.format_messages() method to format the template by replacing the variables with actual values. This generates a list of HumanMessage objects.

## Chat interaction: 
The code passes the formatted prompt messages to the chat instance, which interacts with the OpenAI Chat API and generates a response.

## Output parsing: 
The code demonstrates how to define an output parsing schema using the ResponseSchema class from langchain.output_parsers. It also shows how to parse the LLM output string into a Python dictionary using the StructuredOutputParser class.
