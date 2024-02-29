# SomeContract

This contract defines a structure SomeStruct and a resource SomeResource within the context of access control. The contract also provides functions with various access modifiers.
SomeStruct
Variables

    a (public, set restricted): String
    b (public): String
    c (contract restricted): String
    d (self restricted): String
# Functions

    publicFunc (public): No restrictions on access.
    contractFunc (contract restricted): Accessible only from within the contract.
    privateFunc (self restricted): Accessible only within the SomeStruct struct.
    structFunc (public): Includes comments specifying AREA 1.

# Initialization

Constructor initializes variables a, b, c, and d with values "a", "b", "c", and "d" respectively.
SomeResource
Variables

    e (public): Int

# Functions

    resourceFunc (public): Includes comments specifying AREA 2.

# Initialization

Constructor initializes variable e with the value 17.
Contract Functions

    createSomeResource (public): Creates and returns a new instance of SomeResource.
    questsAreFun (public): Includes comments specifying AREA 3.

# Initialization

Constructor initializes a variable testStruct with a new instance of SomeStruct.
