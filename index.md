## My little cheat sheet

Random things that I can use at a later date.

### Foreman

Switch to the US Locale when systemm was installed with something else.
1. Show current locale with ```locale -a```
2. If en_US.utf8 is missing from that list - Step 3
3. Use the following command ```dpkg-reconfigure locales``` to add ```en_US.utf8``` as the default system locale.
4. Restart postgreslsql with ```systemctl restart postgresql```
5. Restart the Foreman Installer with ```foreman-installer```
