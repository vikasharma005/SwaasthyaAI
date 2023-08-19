# SwaasthyaAI: Personalized Fitness Assistant

![SwaasthyaAI Logo]([link_to_your_logo_image](https://github.com/vikasharma005/logo.png))

SwaasthyaAI is an interactive web application built using Streamlit and powered by the OpenAI GPT-3.5 model. It aims to provide users with personalized fitness plans and recommendations based on their fitness goals, dietary preferences, training styles, and other inputs.

## Features

- Choose from various fitness goals: Weight Loss, Muscle Gain, or Maintenance.
- Select dietary preferences to customize your meal recommendations.
- Input the items in your fridge for more accurate dietary recommendations.
- Mix and match training styles from a range of renowned trainers and disciplines.
- Get a detailed, AI-generated fitness plan and philosophy tailored to your inputs.
- Download your personalized fitness plan as a text file.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/vikasharma005/SwaasthyaAI.git
   cd SwaasthyaAI
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Set up your OpenAI API key:

   - If you have an OpenAI API key, add it to the `secrets.toml` file in the project root:

     ```toml
     [secrets]
     OPENAI_API_KEY = "your_openai_api_key_here"
     ```

   - If you don't have an OpenAI API key, you can still explore the app without it by leaving the field empty.

4. Run the Streamlit app:

   ```bash
   streamlit run app.py
   ```

5. Access the app in your web browser at `http://localhost:8501`.

## Contributing

Contributions are welcome! If you find any issues, have suggestions, or want to add new features, feel free to open an issue or submit a pull request.

## Credits

This project was developed by ([Vikas Sharma](https://github.com/vikasharma005)). The app utilizes the Streamlit library and the OpenAI GPT-3.5 model.

## License

This project is licensed under the [MIT License](LICENSE).
```

