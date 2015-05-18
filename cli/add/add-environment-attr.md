## add environment attr

### Usage

`stack add environment attr {environment} {attr} {value} [attr=string] [value=string]`

### Description

Adds an attribute to an environment and sets the associated values

### Arguments

* `{environment}`

   Name of environment

* `{attr}`

   Name of the attribute

* `{value}`

   Value of the attribute


### Parameters
* `[attr=string]`

   same as attr argument
* `[value=string]`

   same as value argument

### Examples

* `stack add environment attr test sge False`

   Sets the sge attribution to False for test nodes


