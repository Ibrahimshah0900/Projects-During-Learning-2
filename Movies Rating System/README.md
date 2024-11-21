

# Movie Ratings System

## 📜 Project Description
The **Movie Ratings System** is a simple Python-based project that allows users to rate movies, view average ratings, and find the top-rated movie. Ratings are stored in a CSV file for easy access and data management. This project demonstrates the use of Python's `csv` module for handling CSV files, basic statistics, and user interaction.

---

## 🛠️ Features
- Add ratings for movies (movie name, user name, and rating).
- Calculate and display average ratings for all movies.
- Identify the top-rated movie based on average ratings.
- Enhanced user interaction through a menu-driven interface.
- Input validation to ensure ratings are between 1 and 5.

---

## 🚀 Technologies Used
- **Python**: Core programming language for the project.
- **CSV**: To store and manage movie ratings data.

---

## 📂 File Structure
```
├── movie_ratings.csv      # CSV file for storing movie ratings
├── movie_ratings_system.py # Python script for the project
```

---

## 🖥️ How to Run the Project
1. **Clone the Repository**  
   ```bash
   git clone https://github.com/your-username/movie-ratings-system.git
   cd movie-ratings-system
   ```

2. **Run the Script**  
   ```bash
   python movie_ratings_system.py
   ```

---

## 🔍 How It Works
### Menu Options:
1. **Add a Rating**  
   - Enter the movie name, your name, and a rating (between 1 and 5).  
   - The rating is appended to the `movie_ratings.csv` file.

2. **View Average Ratings**  
   - Displays the average ratings for all movies listed in the CSV file.

3. **Find the Top-Rated Movie**  
   - Identifies and displays the movie with the highest average rating.

4. **Exit**  
   - Closes the program.

### Input Validation:
- Ensures that ratings are numerical values between 1 and 5.
- Handles invalid inputs gracefully.

---

## 📖 Code Explanation
The project is structured using the following functions:

1. **`initialize_csv(file_path)`**  
   - Creates the `movie_ratings.csv` file if it doesn't exist and adds column headers.

2. **`add_rating(file_path, movie_name, user_name, rating)`**  
   - Adds a movie rating to the CSV file.

3. **`calculate_average_ratings(file_path)`**  
   - Calculates and returns a dictionary of movies and their average ratings.

4. **`find_top_rated_movie(file_path)`**  
   - Finds the movie with the highest average rating.

5. **`display_average_ratings(file_path)`**  
   - Displays all movies with their average ratings.

6. **`movie_ratings_system()`**  
   - Implements the menu-driven interface for the project.

---

## 🔢 Example Interaction
```
--- Movie Ratings System ---
1. Add a Rating
2. View Average Ratings
3. Find the Top-Rated Movie
4. Exit
Enter your choice: 1
Enter the movie name: Interstellar
Enter your name: User1
Enter your rating (1-5): 4.5
Rating added successfully!

--- Movie Ratings System ---
1. Add a Rating
2. View Average Ratings
3. Find the Top-Rated Movie
4. Exit
Enter your choice: 2

Average Ratings:
Interstellar: 4.50
```

---

## 📈 Learning Focus
This project demonstrates:
- Managing and aggregating data from CSV files.
- Using Python's `csv` module for reading and writing files.
- Implementing a menu-driven system for user interaction.
- Performing basic statistics like calculating averages.

---

## 🙌 Contributions
Contributions are welcome! Feel free to fork the repository, make changes, and submit a pull request.

-