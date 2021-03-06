 - <b id="#/properties/blockId">blockId</b>
	 - **Description:** Identifier for the block
	 - **Type:** `string`
 - <b id="#/properties/blockName">blockName</b>
	 - **Description:** Name of the block
	 - **Type:** `string`
 - <b id="#/properties/effectiveArea">effectiveArea</b>
	 - **Description:** Block effective area in hectares
	 - **Type:** `integer`
 - <b id="#/properties/ungrazeableArea">ungrazeableArea</b>
	 - **Description:** Block ungrazeable area in hectares
	 - **Type:** `integer`
 - <b id="#/properties/blockOwnership">blockOwnership</b>
	 - **Description:** Values can be 'Owned' or 'Leased'
	 - **Type:** `string`
 - <b id="#/properties/topography">topography</b>
	 - **Description:** Values can be Flat,Rolling,Easy hill, Steep hill
	 - **Type:** `string`
 - <b id="#/properties/blockType">blockType</b>
	 - **Description:** Pature, Support or Crop
	 - **Type:** `string`
 - <b id="#/properties/dtStart">dtStart</b>
	 - **Description:** Date started operating for specific paddock type
	 - **Type:** `string`
 - <b id="#/properties/dtEnd">dtEnd</b>
	 - **Description:** Date ended(ceased) operating for specific paddock type
	 - **Type:** `string`
 - <b id="#/properties/pastureType">pastureType</b>
	 - **Description:** Enumeration: Ryegrass/white clover, Browntop, Unimproved/tussock grasslands, Summer C4 (paspalum) pastures, C4 (kikuyu) pastures, Lucerne, Grass only (enumeration defined by Overseer)
	 - **Type:** `string`
 - <b id="#/properties/cloverLevel">cloverLevel</b>
	 - **Description:** Annual average clover content (as a proportion of pasture dry matter) where fertiliser N inputs are not applied. Enumeration defined by Overseer. Enumeration: Very low, Low, Medium, High, Very high
	 - **Type:** `integer`
 - <b id="#/properties/pastureUtilisation">pastureUtilisation</b>
	 - **Description:** Expressed in percentage
	 - **Type:** `integer`
 - <b id="#/properties/avgPastureNConc">avgPastureNConc</b>
	 - **Description:** Expressed in percentage
	 - **Type:** `integer`
 - <b id="#/properties/roadAddress">roadAddress</b>
	 - **Description:** Road address of the block
	 - **Type:** `string`
 - <b id="#/properties/stockTypes">stockTypes</b>
	 - **Description:** Dairy Cows [Cows], Dairy Replacements [Young Stock], Pigs, Sheep, Beef Cattle [Cattle], Deer
	 - **Type:** `array`
 - <b id="#/properties/numberOfStock">numberOfStock</b>
	 - **Description:** Number of animals
	 - **Type:** `integer`
 - <b id="#/properties/dtStockCome">dtStockCome</b>
	 - **Description:** Date when the animals came in
	 - **Type:** `string`
 - <b id="#/properties/dtStockLeave">dtStockLeave</b>
	 - **Description:** Date when the animals moved out
	 - **Type:** `string`
 - <b id="#/properties/areaHayPerSilageHarvested">areaHayPerSilageHarvested</b>
	 - **Description:** Expressed in Hectares
	 - **Type:** `integer`
 - <b id="#/properties/destinationHaySilage">destinationHaySilage</b>
	 - **Description:** Fed on support block, Milking area or Elsewhere (defined by Overseer)
	 - **Type:** `string`
 - <b id="#/properties/runoff">runoff</b>
	 - **Description:** True if runoff block
	 - **Type:** `string`
 - <b id="#/properties/pastureSpecies">pastureSpecies</b>
	 - **Description:** Plant species names as defined in http://www.feedipedia.org/content/feeds?category=15965
	 - **Type:** `string`
 - <b id="#/properties/croppingArea">croppingArea</b>
	 - **Description:** Area planted in crop. In Hectares
	 - **Type:** `integer`

_Generated with [json-schema-md-doc](https://brianwendt.github.io/json-schema-md-doc/)_