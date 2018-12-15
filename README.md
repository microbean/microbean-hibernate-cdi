# microBean Hibernate CDI

[![Build Status](https://travis-ci.org/microbean/microbean-hibernate-cdi.svg?branch=master)](https://travis-ci.org/microbean/microbean-hibernate-cdi)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.microbean/microbean-hibernate-cdi/badge.svg)](https://maven-badges.herokuapp.com/maven-central/org.microbean/microbean-hibernate-cdi)

This project supplies an implementation of the
[`AbstractJtaPlatform`](https://github.com/hibernate/hibernate-orm/blob/master/hibernate-core/src/main/java/org/hibernate/engine/transaction/jta/platform/internal/AbstractJtaPlatform.java)
interface that acquires its `UserTransaction` and `TransactionManager`
implementations without using JNDI.
