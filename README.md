# ollama Lab Demos

Demos about running ollama within "lab environments"

## Colab

> [!IMPORTANT]  
> Pay attention to the first instruction in the notebook, which instructs you to switch runtime -- otherwise the rest may not work.

### The "xterm" way

[Open in Colab](https://colab.research.google.com/github/hemidactylus/ollama-lab-demos/blob/main/ollama1_xterm.ipynb), [view here](ollama1_xterm.ipynb)

_(adapted from [this](https://medium.com/@abonia/running-ollama-in-google-colab-free-tier-545609258453))_

### The in-thread way

[Open in Colab](https://colab.research.google.com/github/hemidactylus/ollama-lab-demos/blob/main/ollama2_threading.ipynb), [view here](ollama2_threading.ipynb)

_(adapted from [this](https://github.com/5aharsh/collama/blob/main/Ollama_Setup.ipynb))_

## Gitpod

Note: in April 2025 "Gitpod classic" will be discontinued fully, in favour of "Gitpod Flex" ([blog post](https://www.gitpod.io/blog/introducing-gitpod-flex)).

- TODO assess impact on Gitpod-based labs.

[Open in Gitpod](https://gitpod.io/new/#https://github.com/hemidactylus/ollama-lab-demos)

**Note**: on Gitpod,
> Ollama will run in CPU-only mode.

Left as an exercise:

1. using more specialized Python libraries, e.g. `langchain-ollama` (see notebooks for details);
2. setting up a Katapod scenario with an `ollama` instance running alongside it.
