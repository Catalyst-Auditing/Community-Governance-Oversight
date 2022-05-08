# Cardano Treasury with Kevin Hammond

{% embed url="https://youtu.be/yG0lifQOaFk" %}

## Overview

At an Catalyst After Town Hall of April 20th 2022, [Kevin Hammond](https://iohk.io/en/team/kevin-hammond) an IOHK Technology manager and [Jared Corduan](https://iohk.io/en/team/jared-corduan) an IOHK Software Engineering Lead answered questions about the Cardano Treasury.

### Kevin Hammond

> Kevin Hammond is a technology manager at IOHK. He has 35 years of experience in functional programming. He was a member of the Haskell Committee, produced the first Haskell compiler implementation at Glasgow University, and worked on the design and implementation of the Glasgow Haskell compiler. Kevin has produced more than 130 research publications and established an excellent reputation for his work on functional programming, types and resource analysis. He has worked for IOHK since 2019, and has been a key member of the formal methods and Cardano delivery teams.

### Jared Corduan

> Jared Corduan is a mathematician with interests in logic and computer science. He holds a PhD in mathematical logic from Dartmouth College, where he studied reverse mathematics, computability theory, infinitary combinatorics, and forcing. He is fascinated by the incompleteness phenomenon. Jared worked as an industrial programmer from 2011, both in finance and in healthcare technology, before joining IOHK in 2018. He is most excited when he gets to work on projects that combine his love of mathematics and programming.

## Questions

### Is there a Treasury Address ? How can it be queried ?

On Cardano we have addresses that are controlled by private and public keys. So Treasury has some sort of multi SIG functionality. But I've never seen a treasury address. Is it an address? Can we query it somewhere? - Filip

0:51 - Is there a Treasury Address ? How can it be queried ? - Filip

Jared Corduan

Its not an address in the usual sense. All 45 billion ADA are a part of one of what I like to call the six pots of ADA.&#x20;

The reserves in the treasury are two of those pots of ADA.&#x20;

Even though they're not technically an address, they don't show up in the UTXO set, they are not one of the unspent transaction outputs.&#x20;

There are special rules that govern it. In order to draw from the treasury, it does require quorum many signatures from the governance nodes.&#x20;

You can query the balance, if you have a running Node, there is a command line utility or Cardano. CLI that you can get the balance of the Treasury and the reserves at any time.&#x20;
