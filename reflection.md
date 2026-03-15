# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started?

- What did the game look like the first time you ran it?
- List at least two concrete bugs you noticed at the start  
  (for example: "the hints were backwards").
  The difficulty doesnt reset
  When it was one normal I guessed 100 and said go lower,guessed 99 then said go higher despite the range is 1-100
  The hard difficulty is easier than Normal

---

## 2. How did you use AI as a teammate?

- Which AI tools did you use on this project (for example: ChatGPT, Gemini, Copilot)?  Claude
- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result). AI suggested Hard difficulty was easier than Normal and I verfied this by changing the difficulty on the website and saw it was true deu to the range of hard being smaller
- Give one example of an AI suggestion that was incorrect or misleading (including what the AI suggested and how you verified the result).


--- AI was wrong about the hints saying the order was wrong but indeed was correct

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed?  I decided the bug was really fixed when i tested it myself and saw the code was working perfectly also used a pytest case
- Describe at least one test you ran (manual or using pytest)  i started a new game adn the answer was 92 when i guessed 98 it said go lower and when i guessed 50 it said go higher
  and what it showed you about your code.
- Did AI help you design or understand any tests? How? yes it did , it helped me test my code in every possible case adn gave me an explaination for doing such

---

## 4. What did you learn about Streamlit and state?

- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?
Streamlit "reruns" the entire script runs from top to bottm every time the user interacts with the app take it as refershing a webpage automatically whenever the user does something. WHile Session state is about the the variables reseting each time the code runs in the sense of a new game it gives us new attmpts and a new secret number

---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?
- This could be a testing habit, a prompting strategy, or a way you used Git.
One habit I would love to resuse in future projects would be the act of using ai to help me generate test cases for my bugs i fixed
- What is one thing you would do differently next time you work with AI on a coding task?
i woudl take time to identify all files im working on with the ai and always start a new chat for each section
- In one or two sentences, describe how this project changed the way you think about AI generated code.
Now i feel i understand how coding with ai works instead of just copy and paste this time I actually worked with the ai served more as my tool than the one doing the work.
