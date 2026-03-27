# Docker Python Info

#programming challenge
Run a Python Info Script inside Docker (simulated with online compiler).

---
## Objective
- Write a simple Python script  
- Push it to GitHub  
- Run it inside a container / sandbox environment  
- Capture output  

---

##  Steps Followed
1. **Created `info.py`**  
   ```python
   import os
   import socket
   import datetime

   print("=== SYSTEM INFO ===")
   print("Time:", datetime.datetime.now())
   print("Hostname:", socket.gethostname())
   print("Current Files:", os.listdir())
   print("User:", os.getlogin())
