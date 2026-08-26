# TC-LOGIN-001: Valid User Can Log In

## Objective

Verify that a user with valid credentials can successfully log in.

## Environment

- Website: SauceDemo
- Browser: Google Chrome
- Operating System: macOS Tahoe 26.5.2  
- Date Tested: 2026-08-25

## Preconditions

- SauceDemo is accessible
- The tester is on the login page.
- Valid sample credentials are available

## Test Data

- Username: `standard_user`
- Password: `secret_sauce`

## Test Steps

1. Enter the valid username.
2. Enter the valid password.
3. Select the **Login** button.

## Expected Result

The user successfully logs in and is redirected to the product inventory page.

## Actual Result

After entering a valid username and password and selecting the login button, the user was successfully redirected to the Products inventory page.

## Status

Pass
