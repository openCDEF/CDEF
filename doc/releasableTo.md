# releasableTo code list introduction 
The below outlines, in a document format, the code list of applicable codes for "releasableTo". 

This code list is derived from the US Department of Defense (DoD) json-ism standard, the json-ism standard focusses on JSON payload classification where the open CDEF standard has a focus on JSON based events to be used in NATO event based architectures and data mesh constructs.

Department of Defense (DoD) policy requires the identification and protection of national security information and controlled unclassified information (CUI). Department of Defense Manual (DoDM) 5200.01, Volumes 2 and 4 (referenced below) describe how to appropriately mark classified information and CUI to facilitate information sharing. These markings are used (along with other factors) to make access/dissemination decisions.

Exstensible Markup Language (XML) is widely used within the DoD to share information and a comprehensive marking standard called Information Security Marking Metadata (ISM or IC-ISM) has been made available by the Office of the Director of National Intelligence (referenced below). We are not aware of any similar marking standards based on JavaScript Object Notation (JSON). With the ever increasing popularity of event based architectures and data mesh architectures for sharing information between applications/systems, many now using JSON over XML, a standard for marking JSON based events has become necessary. The open CDEF standard aims at including the principles of the JSON-ISM and ISM/ISM-C Information Security Marking Standard within the event JSON payload standard to be used within the wider NATO architecture. 

## References

