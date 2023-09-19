### Webscraping AED locations from the Norwegian Automated External Defibrillator Registry.
**[norskhjertestarterregister](https://www.norskhjertestarterregister.no)**

#### Methodology:

In order to capture the current AED locations coordinates hosted on the [norskhjertestarterregister](https://www.norskhjertestarterregister.no), we saved the site as a html file.
With beautiful soup we gain access to the html content, and use regular expression to find the "markers" which contain the Longitde and Latitude coordinates.
Eventually we export the the coordinates along with their attributes to a csv file with handling errors.
For easy visualization, prior to any manual preprocessing we host the coordinates on [google mymaps](https://www.google.com/maps/d/edit?mid=1y8HDK0ikYhxhw880fL8i5mM6k1FcZAA&usp=sharing)






