# <span style="color:tan"> **Module 11 Homework: Web-Design-Challenge**</span>
## <span style="color:bisque">Chris Gruenhagen 8Dec2022</span>

Module 11 Homework saved in the Web-Design-Challenge repository.

Latitude Study website  <a href = 'https://christygruen.github.io/Web-Design-Challenge/'> https://christygruen.github.io/Web-Design-Challenge/</a>

### **Attribution**
‘Weather data provided by OpenWeather’
https://openweathermap.org/

Powered by https://www.geoapify.com/ Geoapify

Powered by https://www.openstreetmap.org/copyright © OpenStreetMap contributors

Data analyses obtained from https://github.com/ChristyGruen/python-api-challenge

---

# &#x1F31E; &#x26C5; &#x2601; &#x1F327; &#x1F308; &#x1F327; &#x2601; &#x26C5; &#x1F31E;

     emoji & format references:
        https://emojipedia.org
        https://commons.wikimedia.org/wiki/Emoji/Table
        https://www.markdownguide.org/basic-syntax/

        
***See below for original homework instructions***
# <span style="color:tan"> Module 11 Web-Design-Challenge </span>
Due Dec 14, 2022 by 11:59pm 

Points 100 

Submitting a text entry box or a website url
_________________________________________________________
## <span style="color:red"> **Background**  </span>

Data becomes more powerful when you share it with others! That’s because people can use your data only if they can access it. So, you’ll use HTML and CSS to create a dashboard featuring the Latitude vs. X analysis of weather.

##  <span style="color:orange"> **Before You Begin** </span>

1. Create a new repository for this project called Web-Design-Challenge. Do not add this assignment to an existing repository.

2. Clone the new repository to your computer.

3. Inside your local Git repository, add the following:

    * Three folders named assets, Resources and visualizations.

        #### **NOTE**

        You’ll later add your CSS and image files to the assets folder. You’ll add the CSV file containing the data for your website to the Resources folder. You’ll add the HTML pages that display your visualizations to the visualizations folder.

    * An index.html file in the main folder.

        #### **NOTE**
        You’ll later edit this file to be the landing page that a user first encounters when reviewing your submission.

    * Inside the assets folder, two more folders named css and images.

        #### **NOTE**
        You’ll use these folders to store your CSS assets and image assets, respectively.*

4. Push the changes from Steps 1–3 to GitHub.

5. Deploy your index.html file to GitHub Pages.

    #### **NOTE**
    By deploying this empty HTML file to GitHub Pages now, you’ll find that it automatically refreshes as you build your pages. You can then review the updates with each push that you make to GitHub.

##  <span style="color:yellow"> **Files** </span>

Download the following files to help you get started:

<a href = "https://static.bc-edx.com/data/dl-1-1/m11/lms/starter/Starter_Code.zip" target = "_blank"> Module 11 Challenge files </a>


##  <span style="color:green">  **Instructions** </span>
Create a website by using either the visualizations that you created for your Python-APIs Challenge or the weather data and images that are provided for this Challenge. To do so, use the considerations and website requirements that the following subsections describe. Also, ensure that your repository has regular commits and a descriptive README.md file.

#### NOTE
    As you build this dashboard, you'll create a page for each plot and a way to navigate among these pages. These pages should contain the visualizations and the descriptions. You’ll also create two more pages. One will be a landing page that provides a comparison of all the plots. The other will be a page that presents the data used to build the plots.

###  <span style="color:bisque">  **Considerations** </span>
* Be aware that you must use Bootstrap. This includes using the Bootstrap navbar component for the header on every page, the Bootstrap grid for responsiveness on the comparison page, and the Bootstrap table component for the data page.

* Be aware that you must deploy your website to GitHub Pages, and that as a result, the website must work at a live, publicly accessible URL.

* Make sure to use a CSS media query that uses Bootstrap and/or @media for the navigation bar.

* Make sure that your website works at all window widths.

* Feel free to take some liberties with the visual aspects, but keep the core functionality the same as the instructions describe. (For example, keep the comparison visualizations on the comparison page.)

