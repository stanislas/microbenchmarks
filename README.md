microbenmarks
=============

LinkedList vs ArrayList
-----------------------

mvn clean package && java -jar target/benchmarks.jar LinkedListVsArrayList -wi 5 -i 5 -t 1 -f 4

c.h.m.LinkedListVsArrayList.arrayListLarge        10  thrpt       20  17300255.161   267587.928  ops/s
c.h.m.LinkedListVsArrayList.arrayListLarge       100  thrpt       20   2781759.571    56645.781  ops/s
c.h.m.LinkedListVsArrayList.arrayListLarge      1000  thrpt       20    295587.926     7397.432  ops/s
c.h.m.LinkedListVsArrayList.arrayListSmall        10  thrpt       20  17791335.200   245755.759  ops/s
c.h.m.LinkedListVsArrayList.arrayListSmall       100  thrpt       20   1772545.335    23706.529  ops/s
c.h.m.LinkedListVsArrayList.arrayListSmall      1000  thrpt       20    197485.552     2127.006  ops/s
c.h.m.LinkedListVsArrayList.linkedList            10  thrpt       20  10632924.080    85256.022  ops/s
c.h.m.LinkedListVsArrayList.linkedList           100  thrpt       20   1091788.231    12115.939  ops/s
c.h.m.LinkedListVsArrayList.linkedList          1000  thrpt       20    109027.439     2270.824  ops/s
