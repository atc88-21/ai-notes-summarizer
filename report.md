# Semester Project Report: AI Notes Summarizer

## AI tools used and how
I used ChatGPT during development to help generate code structure, refine prompts, and debug issues in Colab. In the final product, the app uses the OpenAI API to generate a summary, key terms, and quiz questions from user-provided notes. This demonstrates both AI-assisted development and an AI-integrated final product.

## Difficulties encountered
The main difficulty was getting consistent output formatting. I addressed this by enforcing a strict prompt template (SUMMARY / KEY TERMS / QUIZ) and using a system message to require concise, structured output. Another challenge was handling the API key safely, which I solved by entering it at runtime in Colab (not storing it in the repository).

## Reflection on working with AI
AI significantly reduced the time required to build a working interactive app and helped me debug faster. However, it still required testing and careful instructions, since AI-generated code can look correct but fail due to missing setup steps or formatting issues. Overall, AI was most useful as a rapid assistant, but I still had to verify and iterate to make the project reliable.