###  <span style="color:bisque">  **Website Requirements** </span>
The overall requirements for your website are as follows:

#### NOTE
    For reference, review the following Screenshots section.
* Your website must consist of seven pages.
* At the top of every page, your website must have a navigation bar.
* Your website must be deployed to GitHub Pages.

Next, we’ll describe these requirements in detail.

Your website must consist of seven pages as follows:

* A landing page that contains the following elements:

    * An explanation of the project.

    * A link to each visualization page. For these, a sidebar should contain a preview image of each visualization. Clicking an image should take the user to that visualization.

* Four visualization pages, stored in the visualizations folder, each with the following elements:

    * A descriptive title and a heading tag.

   * The visualization for the selected comparison (latitude vs. max temperature, latitude vs. humidity, latitude vs. cloudiness, or latitude vs. wind speed). The images that these pages display should be stored in the assets/images folder.

   * A paragraph describing the visualization and its significance.

* A comparisons page that does the following:

   * Contains all the visualizations on the same page so that people can easily compare them.

   * Uses a Bootstrap grid for the visualizations. This grid must contain two visualizations across a medium or large screen and one visualization across an extra-small or small screen.

* A data page that displays a responsive table containing the data that the visualizations use, as follows:

   * The table must be a Bootstrap table component.

        #### HINT
        For more information about how to use responsive tables, see <a href = 
        'https://getbootstrap.com/docs/4.3/content/tables/#responsive-tables'> Responsive tables</a> in the Bootstrap documentation.

   * The data must come from either exporting or converting the CSV file to HTML. To do so, try using a tool that you already know: Pandas. Pandas has a to_html method that generates an HTML table from a Pandas DataFrame. To learn more, see pandas.DataFrame.to_html Links to an external site.in the official Pandas documentation.

        **Note:** Whether you use your own CSV file or the one provided, you should also upload the CSV file you used with your submission. This way your data page can be compared with the CSV file by your grader.

At the top of every page, your website must have a navigation bar that does the following:

* Contains the name of the site on the left side of the navigation bar, allowing users to return to the landing page from any page.

* Contains a drop-down menu, named Plots, on the right side of the navigation bar that contains a link to each visualization page.

* Provides two more text links on the right side: Comparisons, which links to the comparisons page, and Data, which links to the data page.

* Is responsive (via media queries). Note that the navigation bar must resemble the one in the screenshots in the Navigation Bar section. In particular, notice the background color change.

Your website must be deployed to GitHub Pages:

* As a result, the website must work at a live, publicly accessible URL. Save this URL for your later submission.

##  <span style="color:blue"> **Bonus** </span>

For extra challenges (but no additional points), you may wish to try any or all of the following:

* Use the same requirements but a different dataset to make it your own.

* Use the same requirements, but add a Bootstrap theme to customize your website. To do so, you can use a tool like Bootswatch Links to an external site..

* Add extra visualizations.

* Use meaningful glyphicons next to the links in the navigation bar.

* On every visualization page that has an active state, add visualization navigation, as shown in the following images in the Screenshots section.

##  <span style="color:indigo"> **Screenshots** </span>
This section contains screenshots of each page, at various screen widths, that you must create. Keep in mind that these screenshots are intended as a guide. You can meet the requirements without exactly matching your pages to the screenshots.

