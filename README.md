## gpc-data
GeoPostcodes public datasets.<br><br>

#### GeoPC_Countries
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
#### GeoPC_Admin
All official administrative division names included in GeoPostcodes datasets. 

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
#### GeoPC_Timezones
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
#### GeoPC_Currencies
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
#### GeoPC_Statistics
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
#### GeoPC_Languages
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
#### GeoPC_Callingcodes
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


