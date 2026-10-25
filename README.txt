BLIND PERSON’S TALENT WEBSITE
Version 0.3 Beta

Pages:
- index.html: Home
- about.html: Mission, vision, and values
- programs.html: Content areas and creative work
- latest-content.html: Playlist embed with a direct YouTube fallback
- changelog.html: Version history and changes
- contact.html: Contact details and official channels
- 404.html: Not-found page
- styles.css: Responsive styles, focus indicators, and Version 0.3 additions
- app.js: Accessible mobile navigation and current year

Version 0.3 Beta changes:
- Added a Changelog page and navigation link.
- Updated the Latest Content page to use the playlist ID supplied by the site owner.
- Added YouTube IFrame Player API setup and requested shuffle playback where supported.
- Added status messaging and a direct playlist fallback link.
- Restored the complete tagline throughout the site's brand areas.
- Updated the visible version label to Version 0.3 Beta.
- Retained the skip link, keyboard focus indicators, semantic page structure, responsive layout, and accessible navigation.

Important player note:
YouTube controls the availability and playback behaviour of embedded videos. Shuffle is requested through YouTube's player API, but YouTube may alter player behaviour, and browsers or networks may block embeds. The direct playlist link remains available as a fallback.

Privacy and terms:
Terms of Service and Privacy Policy have intentionally not been added to this version, as requested. They can be added in a later release once the final content is provided.

Accessibility:
- Skip to main content link, visible on keyboard focus.
- Main landmark and labelled primary navigation.
- aria-current="page" on the current navigation item.
- Logical heading hierarchy.
- Clear keyboard focus indicators.
- Accessible menu button with aria-expanded and aria-controls.
- Descriptive player region and live status text.
- Reduced-motion support and responsive layout.

Publishing:
Upload all files in this package to the root of your static hosting project. Keep the HTML files, styles.css, and app.js together in the same directory.
