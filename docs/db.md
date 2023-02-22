### database mysql

#### nft
    id
    collecionId
    imgPath:
    creator
    desc
    holderLabel
    holderAddress
    contractAddress
    chain
    tokenId
    contentUrl
    mintHash
    mintDate
    price
    priceChange

#### nftWhaleHolders
    id
    nftId
    address
    tokenValue
    owned
    ownedPercentpage
    label

#### collectionDesc
    id
    creator
    address 
    chain
    desc
    shadowScore
    name
    whaleHolders
    holders
    mints
    24hrsValue
    24hrsValueChange
    floorPrice
    bestOffer
    uniqueHolders

#### whaleHolders
    id
    address
    tokenValue
    tokenValueChange
    label
    ccy

#### whaleHolderNfts
    id
    whaleHolderId
    imgPath
    pl7d
    label

#### collectionMintCount
    id
    collecionName
    collectionImgPath
    collectionWhaleHolders
    holders
    stars
    mintsNumber
    holdersNumber
    uniqueHolders
    totalMint
    lastMintTime


#### shadowScore
    collectionId
    value
    date

