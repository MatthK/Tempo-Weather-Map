# Tempo Weather Map

This is based on the <a href="https://github.com/leoneljdias/tempo">Tempo API</a> and takes the data provided and maps them to OpenStreetMaps.

## Setup

1. Simply copy the html and four PNG images to a local folder or your webserver. 
2. Adjust the "/tempo/" base API with the URL where your Tempo API data is available.
3. Adjust the center of the map and the initial zoom level to your preferences.

## Description

The page displays a (World) map and renders the maps/isolines provided by Tempo API onto the map. Four icons allow to select the desired overlay, and a slider allows for an easy selection of the date/time.

Small toasts provide information in case an overlay isn't available or the API shows an error.

The page was made by my local GPT-OSS 120b with plenty of iterations.

<img src="https://raw.githubusercontent.com/MatthK/Tempo-Weather-Map/refs/heads/main/map.png" alt="Sample map" width="1024" height="auto">