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

<img width="5292" height="2612" alt="IMG-20260702-WA0312" src="https://github.com/user-attachments/assets/e351eb6e-98ea-45c2-bf86-9bb17afbb52c" />

<img width="5232" height="2548" alt="IMG-20260702-WA0353" src="https://github.com/user-attachments/assets/c8a94316-8823-4157-a8c4-613fb2766d3b" />

<img width="5288" height="2560" alt="IMG-20260702-WA0352" src="https://github.com/user-attachments/assets/d7441914-b45d-4344-bf07-307ed17b71b0" />


<strong>Chatbot With Web Tool</strong>

<img width="5292" height="2612" alt="IMG-20260702-WA0312" src="https://github.com/user-attachments/assets/df7450a9-28f0-41e8-a5e4-cb5145deb6ac" />









