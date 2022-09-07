# SharePoint Column Name
Type of choice column name with very-long (long) character will causing an issue in PowerApps. Here is how to handle!

Well, here is not the expected result;
![Issue1](https://user-images.githubusercontent.com/39186543/188778830-425c6e3e-b575-482f-90ed-f36ac71d682c.png)

Here is how to solve:
1. Open PowerApps
2. After added column from SharePoint and Play the App, the choice value not return as expected value
3. Select DataCardValue of the column and go to **Items** property, by default it will look like this below image;
![Issue2](https://user-images.githubusercontent.com/39186543/188779420-8b8396a5-9b8e-4b67-b395-bbffac444564.png)
4. Now, just remove (the weird name) after (.) with a proper name;
![Issue3](https://user-images.githubusercontent.com/39186543/188779591-14678e9a-6f6e-4ff0-826f-354f99fbbd8f.png)
5. Done! Play the App, should be look like below;
![Issue4](https://user-images.githubusercontent.com/39186543/188779684-93a480ab-5ec3-4a9b-8313-7fd52433cef8.png)

_Note: Sometimes before we modify the **Items** property it return blank or has value like item1, item2, item3, etc._
