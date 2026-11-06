# NEO4j_OLLamaLLM_recipe-recommendation
- This is a project for user recipes recommendation using a graph database to fetch relevant data and answer question in natural English.
- Agents were used to make the process of building the pipeline easier as instructed by our professor.

## Table of Contents

- [Tools](#tools)
- [Notes](#notes)

## Tools
- Python
- Qwen 3:4b
- Ollama
- Neo4j Cloud Database

## Notes
- The data is stored in a Neo4j database that is hosted online using an official Neo4j account.
- Qwen 3:4b open source local LLM was used instead of a bigger model because of GPU limitations. Using smaller models sometimes results in simpler answers such as "I don't know.". You can use a larger model if you want.
- I filled the text files with random ingredients and recipes. You can fill them yourself as I didn't have actual data. I made the data up.
