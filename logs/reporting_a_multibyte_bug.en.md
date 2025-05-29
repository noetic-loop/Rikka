
## When Japanese Text Disappears： Reporting a Multibyte Bug in ChatGPT’s PDF Export

###### 2025/05/07
---
**License:** CC BY-NC 4.0  
**Author:** [Rikka](https://github.com/noetic-loop)  
**Details:** [creativecommons.org/licenses/by-nc/4.0](https://creativecommons.org/licenses/by-nc/4.0/)

---

**1. Introduction**

While most of the feedback and development around AI tools is conducted in English, issues affecting non-English users often remain in the background. As a Japanese user, I encountered a quiet but persistent problem: certain Japanese characters were disappearing—sometimes replaced with blank boxes—when exporting content to PDF via ChatGPT.

This post is not a technical analysis, nor a complaint. It’s simply a record of what happened, what I did, and why this matters.

**2. The Bug: What Happened**

When exporting documents that included Japanese text to PDF using ChatGPT, I noticed that certain characters—especially more complex kanji—did not render properly. Instead of text, the output showed corrupted glyphs or simply blank boxes.

The issue did not occur in Word format. The same content exported as a .docx file displayed all characters correctly. This strongly suggested that the problem was not with the model’s output, but with the PDF rendering engine—likely related to font fallback or Unicode handling for multibyte characters.

In short: text was disappearing quietly, but consistently.

**3. What I Did**

I wasn’t sure if the issue was known or if it only affected my environment. But given how cleanly the same document rendered in Word, I suspected it was systemic.

So I did what I could: I wrote a short report in English, explained the behavior clearly, and attached two files—one Word document and one PDF exported from it. The difference was obvious. I sent this through the ChatGPT help center’s support chat, hoping it would reach the right team.

To my surprise, a human responded quickly. They confirmed the issue and said it would be forwarded to the development team. No further action was needed on my part.

**4. Why This Matters**

Issues with multibyte characters are not uncommon when exporting content across different formats. PDF rendering engines often rely on default font sets and character mapping behaviors, which may quietly fail when dealing with complex writing systems—without producing errors or visible warnings.

In this case, the system didn’t crash or display any alerts. The characters were simply gone, without notice. They appeared normally in Word format, but the same content exported to PDF would turn into blank boxes or vanish entirely. It didn’t seem like a major problem at first, but the behavior was consistent. A quiet kind of fatigue and inconvenience starts to build—“Ah, this again.”

When a system drops data without warning, you only realize it later—when you're trying to figure out what disappeared. It's not just the extra work it causes. It’s the quiet wear that follows. This isn’t rare. Many users likely encounter similar situations. It’s not just about being “inconvenient”—sometimes, it quietly removes the tool from your list of usable options.

**5. Closing Thoughts**

This wasn’t a major issue. Nothing crashed. Nothing burned.

But something did quietly disappear.

I’m writing this not to complain, but to document. To make something quietly missing… slightly more visible.

Even if it doesn’t get fixed right away, someone else might notice it sooner.

And if they do, they won’t have to wonder if it was just them.

This isn’t meant to point a finger at anyone.

Building systems like these is incredibly complex.

I only hope this note helps make a small invisible thing a little more visible.

---

© Rikka, licensed under CC BY-NC 4.0  
https://creativecommons.org/licenses/by-nc/4.0/

