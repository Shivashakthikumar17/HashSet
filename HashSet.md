Hashset is a data structure used to strore values without duplicate.
Order not maintained / If you want to maintain the order means go with LinkedHashset.
allows one null value
Its not a thread Safe / If you want to achieve thread safe means go with concurrentHashMap.newKeySet().
Based on the hashcode its define the bucket / In bucke we are using .equals to find the duplicates.
Initially it has 16 buckets
