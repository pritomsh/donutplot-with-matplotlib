A donut plot (also known as a doughnut chart or donut chart) is a type of chart that displays data in a circular shape, similar to a pie chart. However, unlike a pie chart, the center of the circle is empty, creating a "hole" in the middle, like a donut. ✔️
[Kaggle Notebook](https://www.kaggle.com/code/pritomsh/donutplot-with-matplotlib)  https://www.kaggle.com/code/pritomsh/donutplot-with-matplotlib for details 💯

## Create a Simple Donutplot🎉
```bash
# Create a pieplot
plt.pie(values, labels=labels,)
# add a circle at the center to transform it in a donut chart
my_circle=plt.Circle( (0,0), 0.7, color='white')
p=plt.gcf()
p.gca().add_artist(my_circle)
```
![](https://www.googleapis.com/download/storage/v1/b/kaggle-forum-message-attachments/o/inbox%2F8673484%2Ffc79a2097a5e49fb5b5a3619da46e84f%2Fsimple.png?generation=1679540110903892&alt=media)


## customize the distances of labels ✨

```bash
# using labeldistance parameter in the pie() function
# Label distance: gives the space between labels and the center of the pie
plt.pie(values, labels=labels, labeldistance=0.45)
```
![](https://www.googleapis.com/download/storage/v1/b/kaggle-forum-message-attachments/o/inbox%2F8673484%2Fd980491be184614b84d2269821267e75%2Flabel.png?generation=1679540140885131&alt=media)


## Give Legend

```bash
plt.legend(loc='upper left')
```
![](https://www.googleapis.com/download/storage/v1/b/kaggle-forum-message-attachments/o/inbox%2F8673484%2F78639d6a91b52f1db519926108d03e0d%2Flegend.png?generation=1679540226530091&alt=media)



## Wedges
wedgeprops parameter can be passed to the pie() function in order to set width of the wedge border lines and color:

```bash
plt.pie(values, labels=labels, wedgeprops = { 'linewidth' : 7, 'edgecolor' : 'white' })
```
 ![](https://www.googleapis.com/download/storage/v1/b/kaggle-forum-message-attachments/o/inbox%2F8673484%2Fa289846f67ee0568984cb40578e15e7c%2Fwedges.png?generation=1679540201552372&alt=media)


## Changing the background color of a donut plot
![](https://www.googleapis.com/download/storage/v1/b/kaggle-forum-message-attachments/o/inbox%2F8673484%2Face4d70967eea7e2d4ae43690d34f81e%2Fback.png?generation=1679540183668272&alt=media)

https://www.kaggle.com/code/pritomsh/donutplot-with-matplotlib for details

I would really appreciate it if you could take a time to **upvote** this notebook if you found it to be useful and instructive. I appreciate your time and thought in advance.
