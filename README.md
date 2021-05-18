# plone-hotfixes

A list of needed hotfixes for each Plone version.

See the [list of available hotfixes](https://plone.org/security/hotfixes)

## usage

Extend the right version in your buildout config file:

    [buildout]

    extends =
        http://dist.plone.org/release/5.2.4/versions.cfg
        https://raw.githubusercontent.com/RedTurtle/plone-hotfixes/main/5.2.x.cfg

    ...

    eggs =
        ${hotfixes:eggs}
        ...
