* This template includes a pipeline that can be submitted as a Jet Job.
* It creates a pipeline that creates one item per second and writes it to a map with the name given as an argument or my-map.
* Created items hashids are generated using: https://hashids.org/java
* And it writes sequence numbers and generated hasids into another map. Map key is the sequence number, and value is the hash ID of the sequence.

Available Placeholders:
* `Group`
* `Version`
* `MapName`
* `rootProjectName` (user defined argument)
