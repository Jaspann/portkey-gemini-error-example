# Portkey Gemini Errors

I made this to record the errors I was getting when using the Portkey Gemini API.

## Setup

Windows 11
Python 3.12
uv package manager

## Modifications

This is the default CrewAI project with the following modifications:
- Added Portkey env variables to the .env file
- Added three LLM configurations to the `src/portkey_test/crew.py` file with comments to indicate error file locations
- Added `prefix.txt` and `no_prefix.txt` to the root folder to record the errors I was getting when using the Portkey Gemini API.
- I additionally shortened the llm's responses for debugging.

To test, uncomment the LLM configuration you want to use and run `crewai run` from the root folder.
