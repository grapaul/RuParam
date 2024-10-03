# RuParam
A Russian corpus for testing linguistic competence

The RuParam project has been implemented in the Lomonosov Moscow State University by Pavel Grashchenkov, Lada Pasko and Ksenia Studenikina. We are very greatful for our students, Maria Kravchuk and Daniil Burmistrov, who marked a lot of data themselves. Thanks are also due to Mikhail Tikhomirov (RCC of the Lomonosov Moscow State University) who helped us to test the data on the wide range of models.

### Current size: 9479 pairs
### Format:	id,gram,ungram,label,source,order
### String example1: 900_3,С самого начала научная деятельность Ломоносова была исключительно интенсивна.,С самого начала научная деятельность Ломоносова была исключительно интенсивен.,согл_пред_р,torfl_B2,s
### String example2: 61_1,"Что он помогал мне, когда я делал?","Он помогал мне, когда я делал пожертвования.",adj_wh_isl,RuConst,i
### "order" can be "s" (strict, gram-ungram) or "i" (inversed, ungram-gram), but this parameter is ommitted in the data for now
