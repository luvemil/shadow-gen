shadow-gen
==========

Generates hashes for /etc/shadow

#Instruction

Compile with `gcc mkpass.c -o mkpass -lcrypt`.

Run with
```
./mkpass yourpass '$n$yoursalt$'
```
where n is an integer defining the hash method and yoursalt is a string.

See [post on
StackOverflow](http://stackoverflow.com/questions/11243301/change-root-password-from-script)
and
[libc/crypt](https://www.gnu.org/software/libc/manual/html_node/crypt.html).
