# TC-LOGIN-003: Blank Username Prevents Login

## Objective

Verify that a user cannot log in without entering a username.

## Environment

- Website: SauceDemo
- Browser: Google Chrome
- Operating System: macOS Tahoe 26.5.2
- Date Tested: 2026-08-26

## Preconditions

- SauceDemo is accessible.
- The tester is on the login page.
- A valid sample password is available.

## Test Data

- Username: `<empty>`
- Password: `secret_sauce`

## Test Steps

1. Leave username field blank.
2. Enter the valid password.
3. Select the **Login** button.

## Expected Result

The user remains on the login page, access is denied, and an appropriate error message is displayed.

## Actual Result

After leaving the username field blank, entering a valid password, and selecting the **Login** button, access was denied and the user remained on the login page. The following error message was displayed:
> Epic sadface: Username is required

## Status

Pass
