# Convert Farm Calendar to OpenAgri Common Semantic Model

OpenAgri Common Semantic Model is an [Agricultural Information Model](https://h2020-demeter.eu/technical-components/#aim) which is used to describe
all data used from OpenAgri services

`farm_calendar_to_jsonld.py` aims to model a generic farm_calendar json to OpenAgri Common Semantic model using a json-ld structure.

Optionally the script communicates with locally running reporting service and produces PDF reports for calendar data.

## Farm Calendar

The farm calendar json consists information reagarding the farm and its indivisual parcels. It also includes information on operations
performed on the farm like irrigation, pesticides used, fertilization, etc. YOu can find an example farm calendar json [here](../examples/generic_farm_calendar_v2.json)

## Usage

```
python3 farm_calendar_to_jsonld.py <generic_farm_calendar.json>
```

As a farm calendar you can use [generic_farm_calendar_v2.json](../examples/generic_farm_calendar_v2.json)

Run the script and follow the instructions.

To run locally the reporting service please follow this [guide](https://github.com/openagri-eu/reporting-service/blob/main/README.md)
