Name: Yifei Du



## 1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

#### Within a Github action that runs whenever code is pushed

I believe this would be the best way to fit the automated tests since if it's only local, then there is a chance somebody may forget to test them before pushing their code and running it after development is completed makes it very difficult to know what exactly is causing the problem, making it take much longer to debug than necessary.

## 2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)

No, I would use a unit test for that instead of E2E. Since you may not be able to notice see the output of certain functions in E2E testing.


## 3) What is the difference between navigation and snapshot mode?

Navigation mode refreshes the webpage and tracks its loading speed, and overall performance metrics, but cannot interact with the page itself. Snapshot mode analyzes the page without reloading, freezes the current DOM, and finds any accesibility and code structure issues that may appear with user interactions. 

## 4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.

We can include a meta descriptions in search results to concisely summarize page content. 

Adding a [lang] attribute to the html elements so that we can make sure the language is correct for accessibility issues. 

Lastly, we can optimize the viewport better since currently tap interactions on mobile can be delayed by up to 300ms.