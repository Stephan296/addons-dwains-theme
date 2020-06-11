Ziggo Medianext box Add-on (rooms)
Created by Stephan
Installation
Copy the files page.yaml and button.yaml to your <config dir>/dwains-theme/addons/rooms/<your room>/nextmedia_box directory.
Configure your rooms.yaml file in <config dir>/dwains-theme/configs with config below.
Reload theme configuration at Theme settings.
Usage
To use this add-on in your Dwains Theme, add the following to your rooms.yaml file:

# Example rooms.yaml entry
  - name: Garage
    addons:
      - name: Camera
        path: 'dwains-theme/addons/rooms/<your room>/nextmedia_box/page.yaml'
        button_path: 'dwains-theme/addons/<your room>/nextmedia_box/button.yaml'
        data:
          entity: <your_medianext_box_entity>
