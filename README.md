# ollama-recipes

Playground and journal of me trying out ollama and open-source llm's.

## Setup

1. Install Mac via Homebrew.

   ```shell
   brew install --cask ollama
   ```

1. Download llama model (8B chat model, 4.7GB).

   ```shell
   ollama pull llama3
   ```

1. Run the model interactively.

   ```shell
   $ # Run with --verbose to give perf info
   $ ollama run llama3 --verbose 
   >>> who wrote the book godfather?
   ... {response from llama} ...
   ```

   > **Note**
   >
   > We can also use the 70B llama 3 model. By running the following:
   > `ollama pull llama3:70b; ollama run llama3:70b` 

## References

* [Running Llama on Mac](https://www.llama.com/docs/llama-everywhere/running-meta-llama-on-mac/)