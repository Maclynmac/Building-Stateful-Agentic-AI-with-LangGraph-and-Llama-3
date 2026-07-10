<strong>LangGraph-Powered Stateful AI News Assistant</strong>

<strong>Features:</strong>

<ul>
  
<li>Streamlit-based UI for interactive chatbot workflows</li>
<li>LLM selection via Groq with model choices: llama3-8b-8192, llama3-70b-8192, gemma2-9b-it</li>
<li>Three built-in use cases: Basic Chatbot, Chatbot With Web, AI News</li>
<li>LangGraph stateful graph architecture using StateGraph</li>
<li>Custom node types: BasicChatbotNode, ChatbotWithToolNode, AINewsNode</li>
<li>Tool-enabled chatbot integration using Tavily search</li>
<li>AI News Explorer:fetch latest AI news for Daily / Weekly / Monthly and summarize news using LLM prompts</li>
<li>API key handling for GROQ and TAVILY in the sidebar</li>

</ul>

<strong>Technologies used:</strong>

<ul>
  <li>Python – Used as the main programming language for developing AI.</li>
  <li>Streamlit - Used to build interactive web interfaces for AI applications quickly.</li>
  <li>LangGraph - Used to model stateful agent flows with nodes and edges, enabling multi-step chatbot and news-summary pipelines.</li>
  <li>LangChain - Used to orchestrate prompts, manage LLM interactions, and support tool integration.</li>
  <li>langchain_groq - Used to connect to Groq-hosted LLM backends like llama3-8b-8192, llama3-70b-8192, and gemma2-9b-it.</li>
  <li>tavily-python - Used to fetch live web search/news content for the Chatbot With Web and AI News flows.</li>
  <li>FAISS (faiss-cpu): Included for local vector similarity and retrieval support in the tool/agent pipeline.</li>
</ul>

# Output

<strong>Basic Chatbot</strong>

<img width="5360" height="2632" alt="IMG-20260702-WA0335" src="https://github.com/user-attachments/assets/1260ba1b-78b2-455e-b031-2c881a1bd577" />

<img width="5232" height="2548" alt="IMG-20260702-WA0353" src="https://github.com/user-attachments/assets/c8a94316-8823-4157-a8c4-613fb2766d3b" />


<img width="5288" height="2560" alt="IMG-20260702-WA0352" src="https://github.com/user-attachments/assets/d7441914-b45d-4344-bf07-307ed17b71b0" />


<strong>Chatbot With Web Tool</strong>


<img width="5292" height="2612" alt="IMG-20260702-WA0312" src="https://github.com/user-attachments/assets/df7450a9-28f0-41e8-a5e4-cb5145deb6ac" />


<strong>AI News</strong>

<img width="5428" height="2704" alt="IMG-20260702-WA0328" src="https://github.com/user-attachments/assets/67e6ced2-17c0-485b-9938-b0c9c7033980" />


<img width="5404" height="2636" alt="IMG-20260702-WA0327" src="https://github.com/user-attachments/assets/dae353d5-77c4-410b-ab58-fcba49aa27e4" />


<img width="5320" height="2652" alt="IMG-20260702-WA0347" src="https://github.com/user-attachments/assets/691d953d-cff1-4192-84ce-a46449aca94f" />


<img width="5396" height="2672" alt="IMG-20260702-WA0342" src="https://github.com/user-attachments/assets/ffd62051-5e70-4d56-a6b2-4c8b65a04b4f" />


<img width="5428" height="2676" alt="IMG-20260702-WA0339" src="https://github.com/user-attachments/assets/b544b9c2-c4cf-450e-be4f-eb4f9bd28e5c" />


<img width="5432" height="2616" alt="IMG-20260702-WA0333" src="https://github.com/user-attachments/assets/de312d52-51b2-4e05-a45c-2f8dd77c0b51" />


<img width="5384" height="2716" alt="IMG-20260702-WA0330" src="https://github.com/user-attachments/assets/ab0c3bf7-8193-49a4-b591-92f966cc4952" />
















