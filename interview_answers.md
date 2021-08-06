# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What are the main differences between a stateful and a functional component?

    Stateful components are keeping track of changing data, while stateless components print out what is given to them via props, or they always render the same thing.

2. When does a componentWillMount function be called? What about a componentWillUpdate?

     ComponentWillMount is called before the render function. ComponentWillUpdate is called right before the component renders and right after shouldComponentUpdate.

3. Define stateful logic.

    Stateful logic is any code that uses state, but in the case of hooks I would define it as a behaviour created with the use of one or more hooks. It's like a perk that you're adding to a component

4. What are the three step of creating a successful test? What is done in each phase?

    Your test cases should work in three phases: First, you set some stuff up (“Arrange”) Then, you do something (“Act”) Then, you make sure that what you expected to happen, actually happened.
