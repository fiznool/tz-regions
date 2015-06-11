This node-based script is used to convert timezone json data into a list of cities that can be used in a HTML select dropdown.

The input JSON file should first be generated using the [timezone-js](https://github.com/mde/timezone-js) project.

Note that you may need to sort some of the returned items in the array manually, particularly those in the _Other_ region.

## Usage

``` js
node index.js <datafile> > <outfile>
```

## Example

``` js
node index.js tzdata2015d.json > tzregions.json
```

## Existing data

Timezone data in `tzregions.json` was generated on 2015-06-11.
