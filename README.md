# AI Multiagent Apps for Automatic Research Paper Writing

## Rules

1. **Goal**: The primary objective is to automatically write a research paper, potentially excluding the results and discussion sections, as they depend on the author's research work.

2. **Input**:
   - Researcher provides a **prompt** including:
     - Research topic
     - Purposes
     - Methodology
     - Goals
   - Researcher uploads a **journal template** (file upload) or specifies a **journal writing style** (e.g., APA style, IEEE, etc.). If it not be provided, Agent will writing using random writing style. 
   - Researcher specifies the **minimum number of references** required.

3. **Agent Tasks**:
   - Perform **web scraping** across the internet, specifically targeting **scientific journal platforms** (e.g., Scopus, IEEE Xplore, PubMed) to find relevant literature.
   - Ensure the number of references matches the researcher's input requirement.
   - Process and organize the gathered information into a structured research paper following the specified template and writing style.
   - Write the Scientific Research Paper
