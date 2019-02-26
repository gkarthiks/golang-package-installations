To install th epackage `gopkg.in/inf.v0` locally in Mac, set the following

1. git config --global http.sslVerify true
1. git config --global http.https://gopkg.in.followRedirects true

else the following error will occur,

```
# cd .; git clone https://gopkg.in/inf.v0 /Users/kagovind/GODeveloper/src/gopkg.in/inf.v0
Cloning into '/Users/kagovind/GODeveloper/src/gopkg.in/inf.v0'...
fatal: unable to access 'https://gopkg.in/inf.v0/': Unknown SSL protocol error in connection to gopkg.in:-9838
package gopkg.in/inf.v0: exit status 128
```
