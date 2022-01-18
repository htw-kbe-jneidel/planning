## RPC Queues

Services provides through RPC Queues

**product**

getProducts()
  => product[]
getProduct( productid )
  => product

**storage**

getLocations()
  => location[]
getLocation( locationid )
  => location

**vat-calculator**

caculateVat( price, product category )
  => vat

**distance-calculator**

calculateDistance( locationCoords1, locationCoords2 )
  => walkingDistanceInMinutes, osmLink

## Worker Queues

**csv-export**

createExport( product[] )
  => csvFile
