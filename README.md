# Tech Test - React Form

_Languages:_ 
<br>
- Também disponível em pt-BR aqui 👉 [Aqui](link)

## About
This project is about an tech test from an interview for junior/entry level react developer<br>
Another person has made this form, but still somehow bugged and incomplete, my task was fix it and push to production asap<br>

### Instructions

* You have an UNFINISHED login form
* Adding new HTML elements it not allowed
* It's not allowed to use refs<br>

### Tasks:

* The login button should call the function `login()`, imported on top of the file
* Disable the Login button if the e-mail field is empty OR the password has less than 6 characters
* Disable the Login button while you waiting for `login()` function
* Show an error message if login fails. The message should be clear at each new loggin attempt 
* Show an alert if the login has succeed (`alert()`). Investigate the `login()` function to understand how to succeed on the request<br>

### What i've done
Besides completing those tasks above using `useState`:
* I've used conditional rendering on the div that displays the error message
* Used `onKeyDown` to acess the Login button to UX purposes<br>

#### Special Thanks
I wanna thank to Fernandev, for making this challenge avaliable on his GitHub!<br>
https://github.com/nandokferrari/fernandev-react-challenge-02<br>
If you want to try this out, you can clone the repository above, or just clone this repo at the initial commit