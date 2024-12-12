# Run LLMs in the Cloud Using Google Colab and Ngrok

This repository contains a simple guide and code to help you run large language models (LLMs) in the cloud using **Google Colab** and **Ngrok**, keeping your local machine safe from heavy resource usage. Follow these instructions to set up your environment and get started.

## Prerequisites

1. A **Google Colab** account.
2. An **Ngrok** account. You’ll need to generate an authentication token from [Ngrok](https://ngrok.com/) and use it for configuration.
3. Install OLLAMA from here: [Ollama](https://ollama.com/) on your local machine.
4. Just upload the ipynb file found in this repo to colab and let the magic happens

## Setting Up Ollama URL in Your Environment Variables

To ensure the service runs seamlessly, you need to set the Ngrok URL as an environment variable on your local machine. Here’s how to do it on various operating systems:

### For Linux/macOS

1. Open your terminal.
2. Add the Ollama URL as an environment variable using the following command:

   ```bash
   export OLLAMA_HOST=<your-ngrok-url>
   ```

### For Windows (Command Prompt)

1. Open Command Prompt.
2. Set the environment variable using the following command:

   ```cmd
   set OLLAMA_HOST=<your-ngrok-url>
   ```

### For Windows (PowerShell)

1. Open PowerShell.
2. Set the environment variable using the following command:

   ```powershell
   $env:OLLAMA_HOST = "<your-ngrok-url>"
   ```

## Steps to Run the Project

1.Simply download the ipynb file attached in this repo and load it in your colab account and let the games begin!!!

## Additional Notes

- Make sure your Ollama URL is configured correctly as an environment variable. Without this, the service may fail to start.
- Update your Ngrok authentication token in the Colab notebook as instructed.

## Support

If you encounter any issues or have questions, feel free to open an issue in this repository. We’re here to help!

---

**Don’t forget to give this repository a star if you found it useful!** ⭐

