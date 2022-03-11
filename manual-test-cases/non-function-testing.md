Non - functional testing

1. Verify zoom in the map to a country, make sure that all cities in that country are shown.
	- Pre-conditions:
		- The Open Weather website is shown
	- Steps:
		- Zoom in the map to a country (ex: Viet Nam)
		- Observe the result
	- Expected Result:
		- Verify all cities in that country are shown on the map smoothly

2. Verify zoom out the map to a continent, make sure that all countries in that continent are shown.
	- Pre-conditions:
		- The Open Weather website is shown
	- Steps:
		- Zoom in the map to a continent (ex: Asia)
		- Observe the result
	- Expected Result:
		- Verify all countries in that continent are shown on the map smoothly
		
3. Search with block the access to my location (browser asking)
	- Steps:
		- Access into the page: https://openweathermap.org/
		- Browser asking > Click Block button
	- Expected Result:
		- Verify in browser config does not have the Open Weather page

4. Search with Allow the access to my location (browser asking)
	- Steps:
		- Access into the page: https://openweathermap.org/
		- Browser asking > Click Allow button
	- Expected Result:
		- Verify in browser config exists the Open Weather page