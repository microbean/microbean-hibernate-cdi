# microBean Hibernate CDI

This project supplies an implementation of the
[`AbstractJtaPlatform`](https://github.com/hibernate/hibernate-orm/blob/master/hibernate-core/src/main/java/org/hibernate/engine/transaction/jta/platform/internal/AbstractJtaPlatform.java)
interface that acquires its `UserTransaction` and `TransactionManager`
implementations without using JNDI.
