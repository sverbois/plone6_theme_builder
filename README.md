# Plone 6 Classic Theme Builder

Create a Plone 6 Classic theme for TTW upload.

- use Docker Plone image and Docker bind mounts
- no Plone product / no Python

## Start Plone

	docker-compose up

## Kitty Theme Development

    npm install
    npm watch
    code resources/theme/scss/theme.scss
    npm build

## Upload *kitty.zip* file in the Theming control panel

    https://www.my-plone-site.net/@@theming-controlpanel

