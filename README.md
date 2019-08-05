# Table of Contents

1. [Description](#description)
2. [Filename Rules](#filename-rules)
3. [TODO](#todo)
4. [Licenses Understanding](#licenses-understanding)
5. [Requirements when a Clone is performed](#requirements-when-a-Clone-is-performed)
6. [References](#references)

<a name="description"></a>
# 1. Description

This repository is used for the development of source code examples, for the tool evaluations, concept understandings and idea explorations.

<a name="filename-rules"></a>
# 2. Filename rules

The directory names are prefixed by

* **source** for the source code examples
* **tool** for the tool evaluations
* **concept** for the concept understandings
* **idea** for the idea explorations

<a name="todo"></a>
# 3. TODO

1. ~~**understand** how to automate a *ToC* deployment in the Markdown files under GitHub~~
    * not possible to automate directly
2. ~~**understand** how to automate a *References* deployment in the Markdown files under GitHub~~ [[1]](#dummy-1)
    * not possible to automate directly
3. **understand** the differences between the *licenses* proposed by GitHub
4. locally, **merge** the *sandbox* branch into the *master* one
5. locally, **rename** the sandbox branch (into *sandbox-to-export*)
6. remotely, make an **archive** of the sandbox repository
7. remotely, create a **new repository** sandbox
8. locally, make a **clone**
9. locally, **merge** the *sandbox-to-export* branch into the *sandbox* repository
10. locally, **commit** and **push** the changements

<a name="licenses-understanding"></a>
# 4. Licenses Understanding

<a name="requirements-when-a-Clone-is-performed"></a>
# 5. Requirements when a Clone is performed

1. no *subdirectory* having the **repository name**
2. add the *repository name* inside the **.gitignore** file of the embedding local repository
3. have a *makefile rule* to automate (with the proper checks) the **clone** operation
4. hale a *makefile rule* to automate (with the proper checks) the **push** operation

<a name="references"></a>
# 6. References

<a name="dummy-1"></a>[1] John Doe. 2099. *The book without title*. Dummy Publishing, not here. (notes:
This is a joke!)
