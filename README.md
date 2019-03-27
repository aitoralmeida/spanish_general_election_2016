# Political party and candidate tweets for the campaign period of the 2016 Spanish general election
This dataset contains the political party and candidate tweets for the campaign period (10th to 24th of June) of the 2016 Spanish general election (https://en.wikipedia.org/wiki/Spanish_general_election,_2016).

The 2016 Spanish general election was held on Sunday, 26 June 2016, to elect the 12th Cortes Generales of Spain. All 350 seats in the Congress of Deputies were up for election, as well as 208 of 266 seats in the Senate.

The dataset contains 35,624 tweets with the following distribution:

| Screen_name   | Number of tweets  |
| ------------- | -----:|
|compromis|898| 
|sanchezcastejon|690| 
|PPopular|1905| 
|iunida|4253| 
|eajpnv|852| 
|tone_corunha|168| 
|UnidadPopular__|1270| 
|coalicion|1916| 
|ConvergenciaCAT|1280| 
|CiudadanosCs|1943| 
|vox_es|738| 
|ForoAsturias|31| 
|marianbeitia|255| 
|komaur|112| 
|Nueva_Canarias|834| 
|Albert_Rivera|705| 
|geroabai|652| 
|obloque|948| 
|En_Marea|1300| 
|anioramas|283| 
|Esquerra_ERC|1512| 
|ehbildu|1123| 
|Herzogoff|183| 
|ahoraencomun|22| 
|gabrielrufian|360| 
|UPYD|1119| 
|CatalunyaSi|10| 
|carloscallon|500| 
|Pablo_Iglesias_|121| 
|agarzon|348| 
|marianorajoy|769| 
|AITOR_ESTEBAN|32| 
|unio_cat|115| 
|ahorapodemos|3822| 
|PSOE|4399| 
|franceschoms|156|

## Format

The file is formatted with a tweet per line, each line with the following fields separated by commas:

```
tweet_id, username, md5_hash
```

The tweet_id and the username can be used to recover the tweet content, and the md5 hex hash to validate the tweet text. To comply with the Twitter TOS we do not provide the content ourselves.

## Reference

Please, use the following reference if you use this dataset for your research:

Bilbao-Jayo, A., & Almeida, A. (2018). Automatic political discourse analysis with multi-scale convolutional neural networks and contextual data. International Journal of Distributed Sensor Networks, 14(11), 1550147718811827.

Aitor Almeida, Pablo Orduña, Aritz Bilbao. 
Party and candidate tweets for the campaign period of the 2016 Spanish general election. 
URL: https://github.com/aitoralmeida/spanish_general_election_2016/

## Other datasets

Take a look at our other datasets:
* City4Age Behaviour dataset: https://zenodo.org/record/2602652#.XJtz26SkGUl
* Spanish 3B words Word2Vec Embeddings: https://zenodo.org/record/1155474#.XJt0K6SkGUk
*  Political party and candidate tweets for the campaign period of the 2015 Spanish general election: https://github.com/aitoralmeida/spanish_general_election_2015
* Tweets for the campaign period of the 2014 European Parliament election: https://github.com/aitoralmeida/european_parliament_election_2014

