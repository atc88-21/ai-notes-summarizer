# AI Notes Summarizer

A simple interactive Python app (Gradio in Google Colab) that uses the OpenAI API to turn pasted notes into:
- a 5-bullet summary
- 5 key terms with definitions
- a 5-question mini quiz (with answers)

## How to run
1. Open `app.ipynb` in Google Colab.
2. Run the cells from top to bottom.
3. When prompted, paste your `OPENAI_API_KEY`.
4. Click the Gradio public link that appears.
5. Paste notes and click **Generate**.

## AI tools used
- ChatGPT: used during development to plan the project, write code, and debug.
- OpenAI API: used inside the final app to generate the summary, key terms, and quiz content.
- (Optional) Image generation: used to create a banner/logo for the repository (if included).

## Notes
- The API key is entered at runtime in Colab and is not stored in the GitHub repository.
