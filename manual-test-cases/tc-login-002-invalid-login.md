# TC-LOGIN-002: Invalid Password Prevents Login

## Objective

Verify that a user cannot log in with a valid username and an invalid password.

## Environment

- Website: SauceDemo
- Browser: Google Chrome
- Operating System: macOS Tahoe 26.5.2
- Date Tested: 2026-08-26

## Preconditions

- SauceDemo is accessible.
- The tester is on the login page.
- A valid sample username is available.

## Test Data

- Username: `standard_user`
- Password: `wrong_password`

## Test Steps

1. Enter the valid username.
2. Enter the invalid password.
3. Select the **Login** button.

## Expected Result

The user remains on the login page, access is denied, and an appropriate error message is displayed.

## Actual Result

Upon entering a valid username and an incorrect password and selecting the **Login** button, access was denied and the user remained on the login page. The following error message was displayed:

> "Epic sadface: Username and password do not match any user in this service"

## Status

Pass
