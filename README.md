<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# FootballManager AI

Final project for the Building AI course

## Summary

iFootballManager AI helps football managers and enthusiasts manage a team on a budget. It identifies undervalued players who outperform their market value and helps maximize team performance while staying within a budget. It provides recommendations tailored to teams that can't compete financially with giants like Manchester City.


## Background


*The challenge of scouting and identifying undervalued talent.

*The difficulty of optimizing player quality within budget constraints.

*Empowering smaller teams to compete strategically.

As an football enthusiast, I want to create a tool that levels the playing field for smaller clubs, encouraging smarter team-building strategies and making football management more accessible.


## How is it used?

Users input:

*Team budget

*Required player positions

*Existing squad composition

*Preferred playing style (e.g., high pressing, possession-based)

The AI outputs:

*A list of recommended players with high performance-to-value ratios.

*Analysis of how the recommended players fit into the team’s tactical needs.

*Predictions for potential team performance improvements.

This solution is ideal for:

*Football managers of smaller clubs.

*Football enthusiasts playing management simulation games.

*Real-life analysts looking for quick, data-driven insights.

Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?

![image](https://github.com/user-attachments/assets/7216fb29-b75b-4f9d-8f14-6fbab68acc0a)

Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods


*Player performance data from sources like FBref or Opta.

*Transfer market data from Transfermarkt.

*Machine learning techniques:

*Regression models to estimate player market value.

*Clustering to identify similar players.

*Optimization algorithms for squad building within a budget.


Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

*Account for subjective factors like player mentality or team chemistry.

*Handle real-time market fluctuations during transfer windows.

*Guarantee performance consistency due to injuries or external factors.

*The quality of predictions depends on the accuracy and availability of player data.

*Smaller datasets for lower leagues may result in less accurate recommendations.


## What next?

*Adding support for more leagues and competitions.

*Integrating real-time match performance updates.

*Developing a user-friendly app for fans and managers.

*Partnering with football analytics companies for broader adoption.

## Acknowledgments

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
