# ✈️ AI Travel Agent

An intelligent, free-to-use travel assistant that generates personalized trip itineraries and provides accurate weather forecasts. Built using **Python**, **Hugging Face Transformers**, and **Gradio**.

## 🚀 Features

* **Custom Itineraries:** Generates day-by-day travel plans based on destination, trip duration, and user interests using the `tiiuae/falcon-7b-instruct` LLM.
* **Real-Time Weather:** Fetches accurate, real-time weather forecasts (Max Temp & Rain Probability) using the Open-Meteo API.
* **Zero Cost:** Runs entirely on free tools—no OpenAI API keys or paid weather subscriptions required.
* **User-Friendly Interface:** clean web UI built with Gradio.
* **Robust Location Search:** Uses `Geopy` to convert city names into precise coordinates.

## 🛠️ Tech Stack

* **Language:** Python 3.10+
* **UI Framework:** Gradio
* **AI Model:** Falcon-7B-Instruct (via Hugging Face)
* **Weather Data:** Open-Meteo API
* **Geolocation:** Geopy (Nominatim)

## 📦 Installation & Usage

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/suhashgampa1/ai_travel-agent.git](https://github.com/suhashgampa1/ai_travel_agent.git)
    cd ai-travel-agent
    ```

2.  **Install dependencies:**
    ```bash
    pip install transformers duckduckgo-search gradio geopy requests accelerate
    ```

3.  **Run the App:**
    ```bash
    python app.py
    ```
    *(Or run the notebook `AI_Travel_Agent.ipynb` in Google Colab)*

4.  **Access the Interface:**
    Open the local URL provided in the terminal (usually `http://127.0.0.1:7860`).

## 📸 Demo

* **Input:** "Rome", 3 Days, "History and Food"
* **Output:** A detailed 3-day breakdown of historical sites and restaurants, followed by the actual weather forecast for Rome for the next 3 days.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is open-source and available under the MIT License.
