# itunesAnalyticsUsingPig
Problem Statement : To find still popular songs using Million Song Dataset(MSD) dataset in short time duration. </br>
Solution : Idea is to find most popular songs by calculating isolated songs. </br>
1. Read the input dataset using Load.</br>
2. Calculate songs without long localization.</br>
3. Pair all differnet set of songs and calcualte distance between their artist localization.</br>
4. Calculate average songs localization.</br>
5. Limit dataset from 4 to get the desired result set of popular songs.</br>
6. Store result for further visualiztion with Google Maps.</br>


