# Full-stack open --- Part 11 --- Exercise 11.1

This imaginary project would be coded in Java.

## Tools

#### Linting

Java is mostly coded with Eclipse, where one could install for example Sonar Lint plugin from the Eclipse market place to handle the linting. If would be developing with VSCode, one could install an extension, e.g. Red Hat's Language support for Java.

#### Testing

Again Eclipse would have ready clicking options for this job. In VSCode one could install e.g. Microsoft's Java Test Runner plugin.

#### Building

For building Java code I would choose Apache Maven, because I'm already familiar with it and it's very flexible. However, there are also other tools available, such as Grandle, Sonatype Nexus, CMake, and Bazel.

## CI Alternatives

There are plenty of CI alternatives besides Jenkins and GitHub actions. Without the help of Google I can come up with CircleCI, but with the help of Google there can be found several, e.g. Travis, TeamCity from Jetbrains, Codeship, GitLabCI (similar to GitHub Actions), TeamCity and Bamboo. And this is just the tip of an iceberg into the multitude of existing CI tools.

## Self-hosted or Cloud-based Environment?

Java applications can be run easily in both options, so in order to make the decision regarding whether to run in cloud or host myself, I would need to know e.g.

- How complex the application is? Does it need some specific resources such as GPU?
- How sensitive the application's secrets are (can those be exposed into cloud-based solutions)?

Many self-hosted options can also be run on a private cloud (which would enable them to be "cloud-based" and easily available through-out your organization but still having the full ownership of all your secrets etc.)

If this setup would be used by just the 6 people's team (and not shared by other teams), I would choose some existing cloud-based solution due to the time-savings.
