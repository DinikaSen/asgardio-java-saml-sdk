# Asgardio SAML SDK for Java

The Asgardio SAML SDK for Java enables software developers to integrate SAML based SSO authentication with Java Web
 applications. The SDK is built on top of the OpenSAML library which allows Java developers to develop cross-domain
  single sign-on and federated access control solutions with minimum hassle.

## Table of Contents
- [Installing the SDK](#installing-the-sdk)
  * [Github](#github)
  * [Building from the source](#building-from-the-source)
  * [Maven](#maven)
- [Contributing](#contributing)
  * [Reporting Issues](#reporting-issues)
- [Versioning](#versioning)
- [License](#license)

## Installing the SDK

### Github
The SDK is hosted on github. You can download it from:
- Latest release: https://github.com/asgardio/asgardio-java-saml-sdk/releases/latest
- Master repo: https://github.com/asgardio/asgardio-java-saml-sdk/tree/master/

### Building from the source

If you want to build **identity-agent-sso** from the source code:

1. Install Java 8
2. Install Apache Maven 3.x.x (https://maven.apache.org/download.cgi#)
3. Get a clone or download the source from this repository (https://github.com/asgardio/asgardio-java-saml-sdk.git)
4. Run the Maven command ``mvn clean install`` from the ``asgardio-java-saml-sdk`` directory.

### Maven

Install it as a maven dependency:
```
<dependency>
    <groupId>org.wso2.carbon.identity.agent.sso.java</groupId>
    <artifactId>org.wso2.carbon.identity.sso.tomcat.server</artifactId>
    <version>5.5.5</version>
</dependency>
```
The SDK is hosted at the WSO2 Internal Repository. Point to the repository as follows:


```
<repositories>
    <repository>
        <id>wso2.releases</id>
        <name>WSO2 internal Repository</name>
        <url>http://maven.wso2.org/nexus/content/repositories/releases/</url>
        <releases>
            <enabled>true</enabled>
            <updatePolicy>daily</updatePolicy>
            <checksumPolicy>ignore</checksumPolicy>
        </releases>
    </repository>
</repositories>
```

## Contributing

Please read [Contributing to the Code Base](http://wso2.github.io/) for details on our code of conduct, and the
 process for submitting pull requests to us.
 
### Reporting Issues
We encourage you to report issues, improvements, and feature requests creating [git Issues](https://github.com/wso2-extensions/identity-samples-dotnet/issues).

Important: And please be advised that security issues must be reported to security@wso2.com, not as GitHub issues, 
in order to reach the proper audience. We strongly advise following the WSO2 Security Vulnerability Reporting Guidelines
 when reporting the security issues.

## Versioning

For the versions available, see the [tags on this repository](https://github.com/asgardio/asgardio-java-saml-sdk/tags). 

## License

This project is licensed under the Apache License 2.0 under which WSO2 Carbon is distributed. See the [LICENSE
](LICENSE) file for details.

