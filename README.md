## About Me

I'm an undergraduate Computer Science student at the **University of North Carolina at Chapel Hill**, and I live for disassembly: reverse engineering, binary exploitation, and understanding what code really does.
I’m especially interested in **backend development**, **cybersecurity**, **networking**, and **systems programming**. I enjoy building reliable, low-level systems, automating infrastructure, and experimenting with my personal network and homelab-style setups.

When I’m not debugging something, I’m usually playing games like *Minecraft* or *Factorio* or reading fiction.

---

## Security & Reversing Experience

I spend a lot of time working on CTF-style challenges and documenting how they break.

**Some of the things I’ve done:**

- **Binary exploitation**
  - Stack overflows via unsafe functions like `gets` and bad buffer layouts.
  - `ret2win` exploits by overwriting saved return addresses.
  - Using **GDB + GEF** to analyze stack frames, registers, and control flow.
  - Unwinding layered Python `exec` calls by monkey-patching `exec` to log each layer.

- **Reverse engineering**
  - Analyzing ELF binaries with **Ghidra** to recover control flow and logic.
  - Treating custom encryption as a black-box oracle and recovering flags via debugger automation.
  - Working with calling conventions, function arguments, and buffer layouts.

- **Web & file vulnerabilities**
  - Abusing PHP file uploads with `.php.jpg` polyglots to get remote command execution.
  - Exploiting weak ZIP encryption with **bkcrack** and known-plaintext attacks.
  - Manipulating PNG headers/IHDR values in a hex editor and fixing CRCs with `pngcheck`.
  - Building minimal PHP web shells and driving them with `curl`.

- **Cryptography & cracking**
  - Breaking RSA challenges by factoring `n` (FactorDB), computing λ(n), finding `d`, and decrypting `C^d mod n`.
  - Cracking encrypted Office documents using `office2john.py` + **Hashcat** (`rockyou.txt`, mode 9600).
  - Constructing MD5-collision PDFs by prepending known colliding prefixes to a base PDF.
  - Solving monoalphabetic substitution ciphers with frequency analysis and pattern reasoning.
  - Recovering rolling XOR keys from known file signatures (e.g. PNG magic bytes).

---

## Projects

### Web Security Scraper  
**Tech:** Python, sockets, BeautifulSoup (bs4)

- Built a Python socket-based client to crawl HTTP endpoints in a lab environment and collect security-relevant responses.  
- Analyzes pages and parameters to flag potential SQL injection vectors, exposed files (e.g., `robots.txt`), and outdated server headers.  
- Outputs structured scan results to prioritize suspected vulnerable routes and misconfigurations for manual validation.

### Food Finder  
**Tech:** Node.js, Express, MongoDB (Mongoose), JavaScript, HTML/CSS, Vercel

- Developed an Akinator-style web app that infers user food preferences and recommends both a cuisine and a restaurant.  
- Implemented a modular Node.js/Express backend with decision-tree logic and Mongoose models for user and restaurant data.  
- Deployed a responsive JavaScript/HTML/CSS frontend on Vercel for fast, mobile-friendly interaction.

*(More security tooling and CTF writeups are pinned on my profile.)*

---

## Relevant Coursework

**COMP 110 – Intro to Programming & Foundations**  
- Fundamental programming concepts, problem-solving, and software design basics.

**COMP 210 – Data Structures & Analysis**  
- Time and space complexity, implementation of core data structures (lists, trees, graphs, hash tables).

**COMP 211 – Systems Fundamentals**  
- Command-line/Linux workflows, data representation, memory, and low-level programming in C.

**COMP 290 – Software Development Tools & Practices**  
- Git workflows, collaboration, industry tooling, and software engineering best practices.

**COMP 301 – Foundations of Programming**  
- Object-oriented design, design patterns, software testing, and professional software development practices.

---

## Technologies

## Technologies

**Languages**  
- Python  
- C  
- Java  
- JavaScript  
- HTML/CSS  

**Security & Systems**  
- Ghidra  
- GDB / GEF  
- Linux / CLI  
- Basic pwntools and socket programming  

**Web & Backend**  
- Node.js / Express  
- REST-style APIs  
- MongoDB (Mongoose)  

**Data & Libraries**  
- pandas  
- NumPy  
- Matplotlib  

**Tools**  
- Git & GitHub  
- Docker  
- VS Code  
- IntelliJ  

---

## Technical Focus

- **Backend & Systems:** CLI-based workflows, low-level programming, debugging with GDB/GEF, and building small backend services.  
- **Security:** Reverse engineering, binary exploitation fundamentals, and CTF-style reversing/pwn problem solving.  
- **Networking & Infrastructure:** Basic server setup, network configuration, and troubleshooting; early homelab tinkering.  

---

## Contact

- Based in North Carolina, USA  
- Open to software engineering, backend, systems, and security-focused internship opportunities
- Currently seeking Summer 2025 internships in backend, systems, or security-focused software roles.

- Email: vinzy@ad.unc.edu  
- LinkedIn: https://www.linkedin.com/in/https://www.linkedin.com/in/vincent-maynard-495259325
- Résumé: [View my resume (PDF)](./Vincent_Resume.pdf)
