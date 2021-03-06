## gpc-data
GeoPostcodes public datasets. All files are in CSV format, with UTF-8 encoding and ; as delimiter.<br><br>

#### GeoPC_Countries.csv
Country codes and names with their postal code schemes. This list is based on the cartographic section of the United Nations. 

<table class="table table-bordered table-striped">
<thead>
  <tr><th width="150">Field name</th><th width="120">Field type</th><th>Description</th></tr>
</thead>
<tbody>
  <tr><td><b>ISO</b></td><td><code>Char(2)</code></td><td>ISO 3166-1 Country code</td></tr>
  <tr><td><b>Country</b></td><td><code>Char(50)</code></td><td>Country name</td></tr>
  <tr><td><b>Sovereign</b></td><td><code>Char(2)</code></td><td>Sovereign country code</td></tr>
  <tr><td><b>Capital</b></td><td><code>Char(60)</code></td><td>Capital city</td></tr>
  <tr><td><b>PostalFormat</b></td><td><code>Char(10)</code></td><td>Postal code format</td></tr>
  <tr><td><b>PostalName</b></td><td><code>Char(30)</code></td><td>Postal code name</td></tr>
  <tr><td><b>Comments</b></td><td><code>Char(30)</code></td><td>Comments</td></tr>
</tbody>
</table>

<br>
#### GeoPC_Admin.csv
All official administrative division names included in the GeoPostcodes datasets. 

<table class="table table-bordered table-striped">
<thead>
  <tr><th width="150">Field name</th><th width="120">Field type</th><th>Description</th></tr>
</thead>
<tbody>
  <tr><td><b>ISO</b></td><td><code>Char(2)</code></td><td>ISO 3166-1 Country code</td></tr>
  <tr><td><b>Country</b></td><td><code>Char(50)</code></td><td>Country name</td></tr>
  <tr><td><b>Sovereign</b></td><td><code>Char(2)</code></td><td>Sovereign country code</td></tr>
  <tr><td><b>Level</b></td><td><code>Smallint</code></td><td>Administrative level</td></tr>
  <tr><td><b>Name</b></td><td><code>Char(60)</code></td><td>Division name</td></tr>
  <tr><td><b>Name_EN</b></td><td><code>Char(60)</code></td><td>English name</td></tr>
  <tr><td><b>Total</b></td><td><code>Integer</code></td><td>Number of divisions</td></tr>
</tbody>
</table>

<br>
#### GeoPC_Timezones.csv
World time zone names and codes including Daylight Saving Time (DST), data maintained by IANA.

<table class="table table-bordered table-striped">
<thead>
  <tr><th width="150">Field name</th><th width="120">Field type</th><th>Description</th></tr>
</thead>
<tbody>
  <tr><td><b>ISO</b></td><td><code>Char(2)</code></td><td>ISO 3166-1 Country code</td></tr>
  <tr><td><b>Country</b></td><td><code>Char(50)</code></td><td>Country name</td></tr>
  <tr><td><b>Olson</b></td><td><code>Char(40)</code></td><td>Olson Time zone code</td></tr>
  <tr><td><b>UTC</b></td><td><code>Char(6)</code></td><td>UTC Offset</td></tr>
  <tr><td><b>DST</b></td><td><code>Char(6)</code></td><td>Daylight Saving Time</td></tr>
  <tr><td><b>Zone</b></td><td><code>Char(10)</code></td><td>Time zone abbreviation</td></tr>
  <tr><td><b>ZoneName</b></td><td><code>Char(50)</code></td><td>Time zone name</td></tr>
</tbody>
</table>

<br>
#### GeoPC_Currencies.csv
Currency codes ISO 4217 standard as published by the International Organization for Standardization (ISO).

<table class="table table-bordered table-striped">
<thead>
  <tr><th width="150">Field name</th><th width="120">Field type</th><th>Description</th></tr>
</thead>
<tbody>
  <tr><td><b>ISO</b></td><td><code>Char(2)</code></td><td>ISO 3166-1 Country code</td></tr>
  <tr><td><b>Country</b></td><td><code>Char(50)</code></td><td>Country name</td></tr>
  <tr><td><b>Currency</b></td><td><code>Char(40)</code></td><td>Currency name</td></tr>
  <tr><td><b>Code</b></td><td><code>Char(3)</code></td><td>Currency code</td></tr>
  <tr><td><b>Symbol</b></td><td><code>Char(5)</code></td><td>Currency symbol</td></tr>
  <tr><td><b>NumCode</b></td><td><code>Char(3)</code></td><td>Currency numeric code</td></tr>
  <tr><td><b>Decimal</b></td><td><code>Integer</code></td><td>Decimal positions</td></tr>
</tbody>
</table>

<br>
#### GeoPC_Statistics.csv
Statistical offices by country. Whenever possible we provide the statistical codes provided by these organisations in our region datasets.

<table class="table table-bordered table-striped">
<thead>
  <tr><th width="150">Field name</th><th width="120">Field type</th><th>Description</th></tr>
