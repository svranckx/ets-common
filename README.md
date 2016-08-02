## Common ETS POM

### Purpose
This is the top-level POM for the conformance test suites developed as part of the 
[OGC Compliance Program](http://cite.opengeospatial.org/). Each project implements 
an executable test suite (ETS) that can be run using a test harness such as 
[TestNG](http://testng.org/).

### Usage
An ETS project refers to the common POM as shown below.

    <project xmlns="http://maven.apache.org/POM/4.0.0">
      <parent>
        <groupId>org.opengis.cite</groupId>
        <artifactId>ets-common</artifactId>
        <version>8</version>
      </parent>
      <!-- remaining POM elements -->
    </project>

Any ETS project generated from the `ets-archetype-testng` archetype will 
include such a reference. Inherited elements may be overridden if desired.
