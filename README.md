# GTU Results Scraper

## Disclaimer
**Warning:** This code is intended for educational purposes only. Use it responsibly and in compliance with the terms of service of the targeted website. Unauthorized scraping of websites may violate their terms of service.

## Overview
This script is designed to scrape student results from the Gujarat Technological University (GTU) results website. It utilizes asynchronous JavaScript, FormData, and the Fetch API to automate the process of retrieving results for a range of enrollment numbers.

## Prerequisites
Before using this script, make sure to:

1. **Inspect Elements:**
   - Open the GTU results website (https://www.gturesults.in/) and inspect the relevant elements using browser developer tools.
   - Obtain the correct values for the `CodeNumberTextBox` (captcha code) and `__VIEWSTATE` parameters.

2. **Adjust Parameters:**
   - Set the correct `CodeNumberTextBox` value as the captcha code.
   - Update the `__VIEWSTATE` value with the one observed in the corresponding element.

## Usage
1. Clone or download the repository.
2. Open the GTU results website (https://www.gturesults.in/)
3. Open the browser console (usually by pressing `F12` or right-clicking on the page and selecting "Inspect," then navigating to the "Console" tab).
4. Run this script in console.
5. Call the `getResult` function with the desired enrollment range:

    ```javascript
    getResult(startEnrollment, endEnrollment);
    ```

   Example:

    ```javascript
    getResult(1001, 1010);
    ```

6. Review the console output for the scraped results.

## Important Notes
- Do not misuse this script for any unauthorized activities or violate the terms of service of the GTU results website.
- Regularly check and update the script if there are changes to the website's structure that may affect scraping.
