# Dockerfile: Ubuntu Noble, Qt 6.4

Docker image for building and testing of Qt 6 applications.

Image configuration:
- Ubuntu Noble (24.04)
- Python 3.12.2
- Qt 6.4.2
	- qmake6
	- qt6-base-dev
	- qt6-base-dev-tools
	- qt6-documentation-tools
	- qt6-declarative-dev
	- qt6-declarative-dev-tools
	- qt6-image-formats-plugins
	- qt6-l10n-tools
	- qt6-translations-l10n
- GCC/G++ 13.2.0
- CMake 3.28.3
- Conan 2.9.3
- Qbs 2.1.2 (default profile: qt-6-4-2-bin)
- Doxygen 1.9.8
- gcovr 7.0
- lcov 2.0
- coverxygen 1.8.1
- Tags files for Qt 6.4.2 (to link in Doxygen documentation)
- OpenJDK 17 JRE
- SonarQube Scanner 6.1.0.4477 (located at `/opt/sonar-scanner`)


### Other Versions ###
See the [Ubuntu Qt Version Table](https://github.com/j-ulrich/docker_qt/wiki/Ubuntu-Qt-Version-Table) in the project
wiki for an overview of the provided Ubuntu versions along with the corresponding Qt version.