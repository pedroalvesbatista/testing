## chkcomp

Checks hardware compability in RHEL databases, as well drives from external sources like linux-drivers.org

## Installing 

To install `chkcomp`, you must run :

```
git clone github.com/pedroalvesbatista/chkcomp
```  

Then, run `make` utilities :

``` 
make
```


```
sudo make install
```  

## Getting started

`chkcomp` will make some consultations with `dmidecode` to get your hardware information, parse it and then compare with the returned results from the database, via `chkcomp_scraping` package.

