# 🎬 Movie Recommendation System

Deployed on: https://movie-recommender-system-web-c548179c70e6.herokuapp.com/

A content-based movie recommendation system built with Python, Streamlit, and the TMDb API. The system suggests similar movies based on your selection using machine learning techniques.

## 🚀 Features

- Interactive movie search with autocomplete
- Real-time movie recommendations
- Movie poster displays
- Content-based filtering using movie features
- Responsive web interface
- Error handling and user feedback

## 📋 Prerequisites

Before running this application, make sure you have:

- Python 3.8 or higher
- TMDb API key (get it from [TMDb website](https://www.themoviedb.org/documentation/api))
- Required Python packages (listed in requirements.txt)

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/movie-recommendation-system.git
cd movie-recommendation-system
```

2. Create and activate a virtual environment (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install required packages:
```bash
pip install -r requirements.txt
```

4. Set up your TMDb API key:
   - Replace `"YOUR_API_KEY"` in `app.py` with your actual TMDb API key
   - Or set it as an environment variable:
     ```bash
     export TMDB_API_KEY="your_api_key_here"  # On Windows: set TMDB_API_KEY=your_api_key_here
     ```

## 🏃‍♂️ Running the Application

1. Make sure you have the required data files:
   - `movies_dict.pkl`: Preprocessed movies data
   - `similarity.pkl`: Similarity matrix for recommendations

2. Start the Streamlit app:
```bash
streamlit run app.py
```

3. Open your web browser and go to `http://localhost:8501`

## 📦 Project Structure

```
movie-recommendation-system/
│
├── app.py                  # Main Streamlit application
├── movies_dict.pkl        # Preprocessed movies data
├── similarity.pkl         # Similarity matrix
├── requirements.txt       # Python dependencies
└── README.md             # Project documentation
```

## 📝 Requirements

```
streamlit>=1.24.0
pandas>=1.5.0
requests>=2.28.0
pickle5>=0.0.11  # If using Python < 3.8
```

## 🤝 Contributing

1. Fork the repository
2. Create a new branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature/improvement`)
6. Create a Pull Request

## 🪲 Known Issues

- The TMDb API may occasionally be slow to respond
- Some movies might not have poster images available


## 🙏 Acknowledgments

- [TMDb API](https://www.themoviedb.org/documentation/api) for movie data
- [Streamlit](https://streamlit.io/) for the web interface

Project Link: ([https://movie-recommender-system-web-c548179c70e6.herokuapp.com/](https://movie-recommender-system-web-c548179c70e6.herokuapp.com/))
