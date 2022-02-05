# NFTs_Upload_To_OpenSea_With_Metadata

## Instructions:

* ### Basic installation of Python for beginners:

  * Download this repository or clone it:
```
git clone https://github.com/nftdevs/NFTs_Upload_To_OpenSea_With_Metadata.git
```
  * It requires [Python](https://www.python.org/) 3.7 or a newest version.
  * Install [pip](https://pip.pypa.io/en/stable/installation/) to be able to have needed Python modules.
  * Open a command prompt in repository folder and type:
```
pip install -r requirements.txt
```

* ### Configuration of bot:

  * Download and install [Google Chrome](https://www.google.com/intl/en_en/chrome/).
  * Download the [ChromeDriver executable](https://chromedriver.chromium.org/downloads) that is compatible with the actual version of your Google Chrome browser and your OS (Operating System). Refer to: _[What version of Google Chrome do I have?](https://www.whatismybrowser.com/detect/what-version-of-chrome-do-i-have)_
  * Extract the executable from the ZIP file and copy/paste it in the `assets/` folder of the repository.
    



* ### Data file structure:
```json
{
  "nft": [
    {
      "file_path": "C:/Users/User/build/images/1.png",	
      "nft_name": "NFT #1",
      "external_link": "https://www.google.com/",
      "description": "Remember to replace this description",
      "collection": "CollectionName",
      "properties": [
        {
          "type": "Background",
          "value": "Black"
        },
        {
          "type": "Eyeball",
          "value": "White"
        },
        {
          "type": "Eye color",
          "value": "Green"
        },
        {
          "type": "Iris",
          "value": "Large"
        },
        {
          "type": "Shine",
          "value": "Shapes"
        },
        {
          "type": "Bottom lid",
          "value": "Middle"
        },
        {
          "type": "Top lid",
          "value": "Low"
        }
      ],
	   "levels": [
           {
             "name": "Speed",
             "from": 2,
             "to": 5
           },
           {
             "name": "Width",
             "from": 2,
             "to": 15
           }
         ],
         "stats": [
           {
             "name": "Strenght",
             "from": 1,
             "to": 10
           },
           {
             "name": "Age",
             "from": 1,
             "to": 9
           }
         ],
      "unlockable_content": [
        true,
        "Content"
      ],
      "explicit_and_sensitive_content": true,
      "supply": 1,
      "blockchain": "Polygon",
      "price": 0.005,
      "quantity": 1
    }
  ]
}


Credits to @maximedrn -> https://github.com/maximedrn/opensea_automatic_uploader


