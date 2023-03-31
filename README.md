# 🚀 Putting ChatGPT to (Data Science) Work

## About

I started off with the objective of writing a Streamlit application for using OpenAI APIs to query and produce responses for project data. To get started, I used a test dataset -- a [directory of Starbucks locations](https://www.kaggle.com/datasets/starbucks/store-locations) -- that I found on Kaggle. 

Initial results were very promising:

![](/Users/holly/Documents/GitHub/coffee_chat/docs/images/Botty0.png)

![](/Users/holly/Documents/GitHub/coffee_chat/docs/images/botty1.png)

But it quickly became apparant that the answers were nonsense. What we really need ChatGPT to do is to:

(1)  Understand the basic nature our dataset -- column names, sample data, where the files are located, etc.

(2) Write code that could help us answer our question, based on the dataset. The code should be easy to cut-paste and use. 

This worked out super well:

![](/Users/holly/Documents/GitHub/coffee_chat/docs/images/Botty2.png)

But, all this cutting-and-pasting from Streamlit into PyCharm got annoying. So, I started over again and prepared a Jupyter notebook that does the same thing, plus (at your own risk) automatically parses and executes the code as well. It's so neat! Take a look at a sample output:

![](/Users/holly/Library/Application%20Support/marktext/images/2023-03-30-22-53-30-image.png)

![](/Users/holly/Library/Application%20Support/marktext/images/2023-03-30-22-57-55-image.png)

The craziest thing is that the output (maps, charts) will look a little different everytime (!), but the numerical results will generally be consistent. 

As a next step, I will apply these techniques to project data -- including multiple datasets -- to see how we may expedite our data exploration work. Meanwhile, comments and feedback welcome!





## License

This repo is licensed under the [**World Bank Master Community License Agreement**](LICENSE.md), because I'm a company gal, through and through. 
