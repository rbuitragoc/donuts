# donuts
Import following lines to your .rc file:

# This is to enable the sending of doughnuts alerts to predefined channel in VP slack!
# You have to run the alias from any command line and your message will appear on predefined slack channel.
export DONUTS_HOME=$HOME
# Default file place is $HOME. Create a file named .donuts there
# Make sure .donuts file has these contents: payload={"text": "your text here"}
alias donuts='curl --data @$DONUTS_HOME/.donuts https://hooks.slack.com/services/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'
