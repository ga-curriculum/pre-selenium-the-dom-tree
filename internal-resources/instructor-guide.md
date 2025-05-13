<h1>
  <span class="headline">Pre-Selenium: The DOM Tree</span>
  <span class="subhead">Instructor Guide</span>
</h1>

## Exploring DOM Nesting with DevTools

### Delivery Tips

- Begin by reinforcing the concept of the DOM as a **nested tree structure**, and connect this to familiar Python data structures (ex:, dictionaries inside dictionaries, nested lists).
- Use a **shared screen or projector** to walk learners through opening Chrome DevTools and exploring the **Elements** panel.
- Demonstrate how to identify parent, child, and sibling relationships using the provided **login form HTML example**. Emphasize the value of nesting context in writing reliable selectors.
- Encourage learners to expand and collapse elements manually in DevTools to build comfort with interpreting DOM structure.

### Accessibility and Inclusion Tips

- Provide ample time for learners to **manually explore the DOM tree**, especially those new to browser-based tooling.
- Encourage learners to **share screens** (in remote or hybrid sessions) during guided practice, fostering peer support and troubleshooting.
- Use neutral, globally accessible examples like **login forms** and **generic page structures** (ex:, example.com), avoiding region-specific references or metaphors.

## DOM relationships and Selenium selectors

### Delivery tips

- Revisit the everyday analogy—library, shelves, book series—to establish why relationships matter.
- Model tracing relationships using the Chrome DevTools and grocery or navigation menu examples. Use suggested visuals to clarify concepts.
- Encourage learners to talk through their steps in the activity, focusing on _why_ one selector is more reliable than another.
- For remote sessions, use breakout groups during the activity for learners to compare selector strategies.
- Emphasize that testing selectors in DevTools is a key part of the process—making invisible DOM relationships visible and actionable.

**Discussion prompt—sample answers:**

- Using parent–child–sibling patterns almost always reduces accidental matches. Missing these relationships means selectors may break the moment a new element is added or the structure changes.
- Practicing with DevTools clarifies the connection between what learners see visually, what is in the HTML, and what their selector matches in code—building both skill and confidence.

### Accessibility, inclusion, and adaptation tips

- Give learners time to navigate DevTools at their own pace; check that everyone can expand/collapse nodes before moving on.
- Use globally neutral examples (sample websites, menu items, library analogy) to ensure concepts are universally relatable.
- If anyone faces barriers with DevTools, provide screenshots or step-by-step walk-throughs as an alternative.

---

## Handling deeply nested structures

### Delivery tips

- Reiterate the analogy of searching for an office in a multi-level building to ground why DOM ancestry is crucial in automation.
- Demonstrate the process live: select a deeply nested form input, trace its ancestry step-by-step, and write selectors in both CSS and XPath. Highlight differences in what each selector matches.
- Remind learners to always test selectors directly in DevTools before using them in Selenium scripts.

### Accessibility and inclusion tips

- Remind learners that complex UI layouts are common globally, and everyone faces this challenge—selectors should always be built for resilience, not just convenience.
- Use imagery and analogies that are universally relevant (multi-level building, government agency floor plan) instead of region-specific scenarios.
- Offer assistance if any learner is unfamiliar with Chrome DevTools shortcuts or navigation.

---

## Mapping visual layout to DOM structure

### Delivery tips

- Use the theater seating or group photo analogy to clarify why the DOM is the "source of truth" for element order and selection, regardless of on-screen appearance.
- Model the element picker workflow live, showing how an element can appear first visually but be second or third in the DOM tree due to CSS.
- Encourage participants to take turns sharing what they selected and what they found—are there patterns where visual and DOM order diverge?
- Reiterate that inspecting and verifying in the DOM is a core testing habit for robust automation.

### Accessibility and inclusion tips

- Avoid references to culturally specific websites or navigation patterns. The theater seating analogy and group photo are globally relevant.
- Walk through the DevTools interaction step by step so all learners can follow regardless of prior experience.
- Offer keyboard and screen reader navigation tips for DevTools when possible.
- Provide screenshots or step-by-step written support for learners struggling with visual complexity.

---

🏗️ **Under Construction**

We are constantly working to improve our resources for instructors and students.

**Have something to contribute to this Instructor Guide?** [Let us know](https://pages.git.generalassemb.ly/modular-curriculum-all-courses/universal-resources-internal/module-feedback.html).
