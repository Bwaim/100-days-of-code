# 100 Days Of Code - Log

## Goals: Apply MVVM architecture with Architecture component on my second Android Project of ABND track - ScoreKeeper

### Day 0: August 29, 2018

**Today's Progress**: Creation of the new branch. Updating projects. Start to refactor.

**Thoughts:** I don't know exactly how to implement MVVM, so i searched some sources with examples.

**Link to work:** [ScoreKeeper App](https://github.com/Bwaim/ScoreKeeper)

**Sources:** 
1. [Model-View-ViewModel article](https://medium.com/upday-devs/android-architecture-patterns-part-3-model-view-viewmodel-e7eeee76b73b)
2. [MVVM with the Data Binding Library article](https://labs.ribot.co.uk/approaching-android-with-mvvm-8ceec02d5442)
2. [Android Architecture Repository](https://github.com/googlesamples/android-architecture)

### Day 1: August 30, 2018

**Today's Progress**: Refactoring layer data. Create the test of the repository

**Thoughts:** I understand the principle of the repository, using and interface with callback to pass data to the ViewModel.

**Link to work:** [ScoreKeeper App](https://github.com/Bwaim/ScoreKeeper)

### Day 2: August 31, 2018

**Today's Progress**: Starting to refactor the layer ViewModel with the use of LiveData. Initiate the test of the ViewModel

**Thoughts:** I understand how to use LiveData and on test side the use of @Captor.

**Link to work:** [ScoreKeeper App](https://github.com/Bwaim/ScoreKeeper)

### Day 3: September 1, 2018

**Today's Progress**: Continuing to refactor the layer ViewModel and View with the use of LiveData.

**Thoughts:** It's a bit difficult to put the databinding, i still need more documentation on it.

**Link to work:** [ScoreKeeper App](https://github.com/Bwaim/ScoreKeeper)

### Day 4: September 2, 2018

**Today's Progress**: Initiate the data binding. Helper classes created.

**Thoughts:** It was a bit difficult to put the databinding but finally it works.

**Link to work:** [ScoreKeeper App](https://github.com/Bwaim/ScoreKeeper)

### Day 5: September 3, 2018

**Today's Progress**: Finish the initial data binding.

**Thoughts:** Trying to write tests at same time.

**Link to work:** [ScoreKeeper App](https://github.com/Bwaim/ScoreKeeper)

### Day 6: September 4, 2018

**Today's Progress**: Refactor a bit the ModelView for testing purpose. Add some tests of the ModelView

**Thoughts:** Well architecture the code to facilitate the tests.

**Link to work:** [ScoreKeeper App](https://github.com/Bwaim/ScoreKeeper)

### Day 7: September 5, 2018

**Today's Progress**: Add initial tests of the UI

**Thoughts:** 

**Link to work:** [ScoreKeeper App](https://github.com/Bwaim/ScoreKeeper)

### Day 8: September 6, 2018

**Today's Progress**: Refactor the UI with the ConstraintLayout

**Thoughts:** It's very simple to use the graphic designer for the ConstraintLayout

**Link to work:** [ScoreKeeper App](https://github.com/Bwaim/ScoreKeeper)

### Day 9: September 7, 2018

**Today's Progress**: Refactor the UI in two fragment to reuse them in the landscape layout

**Thoughts:** Understanding better how the fragment works

**Link to work:** [ScoreKeeper App](https://github.com/Bwaim/ScoreKeeper)

### Day 10: September 8, 2018

**Today's Progress**: Add the countDownTimer to the ViewModel and implement the logic part of the start countdown functionality

**Thoughts:** Learning how to separate dependencies for easy testing

**Link to work:** [ScoreKeeper App](https://github.com/Bwaim/ScoreKeeper)

### Day 11: September 9, 2018

**Today's Progress**: Finalize the start pause timer functionality

**Thoughts:** 

**Link to work:** [ScoreKeeper App](https://github.com/Bwaim/ScoreKeeper)

### Day 12: September 10, 2018

**Today's Progress**: Add the reset timer functionality

**Thoughts:** It's very easy to add a new functionality once the architecture is done

**Link to work:** [ScoreKeeper App](https://github.com/Bwaim/ScoreKeeper)

### Day 13: September 11, 2018

**Today's Progress**: Add the syntax error functionality in the ViewModel

**Thoughts:** Don't forget to update previous tests

**Link to work:** [ScoreKeeper App](https://github.com/Bwaim/ScoreKeeper)

### Day 14: September 12, 2018

**Today's Progress**: Refactor some click listener, start implementing the update of the score

**Thoughts:** With a LiveData on an object, if you update a property, the ui is not notified !

**Link to work:** [ScoreKeeper App](https://github.com/Bwaim/ScoreKeeper)

### Day 15: September 13, 2018

**Today's Progress**: Correct the use of LiveData for correct update. Add parameterized test

**Thoughts:** Parameterized tests are cool !

**Link to work:** [ScoreKeeper App](https://github.com/Bwaim/ScoreKeeper)

### Day 16: September 14, 2018

**Today's Progress**: Add logic error functionality. Automate unlock screen for test !

**Thoughts:** 

**Link to work:** [ScoreKeeper App](https://github.com/Bwaim/ScoreKeeper)

### Day 17: September 15, 2018

**Today's Progress**: Add logic error functionality in ui and virus attack functionality

**Thoughts:** Next step add library (ButterKnife and Dagger2)

**Link to work:** [ScoreKeeper App](https://github.com/Bwaim/ScoreKeeper)

### Day 18: September 16, 2018

**Today's Progress**: Add the display of the winner, read documentation about butterknife

**Thoughts:** Next step add library (ButterKnife and Dagger2)

**Link to work:** [ScoreKeeper App](https://github.com/Bwaim/ScoreKeeper)

### Day 19: September 17, 2018

**Today's Progress**: Refactor some code and start to use ButterKnife

**Thoughts:** ButterKnife is easy to use

**Link to work:** [ScoreKeeper App](https://github.com/Bwaim/ScoreKeeper)

### Day 20: September 18, 2018

**Today's Progress**: Correct a bug, finish to set ButterKnife to learn that is useless with data binding

**Thoughts:** ButterKnife is great but not useful with data binding. At least i learnt to use it.

**Link to work:** [ScoreKeeper App](https://github.com/Bwaim/ScoreKeeper)

### Day 21: September 19, 2018

**Today's Progress**: Correct a bug

**Thoughts:** 

**Link to work:** [ScoreKeeper App](https://github.com/Bwaim/ScoreKeeper)

### Day 22: September 20, 2018

**Today's Progress**: Remove the use of ButterKnife as in this context is useless with data binding. Start to read dagger2 documentation

**Thoughts:** Dagger2 seems a bit complicated at the first approach

**Link to work:** [ScoreKeeper App](https://github.com/Bwaim/ScoreKeeper)

### Day 23: September 21, 2018

**Today's Progress**: Create a specific branch for DI. Add dependencies to dagger2

**Thoughts:** After reading some docs on dagger2, it seems more clear

**Link to work:** [ScoreKeeper App](https://github.com/Bwaim/ScoreKeeper)

### Day 24: September 22, 2018

**Today's Progress**: Add dagger2 to the project. Next step, correct the tests.

**Thoughts:** Wow ! Was quite difficult !

**Link to work:** [ScoreKeeper App](https://github.com/Bwaim/ScoreKeeper)

### Day 25: September 23, 2018

**Today's Progress**: Correct the unit tests taking advantage of dagger2

**Thoughts:** 

**Link to work:** [ScoreKeeper App](https://github.com/Bwaim/ScoreKeeper)

### Day 26: September 24, 2018

**Today's Progress**: Download AS 3.2, start checking dagger implementation

**Thoughts:** 

**Link to work:** [ScoreKeeper App](https://github.com/Bwaim/ScoreKeeper)

### Day 27: September 25, 2018

**Today's Progress**: Made changes in dagger implementation but it's not working

**Thoughts:** 

**Link to work:** [ScoreKeeper App](https://github.com/Bwaim/ScoreKeeper)

### Day 28: September 26, 2018

**Today's Progress**: Still not working but code is better, i'm desperate !

**Thoughts:** disable databinding to check dagger2 errors

**Link to work:** [ScoreKeeper App](https://github.com/Bwaim/ScoreKeeper)

### Day 29: September 27, 2018

**Today's Progress**: It's working ! An import of the data binding generated class was missing, auto import didn't work for it !

**Thoughts:** Better understanding of dagger2

**Link to work:** [ScoreKeeper App](https://github.com/Bwaim/ScoreKeeper)

### Day 30: September 28, 2018

**Today's Progress**: Working on the modelView to improve the databinding

**Thoughts:** 

**Link to work:** [ScoreKeeper App](https://github.com/Bwaim/ScoreKeeper)
