# Instruct Fine-Tuning Llama-2 for Email Response Generation
This Project outlines the process and outcomes of fine-tuning a Large Language Model Llama-2 to generate email responses based on given inputs. The primary objective of this project is to develop an instruction fine-tuning layer that enables the model to generate email responses in a format suitable for email communication.

## Methodology
The project has been divided into 5 major phases: 
- Dataset Creation & Mapping: Synthetic Dataset has been created with relevant instruction-response pairs. Further the dataset is formatted according to the chat template for the Llama-2.To prepare the dataset for fine-tuning the datset is formatted with a mapping function.
- Hugging face Integration: The dataset is pushed to Hugging Face for further retrieval during the implementation.
- Model Training: Model is Fine-Tuned using the Instruction layer for email response generation. Initialization of trainer with model, training dataset, peft configuration and other requisites is done.
- Prompt Curation: The prompt is curated in accordance to the appropriate format for the output generation. 
- Text Generation/Outputs: Evaluation of Instruct fine-tuned model is done by generating email responses to input text. Email response is printed for later evaluations.

## Architectural overview
![InstrucT Fine Tune Architecture](fine-tuning architecture.png)

