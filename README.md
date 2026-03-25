# ymcamp41
Lehi 41st YM Camp Information for Stake YM Camp

## Registration Form

`index.html` contains the attendance registration form with:
- First & last name fields
- Attendee role (Youth / Leader)
- $10 fee submission confirmation
- Email copy sent to **lehi41st@gmail.com** on every submission

### One-time Setup (Formspree)

1. Go to [https://formspree.io](https://formspree.io) and sign in with lehi41st@gmail.com.
2. Create a new form — set the destination email to **lehi41st@gmail.com**.
3. Copy the form ID (looks like `xabcdefg`).
4. In `index.html`, replace `YOUR_FORM_ID` in the form's `action` URL:
   ```
   action="https://formspree.io/f/YOUR_FORM_ID"
   ```
5. Deploy `index.html` (GitHub Pages, Netlify, or any static host).

After these steps, every registration submission will automatically email lehi41st@gmail.com with the registrant's details.
