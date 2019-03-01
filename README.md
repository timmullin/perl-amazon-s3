# README

This project was been cloned from:

https://github.com/tima/perl-amazon-s3.

The project provide a Perl interface to S3.  For more details see the
README in the `dist` directory.

# Building an rpm

To build an rpm from this:

```
git clone http://gitlab.signatureinfo.net/sis/perl-Amazon-S3.git
cd perl-Amazon-S3
autoreconf -i --force
./configure
make dist
rpmbuild -tb perl-Amazon-S3-1.0.0.tar.gz
```

YMMV depending on the current version of course...

# Caveats

*Don't do a `make && make install`.  This project is just for creating
an rpm from the Perl distribution in the `dist` directory which
itself does a normal Perl build.*

# Carps & Complaint Department

bigfoot@cpan.org
