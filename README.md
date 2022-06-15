# Introduction
I love data visualization, I love charts and graphic products. So my eyes are really sensitive to charts, shapes and colors. I believe that there will always be a way to facilitate the information digestion process for the audience by using data visualization.<br />
So there was a time when I was reading news on the Internet, I saw [this article](https://laodong.vn/tien-te-dau-tu/chung-khoan-tien-khon-dang-chay-vao-co-phieu-nao-1041204.ldo). This is a Vietnamese National Journal about stock news. Its title is kind of like " Where does the "wise money" go?". And as you can guess, the chart immediately caught my eyes and got my attention. <br />
I mean, it is such a great idea to add a viz to a type of article that is supposed to be full of numbers. But the thing is, this chart failed to aid the readers to digest the article. And turns out, it does not help at all.<br />
I think data visualization is not so popular in this kind of article in Vietnam. People may add it like adding eye's candy for the dull pages of news . Anyway, I believe it's worth a try to give it a better visualization so the information would be conveyed more effectively, because at the end of the day, I think, the audience deserve to have an easier way to digest information. <br />
 
Let's consider this viz and see how much we can help it communicate more effectively!

# Inspection
These followings are the pros and cons of the article in terms of using data viz
## Pros
* Using a cooler way to tell a story<br />
In this article, they use a chart to show the information instead of throwing out a bunch of hypnotizing numbers. Obviously, information in graphic form will be much easier to absorb.
* The good use of chart<br />
Bar charts is such a good choice in this article to visualize because they are simple and intuitive especially when comparing among several items. Additionally, the industries names are listed in a logical order so the audience are easier to read the chart. The highlight also is added to grasp the attention.
## Cons
* The article does not leverage the advantage of data visualization<br />
The article does not use the bar chart to reflect the crucial problem, or in other words, the chart does not help answer the topic question which is “Where is the money flowing into?”
* The problems with the bar chart itself prevents it from supporting the article in an effective way. <br />
In the article, the bar chart summarizes the information of a paragraph. However, the audience would find it difficult to identify this paragraph. The chart gets the audience confused, or even misled.

After studying the chart, I think there are some problems that need to be considered:
  * The lack of title/subtitle gives the audience an ambiguous idea about what the chart is telling.  
  * Adding irrelevant information <br />
VN-INDEX, HNX-INDEX, UPCOM-INDEX are the items that differ from the others. Furthermore, throughout the article, these items, or its relationship with other items, are not mentioned at all. There is no explanation for why they are in the chart and how they interact with the other ones.
  * Weak use of highlighting effects <br />
It is easy to notice the red rectangular is added to attract the audience’s attention to the VN-INDEX item. However, this is such a lazy way of highlighting and does not give an aesthetic pleasing.  

# Implement 
In this project, my work will narrow down the scope to the second part of the article which starts with the question “Where is the money flowing into?”. Accordingly, I will try to achieve two goals which are answering the topic question “Where is the money flowing into?” and improving the chart in the article. 

## Answering the topic question “Where is the money flowing into?”

![image](https://user-images.githubusercontent.com/106227875/173179645-480de6f5-9b66-4369-adf3-990ac1850b8f.png)
These are steps that I have taken to create the first chart. <br />
  * **Collecting the raw data** from the article. If you read the article, the data measures the same type of information but in different time references. To answer the  question, my first chart used the data which shows the cash flowing into certain industries. This data set compares the average trading volume between April and   March. <br />
  * **Creating column chart** because it is simple and intuitive. The first idea was to create two contrast sections which indicated the in and out of cash flow.  I chose Excel to visualize because with the usual types of chart, Excel would be the better tool. Also, I did not have to import the dataset into some other tools.<br />
  * **Pushing the chart to the background by making it all in grey**. This is the way I do a chart. I push everything in the background and only fill color to the objects that contain crucial information.<br />
  * **Filling the positive percentage with green** because I wanted them to be associated with the green on the stock tickers. In the stock tickers, the green means the rise and the red means the decline of stock prices. However, I did not choose the red for the decreasing percentages because I did not want the audience's attention to be on this part. So I filled the cash flowing out in grey. <br />
  * **Adding the dollar sign** to indicate the flowing direction of money. <br />
  * **Adding data labels for all the columns**. I also deleted y-axis because it was then redundant.<br />
  * **Adding title and subtitle** and let them in grey.<br />
## Improving the chart in the article.<br />
![image](https://user-images.githubusercontent.com/106227875/173179713-771a7fbd-c0a7-4c74-a156-7a36f7dd4b16.png)
  * **Using Excel to create a column chart** because I thought it would be a better reflection of decreasing numbers than a bar graph.   <br />
  (optional)**Adding a highlight** for the VN-Index item.  However, this could be omitted because it was not relevant to the article’s content. 
  * **Setting the chart all in grey** <br />
  * **Filling color for the column with the numbers mentioned in the article**. I chose red for the columns to let the audience associate with the decreasing prices on the stock tickers.<br />
  * **Adding add-in information** (if any) to the columns. I kept the y-axis to make to column easier to look up the columns'values because there were too many columns for each column data label. <br />
  * **Adding title and subtitle** and put them in grey.

# File reading guide
**Translated article (PDF file)** <br />
This is the transcript of the article (credit to Google Translate) that lets you understand the context for this viz.<br />
**Dataset (Excel file)** <br />
This is the data source and the primary viz I created by using Excel.<br />
**Data Viz (PDF file)** <br />
This is the PDF version for two charts I have created .
