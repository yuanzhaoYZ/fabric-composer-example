
## Auctioneer
```
{
  "$class": "org.acme.vehicle.auction.Auctioneer",
  "email": "email:0250",
  "firstName": "asleep arrow military",
  "lastName": "explain current jar tired"
}
```

## Member
```
{
  "$class": "org.acme.vehicle.auction.Member",
  "balance": 171.65,
  "email": "email:1871",
  "firstName": "frog ability",
  "lastName": "aware least park chose tropical"
}

{
  "$class": "org.acme.vehicle.auction.Member",
  "balance": 3100000.579,
  "email": "email:2026",
  "firstName": "cup boat without anyway design",
  "lastName": "distance might sing"
}

{
  "$class": "org.acme.vehicle.auction.Member",
  "balance": 13600000.851,
  "email": "email:3440",
  "firstName": "money invented had came",
  "lastName": "best throat express"
}

{
  "$class": "org.acme.vehicle.auction.Member",
  "balance": 18900000.181,
  "email": "email:4558",
  "firstName": "beside table boy",
  "lastName": "office"
}

```

## Vehicle
```

{
  "$class": "org.acme.vehicle.auction.Vehicle",
  "vin": "vin:2760",
  "owner": "email:1871"
}
```

```
{
  "$class": "org.acme.vehicle.auction.Vehicle",
  "vin": "vin:4891",
  "owner": "email:1871"
}
```

## VehicleListing
```
{
  "$class": "org.acme.vehicle.auction.VehicleListing",
  "listingId": "listingId:4814",
  "reservePrice": 123000.65,
  "description": "science limited proper camp letter",
  "state": "RESERVE_NOT_MET",
  "offers": [
    {
      "$class": "org.acme.vehicle.auction.Offer",
      "transactionId": "transactionId:1896",
      "bidPrice": 17000.261,
      "listing": "listingId:4814",
      "member": "email:1871",
      "timestamp": "1991-01-03T19:54:58.545Z"
    },
    {
      "$class": "org.acme.vehicle.auction.Offer",
      "transactionId": "transactionId:2500",
      "bidPrice": 60000.623,
      "listing": "listingId:4814",
      "member": "email:2026",
      "timestamp": "1972-01-15T15:37:59.016Z"
    },
    {
      "$class": "org.acme.vehicle.auction.Offer",
      "transactionId": "transactionId:7772",
      "bidPrice": 56000.454,
      "listing": "listingId:4814",
      "member": "email:3440",
      "timestamp": "1970-03-21T17:25:54.427Z"
    }
  ],
  "vehicle": "vin:2760"
}

```


```
{
  "$class": "org.acme.vehicle.auction.VehicleListing",
  "listingId": "listingId:5420",
  "reservePrice": 520000.459,
  "description": "save",
  "state": "RESERVE_NOT_MET",
  "offers": [
    {
      "$class": "org.acme.vehicle.auction.Offer",
      "transactionId": "transactionId:8386",
      "bidPrice": 210000.841,
      "listing": "listingId:5420",
      "member": "email:2026",
      "timestamp": "1990-10-31T04:03:42.637Z"
    },
    {
      "$class": "org.acme.vehicle.auction.Offer",
      "transactionId": "transactionId:1985",
      "bidPrice": 142000.392,
      "listing": "listingId:5420",
      "member": "email:1871",
      "timestamp": "2002-10-13T00:12:47.202Z"
    },
    {
      "$class": "org.acme.vehicle.auction.Offer",
      "transactionId": "transactionId:0110",
      "bidPrice": 60000.035,
      "listing": "listingId:5420",
      "member": "email:2026",
      "timestamp": "1990-03-24T07:28:08.213Z"
    },
    {
      "$class": "org.acme.vehicle.auction.Offer",
      "transactionId": "c50fa09c-ebef-4710-8b1d-b1c1aa3080b8",
      "bidPrice": 70000.679,
      "listing": "listingId:5420",
      "member": "email:3440",
      "timestamp": "2017-03-31T01:32:52.205Z"
    }
  ],
  "vehicle": "vin:4891"
}

```
## Transaction

### Bid
#### Under reserve price
```
{
  "$class": "org.acme.vehicle.auction.Offer",
  "bidPrice": 76.679,
  "listing": "listingId:5420",
  "member": "email:4558"
}
```

#### Beyond reserve price
```
{
  "$class": "org.acme.vehicle.auction.Offer",
  "bidPrice": 143000,
  "listing": "listingId:4814",
  "member": "email:4558"
}
```


### End the Auction
```
{
  "$class": "org.acme.vehicle.auction.CloseBidding",
  "listing": "listingId:5420"
}
```
