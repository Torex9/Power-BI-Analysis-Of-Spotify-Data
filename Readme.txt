Stages of dash board development

. Download dataset of choice
. Enrich Dataset with GenAI/ python
. Make Glassmorphism Background
. Load into PowerBI
. Create DAX
. Make HTML code for ALbum Art
. Make DENEB heatMap
. Make DENEB Donut




******* First Dashboard ********

Power BI Transforming steps
. Create new calculated column called date using  Date = DATE([released_year], [released_month],[released_day]
. Created a many to one relationship between spotify dataset table and date column
. Now i make two charts
  . number of streams per track
  . number of tracks per release date
. KPI cards on data of most played songs (green segment)
  . New measure to identify the most played stream amount
  . Using new measure create the two cards that will show the top streamed songs
. New DAX measure to calculate the sum of streams for the top songs where the streams is the max possible streams
. New DAX measure to calculate the average streams per year
. New DAX measure to calculate the percentage difference  between top songs streams and average streams per year
. New DAX measure that formats to include a up or down arrow depending on if it's positive or negative
. Two KPI cards
  . Average streams per year
  . Top songs versus average
. Using HTML to show the album cover art with rounded corners
. First create a new DAX measure to calculate the cover url the top songs actually has.
. show album art using html code
. New DAX measure to the count of occurrences of each unique value in the 'artist_name' column.
. Pie chart using the the DAX _Artist to show the amount of songs an artist has dropped so far
. New DAX measure to the count of occurrences of each unique value in the 'track_name' column.
. DENED heatmap gotten from github used to show the number of tracks that was release on which day and in which month
. Optimizing view
.Filter on the year that's above 2010




******* Second Dashboard ********
. Created new table and relationship between playlist and spotify data set
. charts to be created 
  . Using HTML to show the album cover art with rounded corners
  . show the chart of number of users playlist that a particular song is on different platforms





******* third Dashboard ********

New DAX measure to calculate how much energy there is on average in each song
DENEB unitchart using _to show the amount of energy in the songs
New DAX measure to calculate how much danceablity there is on average in each song
DENEB unitchart using _to show the danceability of the songs







