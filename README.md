krmInput
========

A simple way to handle assignment delivery from my pupils. Born from my frustration at how badly the workflow is in the system my school uses. It is not ready or finish, I only collected my thouths in this README.

## Installation

Server with web and ssh and a client computers with nice software for correction task. Install __krmInput__ from binary or download source, install go and compile it.

## Use

1.  Change in config, krmInput.conf, so the server settings are correct.
2.  Create class lists, see the [example](./example-class.txt).
3.  Create password for the mebers in the class list, it will be the same password for all in the class __krmInput passwd _class-list_ __.
4.  Create new submission, __krmInput create _class-list_ _name-on-assignment_ __.
5.  Go to the folder of _name-on-assignment_ and make changes.
6.  Update the server by typing __krmInput update__.
7.  Get information about how many people have submitted and what you have done by writing __krmInput status__.
8.  Start correction of the assignments by the command __krmInput next__ or __krmInput next _nummer-of-assigment_ __.
9.  Log a comment for submission __krmInput commit_ or if you have a short comment __krmInput commit _comment-text_ __.
10. Get a list of comments by __krmInput report _name-on-assignmen_ __. Copy these into your schools official system.
