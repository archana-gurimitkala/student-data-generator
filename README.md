# 🎓 Synthetic Student Data Generator

An AI-powered tool to generate realistic synthetic student data using OpenAI GPT-4o-mini or Hugging Face's Llama 3.2 model. Perfect for testing, development, and creating sample datasets without privacy concerns.

## ✨ Features

- **AI-Powered Generation**: Uses advanced LLMs to create realistic student records
- **Dual Model Support**: Choose between OpenAI (faster) or Hugging Face Llama (free, local)
- **Customizable**: Describe any type of student data you need
- **Interactive UI**: Beautiful Gradio interface for easy data generation
- **Export Ready**: Generated data is returned as a Pandas DataFrame for easy export

## 🚀 Quick Start

### Prerequisites

- Google Colab account (for running the notebook)
- OpenAI API key (optional, for faster generation)
- Hugging Face token (optional, for using Llama model)

### Setup

1. Open the notebook in Google Colab
2. Add your API keys to Colab Secrets:
   - `OPENAI_API_KEY` (if using OpenAI)
   - `HF_TOKEN` (if using Hugging Face)
3. Run all cells to install dependencies and launch the interface

## 📖 Usage

1. **Describe your data**: Enter a description of the students you want (e.g., "Computer Science students with high GPAs")
2. **Set quantity**: Choose how many student records to generate (1-50)
3. **Choose model**: Select OpenAI for faster results or Hugging Face for free local generation
4. **Generate**: Click submit and view your synthetic student data!

### Example Descriptions

- "Computer Science students with high GPAs"
- "Business majors from 2022"
- "Engineering students with internships"
- "Freshman students enrolled in 2024"

## 📸 Screenshots

### Using OpenAI (GPT-4o-mini)
![OpenAI Output](images/openai_output.png)
*Faster generation with OpenAI API - checkbox checked*

### Using Hugging Face (Llama 3.2)
![Hugging Face Output](images/huggingface_output.png)
*Free local generation with Hugging Face model - checkbox unchecked*

### Interface Overview
![Interface Overview](images/interface_overview.png)
*Interactive Gradio interface with example prompts*

## 📊 Generated Data Fields

Each student record includes:
- **Name**: Full name
- **Email**: University email (format: firstname.lastname@university.edu)
- **Student ID**: Unique ID (format: STU######)
- **Age**: Between 18-25
- **Major**: Academic program
- **GPA**: Between 2.0-4.0 (2 decimal places)
- **Year**: Freshman, Sophomore, Junior, or Senior
- **Enrollment Date**: Date in YYYY-MM-DD format (2020-2024)

## 🛠️ Technologies Used

- **Gradio**: Interactive web interface
- **OpenAI API**: GPT-4o-mini for fast data generation
- **Hugging Face Transformers**: Llama 3.2 3B Instruct model
- **Pandas**: Data manipulation and DataFrame handling
- **PyTorch**: Deep learning framework
- **bitsandbytes**: 4-bit quantization for efficient model loading

## 📝 Notes

- The notebook is designed to run in Google Colab for easy GPU access
- OpenAI model requires API credits (pay-per-use)
- Hugging Face model runs locally and is free but requires GPU
- Generated data is synthetic and should not be used for real student records

## 🔒 Privacy & Security

- All API keys are stored securely in Colab Secrets
- No real student data is used or stored
- Generated data is completely synthetic

## 📄 License

This project is open source and available for educational purposes.

