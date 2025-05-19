# Exno.3-Scenario-Based Report Development Utilizing Diverse Prompting Techniques
### DATE: 12-May-2025                                                                            
### REGISTER NUMBER : 212222230116 
### Aim: 
  To design an AI-powered chatbot that assists customers in resolving issues related to product troubleshooting, order tracking, and general inquiries. The chatbot should handle various customer queries efficiently while maintaining a conversational and user-friendly tone. In this experiment, we will employ different prompt patterns to guide the development process of the chatbot, ranging from basic task-oriented prompts to more complex, persona-driven prompts.

### Algorithm:  
### 1. Direct Instruction Prompting
- What it is: Tells the chatbot exactly what to say.
- Why use it: Ensures the bot gives a precise, correct response every time.

### Prompt:
"When a customer asks how to check their data balance, reply with:
'To check your data balance, dial *123# or log into the Telconet app and view your usage on the dashboard.'"

### Bot Response:
*"To check your data balance, dial 123# or log into the Telconet app and view your usage on the dashboard."

### 2. Contextual Prompting
- What it is: Uses earlier messages to shape the current response.
- Why use it: Makes the bot feel more human and aware of the conversation.

### Prompt:
"If a customer previously mentioned that they experienced a call drop, respond with:
'You mentioned a dropped call earlier—let me check the signal strength in your area and assist further.'"

### Bot Response (when context exists):
"You mentioned a dropped call earlier—let me check the signal strength in your area and assist further."

### 3. Persona-Based Prompting
- What it is: Gives the bot a specific personality or tone.
- Why use it: Builds emotional connection and keeps the experience friendly.

### Prompt:
"Act as a cheerful support agent named Max. Use friendly language like,
'Hey! I totally get how frustrating that is—let me help you fix it ASAP!'"

### Bot Response:
"Hey! I totally get how frustrating that is—let me help you fix it ASAP! Just a sec while I look into it."

### 4. Few-Shot Prompting
- What it is: Provides a few examples so the bot learns the pattern.
- Why use it: Helps the bot generalize responses to similar but new inputs.

### Prompt with examples:

"My internet is slow." → "Try restarting your modem. If it doesn't help, I can run a diagnostic."

"I can’t make outgoing calls." → "Check if your outgoing call limit has been reached or try restarting your device."
Now respond to:
"I’m getting no signal at home."

### Bot Response:
"Let’s check the network coverage in your area. Have you tried turning Airplane Mode on and off or restarting your phone?"

### 5. Chain of Thought Prompting
- What it is: Guides the bot to solve problems step by step.
- Why use it: Improves reasoning and gives clearer, more helpful answers.

### Prompt:
"When a customer says their Telconet router isn’t connecting to the internet, respond by:
- Asking if the router lights are blinking normally.
- Guiding them to restart the router.
- Checking if other devices are facing the same issue.
- Recommending a reset if the issue persists."

### Bot Response:
"Let’s troubleshoot this step-by-step. First, are the router lights blinking normally? If not, please unplug the router, wait 30 seconds, and plug it back in. Are other devices also having trouble connecting? If so, we may need to reset the router or check the service status in your area."

### 6. Instruction with Constraints
- What it is: Gives rules like length or tone the bot must follow.
- Why use it: Ensures replies are short, simple, and user-friendly.

### Prompt:
"Answer questions about billing in under 40 words and avoid technical terms. Example:
'Your bill is due on the 10th. You can pay via the app or website. Let me know if you need help with the steps!'"
Now respond to:
"Can I pay my bill later this month?"

### Bot Response:
"Yes, you can pay by the 25th without a late fee. Let me know if you'd like a reminder!"

### 7. Reflective Prompting
- What it is: Repeats or reflects part of the question before answering.
- Why use it: Shows understanding and makes the bot seem thoughtful.

### Prompt:
"When someone asks about changing their phone number, reflect the question back first. Example:
'You're looking to change your number, right? I can help you with that—here’s how…'"
Now respond to:
"Can I get a new number with the same plan?"

### Bot Response:
"You want to switch to a new number but keep the same plan, right? Yes, that’s possible! I can help you with the process—it just takes a minute."

### Tabular form:
![Screenshot 2025-05-19 162911](https://github.com/user-attachments/assets/65c172d3-7b67-4a64-96eb-5651789f7f67)





# Result: 
Thus the Prompts were exected succcessfully .

