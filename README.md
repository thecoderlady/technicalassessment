<h2>BJAK Technical Assessment</h2>
<p> Please create 2 web pages with the following two endpoints:

First page: list of movie/tvshow titles
https://cdn-discover.hooq.tv/v1.2/discover/feed?region=ID&page=1&perPage=20

Extract rows with type "Multi-Title-Manual-Curation". Each row shows “row_name” on top followed by a list of horizontally scrollable images (use POSTER type). Put title below each image. 
The end result page is a list of rows with scrollable images with individual titles below.

Please handle pagination by changing the page=x in query when scrolling down.
On click of any image, call the following endpoint using the corresponding id: https://cdn-discover.hooq.tv/v1.2/discover/titles/:id for second page



Second page: the details of the movie
e.g. https://cdn-discover.hooq.tv/v1.2/discover/titles/e6464ce6-42c9-43ae-be23-0dd57f50add1
Show the details from the response, the layout is up to your creativity


If possible, please use react.js and pwa. You can deploy the pages anywhere, send us the url if available. Please send us the repository link and indicate in Readme file how to run locally. 
</p>
<h3>Live Demo Site</h3>

[https://www.thecoderlady.com/bjak/](https://www.thecoderlady.com/bjak/)

<h3>Instructions to run on local server</h3>
<p>As easy as 1, 2, 3...</p>
<ol>
<li>Clone git repository</li>
<li>Run 'npm install' to install dependencies</li>
<li>Run 'npm start' to run the app in development mode on http://localhost:3000</li>
  </ol>

<i>Please note that the page will reload if you modify the code while the command 'npm start' is running</i><br>

<h3>Tech Stack / Approach</h3>
<ul>
  <li>ReactJS </li>
    <li>PWA </li>
    <li>Create React App by FaceBook </li>
    <li>Material UI </li>
</ul>

