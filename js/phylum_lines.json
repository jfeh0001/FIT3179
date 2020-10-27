{
  "$schema": "https://vega.github.io/schema/vega-lite/v4.json",
  "description": "Changes",
  "data": {"url": "https://raw.githubusercontent.com/jfeh0001/FIT3179/main/Data/animal_table.csv"},
  "mark": {
    "type": "line",
    "point": false
  },
  "encoding": {
    "x": {"field": "period", "sort": ["Cambrian", "Ordovician", "Silurian", "Devonian", "Carboniferous", "Permian", "Triassic", "Jurassic", "Cretaceous", "Paleogene", "Neogene", "Quaternary"]},
    "y": {"aggregate":"count", "field": "phylum", "type": "nominal"},
    "color": {"field": "phylum_large", "type": "nominal"},
    "tooltip": [
    {"field": "period", "type": "nominal", "title": "Period"}]
}
}
