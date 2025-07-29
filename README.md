# Islamic Agent n8n Workflow

This project contains an n8n workflow for an Islamic agent. The workflow utilizes custom tools to interact with Islamic texts.

## Project Structure

- `README.md`: This file.
- `islamic_agent/islamic_agent_workflow.json`: The main n8n workflow file.
- `islamic_agent/tools/get_all_syahs_of_surah.json`: A custom tool to get all ayat (verses) of a specific surah (chapter) from the Quran.
- `islamic_agent/tools/get_one_ayah.json`: A custom tool to retrieve a specific ayah (verse) from the Quran.
- `islamic_agent/vectors/quran_vector_store.json`: A vector store likely used for searching or embedding Quranic text.

## Setup and Usage

1.  **Import the workflow:** Import the `islamic_agent/islamic_agent_workflow.json` file into your n8n instance.
2.  **Add the custom tools:** Add the tools defined in `islamic_agent/tools/get_all_syahs_of_surah.json` and `islamic_agent/tools/get_one_ayah.json` to your n8n instance. Refer to the n8n documentation for how to add custom nodes or tools.
3.  **Configure the workflow:** You may need to configure the custom tool nodes within the workflow depending on their specific requirements.
4.  **Run the workflow:** Execute the workflow within n8n.

## Functionality

The workflow is designed to...

*(Further details on the workflow's specific functionality can be added here based on the workflow's design.)*

## Contributing

*(Add contributing guidelines here if applicable.)*

## License

*(Add license information here if applicable.)*
