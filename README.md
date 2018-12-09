## Lending Club – Group 13

# Motivation
- Introduce the project motivation both as a whole as well as motivations
for important defining aspects of your work. For example were there any visualization
or UI primitives that informed your work?

The objective is to help Lending Club investors in deciding which loans to make investments in, such that (1) the expected rate of return is maximized for the investors and (2) that the portfolio recommendation for the investor is not racially discriminatory. We have sought to achieve the objectives laid out above by examining a wide range of loan characteristics (such as loan amount, interest rate, repayment schedule, and grade), as well as the individual characteristics (such as employment, annual income, and credit history).

# Description of Data and EDA
- What data are you dealing with? What methods have you used to explore the data (incl. initial explorations, models, data cleansing and reconciliation, etc)? What insights did you gain? How did those methods influence your work?

We downloaded year-by-year datasets (quarter-by-quarter datasets for loans given out between 2016 and 2018) from the Lending Club website. 


# Literature Review/Related Work
- This can include noting any key papers, texts,
other software sources, talks or websites that you have used to develop your modeling
approach and/or that informed your demo/site.

A number of literature on mortgage and lending practices were helpful in calibrating the trajectory of our work. The research work done by Padhi (2017) helped us formulate the relevant questions with respect to loan applications and racial discrimination (for example, is there a substantially higher proportion of loan rejection in the neighborhoods with higher black and hispanic resident population? Do black and hispanic residents have inherently lower credit ratings, or are lending practices guided by racially motivated schemes?"). Another literature that helped us raised relevant questions is the work of Scheurmann and Matthews (2005) on building a Neural Network to manage arrears. The literature raises the question of the effect of varying level of train-to-test dataset proportions on the accuracy performance; specifically, the literature suggests that it is helpful to include higher proportion of samples in the training set (say, 67% to 33%) to enlarge the number of samples of defaulted borrowers (since the proportion of defaulted borrowers is generally smaller). 

**References**

Padhi, Michael. "The Effects of Peer-to-Peer (P2P) Lending on Competition, Discrimination, and Financial Stability". 2017. Working Paper, Robert H. Smith School of Business.

Scheurmann, Esther, and Chris Matthews. "Neural network classifers in arrears management." International Conference on Artificial Neural Networks. Springer, Berlin, Heidelberg, 2005.

# Modeling Approach: 
- What was your baseline model for comparison? What further
models did you implement? Description of your implementations beyond the baseline
model. Briefly summarize any changes in your project goals or implementation plans
you have made along the way. These changes are a natural part of any project, even
those that seem the most straightforward at the beginning. The story you tell about
how you arrived at your results can powerfully illustrate your process.

## Repayment Analysis – Regression
## Default Probability Analysis – Random Forest

# Results
- Describe the results and emphasize the most important results. Did you have
to reconsider some of the original assumptions?

# Conclusions and Summary
- Review what was discussed in the Overview and
Motivation sections (don’t repeat them word-for-word!). Discuss your contributions
including the successes and areas for improvement.

# Future work
- Discuss extensions to and new directions for your work. What do you
think would be interesting to pursue next? Are there any ideas worth exploring that
you didn’t get a chance to explore?

# Style (this is just a reference written in the Guidelines)
- Your work should embrace simplicity over complexity, be intuitive for an only
slightly informed user to navigate, and as much as possible be appropriately polished,
robust, and reliable. Visualizations should be constructed to slice through complexity
and convey information and insight elegantly and concisely. We recognize that these
are not going to be fully constructed products, but style still matters.



# Discrimination/Equity Analysis









# General GitHub Guidelines

You can use the [editor on GitHub](https://github.com/ms-choi/lendingclub13/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/ms-choi/lendingclub13/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
