# danya kolega for danya ostatki

# My name is Anton

![my img](https://icdn.lenta.ru/images/2023/01/30/14/20230130140500627/square_320_fe1384ed53cd80a7167f42341b63b345.jpeg)

I`m **JavaScript developer**. *danya skushav miu kod:*

```javascript
if(event.target["defence-filter-to"].value < 180){
        sortedPokemons = sortedPokemons.filter((pokemon)=>{
            return pokemon.stats[2].base_stat <= event.target["defence-filter-to"].value
        })
    }
    event.target['types'].forEach(function(filterType){
        if(!filterType.checked){
            sortedPokemons = sortedPokemons.filter(function(pokemon){
                for(let i in pokemon.types){
                    if(pokemon.types[i].type.name == filterType.value) return false
                }
                return true
            })
        }
    })
    redddrawSortPokemons();
})

```

My social links
* [my inst:](http://instagram.com/annuwii)
