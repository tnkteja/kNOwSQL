# kNOwSQL

(firstthingsfirst)[]

In NOSQL we *** No Reduce*** , which translates into ***No Normalization***, only a compromise on the data modelling.

`nosql`

## First lets SQL
It is to create this reduced and elemental form from requirements-generated-data model for the Relational Database Management Systems - a Management system with a store full of tables to hold data of "same type", and relationships between them. The requirements generated data model is subject to several techniques. They are as follows and by the way in the quest for these normalisations we derive primary keys, define secondary keys, composite keys, and also super keys, ohh just not that we also create relationships and end up with a Physical ERD. ***zzz Its heaven!!***

A Logical Entity Relationship Diagram is a 
### 1NF - izing the type into table
requirements generted data model will give crude types of representations for the data. This data is atomicized. *Yay* a ***primary key*** is picked.
#### Atomization
the individual attribute containers should be holding an further unreducable value ... *** yep literally an atom like value***. Just to try an attempt to give a motivational example not to unfamiliar to when looking at the any requirements generated datamodel.

#### Primary key picking
* Probably doess not contain sensitive data
* 
*
### 2NF - izing the 1NFized table
### 3NF - izing the 2NFized table
### And BCNF - izing 
### We also have 4NF and 5NF - *if you have time*
#### 4NF - izing the 3NFized table
#### 5NF - izing the 4NFized table

`note: I want to complete these sections but the tutorial videos which put on this were lost.` :sad:
![evolution](https://highlyscalable.files.wordpress.com/2012/02/overview2.png)

#### Key-Value stores

##### LevelDB
Used in ***Google Chrome***.

##### RocksDB

After getting the rockdb [build](https://github.com/facebook/rocksdb/blob/master/INSTALL.md) + [static_lib](https://github.com/facebook/rocksdb/tree/master/examples) made  (yeah!! sucks! right!!) and up.    
#### BigTable-style 
#### Document db

### Domain-Driven Design
***immutability of Value Objects*** 

### Modelling 
Access patterns - 
## Related Work

## References
1. _https://highlyscalable.wordpress.com/2012/03/01/nosql-data-modeling-techniques/_
2. _https://www.credera.com/blog/technology-insights/java/a-managers-guide-to-nosql/_
3. _https://www.slideshare.net/alexandre_morgaut/wakanda-nosql-for-modeldriven-web-applications_
4. _http://bradley-holt.com/2011/07/addressing-the-nosql-criticism/_
5. _https://dzone.com/articles/our-experience-domain-events_
6. _https://www.slideshare.net/fehguy/data-modeling-for-nosql_
7. _https://www.kidscodecs.com/database-design/_
8. _http://www.informit.com/articles/article.aspx?p=2339664_
9. _https://www.thoughtworks.com/insights/blog/nosql-databases-overview_
10. _http://www.ebaytechblog.com/2014/10/10/nosql-data-modeling/_
11. _https://www.infoq.com/articles/unified-data-modeling-for-relational-and-nosql-databases_
12. 
