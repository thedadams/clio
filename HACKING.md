# Hacking

Clio under the hood is just a GPTScript. The main GPTScript is [agent.gpt](./agent.gpt). You can run the GPTScript by doing `gptscript ./agent.gpt`.

The go code is just a wrapper around the GPTScript that mostly handles authentication. If you want to develop on the core GPTScript is best to no use the `clio` go code wrapper and just use the GPTScript directly instead.