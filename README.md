# MODULE 9: SURFS UP

## Overview of the statistical analysis:

In this exercise, I was helping a local surfshop owner prepare his business decisions better by analyzing seasonal weather data (June vs December) for the state of Hawaii, specifically the island of Oahu (where the surf shop is located). As one could very likely assume, surf shops have more business on nice sunny beach days in the summer with no rain forecasted- thats why this information is important to the shopkeeper. The shop owner needs to know if a surfshop is a sustainable business even accounting for seasonal temperature differences in the winter.

For deliverable one, my goal was to determine the summary statistics for the month of June on the island of Oahu- For deliverable two, I had the same process but for December instead of June.

I first wrote a query to filter the measuremnt table to retrieve temperatures for the month of June:

<img width="569" alt="1" src="https://user-images.githubusercontent.com/80979705/123770636-708f4c00-d898-11eb-833c-ca4fccb26d9e.PNG">

I then converted the June temperatures to a list:

<img width="327" alt="2" src="https://user-images.githubusercontent.com/80979705/123770643-72590f80-d898-11eb-9b75-c462de5aa964.PNG">

I soon had an easy to work with list of June temperatures on the island of Oahu:

<img width="83" alt="3" src="https://user-images.githubusercontent.com/80979705/123770654-7422d300-d898-11eb-9388-0e6c26128673.PNG">

June Summary Statistics:

<img width="70" alt="4" src="https://user-images.githubusercontent.com/80979705/123770666-75ec9680-d898-11eb-9608-e1ad39e7be4c.PNG">

I repeated the same steps for deliverable two, but for December instead of June. So here I queried to filter the table to only retrieve temperatures for December:

<img width="570" alt="5" src="https://user-images.githubusercontent.com/80979705/123770679-77b65a00-d898-11eb-8105-86bb8100800f.PNG">

I then converted the December temperatures to a list:

<img width="273" alt="6" src="https://user-images.githubusercontent.com/80979705/123770689-78e78700-d898-11eb-916e-cf5c3133f8a4.PNG">

Then I converted it to a dataframe:

<img width="357" alt="7" src="https://user-images.githubusercontent.com/80979705/123770701-7ab14a80-d898-11eb-96e3-3cea82ad23b7.PNG">

December Summary Statistics:

<img width="74" alt="8" src="https://user-images.githubusercontent.com/80979705/123770706-7be27780-d898-11eb-8797-3a131f9dcd4a.PNG">


## Results:

June and December Summary Statistics:

<img width="70" alt="4" src="https://user-images.githubusercontent.com/80979705/123770666-75ec9680-d898-11eb-9608-e1ad39e7be4c.PNG">
<img width="74" alt="8" src="https://user-images.githubusercontent.com/80979705/123770706-7be27780-d898-11eb-8797-3a131f9dcd4a.PNG">

From looking at this, we can see that:

- Temperatures on Oahu stay stable all year round, with the average June temperature being 75 degrees F, and the average December temperature being around 71 Degrees F. 
- This is only a 4 degree difference in average temperatures between June and May.
- Both June and May receive high temperature days in the mid 80 degree F range. (83 degrees F for DEC; 85 degrees F for June).
- Temperatures are consistent all year long, although December can have the occasional day in mid 60 degrees F when it may be too cold for a beach day (or surfing without a wetsuit). But even 64 degrees F is relatively warm for a minimum temperature in the wintertime.

## Summary:

The temperature summary statistics suggest Oahu's temperatures stay pretty stable and relatively warm year round, as a result of this, I would label the surfshop entrepreneurial idea by W.avy as financially sound and sustainable.

For deliverable three I was asked to pick two more queries at my own descretion and show the results. 

As rainfall is just as much of a determinant as temperature in deciding whether or not its a beach day for most holidaymakers and locals, I thought finding the data for the amount of rainfall for both June and December could be useful to W.avy in determining whether the surf shop will maintain business success during all seasons.

Here are the summary statistics for June, and December, respectively.

JUNE:

<img width="73" alt="9" src="https://user-images.githubusercontent.com/80979705/123784095-1648b800-d8a5-11eb-9d65-038ee9f09897.PNG">

DECEMBER:

<img width="76" alt="10" src="https://user-images.githubusercontent.com/80979705/123784112-1b0d6c00-d8a5-11eb-8e1b-01abfd8a18a5.PNG">

It likely still makes sense to open the business as neither month has too much rain, although you can expect slightly higher average rainfall in the month of June compared to September.




