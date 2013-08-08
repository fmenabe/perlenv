perlenv
=======

This create a virtualenv for Perl based on local::lib. This a copy of the script
at https://bitbucket.org/jtopjian/penv/src/20bcd9049c95/penv.pl but with
possibility to change the prompt.


First you need to install local::lib package if it is not already done:
`*prompt*$ cpanp "i local::lib"`


For using environments:
    1) create a new environment:
`*prompt*$ perlenv env --prompt "myproject"`
=> This create a directory *env* in the current directory.

    2) activate the environment:
`*prompt*$ source env/bin/activate`
`(test)*prompt*$`

    3) install packages, writing scripts, ...

    4) quit environment:
`(test)*prompt*$ deactivate`
`*prompt*$`
