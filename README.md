# 3D-Plots-in-Matplotlib
This repo help us understand three dimensional plots by using widely used visualization tool - Matplotlib

# Get started
Here are some necessary dependencies we will need: <br>
- matplotlib.pyplot of cause
- mpl_toolkits.mplot3d for creating the 3d projection
- numpy for manipulating data

*We add %matplotlib inline so that we can display the plots inline in the notebook. This saves us from having to call plt.show() all the time. Alternatively, you could also use %matplotlib notebook to enter interactive mode, which allows you to simply click and drag to change the viewpoint.*

Python is known to be good for data visualization. There are many tools in Python enabling it to do so: matplotlib, pygal, Seaborn, Plotly, etc. Among these, matplotlib is probably the most widely used one. On one hand, it offers a lot of flexibilities; on the other hand, it is also very low-level and may not the most straight forward to use. There are a lot of articles explaining how to do 2d plotting with matplotlib already. In this post, we will focus more on plotting in 3d.

# Data Visualization Techniques
*There are many ways to visualize data, the two most popular techniques among them are PCA and t-SNE:*<br>
- PCA: Principal Component Analysis, as the name suggests, it finds the most important and relevant components to represent the data. In essence, this algorithm reduces dimensionality in a way that the information loss is minimum. There is a more detailed explanation for those who are curious.
- T-SNE: t-Distributed Stochastic Neighbor Embedding, a more complicated name. Essentially, this algorithm looks at the data distribution and tries to represent the same distribution with fewer dimensions. Again there some more detailed information.

