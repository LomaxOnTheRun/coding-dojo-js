## What is a coding dojo?

A coding dojo is a space where a group of developers can practice their skills in a cooperative and encouraging environment. Every person in the room is working towards the same goal of completing the challenge in the alloted time.

### Roles in the dojo

**Sensei**: Overlooks and guides proceedings.

**Pilot**: Person physically typing code on the laptop.

**Co-pilot**: Sits next to pilot, advising on what to write.

**Advisors**: Everyone else, can give advice to pilot and co-pilot.

### Rules of the dojo

1. The pilot is the only person who can type on the latop.

2. The pilot and co-pilot get final say on what they type. Others can change it later.

3. Everyone takes a turn being pilot, then co-pilot.

4. Everyone is participating in the excerise together - no running the exercise on your own laptop.

5. Once every cycle (to be determined by the sensei) the co-pilot becomes an advisor, the pilot becomes the co-pilot, and a new person becomes pilot.

6. The dojo is an inclusive, supportive space. Intolerant, racist, sexist, homophobic and general shitty behaviour will incur a warning. A second instance of it and you will be asked to leave.

7. Everyone has a right to be heard. If someone is wrong, don't just shout them down; spend a minute to teach them instead. There will always be others in the room for whom this is also new information.

### TDD

Test Driven Development (TDD) is a methodology by which an (initially failing) automated test is written which defines a new piece of desired functionality. A minimum amount of code is then written to make the test work. Finally, the code is refactored to increase the quality of the code whilst making sure the tests remain unbroken.

### Kata steps

To this end, the steps the group will take are:

1. Write a small test to define a new piece of desired functionality, or to define a corner case that is not yet catered for. You may only write code in the test file during this phase, and every new test must be failing when initially written.

2. Make the new test pass as quickly and cheaply as possible. You can only write code in the main file during this phase, and every test must be passing by the time you're finished, but otherwise you are encouraged to cut as many corners and cheat as much as possible to get the tests to pass.

3. Refactor the code wherever you think it can be. You can write and edit code in either file during this phase, but all tests must still be passing by the time you're finished. It is exceedingly rare that there is nothing to refactor.

Once the refactoring phase is over, circle back to writing a new test and keep looping through the list until the time runs out or the kata is completed.

### Additional thoughts

- Try to make each test as small as possible. The smaller the better a coder you are.
- Only add new tests (unless refactoring). All tests should keep in mind the final goal.
- No looking up the answer(?)