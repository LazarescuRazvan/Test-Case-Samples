# Test-Case-Samples

Below are some Test Case samples that I wrote while working on previous projects.

------

**Title:**

Test login with correct credentials

**Description:**

Check if the login works when a person uses a correct user/pass.

**Steps to reprodce:**

1. Go to [site](https://wordpress.com/log-in)
2. Add a correct user / pass
3. Press Login button

**Expected result:**

User should be able to login and is taken to his profile page.

**Test data:**

User: razvan2909 & Pass: Testare12

**Status:**

Passed

------

**Title:**

Test login with incorrect credentials

**Description:**

Check if the login works when a person uses a incorrect user/pass.

**Steps to reprodce:**

1. Go to [site](https://wordpress.com/log-in)
2. Add a incorrect user / pass
3. Press Login button

**Expected result:**

User should not be able to login and remain to the login page.

**Test data:**

User: razvan2909 & Pass: Testare12

**Status:**

Passed

------

**Title:**

Test login with modified URL

**Description:**
Check if the login works when a person modify the URL.

**Steps to reprodce:**

1. Go to [site](https://wordpress.com/log-in)
2. Modify the URL 
3. Add a incorrect user / pass
4. Press Login button

**Expected result:**

User should not be able to login and another page will be open with content "Page not found" and user still be able to search anything.

**Test data:**

User: razvan2909 & Pass: Testare12

**Status:**

Passed

------

**Title:**

Test login without credentials

**Description:**
Check if the login works when a person try to login without credentials.

**Steps to reprodce:**

1. Go to [site](https://wordpress.com/log-in)
2. Don't add credentials
3. Press Login button

**Expected result:**

User should not be able to login and page need to display a specific message like "Please enter a username or email address.".

**Test data:**

User: razvan2909 & Pass: Testare12

**Status:**

Passed

------


**Title:**

Test search engine with correct credentials

**Description:**
Check if the search engine works when a person try to search something with correct credentials.

**Steps to reprodce:**

1. Go to https://www.emag.ro/
2. Search something you need to buy
3. Press search button

**Expected result:**

Search engine should display your product correctly.

**Test data:**

Pantaloni lungi

**Status:**

Passed

