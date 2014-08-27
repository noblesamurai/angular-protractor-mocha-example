You will need to include your saucelabs config details in .travis.yml.

```bash
gem install travis
travis login --pro   # need to let travis know who I am, --pro for hidden repos
travis encrypt SAUCE_USERNAME=noblesamurai --add
travis encrypt SAUCE_ACCESS_JEY=[key] --add
```
