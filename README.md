

# 🥗 AI Diet Planner with Python

This project generates personalized meal plans based on user preferences and goals. It uses Python, Gradio, and OpenAI.

# 💡 It is a simple web application built with Gradio and OpenAI GPT-3.5 that generates personalized diet plans in Romanian.
The user provides information such as food preferences, dietary restrictions, budget, height, weight, and fitness goals (cutting, maintenance, or bulking). The app then generates:

✅ A detailed daily plan with meals and portion sizes

✅ Macronutrient and calorie breakdown for each day

✅ Maintenance calories calculated with the formula:

total_calories_of_maintenance = 2 * 15 * weight
+500 kcal for bulking and -300 kcal for cutting

✅ References for nutritional recommendations

# ⚙️ Technologies Used
- Python 3.13.1
- Gradio
- OpenAI GPT-3.5

# 🚀 How to Run the Application
1. Clone or download the project.
2. Create a 'requirements.txt' file with the following content:
   gradio==5.12.0
   openai==0.28.0
3. Install the required libraries using the command:
   pip install gradio==5.12.0 openai==0.28.0
4. Set the API key in CMD, as an administrator, using the key provided from platform.openai.com:
   setx OPENAI_API_KEY "your_openai_api_key"
5. Run the application with:
   python Main.py
   Then access the Gradio-generated link to use the graphical interface.

# 🖥️ Interface

The Gradio interface provides input fields for:

Food preferences, dietary restrictions, weekly budget, height & weight, fitness goals (cutting / maintenance / bulking)
Additional preferences (e.g., high protein, low carb)

# 📋 Examples

You can try some predefined inputs:

Vegetarian diet with a 450 RON weekly budget and cutting goal
Non-vegetarian, lactose-free diet for maintenance

# Author
Necula Valentin-Cristian (through Neural Networks Course)

![image](https://github.com/user-attachments/assets/3e1370bb-27a0-475b-ad25-368e6565b49c)

