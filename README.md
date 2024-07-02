{
  "setting": [
    {
      "/index.html": { "isHome": true, "title": "メインページ" },
      "/list.html": {
        "isHome": false,
        "title": "リストページ",
        "items": ["red", "green", "yellow"]
      },
      "/about/index.html": {
        "isHome": false,
        "title": "Aboutページ",
        "items": ["りんご", "メロン", "バナナ"]
      }
    }
  ]
}








import data from "./src/js/json/seting.json" assert {type: 'json'}



const pageData = data.setting[0]
