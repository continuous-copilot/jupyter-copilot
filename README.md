# GitHub Codespaces ♥️ Jupyter Notebooks

Welcome to your shiny new codespace! We've got everything fired up and running for you to explore Python and Jupyter notebooks.

You've got a blank canvas to work on from a git perspective as well. There's a single initial commit with what you're seeing right now - where you go from here is up to you!

Everything you do here is contained within this one codespace. There is no repository on GitHub yet. If and when you’re ready you can click "Publish Branch" and we’ll create your repository and push up your project. If you were just exploring then and have no further need for this code then you can simply delete your codespace and it's gone forever.

<img src="https://github.com/user-attachments/assets/23d3ea40-e450-4d42-9cc1-5e0deca7dff5" alt="GitHub Copilot and Jupyter Notebooks" width="800" height="800">

# Titanic Exploration

The following steps will explore the data in Microsoft's _mslearn-introduction-to-machine-learning_ [Titanic dataset](https://raw.githubusercontent.com/MicrosoftDocs/mslearn-introduction-to-machine-learning/main/Data/titanic.csv) with GitHub Copilot by your side!

1. Create a new ipython notebook `titanic.ipynb`
1. Add a markdown cell and type the following (let Copilot complete the lines)

    ```md
    # Exploring Titanic Dataset
    The titanic is
    ```

1. Add a code cell and copy+paste the following into it, letting Copilot complete the rest:

    ```
    # Import the dataset at this URL as a Pandas dataframe
    url = 'https://raw.githubusercontent.com/MicrosoftDocs/mslearn-introduction-to-machine-learning/main/Data/titanic.csv'
    ```

1. Print the head of the dataframe.
1. Add a code cell and copy+paste the following into it, letting Copilot complete the rest:

    ```
    # calculate the number of survivors and print it
    ```

1. Add a code cell and copy+paste the following into it, letting Copilot complete the rest:

    ```
    # calculate the number of nonsurvivors and print it
    ```

1. Ask Copilot&mdash;either inline using `q:` and `a:` or via Copilot Chat&mdash;what the `sibsp` and `parch` columns mean.
1. Ask for a `catplot` showing correlation between passenger class and survivability.
1. Ask for a model to predict survivability by age.
1. Ask Copilot to help improve the survivability model.
1. Ask Copilot to help you understand the survivability model.
1. Ask Copilot to help you understand the data in the dataset.