</thead>
<tbody>
  <tr><td><b>ISO</b></td><td><code>Char(2)</code></td><td>ISO 3166-1 Country code</td></tr>
  <tr><td><b>Country</b></td><td><code>Char(50)</code></td><td>Country name</td></tr>
  <tr><td><b>Name</b></td><td><code>Char(100)</code></td><td>Statistical organisation name</td></tr>
  <tr><td><b>Abbreviation</b></td><td><code>Char(20)</code></td><td>Statistical organisation abbreviation</td></tr>
  <tr><td><b>Website</b></td><td><code>Char(100)</code></td><td>Website URL</td></tr>
</tbody>
</table>

<br>
#### GeoPC_Languages.csv
Official languages list by country. ISO 639-1 and ISO 639-2 standards are published by the International Organization for Standardization (ISO).

<table class="table table-bordered table-striped">
<thead>
  <tr><th width="150">Field name</th><th width="120">Field type</th><th>Description</th></tr>
</thead>
<tbody>
  <tr><td><b>ISO</b></td><td><code>Char(2)</code></td><td>ISO 3166-1 Country code</td></tr>
  <tr><td><b>Country</b></td><td><code>Char(50)</code></td><td>Country name</td></tr>
  <tr><td><b>LanguageEN</b></td><td><code>Char(40)</code></td><td>English language name</td></tr>
  <tr><td><b>Language</b></td><td><code>Char(40)</code></td><td>Language name</td></tr>
  <tr><td><b>Code1</b></td><td><code>Char(2)</code></td><td>ISO 639-1 language code</td></tr>
  <tr><td><b>Code2</b></td><td><code>Char(3)</code></td><td>ISO 639-2 language code</td></tr>
</tbody>
</table>

<br>
#### GeoPC_Callingcodes.csv
International dialling codes by country.

<table class="table table-bordered table-striped">
<thead>
  <tr><th width="150">Field name</th><th width="120">Field type</th><th>Description</th></tr>
</thead>
<tbody>
  <tr><td><b>ISO</b></td><td><code>Char(2)</code></td><td>ISO 3166-1 Country code</td></tr>
  <tr><td><b>Country</b></td><td><code>Char(50)</code></td><td>Country name</td></tr>
  <tr><td><b>CCode</b></td><td><code>Char(3)</code></td><td>Currency code</td></tr>
</tbody>
</table>

<br>
#### GeoPC_ISO3166-2.csv
Principal subdivisions by country. ISO 3166-2 standard as published by the International Organization for Standardization (ISO).

<table class="table table-bordered table-striped">
<thead>
  <tr><th width="150">Field name</th><th width="120">Field type</th><th>Description</th></tr>
</thead>
<tbody>
  <tr><td><b>ISO</b></td><td><code>Char(2)</code></td><td>ISO 3166-1 Country code</td></tr>
  <tr><td><b>Country</b></td><td><code>Char(50)</code></td><td>Country name</td></tr>
  <tr><td><b>Code</b></td><td><code>Char(5)</code></td><td>ISO 3166-2 Region code</td></tr>
  <tr><td><b>Name</b></td><td><code>Char(80)</code></td><td>Region name</td></tr>
  <tr><td><b>AltName</b></td><td><code>Char(80)</code></td><td>Alternative region name</td></tr>
</tbody>
</table>

<br>
#### GeoPC_NUTS.csv
Nomenclature of Territorial Units for Statistics (NUTS) standard as provided by the European Commission for statistical purposes.

<table class="table table-bordered table-striped">
<thead>
  <tr><th width="150">Field name</th><th width="120">Field type</th><th>Description</th></tr>
</thead>
<tbody>
  <tr><td><b>ISO</b></td><td><code>Char(2)</code></td><td>ISO 3166-1 Country code</td></tr>
  <tr><td><b>Country</b></td><td><code>Char(50)</code></td><td>Country name</td></tr>
  <tr><td><b>Code</b></td><td><code>Char(5)</code></td><td>NUTS code</td></tr>
  <tr><td><b>Level</b></td><td><code>Integer</code></td><td>NUTS Level</td></tr>
  <tr><td><b>Name</b></td><td><code>Char(80)</code></td><td>Statistical region name</td></tr>
  <tr><td><b>AltName</b></td><td><code>Char(80)</code></td><td>Alternative statistical region name</td></tr>
</tbody>
</table>

<br>
#### GeoPC_NGA.csv
NGA Geopolitical codes (Formerly known as FIPS PUB 10-4) standard as published by the U.S. National Geospatial Intelligence Agency. The file contains countries, dependencies, areas of special sovereignty and their principal administrative divisions.

<table class="table table-bordered table-striped">
<thead>
  <tr><th width="150">Field name</th><th width="120">Field type</th><th>Description</th></tr>
</thead>
<tbody>
  <tr><td><b>ISO</b></td><td><code>Char(2)</code></td><td>ISO 3166-1 Country code</td></tr>
  <tr><td><b>NGA</b></td><td><code>Char(2)</code></td><td>NGA Country code</td></tr>
  <tr><td><b>Country</b></td><td><code>Char(50)</code></td><td>Country name</td></tr>
  <tr><td><b>Code</b></td><td><code>Char(4)</code></td><td>NGA region code (FIPS)</td></tr>
  <tr><td><b>Name</b></td><td><code>Char(80)</code></td><td>Administrative division name</td></tr>
  <tr><td><b>Class</b></td><td><code>Char(60)</code></td><td>Administrative division class</td></tr>
</tbody>
</table>

