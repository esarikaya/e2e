# Getting Started with BDD and Cucumber - 2

Now that you've implemented addition, let's add a new feature for subtraction. This exercise will help you practice writing your own scenarios and step definitions.

### Step 1: Add a new scenario

Create a scenario that verfies that two numbers can be subtracted. Add it to your `features/calculator.feature` file.

### Step 2: Implement the new step definition

Now, open your `features/step_definitions/calculator_steps.js` file and add the new step definition for subtraction. You'll need to:

1. Modify the existing `Given` step to work for both addition and subtraction scenarios.
2. Add a new `When` step for subtraction.
3. The existing `Then` step should work as-is for both scenarios.

Try to implement these changes yourself. Here are some hints:

- You can use the same `numbers` array for both addition and subtraction.
- The subtraction step should subtract the second number from the first.

### Step 3: Run the tests

After implementing your changes, run the tests again:

```
npm test
```

If you've implemented the steps correctly, both scenarios (addition and subtraction) should pass.

### Challenge

If you're up for a challenge, try adding more complex scenarios, such as:

1. Multiplying two numbers
2. Dividing two numbers (don't forget to handle division by zero!)
3. A scenario that performs multiple operations in sequence

Remember to write the feature first, then implement the step definitions. This is the essence of Behavior-Driven Development!

By completing this exercise, you'll gain more practice in writing BDD scenarios and implementing the corresponding step definitions. This will help you think about how to structure your features and steps for more complex real-world applications.
