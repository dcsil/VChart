# WCAG Accessibility Checklist

This is the WCAG accessibility checklist for our app. The table below outlines how we have followed the guidelines to ensure our application is accessible to all users.

| Guideline | Summary | Description of how you accommodated this |
|-----------|---------|----------------------------------------|
| 1.1.1 – Non-text Content | Provide text alternatives for non-text content | All images either have an alt text attribute, or are purely decorative and already has a text label next to them. |
| 1.2.1 – Audio-only and Video-only (Pre-recorded) | Provide an alternative to video-only and audio-only content | We don't use audio or video content on our app. |
| 1.2.2 – Captions (Pre-recorded) | Provide captions for videos with audio | We don't use audio or video content on our app. |
| 1.2.3 – Audio Description or Media Alternative (Pre-recorded) | Video with audio has a second alternative | We don't use audio or video content on our app. |
| 1.3.1 – Info and Relationships | Logical structure | We use semantic HTML to structure our app. All headings use h1, h2, h3, etc. in logical order.|
| 1.3.2 – Meaningful Sequence | Present content in a meaningful order | All elements are nested in a logical order. |
| 1.3.3 – Sensory Characteristics | Use more than one sense for instructions | All instructions (e.g. pending review status) contains both text, shapes, and colors.|
| 1.4.1 – Use of Colour | Don't use presentation that relies solely on colour | No button use color along to indicate purpose or action. |
| 1.4.2 – Audio Control | Don't play audio automatically | We don't use audio content on our app. |
| 2.1.1 – Keyboard | Accessible by keyboard only | All interactive elements can be focused and interacted with keyboard only. The entire workflow has been tested using keyboard navigation. |
| 2.1.2 – No Keyboard Trap | Don't trap keyboard users | All interactive elements can be focused and interacted with keyboard only. The entire workflow has been tested using keyboard navigation. |
| 2.2.1 – Timing Adjustable | Time limits have user controls | We don't use time limits on our app. |
| 2.2.2 – Pause, Stop, Hide | Provide user controls for moving content | We don't use moving content on our app. |
| 2.3.1 – Three Flashes or Below | No content flashes more than three times per second | None of our content or interactive elements contain flashing sequences. |
| 2.4.1 – Bypass Blocks | Provide a 'Skip to Content' link | Each page of our  app is layed out entirely on both PC and mobile screens, with minimal repetitive header, without requiring users to scroll to interact with the main content. |
| 2.4.2 – Page Titled | Use helpful and clear page titles | Each page of our app has a helpful and clear page title. |
| 2.4.3 – Focus Order | Logical order | All interactive elements can be focused and interacted with keyboard only, from top to bottom, and from outer to inner. |
| 2.4.4 – Link Purpose (In Context) | Every link's purpose is clear from its context | Every button and link in our app has a text label that describes its purpose. |
| 3.1.1 – Language of Page | Page has a language assigned | Our app is consistenly available in English. |
| 3.2.1 – On Focus | Elements do not change when they receive focus | All interactive elements have a focus state with an outline that looks distinct from the default state. |
| 3.2.2 – On Input | Elements do not change when they receive input | We don't feature any interactive elements that will change as they receive input. |
| 3.3.1 – Error Identification | Clearly identify input errors | We provide instructions when user input is invalid. |
| 3.3.2 – Labels or Instructions | Label elements and give instructions | Labels use concise wording only, and where unclear, has placeholder text to indicate what to enter. |
| 4.1.1 – Parsing | No major code errors | We have no major code errors in our app, as our test suite has been run and passed. |
| 4.1.2 – Name, Role, Value | Build all elements for accessibility | All components have a name that is consistent with its label or function. |
| Colour Part II | Colours are chosen in a way that won't make things difficult for colour blind users | Our main color theme are white and purple, and if other colors are used, they are sufficienty distinct from these colors. |
