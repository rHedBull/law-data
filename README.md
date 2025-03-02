# law-data
German Laws parsed into Json format with refrences to each other

# law-data

This repository holds data about German law parsed into JSON format. Each law is broken down into articles, paragraphs, and nodes representing references between articles. However, there is currently no referencing between different laws.

**Disclaimer**: There is no guarantee that the data is complete or parsed correctly. Contributors are not liable for any inaccuracies.

If you want to contribute to this project, feel free to open a pull request. If you have any questions, feel free to open an issue.
THIS is not an actively maintained project, but I might from time to time add content or fix issues.

Feel free to comment if you have any questions or suggestions. I am looking forward to see what projects you are using this data for.

## Law resources
The German laws are from the [gesetze-im-internet.de](https://www.gesetze-im-internet.de/aktuell.html) website.

## Parsed Laws
### Germany
- [Grundgesetz]("parsed_GG.json")
- [Bürgerliches Gesetzbuch]("parsed_BGB.json")
- [Strafgesetzbuch]("parsed_StGB.json")
- [Strafprozessordnung]("parsed_StPO.json")
- [Zivilprozessordnung]("parsed_ZPO.json")
- [Handelsgesetzbuch]("parsed_HGB.json")

## TODO
- [ ] Add references between different laws
- [ ] add more laws
- [ ] add more metadata to the laws
- [ ] tracking of active and inactive laws
- [ ] laws from other countries, Us constitution, European laws, etc.
- [ ] add law adjacent data, like court decisions, legal commentary, etc.
- [ ] Landesrecht, EU-Recht, Völkerrecht, etc.
