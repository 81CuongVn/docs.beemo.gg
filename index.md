---
layout: default
title: Home
nav_order: 1
description: "Beemo is a free antispam Discord Bot that can stop userbot raids against your server."
permalink: /
---

# What is Beemo?
{: .fs-9 }

Beemo is a free antispam Discord Bot that can stop userbot raids against your server.

{: .fs-6 .fw-300 }

## Important Documentation Notes

The documentation for Beemo Max is limited, but there are some pages available. Since Beemo is designed to be configured in-Discord, all of the commands are generally well documented via their respective help menus. If you would like more information on Beemo Max (beyond the docs), [join the Discord](https://beemo.gg/Discord)!

## Adding Beemo & Setting Up 

Adding Beemo to your server is super simple!

1. [Invite Beemo to your server](https://beemo.gg/invite)! Beemo will not function if it is denied the `Ban Members` permission, but do note that all of the permissions being requested are there for the purposes of logging and antispam improvements.

2. Move Beemo's highest role above regular server members so that it can ban regular members.

3. (Optional) Set up an action log for antispam with `/banpool actionlog #channel`

And you should be done! Beemo is now automatically checking and banning any userbot raids that it detects. The algorithm is not configurable because it is designed to work dynamically, but in the future you will be able to disable/enable the antispam via a command.

### How To Contribute

Contributing to the documentation is relatively simple! At the bottom of every documentation page is an "`Edit on GitHub`" button; Simply press this and make your changes on the page it opens- and submit a pull request when you're done. The pull request will be reviewed, and if your changes are good, they will be added to the docs!

### Documentation Contributors

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"/></a>
  </li>
{% endfor %}
</ul>
