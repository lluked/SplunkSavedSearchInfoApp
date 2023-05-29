# Saved Search Info App

Runs a scheduled search `SavedSearchesInfoApp-SignaturesLookupGenerator` to collate information about savedsearches and output to a lookup `SavedSearchesInfo-SignatureLookup`.

`SavedSearchesInfoApp-SignaturesLookupGenerator` needs to be run before the dashboards work.

Results are filtered with the `SavedSearchesInfo-SignaturesLookupFilter` filter.

Information is then viewable through this app.

## Requirements

- [MITRE ATT&CK Heatmap for Splunk](https://splunkbase.splunk.com/app/5742)
- [DA-ESS-ContentUpdate](https://splunkbase.splunk.com/app/3449)
