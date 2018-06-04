## Questions
>In your own words, explain the essential differences between props and state in React. Which is immutable or read-only, and which changes? Discuss the answer >with your mentor.

* Both props and state provide data for React's rendering of components. The data can come from a parent or can come from within the component itself. Both props and state are objects. They both trigger a render update.
* State is internal to the component and is controlled by the component itself.
  * State holds information about the component, but handles different kinds of information.
  * State is created in the component. It cannot be changed by a parent Component.
  * State is changeable, and contains information for the component to initialize, change, and use on its own.
  * State is for interactivity; the data changes over time.
* Props are external to the component and are controlled by whatever it is that renders the component. They are the configuration of the component.
  * Props are passed in, and they are immutable.
  * Props are a way to pass things from parent to child.
  * React components that use only props will always render the same output given the same input.