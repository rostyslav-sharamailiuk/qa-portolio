# Login Test Cases - PrestaShop Demo

| ID    | Test Case                    | Steps                                                                                  | Expected                                           | Status |
|-------|------------------------------|----------------------------------------------------------------------------------------|----------------------------------------------------|--------|
| TC001 | Login with valid credentials | 1. Go to login page. 2. Enter valid email/password. 3. Click login                     | User redirected to main page with logged in status | Pass   |
| TC002 | Login with invalid password  | 1. Go to login page. 2. Enter valid email and wrong password. 3. Click login           | Error: "Authentication error" appears              | Pass   |
| TC003 | Register new user            | 1. Go to login page. 2. Choose "Create account" option. 3. Fill in the form. 4. Submit | Account created, user logged in                    | Pass   |
|       |                              |                                                                                        |                                                    |        |
