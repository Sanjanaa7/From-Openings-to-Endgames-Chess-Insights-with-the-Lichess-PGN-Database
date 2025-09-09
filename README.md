# ♟ From Openings to Endgames: Chess Insights with the Lichess PGN Database  

## 📌 Overview  
This project leverages the **Lichess PGN Database** to explore chess strategies across the entire game — from the very first move to the final checkmate.  

By processing PGN (Portable Game Notation) files, the analysis identifies the most frequent **opening moves**, generates **piece activity heatmaps**, evaluates **king safety zones**, tracks **pawn promotions**, and visualizes **frequent endgame positions**.  

The goal is to provide **data-driven insights into chess** through a combination of statistical analysis and visual storytelling, making it valuable for players, learners, and researchers alike.  

---

## 📊 Dataset Used  
- **Source:** [Lichess Database](https://database.lichess.org/)  
- **Dataset File:** `lichess_db_standard_rated_2013-01.pgn.zst`  
- **Description:** This dataset contains rated standard chess games played on Lichess in **January 2013**.  
- **Format:** PGN (Portable Game Notation), compressed with Zstandard.  

---

## 🚀 Features  
- **Opening Trends** → Most common opening moves for White and Black.  
- **Piece Activity Heatmap** → Which squares are most frequently visited.  
- **King Safety Analysis** → Check and checkmate visualization zones.  
- **Pawn Promotion Tracker** → Where pawns are most often promoted in endgames.  
- **Frequent Endgame Positions** → Common piece distributions in late-game scenarios.  

---

Dependencies:

python-chess

cairosvg

pillow

IPython

📂 Usage

Download the dataset from the Lichess Database
:

wget https://database.lichess.org/standard/lichess_db_standard_rated_2013-01.pgn.zst
zstd -d lichess_db_standard_rated_2013-01.pgn.zst -o lichess_sample.pgn


Update the input_file path in the notebook/script.

Run the notebook to generate:

Top opening moves with frequency counts

Chessboard visualizations with arrows

Heatmaps of board activity

King safety analysis

Endgame promotion and position visualizations

📊 Example Outputs
✅ Opening Move Visualization

✅ Piece Activity Heatmap

✅ King Safety Analysis

✅ Pawn Promotion Tracker

✅ Frequent Endgame Positions

🎯 Applications

Learn common chess openings and their popularity.

Study positional play through heatmaps.

Analyze check, checkmate, and king safety patterns.

Explore endgame strategies and pawn promotions.

Serve as a foundation for AI/ML chess prediction models.

🤝 Contributing

Contributions are welcome! Feel free to fork this repository, open issues, and submit pull requests.

📜 License

This project is licensed under the MIT License.
About Me

Name: Sanjanaa S

Course: B.Tech Artificial Intelligence and Data Science

College: Rajalakshmi Institute of Technology

Year: 3rd Year

Email: sanjanaasrinivasan7@gmail.com

LinkedIn: www.linkedin.com/in/sanjanaa-srinivasan-802ba5290

GitHub: https://github.com/Sanjanaa7
