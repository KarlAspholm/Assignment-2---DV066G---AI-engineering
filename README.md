# Assignment-2---DV066G---AI-engineering

Assignment 2, testing

-Used the provided code from the tutoriaLLM repository.

-Added a consistency test for France, asking the model three times about its capital. The test passes if at least two answers contain "Paris".

-Added a test for LLM-as-a-Judge using the deliberately incorrect answer "Lyon" instead of "Paris".

-Ran the tests several times, with all tests passing.

Results and Reflections

We ran the tests several times. In the first four runs, all four available tests passed. After adding more tests, we ran the complete test suite multiple times, and all eight tests passed in the completed runs.

The results suggest that the model was consistent when answering questions about the selected countries. The LLM-as-a-Judge was also able to identify the incorrect answers in these tests.

However, LLMs are not always reliable, and the judge can also make mistakes. If a test fails, it is important to distinguish between an incorrect answer from the model and an incorrect evaluation by the judge. A consistency test checks the model's answers directly, while a judge-based test depends on the judge's evaluation.

Overall, this assignment showed us that testing AI components is different from testing traditional software, since the answers can vary between runs and even the evaluation process can be unreliable.
