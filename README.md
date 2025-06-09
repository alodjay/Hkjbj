If your goal is to increase the **view count** (or play count) on a music link (like [your Radio Javan song](https://play.radiojavan.com/song/behzad-leito-sijal-chikar-kardi-(ft-sepehr-khalse-heliyom))) by simply opening or playing the link every 2 minutes, here is what you should know:

---

### 1. **How Play/View Counting Usually Works**
- Most platforms (like Radio Javan, YouTube, Spotify, etc.) count unique plays/views based on user sessions, cookies, device IDs, IP addresses, or even logged-in accounts.
- Repeatedly opening the link from the same device/browser within a short period may **not** always increase the public view count, as platforms often have protections to prevent artificial inflation.

---

### 2. **Manual Method**
- You can manually open the link in your browser, wait 2 minutes, close it, and repeat.
- This may only increase your local session count; the platform may not count every repeat as a new view, depending on their detection system.

---

### 3. **Automated Method (For Learning Purposes)**
If you’re a developer and want to automate this for **testing** (not for violating terms of service!), you could use a script. Here’s a simple **Python example** for educational purposes:

```python
import webbrowser
import time

url = "https://play.radiojavan.com/song/behzad-leito-sijal-chikar-kardi-(ft-sepehr-khalse-heliyom)"

while True:
    webbrowser.open(url)
    time.sleep(120)  # Wait 2 minutes (120 seconds)
```

- **Note:** Most browsers will open a new tab each time, which can quickly become overwhelming.
- **Ethics:** Repeatedly opening a link to artificially increase play/view counts can violate the platform’s rules.

---

### 4. **Mobile App (Android/iOS)**
- You could make a simple app to open a URL every 2 minutes, but app stores may reject apps for this purpose.
- This method will face the same counting protections as above.

---

### 5. **Summary**
- Simply refreshing or replaying the link every 2 minutes doesn’t guarantee an increase in official view/play counts.
- Most services have protections against this kind of behavior.
- Always respect the platform’s terms of service.

---

**If you’d like code for a particular platform (Android, iOS, desktop), or want to understand how real view counting works on a service, let me know!**