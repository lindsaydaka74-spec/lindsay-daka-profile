# lindsay-daka-profile
A semantic HTML5 profile and mini‑portfolio page showcasing my skills, contact form, and accessibility features for Web Technologies assignment

#See [PROMPT_LOG.md](./PROMPT_LOG.md) for the full prompt, the AI's raw output, my edited final version, and a reflection on the changes I made

## Accessibility: Peer Review Issue & Fix
**Issue found by peer reviewer (Thursday's practical session):**
During Thursday's practical session, one of my classmates reviewed my page and pointed
out that my profile image had no `alt` attribute at all. At the time, my `<img>` tag
looked like this:

<img src="C:\Users\LINDSAY\OneDrive\Pictures\Screenshots\Screenshot 2024-05-12 134045.png">

My peer explained that without an `alt` attribute, a screen reader has no text to fall
back on when it reaches an image — it either skips it silently or, depending on the
browser and assistive technology, reads out the raw file path instead. In my case, that
would have meant a visually impaired visitor either got no information at all about the
header image, or heard something meaningless like a long file path read aloud, neither
of which tells them the image is a photo of me. This mattered more than it might seem,
since the header image is one of the first things a visitor encounters on the page, and
it's meant to introduce who the site belongs to.

**Fix applied:**
I added a proper, descriptive `alt` attribute to the image so that a screen reader now
announces something meaningful instead of nothing:

<img src="profile.jpg" alt="Lindsay Daka smiling, headshot photo">

While fixing this, I also noticed the image's `src` attribute was pointing to a file
path on my own laptop rather than a file inside the project folder, which meant the
image would never have displayed correctly for anyone else viewing the page — including
someone relying on the `alt` text as a fallback for a broken image. I copied the actual
photo into the project folder, renamed it `profile.jpg`, and updated the `src` to use
that relative path instead, so the image now loads correctly and has meaningful
alternative text if it doesn't.

**Reflection:**
This feedback was a good reminder that accessibility issues aren't always visible to me
as the person building the page — I could see the image just fine on my own screen, so
the missing `alt` text wasn't obvious until someone pointed it out. It also showed me
that accessibility and basic functionality are often linked: fixing the `alt` text led
me to notice and fix the broken image path too, since I was looking at that line of code
closely for the first time since the practical session.
