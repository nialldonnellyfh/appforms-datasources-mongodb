# Feedhenry Sample Service Using MongoDB Data for Datasources

This is a sample RESTful service to load a list of **Assets** stored in a MongoDB database that is properly formatted as a Data Source.

The endpoint can be found at `/assets`

The assets are pre-populated when the service first starts.  They can also be edited in the Data Browser.

An example of the Data Sources format is below:

    [
        {
            "key": "some_key",
            "value": "some_value"
        }
    ]

You can also choose which item is to be selected by default by adding the "selected" property


    [
        {
            "key": "some_key",
            "value": "some_value"
        },
        {
            "key": "other_key",
            "value": "other_key",
            "selected": true
        }
    ]

