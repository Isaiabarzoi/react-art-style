## Vanilla CSS

Advantages:

- CSS code is decoupled from JSX code
- You write CSS code as you (maybe) know and (maybe) love it
- CSS code can be written by another developer who needs only a minimal amount of access to your JSX code

Disadvantages:

- You need to know CSS
- CSS code is not scoped to components → CSS rules may clash across components (e.g., same CSS class name used in different components for different purposes)

## Inline Style

Advantages:

- Quick & easy to add to JSX
- Styles only affect the element to which you add them
- Dynamic (conditional) styling is simple

Disadvantages:

- You need to know CSS
- You need to style every element individually
- No separation between CSS & JSX code

## CSS Modules

Advantages:

- CSS code is decoupled from JSX code
- You write CSS code as you (maybe) know and (maybe) love it
- CSS code can be written by another developer who needs only a minimal amount of access to your JSX code
- CSS classes are scoped to the component (files) which import them → No CSS class name clashes

Disadvantages:

- You need to know CSS
- You may end up with many relatively small CSS files in your project

## Styled Components

npm install styled-components

Advantages:

- Quick & easy to add
- You continue “thinking in React” (→ configurable style functions)
- Styles are scoped to components → No CSS rule clashes

Disadvantages:

- You need to know CSS
- No clear separation of React & CSS code
- You end up with many relatively small “wrapper” components

## Tailwind CSS

Advantages:

- You don't need to know (a lot about) CSS Rapid development
- No style clashes between components since you don't define any CSS rules
- Highly configurable & extensible

Disadvantages:

- Relatively long className values
- Any style changes require editing JSX
- You end up with many relatively small "wrapper" components or lots of copy & pasting
