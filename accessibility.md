---
allowed-tools: "*"
description: Review and improve accessibility (a11y) for web components and applications
---

# Accessibility Review

Review and improve accessibility for the following code:

## WCAG 2.1 Compliance
- **Level AA Standards**: Ensure compliance with WCAG 2.1 AA guidelines
- **Semantic HTML**: Use proper HTML semantic elements (header, nav, main, section, article)
- **Heading Structure**: Logical heading hierarchy (h1, h2, h3, etc.)
- **Landmarks**: Proper use of ARIA landmarks and roles

## Keyboard Navigation
- **Focus Management**: Ensure all interactive elements are keyboard accessible
- **Tab Order**: Logical tab sequence through the page
- **Focus Indicators**: Visible focus indicators for all focusable elements
- **Keyboard Shortcuts**: Implement standard keyboard shortcuts where appropriate
- **Escape Routes**: Provide ways to exit modal dialogs and overlays

## Screen Reader Support
- **Alt Text**: Descriptive alt text for images
- **ARIA Labels**: Proper aria-label and aria-labelledby attributes
- **ARIA Descriptions**: Use aria-describedby for additional context
- **Live Regions**: aria-live for dynamic content updates
- **Hidden Content**: aria-hidden for decorative elements

## Visual Accessibility
- **Color Contrast**: Ensure sufficient color contrast ratios (4.5:1 for normal text)
- **Text Scaling**: Support up to 200% zoom without horizontal scrolling
- **Motion Preferences**: Respect prefers-reduced-motion settings
- **Focus Indicators**: High contrast, visible focus indicators

## Form Accessibility
- **Labels**: Proper label association with form controls
- **Error Messages**: Clear, accessible error messages
- **Required Fields**: Indicate required fields accessibly
- **Field Descriptions**: Use aria-describedby for helpful text
- **Validation**: Real-time validation with screen reader announcements

## React/Next.js Specific
- **next/image**: Proper alt text for Next.js Image components
- **React Fragments**: Use fragments instead of unnecessary divs
- **useEffect**: Manage focus programmatically when needed
- **Dynamic Content**: Announce dynamic content changes

## Testing Recommendations
- **axe-core**: Use axe accessibility testing library
- **Screen Readers**: Test with NVDA, JAWS, or VoiceOver
- **Keyboard Only**: Test navigation without a mouse
- **Color Blindness**: Test with color blindness simulators

Provide accessibility improvements with explanations and testing strategies.

$ARGUMENTS 