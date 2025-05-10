 CLI interface to OpenAI ChatGPT. It uses langchain to interact with ChatGPT, and implements the ConversationChain and both ConversationBufferMemory and ConversationSummaryMemory with CombinedMemory.

## Features

- Uses langchain for seamless integration with ChatGPT
- Implements ConversationChain for more natural conversations
- Uses CombinedMemory with ConversationBufferMemory and ConversationSummaryMemory for a more natural experience
- Swapable prompts! Customize Doug in any way you see fit. Check out `data/prompt` and add your own!
- Persitent data in `data/db` for indexed documents. Currently limited to PDFs only!
