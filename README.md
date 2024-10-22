# Database-Notes-Hub
Notes from University of Messina 2nd year Data Analysis Student

The Relational Model

1. Introduction

	•	The relational model was proposed by E. F. Codd in 1970 to promote data independence.
	•	It was adopted in commercial Database Management Systems (DBMS) in 1981.
	•	The model is based on the mathematical concept of relations, which are represented by tables.

2. Key Concepts

	•	Logical Data Models:
	•	Traditional models: Hierarchical, Network, Relational.
	•	Relational model is a higher-level abstraction, with data represented only through values (no pointers).
	•	Mathematical Relations:
	•	Defined by the Cartesian product of domains.
	•	A relation is a subset of the Cartesian product.
	•	Terms:
	•	Degree: Number of attributes in the relation.
	•	Cardinality: Number of tuples.

3. Properties of Relations

	•	Relations are represented as sets of ordered n-tuples.
	•	The ordering is based on the domains, and each domain’s position determines the attribute.

4. Tabular Representation

	•	In relational models, tables represent relations.
	•	Columns represent attributes, and rows represent tuples (data instances).

5. Formalizing Relations

	•	Attributes correspond to the domains.
	•	A tuple is a function that maps attributes to domain values.
	•	A relation is a set of such tuples.

6. Keys and Constraints

	•	Keys:
	•	A set of attributes that uniquely identifies tuples in a relation.
	•	Primary Key: A key where null values are not allowed.
	•	Referential Integrity:
	•	Ensures that foreign keys reference valid tuples in other tables.

7. Advantages of the Relational Model

	•	Independence from physical data structures.
	•	Easy data transfer between systems.
	•	Data references are made through values, not physical pointers.

8. Conclusion

	•	The relational model’s flexibility and simplicity made it a fundamental aspect of modern databases.
	•	It remains a central model in database theory and practice, especially with relational databases like MySQL, PostgreSQL, and SQL Server.
