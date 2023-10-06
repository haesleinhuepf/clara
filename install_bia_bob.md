## Install bia-bob on clara

Login to the clara [Jupter hub](https://lab.sc.uni-leipzig.de/) and open a terminal.

Activate an environment and install these packages using pip:
```
conda activate bio39
pip install bia-bob openai
```

Afterwards, start a text editor such as `vim`:
```
vim .bashrc
```

And add your [OPENAI API KEY](https://platform.openai.com/account/api-keys) to this file (replace `sk-...` with your key):
```
export OPENAI_API_KEY=sk-...
```

Afterwards, you may have to restart the Jupyter hub server.
