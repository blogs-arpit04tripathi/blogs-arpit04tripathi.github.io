---
layout: post
title: Hibernate
permalink: /:collection/hibernate/
---

- [Hibernate Introduction](introduction)
- [ORM (Object Relational Mapping)](orm)
  - [Why ORM?](orm/why)
  - [Problems ORM Solves](orm/problems-solved)
- [Hibernate vs JDBC](hibernate-vs-jdbc)
- [Hibernate Architecture](architecture)
- [Setup Hibernate](setup)
  - xml
    - [Hibernate Configuration File](config-file)
    - [Hibernate Mapping File](mapping-file)
  - properties and annotation
    - [Hibernate Properties](properties)
    - [Hibernate Mapping](mapping)
    - [Hibernate mapping Annotations](mapping-annotations)
- [Understanding Associations with Example](associations)
  - [Association managed by both entities](associations/both-entities)
  - [Association managed by single entity](associations/single-entity)
  - [Associations for Various Mappings](associations/various-mappings)
- [JPA 2 Annotations](annotations)
  - [@Entity](annotations/entity)
  - [Primary Keys with @Id and @GeneratedValue](annotations/id)
  - [@TableGenerator](annotations/table-generator)
  - [@Id, @IdClass, or @EmbeddedId (Compound Primary Keys)](annotations/embedded-id)
  - [@Table and @SecondaryTable](annotations/table)
  - [@Basic](annotations/basic)
  - [@Transient](annotations/transient)
  - [@Column](annotations/column)
  - [@Temporal](annotations/temporal)
  - [@ElementCollection](annotations/element-collection)
  - [@Lob](annotations/lob)
  - [@MappedSuperclass](annotations/mapped-super-class)
  - [@OrderColumn](annotations/order-column)
  - [@NamedQuery and @NamedQueries](annotations/named-query)
  - [@NamedNativeQuery and @NamedNativeQueries](annotations/named-native-query)
  - [@Immutable](annotations/immutable)
  - [@NaturalId](annotations/natural-id)
    - [Composite Natural ID](annotations/composite-natural-id)
- [Modeling Entity Relationships/Associations](er-relationship)
  - [One to One Mapping](mapping/one-to-one)
  - [One to Many Mapping](mapping/one-to-many)
  - [Many to Many Mapping](mapping/many-to-many)
- [JPA Cascading](jpa-cascade)
  - [JPA Cascade Types](cascade/types)
    - [Orphan Removal](cascade/orphan-removal)
  - [Hibernate Cascading](cascade)
- [Mapping Inheritance Hierarchies](inheritance)
  - [SINGLE_TABLE Strategy (Table Per Hierarchy)](table-per-hierarchy)
  - [TABLE_PER_CLASS Strategy (Table Per Concrete class )](table-per-class)
  - [JOINED Strategy (Table Per Subclass)](table-per-subclass)
- [SessionFactory and Session](session-factory)
- [Lazy Loading](lazy-loading)
  - [Get Data by Lazy Loading](lazy-loading/get)
  - [Hibernate lazy loading – why we need it?](lazy-loading/why)
  - [How lazy loading solve above problem](lazy-loading/problems-solved)
  - [How to enable lazy loading in hibernate](lazy-loading/how-to-enable)
  - [How lazy loading works in hibernate](lazy-loading/how-it-works)
  - [Effect of lazy loading on detached entities](lazy-loading/effect-on-detached-entities)
- [Entity / Persistence LifeCycle States](persistence/lifecycle)
  - [Transient Object](persistence/transient)
  - [Persistent Object](persistence/persistent)
  - [Detached Object](persistence/detached)
  - [Removed Object](persistence/removed)
  - [CRUD (Create / Read / Update / Delete)](persistence/crud)
  - [Detached to Persistent](persistence/detached-to-persistent)
  - [Equality](persistence/equality)
- [Hibernate Collections](collections)
  - [BLOB](blob-data)
- [Hibernate Queries](queries)
  - [Native SQL](queries/native-sql)
  - [SQL Injection](queries/sql-injection)
  - [Named Query](queries/named-queries)
- [Hibernate HQL](hql)
  - [HQL Update](hql/update)
  - [HQL Delete](hql/delete)
  - [HQL Insert](hql/insert)
  - [HQL Select](hql/select)
  - [HQL – from clause and aliases](hql/from)
  - [HQL select clause and projection](hql/projection)
  - [HQL Named Parameters](hql/named-params)
  - [HQL – Paging Through the ResultSet](hql/paging)
  - [HQL – Get a Unique Result](hql/unique-result)
  - [HQL – Sorting Results with the ‘order by’ clause](hql/order-by)
  - [HQL Aggregate Methods](hql/aggregate)
  - [HQL – Enable Logs and Comments](hql/log-and-comments)
- [Criteria Queries](hql/criteria-queries)
  - criteria – using Restrictions
    - [Basic Restrictions](hql/criteria/basic-restrictions)
    - [Comibining Restrictions](hql/criteria/combining-restrictions)
    - [Using Disjunction Objects with Criteria](hql/criteria/disjoint)
    - [sqlRestriction()](hql/criteria/sql-restriction)
  - [paging through the result set](hql/criteria/paging)
  - [Obtain unique result](hql/criteria/unique-result)
  - [obtain distinct results](hql/criteria/distinct)
  - [sort query results](hql/criteria/sort)
  - [perform associations (joins)](hql/criteria/joins)
  - [projections and aggregates](hql/criteria/aggregation)
  - [query by example (QBE)](hql/criteria/query-by-example)
- [Hibernate Cache](cache)
  - [First Level Cache](cache/first-level)
  - [Second Level Cache](cache/second-level)
  - [Caching Strategies](cache/strategies)
  - [Steps For Enabling Cachce](cache/enable-steps)
- [Hibernate Transaction Management](transaction-management)
- [Hibernate C3P0 Connection Pool](connection-pool)
- [Hibernate Validations](validations)
  - [Validation annotations](validations/annotations)
- [Hibernate - Misc](misc)
- [n+1 select problem](n+1-select-problem)
- [Store Procedure Call](stored-procedure-call)
