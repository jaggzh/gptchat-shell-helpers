# gptchat-shell-helpers
Manage GPTChat Pre/Prompts - Select and Copy to Clipboard

# Usage
1. Clone repo
2. Add variable "gpt_prompt_dir=" to your bashrc and source the bash script, like:
```bash
gpt_prompt_dir=~/mydata/gpt/prompts
. ~/bin/gptchat-shell-helpers/bash-gpt-prompt-tools
3. Run `gptprompt` or `gptprompt some_string`.  (Providing a string will do an initial filtration of the results)
```

# Dependencies
* This uses fzf for the listing/selection

# Limitations
* I've not yet included prompt adding/editing
* I didn't include tab completion [yet]


