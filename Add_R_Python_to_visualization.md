


https://learn.microsoft.com/en-us/power-bi/create-reports/desktop-r-visuals

1. Download R from here: https://mran.revolutionanalytics.com/download
   Download Python form here: https://www.python.org/downloads/
2. Install R
3. Enable R visuals in Power BI Desktop

After you've installed R, Power BI Desktop enables it automatically. To verify that Power BI Desktop has enabled R in the correct location, follow these steps:

- From the Power BI Desktop menu, select File > Options and settings > Options.

- On the left side of the Options page, under Global, select R scripting.

- Under R script options, verify that your local R installation is specified in Detected R home directories and that it properly reflects the local R installation you want Power BI Desktop to use. In the following image, the path to the local installation of R is C:\Program Files\R Open\R-3.4.4\.

<img src='https://user-images.githubusercontent.com/118057504/218461522-cc60f0a5-5e20-4495-86e2-1f57d7989163.png' width = 700 height = 700>
4. Create R visuals in Power BI Desktop
 - Select the R Visual icon in the Visualization pane to add an R visual.
 
<img src='https://user-images.githubusercontent.com/118057504/218461876-31b06501-fdf1-4aec-916d-4b0d582121f7.png' width = 350 height = 600>
 - In the Enable script visuals window that appears, select Enable.

<img src='https://user-images.githubusercontent.com/118057504/218462469-7abe17be-09c3-4211-8e2d-cce018b70d99.png' width = 350 height = 250>

When you add an R visual to a report, Power BI Desktop makes the following changes:

 - A placeholder R visual image appears on the report canvas.

 - The R script editor appears along the bottom of the center pane.
 
<img src='https://user-images.githubusercontent.com/118057504/218464279-b723de48-7bd5-42ab-8257-262ebbcac161.png' width = 700 height = 550>

5. In the Values section of the Visualization pane, drag fields from the Fields pane that you want to consume in your R script, just as you would with any other Power BI Desktop visual. Alternatively, you can also select the fields directly in the Fields pane.

Only fields that you've added to the Values section are available to your R script. You can add new fields or remove unneeded fields from the Values section while working on your R script in the R script editor. Power BI Desktop automatically detects which fields you've added or removed.



6. Now you can use the data you selected to create a plot:

 - As you select fields, the R script editor generates supporting R script binding code for those fields in the gray section along the top of the editor pane.
 - If you remove a field, the R script editor automatically removes the supporting code for that field.

In the example shown in the following image, two fields are selected: COGS and Description (items). As a result of those selections, the R script editor generates binding code, which is summarized as follows:
![image](https://user-images.githubusercontent.com/118057504/218466185-97b4f9d2-6548-480a-b7ee-a967923d5de0.png)
 In the example shown in the following image, three fields are selected: Horse Power, gear, and drat. As a result of those selections, the R script editor generates binding code, which is summarized as follows:

Create a dataframe called dataset, which is comprised of the different fields selected by the user.
 - The default aggregation is: do not summarize.
 - Similar to table visuals, fields are grouped and duplicate rows appear only once.
 
 The generated dataframe is named dataset, and you access selected columns by their respective names. For example, access the gear field by adding dataset$gear to your R script. For fields with spaces or special characters, use single quotes.


