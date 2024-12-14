# MEDA: Your Medicine Assistant  

## Project Overview  
MEDA is an AI-powered conversational assistant tailored for healthcare professionals. By leveraging a fine-tuned language model, MEDA provides accurate and reliable medication recommendations based on patient symptoms. This project bridges the gap between AI and healthcare, aiming to improve clinical decision-making and patient outcomes.

## Aim  
- To develop a reliable AI-based medication recommender system.
- To enhance clinical workflows and decision support for medical professionals.
- To provide a scalable solution adaptable to various healthcare settings.

## Features  
- **Symptoms Checker**: AI interprets symptoms to recommend appropriate medications.
- **Conversational Interface**: Enables quick and efficient interactions.
- **Fine-Tuned Model**: Ensures accuracy and reliability in recommendations.

## Tools and Technologies  
- **Programming Language**: Python  
- **AI Framework**: OpenAI GPT-3.5 Turbo  
- **Data Processing**: CSV to JSONL conversion using Pandas  
- **Libraries**: JSON, Pandas, OpenAI API  

## Methodology  
1. **Data Preparation**: Medical data was structured and transformed into JSONL format for training.
2. **Model Fine-Tuning**: OpenAI GPT-3.5 Turbo was fine-tuned with realistic medical scenarios.
3. **Inference**: The fine-tuned model was deployed to provide real-time medication recommendations.

## Dataset Description  
The dataset includes:
- Drug names and their corresponding medical conditions.
- Descriptions of medical conditions and potential side effects.
- Structured columns for seamless integration into AI training workflows.

## Conclusion  
MEDA demonstrates the potential of AI in enhancing healthcare decision-making. With its accurate medication recommendations and user-friendly interface, MEDA supports healthcare providers in delivering targeted, efficient care while paving the way for future advancements like EHR integration and real-time analytics.

## Future Scope  
- Integration with EHR systems for holistic healthcare management.
- Multi-language support for broader accessibility.
- Real-time predictive analytics for proactive healthcare solutions.

## Installation and Usage  
1. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/meda.git
   cd meda
