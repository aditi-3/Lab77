# Explore
## 1. Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.
    Answer: 1. Within a Github action that runs whenever code is pushed
    The best way to automate testing would be to have it automatically run when a code is pushed. 
    This way, we don't have to manually check our code and it saves a lot of work, feeding into the "automated" portion of the description.

## 2. Would you use an end to end test to check if a function is returning the correct output? (yes/no)
    No. End to end testing is more about testing user actions. Its purpose is not to test individual functions but to test how users interact with the web page as whole.

# Expose
## 1. What is the difference between navigation and snapshot mode?
    Navigation mode analyzes the page right after it is loaded but snapshot analyzes the page at the current state.
    Navigation can provide the overall performance metric, but it can't update the analysis after making changes whilead snapshot can find accessibility issues.
## 2. Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.
    The accessibility can be improved since it is at 90% right now, for example, <html> element does not have a [lang] attribute. SEO (Document does not have a meta description) and best practices (No `<meta name="viewport">` tag found) can also be optimized. Property size image is big and can save up to 718 KB when optimized. 


