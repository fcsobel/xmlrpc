# Kveer.XmlRPC

Created unsigned version to resolve: 
[Strong name signature could not be verified](https://github.com/LordVeovis/xmlrpc/issues/28)

```
Could not load file or assembly 'Kveer.XmlRPC' or one of its dependencies. 
Strong name signature could not be verified. 
The assembly may have been tampered with, or it was delay signed but not fully signed with the correct private key. 
(Exception from HRESULT: 0x80131045)
```

This repository contains a .net library for consuming XML-RPC web services. It is a port of the Charles Cook's library mainly for .NET Core 2.x+ but target the netstandard 2.0, so it can also be used on the full .NET Framework 4.6.1+.

## How to use

As a port, very few changes have been done but the API is still the same. The documentation on the original project remains valid: [http://xml-rpc.net/][]

## Improvements

* Can/Should we use Roslyn to generate the proxy implementation of the IXmlRpcProxy interface instead of using System.Reflection?

## Legal and Licensing

This library is licensed under the [MIT license][].

[MIT license]: https://github.com/LordVeovis/xmlrpc/blob/master/LICENSE
[http://xml-rpc.net/]: https://web.archive.org/web/20210909161907/http://xml-rpc.net/
