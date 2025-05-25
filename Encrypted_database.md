# Encrypted database 🔐

**Platform:** CyberTalents  
**Category:** Web Exploitation  
**Difficulty:** Easy  
**CTF Type:** Jeopardy-style  
**Status:** Solved  
**Flag:** (Redacted for ethical reasons)

---

## 🗄️ My Fifth CTF Challenge

**"Encrypted database"** was a web challenge that introduced me to manual URL manipulation and basic network inspection.

Without using advanced tools at the time, I learned how to explore the application by changing URLs manually to find hidden pages, like the admin page.

---

## 🧠 What I Learned

- How to manually manipulate URLs to discover hidden or restricted pages.
- How to inspect network requests and responses using browser DevTools.
- How usernames and passwords are transmitted between client and server.
- How to use online tools to reverse MD5 hashes and decrypt hidden flags.

---

## 🛠️ Tools Used

- **Browser DevTools (Network tab)** – to observe requests and responses.
- **Manual URL manipulation** – to find hidden pages or endpoints.
- **Online MD5 reverse tool** – to decrypt MD5 hashes and find the flag.
- **External IDE** – to better read and analyze code snippets.

---

## 📝 My Process (High-Level Overview)

1. Started by manually changing the URL in the browser’s address bar to discover a hidden admin page.
2. Inspected the page’s source code and used **DevTools Network tab** to monitor data sent between client and server.
3. Found where usernames and passwords were submitted.
4. Identified an MD5 hash suspected to contain the flag.
5. Used an online MD5 reverse lookup tool to decrypt the hash and reveal the flag.

---

## 📌 Takeaway

**"Encrypted database"** was a great lesson in **basic web exploration and cryptanalysis**. It showed me that sometimes, simple manual techniques combined with careful inspection can reveal valuable information.

This challenge boosted my confidence to dive deeper into web security and hashing concepts.

---

> 💬 *This write-up is for educational purposes only. The challenge has been solved and shared in a way that respects CyberTalents’ rules and the CTF community.*
