#HDFS Schema for Data Lake

__/data__

Final transformed data is preserved here which can be consumed by different applications.

>__/ecom__

>>_/ajio_

>>>__/raw__
 
>>>Raw data ingested from different sources.<-

>>><div>
 
 ```scala
/stream
  /android
    /event
    /session
    /user
  /ios
    /event
    /session
    /user
  /web
    /event
    /session
    /user
  /searchquerylogs
/sizefitdata
```
</div>
    
>>>__/processed__

>>>__/etl__

Data generated during transformations will be persisted here. It will be periodically cleaned by garbage collector.

~~__/etld__~~

~~Data generated during transformations will be persisted here. It will be periodically cleaned by garbage collector.~~

~~__/ecom__~~

~~/ajio~~

__/users__

A scratch pad for users to develop and test. This is only part of dev environment.

```
/{user-id}
```
__/metadata__

All schema definitions and global constants will be stored here.

__/ecom__

__/ajio__

 <br>
 <br>
 
__/app__

Jar files and other artifacts etc.

__/ecom__

__/ajio__

<br>
 
__/tmp__

Accessible to everyone. For sharing data/tools between users. Periodically cleaned by garbage collector.
