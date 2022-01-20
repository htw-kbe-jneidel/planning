## RPC Queues

Services provides through RPC Queues

**product**

- getAllProducts()
  => product[]
- getProduct( productid )
  => product
- getAllStoreLocations()
  => storeLocation[]
- getStoreLocation( locationid )
  => storeLocation

**storage**

- getProductQuantityAtLocation( productId, locationId )
  => productQuantityAtLocation
 - getAllProductQuantitiesAtLocations()
  => productQuantityAtLocation[]

**vat-calculator**

- caculateVat( price, product category )
  => vat

**distance-calculator**

- calculateDistance( startStoreLocationCoordinates, endStoreLocationCoordinates )
  => walkingDistanceInMinutes, osmLink

## Worker Queues

**csv-export**

- createExport( product[] )
  => csvFile
