A community is hosting a series of festive feasts, and they want to ensure a balanced menu. Write a query to identify the top 3 most calorie-dense dishes (calories per gram) served for each event. Include the dish_name, event_name, and the calculated calorie density in your results.

Table name: events

<table class="chakra-table css-5605sr"><thead class="css-0"><tr class="css-0"><th class="css-19iw99a">event_id</th><th class="css-19iw99a">event_name</th></tr></thead><tbody class="css-0"><tr class="css-0"><td class="css-x7usx6">1</td><td class="css-x7usx6">Christmas Eve Dinner</td></tr><tr class="css-0"><td class="css-x7usx6">2</td><td class="css-x7usx6">New Years Feast</td></tr><tr class="css-0"><td class="css-x7usx6">3</td><td class="css-x7usx6">Winter Solstice Potluck</td></tr></tbody></table>

Table name: menu

<table class="chakra-table css-5605sr"><thead class="css-0"><tr class="css-0"><th class="css-19iw99a">dish_id</th><th class="css-19iw99a">dish_name</th><th class="css-19iw99a">event_id</th><th class="css-19iw99a">calories</th><th class="css-19iw99a">weight_g</th></tr></thead><tbody class="css-0"><tr class="css-0"><td class="css-x7usx6">1</td><td class="css-x7usx6">Roast Turkey</td><td class="css-x7usx6">1</td><td class="css-x7usx6">3500</td><td class="css-x7usx6">5000</td></tr><tr class="css-0"><td class="css-x7usx6">2</td><td class="css-x7usx6">Chocolate Yule Log</td><td class="css-x7usx6">1</td><td class="css-x7usx6">2200</td><td class="css-x7usx6">1000</td></tr><tr class="css-0"><td class="css-x7usx6">3</td><td class="css-x7usx6">Cheese Fondue</td><td class="css-x7usx6">2</td><td class="css-x7usx6">1500</td><td class="css-x7usx6">800</td></tr><tr class="css-0"><td class="css-x7usx6">4</td><td class="css-x7usx6">Holiday Fruitcake</td><td class="css-x7usx6">3</td><td class="css-x7usx6">4000</td><td class="css-x7usx6">1200</td></tr><tr class="css-0"><td class="css-x7usx6">5</td><td class="css-x7usx6">Honey Glazed Ham</td><td class="css-x7usx6">2</td><td class="css-x7usx6">2800</td><td class="css-x7usx6">3500</td></tr></tbody></table>