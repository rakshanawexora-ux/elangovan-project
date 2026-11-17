# Usability review

The interface uses Nielsen's usability heuristics as a practical review framework. This is an implementation review, not a claim of a moderated user study or complete accessibility certification.

- **Visibility of system status:** Current navigation page has `aria-current`; service filters expose pressed state and announce the number of results. Content is visible before scroll animation runs.
- **Match with the real world:** Familiar document names, specific examples and an explanation of the application process replace abstract marketing language.
- **User control:** Users can change the selected service, close mobile navigation with Escape, and choose Call or WhatsApp directly. No enquiry popup interrupts the journey.
- **Consistency:** Four-page navigation, repeated service-card structure and consistent CTA labels and focus styles.
- **Error prevention:** Document review checklist, explicit availability/fee guidance and no collection of sensitive identity data through a website form.
- **Recognition over recall:** Service descriptions, supporting task lists and selected-service context on Contact and WhatsApp.
- **Efficiency:** Direct phone links, contextual WhatsApp links, service filtering, sticky navigation and a skip-to-content link.
- **Minimal design:** Blue and white palette with photographs, clear section grouping and space between content blocks.
- **Recovery:** Service selection can be changed without losing access to navigation; FAQs explain where decisions and processing are controlled by authorities.
- **Help:** Document preparation guidance, FAQs and direct contact options on every page.

## Checks

Check the four routes at desktop, tablet and phone widths. Verify visible content without scrolling, no horizontal overflow, image loading, keyboard menu dismissal, service filter counts and pressed state, enquiry context and reduced-motion behaviour. Run automated axe checks for WCAG A/AA rules alongside manual review; automated checks alone do not establish full compliance.

Generated photographs are illustrative, including the image adjacent to the business biography. No customer counts, reviews, office address, charges or guarantees have been invented.
