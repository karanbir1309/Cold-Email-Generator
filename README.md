# Cold Email Generator
Cold Email Generator is a tool that can be used by SaaS companies to reach to new potential clients. 
This tool extracts Role, Experience, Skills and Description from the careers site of the potential lead, matches the sentiments with relevant portfolio and generates an email draft.
It uses Llama3.1 pretrained LLM and runs on Groq cloud for faster processing using the Langchain framework. 
The models extracts information from the careers website in JSON format and has a csv file for sample portfolio links.
The data embedding for the Portfolio.csv is done on ChromaDB. 
