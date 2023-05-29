# Mind Lake Python SDK

An Python implementation for Mind Lake

## Description

The Mind Lake SDK utilizes Mind Lake's encryption storage and privacy computing capabilities to provide secure data management. 
* Mind Lake is the backbone of Mind Network. 
* All data is end-to-end encrypted at the client-side SDK side, ensuring that plaintext data never leaves the user's client. 
* Cryptographic principles ensure that only the data owner can access their own plaintext data. 
* Additionally, Mind Lake's powerful privacy computing capabilities enable the performance of calculations and querying of encrypted data.

## Getting Started

### Dependencies

* Python > 3.7
* pip
* web3
* pynacl
* colorlog (optional for logging only) 

### Installing

* pip install mindlake

### Executing program

* [quick starts](https://mind-network.gitbook.io/mind-lake-sdk/get-started)
* [more examples](https://mind-network.gitbook.io/mind-lake-sdk/use-cases)
* Step-by-step bullets
```
from mindlake import MindLake
...
```

## code
```
mind-lake-sdk-python
|-- MindLake # source code
|   |-- __init__.py
|   |-- DataLake.py
|   |-- Permission.py
|   |-- Cryptor.py
|   └-- utils.py
|-- tests # unit test code
|-- examples # use case examples
|-- README.md
└--- LICENSE

```

## Help

Full doc: [https://mind-network.gitbook.io/mind-lake-sdk](https://mind-network.gitbook.io/mind-lake-sdk) 

## Authors
 
* Dennis [@yuhaos](https://twitter.com/yuhaos)
* George [@georgemindnet](https://twitter.com/georgemindnet)

## Version History

* v1.0
    * Initial Release

## License

This project is licensed under the [MIT] License - see the LICENSE.md file for details
