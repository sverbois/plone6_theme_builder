# Plone 6 Classic Theme Builder

Create a Plone 6 Classic theme for TTW upload.

- use Docker Plone image and Docker bind mounts
- no Plone product / no Python

## Start Plone

	docker-compose up

## Kitty Theme Development

    npm install
    npm watch
    npm build

## Zip Kitty Theme

    cd resources/theme
    zip -r kitty.zip kitty

## Upload Zipe file in the Theming control panel

    http://localhost:8080/Plone/@@theming-controlpanel

