
=====================================================================================================================================================================
Step A :- 

-----------------------------
Step B ->

1) Install Claud Code => irm https://claude.ai/install.ps1 | iex   ( System Setup also)
  How to check after install => claude --version
2) Get OpenRouter Key => Visit to OpenRouter website and click on "Get API Key" . Create a new key.
3) VS Code, Git Bash & Node js download and install.
4) Open VS code terminal in folder path =>
{
  $env:ANTHROPIC_BASE_URL="https://openrouter.ai/api"; $env:ANTHROPIC_API_KEY="your-openrouter-key"; $env:ANTHROPIC_MODEL="moonshot/kimi-k2.6:free"; claude
}
5) We can change the model. VIsiti the OpenRouter Website ans check the required model like Gemma (google/gemma-4-31b-it:free) and update the Model name in step 4.
=====================================================================================================================================================================
