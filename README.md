# AI-FASHION-SHOPPING-ASSISTANT-CHATBOT

## 📌 Project Overview

AI-FASHION-SHOPPING-ASSISTANT-CHATBOT is an AI-powered fashion outfit generation system that creates realistic full-body outfit images using text-based user inputs. The project uses the pretrained Stable Diffusion v1.5 model to generate photorealistic fashion images by combining clothing items such as tops, bottoms, and footwear into a single output image.

The system also provides weather-based clothing recommendations using temperature and humidity analysis to improve user comfort and shopping experience.

---

# 🎯 Objectives

* Generate realistic full-body fashion outfit images
* Combine top, bottom, and footwear into one image
* Reduce the imagination gap in online shopping
* Provide weather-based fabric recommendations
* Improve virtual shopping experience using AI
* Build a scalable AI fashion assistant system

---

# ✨ Features

* AI-based outfit image generation
* Full-body photorealistic fashion output
* User-customized outfit creation
* Weather-based clothing suggestions
* Temperature and humidity analysis
* Fast image generation using GPU
* Stable Diffusion v1.5 integration
* Google Colab implementation

---

# 🧠 Technologies Used

* Python
* Stable Diffusion v1.5
* PyTorch
* Diffusers
* Transformers
* Google Colab
* CUDA GPU
* PIL (Python Imaging Library)

---

# ⚙️ Working Process

## Step 1: User Input

The user provides:

* Gender
* Category
* Color
* Top wear
* Bottom wear
* Footwear
* Temperature
* Humidity

## Step 2: Prompt Construction

The system converts user inputs into a descriptive text prompt.

Example:

> "A female wearing a blue printed kurti with pants and sandals in casual style"

## Step 3: AI Image Generation

The pretrained Stable Diffusion v1.5 model processes the prompt and generates a realistic fashion outfit image.

## Step 4: Weather Recommendation

Based on temperature and humidity values, the system recommends suitable fabrics such as:

* Cotton
* Linen
* Wool
* Light breathable fabrics

## Step 5: Output

The generated image is saved in PNG format.

---

# 🤖 Model Used

## Stable Diffusion v1.5

Stable Diffusion is a diffusion-based text-to-image deep learning model.

### Why Stable Diffusion?

* Produces realistic high-quality images
* Faster generation with GPU
* Better visual consistency
* No training from scratch required
* Supports customizable prompts

---

# 🔄 Diffusion Process

The model works using a denoising diffusion process:

1. Starts with random noise
2. Gradually removes noise
3. Generates a clear photorealistic image

---

# 🖥️ Execution Environment

* Platform: Google Colab
* Language: Python
* GPU Support: CUDA Enabled

---

# 📊 Performance

* GPU generation time: ~8–10 seconds
* CPU execution: Slower compared to GPU
* Output quality depends on prompt clarity

---

# 📂 Project Structure

```text
AI-FASHION-SHOPPING-ASSISTANT-CHATBOT/
│── project.ipynb
│── screenshots/
│── outputs/
│── README.md
│── requirements.txt
```

---

# 📸 Sample Inputs

* Gender: Female
* Category: Casual
* Color: Blue
* Top: Printed Kurti
* Bottom: Pant
* Footwear: Sandals
* Temperature: 45°C
* Humidity: 70%

---

# 📷 Output

The system generates:

* Full-body fashion outfit image
* Weather-based clothing recommendation
* PNG image output

---

# 🚀 Future Enhancements

* Web application deployment
* Real-time virtual try-on system
* Voice-based fashion assistant
* AR/VR fashion integration
* Personalized recommendation engine
* Mobile application support

---

# 📚 Advantages

* Enhances online shopping experience
* Reduces outfit imagination difficulty
* Provides personalized outfit generation
* Improves comfort using weather analysis
* Saves shopping time

---

# ⚠️ Limitations

* Output quality depends on prompt accuracy
* GPU required for faster execution
* Limited customization in current version

---

# 📖 References

1. AI-Powered Chatbots in E-Commerce
2. FashionBERT: Text and Image-based Recommendation Model for Fashion Items
3. Conversational Agents in Retail: A Review
4. Personalized Product Recommendation Using Machine Learning
5. Natural Language Processing Techniques for Intelligent Chatbots

---

# 👩‍💻 Authors

* Thanuja V

Department of Computer Science and Engineering (Artificial Intelligence and Machine Learning)

---

# 🙏 Acknowledgement

We thank our faculty members and institution for supporting this project and providing guidance throughout the development process.

---

# ⭐ Conclusion

This project successfully demonstrates how AI can improve the online fashion shopping experience through intelligent outfit generation and weather-based clothing recommendations. Using Stable Diffusion v1.5, the system generates realistic full-body fashion images efficiently and provides a foundation for future AI-powered fashion assistant applications.
