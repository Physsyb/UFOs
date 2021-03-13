# UFOs
# Project Overview
#### Dana’s webpage and dynamic table are working as intended, but she’d like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, you’ll add table filters for the city, state, country, and shape. The deliverables of this project are;
1. Deliverable 1: Filter UFO sightings on multiple criteria
2. Deliverable 2: A written report on the UFO analysis `(README.md)`

## Resources
Data Source: `data.js`, `ufo_starterCode.js` and `index.html`
Data Software/Tools: ES6+, Visual Studio Code 1.54.1, JavaScript

## Deliverable 1: Filter UFO sightings on multiple criteria 
> Using JavaScript and HTML, you’ll modify the code in your `index.html` file to create more table filters. In addition to the date filter you created in this module, you’ll add filters for the city, state, country, and shape. Using JavaScript, you’ll replace the `handleClick()` function in your `app.js` file with a new function that saves the element, value, and id of the filter that was changed. Then, you’ll create a new function to loop through the dataset and keep only the results that match the search criteria. The webpage will be updated with the search criteria after pressing "Enter".
### Requirements;
1. #### The list element that creates the button is removed, and there are five list elements for filtering in the `index.html` file.
![1](https://user-images.githubusercontent.com/76136277/111017472-c390d200-8381-11eb-9f5f-b691c6159ff7.PNG)
![2](https://user-images.githubusercontent.com/76136277/111017483-e1f6cd80-8381-11eb-8972-c9ef1fab5a1a.PNG)

2. #### The event listener is modified to detect changes to each filter in the `app.j` file.
![7](https://user-images.githubusercontent.com/76136277/111017707-128b3700-8383-11eb-8e86-59202ecefd06.PNG)
![3](https://user-images.githubusercontent.com/76136277/111017519-166a8980-8382-11eb-8eac-ebef270fd063.PNG)

3. #### The `updateFilters()` function saves the element, value, and the id of the filter that was changed.
![4](https://user-images.githubusercontent.com/76136277/111017582-6fd2b880-8382-11eb-8f78-519a3370d443.PNG)

4. #### The `filterTable()` function loops through all of the filters and keeps any data that matches the filter values.
![5](https://user-images.githubusercontent.com/76136277/111017619-ab6d8280-8382-11eb-992f-0afb1ab96cc0.PNG)

5. #### The webpage filters the table correctly based on user input.
![6](https://user-images.githubusercontent.com/76136277/111017674-e1126b80-8382-11eb-825a-2812790b81e4.PNG)

## Results
> Describe to Dana how someone might use the new webpage by walking her through the process of using the search criteria. Use images of your webpage during the filtering process to support your explanation.
#### The new webpage have 5 filters
1. #### To filter the table, use the filter button
![4](https://user-images.githubusercontent.com/76136277/111018878-b7107780-8389-11eb-9086-e26596d0b249.PNG)

2. #### Filter by date - filter data using a specific date(s) from the webpage
![2](https://user-images.githubusercontent.com/76136277/111018539-613ad000-8387-11eb-995e-ac451d7b4d13.PNG)

3. #### Filter by City - filter data by city or cities from the webpage
![1](https://user-images.githubusercontent.com/76136277/111018521-38b2d600-8387-11eb-98d3-ef1936b1ab46.PNG)

4. #### Filter by State - filter data by state(s) from the webpage
![9](https://user-images.githubusercontent.com/76136277/111018478-f8535800-8386-11eb-9714-a0816ff9b104.PNG)

5. #### Filter by Country - filter data by country or countries from the webpage. We have only one country in the data set "United States", so filtering by country is not applicable for this particular data.

6. #### Filter by Shape - filter out data by shape
![8](https://user-images.githubusercontent.com/76136277/111018434-c4783280-8386-11eb-90bd-7fd786003157.PNG)

7. #### Filter City by Shape - this will filter a city of your choice and with a specific shape , e.g, we will filter el cajon by light
![3](https://user-images.githubusercontent.com/76136277/111018735-972c8400-8388-11eb-97f5-e2146f7417bc.PNG)

## Summary
>  In a summary statement, describe one drawback of this new design and two recommendations for further development.
Recommendations
1. The `clear table button` needs to be added to the design ( although, i created the button), to clear all filters and reset it to its original. This will save the stress of refreshing the page before we start another search.
2. A filter search "Duration" added to the lists.
