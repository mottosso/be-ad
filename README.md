![image](https://cloud.githubusercontent.com/assets/2152766/8331931/e261ffba-1a82-11e5-97f5-c77ca5dd71b2.png)

A `be` project preset for advertisements.

<br>
<br>
<br>

### Introduction

This preset defines a generic set of patterns common in the production of animated advertisements. It is provided as a foundation from which to build more complex configuration more suitable to your particular environment.

### Content

A skeleton is provided with the template that looks like this.

```bash
$ tree
└── project
    ├── assets
    ├── shots
    └── shared
        └── scripts
```

Upon entering the project, a development directory will be created corresponding to the 2 types of inventory items - `asset` and `shot`.


```bash
$ be in myproject myasset mytask --enter
$ tree
├── assets
│   └── myasset
│       └── mytask
├── shots
└── shared
```

The shared directory is where production and content creators unite and share information, such as deliverables.