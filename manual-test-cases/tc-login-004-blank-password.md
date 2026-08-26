# TC-LOGIN-004: Blank Password Prevents Login

## Objective

Verify that a user cannot log in without entering a password.

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
- Password: `<empty>`

## Test Steps

1. Enter the valid username.
2. Leave the password field blank.
3. Select the **Login** button.

## Expected Result

The user remains on the login page, access is denied, and an appropriate error message is displayed.

## Actual Result

After entering a valid username, leaving the password field blank, and selecting the **Login** button, access was denied and the user remained on the login page. The following error message was displayed:
> Epic sadface: Password is required

## Status

Pass
