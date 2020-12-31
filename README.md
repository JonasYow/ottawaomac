
# Websit Url

- default url : https://jonasyow.github.io/ottawaomac/
- URL in production: https://www.ottawamandarinalliance.ca/
- To do run as PWA (Like mobile application, can be accessed offline)

# How to update website content

Almost of websit conten is in data files (yaml, cvs ...), any update in the data files (commit your changes), the website will be updated automatically. 
The site will be rebuilt and take about 2min to refresh. 

If you have an account of github, you can do the update via browser, no IDE is needed.

## website layout
- In `_layouts/front.html` reorder or remove section as you prefer.
- subpage layout: -- `_layouts/subpage.html`

## Data files
- The contact information is in `_config.yml`
- 小组信息 -- `_data/groups.yaml`
- 教会行事历 -- `_data/calendar.yaml`
- 关于我们 -- `_data/services.yaml`
- 灵命进深 -- `_data/study.yaml`
- 主日学 -- `_data/sundayschool.yaml`

## Font, font size and theme color, background image
-- `_sass/_base.scss`

## Edit YAML file

make sure the YAML files follow these rules:

- Use spaces instead of tabs.
- Include a space after the : for each key value pair, like timezone: Africa/Nairobi.
- Use only UTF-8 characters.
- Quote any special characters, such as :, like title: "my awesome site: an adventure in parse errors".
- For multi-line values, use | to create newlines and > to ignore newlines.
- To identify any errors, you can copy and paste the contents of your YAML file into a YAML linter, such as [YAML Validator](https://codebeautify.org/yaml-validator).


