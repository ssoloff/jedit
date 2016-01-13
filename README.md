# jedit

The jEdit application binaries

The purpose of this project is simply to publish the jEdit application binaries to a public repository so they can be easily used by plugin developers.

## Usage

For example, to publish jEdit version 5.3.0 to Bintray, use the following command:

    $ ./gradlew -Pversion=5.3.0 bintrayUpload
