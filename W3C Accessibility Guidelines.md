Developing something with accessibility in mind implies support reader technology and (at the very least) pass inspections like the ones provided by the extension [Accessibility Insights for Web](https://accessibilityinsights.io/docs/web/overview/).
This implies components are recognized by the system as what they actually are, have proper contrast, are properly labelled (use ARIA identifiers in HTML), are fully accessible via keyboard only, among other things.

Something that is important but not very mentioned is that your interface should be viewable by a sighted person while a blind person is using it, so they can share activities.

You can check out the official W3C Accessibility Guidelines [here](https://www.w3.org/TR/WCAG21/) but for a more readable summary of how to achieve AA complaince see [here](https://usability.yale.edu/web-accessibility/articles/wcag2-checklist).
