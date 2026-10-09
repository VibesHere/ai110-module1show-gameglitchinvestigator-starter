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
| Fresh start | 8 attempts | 7 attempts | No label associated with a form field |
| Any number | Consistent hint | Alternating hint | Incorrect use of autocomplete attribute |
| Clicked new game | New Game | Nothing | No label associated with a form field |

---

## 2. How did you use AI as a teammate?

- Which AI tools did you use on this project (for example: ChatGPT, Gemini, Copilot)?

Claude

- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result).
I can move the info near the end of the document to fix the bug I was seeing with offset attempts. 


- Give one example of an AI suggestion you did not accept as written (including what the AI suggested, why you rejected or changed it, and how you verified your version). It does not have to be a suggestion that was wrong: over-engineered, out of scope, harder to read, or a poor fit for this codebase all count.



---

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed?

I changed the project and observed a correction in the previously flawed output

- Describe at least one test you ran (manual or using pytest)  
  and what it showed you about your code.

I gave an input as a standard user would for this project (numbers) and observed the wrong output, as my flounderish attempts at finding the right result was doomed as my hints lead me astray from the one true answer.

- Did AI help you design or understand any tests? How?

No, the problems I had were easy to test for as a human, and any testing I did was natural or logical. 

---

## 4. What did you learn about Streamlit and state?

- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?

---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?
  - This could be a testing habit, a prompting strategy, or a way you used Git.
Utilizing my intuition as an engineer to read and understand the code before using AI to help. 

- What is one thing you would do differently next time you work with AI on a coding task?

Remembering that not everything it does is perfect, its my responsibility to verify the output of my work.

- In one or two sentences, describe how this project changed the way you think about AI generated code.

AI generated code can often have bugs that affect the quality and performance of your programs. It can easily be swayed but with supervision you can get accurate results. 
