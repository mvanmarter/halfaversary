# UI Design Standards

## Objective

Build polished, professional, production-quality web interfaces with a distinctive visual identity, consistent design language, responsive layouts, and accessible interactions.

## Primary UI Stack

- Component library: shadcn/ui
- Styling: Tailwind CSS
- Icons: Lucide
- Animation: Motion, when appropriate
- Additional components: Only approved libraries and registries

## Design Principles

### 1. Visual Hierarchy

- Establish a clear hierarchy between page titles, section headings, body text, and supporting information.
- Use typography, spacing, and contrast to guide attention.
- Give important content appropriate prominence.

### 2. Layout and Spacing

- Use a consistent spacing system.
- Establish appropriate content widths and alignment.
- Avoid excessive card nesting, unnecessary borders, and repetitive layouts.
- Ensure layouts adapt to mobile, tablet, and desktop screens.

### 3. Color and Typography

- Define semantic design tokens for primary, secondary, background, foreground, border, and accent colors.
- Use a consistent typographic scale.
- Maintain sufficient contrast and readable text sizes.
- Avoid introducing arbitrary colors or font sizes when suitable design tokens already exist.

### 4. Component Reuse

- Prefer existing project components and approved UI libraries.
- Reuse established buttons, inputs, cards, dialogs, and navigation components.
- Extend existing components when appropriate rather than creating competing implementations.
- Avoid introducing additional UI libraries without justification.

### 5. Distinctive Design

- Avoid generic layouts that rely on repetitive cards and gradients.
- Select a visual direction appropriate to the product and its audience.
- Use high-quality imagery, illustrations, and data visualizations where they add value.
- Treat marketing pages, dashboards, and forms as different design problems.

### 6. Interaction and Animation

- Provide clear hover, focus, active, disabled, and loading states.
- Use animation purposefully and sparingly.
- Respect reduced-motion preferences.
- Ensure interactions work with a keyboard and on touch devices.

### 7. Accessibility

- Use semantic HTML.
- Provide accessible labels and keyboard navigation.
- Maintain appropriate color contrast.
- Avoid communicating important information through color alone.

## Implementation Workflow

Before implementing a page:

1. Inspect the existing project and identify its framework, styling system, and UI components.
2. Review existing design tokens and page patterns.
3. Identify appropriate reference layouts and reusable components.
4. Define the page structure and responsive behavior.
5. Implement the page using the approved stack.
6. Test interactions, responsiveness, accessibility, and visual consistency.
7. Review the rendered page and refine obvious visual defects.

## Constraints

- Preserve the existing framework and architecture unless a change is justified.
- Do not introduce duplicate component libraries.
- Do not fabricate product screenshots, customer logos, or testimonials.
- Do not stop at a technically functional page when significant visual problems remain.
- Prefer coherent, intentional design over unnecessary visual effects.
