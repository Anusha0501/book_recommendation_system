### 📚 BookNexus – A Book Recommendation System  

#### 🔹 Overview  
BookNexus is a web-based book recommendation system that suggests books based on collaborative and content-based filtering techniques. Users can browse the **Top 50 Books** or get personalized recommendations by entering a book title.  

#### 🔹 Features  
- Displays the **Top 50 Books** with ratings, authors, and cover images.  
- Provides **personalized recommendations** based on a book title.  
- Built using **Flask** and **Gunicorn** for backend processing.  
- Uses **HTML, CSS, and Bootstrap** for a simple UI.  
- Implements machine learning models for book recommendations.  

#### 🔹 Tech Stack  
- **Frontend:** HTML, CSS, Bootstrap  
- **Backend:** Flask, Gunicorn  
- **Libraries:** NumPy, Pandas, Pickle  
- **Deployment:** Hosted using Gunicorn  

#### 🔹 Project Structure  
```
├── templates/
│   ├── index.html       # Home Page - Displays Top 50 Books
│   ├── recommend.html   # Recommendation Page
├── app.py               # Flask Backend
├── books.pkl            # Books dataset
├── popular.pkl          # Popular books dataset
├── pt.pkl               # Processed data for recommendations
├── similarity_scores.pkl # Precomputed similarity matrix
├── requirements.txt      # Dependencies
├── Procfile              # Deployment configuration
├── README.md             # Project Documentation
```

#### 🔹 Installation & Usage  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/BookNexus.git
   cd BookNexus
   ```  
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```  
3. Run the Flask app:  
   ```bash
   python app.py
   ```  
4. Open `http://127.0.0.1:5000/` in your browser.  

#### 🔹 Contributing  
Feel free to fork this project, create a feature branch, and submit a pull request!  
