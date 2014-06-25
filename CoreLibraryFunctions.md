
| Function   | Comment   | List      | Array     | Seq      | Map         | Set         |
|:-----------|:----------|:---------:|:---------:|:--------:|:--------:|:--------:|
| append	 	 |           |     o     |    o      |    o     |          |          |
| average	 	 |           |      o    |        o  |      o   |          |          |
| averageBy	 |           |    o      |      o    |    o     |          |          |
| blit	 	 	 |           |     n/a   |   o   |   n/a    |          |          |
| cache	 	 	 |           |    n/a    |    n/a    |   o      |          |          |
| cast	 	 	 |           |   n/a     |   n/a     |   o      |          |          |
| choose	 	 |           |   o       |     o     |   o      |          |          |
| collect	 	 |           |  o        |      o    |      o   |          |          |
| compareWith|           |  ADD     |     ADD   |     o    |          |          |
| concat	 	 |           |     o     |       o   |     o    |          |          |
| copy	 	 	 |           |   n/a     |     o   |     n/a  |          |          |
| countBy	 	 |           |  ADD     |     ADD  |      o   |          |          |
| create	 	 |           |   ADD    |      o    |    ADD   |          |          |
| delay	 	 	 |           |    n/a    |    n/a    |    o   |          |          |
| distinct	 |           |   ADD     |     ADD   |     o    |          |          |
| distinctBy |           |    ADD    |    ADD    |    o     |          |          |
| empty	 	 	 |           |    o      |    o      |      o   |          |          |
| exactlyOne |           |    ADD    |    ADD    |        o |          |          |
| exists	 	 |           |     o     |       o   |     o    |          |          |
| exists2	 	 |           |    o      |        o  |      o   |          |          |
| fill	 	 	 |           |   n/a     |     o     |     n/a  |          |          |
| filter	 	 |           |   o       |     o     |     o    |          |          |
| find	 	 	 |           |   o       |     o     |     o    |          |          |
| findIndex	 |           |  o        |      o    |      o   |          |          |
| fold	 	 	 |           |     o     |     o     |     o    |          |          |
| fold2	 	 	 |           |           |           |          |          |          |
| foldBack	 |           |           |           |          |          |          |
| foldBack2	 |           |           |           |          |          |          |
| forall	 	 |           |           |           |          |          |          |
| forall2	 	 |           |           |           |          |          |          |
| get	       | “get i” same as “nth (i + 1)” ?	 	 	 |           |           |           |          |          |          |
| groupBy	 	 |           |           |           |          |          |          |
| head	 	 	 |           |           |           |          |          |          |
| init	 	 	 |           |           |           |          |          |          |
| initInfinite |           |           |           |          |          |          |
| isEmpty	 	 	 |           |           |           |          |          |          |
| iter	 	 	 	 |           |           |           |          |          |          |
| iter2	 	 	 	 |           |           |           |          |          |          |
| iteri	 	 	 	 |           |           |           |          |          |          |
| iteri2	 	 	 |           |           |           |          |          |          |
| last	 	 	 	 |           |           |           |          |          |          |
| length	 	 	 |           |           |           |          |          |          |
| map	 	 	 	   |           |           |           |          |          |          |
| map2	 	 	 	 |           |           |           |          |          |          |
| map3	 	 	 	 |           |           |           |          |          |          |
| mapi	 	 	 	 |           |           |           |          |          |          |
| mapi2	 	 	 	 |           |           |           |          |          |          |
| max	 	 	 	   |           |           |           |          |          |          |
| maxBy	 	 	   |           |           |           |          |          |          |
| min	 	 	 	   |           |           |           |          |          |          |
| minBy	 	 	 	 |           |           |           |          |          |          |
| nth	 	 	 	   |           |           |           |          |          |          |
| ofArray	 	 	 |           |           |           |          |          |          |
| ofList	 	 	 |           |           |           |          |          |          |
| ofSeq	 	 	 	 |           |           |           |          |          |          |
| pairwise	 	 |           |           |           |          |          |          |
| partition	 	 |           |           |           |          |          |          |
| permute	 	 	 |           |           |           |          |          |          |
| pick	 	 	 	 |           |           |           |          |          |          |
| readonly	 	 	 	 |           |           |           |          |          |          |
| reduce	 	 	 	 |           |           |           |          |          |          |
| reduceBack	 	 	 	 |           |           |           |          |          |          |
| replicate	| Similar to ‘copy’	 	 	 |           |           |           |          |          |          |
| rev	 	 	 	 |           |           |           |          |          |          |
| scan	 	 	                                             	 |           |           |           |          |          |          |
| scanBack	 	 	 	 |           |           |           |          |          |          |
| set	 	 	 	 |           |           |           |          |          |          |
| singleton	 	 	 	 |           |           |           |          |          |          |
| skip	 	 	 	 |           |           |           |          |          |          |
| skipWhile	 	 	 	 |           |           |           |          |          |          |
| sort	 	 	 	 |           |           |           |          |          |          |
| sortBy	 	 	 	 |           |           |           |          |          |          |
| sortInPlace	 	 	 	 |           |           |           |          |          |          |
| sortInPlaceBy	 	 	 	 |           |           |           |          |          |          |
| sortInPlaceWith	 	 	 	 |           |           |           |          |          |          |
| sorthWith	 	 	 	 |           |           |           |          |          |          |
| sub	 	 	 	 |           |           |           |          |          |          |
| sum	 	 	 	 |           |           |           |          |          |          |
| sumBy	 	 	 	 |           |           |           |          |          |          |
| tail	| ‘tail’ usually indicates a list, but I’ve seen this called ‘rest’ in other languages, a dedicated version of “skip 1”	 	 	  |           |           |           |          |          |    
| take	 	 	 	 |           |           |           |          |          |          |
| takeWhile	 	 	 	 |           |           |           |          |          |          |
| toArray	  |           |           |           |          |          |          |
| toList	 |           |           |           |          |          |          |	 	 	         
| toSeq	 	 	 |           |           |           |          |          |          |
| truncate	 	 	 	 |           |           |           |          |          |          |
| tryFind	 	 	 	 |           |           |           |          |          |          |
| tryFindIndex	 	 	 	 |           |           |           |          |          |          |
| tryPick	 	 	 	 |           |           |           |          |          |          |
| unfold	 	 	 	 |           |           |           |          |          |          |
| unzip	 	 	 	 |           |           |           |          |          |          |
| unzip3	 	 	 	 |           |           |           |          |          |          |
| where	| Same as ‘filter’	 	 	 |           |           |          |          |          |
| windowed	 	 	 	 |           |           |           |          |          |          |
| zeroCreate	 	 	 	 |           |           |           |          |          |          |
| zip	 	 	 	 |           |           |           |          |          |          |
| zip3	 	 	 	 |           |           |           |          |          |          |