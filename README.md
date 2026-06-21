# Sonehara Consulting Website

A 3-page personal consulting website for UC Berkeley Haas admissions consulting.

## Files

| File | Description |
|------|-------------|
| `index.html` | Main homepage |
| `book.html` | Booking page with intake form |
| `middle-college.html` | Middle College pathway explainer |
| `style.css` | Shared styles across all pages |
| `photo.jpg` | **Add your own photo here** |

---

## Setup on GitHub Pages

1. Create a new GitHub repository (e.g. `sonehara-consulting`)
2. Upload all files in this folder to the repository root
3. Go to **Settings → Pages**
4. Under "Branch", select `main` and click Save
5. Your site will be live at `https://YOUR_USERNAME.github.io/sonehara-consulting/`

---

## Adding Your Photo

Replace `photo.jpg` with your own portrait photo. The file must be named exactly `photo.jpg` (or update the `src` in `index.html` to match your filename).

For best results: a vertical/portrait-oriented photo, well-lit, with you centered in the upper half.

---

## Connecting a Calendar (Calendly)

1. Create a free account at [calendly.com](https://calendly.com)
2. Set up your availability
3. Go to your event type → **Share** → **Embed**
4. Copy the embed code
5. In `book.html`, find the `<!-- CALENDLY EMBED -->` comment block and replace the placeholder `<div>` with your embed code

---

## Collecting Emails Privately (Formspree)

Emails from the sign-up form and booking form are sent to your email inbox using [Formspree](https://formspree.io) — they are never publicly visible.

1. Create a free account at [formspree.io](https://formspree.io)
2. Click **New Form** and name it (e.g. "Newsletter" and "Booking Intake")
3. Copy the unique form ID (looks like `xpzgkwrb`)
4. In `index.html`, find `action="https://formspree.io/f/YOUR_FORM_ID"` and replace `YOUR_FORM_ID`
5. Do the same in `book.html`
6. Submissions will land in your Formspree dashboard and be emailed to you

Free tier: 50 submissions/month. Upgrade as needed.

---

## Customization Checklist

- [ ] Add `photo.jpg`
- [ ] Replace `YOUR_FORM_ID` in `index.html` (newsletter signup)
- [ ] Replace `YOUR_FORM_ID` in `book.html` (intake form)
- [ ] Add Calendly embed to `book.html`
- [ ] Update the Middle College page content with your personal story details
- [ ] Deploy to GitHub Pages
