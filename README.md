# HomeAssistant_SGNEARainAreas
Simple project to locally host SG NEA Rain Areas Webpage Card locally

![EndResult](https://user-images.githubusercontent.com/1997252/190862299-d5e0b68a-1a51-415a-bc2d-75f8c9b205bf.JPG)

## Installation

Add this integration to Home Assistant using HACS, or copy everything in `custom_components/nea_sg_weather` to your `custom_components` folder in your Home Assistant `config` folder. 

Follow these steps below:
- Copy the contents of the WWW folder to your www folder hosted in the configuration path (/config). The static files in www/ can be accessed by the following URL http://your.domain:8123/local/, for example index.html would be accessed as http://your.domain:8123/local/index.html. See here for more information: https://www.home-assistant.io/integrations/http/#hosting-files
- In the webpage lovelace card - note the following configuration
- - `type:` iframe
- - `url:` http://your.domain:8123/local/index.html
- - `aspect_ratio:` 80%
- - `title:` Singapore Rain Areas
