# DataCampSQL-When was the Golden Age of Video Games
In this project, we analyze video game critic and user scores as well as sales data for the top 400 video games released since 1977. Using joins and set theory we discover the best years for video games!

![VideoGamesProjectOverview](https://github.com/IoanaMRusu/DataCamp-SQL-Project-When-Was-the-Golden-Age-of-Video-Games/assets/144055123/dc6f6280-6fa9-4996-a62f-0ed0e57b3ee4)

# Data and Tables
*https://www.kaggle.com*

Our database contains two tables. We've limited each table to 400 rows for this project, but you can find the complete dataset with over 13,000 games on Kaggle.
<h3 id="game_sales"><code>game_sales</code></h3>
<table>
<thead>
<tr>
<th style="text-align:left;">column</th>
<th>type</th>
<th>meaning</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:left;"><code>game</code></td>
<td>varchar</td>
<td>Name of the video game</td>
</tr>
<tr>
<td style="text-align:left;"><code>platform</code></td>
<td>varchar</td>
<td>Gaming platform</td>
</tr>
<tr>
<td style="text-align:left;"><code>publisher</code></td>
<td>varchar</td>
<td>Game publisher</td>
</tr>
<tr>
<td style="text-align:left;"><code>developer</code></td>
<td>varchar</td>
<td>Game developer</td>
</tr>
<tr>
<td style="text-align:left;"><code>games_sold</code></td>
<td>float</td>
<td>Number of copies sold (millions)</td>
</tr>
<tr>
<td style="text-align:left;"><code>year</code></td>
<td>int</td>
<td>Release year</td>
</tr>
</tbody>
</table>
<h3 id="reviews"><code>reviews</code></h3>
<table>
<thead>
<tr>
<th style="text-align:left;">column</th>
<th>type</th>
<th>meaning</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:left;"><code>game</code></td>
<td>varchar</td>
<td>Name of the video game</td>
</tr>
<tr>
<td style="text-align:left;"><code>critic_score</code></td>
<td>float</td>
<td>Critic score according to Metacritic</td>
</tr>
<tr>
<td style="text-align:left;"><code>user_score</code></td>
<td>float</td>
<td>User score according to Metacritic</td>
</tr>
</tbody>
</table>

# Visualization
*https://public.tableau.com/app/profile/ioana.rusu2529/viz/GoldenAgeofVideoGamesDashboard/Dashboard*
