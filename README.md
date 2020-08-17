# Search Results

Use JavaScript and HTML to build a website based on these search results

## Installation

Run `npm install`

## Usage

In the terminal, run the following command:

`npm run start`

## Advanced Usage

- To check your JavaScript with ESlint, run `npm run eslint`

## Assignments

1. Use ES6 modules (import / export) to import the data from the file `js/MOCK_DATA.json` into your `js/app.js` file.

2. Combining HTML / CSS and JavaScript, write some code which will:

    - Read through the array you found in `js/MOCK_DATA.json`
    - Generate an HTML list which makes use of all the keys in the objects.
    
    > Hint: You may want to use the `<ul>` and `<li>` tags
    
    
3. Create an interface which allows you to:

    - Filtering and display the `balance` data, based on input values. For example, if you insert the values `0` and `100`, it should only show balances that are between $0 and $100
    
    > Hint: You will have to do multiple operations here
    
    > Hint: parseInt() on the original data (since it is a string)
    
    > Hint: You will have to use the Array filter method to filter your results
