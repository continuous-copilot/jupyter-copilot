# GitHub Codespaces ♥️ Jupyter Notebooks

Welcome to your shiny new codespace! We've got everything fired up and running for you to explore Python and Jupyter notebooks.

You've got a blank canvas to work on from a git perspective as well. There's a single initial commit with what you're seeing right now - where you go from here is up to you!

Everything you do here is contained within this one codespace. There is no repository on GitHub yet. If and when you’re ready you can click "Publish Branch" and we’ll create your repository and push up your project. If you were just exploring then and have no further need for this code then you can simply delete your codespace and it's gone forever.

# Titanic Exploration

Try exploring data from [MSDocs](https://raw.githubusercontent.com/MicrosoftDocs/mslearn-introduction-to-machine-learning/main/Data/titanic.csv)

Steps:
1. Create a new ipython notebook `titanic.ipynb`
1. Add a markdown cell and type the following (let Copilot complete the lines)
    ```md
    # Exploring Titanic Dataset
    The titanic is_
    ```
1. Type `url = 'https://raw.githubusercontent.com/MicrosoftDocs/mslearn-introduction-to-machine-learning/main/Data/titanic.csv'` and then prompt Copilot to import the data as a dataframe
1. Print the head of the dataframe
1. `# calculate the number of survivors and print it`
1. `# calculate the number of nonsurvivors and print it`
1. Ask Copilot (using `q: and a:`) or Copilot Chat what the `sibsp and parch` columns mean
1. Ask for a `catplot` showing correlation between class and survivability
1. Ask for a model to predict survivability by age
1. Ask Copilot to help improve the model