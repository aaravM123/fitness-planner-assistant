
# 🏋️ Fitness Planner AI Assistant

This is a memory-aware AI assistant built using OpenAI GPT-4o. It uses **function calling, token-by-token streaming**, and a memory log to help users plan workouts, meals, and goals over multiple messages.

---

## 💡 Features
- 🧠 Remembers previous user messages and GPT responses
- ⏳ Streams replies word-by-word for a real-time feel
- 📋 Tracks prompts and responses in a memory log
- 💬 Continues conversations like a true AI assistant

---

## 🧪 Example Prompts
```python
stream_with_memory("I want to get lean and strong. I can work out 3 days a week.")
stream_with_memory("I prefer bodyweight workouts at home.")
stream_with_memory("Give me a meal plan suggestion for this goal.")
