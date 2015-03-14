JType
=====

Java 5 introduced a richer type system for generics with [Type](http://java.sun.com/j2se/1.5.0/docs/api/java/lang/reflect/Type.html) and its various subtypes, but lacks any easy way to perform common operations on these types.  JType aims to fill this gap.

Features
--------

  * A factory to easily create implementations of the various type interfaces.

  * Methods to compare and manipulate type instances, such as checking whether a type is a subtype of another.

  * A generic type literal that provides an equivalent of class literals for types.

Getting started
---------------

To start using JType in a [Maven](http://maven.apache.org/) project, add the following dependency to the POM:

	<project>
		...
		<dependencies>
			<dependency>
				<groupId>com.googlecode.jtype</groupId>
				<artifactId>jtype</artifactId>
				<version>0.1.3</version>
			</dependency>
		</dependencies>
		...
	</project>

JType is deployed to [Sonatype's OSS Repository](http://oss.sonatype.org/) and synced with the [Maven Central Repository](http://search.maven.org/), so no repository definitions are required.
