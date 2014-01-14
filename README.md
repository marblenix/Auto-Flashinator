Auto-Flashinator
================

Automatically download and install flash plugin for the Mozilla Firefox
addon "Flashinator". Useful for those who do not want to run the Adobe
flash plugin install.

Works on Mac OS running Firefox _only_.

To use:

1. Start firefox and download the addon "Flashinator"
⋅⋅* https://addons.mozilla.org/en-US/firefox/addon/flashlight-1/?src=api
2. Restart firefox.
⋅⋅* This must be done to create the initial flashinator folder.
3. Fully quite out of firefox. (⌘ - q, or Menu->Firefox->Quit)
4. Run flashinator from the command line.


<!-- language: lang-bsh -->
`################################################################################`
`# Original script by:                                                          #`
`# http://jacktourist.wordpress.com                                             #`
`# Editied [and perfected] by Me - [cm :at: marblenix.com]                      #`
`#                                                                              #`
`#  This script automatically downloads the latest Flash plug-in installer and  #`
`#  installs only the plugin.                                                   #`
`#                                                                              #`
`#  There is no icon in the PrefPane, No launch daemon, no updator,             #`
`#  no shovelware, only the Flash Player plugin inside firefox without putting  #`
`#  any of Adobe's files anywhere else on your machine.                         #`
`#  This script is capable of installing flash _without_ the admin password.    #`
`#                                                                              #`
`#  This script assumes you have the following installed on your machine:       #`
`#  1: Firefox, already run at least once to ensure a profile has been created. #`
`#  2: The Firefox plugin Flashlight:                                           #`
`#     https://addons.mozilla.org/en-US/firefox/addon/flashlight-1/             #`
`#  3: After installing Flashlight, be sure to restart firefox at least once    #`
`#     to ensure that the proper folders have been created.                     #`
`#                                                                              #`
`#  Running this script implies that you agree to all applicable terms and      #`
`#  conditions found on the Adobe website. I take no responsiblity for any      #`
`#  damage that may occur by running this script. I am in no way affiliated     #`
`#  with Adobe or it's products or partners. No ownership of any of the         #`
`#  afformentioned is implied.                                                  #`
`#                                                                              #`
`#  Distributed under GPLv2                                                     #`
`#  http://www.gnu.org/licenses/gpl-2.0.html                                    #`
`#                                                                              #`
`#                                                                              #`
`################################################################################`
