# pandas-puzzles
Make data manipulation bearable. Solve pandas puzzles.

## Guide 
[`pandas`](https://pandas.pydata.org/pandas-docs/stable/index.html) is one of the most popular Python packages for data manipulation. Knowing how to use `pandas` well can save you lots of time and labor. So that more people can reap the benefits of `pandas`, I've created some puzzles that can help you become more familiar with handling and wrangling data of all different kinds.[^1][^2]

Note that this repository assumes _no experience_ with `pandas`, though I _do_ expect that you have at least some Python experience. `pandas` beginners (cubs?) should start with the `easy` puzzles; those with more experience (yearlings?) can skim through these puzzles to ensure they've got good fundamentals. `medium` puzzles introduce more complex and less-common `pandas` methods and functions. Both `easy` and `medium` puzzles grow incrementally in difficulty and have some hand-holding regarding coding logic. `hard` puzzles attempt to mimic "real-world applications": each problem gives you a goal, raw data, and a gold DataFrame, and you must figure out how to process the raw data into the gold DataFrame as efficiently as possible.  

All puzzles are in Jupyter notebooks[^3] (`.ipynb` files) -- **please solve the notebooks on Google Colab (links provided below).** To actually write code on the notebook, you will need to make a copy of the Colab notebook.

Within each notebook, each puzzle is numbered and contains three kinds of cells: __goal__ cells tell you the problem number and what you are supposed to do, __solution__ cells show you the intended output (though the actual solution itself is hidden on Colab), and __code__ cells are where you write your answer. __Code__ cells are marked with the comment `### YOUR CODE HERE`. If you find solutions that are more efficient than mine, please let me know and I will include them in the possible solutions set for each problem.

Some tips for solving these problems:
- Documentation is your friend. Use [it](https://pandas.pydata.org/docs/).
- Dig around your data before you mess with it. 
- To mark how many lines of code that a problem should take you, I've marked all of the `easy` and `medium` puzzles with comments, where each comment requires one line of code; most of the puzzles can be solved in one line. As such, if you are taking multiple lines of code to solve these problems, you should probably rethink your approach and look at the documentation!

Best of luck!

## PUZZLES 
- [Easy puzzles](https://colab.research.google.com/drive/1ctHF2J8i-XgeQ1Vy7W5i8rrMd_iTM-z9?usp=sharing)



[^1]: Selfishly, I created these puzzles to force myself to be better at `pandas`. 
[^2]: Note that these puzzles are *not* tutorials. 
[^3]: To make materials available in more than one place, you can also find the full notebooks (aka notebooks **with solutions visible**) from the `notebooks` folder. Unfortunately, there is no easy way of hiding the input code when I give you the `.ipynb` files, so download at your own risk of spoiling the fun!
