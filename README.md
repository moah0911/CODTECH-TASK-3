# CODTECH-TASK-3
Here’s a description you can use for your GitHub repository:

---

### **Chatbot with Weather and Calculator Features**

This Python-based chatbot is designed to interact with users through simple text-based commands. It leverages the OpenWeatherMap API for weather queries and Python's `eval()` function for basic arithmetic calculations. The chatbot can perform the following functions:

1. **Weather Information**:
   - Users can ask for the weather in a specific city (e.g., "What's the weather in London?").
   - The chatbot fetches the current weather details such as temperature and weather description using the OpenWeatherMap API.
   
2. **Basic Arithmetic Calculator**:
   - Users can input simple arithmetic expressions like "5 + 3", "10 - 2", etc., and the chatbot will compute the result.
   - It supports addition, subtraction, multiplication, and division operations.

3. **Greeting and Farewell**:
   - The chatbot can respond to greetings like "Hello!" and say goodbye with a farewell message.

4. **Error Handling**:
   - The chatbot provides a default response for unrecognized input, asking the user to rephrase their query.

---

### **How It Works**

1. **Weather Queries**:
   - The chatbot recognizes phrases related to weather (e.g., "What's the weather in [City]?") and fetches weather details using the OpenWeatherMap API.

2. **Calculator**:
   - The chatbot processes user-provided arithmetic expressions and returns the computed result.

3. **User Interaction**:
   - The chatbot continuously interacts with the user until the user types "exit" to quit the session.

### **Technologies Used**
- Python
- OpenWeatherMap API
- `eval()` for arithmetic calculations
- Basic error handling for invalid expressions and commands

### **Usage**
1. Install the `requests` library:
   ```bash
   pip install requests
   ```

2. Replace the `API_KEY` in the script with your own OpenWeatherMap API key.

3. Run the script:
   ```bash
   python chatbot.py
   ```

### **Example Interaction**:
```
Chatbot: Hello! How can I assist you today? (Type 'exit' to quit)
You: hello
Chatbot: Hello! How can I assist you today?
You: What's the weather in London?
Chatbot: The temperature in London is 15°C with light rain.
You: Calculate 5 + 3
Chatbot: The result of 5 + 3 is 8
You: Goodbye
Chatbot: Goodbye! Have a great day!
```

---

This description provides a clear overview of the chatbot's functionality and gives easy-to-follow instructions for running the script on any machine. You can modify or extend it as per your requirements.
