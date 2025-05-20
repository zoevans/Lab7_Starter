Name: Zoey Evans

"Check Your Understanding" Question Answers:

1) I would fit my tests within a GitHub action that runs whenever code is pushed because that way the tests are run fairly often on the applicable code for the code project. Tests should be at a place in the CI/CD pipeline where the relevant code to the project can be tested often. If we test all the code at the end of the pipeline after all development is completed like in Option 3, it is likely there will be a lot of issues in the code that the tests will identify that will be extremely difficult to resolve after all development is finished, so it is better to put the tests at a spot in the CI/CD pipeline where the code can be tested more gradually throughout the development process. Additionally, if we put our tests in the pipeline before our code is pushed like in Option 2, we risk losing a lot of time in the development process by running tests on code that may or may not be relevant to our project because the code is not guaranteed to be used or relevant to the project. Therefore, Option 1 is the best choice because it ensures that tests are consistently run on relevant code, without being overkill.

2) No, I would NOT use an end to end test to check if a function is returning the correct output. That would instead require a unit test.

3) The difference between navigation and snapshot mode is that navigation mode analyzes a page right after it loads and provides a wider range of general performance metrics, while snapshot mode analyzes a page in its current state and is useful for finding relevant accessibility metrics.

4) Based on the Lighthouse results, 3 things we could do to improve the CSE 110 shop site are: properly size the images to save cellular data and improve load time; include a "<meta-name = "viewport">" tag to prevent delay for the user and optimize the site for mobile screen sizes; and serve images in next-gen formats, like WebP and AVIF instead of JPEG or PNG, for less data consumption and faster downloads.





