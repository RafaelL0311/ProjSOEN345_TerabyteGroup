# ProjSOEN345_TerabyteGroup


## App RunnerUp - Rafael

#### Ease of use: Have you successfully compiled and executed the app?
Yes. We were able to compile and run it, although it proves slightly awkward to run as it needs GPS and tracks position.

#### Existing Tests: Does the project contain any test cases?
Not many. The current tests seem to be old, from 2017 and 2021.


#### How many stars does the project have on GitHub? (1 point)
958 Stars at this moment.

#### Is the project available for download in Google Play? If yes, what is the number of downloads in Google Play? If no, give any data that shows the popularity of the app (for example, is it available in F-Droid?) 
Over 50k downloads in PlayStore

#### Actively Maintained: When was the latest commit to the project?
The project has been updated recently, with 71 releases, with the last one being in February of this year. 

#### Likelihood of finding new bugs: How many bug-related (e.g., with label “bug”) GitHub issues does the project have? The more issues a project has, the more likely it has bugs (but if most of these issues have not been resolved/closed, it may mean that the developers of the project usually are not active in resolving the issues).

There are currently 200 issues open, with about 400 more closed. While they aren't tagged, it seems as at least 30%-50% of them are bugs. 

#### What are the lines of code (LoC) in the project?
Repository jonasoreland/runnerup has 77,744 lines of code.

Measured with https://g--3e1749b2278111f0b46e569c3dd06744.web.val.run/gh/jonasoreland/runnerup.

## App FreeOTP - Mohamed

#### Ease of use: Have you successfully compiled and executed the app?
Yes. I compiled FreeOTP with Gradle and ran it on an Android emulator.

#### Existing Tests: Does the project contain any test cases?
Yes. The app is Java, and it has 11 instrumented tests under `mobile/src/androidTest`. They use JUnit and cover token persistence, the keystore, and the RFC 4226 and RFC 6238 one-time-password test vectors.

#### How many stars does the project have on GitHub?
1,676 stars on October 9, 2026.
https://github.com/freeotp/freeotp-android

#### Is the project available for download in Google Play? If yes, what is the number of downloads in Google Play? If no, give any data that shows the popularity of the app (for example, is it available in F-Droid?)
Yes. Google Play lists 1,000,000+ downloads, shown as 1M+.
https://play.google.com/store/apps/details?id=org.fedorahosted.freeotp

It is also on F-Droid. Version 2.0.6 was added there on February 19, 2026.
https://f-droid.org/packages/org.fedorahosted.freeotp/

#### Actively Maintained: When was the latest commit to the project?
The latest commit on the default branch, `master`, was on August 18, 2026: "Use view binding for ManualAdd". That is within the past year. The latest release is v2.0.6, published on February 17, 2026.

#### Likelihood of finding new bugs: How many bug-related (e.g., with label "bug") GitHub issues does the project have?
18 issues are labeled `bug`. 11 are still open and 7 are closed. The repository also has 111 open issues and 227 closed issues overall, but those are not all tagged as bugs.

#### How many of these bug-related issues have been resolved/closed?
7 of the 18 bug-labeled issues are closed.

#### What are the lines of code (LoC) in the project?
5,144 lines of Java code, excluding blank lines and comments, in 44 Java files. There are no Kotlin files. Counting blank lines and comments as well, the Java files total 6,940 lines.

#### What tool did you use to measure the LoC?
A line count of a local clone of the `master` branch on October 9, 2026. The CodeTabs API was unavailable when this was measured.
