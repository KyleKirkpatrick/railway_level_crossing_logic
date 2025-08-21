# Documentation of AI Use in this Project

The Copilot feature integrated in VSCode was used for some limited consultation in this project. The general experience was time-consuming, with the AI losing context and suggesting things that were beyond the scope of this assignment.

## Documentation Improvements

### Citation

One helpful use of a LLM is to quickly adapt information into a standard syntax. I improved the documentation by adding an IEEE article reference to the Solutions document.

![Screenshot of Copilot citation prompt](Screenshot%202025-08-20%20222850.png)

However, this exposed limitations of the LLM's context. It does not know the current date, and did not seem to parse the information on the webpage for the reference. It *can* parse websites, but the prompt must explicitly provoke that action. 

### README Summary

I used Copilot to summarise the content in this repo, but it took many corrections to get a viable output. The principal issue was that it could not parse the other files in this directory. 

![Screenshot of Copilot README prompt](Screenshot%202025-08-21%20222055.png)

Having not read the documentation, it hallucinated the contents of the repository.

![Screenshot of Copilot refinement prompt](<Screenshot 2025-08-21 222307.png>)

I had to explicitly pass the URL of the public Github repo, and then the LLM invoked its webpage parsing tool and wrote a decent summary. 

## Generating Alternative Solutions

Copilot was also prompted to provide suggestions for the various solution approaches. Some of its suggestions were integrated in the project. Substantial editing was necessary, as the LLM does not have an understanding of the context to generate systems that are actually safe and logical.  