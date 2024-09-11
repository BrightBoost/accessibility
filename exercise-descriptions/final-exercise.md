### **Final challenge: Create an accessible Escape Room**

You will create a web based “escape room” challenge where users (=your colleagues) must solve puzzles or tasks to "escape." The challenge should be fully accessible, following WCAG guidelines and using ARIA elements to ensure that all users, including those using assistive technologies, can participate in the escape room.

#### **Requirements:**
1. **Multiple interactive elements**: 
   - At least 3 tasks that involve interaction, such as solving riddles, entering codes, finding clues, or unlocking elements on the page.
   
2. **Accessibility features**:
   - Proper use of semantic HTML.
   - Proper use of ARIA roles, properties, and states (like `aria-live`, `aria-expanded`, etc.) to ensure dynamic content is accessible.
   - Clear and consistent navigation using `tabindex` to control focus order.
   - Proper contrast and color use (avoid using color as the only indicator).
   - Descriptive alt text for images or icons used as clues.
   - Accessible keyboard controls for all interactive elements.
   
3. **Dynamic content**:
   - Use JavaScript to dynamically load or change content based on user interaction (e.g., revealing a clue when a button is clicked or unlocking the next puzzle).
   - Have all the dynamically loaded content being announced to screen readers using `aria-live` regions.

4. **Responsive design**:
   - Ensure the escape room works well on both desktop and mobile devices.
   - Include responsive design principles while maintaining accessibility.

5. **Creative theme: GO WILD**:
   - You can choose your own fun and creative theme for the escape room (e.g., escaping from a haunted house, a mystery at a zoo, or even an underwater adventure with accessible sea creatures!).

6. **Focus management**:
   -  After solving each task, the focus moves to the next task automatically for screen readers, or make sure users can navigate easily via keyboard shortcuts.

#### **I know it's late, so here are some ideas**:
- **Puzzle 1**: Solve a riddle and enter the answer in a text box (make sure it has labels and is keyboard navigable).
- **Puzzle 2**: Find hidden clues (e.g., text hidden in `aria-hidden` content that reveals itself when a correct action is performed).
- **Puzzle 3**: Use a keypad to enter a code (button controls are fully keyboard accessible and announced).
- **Puzzle 4**: Answer questions where buttons dynamically load clues (announced to screen readers using `aria-live`).

#### **Final final challenge: Escape!**
Pair up with another duo, and see if you can escape with your eyes closed!

