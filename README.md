
# Websit Url

- default url : https://jonasyow.github.io/ottawaomac/
- It can be customized as http://www.ottawamandarinalliance.ca/ (Can we enable https ?)
- To do run as PWA (Like mobile application, can be accessed offline)

# How to update website content

Almost of websit conten is in data files (yaml, cvs ...), any update in the data files (commit your changes), the website will be updated automatically. 

If you have a account of github, you can do the update via browser, no IDE is needed.

## website layout
- In `_layouts/front.html` reorder or remove section as you prefer.

## Data files
- The contact information is in `_config.yml`
- 小组信息 -- `_data/group.yaml`
- 最新活动 -- `_data/news.yaml`
- 教会事工 -- `_data/services.yaml`
- 灵命进深 -- `_data/study.yaml`

## Font, font size and theme color, background image
-- `_sass/_base.scss`

