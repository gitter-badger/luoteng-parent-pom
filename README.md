luoteng-parent-pom
==============

<a href="https://raw.githubusercontent.com/suetming/luoteng-parent-pom/master/LICENSE">
    <img src="https://img.shields.io/hexpm/l/plug.svg"
         alt="License: Apache 2">
</a>

Standardized set of build tool configurations for Luoteng API projects.

Motivation
-----

As the number of Luoteng API projects has grown and our code/build standards have matured.  We required a better way to share configuration across projects rather than replicate the same configuration (e.g. compiler, checkstyle, findbugs, etc.) across all of our projects.  The parent pom is intended to only provide the base configuration for plugins that we expect to be consistent throughout projects. Project specific configuration and plugins should not be included in the parent pom.

License
-------

Published under Apache Software License 2.0, see LICENSE

&copy; Luoteng Inc., 2015