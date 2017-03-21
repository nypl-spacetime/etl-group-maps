# Space/Time ETL module: Map Warper maps, grouped by decade

[ETL](https://en.wikipedia.org/wiki/Extract,_transform,_load) module for NYPL's [NYC Space/Time Direcory](http://spacetime.nypl.org/). This Node.js module downloads, parses, and/or transforms Map Warper maps, grouped by decade data, and creates a NYC Space/Time Directory dataset.

## Details

<table>
<tbody>

<tr>
<td>ID</td>
<td><code>group-maps</code></td>
</tr>

<tr>
<td>Title</td>
<td>Map Warper maps, grouped by decade</td>
</tr>

<tr>
<td>License</td>
<td>CC0</td>
</tr>

<tr>
<td>Author</td>
<td>Bert Spaan</td>
</tr>

<tr>
<td>Website</td>
<td><a href="http://spacetime.nypl.org/maps-by-decade">http://spacetime.nypl.org/maps-by-decade</a></td>
</tr>
</tbody>
</table>

## Available steps

  - `aggregate`

## Usage

```
git clone https://github.com/nypl-spacetime/etl-group-maps.git /path/to/etl-modules
cd /path/to/etl-modules/etl-group-maps
npm install

spacetime-etl group-maps [<step>]
```

See http://github.com/nypl-spacetime/spacetime-etl for information about Space/Time's ETL tool. More Space/Time ETL modules [can be found on GitHub](https://github.com/search?utf8=%E2%9C%93&q=org%3Anypl-spacetime+etl-&type=Repositories&ref=advsearch&l=&l=).