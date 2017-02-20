# donuts
Import following lines to your .rc file:

``` bash
# This is to enable the sending of doughnuts alerts to predefined channel in VP slack!

# Default file place is $HOME. Create a file named .donuts there
# Make sure .donuts looks like the sample file in samples/.donuts
export DONUTS_HOME=$HOME

# You have to run the alias from any command line and your message will appear on predefined slack channel.
alias donuts='curl --data @$DONUTS_HOME/.donuts https://hooks.slack.com/services/T03EA2QBM/B47MFMTNG/Snyc0QhNN4BpynoV0vTCAp5
```

