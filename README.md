# gptchat-shell-helpers
Manage GPTChat Pre/Prompts - Select and Copy to Clipboard

# Usage
1. Clone repo
2. Add variable "gpt\_prompt\_dir=" to your bashrc and source the bash script, like:
```bash
gpt_prompt_dir=~/mydata/gpt/prompts
. ~/bin/gptchat-shell-helpers/bash-gpt-prompt-tools
```
3. Run `gptprompt` or `gptprompt some_string`.  (Providing a string will do an initial filtration of the results)

# Dependencies
* This uses fzf for the listing/selection

# Limitations
* I've not yet included prompt adding/editing
* I didn't include tab completion [yet]
* I left a bunch of commented-out references and stuff in there, but the code itself (and what ends up stored in a bash function) should be pretty clean

