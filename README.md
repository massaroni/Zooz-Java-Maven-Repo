# Zooz Java SDK (v1) hosted maven releases
Unofficial, maven-compatible, hosted Zooz-Java releases.
See the official [Zooz-Java repository](https://github.com/Zooz/Zooz-Java), for more details.

# Gradle

repositories {
    maven { url "https://raw.github.com/massaroni/Zooz-Java-Maven-Repo/master/mvn/releases" }
}

dependencies {
    compile 'com.zooz.ecomm:ecomm-common:2.61.1.0'
}
