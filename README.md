## Common ETS POM

### Purpose
This is the top-level POM for test suite projects developed as part of the 
[OGC Compliance Program](http://cite.opengeospatial.org/). Each test project 
provides an executable test suite (ETS) that can be run using a test harness 
such as [TestNG](http://testng.org/).

### Usage
An ETS project refers to the common POM as shown below.

    <project xmlns="http://maven.apache.org/POM/4.0.0">
      <parent>
        <groupId>org.opengis.cite</groupId>
        <artifactId>ets-common</artifactId>
        <version>1</version>
      </parent>
      <!-- remaining elements -->
    </project>

Any ETS project generated with the `ets-archetype-testng` archetype will 
have such a reference. Inherited elements may be overridden if desired.
