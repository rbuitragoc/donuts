# donuts

Makes a nice appearance in a slack channel, posting an informative text. Inspired by the shoutout for donuts on wednesdays. It's basically what it does for the moment.

### Setup
Import following lines to your .rc file:

``` bash
# This is to enable the sending of doughnuts alerts to predefined channel in VP slack!

# Default file place is $HOME. Create a file named .donuts there
# Make sure .donuts looks like the sample file in samples/.donuts
# NOTE: Edit values for "text", channel", "username" and "icon_emoji"
export DONUTS_HOME=$HOME

# You have to run the alias from any command line and your message will appear on predefined slack channel.
# Pay heed to the proper value for YOUR_URL. Ask your local slack donut embassador.
alias donuts='curl --data @$DONUTS_HOME/.donuts YOUR_URL'
```

