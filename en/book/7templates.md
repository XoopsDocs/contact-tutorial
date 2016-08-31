# 7.0 Templates

This module uses template files (.tpl) containing Smarty (http://www.smarty.net) version 2 compatible tags.

There are five templates for administration:

|Template|Function|
|---|---|
|***contact_about.tpl***|to display the module About page.  The contents populated using this template is highly influenced by the XOOPS ModulesAdmin class.|
|***contact_contact.tpl*** |to display the contact (message) information. The template loops through each contact (message) and displays the relevant information based on module settings.|
|***contact_index.tpl*** |to display the administration Home page.  The contents populated using this template is highly influenced by the XOOPS ModulesAdmin class.|
|***contact_logs.tpl*** |to display the logs request form and the subsequent results.|
|***contact_tools.tpl*** | to display the prune page |

One (1) template for the “front side” form:

|Template|Function|
|---|---|
|***contact_index.tpl*** | displays the “Contact Us” form. The template may be edited through Admin -> System -> Templates -> Contact Us.|

For the blocks three templates existing:

|Template|Function|
|---|---|
|***block_contact_form.tpl**** | to display the contact form (without map) |
|***block_contact_map.tpl**** | to display the contact map (without form) |
|***block_contact_form_maps.tpl**** | to display the contact form with map |

All templates may be edited through Admin -> System -> Templates -> Contact Us.
