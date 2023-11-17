plugins {
    id("java")
}

group = "com.github.HighPolyNeko"
version = "1.0-SNAPSHOT"

repositories {
    mavenCentral()
}

dependencies {
    implementation(project(":db"))
    implementation(project(":service"))
}

tasks.test {
    useJUnitPlatform()
}