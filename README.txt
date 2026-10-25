BLIND PERSON'S TALENT WEBSITE
Version 0.2 Beta

Pages:
- index.html: Home
- about.html: Mission, vision, values
- programs.html: Content areas and creative work
- latest-content.html: YouTube uploads embed and fallback link
- contact.html: Contact details and official channels
- 404.html: Not-found page
- styles.css: Responsive styles and focus indicators
- app.js: Accessible mobile navigation and current year

Accessibility improvements:
- Skip to main content link, visible on keyboard focus.
- Main landmark and labelled primary navigation.
- aria-current="page" on the current navigation item.
- Logical heading hierarchy with one H1 per page and H2/H3 nested in order.
- Clear keyboard focus indicators.
- Accessible menu button with aria-expanded and aria-controls.
- Descriptive iframe title for the YouTube player.
- Reduced-motion support.
- Responsive layout and readable contrast.
- Decorative graphics are hidden from assistive technology.

Latest content:
The latest-content.html page uses YouTube's legacy user uploads embed format with the channel handle as the list value. YouTube may change or restrict support for this embed format. The page includes a direct fallback link to the official Videos tab. If the embedded player does not load the uploads correctly after publishing, obtain the channel's permanent UC... ID and use the channel uploads playlist ID (UU + the channel ID after removing its leading UC) in a playlist embed.

Publishing:
Upload all files together to Vercel, GitHub Pages, Netlify, Cloudflare Pages, or a static web host. This ZIP package does not itself publish the site or register a domain.

Before public launch:
- Verify the CEO name and telephone number.
- Confirm all official channel links.
- Test the YouTube embed on the deployed site and mobile.
- Confirm the preferred spelling of the organization name and use it consistently.
- Add a privacy policy if you later add forms, analytics, mailing lists, accounts, or collect personal data.
- Do not add donation or non-profit registration claims without verified details.
