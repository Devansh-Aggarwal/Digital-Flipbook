# Digital-Flipbook

This script connects an Arduino device to a Selenium-powered web browser, allowing physical hardware (like buttons or sensors connected to the Arduino) to control the navigation of an online flipping book.

<h3>libraries used:</h3>
<h4>i) serial:</h4> Used to handle serial communication between the computer and Arduino via a COM port (e.g., COM4). Part of the pyserial library.
<h4>ii) selenium:</h4> Web automation tool used to control the browser.
<h4>iii) By:</h4> For locating elements using strategies like ID, CSS selector, etc.
<h4>iv) WebDriverWait & EC:</h4> Used for implementing explicit waits to wait until elements are clickable or visible.
<h4>v) time:</h4> For hard delays (less ideal, but sometimes needed).
