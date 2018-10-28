# sal README

SALL language extension

## Features

* Syntax highlighting for .SAL language files.
* snippets to assist development

## Release Notes

### 0.1.0

Initial release of SALL language extension

## SALL Snippets

| Trigger     | Snippet                                      |
| ----------- | -------------------------------------------- |
| sall        | Boilerplate code                             |
| bf          | Boolean function                             |
| sgopen      | check switchgear open (where indication is comprised of two bits: name**_O** - open bit, name**_C** - close bit) |
| sgclosed    | check switchgear closed (where indication is comprised of two bits: name**_O** - open bit, name**_C** - close bit) |
| sgindete    | check switchgear indeterminate (where indication is comprised of two bits: name**_O** - open bit, name**_C** - close bit) |
| sginvalid   | check switchgear invalid (where indication is comprised of two bits: name**_O** - open bit, name**_C** - close bit) |
| seton       | set indication on                            |
| setoff      | set indication off                           |
| h2l         | check for high to low transition             |
| l2h         | check for low to high transition             |
| outputpulse | issue output control of type PULSE           |
| outputtrip  | issue output control of type TRIP            |
| outputclose | issue output control of type CLOSE           |
| airaw       | retrieve counts of ai                        |
| ai=         | check ai is equal to a value                 |
| ai>         | check ai is greater than a value             |
| ai<         | check ai is less than a value                |
| ai<=        | check ai is less than or equal to a value    |
| ai>=        | check ai is greater than or equal to a value |


![Boilerplate example](https://github.com/Zix44/vscode-sall-lang/blob/master/images/SALL_Boilerplate_more.gif)