# NEFT Transfer – Paisa

A simple **HTML-based banking interface** that demonstrates the structure of a NEFT fund transfer page. This project focuses on basic HTML elements such as tables, forms, radio buttons, labels, dropdown menus, and structured content.

## Project Overview

**Paisa – NEFT Transfer** is a beginner-level HTML project designed to simulate the layout of an online banking NEFT transfer page.

The webpage allows users to view a source bank account, enter a transfer amount, select a transfer purpose, and choose a beneficiary account.

> **Note:** This is a static HTML practice project. It does not perform real banking transactions or connect to any banking system.

## Features

* NEFT Transfer page layout
* Source account information table
* Account selection using radio buttons
* Account number and branch details
* Available balance display
* Transfer amount input field
* Currency indication (INR)
* Beneficiary addition option
* Transfer purpose dropdown
* Beneficiary account selection
* Beneficiary details table
* Bank and branch information
* Transfer limit display

## Technologies Used

* HTML5
* Tables
* Forms
* Radio Buttons
* Dropdown / Select Menu
* Input Fields
* Labels
* Paragraphs
* Basic HTML Structure

## Project Structure

```text
PAISA-NEFT/
│
└── index.html
```

## Page Sections

### 1. NEFT Transfer

The page starts with a heading and description explaining that the user needs to select the account from which the funds will be transferred.

### 2. Source Account

The source account table displays:

* Account Number / Nickname
* Account Type
* Branch
* Available Balance

Example:

```text
Account No.       : 0000002031247XXXX
Account Type      : Savings Account
Branch            : Salem
Balance           : ₹150000
```

### 3. Transfer Amount

The user can enter the amount to be transferred through an input field.

The currency is specified as **INR**.

### 4. Transfer Purpose

A dropdown menu is provided for selecting the purpose of the transfer:

* Business
* Education
* Others

### 5. Beneficiary Selection

The page provides a beneficiary table containing:

* Account Number
* Beneficiary Name
* Branch
* Bank
* Transfer Limit

Radio buttons allow the user to select a beneficiary account.

## HTML Concepts Practiced

This project demonstrates the use of:

```html
<html>
<head>
<title>
<body>
<h1>
<p>
<table>
<tr>
<th>
<td>
<form>
<label>
<input>
<select>
<option>
<div>
```

## How to Run

1. Create a file named `index.html`.
2. Copy the provided HTML code into the file.
3. Save the file.
4. Open `index.html` in a web browser.

No additional software or dependencies are required.

## Future Improvements

The project can be enhanced by adding:

* CSS styling
* Responsive design
* Form validation
* Amount validation
* Required-field validation
* Beneficiary search
* Transfer confirmation page
* Transaction summary
* JavaScript functionality
* Mobile-friendly banking interface

## Important Note

This project is created **only for educational and HTML practice purposes**. The account numbers, beneficiary information, balances, and other banking details shown are sample data and should not be used for real financial transactions.

## Author

**Dinesh**

B.Sc. Information Technology
Full Stack Development Learner
