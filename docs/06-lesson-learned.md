# 06 - Lesson Learned

- **Diagnosis tooling matters as much as the fix**. Using Autoruns instead of Task Manager for Case 3 wasn't just cosmetic, it surfaces autostart location that Task Managerr misses entirely, which is directly relevant to spotting real malware/junkfile in production.

- **Not every diagnostic tool behaves identically**. Autoruns didn't index every shortcut the same way Explorer or Task Manager did (a quirk encountered with `calc.exe`/`notepad.exe` shortcuts), a reminder that tools have their own scanning logic and blind spots, and cross-checking with a second tool is good practice.

- **Attended** vs. **unattended access** is a meaningful security distinction, not just a technical detail, worth understanding for any support role that touches client/company machines.