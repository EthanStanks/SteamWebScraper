<h1>Steam Web Scraper</h1>
<p>This is a Python script that enables scraping information from Steam store pages using a list of URLs. The script retrieves and saves the title, developer, publisher, tags, user review score, price, and URL of each game into a text file. The purpose of this tool is to gather game data for analysis or other purposes.</p>

<h3>Features</h3>
<ul>
<li>Concurrent scraping of multiple URLs using ThreadPoolExecutor.</li>
<li>Utilizes urllib.request and BeautifulSoup libraries for web scraping.</li>
<li>Retrieves game title, developer, publisher, tags, user review score, price, and URL.</li>
<li>Customizable number of concurrent requests.</li>
<li>Outputs the scraped data to a text file for further processing.</li>
</ul>
<h3>Usage</h3>
<ol>
<li>Create a text file named steam_urls.txt.</li>
<li>Add each Steam URL you want to scrape to a separate line in the steam_urls.txt file.</li>
<li>Run the steam_web_scraper.py script.</li>
<li>The script will scrape the provided URLs and save the extracted data into steam_games.txt.</li>
</ol>
<h3>Customization</h3>
<ul>
<li>Adjust the max_workers value in the ThreadPoolExecutor to control the number of concurrent requests made.</li>
<li>Change the output file name by modifying the value passed to open in the line: open('steam_games.txt', 'w', encoding='utf-8') as outfile. </li>
</ul>
<h5>Note: Please ensure that you use this script responsibly and in compliance with Steam's terms of service.</h5>
