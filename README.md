# GenAI-Copilot CLI - How-To install
  * Install GitHub Copilot CLI on your Codespace instance using npm:
  
  - From "main" branch:
   - click on the (green button) "<> CODE"
   - select "Codespaces" tab
   - click the + to launch Codespaces instance
   - This will launch a default Codespaces instance with 2-core 8GB RAM, 32GB (sufficient to build this image)
   - The browser navigates to the codespace instance: something like this... <some random name>gp.github.dev
   - At bottom, select tab "Terminal" - this is bash shell
   - * $>npm install -g @githubnext/github-copilot-cli
     * To authenticate with GitHub Copilot CLI:
   - * $>github-copilot-cli auth
