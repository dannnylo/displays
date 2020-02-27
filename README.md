# CLI display manager

## How to use

 - `display notebook`: Enables only notebook display
 - `display hdmi`: Enables only hdmi display
 - `display both`: Enables notebook and hdmi displays
 - `display mirror`: Enables notebook and hdmi displays and mirrors them.

 ## How to install

 ```sh
 curl -L https://raw.githubusercontent.com/dannnylo/display/master/display -o /usr/local/bin/display
 chmod +x /usr/local/bin/display
 ```

If you need sudo:

 ```sh
 sudo curl -L https://raw.githubusercontent.com/dannnylo/display/master/display -o /usr/local/bin/display
 sudo chown $USER /usr/local/bin/display
 chmod +x /usr/local/bin/display
 ```
