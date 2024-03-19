# Nynorskoversetteren

Nynorskoversetteren makes it easy for editors to translate from Bokmål to Nynorsk by providing a Widget for this. Translation is made using Totaltekst API. Both plain text and HTML markup are supported. 

## Setup
### Building

```bash
git clone https://github.com/seeds/nynorskoversetteren-xp.git
cd nynorskoversetteren-xp
./gradlew clean build
```

### Installation

Install the application and add it to your site. A valid API Key from Totaltekst then needs to be defined in the app settings in order to use the Widget.

## Known issues

- When translating content in Automatic mode the value stored for input fields like radioButton will also be translated. This may result in invalid options once the object is modified and the page is refreshed.
- It is possible that iframes present in HtmlArea fields stop working once the object is modified and the page is refreshed.

Editors may want to double check and review the translated values before publishing the changes.

## Releases and Compatibility

| Version | XP version   |
| ------- | ------------ |
| 1.0.x  | 7.9.0       |
| 2.x.x  | 7.9.0       |

## License and credits

A license is required to use this application. Once the app is installed, the Widget will be blocked until a license is provided.

You can contact [Seeds](https://www.seeds.no/) to request a license. If a valid license is not found in the system, it can be installed by clicking the button `Upload license` in the Widget.

Made by [Seeds Consulting](https://seeds.no)







