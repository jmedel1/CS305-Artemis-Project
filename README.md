# CS305-Artemis-Project

## Project Overview

This project was part of CS 305: Software Security. I looked at the software used by Artemis Financial, found security problems in the code, and explained how to fix them to make the system safer.

## Reflection

### Who was the client and what did they need?
The client was Artemis Financial. They handle money and customer information, including international transactions. They wanted help finding and fixing security problems in their software to protect their data and follow rules for safe communication.

### What did I do well and why does secure coding matter?
I found several security issues in the code, like missing input checks, open data fields, and old libraries with known problems. Writing secure code is important because it keeps customer info safe, builds trust, and helps avoid things like fraud or data leaks.

### What was hard or helpful about the assessment?
Looking through the code by hand helped me understand where problems could happen. Using the static testing tool (Dependency-Check) was a bit tricky at first, but it showed how important it is to update old software libraries.

### How did I improve the security?
I suggested adding input checks, hiding sensitive data, and updating unsafe libraries. In the future, I would use tools like Dependency-Check and regular code reviews to find problems and figure out the best ways to fix them.

### How did I check that the code was still working and secure?
After making changes, I tested the code to make sure it still worked. I also ran a scan to see if any new problems were added. This helped me confirm the code was both safe and working.

### What tools or tips will help me later?
I found tools like OWASP Dependency-Check and secure coding habits (like input validation and hiding data) really helpful. I’ll keep using these in future projects.

### What can I show to employers from this?
This project shows that I can find and fix security problems in code, follow good coding practices, and explain my work clearly. It’s a good example of my skills in software security.
