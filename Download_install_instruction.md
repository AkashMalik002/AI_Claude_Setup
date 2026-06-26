
=======================================================================================

Step A :- 
1) Install Claude Code =>
  Powershell -> irm https://claude.ai/install.ps1 | iex
  windows cmd -> curl -fsSL https://claude.ai/install.cmd -o install.cmd && install.cmd && del install.cmd
  OR irm https://claude.ai/install.ps1 | iex

  How to check => claude code (command in terminal)
  
2) Open code install -> zen -> Get Started with zen -> API Key
3) VS Code, Git Bash & Node js download and install.
4) in vs code terminal -> code ~/.claude -> New folder will open -> Got to settings.json
   {
  "env": {
    "ANTHROPIC_BASE_URL": "https://opencode.ai/zen",
    "ANTHROPIC_MODEL": "minimax-m2.5-free",
    "ANTHROPIC_API_KEY": "opencode-api-key",
    "ENABLE_TOOL_SEARCH": "true"
  }
}
5) in VS code terminal -> claude code
6) Open code install -> curl -fSSL https://opencode.ai/install | bash
    => also check the command from UI
   How to check => run the command in VS terminal -> opencode
   (/model)
8) Setup done.

-----------------------------
Step B -> -> New 

1) Install Claude Code => irm https://claude.ai/install.ps1 | iex   ( System Setup also)
  How to check after install => claude --version
2) Get OpenRouter Key => Visit to OpenRouter website and click on "Get API Key" . Create a new key.
3) VS Code, Git Bash & Node js download and install.
4) Open VS code terminal in folder path =>
(
  $env:ANTHROPIC_BASE_URL="https://openrouter.ai/api"; $env:ANTHROPIC_API_KEY="your-openrouter-key"; $env:ANTHROPIC_MODEL="moonshot/kimi-k2.6:free"; claude
)
5) We can change the model. VIsiti the OpenRouter Website ans check the required model like Gemma (google/gemma-4-31b-it:free) and update the Model name in step 4.
=======================================================================================
