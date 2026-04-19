# ChatAI

👨‍🍳 GenAI Virtual Chef (Chef Buddy)

Goal Built a conversational cooking assistant powered by Gemini that suggests personalized recipes based on dietary restrictions and skill level — keeping all responses warm, fun, and food-focused.

Tech Stack Python, Google Gemini 2.5 Flash (google-genai SDK), Prompt Engineering, Stateful Multi-turn Chat, System Instructions

Challenges & Solutions 

  • Keeping the bot on-topic → Engineered a strict system prompt that redirects any non-food questions back to cooking, enforcing a focused persona 
  
  • Personalization without a database → Designed the bot to always collect dietary restrictions and skill level before suggesting any recipe, making responses feel tailored 
  
  • Beginner-friendly UX → Implemented a rule capping recipes at 6 ingredients for beginners and requiring jargon to always be explained in plain terms 
  
  • Persona consistency → Defined a distinct character (Chef Buddy) with a fixed voice and humor, preventing tone drift across a long conversation

Impact Delivered a stateful multi-turn chatbot that adapts recipe complexity to the user's skill level, making home cooking more accessible and engaging through a consistent, personality-driven experience.

📚 GenAI Study Buddy

Goal Built an AI-powered tutoring chatbot using Gemini that helps students learn any academic topic — one concept at a time — with built-in quizzing, encouragement, and guardrails against doing homework for them.

Tech Stack Python, Google Gemini 2.5 Flash (google-genai SDK), Prompt Engineering, Stateful Multi-turn Chat, System Instructions

Challenges & Solutions 

• Preventing academic dishonesty → Hard-coded a rule in the system prompt blocking direct homework answers, redirecting students toward understanding instead 

• Avoiding cognitive overload → Designed the bot to address one question at a time and confirm understanding before moving on, mimicking a real tutor's pacing 

• Handling wrong answers gracefully → Built in a hint-first escalation flow so incorrect responses get encouragement and clues before the answer is revealed 

• Jargon accessibility → Required all technical terms to be followed by a plain-language explanation, lowering the barrier for any subject

Impact Delivered a patient, structured AI tutor that reinforces learning through active recall and guided questioning — not answer-giving — creating a safer and more effective study experience for students.
