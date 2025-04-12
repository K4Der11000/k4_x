
# K4X Suite - Offensive Web Toolkit

This project includes a full web-based hacking-style toolkit with the following modules:

## Included Tools

1. **IPTV Stream Analyzer**
   - Browse global TV channels by continent/country.
   - Filter channels by category (News, Sports, Movies, etc).
   - Add channels to your favorites (saved in browser).

2. **Hash Cracker**
   - Upload or paste hashes.
   - Select hashing algorithm.
   - Crack hashes and show results in terminal-style output.

3. **URL Brute Forcer**
   - Enter base URL and wordlist.
   - Supports custom thread count, proxies, and live result output.
   - Terminal-like result display with live progress bar.

4. **Email Extractor**
   - Paste HTML or upload HTML files.
   - Crawls and extracts valid email addresses from web pages or files.

## How to Run

### Requirements

- Python 3.8+
- Install dependencies:
```bash
pip install flask requests
```

### Start the App

```bash
python app.py
```

Then open your browser at: [http://localhost:5000](http://localhost:5000)

## Notes

- All tools are unified under one main interface with tabbed navigation.
- Data is not sent to external servers unless using live proxy or streaming tests.
- IPTV data is organized by continent/country with real stream links.

---

Author: kader11000