* [DoDM 5200.01, Volume 2 - DoD Information Security Program: Marking of Classified Information](http://www.dtic.mil/whs/directives/corres/pdf/520001_vol2.pdf)
* [DoDM 5200.01, Volume 4 - DoD Information Security Program: Controlled Unclassified Information (CUI)](http://www.dtic.mil/whs/directives/corres/pdf/520001_vol4.pdf)
* [Office of the Director of National Intelligence - Information Security Marking Metadata (ISM)](https://www.dni.gov/index.php/about/organization/chief-information-officer/information-security-marking-metadata)
* [JSON Information Security Marking Standard (JSON-ISM)] (https://github.com/DoDCIO/json-ism/)

## Releasable To code list
The `releasableTo` attribute (Array[String]) identifies one or more countries and/or international organizations to which classified information may be released based on the determination of an originator in accordance with established foreign disclosure procedures.  This attribute is used in conjunction with the `disseminationControls` attribute.

The possible patterns for `releasableTo` are:

| Pattern | description |
| ------- | ----------- |
| NATO/[a-zA-Z\-_] | North Atlantic Treaty Organization Special Words |

The possible values for `releasableTo` are:

| Value | Description |
| ----- | ----------- |
| USA | United States |
| ABW | Aruba |
| AFG | Islamic Republic of Afghanistan |
| AGO | Republic of Angola |
| AIA | Anguilla |
| ALB | Republic of Albania |
| AND | Principality of Andorra |
| ARE | United Arab Emirates |
| ARG | Argentine Republic |
| ARM | Republic of Armenia |
| ASM | Territory of American Samoa |
| ATA | Antarctica |
| ATF | French Southern and Antarctic Lands |
| ATG | Antigua and Barbuda |
| AUS | Commonwealth of Australia |
| AUT | Republic of Austria |
| AX2 | Guantanamo Bay Naval Base |
| AZE | Republic of Azerbaijan |
| BDI | Republic of Burundi |
| BEL | Kingdom of Belgium |
| BEN | Republic of Benin |
| BES | Bonaire, Sint Eustatius, and Saba |
| BFA | Burkina Faso |
| BGD | People's Republic of Bangladesh |
| BGR | Republic of Bulgaria |
| BHR | Kingdom of Bahrain |
| BHS | Commonwealth of The Bahamas |
| BIH | Bosnia and Herzegovina |
| BLM | Saint Barthelemy |
| BLR | Republic of Belarus |
| BLZ | Belize |
| BMU | Bermuda |
| BOL | Plurinational State of Bolivia |
| BRA | Federative Republic of Brazil |
| BRB | Barbados |
| BRN | Brunei Darussalam |
| BTN | Kingdom of Bhutan |
| BVT | Bouvet Island |
| BWA | Republic of Botswana |
| CAF | Central African Republic |
| CAN | Canada |
| CCK | Territory of Cocos (Keeling) Islands |
| CHE | Swiss Confederation |
| CHL | Republic of Chile |
| CHN | People's Republic of China |
| CIV | Republic of Côte d'Ivoire |
| CMR | Republic of Cameroon |
| COD | Democratic Republic of the Congo |
| COG | Republic of the Congo |
| COK | Cook Islands |
| COL | Republic of Colombia |
| COM | Union of the Comoros |
| CPT | Clipperton Island |
| CPV | Republic of Cape Verde |
| CRI | Republic of Costa Rica |
| CUB | Republic of Cuba |
| CUW | Curaçao |
| CXR | Territory of Christmas Island |
| CYM | Cayman Islands |
| CYP | Republic of Cyprus |
| CZE | Czech Republic |
| DEU | Federal Republic of Germany |
| DGA | Diego Garcia |
| DJI | Republic of Djibouti |
| DMA | Commonwealth of Dominica |
| DNK | Kingdom of Denmark |
| DOM | Dominican Republic |
| DZA | People's Democratic Republic of Algeria |
| ECU | Republic of Ecuador |
| EGY | Arab Republic of Egypt |
| ERI | State of Eritrea |
| ESH | Western Sahara |
| ESP | Kingdom of Spain |
| EST | Republic of Estonia |
| ETH | Federal Democratic Republic of Ethiopia |
| FIN | Republic of Finland |
| FJI | Republic of Fiji |
| FLK | Falkland Islands (Islas Malvinas) |
| FRA | French Republic |
| FRO | Faroe Islands |
| FSM | Federated States of Micronesia |
| GAB | Gabonese Republic |
| GBR | United Kingdom of Great Britain and Northern Ireland |
| GEO | Georgia |
| GGY | Bailiwick of Guernsey |
| GHA | Republic of Ghana |
| GIB | Gibraltar |
| GIN | Republic of Guinea |
| GLP | Department of Guadeloupe |
| GMB | Republic of The Gambia |
| GNB | Republic of Guinea-Bissau |
| GNQ | Republic of Equatorial Guinea |
| GRC | Hellenic Republic |
| GRD | Grenada |
| GRL | Greenland |
| GTM | Republic of Guatemala |
| GUF | Department of Guiana |
| GUM | Territory of Guam |
| GUY | Co-operative Republic of Guyana |
| HKG | Hong Kong Special Administrative Region |
| HMD | Territory of Heard Island and McDonald Islands |
| HND | Republic of Honduras |
| HRV | Republic of Croatia |
| HTI | Republic of Haiti |
| HUN | Hungary |
| IDN | Republic of Indonesia |
| IMN | Isle of Man |
| IND | Republic of India |
| IOT | British Indian Ocean Territory |
| IRL | Ireland |
| IRN | Islamic Republic of Iran |
| IRQ | Republic of Iraq |
| ISL | Republic of Iceland |
| ISR | State of Israel |
| ITA | Italian Republic |
| JAM | Jamaica |
| JEY | Bailiwick of Jersey |
| JOR | Hashemite Kingdom of Jordan |
| JPN | Japan |
| KAZ | Republic of Kazakhstan |
| KEN | Republic of Kenya |
| KGZ | Kyrgyz Republic |
| KHM | Kingdom of Cambodia |
| KIR | Republic of Kiribati |
| KNA | Federation of Saint Kitts and Nevis |
| KOR | Republic of Korea |
| KWT | State of Kuwait |
| LAO | Lao People's Democratic Republic |
| LBN | Lebanese Republic |
| LBR | Republic of Liberia |
| LBY | Libya |
| LCA | Saint Lucia |
| LIE | Principality of Liechtenstein |
| LKA | Democratic Socialist Republic of Sri Lanka |
| LSO | Kingdom of Lesotho |
| LTU | Republic of Lithuania |
| LUX | Grand Duchy of Luxembourg |
| LVA | Republic of Latvia |
| MAC | Macau Special Administrative Region |
| MAF | Saint Martin |
| MAR | Kingdom of Morocco |
| MCO | Principality of Monaco |
| MDA | Republic of Moldova |
| MDG | Republic of Madagascar |
| MDV | Republic of Maldives |
| MEX | United Mexican States |
| MHL | Republic of the Marshall Islands |
| MKD | Republic of Macedonia |
| MLI | Republic of Mali |
| MLT | Republic of Malta |
| MMR | Union of Burma |
| MNE | Montenegro |
| MNG | Mongolia |
| MNP | Commonwealth of the Northern Mariana Islands |
| MOZ | Republic of Mozambique |
| MRT | Islamic Republic of Mauritania |
| MSR | Montserrat |
| MTQ | Department of Martinique |
| MUS | Republic of Mauritius |
| MWI | Republic of Malawi |
| MYS | Malaysia |
| MYT | Department of Mayotte |
| NAM | Republic of Namibia |
| NCL | New Caledonia |
| NER | Republic of the Niger |
| NFK | Territory of Norfolk Island |
| NGA | Federal Republic of Nigeria |
| NIC | Republic of Nicaragua |
| NIU | Niue |
| NLD | Kingdom of the Netherlands |
| NOR | Kingdom of Norway |
| NPL | Federal Democratic Republic of Nepal |
| NRU | Republic of Nauru |
| NZL | New Zealand |
| OMN | Sultanate of Oman |
| PAK | Islamic Republic of Pakistan |
| PAN | Republic of Panama |
| PCN | Pitcairn, Henderson, Ducie, and Oeno Islands |
| PER | Republic of Peru |
| PHL | Republic of the Philippines |
| PLW | Republic of Palau |
| PNG | Independent State of Papua New Guinea |
| POL | Republic of Poland |
| PRI | Commonwealth of Puerto Rico |
| PRK | Democratic People's Republic of Korea |
| PRT | Portuguese Republic |
| PRY | Republic of Paraguay |
| PSE | Palestinian Territory |
| PYF | French Polynesia |
| QAT | State of Qatar |
| REU | Department of Reunion |
| ROU | Romania |
| RUS | Russian Federation |
| RWA | Republic of Rwanda |
| SAU | Kingdom of Saudi Arabia |
| SDN | Republic of the Sudan |
| SEN | Republic of Senegal |
| SGP | Republic of Singapore |
| SGS | South Georgia and South Sandwich Islands |
| SHN | Saint Helena, Ascension, and Tristan da Cunha |
| SLB | Solomon Islands |
| SLE | Republic of Sierra Leone |
| SLV | Republic of El Salvador |
| SMR | Republic of San Marino |
| SOM | Somalia, Federal Republic of |
| SPM | Territorial Collectivity of Saint Pierre and Miquelon |
| SRB | Republic of Serbia |
| SSD | Republic of South Sudan |
| STP | Democratic Republic of Sao Tome and Principe |
| SUR | Republic of Suriname |
| SVK | Slovak Republic |
| SVN | Republic of Slovenia |
| SWE | Kingdom of Sweden |
| SWZ | Kingdom of Swaziland |
| SXM | Sint Maarten |
| SYC | Republic of Seychelles |
| SYR | Syrian Arab Republic |
| TCA | Turks and Caicos Islands |
| TCD | Republic of Chad |
| TGO | Togolese Republic |
| THA | Kingdom of Thailand |
| TJK | Republic of Tajikistan |
| TKL | Tokelau |
| TKM | Turkmenistan |
| TLS | Democratic Republic of Timor-Leste |
| TON | Kingdom of Tonga |
| TTO | Republic of Trinidad and Tobago |
| TUN | Tunisian Republic |
| TUR | Republic of Turkey |
| TUV | Tuvalu |
| TWN | Taiwan |
| TZA | United Republic of Tanzania |
| UGA | Republic of Uganda |
| UKR | Ukraine |
| URY | Oriental Republic of Uruguay |
| UZB | Republic of Uzbekistan |
| VAT | State of the Vatican City |
| VCT | Saint Vincent and the Grenadines |
| VEN | Bolivarian Republic of Venezuela |
| VGB | Virgin Islands, British |
| VIR | United States Virgin Islands |
| VNM | Socialist Republic of Vietnam |
| VUT | Republic of Vanuatu |
| WLF | Wallis and Futuna |
| WSM | Independent State of Samoa |
| XAC | Territory of Ashmore and Cartier Islands |
| XAZ | Entity 1 |
| XBI | Bassas da India |
| XBK | Baker Island |
| XCR | Entity 2 |
| XCS | Coral Sea Islands Territory |
| XCY | Entity 3 |
| XEU | Europa Island |
| XGL | Glorioso Islands |
| XGZ | Gaza Strip |
| XHO | Howland Island |
| XJA | Johnston Atoll |
| XJM | Jan Mayen |
| XJN | Juan de Nova Island |
| XJV | Jarvis Island |
| XKM | Entity 4 |
| XKN | Entity 5 |
| XKR | Kingman Reef |
| XKS | Republic of Kosovo |
| XMW | Midway Islands |
| XNV | Navassa Island |
| XPL | Palmyra Atoll |
| XPR | Paracel Islands |
| XQP | Etorofu, Habomai, Kunashiri, and Shikotan Islands  |
| XQZ | Akrotiri |
| XSP | Spratly Islands |
| XSV | Svalbard |
| XTR | Tromelin Island |
| XWB | West Bank |
| XWK | Wake Island |
| XXD | Dhekelia |
| XXX | No Man's Land |
| YEM | Republic of Yemen |
| ZAF | Republic of South Africa |
| ZMB | Republic of Zambia |
| ZWE | Republic of Zimbabwe |
| ACGU | FOUR EYES |
| APFS | Suppressed |
| BWCS | Biological Weapons Convention States |
| CFCK | ROK/US Combined Forces Command, Korea |
| CMFC | Combined Maritime Forces Central |
| CMFP | Cooperative Maritime Forces Pacific |
| CPMT | Civilian Protection Monitoring Team for Sudan |
| CTOC | Countering Transnational Organized Crime |
| CWCS | Chemical Weapons Convention States |
| FVEY | FIVE EYES |
| GCTF | Global Counter-Terrorism Forces |
| GMIF | Global Maritime Interception Forces |
| ISAF | International Security Assistance Force for Afghanistan |
| KFOR | Stabilization Forces in Kosovo |
| MLEC | Multi-Lateral Enduring Contingency |
| NACT | North African Counter-Terrorism Forces |
| NATO | North Atlantic Treaty Organization |
| NCFE | NATO Convention Armed Forces in Europe |
| OSTY | Open Skies Treaty |
| SPAA | Suppressed |
| TEYE | THREE EYES |
| UNCK | United Nations Command, Korea |
