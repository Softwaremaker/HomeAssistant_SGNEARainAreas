# HomeAssistant_SGNEARainAreas
Simple project to locally host SG NEA Rain Areas Webpage Card locally

Copy the contents of the WWW folder to your www folder hosted in the configuration path (/config). The static files in www/ can be accessed by the following URL http://your.domain:8123/local/, for example index.html would be accessed as http://your.domain:8123/local/index.html. See here for more information: https://www.home-assistant.io/integrations/http/#hosting-files

This webpage card polls the weather.sg site for the latest rainclouds and rain areas every 5 minutes and overlays it on the base country graphic.

In your webpage card in lovelace, configure the following:

type: iframe

url: http://your.domain:8123/local/index.html

aspect_ratio: 80%

title: Singapore Rain Areas


