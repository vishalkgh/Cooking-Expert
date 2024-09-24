# Cooking-Expert
Cooking Expert
Cooking Expert is a chatbot specifically designed to assist users with cooking-related inquiries. By integrating recipes, ingredient information, and cooking techniques into a large language model (LLM), this chatbot provides personalized meal recommendations, cooking tips, and step-by-step guidance for home cooks of all levels.

**Features**
Interactive chatbot interface for cooking-related questions.
Extensive database of recipes, ingredients, and cooking methods.
Personalized meal plans based on user preferences, dietary restrictions, and available ingredients.
Step-by-step cooking instructions with real-time tips.
Ingredient substitution suggestions and portion size recommendations.

**Installation**
To get started with Cooking Expert, follow these steps:

**Clone the repository:**
git clone https://github.com/vishalkgh/cooking-expert.git
cd CookingExpert

Install the Gaia Node by running the following command:
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash

Run the following command to update your config.json to run with a small language model:
gaianet init --config https://raw.githubusercontent.com/harishkotra/Gaia-8G/refs/heads/main/config_8g.json

**Start the node:**
gaianet start

**How to Use**
Open your web browser and navigate to the generated link.
Start interacting with the chatbot by typing your cooking-related questions (e.g., "What can I cook with chicken and broccoli?", "How do I bake a perfect cake?" or "Suggest a vegan dinner recipe").

**License**
This project is licensed under the MIT License. See the LICENSE file for details.
