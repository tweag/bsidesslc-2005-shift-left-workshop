![BSides Utah Events](BSidesUtah.avif "BSides SLC")

# Shifting Left: A Hands-on Introductory Guide to DevSecOps

The following repository contains training material workshops on shifting security left.

This workshop is held at `BSides SLC` on `April 10th 2025` at `10am`.

## Workshop Outline

*Shifting Left: A Hands-on Introductory Guide to DevSecOps* is a two hour workshop where participants get an introduction to baking security into the software development process and leveraging DevSecOps tooling to support this. 

Attendees will learn about setting up a GitHub environment which includes security tools such as CodeQL. Students will then progress into learning how to use DevSecOps pipelines to detect security issues such as accidentally committed secrets.

The workshop will then wrap up with tips on how to handle secure deployments and a look to what the future holds in this space.

## Pre-setup Phase

In order to fully participate in this workshop you will need a GitHub account.

You can obtain this by signing up at http://www.github.com. 

Students will be able to sign up for a .edu account which comes with some added bonuses, such as being able to setup private repositories for free.

Once your account is setup, you will need to `Fork` and `Clone` this repository or spin up a Codespace environment. 


## Working In The Repository Scanning

Here we cover some repository scanning techniques, including secrets scanning and vulnerability detection, using tools like GitHub's dependabot and Tartufo.

### Hour 1

1. Secrets scanning. A demonstration of how secret scanning can be performed in the source code. This includes examples of Tartufo/TruffleHog, GitHub's tooling and Horusec. [Module 1:Secrets Scanning](https://github.com/tweag/bsidesslc-2025-shift-left-workshop/tree/main/course#module-1secrets-scanning)

2. Handling secrets in GitHub. GitHub provides users the ability to store secrets such as API keys securely within the SCM, and pull these out at deployment time. Here participants learn the basics of the environment within GitHub and how to leverage GitHub native secret storage mechanisms. We will also discuss other options for storing secrets and pulling them into CI/CD pipelines [Module 2: Handling secrets in GitHub](https://github.com/tweag/bsidesslc-2025-shift-left-workshop/tree/main/course#module-2handling-secrets-in-github)

3. Detecting security vulnerabilities within the repository. Students are introduced to the concept of detecting security vulnerabilities in the source code repository. A general overview of techniques and approaches is given, as well as those specific to GitHub.[Module 3:Detecting Security vulnerabilities](https://github.com/tweag/bsidesslc-2025-shift-left-workshop/tree/main/course#module-3handling-secrets-in-github)

4. Vulnerable dependency detection. GitHub's dependabot provides a mechanism for analyzing the dependencies associated with a project and understanding if they contain security vulnerabilities. Walkthrough of dependabot is performed. [Module 4:Vulnerable dependencies](https://github.com/tweag/bsidesslc-2025-shift-left-workshop/tree/main/course#module-4vulnerable-dependencies) 

### Hour 2

5. Static analysis. GitHub Advanced Security contains a GitHub native SAST tool built on CodeQL. This section of the class walks through its feature sets and how it can be integrated into GitHub actions. This section of the talk will also cover Horusec and how it cane be used in the same capacity.[Module 5:Static Analysis](https://github.com/tweag/bsidesslc-2025-shift-left-workshop/tree/main/course#module-5static-analysis)

6. Branch protection and pull request gating mechanisms. The penultimate topic covered is how branch protection rules and PR gating mechanisms can leverage SAST tools to block pull requests that fail security checks.[Module 6:Branch protection rules](https://github.com/tweag/bsidesslc-2025-shift-left-workshop/tree/main/course#module-6branch-protection-rules)

7. SBOMs. A final note on SBOMs. These can be used to extract a Software Bill of Materials from your applications stored in GitHub. [Module 7:SBOMs Software Bill of Materials](https://github.com/tweag/bsidesslc-2025-shift-left-workshop/tree/main/course#module-7sboms-software-bill-of-materials)

## Wrap-up

Discussion of future trends in this space.

Recap of what we've learned

