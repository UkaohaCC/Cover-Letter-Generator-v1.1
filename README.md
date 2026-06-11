# Cover-Letter-Generator-v1.1

A free, browser-based tool that uses AI to generate a tailored, professional cover letter in seconds. Just enter your details, paste the job description, and get a ready-to-send letter.

No backend. No server. No account needed. Just open the HTML file and go.

---
## Features

- **Tailored letters** :matches your skills directly to the job description
- **4 tone options** :Professional, Confident, Friendly, or Formal
- **Regenerate** :get a fresh version with one click
- **Edit output** :tweak the letter directly in the app before copying
- **One-click copy** :copies the full letter to your clipboard instantly
- **History** :saves your last 20 generated letters in the browser
- **Your key, your browser** :Gemini API key is stored locally, never exposed in code
- **Fully free** :you bring your own Gemini API key

---

## How to Use

1. **Download or clone this repo**
   ```bash
   git clone https://github.com/UkaohaCC/Cover-Letter-Generator-v1.1.git
   ```

2. **Open `index.html` in your browser**
   - No install needed. No terminal. Just double-click the file.

3. **Get a free Gemini API key**
   - Go to [aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey)
   - Sign in with a Google account
   - Click **Create API key** and copy it

4. **Enter your key in the app**
   - Paste it into the API Key field at the top
   - Click **Save**, stored in your browser only, never in the code

5. **Generate your cover letter**
   - Enter your name, the company name, and your skills
   - Paste the job description
   - Pick a tone
   - Click **Generate** and wait a few seconds
   - Edit, copy, and send!

---

## Tech Stack

| Layer | Technology |
|---|---|
| Structure | HTML5 |
| Styling | CSS3 |
| Logic | Vanilla JavaScript |
| AI | Google Gemini API (`gemini-2.5-flash-lite`) |
| Storage | Browser localStorage |

No frameworks. No build tools. No dependencies.

---

## Privacy & Security

- Your API key is **never stored in the source code**
- It lives only in your own browser's `localStorage`
- Your details and job description are sent directly from your browser to Google's Gemini API ...nothing passes through any third-party server
- Generated letters and history are stored locally in your browser and never uploaded anywhere

---

## Tips for a Better Letter

- **Be specific with your skills** :instead of "good communicator" write "led a team of 5 and presented weekly to stakeholders"
- **Paste the full job description** :the more detail the AI has, the more tailored the letter
- **Use Regenerate** :run it 2-3 times and pick the best version
- **Always edit before sending** :add personal touches the AI can't know about

---

## Limitations

- **Free API tier** allows 30 requests/minute and 1,500/day ...more than enough for personal use
- **Job descriptions** are trimmed to 3,000 characters before being sent to the AI
- AI-generated letters should always be reviewed and personalised before sending

---

## License

MIT License — free to use, modify, and share.

---

Built by Me using HTML, CSS, JavaScript, and the Google Gemini API.
