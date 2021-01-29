# Jaya Kumar Saga
## Chicken Biryani
Chicken biryani is mixed rice dish originating from the **Indian subcontinent**. It is made with Indian spices, rice, chicken,boiled eggs, vegitables. **Hyderabadi chicken biryani is an aromatic, mouth watering and authentic Indian dish** with succulent chicken in layers of fluffy rice, fragrant spices and fried onions. 

___

## To cook scrambled eggs
1. Crack 6 cold eggs into a deep saucepan.
2. Add the butter. For smaller batches, use a 2-to-1 eggs-to-butter ratio.
3. Put the pan on high heat.
4. Stir continuously with a rubber spatula—don't whisk—making sure to scrape the bottom of the pan.
5. After 30 seconds, take the pan off the heat. Keep stirring. After about 10 seconds, put back on the heat. Repeat for 3 minutes.
6. In the last minute, season the eggs lightly. For extra creamy texture, stir in 1 tsp of crème fraîche.
7. Plate and garnish with chopped chives.

___

## Ingredients for scrambled eggs 

- Eggs
- Butter
- Salt and pepper
- Chives
- Creme fraîche

Link to about me is [Aboutme](https://github.com/sagajayakumar/assignment2-saga/blob/main/AboutMe.md)

___

## Recommended places to visit

| Location                  | Hours to spend | Expenses |
| --------------------------| -------------- | ---------|
| Agra, India               |  4 Hours       |   $10    |
| Liberty Memorial Kansas   |  5 Hours       | $10 - 18 |
| Saint Louis Art Museum    |  5 Hours       |  Free    |
| St. louis gateway arch    |  5 Hours       |   $16    |

___

## Quotes about life

| Quote                                               |    Author         | 
| ----------------------------------------------------|-------------------| 
|  Forgive your enemies, but never forget their names | *John F. Kennedy* | 
|  The road to success is always under construction   |  *Lily Tomlin*    | 

___

## Code fencing 

> **Google Apps Script** is a rapid application development platform that makes it fast and easy to create business applications that integrate with Google Workspace. You write code in modern JavaScript and have access to built-in libraries for favorite Google Workspace applications like Gmail, Calendar, Drive, and more. There's nothing to install—we give you a code editor right in your browser, and your scripts run on Google's servers.

Sample code
```
function createAndSendDocument() {
  // Create a new Google Doc named 'Hello, world!'
  var doc = DocumentApp.create('Hello, world!');

  // Access the body of the document, then add a paragraph.
  doc.getBody().appendParagraph('This document was created by Google Apps Script.');

  // Get the URL of the document.
  var url = doc.getUrl();

  // Get the email address of the active user - that's you.
  var email = Session.getActiveUser().getEmail();

  // Get the name of the document to use as an email subject line.
  var subject = doc.getName();

  // Append a new string to the "url" variable to use as an email body.
  var body = 'Link to your doc: ' + url;

  // Send yourself an email with a link to the document.
  GmailApp.sendEmail(email, subject, body);
}

```
link to above source code [link](https://developers.google.com/apps-script/overview#your_first_script)