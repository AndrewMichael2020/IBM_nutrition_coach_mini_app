# AI Nutrition Coach: GenAI-Powered Image-Based Web Application

**Developed by:** Hailey Quach and Ricky Shi, IBM Instructors  
**Implementer:** Andrew Ihnativ  
**Course Lab:** Build a Style Finder Using Multimodal Retrieval and Search  
**Organization:** IBM Skills Network

---

## Project Overview

Welcome to the **AI Nutrition Coach** project! In this hands-on workshop, you'll learn how to create an AI-powered web application that estimates the caloric content of food from images and delivers personalized dietary advice. This project harnesses the advanced capabilities of the **Llama 4 Maverick 17B 128E Instruct FP8** model for generative AI and visual recognition, and integrates it with comprehensive nutritional databases for instant, actionable feedback.

Over just 30 minutes, you'll:

- Encode and analyze food images using state-of-the-art multimodal AI.
- Construct effective prompts for generative models to estimate calories.
- Integrate and query nutritional databases.
- Deliver personalized dietary advice in a user-friendly web interface.

This application demonstrates how cutting-edge AI can simplify complex nutritional tasks, empowering both health enthusiasts and professionals with innovative, real-world tools for dietary management and healthier living.

---

## Key Features

- **Image-Based Calorie Estimation:** Upload a food image and receive an instant calorie count, thanks to Llama 4 Maverick 17B 128E Instruct FP8's multimodal capabilities.
- **Personalized Dietary Guidance:** Get AI-generated advice tailored to your nutritional needs.
- **Extensible Architecture:** Easily integrate additional AI models, data sources, or user personalization features.
- **User-Friendly Interface:** Simple, intuitive, and designed for accessibility.

---

## Getting Started

1. **Clone the Repository**

   ```bash
   git clone https://github.com/AndrewMichael2020/MM-RAG-Style_analyzer_mini.git
   cd MM-RAG-Style_analyzer_mini
   ```

2. **Install Dependencies**

   Please ensure you have Python 3.8+ and pip installed.

   ```bash
   pip install -r requirements.txt
   ```

3. **Model and API Setup**

   - Sign up or log in to [watsonx.ai](https://www.ibm.com/products/watsonx-ai) to access the Llama 4 Maverick 17B 128E Instruct FP8 model.
   - Set up your API credentials and update your `.env` file as needed.

4. **Run the Application**

   ```bash
   python app.py
   ```

5. **Access the App**

   Open your browser and navigate to `http://localhost:5000` (or the port specified in your setup).

---

## Example Use Case

1. **Upload a food image.**
2. **Receive instant calorie estimation and nutritional breakdown.**
3. **Review AI-generated dietary advice tailored to your goals.**

---

## Conclusion

This project demonstrates the capabilities of the Llama 4 Maverick 17B 128E Instruct FP8 model in conjunction with AI-driven technologies for real-world dietary management solutions. The application provides hands-on experience encoding images, prompting generative models, and presenting nutritional data.

This project showcases how advanced AI can make complex nutrition tasks more accessible and actionable. Skills in multimodal AI and real-world application development are valuable assets for leveraging technology in health and wellness.

---

## Next Steps

To further enhance your expertise and build on this foundation, consider:

- **Advanced Prompt Engineering:** Craft more sophisticated prompts to boost AI-generated response quality.
- **Integrating More AI Models:** Try other multimodal models on watsonx.ai and compare results.
- **Adding Personalization:** Support user preferences, dietary restrictions, or profiles for tailored advice.
- **Expanding Nutritional Analysis:** Add features like meal planning, nutrient tracking, or healthy recipe suggestions using external APIs.
- **Optimizing for Mobile/Accessibility:** Build a mobile-friendly version or add accessibility features (voice recognition, text-to-speech, etc.).
- **Learning AI Ethics & Safety:** Explore topics such as bias, privacy, and ethical AI use, and implement user data safeguards.

---

## Authors & Contributors

- **Primary Authors:** Hailey Quach, Ricky Shi (IBM Instructors)
- **Implementer:** Andrew Ihnativ

---

## License

This project is for learning purposes. 

---

## Acknowledgments

- IBM Skills Network
- The watsonx.ai team
- All workshop participants
