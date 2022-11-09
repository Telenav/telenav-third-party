[//]: # (start-user-text)



[//]: # (end-user-text)

# telenav-third-party 1.5.6 &nbsp;&nbsp; <img src="https://telenav.github.io/telenav-assets/images/icons/gears-48.png" srcset="https://telenav.github.io/telenav-assets/images/icons/gears-48-2x.png 2x"/>

Merged JARs to prevent conflicts

<img src="https://telenav.github.io/telenav-assets/images/separators/horizontal-line-512.png" srcset="https://telenav.github.io/telenav-assets/images/separators/horizontal-line-512-2x.png 2x"/>

[//]: # (start-user-text)

### Releasing to Maven Central <a name = "releasing-to-maven-central"></a>

It should rarely be necessary to deploy the projects in this repository
to Maven Central, but when it becomes necessary to push a change, the
following command will build the projects and copy the result to a 
staging repository on OSSRH:

```
mvn -P release clean deploy
```

> *You must have the PGP key to sign the release or it will be rejected.*  
> 
> Contact Jonathan Locke (jon@thanlocke.com, jonathanl@telenav.com) 
> for the PGP key.

The OSSRH staging repository is at:

```
https://s01.oss.sonatype.org/
```

> Contact Jonathan Locke (jon@thanlocke.com, jonathanl@telenav.com) 
> for the username and password.

[//]: # (end-user-text)

### Sub-Projects <a name = "projects"></a> &nbsp; <img src="https://telenav.github.io/telenav-assets/images/icons/diagram-32.png" srcset="https://telenav.github.io/telenav-assets/images/icons/diagram-32-2x.png 2x"/>

[**telenav-third-party-grpc**](telenav-third-party-grpc/README.md)  
[**telenav-third-party-prometheus**](telenav-third-party-prometheus/README.md)  
[**telenav-third-party-protostuff**](telenav-third-party-protostuff/README.md)  
[**telenav-third-party-zookeeper**](telenav-third-party-zookeeper/README.md)  

<img src="https://telenav.github.io/telenav-assets/images/separators/horizontal-line-128.png" srcset="https://telenav.github.io/telenav-assets/images/separators/horizontal-line-128-2x.png 2x"/>

### Code Quality <a name = "code-quality"></a> &nbsp; <img src="https://telenav.github.io/telenav-assets/images/icons/ruler-32.png" srcset="https://telenav.github.io/telenav-assets/images/icons/ruler-32-2x.png 2x"/>

&nbsp; <img src="https://telenav.github.io/telenav-assets/images/meters/meter-0-96.png" srcset="https://telenav.github.io/telenav-assets/images/meters/meter-0-96-2x.png 2x"/> &nbsp; &nbsp; [**telenav-third-party-grpc**](telenav-third-party-grpc/README.md)  
&nbsp; <img src="https://telenav.github.io/telenav-assets/images/meters/meter-0-96.png" srcset="https://telenav.github.io/telenav-assets/images/meters/meter-0-96-2x.png 2x"/> &nbsp; &nbsp; [**telenav-third-party-prometheus**](telenav-third-party-prometheus/README.md)  
&nbsp; <img src="https://telenav.github.io/telenav-assets/images/meters/meter-0-96.png" srcset="https://telenav.github.io/telenav-assets/images/meters/meter-0-96-2x.png 2x"/> &nbsp; &nbsp; [**telenav-third-party-protostuff**](telenav-third-party-protostuff/README.md)  
&nbsp; <img src="https://telenav.github.io/telenav-assets/images/meters/meter-0-96.png" srcset="https://telenav.github.io/telenav-assets/images/meters/meter-0-96-2x.png 2x"/> &nbsp; &nbsp; [**telenav-third-party-zookeeper**](telenav-third-party-zookeeper/README.md)

[//]: # (start-user-text)



[//]: # (end-user-text)

<img src="https://telenav.github.io/telenav-assets/images/separators/horizontal-line-512.png" srcset="https://telenav.github.io/telenav-assets/images/separators/horizontal-line-512-2x.png 2x"/>

<sub>Copyright &#169; 2011-2021 [Telenav](https://telenav.com), Inc. Distributed under [Apache License, Version 2.0](LICENSE)</sub>  
<sub>This documentation was generated by [Lexakai](https://www.lexakai.org). UML diagrams courtesy of [PlantUML](https://plantuml.com).</sub>
