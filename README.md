## Local Opensource Appliance

This is an open-source application designed to interact with locally hosted Large Language Models (LLMs) on your system. It provides multiple interfaces and functionalities for seamless communication with these models.

### Key Features

* **Local LLM Interaction:** Interact with various LLM models hosted on your local machine.
* **WebSocket Interface:** Communicate with models in real-time over your local network, enabling applications like chatbots on your phone interacting with your local LLM.
* **Swagger API:** Interact with models using JSON data through a well-defined Swagger endpoint.
* **Built-in Modules:**
    * `UserThreads`: Manages user connections and interactions efficiently.
    * `ModelThreads`: Handles model loading, processing, and responses.
* **Environment Control:** Control various model parameters through environment variables.
* **Real-time Model Switching:** Change the LLM model used during a WebSocket conversation.
* **Contextual Awareness:** Remembers previous conversations for contextually relevant responses.
* **Simple Model Loading:** Specify the model path through a dedicated environment variable.

### Getting Started

1. **Prerequisites:**
    * Python 3.x
    * Necessary dependencies (listed in `requirements.txt`)
2. **Installation:**
    ```bash
    git clone [https://github.com/your-username/local-llm-appliance.git](https://github.com/your-username/local-llm-appliance.git)
    cd local-llm-appliance
    pip install -r requirements.txt
    ```
3. **Configuration:**
    * Set the path to your desired LLM model in the `.env` file.
    * Adjust any additional environment variables as needed.
4. **Running the Application:**
    ```bash
    python main.py
    ```

### Usage

Once the application is running, you can interact with the LLM models through the provided interfaces:

* **WebSocket:** Use a WebSocket client to connect to the specified port (default: 8765) and send JSON messages for model interaction.
* **Swagger API:** Utilize the Swagger UI or any compatible API client to interact with the model using JSON requests.

For detailed usage instructions and examples, refer to the provided documentation within the repository.

### Contributing

Feel free to fork the repository, propose improvements, and submit pull requests.
