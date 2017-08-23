# JavaScript SDK for Bearded Avenger (CIFv3)

The CIF Software Development Kit (SDK) for Javascript contains library code and examples designed to enable developers to build applications using CIF.

# Installation
To use the components from the CIF SDK for JavaScript, copy the contents of the **src/** directory to your local directory. Then, include the **cif.js** or **cif.min.js** file from this directory in your code.

# Examples
## Client
```javascript
<script type="text/javascript" src="cif.js"></script>

<script type="text/javascript" charset="utf-8">

    var cli = new CIFSDK({token: "1234"});
    cli.ping(function(err, success) {
        if (err) {
            throw err;
        }

        console.log("ping was successful: " + success);
    });

</script>
```
## Search
## Ping
## Submit

# License and Copyright
Copyright (C) 2017 the CSIRT Gadgets Foundation

Free use of this software is granted under the terms of the Mozilla Public License Version 2.0 (MPL2). For details see the file LICENSE included with the distribution.