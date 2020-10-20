# PHP UUID Generator
The following class generates VALID RFC 4211 COMPLIANT Universally Unique IDentifiers (UUID) version 3, 4 and 5.

Version 3 and 5 UUIDs are named based. They require a namespace (another valid UUID) and a value (the name). Given the same namespace and name, the output is always the same.

Version 4 UUIDs are pseudo-random.

UUIDs generated below validates using OSSP UUID Tool, and output for named-based UUIDs are exactly the same. This is a pure PHP implementation.

### Purpose, License & Credit
This is educational purpose which is free of licenses. You can implement, and or distribute this code. All credit on behalf [Andrew Moore](https://www.php.net/manual/en/function.uniqid.php#94959)
