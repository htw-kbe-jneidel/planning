## Queues

**gateway**

locations()
  => location[]
location( locationid )
  => location
products()
  => product[]
product( productid )
  => product

**vat-calculator**

caculateVat( price, product category )
  => vat

**distance-calculator**

calculateDistance( locationCoords1, locationCoords2 )
  => walkingDistanceInMinutes, osmLink

**storage**

locations()
  => location[]
location( locationid )
  => location

**product**

products()
  => product[]
product( productid )
  => product

**csv-export**

createExport( product[] )
  => csvFile
