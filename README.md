## gpc-data
GeoPostcodes public datasets.<br><br>

#### GeoPC_Countries
This file contains all country codes and names with their postal code schemes. The country list is based on the cartographic section of the United Nations. 

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
This file contains for each country the official administrative division names included in our datasets. 
