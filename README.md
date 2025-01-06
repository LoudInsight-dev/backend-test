# Backend Development Test with Node.js 🛠️

Welcome to the **Royal Backend Challenges**! This test will take you on a journey through exciting coding adventures. Complete these challenges to prove your backend mastery.

---

## Challenge 1: **Build Your Own Tiny Kingdom (URL Shortener)**  
You are the king of a small kingdom, and you've decided to build a magical portal system that shortens paths between cities.  

### Task  
1. Create a magical portal system (a URL shortener service):  
   - Create an endpoint where travelers (users) can register a "long path" (URL) and receive a "short portal ID" (shortened URL).  
   - Store the mappings in a treasure map (in-memory object).  
   - Create another endpoint where travelers can use the "short portal ID" to teleport back to the original city (original URL).  

2. Ensure the portal ID is short and unique (e.g., a random alphanumeric string).  

### Bonus  
- Prevent the evil wizard from creating duplicate entries!  
- Test your solution with edge cases (e.g., duplicate long URLs).  

🎯 **Hint:** Remember, your portal IDs should always remain unique and magical!  

---

## Challenge 2: **The Mischievous Goblin and the Event Loop**  
A mischievous goblin has scrambled the order of tasks in your royal message delivery system (event loop). Can you fix it?  

### Task  
Write a Node.js script to simulate your royal message flow:  

1. Announce: "The King has entered the court" (`console.log`).  
2. Schedule a bard (file reader) to sing a song asynchronously (`fs.promises.readFile`).  
3. Schedule a jester's act (`setTimeout` callback for 0 ms).  
4. Let the king's advisor (`process.nextTick`) whisper: "Your Majesty, there’s an urgent matter."  
5. Announce: "The court session has ended."  

### Goal  
- Observe the order of the announcements and explain why they appear as they do.  

🎯 **Hint:** Understand how Node.js handles `process.nextTick` and `setTimeout` callbacks to outsmart the goblin.  

---

## Challenge 3: **The Hierarchical Wizard Library**  
You are the librarian of a wizard's library, where books are categorized by their magical properties. Your job is to organize them hierarchically!  

### Task  
1. Create a data structure to store categories (e.g., "Potions") and subcategories (e.g., "Healing Potions", "Mana Potions").  
2. Write scripts to:  
   - Add a new category (e.g., "Spells").  
   - Add a subcategory under an existing category (e.g., "Fire Spells" under "Spells").  
   - Retrieve and print all subcategories under a given category.  

### Bonus  
- Use MongoDB and the Materialized Path pattern for efficient retrieval of subcategories.  

🎯 **Hint:** The wizard expects quick responses – or risk being turned into a frog!  

---

Good luck, and may your code be bug-free! 🚀


