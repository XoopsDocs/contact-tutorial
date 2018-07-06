# Templates

This module uses template files \(.tpl\) containing Smarty \([http://www.smarty.net](http://www.smarty.net)\) version 2 compatible tags.

There are five templates for administration:

| Template | Function |
| --- | --- |
| _**contact\_about.tpl**_ | to display the module About page.  The contents populated using this template is highly influenced by the XOOPS ModulesAdmin class. |
| _**contact\_contact.tpl**_ | to display the contact \(message\) information. The template loops through each contact \(message\) and displays the relevant information based on module settings. |
| _**contact\_index.tpl**_ | to display the administration Home page.  The contents populated using this template is highly influenced by the XOOPS ModulesAdmin class. |
| _**contact\_logs.tpl**_ | to display the logs request form and the subsequent results. |
| _**contact\_tools.tpl**_ | to display the prune page |

One \(1\) template for the “front side” form:

| Template | Function |
| --- | --- |
| _**contact\_index.tpl**_ | displays the “Contact Us” form. The template may be edited through Admin -&gt; System -&gt; Templates -&gt; Contact Us. |

For the blocks three templates existing:

| Template | Function |
| --- | --- |
| _**block\_contact\_form.tpl\***_ | to display the contact form \(without map\) |
| _**block\_contact\_map.tpl\***_ | to display the contact map \(without form\) |
| _**block\_contact\_form\_maps.tpl\***_ | to display the contact form with map |

All templates may be edited through Admin -&gt; System -&gt; Templates -&gt; Contact Us.

