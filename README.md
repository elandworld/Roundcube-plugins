# Roundcube-plugins
Roundcube plugins
{
    "name": "yourvendor/plugin-name",
    "license": "the license",
    "description": "tell the world what your plugin is good at",
    "type": "roundcube-plugin",
    "authors": [
        {
            "name": "<your-name>",
            "email": "<your-email>"
        }
    ],
    "repositories": [
        {
            "type": "composer",
            "url": "http://plugins.roundcube.net"
        }
    ]
    "require": {
        "roundcube/plugin-installer": "*"
    },
    "minimum-stability": "dev-master"
}
