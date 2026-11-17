# Assignment-2---DV066G---AI-engineering

Assignment 2, testing

-Used the provided code from the tutoriaLLM repository.

-Added a consistency test for France, asking the model three times about its capital. The test passes if at least two answers contain "Paris".

-Added a test for LLM-as-a-Judge using the deliberately incorrect answer "Lyon" instead of "Paris".

-Ran the tests several times, with all tests passing.

All the tests produced consistent results during the tests.
I also tested whether the LLM-as-a-Judge could identify an incorrect answer. Although the judge rejected our deliberately incorrect answer, the judge itself is an AI model and may also make mistakes.
