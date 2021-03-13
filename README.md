# UFOs

## Project Overview
This project focuses on building a dynamic webpage that accepts user inputs and adjusts accordingly to display information about UFO sightings.
In order to perform their analysis, users will be able to filter the UFO sightings table based on multiple criteria such as the event date, city, state, country and shape.

## Resources
Software: HTML/CSS, JavaScript, Visual Studio Code 1.49.1, BootStrap 4.0.0

## Results
### Search Criteria Procedure
Index page
This is the initial page. The user can re-initialize the page by clicking on the navbar at the top.
![1](https://user-images.githubusercontent.com/64053195/111052337-e4136780-8427-11eb-9b22-450571eeb116.png)

Filtering by event date
The user enters the desired date, the change is detected and the table is updated accordingly.
![2](https://user-images.githubusercontent.com/64053195/111052346-f7263780-8427-11eb-8d8d-6a427cf9fc5a.png)

Filtering by city
The user enters the desired city, the change is detected and the table is updated accordingly.
![3](https://user-images.githubusercontent.com/64053195/111052356-0efdbb80-8428-11eb-8bde-2adeaa5e4323.png)

Filtering by country
The user enters the desired country, the change is detected and the table is updated accordingly.
![4](https://user-images.githubusercontent.com/64053195/111052367-2046c800-8428-11eb-8904-72e259351ce1.png)

Filtering by state and shape
The user enters the desired state and shape observed, the changes are detected and the table is updated accordingly.
![5](https://user-images.githubusercontent.com/64053195/111052377-32286b00-8428-11eb-8fc1-515564c3b2b7.png)

All filter parameters can be entered simultaneously.

## Summary
One drawback of this design is the difficulty for the user to know what parameter to use for the filtering. For example to pick a city, the user would have to go through the table a find the city desired for the analysis.
A way to address this would be to present drop-down lists including all filter values in place of the input fields.
Each list would need to update after a parameter is selected in any filter.
Including a button to clear the filters is also needed. The button would be located below the last filter.
