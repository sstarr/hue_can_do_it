## Hue Can Do It!

A simple Sinatra API which takes RGB hex values and passes them on to Hue lamps using the [Hue](https://github.com/soffes/hue) gem. The plan is to have a static HTML/JS front end which POSTs hex values to the API to change the colour of some Hue lights.

### TODO

- Add some validation for the POSTed data
- Figure out rate limiting
- Write the front end code
- Get this app running on a Raspberry Pi
