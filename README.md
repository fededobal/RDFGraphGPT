# RDFGraphGPT
This project extends the Graph GPT project (https://github.com/varunshenoy/GraphGPT) with different approaches in the type of output and the interaction with the originated graph. 
# Natural Language -> RDF -> Graph
@ Main functionality
* The way this project works is that you insert any kind of natural language text, in the background we send it to Open AI API with an specific prompt so it turns it to an RDF turtle format, and then it will be graphed using either Graphviz or Cytoscape, you can choose!
* The RDF archive will be saved in the location you choose, either in a new one or an existent one.
# Other Functionalities
* You can improve the IRIs that chat GPT used by inserting the IRIs you want to change and the ones you would want to use.
* You can edit the RDF code that chat GPT creates and save it in your archive.
# SetUp
1. Run npm install to download required dependencies.
2. Do the same standing in the "serv" folder.
3. Make sure you have an OpenAI API key. You will enter this into the web app when running queries.
4. Run npm run start. RDFGraphGPT should open up in a new browser tab.
