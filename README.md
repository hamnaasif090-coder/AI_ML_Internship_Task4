# General Health Query Chatbot

## Task Objective
Develop a chatbot that answers general health-related questions using a large language model (LLM). The chatbot should provide friendly, clear, and safe information while encouraging users to consult healthcare professionals when necessary.

## Dataset Used
- No structured dataset is required. The chatbot leverages the pre-trained knowledge of the Mistral-7B-Instruct model (Hugging Face).

## Models Applied
- **Mistral-7B-Instruct**: Instruction-tuned large language model capable of understanding user prompts and generating informative responses.
- **Safety Filter**: Rule-based filter to block queries requesting specific medications, dosages, treatments, or diagnoses.

## Key Results and Findings
- The chatbot successfully answers general health questions in a clear and professional tone.
- Example queries like:
  - *“What causes a sore throat?”*
  - *“Is paracetamol safe for children?”*
  received informative and safe responses.
- Queries requesting medical treatment, such as *“What medication should I use for my child's fever?”*, are intercepted by the safety filter and return a standard advisory message.
- Prompt engineering is essential for guiding the LLM to provide helpful, safe, and context-aware responses.
- The system demonstrates that LLM-based chatbots can deliver reliable general health information while minimizing the risk of unsafe advice.

