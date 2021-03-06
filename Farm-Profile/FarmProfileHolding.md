 - <b id="#/properties/id">id</b>
	 - **Description:** Internal identifier in the source system
	 - **Type:** `string`
 - <b id="#/properties/identifiers">identifiers</b>
	 - **Description:** Holding Identifiers using a URN-based identification string containing namespace and unique identifier within the namespace. Used as a unique identifier. Eg. urn:nzl:pri:holding:AgriBase:12345, urn:nzl:pri:holding:FOL_ID:CL:67645
	 - **Type:** `array`
 - <b id="#/properties/name">name</b>
	 - **Description:** Name of the holding
	 - **Type:** `string`
 - <b id="#/properties/sites">sites</b>
	 - **Description:** Array of sites in the holding
	 - **Type:** `array`
	 - <b id="farmprofilesitefarmprofilesite.md">Link to schema: [FarmProfileSite](FarmProfileSite.md)</b>
 - <b id="#/properties/topography">topography</b>
	 - **Description:** Rolling, Easy hill, Steep hill (this enumeration is defined by Overseer). Can be different for other systems
	 - **Type:** `string`
 - <b id="#/properties/organic">organic</b>
	 - **Description:** Indicates whether holding is organic or not.
	 - **Type:** `boolean`
 - <b id="#/properties/meta">meta</b>
	 - **Description:** Any metadata for the object.  Most likely to use 'modified'
	 - **Type:** `object`
	 - <b id="httpsgithub.comdatalinker-orgicar-rezareicarobjectmetadata.md">Link to schema: https://github.com/Datalinker-Org/ICAR-Rezare/ICARObjectMetaData.md</b>

_Generated with [json-schema-md-doc](https://brianwendt.github.io/json-schema-md-doc/)_