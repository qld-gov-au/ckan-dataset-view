## Ckan Dataset View

This is an example of looking at OpenData and Publications by Organisation in a tabular form

To see the html visit https://qld-gov-au.github.io/ckan-dataset-view/

It calls
https://www.data.qld.gov.au/api/3/action/organization_list?all_fields=true&rows=10000&sort=name+asc
and once an org has been picked

https://www.data.qld.gov.au/api/action/package_search?q=owner_org%3A93f12747-9561-4980-bcfd-46b9e5cc51c7+&rows=10000&sort=metadata_created+desc
