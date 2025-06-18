Urban T-Shirts : Talk to a Database

This is an end to end LLM project based on Groq and Langchain. We are building a system that can talk to MySQL database. User asks questions in a natural language and the system generates answers by converting those questions to an SQL query and then executing that query on MySQL database. Urban T-Shirts is a T-shirt store where they maintain their inventory, sales and discounts data in MySQL database. A store manager will may ask questions such as,

How many white color Adidas t shirts do we have left in the stock?
How much sales our store will generate if we can sell all extra-small size t shirts after applying discounts? The system is intelligent enough to generate accurate queries for given question and execute them on MySQL database

<img width="953" alt="Project1" src="https://github.com/user-attachments/assets/c7fed3e7-4e64-4f6f-b11b-875bfa97c492" />

<img width="944" alt="project2" src="https://github.com/user-attachments/assets/96535247-2dc4-43a8-9577-9481dd23c493" />

Project Highlights

Urban T-Shirt is a t shirt store that sells Adidas, Nike, Van Heusen and Levi's t shirts
Their inventory, sales and discounts data is stored in a MySQL database
We will build an LLM based question and answer system that will use following,
Groq LLM
Hugging face embeddings
Streamlit for UI
Langchain framework
Chromadb as a vector store
Few shot learning
In the UI, store manager will ask questions in a natural language and it will produce the answers

Project Structure
main.py: The main Streamlit application script.
langchain_helper.py: This has all the langchain code
requirements.txt: A list of required Python packages for the project.
few_shots.py: Contains few shot prompts
.env: Configuration file for storing your Groq Api Key.
