# Aplos-Raisley---TSE-Assessment

Investigate and identify the root causes of:
- Button unresponsiveness issue
- Cross-browser styling inconsistencies


## Button unresponsiveness issue
- Button appeared unresponsive upon form submission, but checking the browser console and code itself presented no issue, just no alert notification for when form is submitted.<br>
![alt text](https://github.com/jshmartin/Aplos-Raisley---TSE-Assessment/blob/main/screenshots/Screenshot%202025-02-27%20103739.png)
- Added the alert to the function to match example. <br>
![alt text](https://github.com/jshmartin/Aplos-Raisley---TSE-Assessment/blob/main/screenshots/Screenshot%202025-02-27%20140535.png))
- Confirmed to match example.
![alt text](https://github.com/jshmartin/Aplos-Raisley---TSE-Assessment/blob/main/screenshots/Screenshot%202025-02-27%20113954.png)

## Cross-browser styling inconsistencies
- 2 issues were found here. <br>
![alt text](https://github.com/jshmartin/Aplos-Raisley---TSE-Assessment/blob/main/screenshots/Screenshot%202025-02-27%20113707.png)
  - First issue is the submit button text being set to the same bluebackground colour if the system theme is set to dark setting.
  - Fixed issue by changing text colour to white, but can also remove this section entirely as there's no use if the colours remain the same as the light setting. <br>
![alt text](https://github.com/jshmartin/Aplos-Raisley---TSE-Assessment/blob/main/screenshots/Screenshot%202025-02-27%20103658.png)<br>
![alt text](https://github.com/jshmartin/Aplos-Raisley---TSE-Assessment/blob/main/screenshots/Screenshot%202025-02-27%20140836.png)
  - Second issue is the red border around the text inputs.
  - Fixed issue by removing this block entirely. <br>
![alt text](https://github.com/jshmartin/Aplos-Raisley---TSE-Assessment/blob/main/screenshots/Screenshot%202025-02-27%20103755.png)
