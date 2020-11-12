# Install Nexus Repository Manager using Ansible.

The purpose of this repository is to anxiously provision the installation and configuration of the Nexus Repository Manager stack.

## Binary and Build Artifact Control Across Your Software Supply Chain

Sonatype Nexus is a popular repository manager used worldwide for most of the components, binaries, and build artifacts. It comes with support for the Java Virtual Machine (JVM) ecosystem, including Gradle, Ant, Maven, and Ivy.

Compatible with standard tools including Eclipse, IntelliJ, Hudson, Jenkins, Puppet, Chef, Docker, etc., Sonatype Nexus repo can manage dev components through delivery for the binaries containers, assemblies, and finished goods.

## Universal Support for all Popular Build Tools

- Store and distribute Maven/Java, npm, NuGet, Helm, Docker, P2, OBR, APT, GO, R, Conan components and more.
- Manage components from dev through delivery: binaries, containers, assemblies, and finished goods.
- Awesome support for the Java Virtual Machine (JVM) ecosystem, including Gradle, Ant, Maven, and Ivy.
- Compatible with popular tools like Eclipse, IntelliJ, Hudson, Jenkins, Puppet, Chef, Docker, and more.

Official Site: https://www.sonatype.com/nexus/repository-oss

Help Documents: https://help.sonatype.com/repomanager3


## Pre-Requirements

- Minimum CPUs: 4, Recommended CPUs: 8+
- Minimum physical/RAM on the host 8GB
- Lvm volume for the **/opt/nexusdata** partition with a minimum of 50GB

## Configure proxy before run ansible-playbook

Edit file playbook.yml with internal proxy settings

## Installation
```ansible-playbook -i inventory/hosts playbook.yml```