### **Landing Page**
![Alt text](https://static.bc-edx.com/data/dl-1-1/m11/lms/img/landingResize.jpg "Landing Lg")

![Alt text](https://static.bc-edx.com/data/dl-1-1/m11/lms/img/landing-sm.jpg "Landing Sm")

### **Comparisons Page**
![Alt text](https://static.bc-edx.com/data/dl-1-1/m11/lms/img/comparison-lg.jpg "Comparisons Lg")

![Alt text](https://static.bc-edx.com/data/dl-1-1/m11/lms/img/comparison-sm.jpg "Comparisons Sm")

### **Data Page**
![Alt text](https://static.bc-edx.com/data/dl-1-1/m11/lms/img/data-lg.jpg "Data Lg")

![Alt text](https://static.bc-edx.com/data/dl-1-1/m11/lms/img/data-sm.jpg "Data Sm")

### **Visualization Pages**
![Alt text](https://static.bc-edx.com/data/dl-1-1/m11/lms/img/visualize-lg.jpg "Visualization Lg")

![Alt text](https://static.bc-edx.com/data/dl-1-1/m11/lms/img/visualize-sm.jpg "Visualization Sm")

### **Navigation Bar**
![Alt text](https://static.bc-edx.com/data/dl-1-1/m11/lms/img/nav-lg.jpg "NavBar Lg")

![Alt text](https://static.bc-edx.com/data/dl-1-1/m11/lms/img/nav-sm.jpg"NavBar Sm")

##  <span style="color:violet"> **Requirements** </span>
### ***Landing Page (10 points)***
**To receive all points, your landing page must have all of the following**

* A sidebar section with images of each plot that all load (2 points)
* Sidebar images link to their respective pages (2 points)
* Bootstrap grid used correctly to separate sections (2 points)
* Page is responsive when the window is reduced in size (2 points)
* Includes a couple of paragraphs of an overview for this project (2 points)

***Visualization Pages (40 points)***

**To receive all points, you must have a visualization page for each of the following**
* latitude vs. max temperature (10 points)
* latitude vs. humidity (10 points)
* latitude vs. cloudiness (10 points)
* latitude vs. wind speed (10 points)
The point breakdown for each page follows below.

**To receive all points, every visualization page must have all of the following**

* A descriptive title and a heading tag (1 point per page)
* A section with the regular-sized visualization image, with the image correctly loading (1 point per page)
* A sidebar section that displays a smaller version of all the visualization images (2 points per page)
* All sidebar visualization images link to their respective pages (1 point per page)
* Includes a paragraph of text describing the plot (1 point per page)
* Uses Bootstrap grid to separate sections (2 points per page)
* Page is responsive when the window is reduced in size (2 points per page)

***Comparison Page (6 points)***

**To receive all points, your comparison page must have all of the following**

* All Images load (1 point)
* All labels are correct (1 point)
* Images are responsive (2x2 on large screens and 4x1 on small screens) (3 points)
* All images link to their respective visualization page (1 point)

***Data Page (8 points)***

**To receive all points, your data page must have all of the following**

* No rows missing from the CSV data file (2 points)
* The table uses Bootstrap table class(es) (1 point)
* The table is responsive and stays inside a container when the page is reduced in size (2 points)
* The table has all 10 columns (The following columns must be included but may be in a different order or named differently: City_ID, City, Country, Date, Latitude, Longitude, Cloudiness, Humidity, Max Temperature, Wind Speed) (2 points)
* The CSV data file used to produce the data page is included in the submission on GitHub in a Resources folder (1 point)

***Navbar (16 points)***

**To receive all points, your navbar must have all of the following**

* The name of the site is on the left side of the navigation bar and links to the landing page (1 point)
* All links work and direct to the correct page (2 points)
* Navbar has a working dropdown with links to plot pages (4 points)
* Navbar is on every page (3 points)
* Navbar collapses when the window is reduced in size and button works to make nav reappear (4 points)
* Uses Bootstrap navbar class (2 points)

***File Organization and Structure (10 points)***

**To receive all points, your files must include the following structure**

* Visualization pages (cloudiness.html, humidity.html, temp.html, and wind.html) are stored within a visualizations folder (2 points)
* An assets folder contains the css and images folders (2 points)
* CSS file(s) are stored within the css folder (2 point)
* Images are stored within the images folder (2 points)
* index.html, comparison.html, and data.html are stored in the parent directory (2 points)

***Deployment and Submission (10 points)***

**To receive all points, you must**

* Submit a link to a GitHub repository that’s cloned to your local machine and contains your files (2 points)
* Use the command line to add your files to the repository (2 points)
* Include appropriate commit messages in your files (2 points)
* Deploy the website to GitHub Pages (4 points)

## <span style="color:pink"> **References**  </span>
OpenWeatherMap.org. (2012). Сurrent weather and forecast. Retrieved from <a href = 'https://openweathermap.org/'>https://openweathermap.org/</a> 

© 2023 edX Boot Camps LLC






