Setup virtual environment:
python -m venv env
env\Scripts\activate

Install necessary libraries:
pip install -r requirements.txt 
or
pip install langchain langchain-community langchain-openai langchain-core neo4j
and jupyter related modules.

Add api key or select own model while making sure 
that Neo4j desktop with APOC plugin is already installed
with a started database.
