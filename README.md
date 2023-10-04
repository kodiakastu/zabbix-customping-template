# Zabbix: Custom ping

This template allows you to quickly customise ping parameters with macros per hosts. The majority of macro are set to the default value with a description.

## ⚙️ Installation

1. Select a branch according to your Zabbix version and download the xml.
2. Import *zbx_customping_template.xml* to Zabbix (Configuration -> Templates -> Import)
3. Add the template *ICMP Custom Ping* to your host and configure
4. Customize the macros to your needs!

## 🏷️ Features
- ✔️ Customise ping target for loss and reponse time
- ✔️ Customise all parameters for Ping
- ✔️ All macros are set with the usual default value and description
- 🔶 No Linked template!

## 📣 Triggers
Items witch checks are enable by default. Those with Xs are disabled by default. You can customise your triggers to your needs per network interfaces.

From this template:
- ✅ Unavailable by ping
- ❎ High response time
- ❎ High ping loss

## Issues
None so far! Let me know if you found one!


## License
[MIT](https://choosealicense.com/licenses/mit/)

