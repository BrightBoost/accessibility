### Exercise: Accessibility with ARIA

This exercise is designed to help you understand the use of ARIA (Accessible Rich Internet Applications) roles and properties to improve the accessibility of a web application. You will work with a sample website that demonstrates poor accessibility practices and apply ARIA elements to ensure it meets WCAG (Web Content Accessibility Guidelines) standards.

#### Background:
ARIA is a set of attributes that define ways to make web content and web applications more accessible to people with disabilities. ARIA roles, states, and properties provide additional information to assistive technologies, improving the user experience for individuals using screen readers and other assistive tools.

#### Explanation of ARIA Elements:
1. **ARIA Roles**: Define the type of user interface element, such as `role="dialog"` for modals, `role="alert"` for important messages, or `role="navigation"` for navigation menus.

2. **ARIA States and Properties**: Provide information about the current state of an element or its relationship with other elements. Examples include `aria-expanded` to indicate whether a collapsible element is open or closed, and `aria-live` to announce dynamically changing content.

3. **ARIA Landmarks**: Define regions of the page to help users navigate, such as `role="banner"` for site headers or `role="main"` for the main content area.

#### Exercise steps:

**1. Understanding the starter code**
The sample website with poor accessibility practices can be found in `aria-starter.html`.


**2. Analyzing the accessibility issues**
- The dynamically loaded content is not announced to screen readers.
- The button lacks a descriptive label.
- The page lacks appropriate ARIA roles and properties.

**3. Applying ARIA**
Update the code to enhance accessibility.

**4. Use the screen reader with both the starter and the final exercise**
