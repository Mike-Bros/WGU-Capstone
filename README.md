# WGU-Capstone

This project is a Jupyter Notebook that uses Sklearn and Pandas to analyze a dataset of board games and predict the
average rating of a board game.

## Download and Setup Instructions

1. [Download this repository](https://github.com/Mike-Bros/WGU-Capstone) to your local machine. Place it in a directory
   of your choice such as `C:\Users\YourName\Documents\MBros-WGU-Capstone`.
2. [Download this dataset from Kaggle](https://www.kaggle.com/datasets/threnjen/board-games-database-from-boardgamegeek/data?select=games.csv).
    3. [Here is a direct download link](https://storage.googleapis.com/kaggle-data-sets/1870426/3055483/bundle/archive.zip?X-Goog-Algorithm=GOOG4-RSA-SHA256&X-Goog-Credential=gcp-kaggle-com%40kaggle-161607.iam.gserviceaccount.com%2F20240318%2Fauto%2Fstorage%2Fgoog4_request&X-Goog-Date=20240318T220654Z&X-Goog-Expires=259200&X-Goog-SignedHeaders=host&X-Goog-Signature=4189486a99df8e0030039e368bd622774ce3c5c0e60c87dc26b884aaf4552a8d4d8b067ac6de580274c8fa4d5b17f10ff953af2ae60817418a1487043c7547a7ad3059764975c1c131d4e156425776b98424fdd98a2f28c5ed7a667a18468dd6931945efb38aecf3929fef1a86a5eb2cb8ef1fbdfd8fe6a3f5610e215847efba9c1ee6f70aadf00f3066372afd0ef3098b270a49428dd99ef0f4c076e77e857a35428cfdd2a73b4fc07344ba603349b488304d4203d25fd884b6d8be2d1959a1ffd7726d7d14cddc9070864259c899e1f9033ed7dc36e8d8fde702ee24c4defc4e75e9e1e9a6e410b8913bde452af80643ddf3decaf753aedc2a32a43ed4c681).
4. Rename the downloaded zip file to `board-games.zip` and place it in the data folder of the repository downloaded in
   step 1.
5.

Ensure [Google Chrome is installed](https://support.google.com/chrome/answer/95346?hl=en&co=GENIE.Platform%3DDesktop#zippy=%2Cwindows)

6. Navigate to the project directory in the command prompt.
6. Ensure Python is installed.
    7. Running `python --version` should return `Python 3.10.5` or higher.
    8. [How to Install Python on Windows 10/11](https://www.digitalocean.com/community/tutorials/install-python-windows-10) -
       Tutorial provided by Digital Ocean, follow all optional step.
7. Ensure Jupyter Notebook is installed.
    9. Verify Jupyter Notebook is installed by running `jupyter --version` in the project directory command prompt.
    10. If Jupyter Notebook is not installed, run `pip install jupyter` in the project directory command prompt.
11. Run `jupyter notebook --port <open_port>` in the project directory command prompt.
    12. Replace `<open_port>` with an open port on your machine such as `8888`.
    13. The command prompt will display a URL such as `http://localhost:8888/tree?token=...`.
    14. Copy and paste the URL into Google Chrome to open the Jupyter Notebook.
15. This will open the tree view of the project directory in Jupyter Notebook. Select `Capstone.ipynb` and click the "
    Open"
    button to open the notebook in a new tab.
16. Run the notebook by clicking the menu "Run"-> "Restart Kernel and Run All Cells". This will run the entire notebook
    and display the results. Alternatively, you can run each cell individually by clicking the "Run" button in the top.
17. The very end of the notebook has an interactive section where you can input your own values to predict the average
    rating of a board game using the best performing model from the notebook.