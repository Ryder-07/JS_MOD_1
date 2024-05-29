# JS_MOD_1

this repo basically holds a code for storing and printing the NFT's for a user 
Here's the explanation

create a variable to hold your NFT's.

`~const nft = [];~`

this function will take in some values as parameters, create an NFT object using the parameters passed to it for its metadata, and store it in the variable above.

```
function mint_NFT(name,uid,subject,stats_of_enrollment,date) {
    const data = {`
        name,
        uid,
        subject,
        stats_of_enrollment,
        date
    }

    nft.push(data)
}
```
create a "loop" that will go through an "array" of NFT's and print their metadata with console.log()

```
function list_NFTs(arr) {
    const array = arr
    for(let i = 0 ; i < array.length ; i++){
        console.log(array[i])
    }
}
```
print the total number of NFTs we have minted to the console.

```
function get_Total_Supply (arr) {
    return arr.length
}
```

call your functions below this line

```
mint_NFT("Rudra Pratap Singh", "21CBS1089", "AI", "allowed", "1st June 2024")
mint_NFT("Sakashi Thakur", "21CBS1072", "TOC", "Not allowed", "1st June 2024")
mint_NFT("Syed Mehdi Abbas Rezvi", "21CBS1016", "ML", "allowed", "1st June 2024")
mint_NFT("Mandhar Thakur", "21CBS1056", "AI", "Not allowed", "1st June 2024")
```
to print the number of NFTs

```
list_NFTs(nft)


console.log(get_Total_Supply(nft))
```

Thank You 

created with ❤️
