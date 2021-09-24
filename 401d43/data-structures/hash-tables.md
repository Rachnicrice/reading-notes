# Hash Tables

## WHAT

A Hash Table is a data structure comprised of key value pairs. A hash code is used as a key and values are stored into respective buckets or arrays.

## HOW

Use a hash function to create unique indexes for each key (aka a hash code), and then input the value into a bucket or array at that hash code index.

## WHY

A hash table is optimal for insertion and lookup as these are both 0(1) operations. However it is not optimal for searching and/or for maintaining ordered data. 