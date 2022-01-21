As a user, if an item is unavailable at my selected location I want to see routing info to another location that is stocking this item.

Dev Notes:
[API](https://github.com/Project-OSRM/osrm-backend/blob/master/docs/http.md) to get the walking distance between sets of coordinates.
[Link to full route](https://www.openstreetmap.org/directions?engine=fossgis_osrm_foot&route=52.5294%2C13.3976%3B52.5170%2C13.3888#map=15/52.5232/13.3932)

Example call:

```sh
curl 'http://router.project-osrm.org/route/v1/walking/13.388860,52.517037;13.397634,52.529407?overview=false' | jq
```

---
