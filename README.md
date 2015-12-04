# Transwhat #

This app is come from this project : https://github.com/stv0g/transwhat

It's a getway to whatsapp from jabber. It's very usefull for a user how use whatsapp and don't want to use the official client.

Warning : the source code of this app is free but the (whatsapp) network is not free.

## Install ##

With the install option from admin panel
- Find textbox tagged as Install from github
- Copy and paste: https://github.com/Josue-T/transwhat_ynh

or from command line `sudo yunohost app install https://github.com/Josue-T/transwhat_ynh`

## How to ##

Install app :-)

### Get whatsapp password ###

You can get whatsapp password on anywhere linux machin.

put this command :
```
wget https://github.com/tgalal/yowsup/archive/v2.4.zip
unzip yowsup-2.4.zip
cd yowsup-2.4
chmod u+x yowsup-cli
./yowsup-cli registration -p your-full-phone-number -C country-code -r sms
./yowsup-cli registration -p your-full-phone-number -C country-code -R no-of-code-recived-with-last-command
```
Your full phone number including the country code you defined in 'cc', without preceeding '+' or '00'
For country code. See http://www.ipipi.com/help/telephone-country-codes.htm.
Save the whatsapp code for next step


### Configure with pidgin ###

Enable discovery service plugin in pidgin.
Go do discovery service.
Search service name "TransWhat"
Clic on register
Put your phone number and password (got from last step).