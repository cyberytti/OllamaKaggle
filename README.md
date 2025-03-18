# 🚀 Free LLM Development with Kaggle GPUs

Welcome to this GitHub repository! 🎉 In today’s fast-evolving world of AI development, many students and enthusiasts face a big challenge: lack of access to powerful GPUs. Some may have GPUs, but they’re often not strong enough to run large language models (LLMs) with 20 or 30 billion parameters. 😓

To solve this problem, I’ve created this repository featuring a **Kaggle notebook** that leverages **two free Tesla T4 GPUs** provided by Kaggle. With this setup, anyone can run and develop LLM-powered tools using an **ngrok URL** that integrates with **Ollama** or the **OpenAI API schema**. Let’s democratize AI development! 🌍✨

---

## 🌟 What This Repo Offers
- Access to **free GPU power** (2x Tesla T4 GPUs via Kaggle).
- A simple way to generate an **ngrok URL** for remote LLM access.
- Compatibility with **Ollama** and **OpenAI API** workflows.
- Perfect for students, hobbyists, and developers without high-end hardware.

---

## 🛠️ How to Use This

Follow these steps to get started:

### Step 1: Set Up on Kaggle
1. **Log in to Kaggle** – Create an account if you don’t have one.
2. Open the **Kaggle notebook** provided in this repository.
3. In the notebook settings, select **Accelerator: 2x Tesla T4 GPUs**.
4. Run all the cells in the notebook. 🚀
5. Once complete, the notebook will output an **ngrok URL** – copy it!

### Step 2: Connect Locally with Ollama
1. Open a terminal on your local machine.
2. Set the `OLLAMA_HOST` environment variable using the ngrok URL:
   ```bash
   export OLLAMA_HOST=<paste-your-ngrok-url-here>
   ```
3. Download and run any LLM model with Ollama:
   ```bash
   ollama run <model-name>
   ```
   Example: `ollama run llama-13b`

### Step 3 (Optional): Use with OpenAI API
If you’d prefer to use the ngrok URL with the OpenAI API schema:
1. Configure your application with these settings:
   ```plaintext
   base_url="<paste-your-ngrok-url-here>/v1"
   api_key="ollama"
   ```
2. You’re ready to integrate it into your OpenAI-compatible projects! 🎉

---

## 🎯 Example Usage
![Running the Kaggle Notebook](https://i.imgur.com/example123.png)


## 💡 Tips
- Make sure your Kaggle notebook session is active while using the ngrok URL.
- The Tesla T4 GPUs are free but have usage limits – plan your development accordingly.
- Check out [Ollama’s model library](https://ollama.ai/library) for available models.

---

## 🌍 Why This Matters
This project aims to level the playing field by giving everyone access to the GPU power needed for AI development. No expensive hardware? No problem! Let’s build the future of AI together. 🤝

---

## 📢 Contributions
Found a bug? Have an idea to improve this? Feel free to open an issue or submit a pull request! Let’s make this tool even better. 😊

---

## 🙏 Acknowledgments
- Thanks to **Kaggle** for providing free Tesla T4 GPUs.
- Shoutout to **ngrok** and **Ollama** for making this seamless.

Happy coding, and enjoy building your LLM-powered tools! 🎈
