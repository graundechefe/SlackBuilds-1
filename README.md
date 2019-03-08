# Slackers 

Slackware Current Repository by Conraid

## Repository for Slackware Current packages

Repository contains everything (SlackBuild script, slack-desc file, plus all possible patch) you'll need when you want to build the packages yourself.

To *make package from slackbuild* do

Download source code:

  source .info
  curl -JOL $DOWNLOAD

or

  wget [--no-check-certificate] [--content-disposition] $DOWNLOAD

wget, with some servers, doesn't set the correct filename

If exists FILENAME variable means that it contains the filename.

if exists DOWNLOAD__* extra variables, do also

 wget --no-check-certificate --content-disposition $DOWNLOAD [$DOWNLOAD_1] [$DOWNLOAD_2]

## Build

To build:

  sh .SlackBuild

This command builds a package which will be created in the same directory.

## Note

If you have any questions or requests, you can contact me at slackers.it (at) gmail (dot) com

All scrips are released under the GPL License.

## Links

Compiled packages are on http://slack.conraid.net/repository/ or https://sourceforge.net/projects/slackers/

## Support

Support me https://paypal.me/conraid
