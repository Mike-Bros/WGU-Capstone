# WGU-Capstone

This project is a Jupyter Notebook that uses Sklearn and Pandas to analyze a dataset of board games and predict the average rating of a board game.

## User Guide and Setup Instructions

1. [Download this repository](https://github.com/Mike-Bros/WGU-Capstone) to your local machine. Unzip the download it in a directory of your choice such as `C:\Users\YourName\Documents\MBros-WGU-Capstone`.
![Download Repo Image](https://raw.githubusercontent.com/Mike-Bros/WGU-Capstone/main/img/download-repo.png)
2. [Download this dataset from Kaggle](https://www.kaggle.com/datasets/threnjen/board-games-database-from-boardgamegeek/data?select=games.csv).
![Download Kaggle Dataset Image](https://raw.githubusercontent.com/Mike-Bros/WGU-Capstone/main/img/download-kaggle.png)
3. Rename the downloaded zip file to `board-games.zip` and place it in the data folder of the project directory created in step 1.
4. Ensure [Google Chrome is installed](https://support.google.com/chrome/answer/95346?hl=en&co=GENIE.Platform%3DDesktop#zippy=%2Cwindows).
5. Navigate to the project directory in the command prompt.
6. Ensure Python is installed.
    1. Running `python --version` should return `Python 3.10.5` or higher.
    2. [How to Install Python on Windows 10/11](https://www.digitalocean.com/community/tutorials/install-python-windows-10) -
       Tutorial provided by Digital Ocean, follow all optional step.
7. Ensure Jupyter Notebook is installed.
    1. Verify Jupyter Notebook is installed by running `jupyter --version` in the project directory command prompt.
    2. If Jupyter Notebook is not installed, run `pip install jupyter` in the project directory command prompt.
8. Run `jupyter notebook --port <open_port>` in the project directory command prompt.
   1. Replace `<open_port>` with an open port on your machine such as `8888`.
   2. The command prompt will display a URL such as `http://localhost:8888/tree?token=...`.
   3. Copy and paste the URL into Google Chrome to open the Jupyter Notebook.
   
![Open Jupyter in Chrome Image](https://raw.githubusercontent.com/Mike-Bros/WGU-Capstone/main/img/open-jupyter-in-chrome.png)
9. This will open the tree view of the project directory in Jupyter Notebook. Select `Capstone.ipynb` and click the "
   Open" button to open the notebook in a new tab.
![Open Capstone Notebook in Chrome Image](https://raw.githubusercontent.com/Mike-Bros/WGU-Capstone/main/img/open-capstone-notebook.png)
10. Run the notebook by clicking the menu "Run"-> "Restart Kernel and Run All Cells". This will run the entire notebook
    and display the results. Alternatively, you can run each cell individually by clicking the "Run" button in the top.
![Restart and Run All Image](https://raw.githubusercontent.com/Mike-Bros/WGU-Capstone/main/img/restart-kernel-and-run.png)
11. The very end of the notebook has an interactive section where you can input your own values to predict the average
    rating of a board game using the best performing model from the notebook.
![Interactive Prediction Tool Image](https://raw.githubusercontent.com/Mike-Bros/WGU-Capstone/main/img/prediction-tool.png)