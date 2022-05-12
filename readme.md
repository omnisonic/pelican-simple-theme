This is a starting point for creating custom themes for Pelican Static Webssite Generator.  This is theme is based on the simple theme built into pelican.  To install this theme add the ad this to you pelicanconf.py:

```
THEME = "<your_path_to_this_theme_on_your_machine>"


## 2022-11-05  Edit: Removed all id and class attributes , changed footer tag to div.  This is to make it easier to convert web designs into custom themes.  I also moved the feeds section from base.html head into its own template called feeds.html.  if you want it include it in the base.html just use {% include feeds.html %}
