VALKYRIE
========

Valkyrie is a development toolkit for Drupal. It enables building and using a
local development environment built atop Vagrant and Aegir. Valkyrie supports
git- and Features-based workflows. These, in turn, enable teams to easily
collaborate and automate processes from development, through QA to deployment
and ongoing maintenance.

See INSTALLATION.md and USAGE.md for more detailed documentation.


FEATURES
--------

0. Fully Free Software stack.
1. Easy platform management.
2. Version-controlled site configuration.
3. Automatic local domain resolution.


Free Software
-------------

We are firm proponents of Free Software. Valkyrie only exists because of the
ongoing efforts of many other projects including: Aegir, Drupal, Drush, Git,
GNU/Linux, Puppet, Vagrant and VirtualBox. In addition, many plugins, modules,
extensions and libraries are developed and maintained by individual developers
and organizations of all sizes and types. We commend their admirable efforts.


Platform Management
-------------------

The codebase of a modern Drupal site is complex. Maintaining the security
of the codebase requires frequent updates. We are striving to fully automate
such updates. While we aren't there yet, we've made things pretty easy.


Site Configuration
------------------

Keeping site configuration and content separate can be a challenge. The
Features module goes a long way towards solving this issue, but it isn't always
obvious what to export to code. We've found that comparing database dumps is a
pretty good way to visualize these chnges, and so we've added some commands to
make this quick and easy.


Local Domain Resolution
-----------------------

When building websites locally, it's common practice to add development domains
to /etc/hosts. This is fine, as far as it goes. But when you can spin up new
platforms and sites as easily as Valkyrie allows, that extra step starts to be
a hassle. Through the magic of Avahi (on Linux systems) or a vagrant-dns plugin (on
Macs), every site provisioned on Valkyrie automatically resolves to a local alias.
