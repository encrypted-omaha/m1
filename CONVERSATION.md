# Project Conversation Log

## Session 1 - May 10, 2026

### User Request
- Create a static website from the PGP_Party.png design
- Make text easily changeable
- Make "Contact" at the bottom an email link
- Make "RSVP" open a URL in another window/tab
- Change "Cypherpunk Collective" to "Privacy People" (lower right)

### Actions Taken
1. Analyzed the PNG design for "Pizza and Privacy" event
2. Created `index.html` - the main website
3. Created `config.js` - easy-to-edit configuration for all text content
4. Created `styles.css` - styling to match the poster design

### Files Created
- `index.html` - Main website
- `config.js` - Edit this file to change any text
- `styles.css` - Styling
- `CONVERSATION.md` - This file

### Design Notes
- Dark cyberpunk theme matching the original poster aesthetic
- Contact link uses `mailto:` for email
- RSVP link uses `target="_blank"` to open in new tab
- "Privacy People" replaces "Cypherpunk Collective" in lower right
- All text is configurable via `config.js`

### How to Edit Text
Open `config.js` and modify any of these values:
- `title` - Main heading
- `subtitle` - Anniversary text
- `location` - Room/venue
- `date` - Event date
- `sectionTitle` - "GPG KEY EXCHANGE" section
- `description` - Main body text
- `contactEmail` - Email address for contact link
- `rsvpUrl` - URL for RSVP button
- `organization` - Organization name (lower right)

---
