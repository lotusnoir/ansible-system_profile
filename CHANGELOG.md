# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [3.2.0](https://github.com/lotusnoir/ansible-system_profile/compare/3.1.0...3.2.0) - 2025-11-26

### Commits

- update main to include success flag at the end to be able to monitor last playbook run [`5508462`](https://github.com/lotusnoir/ansible-system_profile/commit/5508462f458ada503d4c9f9b1c8c969d10e42e50)

## [3.1.0](https://github.com/lotusnoir/ansible-system_profile/compare/3.0.0...3.1.0) - 2025-11-18

### Commits

- fix molecule test image for rhel8 [`323d05a`](https://github.com/lotusnoir/ansible-system_profile/commit/323d05a26785a46192bdd5c24c8e172967d7e224)
- update core and molecule [`83fe43a`](https://github.com/lotusnoir/ansible-system_profile/commit/83fe43a6bf9efec83f5bee511e98f28c8cac568d)
- add oraclelinux10 support + lint and core fixes [`05ec48b`](https://github.com/lotusnoir/ansible-system_profile/commit/05ec48bcb764dfd776ad98923e31997f6c5be970)

## [3.0.0](https://github.com/lotusnoir/ansible-system_profile/compare/2.0.0...3.0.0) - 2025-10-29

### Commits

- add trixie (debian13) support [`dc3fdb3`](https://github.com/lotusnoir/ansible-system_profile/commit/dc3fdb37e8b8b6f174392672eec573e366d26456)
- update core, molecule + gitlab-ci [`0e67a68`](https://github.com/lotusnoir/ansible-system_profile/commit/0e67a68b0486b79bf294069caba0923d08626521)
- fix lint [`5ab3c1f`](https://github.com/lotusnoir/ansible-system_profile/commit/5ab3c1f7c1c8fc23d9bcc8a2ac2b8c5d98256239)
- fix molecule paralelism and little updates [`c0cdcfb`](https://github.com/lotusnoir/ansible-system_profile/commit/c0cdcfbbc023ac117657f99daf3098c53ad1b85e)
- add support for ubuntu24 [`11c2101`](https://github.com/lotusnoir/ansible-system_profile/commit/11c21012e46090830c911824ddb73969e5cf219c)
- add version on molecule play image to maintain support on old release [`ccd18c7`](https://github.com/lotusnoir/ansible-system_profile/commit/ccd18c7d82f32040deee6961f39c1d02e7a8ae83)
- update molecule [`0bede4c`](https://github.com/lotusnoir/ansible-system_profile/commit/0bede4c467008d5b775dbe7fb4ea74abc26956c8)
- add redhat 9 to default supported distrib [`478c858`](https://github.com/lotusnoir/ansible-system_profile/commit/478c85818dd63742ba1d32e12fbbc67b1a62ad3a)
- add redhat 8 to default supported distrib [`bfec15a`](https://github.com/lotusnoir/ansible-system_profile/commit/bfec15a9f4170e489ecc8122377819ff79c246f6)
- sort testing distrib to avoid random changes [`16c3f16`](https://github.com/lotusnoir/ansible-system_profile/commit/16c3f1604453987839ff2c6f26f2bafa44dd42fe)

## [2.0.0](https://github.com/lotusnoir/ansible-system_profile/compare/1.1.0...2.0.0) - 2023-09-25

### Commits

- update vars [`33b1414`](https://github.com/lotusnoir/ansible-system_profile/commit/33b141440386663a65bd1df24d6a4bbab85aa063)
- update readme + precommit + include vars [`a976ed3`](https://github.com/lotusnoir/ansible-system_profile/commit/a976ed392dcf989ca25c5c79d25e25f28cb8e7c3)
- change import tasks to include in order to support facts on name [`89cb83f`](https://github.com/lotusnoir/ansible-system_profile/commit/89cb83f3e5b1b6621dbdaacf2971badc38b18c46)

## [1.1.0](https://github.com/lotusnoir/ansible-system_profile/compare/1.0.0...1.1.0) - 2023-06-14

### Commits

- add debian12 support [`66db7c8`](https://github.com/lotusnoir/ansible-system_profile/commit/66db7c8f614e62c89925885162a63ac13e73db23)

## [1.0.0](https://github.com/lotusnoir/ansible-system_profile/compare/0.4.0...1.0.0) - 2023-03-23

### Commits

- add precommit for lint [`d45a9f9`](https://github.com/lotusnoir/ansible-system_profile/commit/d45a9f991ec85ec0a87ebe642d062207c942ee4d)
- fix checks [`7d8b6c7`](https://github.com/lotusnoir/ansible-system_profile/commit/7d8b6c70df80175e148c8cbf0ebcac81db95e52b)
- add new molecule all scenario [`2ab0976`](https://github.com/lotusnoir/ansible-system_profile/commit/2ab0976d6c90f89efcbe982317598fe78928e11a)
- split distro for molecule tests on ci [`63aefac`](https://github.com/lotusnoir/ansible-system_profile/commit/63aefac754dd079d0de26d82c9a84c3d6eaf42ae)
- update checks and Readme [`35d793d`](https://github.com/lotusnoir/ansible-system_profile/commit/35d793dddeb63608c92984b613589a4a44abe487)
- add molecule fix for ora9 [`134dd93`](https://github.com/lotusnoir/ansible-system_profile/commit/134dd9367f41c54d753add459a0e74ca4e3ffb70)
- update checks [`1469e6e`](https://github.com/lotusnoir/ansible-system_profile/commit/1469e6e1d2b2293bcae78e7c1e03170ca1842cf3)
- fix test and pipeline [`01631aa`](https://github.com/lotusnoir/ansible-system_profile/commit/01631aaa43663e729deb200458ee83719aac3e96)
- change verify on molecule [`6290614`](https://github.com/lotusnoir/ansible-system_profile/commit/6290614950b006e42ab7bebce9cf46e16e272a62)
- fix: molecule image and optimize scenario [`dbc7747`](https://github.com/lotusnoir/ansible-system_profile/commit/dbc77479e15215707992cbd322db159e9c50754b)

## [0.4.0](https://github.com/lotusnoir/ansible-system_profile/compare/0.3.0...0.4.0) - 2022-07-01

### Commits

- minor: add oracleLinux7 support [`779a334`](https://github.com/lotusnoir/ansible-system_profile/commit/779a3343f9e576cc3ba85b98fd76d38fc0848cd5)

## [0.3.0](https://github.com/lotusnoir/ansible-system_profile/compare/0.2.0...0.3.0) - 2022-06-27

### Commits

- minor: add oracleLinux support + little fixes [`eff1a77`](https://github.com/lotusnoir/ansible-system_profile/commit/eff1a77ee616d1b300fdd202e69fff3606b7535b)

## [0.2.0](https://github.com/lotusnoir/ansible-system_profile/compare/0.1.0...0.2.0) - 2022-06-01

### Commits

- minor: add ubuntu 22 molecule test + fix lint [`208040d`](https://github.com/lotusnoir/ansible-system_profile/commit/208040df9b88a9a914cb56c52b6c69c30eea1b13)
- Update main.yml [`c5b30e6`](https://github.com/lotusnoir/ansible-system_profile/commit/c5b30e6d025c2d3c82070719cb190e24d8f78f5f)
- fix: remove unsupported centos8 + minor fixes [`3033536`](https://github.com/lotusnoir/ansible-system_profile/commit/30335365d9631155e4c66e38dab5a961958fcb24)
- fix: remove bad exemple on defaults [`76bf98c`](https://github.com/lotusnoir/ansible-system_profile/commit/76bf98c2eb3a033efa7d411c55d9af2371ebc9ca)
- fix: add extension becasue profile.d support *.sh scripts [`6c39bea`](https://github.com/lotusnoir/ansible-system_profile/commit/6c39beaccfc27b086695d0bb9e0f46860febfccb)
