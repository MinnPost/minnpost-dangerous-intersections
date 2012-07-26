# Minnesota Danger Intersections

Map of dangerous intersections in Minnesota

## Data processing

The main thing we need to do is convert our CSV to JSON, which [CSVKit](http://csvkit.rtfd.org/) can help with.

    csvjson -k "id" data/2006-2010-mn-high-crash-intersections.csv > data/2006-2010-mn-high-crash-intersections.json
    
## Visualizations

