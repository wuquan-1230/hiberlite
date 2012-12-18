C++ to Sqlite ORM

USAGE: just compile and link all files under src/ to your project.
Add 
    #include "hiberlite.h" 
to your code.


C++ object-relational mapping with API inspired by the Boost.Serialization - that means almost no API to learn.

In contrast to most serialization libraries with SQL serializers, C++ objects mapped with hiberlite behave similar to active record pattern - you are not forced to follow the "read all your data/modify some small part/write everything back" path.

For people who need reliable data storage, ACID transactions, simple random-access to their data files, and don't like coding in SQL.

