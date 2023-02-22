### API
#### collections
post /collections
[{
    id
    collectionImg: './././'
    name
    holders
    whaleHolers
    mint
    24hrsValues:{
        count
        percentChange
    }
    floorPrice
    BestOffer
    shadowScore: [1,2,3,4,5,6,7]
    uniqueHolders
    stars
}]



#### whale Holders top 100
post /whaleHolders
[{
    id
    address
    tokenValue{
        ccy: 'ETH',
        totalValue: 10000000000.00,
        percentChange: 0.0248
    }
    holdNfts: {
        totalValue: 1223,
        imgs: [
            '/s/d',
            '',
            '',
            ''
        ]
    }
    holdCollections: {
        totalValue: 232,
        imgs: [
            '/s/d',
            '',
            '',
            ''
        ]
    }
    7dPL: 2333,
    label
}]

#### hotNfts
post /nfts
[{
    id
    name

}]


#### twitter Explore mock
post /twitter/explore
['tama', 'pink','dps']

#### host exponent mock
[{
    date: 16900000,
    score: 30
},
{
    date: 16900000,
    score: 30
}]


#### collection
get /collections/:id
{
    id
    name
    address
    chain
    desc
    shadowScore: {
        price
        whaleHold
        volume
        tnxs
    }
    totalPrice {
        value: 1000
        ccy: ETH
        percentChange: 0.0248
    }
    totalHolders {
        value: 1000
        percentChange: 0.0248
    }
    totalWhaleHolders {
        value: 1000
        percentChange: 0.0248
    }
    totalTxns{
        value: 1.29
        ccy: eth
        percentChange: 0.0248
    }
    trading {
        price: [
            {
                price 80
                time 180
                ccy: eth
            }
        ]
        volume: [
            {
                time: 16900000
                value: 400
            }
        ]
        list: [{
            time: 16900000
            value: 800
        }]
        tnxs: [
            {
                time: 16900000,
                value: 100
            }
        ]
    }
}

#### collection nfts
post /collections/:id/nfts

[{
    name
    imgPath: '././'
    price: {
        ccy: eth
        price: 0.1111
    }
}]