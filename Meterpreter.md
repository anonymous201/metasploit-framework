The Meterpreter is an advanced payload that has been part of Metasploit since 2004. Originally written by Matt "skape" Miller, dozens of contributors have provided additional code, and the payload continues to be frequently updated as part of Metasploit development.

Meterpreter development occurs in a [separate repository](https://github.com/rapid7/metasploit-payloads) and the compiled results are published as part of the [metasploit-payloads gem](https://rubygems.org/gems/metasploit-payloads). Meterpreter pull requests are [[landed|Landing Meterpreter Pull Requests]] in a slightly different way compared to changes in the Metasploit Framework. For a detailed understanding of the Meterpreter architecture, please review the [development guide](https://dev.metasploit.com/documents/meterpreter.pdf).

Additional documentation about Meterpreter can be found on this wiki:
 * [[Meterpreter Reliable Network Communication]]
 * [[Meterpreter Transport Control]]
 * [[Meterpreter HTTP Communication]]
 * [[Meterpreter Timeout Control]]
 * [[Meterpreter Sleep Control]]
 * [[Meterpreter Stageless Mode]]
 * [[Meterpreter Unicode Support]]
 * [[Meterpreter Configuration]]
 * [[Payload UUID]]

Extension-specific documentation:
 * [[Python Extension]]

A wishlist of features is maintained at the [[Meterpreter Wishlist]] page.

Examples of specific use cases can also be found on this wiki:
 * [[Meterpreter Paranoid Mode]]

Those interested in the technical details of Meterpeter, along with rationale behind some of the implementations, should read the following:
 * [[The ins and outs of HTTP and HTTPS communications in Meterpreter and Metasploit Stagers]]

Got dead Meterpreter sessions? Read this: [[Debugging Dead Meterpreter Sessions]].