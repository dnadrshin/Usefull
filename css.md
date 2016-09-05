##CSS Selectors

* element>element div > p	Selects all <p> elements where the parent is a <div> element	
* element+element	div + p	Selects all <p> elements that are placed immediately after <div> elements	
* element1~element2	p ~ ul	Selects every <ul> element that are preceded by a <p> element	
* [attribute=value]	[target=_blank]	Selects all elements with target="_blank"	
* [attribute~=value] [title~=flower]	Selects all elements with a title attribute containing the word "flower"	
* [attribute|=value] [lang|=en]	Selects all elements with a lang attribute value starting with "en"	
* [attribute^=value] a[href^="https"]	Selects every <a> element whose href attribute value begins with "https"	
* [attribute$=value] a[href$=".pdf"]	Selects every <a> element whose href attribute value ends with ".pdf"	
* [attribute*=value] a[href*="w3schools"]	Selects every <a> element whose href attribute value contains the substring "w3schools"	
