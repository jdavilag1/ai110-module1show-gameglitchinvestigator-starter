# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started?

- What did the game look like the first time you ran it?
- List at least two concrete bugs you noticed at the start  
  (for example: "the hints were backwards").

**Bug Reproduction Log**

Document at least 3 bugs you found. Add rows as needed.

| Input | Expected Behavior | Actual Behavior | Console Output / Error |
|-------|-------------------|-----------------|------------------------|
| guess of 0 | should tell it to go higher | instead says to go lower | cant be less than 0 |
|guess of 3 | hint should be go higher| says to go lower, even though the number was 51| incorrect hint|
|when starting again | should restart | doesn't restart the game, stuck on game over screen |  unable to start again |

---

## 2. How did you use AI as a teammate?

- Which AI tools did you use on this project (for example: ChatGPT, Gemini, Copilot)?
I used Copilot on this project.
- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result).
One example of an AI suggestion was that when I mentioned that when the hints were doing the opposite of what it should be doing it suggested to indeed fix those reversed hints. So,  having known that bug before it was fixed only to use that suggestion to correctly receive true hints was how I verified the result.
- Give one example of an AI suggestion that was incorrect or misleading (including what the AI suggested and how you verified the result).
One example that was misleading was that it claimed to have fixed something but I was still receiving the error, the error being that the game logic was fine but when running pytest it wasn't. So i had to double check that code.

---

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed?
I decided it was fixed when I ran the streamlit command again to check if the game was working properly.
- Describe at least one test you ran (manual or using pytest)  
  and what it showed you about your code.
  I folowed the directions and used pytest so that it passes.
- Did AI help you design or understand any tests? How?
In a way it did, it helped me realized if I had anything wrong.

---

## 4. What did you learn about Streamlit and state?

- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?
I'm actually pretty new to Streamlit myself, and I used copilot to help me. For the "reruns" i simply just used the command again to generate a new session with the updated code.

---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?
A strategy I would like to reuse in future labs or projects is that given that this course focuses on using AI as a tool, I'd probably want to make sure my prompts are as specific as possible in order to make sure what's needed would be properly fixed.
 
- What is one thing you would do differently next time you work with AI on a coding task?
I would probably not try to rely on it too much or 100% blindly trust any changes without test running it first.
- In one or two sentences, describe how this project changed the way you think about AI generated code.
This project changed the way I think about AI generated code because I used ot think it was a bit lackluster to use AI but seeing that it could be used to fix bugs while also the user simultaneously contributes is a good thing. I like the idea of using it as only a tool and not the main course of action.
