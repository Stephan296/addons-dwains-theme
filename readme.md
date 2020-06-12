# Ziggo Medianext box Add-on (rooms)
##### Created by Stephan

### Installation
- Copy the files page.yaml and button.yaml to your <config dir>/dwains-theme/addons/rooms/<your room>/nextmedia_box directory.
- Configure your rooms.yaml file in <config dir>/dwains-theme/configs with config below.
- Reload theme configuration at Theme settings.
### Usage
To use this add-on in your Dwains Theme, add the following to your rooms.yaml file:
```yaml
# Example rooms.yaml entry
  - name: Ziggo Medianext box
    addons:
      - name: Ziggo Medianext box
        path: 'dwains-theme/addons/rooms/<your room>/nextmedia_box/page.yaml'
        button_path: 'dwains-theme/addons/<your room>/nextmedia_box/button.yaml'
        data:
          entity: <your_medianext_box_entity>
  ```
### Setup Dutch Tv-Guide:
When you scroll down to the bottom of the guide page you can click at "instellingen". At the next screen you can select the channels which you want to see in the tv-guide.
  
### Changelog
#### 1.0.0
- First release

---

If you like my work please feel free to buy me a coffee

<a href="https://www.buymeacoffee.com/Stephan296" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/white_img.png" alt="Buy Me A Coffee"></a>
