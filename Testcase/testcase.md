# Test case
<details> <summary> Test Cases </summary>
  <p>
    
| Test Case ID# | Test case description | Test steps | Expected result | Prerequisites | Executed by | Pass/Fail |
| --- | --- | --- | --- | --- | --- | --- |
| API 1.2 | Authorised user enters invalid password , response code 401. | Invalid ceredentials  | response code is 401. | Postman for checking response code | Muhaimin |  |
| API 1.3 | Valid password and invalid username then response code 401. | Response code is 401 on invalid credentials. | response code is 401 | Postman for checking response code | Muhaimin |  |
| TC 1.1 | Default landing page should display the new article. | Run your project and it should land you on articles page without login | News article fetch from the API from general category. | https://newsapi.org/ and valid url| Preet |  |
| TC 1.2 |  Setting page should be displayed upon event occuring. | Click on the setting button/link | Should be able to connect user with the setting page. | Valid Url and browser |  |  |
| TC 1.3 |  Selection of the category of news article. | Click on the check box or link for selecting category. | User able to select aleast one category.| Valid Url and browser |  |  |
| TC 1.4 |  Selection of multiple category of news article. | Click on the check box or link for selecting category. | User able to select multiple category.| Valid Url and browser |  |  |
| TC 1.5 |  If no category is selected no functionality should be occuring for "ok or cancel" | Not selecting any category and click on "ok or cancel" button/link. | With no selection user is not enabled with "Ok /Cancel" buttons | Valid Url for setting pages|  |  |    
| TC 1.6 |  Functionality of ok and cacel button/link after they have selected category. | Select atleast one category or multiple and then press "ok or cancel" button/link. | After selecting category user should be able to click on "ok or cancel" button/link. | Valid Url for setting pages|  |  |    
