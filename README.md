# HomeAssistant_SGNEARainAreas
Simple project to locally host (on Home Assistant) and display the SG NEA Rain Areas Webpage Card in Lovelace

![EndResult](https://user-images.githubusercontent.com/1997252/190862299-d5e0b68a-1a51-415a-bc2d-75f8c9b205bf.JPG)

## Installation:

Follow these steps below:
- Copy the contents of the WWW folder to your www folder hosted in the configuration path (/config). The static files in www/ can be accessed by the following URL http://your.domain:8123/local/, for example index.html would be accessed as http://your.domain:8123/local/index.html. See here for more information: https://www.home-assistant.io/integrations/http/#hosting-files
- In the webpage lovelace card - note the following configuration
- - `type:` iframe
- - `url:` http://your.domain:8123/local/index.html
- - `aspect_ratio:` 80%
- - `title:` Singapore Rain Areas
