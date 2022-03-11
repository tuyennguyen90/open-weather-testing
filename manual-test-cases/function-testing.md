Functional testing:
1. Verify the weather maps is loaded successfully without accepting cookies
	- Pre-conditions:
		- No accept cookies
	- Steps:
		- Access into the page: https://openweathermap.org/
		- Observe the list of countries are listed
		- Check cookies is save or not (Press F12 > Application)
	- Expected Result:
		- Verify the weather maps is loaded successfully without any errors.
		- Verify the Cookie value is returned to NO
		
2. Verify the weather maps is loaded successfully with accepting cookies
	- Pre-conditions:
		- Accept cookies
	- Steps:
		- Access into the page: https://openweathermap.org/
		- Observe the list of countries are listed
		- Check cookies is save or not (Press F12 > Application)
	- Expected Result:
		- Verify the weather maps is loaded successfully without any errors.
		- Verify the Cookie value is returned to YES
		
3. Verify showing weather summary correctly
	- Pre-conditions:
		- The Open Weather website is shown
	- Steps:
		- Click on a city name on the map
		- Observe the box is shown
	- Expected Result:
		- Verify the weather summary will shown on the maps.
		- Verify all informations are correctly
4. Search with the search field is blank
	- Pre-conditions:
		- The Open Weather website is shown
	- Steps:
		- Leave the search field in blank
		- Press Enter button
		- Observe the result
	- Expected Result:
		- Verify the result is returned: No data found
		
5. Search invalid data
	- Pre-conditions:
		- The Open Weather website is shown
	- Steps:
		- Input invalid city
		- Press Enter button
		- Observe the result
	- Expected Result:
		- Verify the result is returned: No data found
		
6. Search valid data by clicking on Search button
	- Pre-conditions:
		- The Open Weather website is shown
		- Searching with correct value
	- Steps:
		- Input valid city
		- Click on the Search button
		- Observe the result
	- Expected Result:
		- Verify the result is returned correctly

7. Search weather in your city - search short name
	- Pre-conditions:
		- The Open Weather website is shown
	- Steps:
		- Input short name (ex: HCM)
		- Press Enter button
		- Observe the result
	- Expected Result:
		- Verify the result is returned: No data found

8. Search weather in your city - search full english name
	- Pre-conditions:
		- The Open Weather website is shown
	- Steps:
		- Input full english name (ex: Ho Chi Minh)
		- Press Enter button
		- Observe the result
	- Expected Result:
		- Verify the results are shown in both English and Vietnamese name
		
		
9. Search weather in your city - search full vietnamese name (ex: Hồ Chí Minh)
	- Pre-conditions:
		- The Open Weather website is shown
	- Steps:
		- Input full vietnamese name (ex: Hồ Chí Minh)
		- Press Enter button
		- Observe the result
	- Expected Result:
		- Verify the results are shown in both English and Vietnamese name

10. Verify showing the weather details page correctly
	- Pre-conditions:
		- Search result is shown correctly.
	- Steps:
		- Click on the city name
		- Observe the page
	- Expected Result:
		- Verify the weather details show accurately.
			- City name
			- Date time
			- Temperature
11. Verify the page back to previous pages when clicking Back button on browser.
	- Pre-conditions:
		- User in the weather details page.
	- Steps:
		- Click on button Back on browser
		- Observe the page
	- Expected Result:
		- Verify the page back to previous pages (the weather city list)

12. Search weather in multi cities
	- Pre-conditions:
		- The Open Weather website is shown
	- Steps:
		- Input 2 cities (ex: Vung Tau, Ho Chi Minh)
		- Press Enter button
		- Observe the result
	- Expected Result:
		- Verify the results is shown the first input city
		


==========================================

