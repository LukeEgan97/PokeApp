# Poke App

**By Luke Egan**

This application was created using create-react-app.
[react-bootstrap](https://react-bootstrap.github.io/) was used as an additional component library.
[react-select](https://react-select.com/home) was used for the select component

# Start Up

Run Npm Start to run the application, listening on localhost:3000

## Thoughts for Future Improvements

- The filter region doesn't actually work. I've left in some pseudo code to show how this was meant to be implemented, but my original implementation caused the select to loop through every pokemon every single time a search was performed which was not ideal.
- The css needs considerable improvement, I used a mix of bootstrap grid and native CSS. I probably would have been better off sticking with just CSS Flex if I were to rewrite it.
- The form controls on the first page don't really have proper validation. I was torn between whether First and Last name needed any validation, but the telephone number should defintely checked. I was also considering splitting up address into multiple fields, but kept it to one to keep the state simpler
