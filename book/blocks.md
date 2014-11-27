# 6.0 Blocks


As of version 1.82 there is a single block for this module.

**Statistics Block**

The statistics block shows the number of messages (contacts) that have replies, those that have no replies and the total number of messages. If Departments are enabled the block will also show the total number of messages for each department. Only departments with messages will be displayed.  

**NOTE:**  A default department (“Contact us”) is created if the module was initially configured without departments enabled, and then subsequently enabled. Messages sent before departments were enabled will be displayed in the Contact us “department”.

Templates
This module uses template files (.tpl) containing Smarty (http://www.smarty.net) version 2 compatible tags.
•	Four (4) templates for administration.
o	contact_about.tpl – to display the module About page.  The contents populated using this template is highly influenced by the XOOPS ModulesAdmin class.
o	contact_contact.tpl – to display the contact (message) information. The template loops through each contact (message) and displays the relevant information based on module settings.
o	contact_index.tpl – to display the administration Home page.  The contents populated using this template is highly influenced by the XOOPS ModulesAdmin class.
o	contact_logs.tpl – to display the logs request form and the subsequent results.
•	One (1) template for the “front side” form:
o	contact_index.tpl - displays the “Contact Us” form. The template may be edited through Admin -> System -> Templates -> Contact Us.
•	One (1) template for the “block”:
o	contact_block_stats.tpl - displays the “Contact Statistics” block. The template may be edited through Admin -> System -> Templates -> Contact Us.
