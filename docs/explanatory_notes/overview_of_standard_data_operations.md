# Standard data operations

This overview outlines some standard data operationsa and then discusses them holistically in the context of the digitial state.

## The Operations

There are a set of operations that pertain to data:

* Definition
* Audit
* Recourse
* Partition
* Create
* Read
* Update
* Delete

### Definition

This is a definition of what data the system will hold and expose and who is responsible for it.

For systems that are to be consumed as data sources it should also include details of the API by which it can be consumed.

### Audit

Data held by the state needs to be audited, maintained and, when appropriate, weeded.

Weeding in this context is different to deletion.

The process and rules of audit need to be defined as does the role of auditor.

### Recourse

Databases include and exclude by their nature - and there need to be mechanisms to enable people or organisations to appeal about the presence or absence of a record in a database.

### Partition

The state is not a homogenous body and some data elements are defined centrally but implemented in different locations. (See for example local government where the same type of data must be collected and used for different populations).

### Create

This is a normal data permission - who can create a new record and under what circumstances.

### Read

Reading is another normal data permission - and restricting people's ability to read data is essential to preserving the privacy of the citizen.

### Update

Update-in-place is a normal data permission in the private sector.

By and large it should be avoided in the public sector as incompatible with the rule of law. (Gordon Guthrie will be issuing a Working Paper addressing this issue soon.)

### Delete

This section pertains to the deletion of a data item as opposed to whole sale deletion or weeding of a set of records which is covered in Audit.

By and large it should be avoided in the public sector as incompatible with the rule of law. (Gordon Guthrie will be issuing a Working Paper addressing this issue soon.)

## Data Operations

The 8 key data operations should be considered holistically in legislation. There should be a strategy covering all of them.

When designing platforms for multiple pieces of legislation (say for instance a licensing platform) the harmonisation of data operations (particularly recourse and audit) will be the key to the design of a reusable system.

By an large we should move towards having as little data operations in legislation as possible. We should state intent - what we are trying to achieve - on the face of the bill.

Standard permissions, retention, weeding, audit and other operations should be defined in a stand alone piece of legislation which can then be refered to in numerous pieces of legislation.

But having harmony in the legislation is not enough to build a high-functioning digital state, the information that is held on data needs to including deep technical information.

It is trivial to enable state body A to use state body B's data in law. But if state body B doesn't have the appropriate infrastructure for digital sharing (indexing, APIs, a mechanism for issuing and manageing API keys and authorisation, an underlying technical platform that can be exposed to the internet, etc, etc) then this is a recipe of increasing cost, complexity and dirty data. Without the technical wherewithal documents will be printed out from system B and sent to be retyped into system A. 

Moving data out of legislation requires a trade-off tho - as access to data, reuse of it, recourse to being on or off a database are of central concern to the parliament.

Moving data concerns down the stack towards implementers and civil servants will require some oversight body that is independent of government to be set up, or civil servants given direct responsibility to parliament in the manner of Senior Responsible Officers.
