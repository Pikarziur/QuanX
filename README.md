2026-08-17T00:52:54.1699316Z Current runner version: '2.336.0'
2026-08-17T00:52:54.1725792Z ##[group]Runner Image Provisioner
2026-08-17T00:52:54.1726677Z Hosted Compute Agent
2026-08-17T00:52:54.1727697Z Version: 20260729.566
2026-08-17T00:52:54.1728339Z Commit: cf7153fe6e25b664e8693c24944bf2b00355d109
2026-08-17T00:52:54.1729028Z Build Date: 2026-07-29T19:17:02Z
2026-08-17T00:52:54.1729815Z Worker ID: {94aa43a1-8ff2-49bc-a4b6-08e499c969c6}
2026-08-17T00:52:54.1730520Z Azure Region: westus
2026-08-17T00:52:54.1731118Z ##[endgroup]
2026-08-17T00:52:54.1732766Z ##[group]Operating System
2026-08-17T00:52:54.1733390Z Ubuntu
2026-08-17T00:52:54.1734068Z 24.04.4
2026-08-17T00:52:54.1734633Z LTS
2026-08-17T00:52:54.1735393Z ##[endgroup]
2026-08-17T00:52:54.1736022Z ##[group]Runner Image
2026-08-17T00:52:54.1736627Z Image: ubuntu-24.04
2026-08-17T00:52:54.1737244Z Version: 20260810.271.1
2026-08-17T00:52:54.1738492Z Included Software: https://github.com/actions/runner-images/blob/ubuntu24/20260810.271/images/ubuntu/Ubuntu2404-Readme.md
2026-08-17T00:52:54.1740095Z Image Release: https://github.com/actions/runner-images/releases/tag/ubuntu24%2F20260810.271
2026-08-17T00:52:54.1741039Z ##[endgroup]
2026-08-17T00:52:54.1742290Z ##[group]GITHUB_TOKEN Permissions
2026-08-17T00:52:54.1744490Z Contents: read
2026-08-17T00:52:54.1745599Z Metadata: read
2026-08-17T00:52:54.1746386Z Packages: read
2026-08-17T00:52:54.1746953Z ##[endgroup]
2026-08-17T00:52:54.1749394Z Secret source: Actions
2026-08-17T00:52:54.1750505Z Prepare workflow directory
2026-08-17T00:52:54.2173100Z Prepare all required actions
2026-08-17T00:52:54.2221907Z Getting action download info
2026-08-17T00:52:54.6197712Z Download action repository 'actions/checkout@v4' (SHA:11d5960a326750d5838078e36cf38b85af677262)
2026-08-17T00:52:54.7923190Z Download action repository 'actions/setup-java@v4' (SHA:cf277c60eb25467037889841efdb72551f06f6c3)
2026-08-17T00:52:55.3194303Z Download action repository 'gradle/actions@v4' (SHA:ed408507eac070d1f99cc633dbcf757c94c7933a)
2026-08-17T00:52:56.3939407Z Download action repository 'android-actions/setup-android@v4' (SHA:40fd30fb8d7440372e1316f5d1809ec01dcd3699)
2026-08-17T00:52:56.6575385Z Download action repository 'actions/upload-artifact@v4' (SHA:ea165f8d65b6e75b540449e92b4886f43607fa02)
2026-08-17T00:52:56.8891746Z Complete job name: Build Android APK
2026-08-17T00:52:56.9698126Z Node 20 is being deprecated. This workflow is running with Node 24 by default. If you need to temporarily use Node 20, you can set the ACTIONS_ALLOW_USE_UNSECURE_NODE_VERSION=true environment variable. For more information see: https://github.blog/changelog/2025-09-19-deprecation-of-node-20-on-github-actions-runners/
2026-08-17T00:52:56.9706255Z ##[group]Run actions/checkout@v4
2026-08-17T00:52:56.9706718Z with:
2026-08-17T00:52:56.9706941Z   repository: Pikarziur/AutoBOT
2026-08-17T00:52:56.9709736Z   token: ***
2026-08-17T00:52:56.9709955Z   ssh-strict: true
2026-08-17T00:52:56.9710162Z   ssh-user: git
2026-08-17T00:52:56.9710378Z   persist-credentials: true
2026-08-17T00:52:56.9710644Z   clean: true
2026-08-17T00:52:56.9710858Z   sparse-checkout-cone-mode: true
2026-08-17T00:52:56.9711118Z   fetch-depth: 1
2026-08-17T00:52:56.9711341Z   fetch-tags: false
2026-08-17T00:52:56.9711555Z   show-progress: true
2026-08-17T00:52:56.9711762Z   lfs: false
2026-08-17T00:52:56.9711994Z   submodules: false
2026-08-17T00:52:56.9712206Z   set-safe-directory: true
2026-08-17T00:52:56.9712455Z   allow-unsafe-pr-checkout: false
2026-08-17T00:52:56.9712922Z env:
2026-08-17T00:52:56.9713125Z   GRADLE_VERSION: 8.5
2026-08-17T00:52:56.9713351Z   JAVA_VERSION: 17
2026-08-17T00:52:56.9713552Z ##[endgroup]
2026-08-17T00:52:57.0749496Z Syncing repository: Pikarziur/AutoBOT
2026-08-17T00:52:57.0751776Z ##[group]Getting Git version info
2026-08-17T00:52:57.0752412Z Working directory is '/home/runner/work/AutoBOT/AutoBOT'
2026-08-17T00:52:57.0753332Z [command]/usr/bin/git version
2026-08-17T00:52:57.0819440Z git version 2.54.0
2026-08-17T00:52:57.0885166Z ##[endgroup]
2026-08-17T00:52:57.0901343Z Temporarily overriding HOME='/home/runner/work/_temp/55dff277-ea57-4ada-96d1-2d4e762f647d' before making global git config changes
2026-08-17T00:52:57.0903173Z Adding repository directory to the temporary git global config as a safe directory
2026-08-17T00:52:57.0907553Z [command]/usr/bin/git config --global --add safe.directory /home/runner/work/AutoBOT/AutoBOT
2026-08-17T00:52:57.0961673Z Deleting the contents of '/home/runner/work/AutoBOT/AutoBOT'
2026-08-17T00:52:57.0966387Z ##[group]Initializing the repository
2026-08-17T00:52:57.0971215Z [command]/usr/bin/git init /home/runner/work/AutoBOT/AutoBOT
2026-08-17T00:52:57.1083848Z hint: Using 'master' as the name for the initial branch. This default branch name
2026-08-17T00:52:57.1085293Z hint: will change to "main" in Git 3.0. To configure the initial branch name
2026-08-17T00:52:57.1086395Z hint: to use in all of your new repositories, which will suppress this warning,
2026-08-17T00:52:57.1087332Z hint: call:
2026-08-17T00:52:57.1087713Z hint:
2026-08-17T00:52:57.1088282Z hint: 	git config --global init.defaultBranch <name>
2026-08-17T00:52:57.1088938Z hint:
2026-08-17T00:52:57.1089786Z hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
2026-08-17T00:52:57.1090965Z hint: 'development'. The just-created branch can be renamed via this command:
2026-08-17T00:52:57.1092142Z hint:
2026-08-17T00:52:57.1092580Z hint: 	git branch -m <name>
2026-08-17T00:52:57.1093052Z hint:
2026-08-17T00:52:57.1093708Z hint: Disable this message with "git config set advice.defaultBranchName false"
2026-08-17T00:52:57.1094773Z Initialized empty Git repository in /home/runner/work/AutoBOT/AutoBOT/.git/
2026-08-17T00:52:57.1106035Z [command]/usr/bin/git remote add origin https://github.com/Pikarziur/AutoBOT
2026-08-17T00:52:57.1154760Z ##[endgroup]
2026-08-17T00:52:57.1155808Z ##[group]Disabling automatic garbage collection
2026-08-17T00:52:57.1160853Z [command]/usr/bin/git config --local gc.auto 0
2026-08-17T00:52:57.1196912Z ##[endgroup]
2026-08-17T00:52:57.1197987Z ##[group]Setting up auth
2026-08-17T00:52:57.1204682Z [command]/usr/bin/git config --local --name-only --get-regexp core\.sshCommand
2026-08-17T00:52:57.1247818Z [command]/usr/bin/git submodule foreach --recursive sh -c "git config --local --name-only --get-regexp 'core\.sshCommand' && git config --local --unset-all 'core.sshCommand' || :"
2026-08-17T00:52:57.1638882Z [command]/usr/bin/git config --local --name-only --get-regexp http\.https\:\/\/github\.com\/\.extraheader
2026-08-17T00:52:57.1681576Z [command]/usr/bin/git submodule foreach --recursive sh -c "git config --local --name-only --get-regexp 'http\.https\:\/\/github\.com\/\.extraheader' && git config --local --unset-all 'http.https://github.com/.extraheader' || :"
2026-08-17T00:52:57.1919022Z [command]/usr/bin/git config --local --name-only --get-regexp ^includeIf\.gitdir:
2026-08-17T00:52:57.1958877Z [command]/usr/bin/git submodule foreach --recursive git config --local --show-origin --name-only --get-regexp remote.origin.url
2026-08-17T00:52:57.2195344Z [command]/usr/bin/git config --local http.https://github.com/.extraheader AUTHORIZATION: basic ***
2026-08-17T00:52:57.2247103Z ##[endgroup]
2026-08-17T00:52:57.2247970Z ##[group]Fetching the repository
2026-08-17T00:52:57.2261924Z [command]/usr/bin/git -c protocol.version=2 fetch --no-tags --prune --no-recurse-submodules --depth=1 origin +90c3697fe0e605356c1995aa011d3f84927b29c1:refs/remotes/origin/main
2026-08-17T00:52:57.6562452Z From https://github.com/Pikarziur/AutoBOT
2026-08-17T00:52:57.6563224Z  * [new ref]         90c3697fe0e605356c1995aa011d3f84927b29c1 -> origin/main
2026-08-17T00:52:57.6599370Z ##[endgroup]
2026-08-17T00:52:57.6599997Z ##[group]Determining the checkout info
2026-08-17T00:52:57.6602385Z ##[endgroup]
2026-08-17T00:52:57.6608842Z [command]/usr/bin/git sparse-checkout disable
2026-08-17T00:52:57.6658597Z [command]/usr/bin/git config --local --unset-all extensions.worktreeConfig
2026-08-17T00:52:57.6691150Z ##[group]Checking out the ref
2026-08-17T00:52:57.6695844Z [command]/usr/bin/git checkout --progress --force -B main refs/remotes/origin/main
2026-08-17T00:52:57.6803523Z Switched to a new branch 'main'
2026-08-17T00:52:57.6806293Z branch 'main' set up to track 'origin/main'.
2026-08-17T00:52:57.6819830Z ##[endgroup]
2026-08-17T00:52:57.6865539Z [command]/usr/bin/git log -1 --format=%H
2026-08-17T00:52:57.6892610Z 90c3697fe0e605356c1995aa011d3f84927b29c1
2026-08-17T00:52:57.7187219Z Node 20 is being deprecated. This workflow is running with Node 24 by default. If you need to temporarily use Node 20, you can set the ACTIONS_ALLOW_USE_UNSECURE_NODE_VERSION=true environment variable. For more information see: https://github.blog/changelog/2025-09-19-deprecation-of-node-20-on-github-actions-runners/
2026-08-17T00:52:57.7189269Z ##[group]Run actions/setup-java@v4
2026-08-17T00:52:57.7189542Z with:
2026-08-17T00:52:57.7189738Z   distribution: temurin
2026-08-17T00:52:57.7189965Z   java-version: 17
2026-08-17T00:52:57.7190174Z   java-package: jdk
2026-08-17T00:52:57.7190387Z   check-latest: false
2026-08-17T00:52:57.7190616Z   server-id: github
2026-08-17T00:52:57.7190828Z   server-username: GITHUB_ACTOR
2026-08-17T00:52:57.7191080Z   server-password: GITHUB_TOKEN
2026-08-17T00:52:57.7191322Z   overwrite-settings: true
2026-08-17T00:52:57.7191552Z   job-status: success
2026-08-17T00:52:57.7194264Z   token: ***
2026-08-17T00:52:57.7194459Z env:
2026-08-17T00:52:57.7194675Z   GRADLE_VERSION: 8.5
2026-08-17T00:52:57.7195181Z   JAVA_VERSION: 17
2026-08-17T00:52:57.7195445Z ##[endgroup]
2026-08-17T00:52:57.8943699Z ##[warning]setup-java v4 is deprecated and will no longer receive updates. Please migrate to actions/setup-java@v5.
2026-08-17T00:52:57.8954002Z ##[group]Installed distributions
2026-08-17T00:52:57.9218559Z Resolved Java 17.0.20+8 from tool-cache
2026-08-17T00:52:57.9219067Z Setting Java 17.0.20+8 as the default
2026-08-17T00:52:57.9230323Z (node:2227) [DEP0040] DeprecationWarning: The `punycode` module is deprecated. Please use a userland alternative instead.
2026-08-17T00:52:57.9231306Z (Use `node --trace-deprecation ...` to show where the warning was created)
2026-08-17T00:52:57.9234417Z Creating toolchains.xml for JDK version 17 from temurin
2026-08-17T00:52:57.9317661Z Writing to /home/runner/.m2/toolchains.xml
2026-08-17T00:52:57.9318237Z 
2026-08-17T00:52:57.9318365Z Java configuration:
2026-08-17T00:52:57.9318887Z   Distribution: temurin
2026-08-17T00:52:57.9319513Z   Version: 17.0.20+8
2026-08-17T00:52:57.9319931Z   Path: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T00:52:57.9320314Z 
2026-08-17T00:52:57.9320824Z ##[endgroup]
2026-08-17T00:52:57.9339488Z Creating settings.xml with server-id: github
2026-08-17T00:52:57.9372382Z Writing to /home/runner/.m2/settings.xml
2026-08-17T00:52:57.9710224Z Node 20 is being deprecated. This workflow is running with Node 24 by default. If you need to temporarily use Node 20, you can set the ACTIONS_ALLOW_USE_UNSECURE_NODE_VERSION=true environment variable. For more information see: https://github.blog/changelog/2025-09-19-deprecation-of-node-20-on-github-actions-runners/
2026-08-17T00:52:57.9713155Z ##[group]Run gradle/actions/setup-gradle@v4
2026-08-17T00:52:57.9713861Z with:
2026-08-17T00:52:57.9714380Z   gradle-version: 8.5
2026-08-17T00:52:57.9715211Z   cache-read-only: false
2026-08-17T00:52:57.9715822Z   validate-wrappers: false
2026-08-17T00:52:57.9716521Z   cache-disabled: false
2026-08-17T00:52:57.9717082Z   cache-write-only: false
2026-08-17T00:52:57.9717494Z   cache-overwrite-existing: false
2026-08-17T00:52:57.9717923Z   cache-cleanup: on-success
2026-08-17T00:52:57.9718406Z   gradle-home-cache-includes: caches
notifications

2026-08-17T00:52:57.9718943Z   add-job-summary: always
2026-08-17T00:52:57.9719425Z   add-job-summary-as-pr-comment: never
2026-08-17T00:52:57.9719897Z   dependency-graph: disabled
2026-08-17T00:52:57.9720396Z   dependency-graph-report-dir: dependency-graph-reports
2026-08-17T00:52:57.9720998Z   dependency-graph-continue-on-failure: true
2026-08-17T00:52:57.9721500Z   build-scan-publish: false
2026-08-17T00:52:57.9722191Z   allow-snapshot-wrappers: false
2026-08-17T00:52:57.9722650Z   gradle-home-cache-strict-match: false
2026-08-17T00:52:57.9723127Z   workflow-job-context: null
2026-08-17T00:52:57.9726823Z   github-token: ***
2026-08-17T00:52:57.9727049Z env:
2026-08-17T00:52:57.9727229Z   GRADLE_VERSION: 8.5
2026-08-17T00:52:57.9727438Z   JAVA_VERSION: 17
2026-08-17T00:52:57.9727755Z   JAVA_HOME: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T00:52:57.9728246Z   JAVA_HOME_17_X64: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T00:52:57.9728626Z ##[endgroup]
2026-08-17T00:52:59.5467211Z Merged default JDK locations into /home/runner/.m2/toolchains.xml
2026-08-17T00:52:59.5469096Z Preparing cache for cleanup.
2026-08-17T00:52:59.5472931Z ##[group]Restore Gradle state from cache
2026-08-17T00:52:59.8080040Z Cache hit for restore-key: gradle-home-v1|Linux-X64|build[266babc85e2a7f6e4c23c8d6be839361]-2250069352764867eb8efd4a6db6503923b097e5
2026-08-17T00:53:01.0900768Z Received 0 of 143456949 (0.0%), 0.0 MBs/sec
2026-08-17T00:53:02.0902914Z Received 125829120 of 143456949 (87.7%), 60.0 MBs/sec
2026-08-17T00:53:02.4796222Z Received 143456949 of 143456949 (100.0%), 57.3 MBs/sec
2026-08-17T00:53:02.4797524Z Cache Size: ~137 MB (143456949 B)
2026-08-17T00:53:02.4934405Z [command]/usr/bin/tar -xf /home/runner/work/_temp/cfb524f3-2e3f-4f2f-9211-a38fca579f25/cache.tzst -P -C /home/runner/work/AutoBOT/AutoBOT --use-compress-program unzstd
2026-08-17T00:53:03.5469771Z Cache restored successfully
2026-08-17T00:53:03.5541232Z Restored cache entry with key gradle-home-v1|Linux-X64|build[266babc85e2a7f6e4c23c8d6be839361]-90c3697fe0e605356c1995aa011d3f84927b29c1 to /home/runner/.gradle/caches,/home/runner/.gradle/notifications,/home/runner/.gradle/.setup-gradle in 4005ms
2026-08-17T00:53:03.8110612Z Cache hit for: gradle-dependencies-v1-ca33a97c11bd8dec625e8d54280f9120
2026-08-17T00:53:03.8121854Z Cache hit for: gradle-kotlin-dsl-v1-86903c45d6b8a8330f048b9beae0c1ea
2026-08-17T00:53:03.8129406Z Cache hit for: gradle-generated-gradle-jars-v1-fa001ab82c3596b4e27ec78f191b889f
2026-08-17T00:53:03.8133084Z Cache hit for: gradle-groovy-dsl-v1-df4ccfff3656846e3168e11ba2954a00
2026-08-17T00:53:03.8138090Z Cache hit for: gradle-wrapper-zips-v1-e89a30cff1b7b918cfe1273c9c8e4a34
2026-08-17T00:53:03.8253891Z Cache hit for: gradle-instrumented-jars-v1-289570630d9f1eeabb0c939ab04670fd
2026-08-17T00:53:04.2950001Z Received 98340 of 98340 (100.0%), 0.5 MBs/sec
2026-08-17T00:53:04.2950770Z Cache Size: ~0 MB (98340 B)
2026-08-17T00:53:04.2973934Z [command]/usr/bin/tar -xf /home/runner/work/_temp/6b3f1fe0-d6b0-43fb-a0d4-1229d5e10d80/cache.tzst -P -C /home/runner/work/AutoBOT/AutoBOT --use-compress-program unzstd
2026-08-17T00:53:04.3712828Z Cache restored successfully
2026-08-17T00:53:04.3718222Z Restored cache entry with key gradle-kotlin-dsl-v1-86903c45d6b8a8330f048b9beae0c1ea to /home/runner/.gradle/caches/*/kotlin-dsl/accessors/*/,/home/runner/.gradle/caches/*/kotlin-dsl/scripts/*/ in 814ms
2026-08-17T00:53:04.6092429Z Received 109102 of 109102 (100.0%), 0.2 MBs/sec
2026-08-17T00:53:04.6093252Z Cache Size: ~0 MB (109102 B)
2026-08-17T00:53:04.6121302Z [command]/usr/bin/tar -xf /home/runner/work/_temp/56058f98-0d68-4a55-bdf4-2dd2d9b4dd57/cache.tzst -P -C /home/runner/work/AutoBOT/AutoBOT --use-compress-program unzstd
2026-08-17T00:53:04.6277410Z Cache restored successfully
2026-08-17T00:53:04.6279120Z Restored cache entry with key gradle-groovy-dsl-v1-df4ccfff3656846e3168e11ba2954a00 to /home/runner/.gradle/caches/*/groovy-dsl/*/ in 1069ms
2026-08-17T00:53:05.0770439Z Received 0 of 328896045 (0.0%), 0.0 MBs/sec
2026-08-17T00:53:05.1000750Z Received 0 of 89746985 (0.0%), 0.0 MBs/sec
2026-08-17T00:53:05.1096574Z Received 0 of 36784583 (0.0%), 0.0 MBs/sec
2026-08-17T00:53:05.1178433Z Received 0 of 131966939 (0.0%), 0.0 MBs/sec
2026-08-17T00:53:05.8625642Z Received 36784583 of 36784583 (100.0%), 20.0 MBs/sec
2026-08-17T00:53:05.8628231Z Cache Size: ~35 MB (36784583 B)
2026-08-17T00:53:05.9343565Z [command]/usr/bin/tar -xf /home/runner/work/_temp/0b687ed9-26b1-481d-b2ea-c4ccac68af95/cache.tzst -P -C /home/runner/work/AutoBOT/AutoBOT --use-compress-program unzstd
2026-08-17T00:53:06.0883842Z Received 100663296 of 328896045 (30.6%), 47.7 MBs/sec
2026-08-17T00:53:06.1042932Z Received 85552681 of 89746985 (95.3%), 40.6 MBs/sec
2026-08-17T00:53:06.1332917Z Received 89746985 of 89746985 (100.0%), 42.0 MBs/sec
2026-08-17T00:53:06.1333710Z Cache Size: ~86 MB (89746985 B)
2026-08-17T00:53:06.1405968Z Received 83886080 of 131966939 (63.6%), 39.5 MBs/sec
2026-08-17T00:53:06.1867029Z [command]/usr/bin/tar -xf /home/runner/work/_temp/a4f0509f-d11e-4a15-b364-873a407410fd/cache.tzst -P -C /home/runner/work/AutoBOT/AutoBOT --use-compress-program unzstd
2026-08-17T00:53:06.2872200Z Cache restored successfully
2026-08-17T00:53:06.2960060Z Restored cache entry with key gradle-generated-gradle-jars-v1-fa001ab82c3596b4e27ec78f191b889f to /home/runner/.gradle/caches/8.5/generated-gradle-jars/gradle-api-8.5.jar in 2740ms
2026-08-17T00:53:06.5519309Z Received 131966939 of 131966939 (100.0%), 51.7 MBs/sec
2026-08-17T00:53:06.5526287Z Cache Size: ~126 MB (131966939 B)
2026-08-17T00:53:06.5549581Z [command]/usr/bin/tar -xf /home/runner/work/_temp/db34cfcd-9b3e-4826-b8a8-d79bd23038ad/cache.tzst -P -C /home/runner/work/AutoBOT/AutoBOT --use-compress-program unzstd
2026-08-17T00:53:06.8756022Z Cache restored successfully
2026-08-17T00:53:06.8908623Z Restored cache entry with key gradle-wrapper-zips-v1-e89a30cff1b7b918cfe1273c9c8e4a34 to /home/runner/.gradle/wrapper/dists/gradle-8.5-bin/5t9huq95ubn472n8rpzujfbqh in 3332ms
2026-08-17T00:53:07.0884000Z Received 201326592 of 328896045 (61.2%), 63.7 MBs/sec
2026-08-17T00:53:07.1031688Z Cache restored successfully
2026-08-17T00:53:07.1131324Z Restored cache entry with key gradle-instrumented-jars-v1-289570630d9f1eeabb0c939ab04670fd to /home/runner/.gradle/caches/jars-*/*/ in 3555ms
2026-08-17T00:53:07.9800243Z Received 328896045 of 328896045 (100.0%), 80.4 MBs/sec
2026-08-17T00:53:07.9803009Z Cache Size: ~314 MB (328896045 B)
2026-08-17T00:53:07.9941647Z [command]/usr/bin/tar -xf /home/runner/work/_temp/6af1a4cb-84b0-4576-b488-4cacba2260f4/cache.tzst -P -C /home/runner/work/AutoBOT/AutoBOT --use-compress-program unzstd
2026-08-17T00:53:08.4748346Z Cache restored successfully
2026-08-17T00:53:08.9859409Z Restored cache entry with key gradle-dependencies-v1-ca33a97c11bd8dec625e8d54280f9120 to /home/runner/.gradle/caches/modules-*/files-*/*/*/*/* in 5428ms
2026-08-17T00:53:09.0126576Z ##[endgroup]
2026-08-17T00:53:09.0464271Z ##[group]Provision Gradle 8.5
2026-08-17T00:53:13.7929207Z Cache hit for: gradle-8.5
2026-08-17T00:53:14.8701916Z Received 0 of 132239594 (0.0%), 0.0 MBs/sec
2026-08-17T00:53:15.8708211Z Received 125829120 of 132239594 (95.2%), 60.0 MBs/sec
2026-08-17T00:53:15.9671339Z Received 132239594 of 132239594 (100.0%), 60.2 MBs/sec
2026-08-17T00:53:15.9673905Z Cache Size: ~126 MB (132239594 B)
2026-08-17T00:53:15.9703186Z [command]/usr/bin/tar -xf /home/runner/work/_temp/0070334d-adcc-468a-a795-70718ae4ed19/cache.tzst -P -C /home/runner/work/AutoBOT/AutoBOT --use-compress-program unzstd
2026-08-17T00:53:16.1302426Z Cache restored successfully
2026-08-17T00:53:16.1362258Z Restored Gradle distribution gradle-8.5 from cache to /home/runner/work/_temp/.gradle-actions/gradle-installations/downloads/gradle-8.5-bin.zip
2026-08-17T00:53:16.1382063Z [command]/usr/bin/unzip -o -q /home/runner/work/_temp/.gradle-actions/gradle-installations/downloads/gradle-8.5-bin.zip
2026-08-17T00:53:17.0952929Z Extracted Gradle 8.5 to /home/runner/work/_temp/.gradle-actions/gradle-installations/installs/gradle-8.5
2026-08-17T00:53:17.0955418Z Provisioned Gradle executable /home/runner/work/_temp/.gradle-actions/gradle-installations/installs/gradle-8.5/bin/gradle
2026-08-17T00:53:17.0956773Z ##[endgroup]
2026-08-17T00:53:17.1159759Z ##[group]Run if [ -f "gradle/wrapper/gradle-wrapper.jar" ]; then
2026-08-17T00:53:17.1160364Z [36;1mif [ -f "gradle/wrapper/gradle-wrapper.jar" ]; then[0m
2026-08-17T00:53:17.1160889Z [36;1m  echo "✅ gradle-wrapper.jar already exists, skip generation"[0m
2026-08-17T00:53:17.1161539Z [36;1m  ls -la gradle/wrapper/[0m
2026-08-17T00:53:17.1161840Z [36;1m  exit 0[0m
2026-08-17T00:53:17.1162082Z [36;1mfi[0m
2026-08-17T00:53:17.1162308Z [36;1m[0m
2026-08-17T00:53:17.1162705Z [36;1mecho "⚠️ gradle-wrapper.jar not found. Generating via gradle command..."[0m
2026-08-17T00:53:17.1163209Z [36;1mecho "gradle version: $(gradle --version)"[0m
2026-08-17T00:53:17.1163763Z [36;1mgradle wrapper --gradle-version "$GRADLE_VERSION" --distribution-type bin --no-daemon[0m
2026-08-17T00:53:17.1164286Z [36;1m[0m
2026-08-17T00:53:17.1164600Z [36;1mif [ -f "gradle/wrapper/gradle-wrapper.jar" ]; then[0m
2026-08-17T00:53:17.1165664Z [36;1m  echo "✅ Generated gradle-wrapper.jar successfully:"[0m
2026-08-17T00:53:17.1166127Z [36;1m  ls -la gradle/wrapper/[0m
2026-08-17T00:53:17.1166430Z [36;1melse[0m
2026-08-17T00:53:17.1166767Z [36;1m  echo "❌ Failed to generate gradle-wrapper.jar"[0m
2026-08-17T00:53:17.1167156Z [36;1m  ls -la gradle/ || true[0m
2026-08-17T00:53:17.1167450Z [36;1m  exit 1[0m
2026-08-17T00:53:17.1167700Z [36;1mfi[0m
2026-08-17T00:53:17.1209010Z shell: /usr/bin/bash --noprofile --norc -e -o pipefail {0}
2026-08-17T00:53:17.1209415Z env:
2026-08-17T00:53:17.1209643Z   GRADLE_VERSION: 8.5
2026-08-17T00:53:17.1209902Z   JAVA_VERSION: 17
2026-08-17T00:53:17.1210287Z   JAVA_HOME: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T00:53:17.1210861Z   JAVA_HOME_17_X64: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T00:53:17.1211357Z   GRADLE_ACTION_ID: gradle/actions/setup-gradle
2026-08-17T00:53:17.1211732Z   GRADLE_USER_HOME: /home/runner/.gradle
2026-08-17T00:53:17.1212067Z   GRADLE_BUILD_ACTION_SETUP_COMPLETED: true
2026-08-17T00:53:17.1212421Z   GRADLE_BUILD_ACTION_CACHE_RESTORED: true
2026-08-17T00:53:17.1212927Z   DEVELOCITY_INJECTION_INIT_SCRIPT_NAME: gradle-actions.inject-develocity.init.gradle
2026-08-17T00:53:17.1213465Z   DEVELOCITY_INJECTION_CUSTOM_VALUE: gradle-actions
2026-08-17T00:53:17.1213839Z   GITHUB_DEPENDENCY_GRAPH_ENABLED: false
2026-08-17T00:53:17.1214149Z ##[endgroup]
2026-08-17T00:53:17.1296298Z ⚠️ gradle-wrapper.jar not found. Generating via gradle command...
2026-08-17T00:53:17.6623221Z gradle version: 
2026-08-17T00:53:17.6624121Z ------------------------------------------------------------
2026-08-17T00:53:17.6625378Z Gradle 8.5
2026-08-17T00:53:17.6625860Z ------------------------------------------------------------
2026-08-17T00:53:17.6626331Z 
2026-08-17T00:53:17.6626536Z Build time:   2023-11-29 14:08:57 UTC
2026-08-17T00:53:17.6627081Z Revision:     28aca86a7180baa17117e0e5ba01d8ea9feca598
2026-08-17T00:53:17.6627354Z 
2026-08-17T00:53:17.6627462Z Kotlin:       1.9.20
2026-08-17T00:53:17.6627744Z Groovy:       3.0.17
2026-08-17T00:53:17.6628106Z Ant:          Apache Ant(TM) version 1.10.13 compiled on January 4 2023
2026-08-17T00:53:17.6628543Z JVM:          17.0.20 (Eclipse Adoptium 17.0.20+8)
2026-08-17T00:53:17.6628896Z OS:           Linux 6.17.0-1022-azure amd64
2026-08-17T00:53:18.2670252Z To honour the JVM settings for this build a single-use Daemon process will be forked. For more on this, please refer to https://docs.gradle.org/8.5/userguide/gradle_daemon.html#sec:disabling_the_daemon in the Gradle documentation.
2026-08-17T00:53:19.8660223Z Daemon will be stopped at the end of the build 
2026-08-17T00:53:30.5705870Z 
2026-08-17T00:53:30.5736037Z > Configure project :app
2026-08-17T00:53:30.5737318Z Checking the license for package NDK (Side by side) 25.2.9519653 in /usr/local/lib/android/sdk/licenses
2026-08-17T00:53:30.5738428Z License for package NDK (Side by side) 25.2.9519653 accepted.
2026-08-17T00:53:30.5739264Z Preparing "Install NDK (Side by side) 25.2.9519653 v.25.2.9519653".
2026-08-17T00:53:45.3657927Z "Install NDK (Side by side) 25.2.9519653 v.25.2.9519653" ready.
2026-08-17T00:53:45.3659043Z Installing NDK (Side by side) 25.2.9519653 in /usr/local/lib/android/sdk/ndk/25.2.9519653
2026-08-17T00:53:45.3667553Z "Install NDK (Side by side) 25.2.9519653 v.25.2.9519653" complete.
2026-08-17T00:53:45.6678779Z "Install NDK (Side by side) 25.2.9519653 v.25.2.9519653" finished.
2026-08-17T00:53:47.3665663Z 
2026-08-17T00:53:47.3666472Z > Task :wrapper
2026-08-17T00:53:47.4684093Z gradle/actions: Writing build results to /home/runner/work/_temp/.gradle-actions/build-results/__run-1786928002251.json
2026-08-17T00:53:47.4685526Z 
2026-08-17T00:53:47.4699340Z BUILD SUCCESSFUL in 29s
2026-08-17T00:53:47.4701720Z 1 actionable task: 1 executed
2026-08-17T00:53:47.7909019Z ✅ Generated gradle-wrapper.jar successfully:
2026-08-17T00:53:47.7923797Z total 56
2026-08-17T00:53:47.7924317Z drwxr-xr-x 2 runner runner  4096 Aug 17 00:53 .
2026-08-17T00:53:47.7925503Z drwxr-xr-x 3 runner runner  4096 Aug 17 00:53 ..
2026-08-17T00:53:47.7925982Z -rw-r--r-- 1 runner runner 43462 Aug 17 00:53 gradle-wrapper.jar
2026-08-17T00:53:47.7926515Z -rw-r--r-- 1 runner runner   250 Aug 17 00:53 gradle-wrapper.properties
2026-08-17T00:53:47.7964062Z ##[group]Run chmod +x gradlew
2026-08-17T00:53:47.7964441Z [36;1mchmod +x gradlew[0m
2026-08-17T00:53:47.8002220Z shell: /usr/bin/bash -e {0}
2026-08-17T00:53:47.8002518Z env:
2026-08-17T00:53:47.8002748Z   GRADLE_VERSION: 8.5
2026-08-17T00:53:47.8003014Z   JAVA_VERSION: 17
2026-08-17T00:53:47.8003517Z   JAVA_HOME: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T00:53:47.8004356Z   JAVA_HOME_17_X64: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T00:53:47.8005285Z   GRADLE_ACTION_ID: gradle/actions/setup-gradle
2026-08-17T00:53:47.8005897Z   GRADLE_USER_HOME: /home/runner/.gradle
2026-08-17T00:53:47.8007656Z   GRADLE_BUILD_ACTION_SETUP_COMPLETED: true
2026-08-17T00:53:47.8008216Z   GRADLE_BUILD_ACTION_CACHE_RESTORED: true
2026-08-17T00:53:47.8009061Z   DEVELOCITY_INJECTION_INIT_SCRIPT_NAME: gradle-actions.inject-develocity.init.gradle
2026-08-17T00:53:47.8009971Z   DEVELOCITY_INJECTION_CUSTOM_VALUE: gradle-actions
2026-08-17T00:53:47.8010637Z   GITHUB_DEPENDENCY_GRAPH_ENABLED: false
2026-08-17T00:53:47.8011166Z ##[endgroup]
2026-08-17T00:53:47.8173255Z ##[group]Run android-actions/setup-android@v4
2026-08-17T00:53:47.8173857Z with:
2026-08-17T00:53:47.8174285Z   accept-android-sdk-licenses: true
2026-08-17T00:53:47.8175101Z   log-accepted-android-sdk-licenses: false
2026-08-17T00:53:47.8175670Z   cmdline-tools-version: 14742923
2026-08-17T00:53:47.8176160Z env:
2026-08-17T00:53:47.8176533Z   GRADLE_VERSION: 8.5
2026-08-17T00:53:47.8176966Z   JAVA_VERSION: 17
2026-08-17T00:53:47.8177625Z   JAVA_HOME: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T00:53:47.8178553Z   JAVA_HOME_17_X64: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T00:53:47.8179363Z   GRADLE_ACTION_ID: gradle/actions/setup-gradle
2026-08-17T00:53:47.8179969Z   GRADLE_USER_HOME: /home/runner/.gradle
2026-08-17T00:53:47.8180544Z   GRADLE_BUILD_ACTION_SETUP_COMPLETED: true
2026-08-17T00:53:47.8181134Z   GRADLE_BUILD_ACTION_CACHE_RESTORED: true
2026-08-17T00:53:47.8182053Z   DEVELOCITY_INJECTION_INIT_SCRIPT_NAME: gradle-actions.inject-develocity.init.gradle
2026-08-17T00:53:47.8182976Z   DEVELOCITY_INJECTION_CUSTOM_VALUE: gradle-actions
2026-08-17T00:53:47.8183595Z   GITHUB_DEPENDENCY_GRAPH_ENABLED: false
2026-08-17T00:53:47.8184117Z ##[endgroup]
2026-08-17T00:53:47.8989280Z Found preinstalled sdkmanager in /usr/local/lib/android/sdk/cmdline-tools/latest with following source.properties:
2026-08-17T00:53:47.8990473Z Pkg.Revision=12.0
2026-08-17T00:53:47.8990991Z Pkg.Path=cmdline-tools;12.0
2026-08-17T00:53:47.8991555Z Pkg.Desc=Android SDK Command-line Tools
2026-08-17T00:53:47.8991961Z 
2026-08-17T00:53:47.8992198Z Wrong version in preinstalled sdkmanager
2026-08-17T00:53:47.8993368Z Downloading commandline tools from https://dl.google.com/android/repository/commandlinetools-linux-14742923_latest.zip
2026-08-17T00:53:49.4562025Z [command]/usr/bin/unzip -o -q /home/runner/work/_temp/472fe2c6-9ed6-4ffe-b318-7f5cc3eeb53a
2026-08-17T00:53:50.2571326Z Accepting Android SDK licenses
2026-08-17T00:53:52.4147191Z ##[group]Run echo "ANDROID_HOME=$ANDROID_HOME"
2026-08-17T00:53:52.4147655Z [36;1mecho "ANDROID_HOME=$ANDROID_HOME"[0m
2026-08-17T00:53:52.4148047Z [36;1mecho "sdkmanager path: $(which sdkmanager)"[0m
2026-08-17T00:53:52.4148436Z [36;1msdkmanager --install \[0m
2026-08-17T00:53:52.4148762Z [36;1m  "platforms;android-34" \[0m
2026-08-17T00:53:52.4149085Z [36;1m  "build-tools;34.0.0" \[0m
2026-08-17T00:53:52.4149388Z [36;1m  "platform-tools" \[0m
2026-08-17T00:53:52.4149681Z [36;1m  "ndk;25.2.9519653" \[0m
2026-08-17T00:53:52.4149975Z [36;1m  "cmake;3.22.1"[0m
2026-08-17T00:53:52.4150277Z [36;1mecho "✅ SDK components installed"[0m
2026-08-17T00:53:52.4150720Z [36;1msdkmanager --list_installed || sdkmanager --list | head -50[0m
2026-08-17T00:53:52.4188663Z shell: /usr/bin/bash --noprofile --norc -e -o pipefail {0}
2026-08-17T00:53:52.4189059Z env:
2026-08-17T00:53:52.4189297Z   GRADLE_VERSION: 8.5
2026-08-17T00:53:52.4189555Z   JAVA_VERSION: 17
2026-08-17T00:53:52.4189977Z   JAVA_HOME: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T00:53:52.4190529Z   JAVA_HOME_17_X64: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T00:53:52.4191003Z   GRADLE_ACTION_ID: gradle/actions/setup-gradle
2026-08-17T00:53:52.4191363Z   GRADLE_USER_HOME: /home/runner/.gradle
2026-08-17T00:53:52.4191704Z   GRADLE_BUILD_ACTION_SETUP_COMPLETED: true
2026-08-17T00:53:52.4192051Z   GRADLE_BUILD_ACTION_CACHE_RESTORED: true
2026-08-17T00:53:52.4192563Z   DEVELOCITY_INJECTION_INIT_SCRIPT_NAME: gradle-actions.inject-develocity.init.gradle
2026-08-17T00:53:52.4193117Z   DEVELOCITY_INJECTION_CUSTOM_VALUE: gradle-actions
2026-08-17T00:53:52.4193506Z   GITHUB_DEPENDENCY_GRAPH_ENABLED: false
2026-08-17T00:53:52.4193858Z   ANDROID_HOME: /usr/local/lib/android/sdk
2026-08-17T00:53:52.4194214Z   ANDROID_SDK_ROOT: /usr/local/lib/android/sdk
2026-08-17T00:53:52.4194549Z ##[endgroup]
2026-08-17T00:53:52.4254379Z ANDROID_HOME=/usr/local/lib/android/sdk
2026-08-17T00:53:52.4269906Z sdkmanager path: /usr/local/lib/android/sdk/cmdline-tools/20.0/bin/sdkmanager
2026-08-17T00:53:53.3209445Z Loading package information...                                                  
2026-08-17T00:53:53.4132668Z Loading local repository...                                                     
2026-08-17T00:53:53.4135552Z [                                       ] 3% Loading local repository...        
2026-08-17T00:53:53.4233357Z [                                       ] 3% Fetch remote repository...         
2026-08-17T00:53:53.7129818Z [=                                      ] 3% Fetch remote repository...         
2026-08-17T00:53:53.7662284Z [=                                      ] 4% Fetch remote repository...         
2026-08-17T00:53:53.7874245Z [=                                      ] 5% Fetch remote repository...         
2026-08-17T00:53:53.8188479Z [==                                     ] 5% Fetch remote repository...         
2026-08-17T00:53:53.8869438Z [==                                     ] 6% Fetch remote repository...         
2026-08-17T00:53:53.9656495Z [==                                     ] 7% Fetch remote repository...         
2026-08-17T00:53:53.9695901Z [==                                     ] 7% Computing updates...               
2026-08-17T00:53:53.9835912Z [===                                    ] 8% Computing updates...               
2026-08-17T00:53:53.9981554Z [===                                    ] 10% Computing updates...              
2026-08-17T00:53:54.3191825Z [===                                    ] 10% Installing CMake 3.22.1           
2026-08-17T00:53:54.3604438Z [===                                    ] 10% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:53:54.3993207Z [====                                   ] 10% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:53:54.4413893Z [====                                   ] 11% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:53:54.4710594Z [====                                   ] 12% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:53:54.4892477Z [=====                                  ] 13% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:53:54.5106031Z [=====                                  ] 14% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:53:54.5231327Z [=====                                  ] 15% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:53:54.5332358Z [======                                 ] 15% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:53:54.5528796Z [======                                 ] 16% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:53:54.5766479Z [======                                 ] 17% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:53:54.5947834Z [=======                                ] 18% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:53:54.6158185Z [=======                                ] 19% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:53:54.6243624Z [=======                                ] 20% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:53:54.6337270Z [========                               ] 20% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:53:54.6499376Z [========                               ] 21% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:53:54.6577144Z [========                               ] 22% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:53:54.6644474Z [=========                              ] 23% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:53:54.6779781Z [=========                              ] 24% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:53:54.6807989Z [=========                              ] 25% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:53:54.6838515Z [==========                             ] 25% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:53:54.6909681Z [==========                             ] 26% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:53:54.6967558Z [==========                             ] 27% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:53:54.7036095Z [===========                            ] 28% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:53:54.7094944Z [===========                            ] 29% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:53:54.7138485Z [===========                            ] 30% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:53:54.7238602Z [============                           ] 30% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:53:54.7323022Z [============                           ] 31% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:53:54.7405420Z [============                           ] 32% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:53:54.7413300Z [============                           ] 33% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:53:54.9181908Z [============                           ] 33% Unzipping...                      
2026-08-17T00:53:54.9217261Z [============                           ] 33% Unzipping... bin/cmake            
2026-08-17T00:53:54.9436263Z [=============                          ] 33% Unzipping... bin/cmake            
2026-08-17T00:53:54.9638725Z [=============                          ] 34% Unzipping... bin/cmake            
2026-08-17T00:53:54.9740306Z [=============                          ] 35% Unzipping... bin/cmake            
2026-08-17T00:53:54.9847954Z [==============                         ] 35% Unzipping... bin/cmake            
2026-08-17T00:53:55.0058190Z [==============                         ] 36% Unzipping... bin/cmake            
2026-08-17T00:53:55.0266370Z [==============                         ] 37% Unzipping... bin/cmake            
2026-08-17T00:53:55.0424750Z [===============                        ] 38% Unzipping... bin/cmake            
2026-08-17T00:53:55.0526621Z [===============                        ] 39% Unzipping... bin/cmake            
2026-08-17T00:53:55.0658341Z [===============                        ] 39% Unzipping... bin/ctest            
2026-08-17T00:53:55.0747630Z [===============                        ] 40% Unzipping... bin/ctest            
2026-08-17T00:53:55.0837892Z [================                       ] 40% Unzipping... bin/ctest            
2026-08-17T00:53:55.1037764Z [================                       ] 41% Unzipping... bin/ctest            
2026-08-17T00:53:55.1246225Z [================                       ] 42% Unzipping... bin/ctest            
2026-08-17T00:53:55.1426095Z [=================                      ] 43% Unzipping... bin/ctest            
2026-08-17T00:53:55.1619213Z [=================                      ] 44% Unzipping... bin/ctest            
2026-08-17T00:53:55.1703429Z [=================                      ] 45% Unzipping... bin/ctest            
2026-08-17T00:53:55.1781831Z [==================                     ] 45% Unzipping... bin/ctest            
2026-08-17T00:53:55.1814256Z [==================                     ] 46% Unzipping... bin/ctest            
2026-08-17T00:53:55.1979351Z [==================                     ] 46% Unzipping... bin/cpack            
2026-08-17T00:53:55.2190382Z [==================                     ] 47% Unzipping... bin/cpack            
2026-08-17T00:53:55.2367491Z [===================                    ] 48% Unzipping... bin/cpack            
2026-08-17T00:53:55.2562144Z [===================                    ] 49% Unzipping... bin/cpack            
2026-08-17T00:53:55.2656362Z [===================                    ] 50% Unzipping... bin/cpack            
2026-08-17T00:53:55.2727246Z [====================                   ] 50% Unzipping... bin/cpack            
2026-08-17T00:53:55.2888579Z [====================                   ] 51% Unzipping... bin/cpack            
2026-08-17T00:53:55.2993358Z [====================                   ] 52% Unzipping... bin/cpack            
2026-08-17T00:53:55.3041701Z [====================                   ] 52% Unzipping... share/vim/vimfiles/in
2026-08-17T00:53:55.3043147Z [====================                   ] 52% Unzipping... share/vim/vimfiles/sy
2026-08-17T00:53:55.3068227Z [====================                   ] 52% Unzipping... share/aclocal/cmake.m
2026-08-17T00:53:55.3077982Z [====================                   ] 52% Unzipping... share/emacs/site-lisp
2026-08-17T00:53:55.3079564Z [====================                   ] 52% Unzipping... share/cmake-3.22/incl
2026-08-17T00:53:55.5710220Z [====================                   ] 52% Unzipping... share/cmake-3.22/Help
2026-08-17T00:53:55.6997193Z [=====================                  ] 53% Unzipping... share/cmake-3.22/Help
2026-08-17T00:53:55.7120862Z [=====================                  ] 53% Unzipping... share/cmake-3.22/Temp
2026-08-17T00:53:55.7638535Z [=====================                  ] 53% Unzipping... share/cmake-3.22/Modu
2026-08-17T00:53:55.9063008Z [=====================                  ] 54% Unzipping... share/cmake-3.22/Modu
2026-08-17T00:53:55.9069743Z [=====================                  ] 54% Unzipping... share/bash-completion
2026-08-17T00:53:55.9073131Z [=====================                  ] 54% Unzipping... doc/cmake-3.22/Copyri
2026-08-17T00:53:55.9076291Z [=====================                  ] 54% Unzipping... doc/cmake-3.22/cmzlib
2026-08-17T00:53:55.9078612Z [=====================                  ] 54% Unzipping... doc/cmake-3.22/cmzstd
2026-08-17T00:53:55.9081020Z [=====================                  ] 54% Unzipping... doc/cmake-3.22/cmnght
2026-08-17T00:53:55.9083524Z [=====================                  ] 54% Unzipping... doc/cmake-3.22/cmsys/
2026-08-17T00:53:55.9086684Z [=====================                  ] 54% Unzipping... doc/cmake-3.22/cmcurl
2026-08-17T00:53:55.9088854Z [=====================                  ] 54% Unzipping... doc/cmake-3.22/cmlibr
2026-08-17T00:53:55.9091400Z [=====================                  ] 54% Unzipping... doc/cmake-3.22/cmliba
2026-08-17T00:53:55.9093906Z [=====================                  ] 54% Unzipping... doc/cmake-3.22/cmlibl
2026-08-17T00:53:55.9096690Z [=====================                  ] 54% Unzipping... doc/cmake-3.22/cmlibu
2026-08-17T00:53:55.9100166Z [=====================                  ] 54% Unzipping... doc/openssl-1.1.1l/LI
2026-08-17T00:53:55.9101716Z [=====================                  ] 54% Unzipping... source.properties    
2026-08-17T00:53:55.9126625Z [=====================                  ] 54% Unzipping... bin/ninja            
2026-08-17T00:53:55.9129668Z [=====================                  ] 54% Unzipping... doc/ninja/LICENSE    
2026-08-17T00:53:55.9134408Z [=====================                  ] 54% Unzipping... share/cmake-3.22/Modu
2026-08-17T00:53:55.9214528Z [=====================                  ] 55% Unzipping... share/cmake-3.22/Modu
2026-08-17T00:53:55.9226194Z [=======================================] 100% Unzipping... share/cmake-3.22/Mod
2026-08-17T00:53:56.0516064Z 
2026-08-17T00:53:56.0780499Z ✅ SDK components installed
2026-08-17T00:53:56.9262652Z Loading package information...                                                  
2026-08-17T00:53:57.0127328Z Loading local repository...                                                     
2026-08-17T00:53:57.0160292Z [=========                              ] 25% Loading local repository...       
2026-08-17T00:53:57.0161129Z Installed packages:
2026-08-17T00:53:57.0311119Z   Path                               | Version       | Description                      | Location                          
2026-08-17T00:53:57.0334455Z   -------                            | -------       | -------                          | -------                           
2026-08-17T00:53:57.0348436Z   build-tools;34.0.0                 | 34.0.0        | Android SDK Build-Tools 34       | build-tools/34.0.0                
2026-08-17T00:53:57.0357679Z   build-tools;35.0.0                 | 35.0.0        | Android SDK Build-Tools 35       | build-tools/35.0.0                
2026-08-17T00:53:57.0365644Z   build-tools;35.0.1                 | 35.0.1        | Android SDK Build-Tools 35.0.1   | build-tools/35.0.1                
2026-08-17T00:53:57.0377234Z   build-tools;36.0.0                 | 36.0.0        | Android SDK Build-Tools 36       | build-tools/36.0.0                
2026-08-17T00:53:57.0385263Z   build-tools;36.1.0                 | 36.1.0        | Android SDK Build-Tools 36.1     | build-tools/36.1.0                
2026-08-17T00:53:57.0387635Z   build-tools;37.0.0                 | 37.0.0        | Android SDK Build-Tools 37       | build-tools/37.0.0                
2026-08-17T00:53:57.0402586Z   cmake;3.22.1                       | 3.22.1        | CMake 3.22.1                     | cmake/3.22.1                      
2026-08-17T00:53:57.0408022Z   cmake;3.31.5                       | 3.31.5        | CMake 3.31.5                     | cmake/3.31.5                      
2026-08-17T00:53:57.0416404Z   cmake;4.1.2                        | 4.1.2         | CMake 4.1.2                      | cmake/4.1.2                       
2026-08-17T00:53:57.0420315Z   extras;android;m2repository        | 47.0.0        | Android Support Repository       | extras/android/m2repository       
2026-08-17T00:53:57.0423752Z   extras;google;google_play_services | 49            | Google Play services             | extras/google/google_play_services
2026-08-17T00:53:57.0428383Z   extras;google;m2repository         | 58            | Google Repository                | extras/google/m2repository        
2026-08-17T00:53:57.0433003Z   ndk;25.2.9519653                   | 25.2.9519653  | NDK (Side by side) 25.2.9519653  | ndk/25.2.9519653                  
2026-08-17T00:53:57.0437358Z   ndk;27.3.13750724                  | 27.3.13750724 | NDK (Side by side) 27.3.13750724 | ndk/27.3.13750724                 
2026-08-17T00:53:57.0444010Z   ndk;28.2.13676358                  | 28.2.13676358 | NDK (Side by side) 28.2.13676358 | ndk/28.2.13676358                 
2026-08-17T00:53:57.0446271Z   ndk;29.0.14206865                  | 29.0.14206865 | NDK (Side by side) 29.0.14206865 | ndk/29.0.14206865                 
2026-08-17T00:53:57.0450766Z   platform-tools                     | 37.0.1        | Android SDK Platform-Tools       | platform-tools                    
2026-08-17T00:53:57.0455451Z   platforms;android-34               | 3             | Android SDK Platform 34          | platforms/android-34              
2026-08-17T00:53:57.0458785Z   platforms;android-34-ext10         | 1             | Android SDK Platform 34-ext10    | platforms/android-34-ext10        
2026-08-17T00:53:57.0461995Z   platforms;android-34-ext11         | 1             | Android SDK Platform 34-ext11    | platforms/android-34-ext11        
2026-08-17T00:53:57.0464717Z   platforms;android-34-ext12         | 1             | Android SDK Platform 34-ext12    | platforms/android-34-ext12        
2026-08-17T00:53:57.0468162Z   platforms;android-34-ext8          | 1             | Android SDK Platform 34-ext8     | platforms/android-34-ext8         
2026-08-17T00:53:57.0471864Z   platforms;android-35               | 2             | Android SDK Platform 35          | platforms/android-35              
2026-08-17T00:53:57.0475166Z   platforms;android-35-ext14         | 1             | Android SDK Platform 35-ext14    | platforms/android-35-ext14        
2026-08-17T00:53:57.0477954Z   platforms;android-35-ext15         | 1             | Android SDK Platform 35-ext15    | platforms/android-35-ext15        
2026-08-17T00:53:57.0481231Z   platforms;android-36               | 2             | Android SDK Platform 36          | platforms/android-36              
2026-08-17T00:53:57.0483663Z   platforms;android-36-ext18         | 1             | Android SDK Platform 36-ext18    | platforms/android-36-ext18        
2026-08-17T00:53:57.0486200Z   platforms;android-36-ext19         | 1             | Android SDK Platform 36-ext19    | platforms/android-36-ext19        
2026-08-17T00:53:57.0488870Z   platforms;android-36.1             | 1             | Android SDK Platform 36.1        | platforms/android-36.1            
2026-08-17T00:53:57.0491757Z   platforms;android-37.0             | 2             | Android SDK Platform 37.0        | platforms/android-37.0            
2026-08-17T00:53:57.0494207Z   platforms;android-37.1             | 1             | Android SDK Platform 37.1        | platforms/android-37.1            
2026-08-17T00:53:57.0496183Z   platforms;android-37.2-beta1       | 1             | Android SDK Platform 37.2-beta1  | platforms/android-37.2-beta1      
2026-08-17T00:53:57.0497868Z   platforms;android-37.2-beta2       | 2             | Android SDK Platform 37.2-beta2  | platforms/android-37.2-beta2      
2026-08-17T00:53:57.0505483Z 
2026-08-17T00:53:57.0630884Z ##[group]Run if [ -f "gradle/wrapper/gradle-wrapper.jar" ]; then
2026-08-17T00:53:57.0631449Z [36;1mif [ -f "gradle/wrapper/gradle-wrapper.jar" ]; then[0m
2026-08-17T00:53:57.0631918Z [36;1m  ./gradlew assembleDebug --stacktrace --no-daemon[0m
2026-08-17T00:53:57.0632291Z [36;1melse[0m
2026-08-17T00:53:57.0632622Z [36;1m  echo "⚠️ wrapper jar missing, using gradle directly"[0m
2026-08-17T00:53:57.0633101Z [36;1m  gradle assembleDebug --stacktrace --no-daemon[0m
2026-08-17T00:53:57.0633484Z [36;1mfi[0m
2026-08-17T00:53:57.0671288Z shell: /usr/bin/bash --noprofile --norc -e -o pipefail {0}
2026-08-17T00:53:57.0671692Z env:
2026-08-17T00:53:57.0671929Z   GRADLE_VERSION: 8.5
2026-08-17T00:53:57.0672193Z   JAVA_VERSION: 17
2026-08-17T00:53:57.0672615Z   JAVA_HOME: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T00:53:57.0673170Z   JAVA_HOME_17_X64: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T00:53:57.0673688Z   GRADLE_ACTION_ID: gradle/actions/setup-gradle
2026-08-17T00:53:57.0674067Z   GRADLE_USER_HOME: /home/runner/.gradle
2026-08-17T00:53:57.0674405Z   GRADLE_BUILD_ACTION_SETUP_COMPLETED: true
2026-08-17T00:53:57.0674748Z   GRADLE_BUILD_ACTION_CACHE_RESTORED: true
2026-08-17T00:53:57.0675397Z   DEVELOCITY_INJECTION_INIT_SCRIPT_NAME: gradle-actions.inject-develocity.init.gradle
2026-08-17T00:53:57.0675957Z   DEVELOCITY_INJECTION_CUSTOM_VALUE: gradle-actions
2026-08-17T00:53:57.0676329Z   GITHUB_DEPENDENCY_GRAPH_ENABLED: false
2026-08-17T00:53:57.0676846Z   ANDROID_HOME: /usr/local/lib/android/sdk
2026-08-17T00:53:57.0677195Z   ANDROID_SDK_ROOT: /usr/local/lib/android/sdk
2026-08-17T00:53:57.0677520Z ##[endgroup]
2026-08-17T00:53:57.6811236Z To honour the JVM settings for this build a single-use Daemon process will be forked. For more on this, please refer to https://docs.gradle.org/8.5/userguide/gradle_daemon.html#sec:disabling_the_daemon in the Gradle documentation.
2026-08-17T00:53:58.7806966Z Daemon will be stopped at the end of the build 
2026-08-17T00:54:05.8816304Z > Task :app:preBuild UP-TO-DATE
2026-08-17T00:54:05.8835650Z > Task :app:preDebugBuild UP-TO-DATE
2026-08-17T00:54:05.8836885Z > Task :app:mergeDebugNativeDebugMetadata NO-SOURCE
2026-08-17T00:54:05.9810933Z > Task :app:checkKotlinGradlePluginConfigurationErrors
2026-08-17T00:54:06.7804503Z > Task :app:dataBindingMergeDependencyArtifactsDebug
2026-08-17T00:54:06.7836364Z > Task :app:generateDebugResValues
2026-08-17T00:54:06.7858283Z > Task :app:generateDebugResources
2026-08-17T00:54:09.3806527Z > Task :app:packageDebugResources
2026-08-17T00:54:10.4843013Z > Task :app:mapDebugSourceSetPaths
2026-08-17T00:54:10.4887991Z > Task :app:parseDebugLocalResources
2026-08-17T00:54:10.4926094Z > Task :app:createDebugCompatibleScreenManifests
2026-08-17T00:54:10.4927204Z > Task :app:extractDeepLinksDebug
2026-08-17T00:54:10.5809809Z > Task :app:checkDebugAarMetadata
2026-08-17T00:54:10.9807374Z > Task :app:mergeDebugResources
2026-08-17T00:54:10.9808297Z > Task :app:processDebugMainManifest
2026-08-17T00:54:11.2809912Z > Task :app:dataBindingGenBaseClassesDebug
2026-08-17T00:54:11.3866486Z > Task :app:processDebugManifest
2026-08-17T00:54:11.3895734Z > Task :app:javaPreCompileDebug
2026-08-17T00:54:11.3925779Z > Task :app:mergeDebugShaders
2026-08-17T00:54:11.3955719Z > Task :app:compileDebugShaders NO-SOURCE
2026-08-17T00:54:11.3965314Z > Task :app:generateDebugAssets UP-TO-DATE
2026-08-17T00:54:11.4802512Z > Task :app:mergeDebugAssets
2026-08-17T00:54:11.4803895Z > Task :app:processDebugManifestForPackage
2026-08-17T00:54:11.5806317Z > Task :app:compressDebugAssets
2026-08-17T00:54:11.8826310Z > Task :app:desugarDebugFileDependencies
2026-08-17T00:54:11.8855886Z > Task :app:checkDebugDuplicateClasses
2026-08-17T00:54:12.5805606Z 
2026-08-17T00:54:12.5825902Z > Task :app:configureCMakeDebug[arm64-v8a]
2026-08-17T00:54:12.5840069Z [CXX5304] This version only understands SDK XML versions up to 3 but an SDK XML file of version 4 was encountered. This can happen if you use versions of Android Studio and the command-line tools that were released at different times.
2026-08-17T00:54:12.5868026Z [CXX5304] This version only understands SDK XML versions up to 3 but an SDK XML file of version 4 was encountered. This can happen if you use versions of Android Studio and the command-line tools that were released at different times.
2026-08-17T00:54:12.7805883Z 
2026-08-17T00:54:12.7876147Z > Task :app:processDebugResources
2026-08-17T00:54:13.6816377Z > Task :app:mergeLibDexDebug
2026-08-17T00:54:14.3797595Z > Task :app:buildCMakeDebug[arm64-v8a]
2026-08-17T00:54:14.9862436Z > Task :app:configureCMakeDebug[x86_64]
2026-08-17T00:54:15.8806130Z > Task :app:buildCMakeDebug[x86_64]
2026-08-17T00:54:15.8835899Z > Task :app:mergeDebugJniLibFolders
2026-08-17T00:54:16.1806478Z > Task :app:mergeDebugNativeLibs
2026-08-17T00:54:18.1806405Z > Task :app:validateSigningDebug
2026-08-17T00:54:18.2806225Z > Task :app:writeDebugAppMetadata
2026-08-17T00:54:18.2855556Z > Task :app:writeDebugSigningConfigVersions
2026-08-17T00:54:18.3857755Z > Task :app:stripDebugDebugSymbols
2026-08-17T00:54:28.6806289Z > Task :app:mergeExtDexDebug
2026-08-17T00:54:34.6827165Z e: file:///home/runner/work/AutoBOT/AutoBOT/app/src/main/java/com/autobot/app/ui/home/HomeFragment.kt:62:13 Unresolved reference: isShowText
2026-08-17T00:54:34.6828308Z 
2026-08-17T00:54:34.6828797Z > Task :app:compileDebugKotlin FAILED
2026-08-17T00:54:34.6886952Z e: file:///home/runner/work/AutoBOT/AutoBOT/app/src/main/java/com/autobot/app/ui/settings/SettingsFragment.kt:45:13 Unresolved reference: isShowText
2026-08-17T00:54:34.6916905Z e: file:///home/runner/work/AutoBOT/AutoBOT/app/src/main/java/com/autobot/app/ui/tasks/MonitorViewModel.kt:12:30 Unresolved reference: TaskMode
2026-08-17T00:54:34.6946944Z e: file:///home/runner/work/AutoBOT/AutoBOT/app/src/main/java/com/autobot/app/ui/tasks/MonitorViewModel.kt:44:15 Conflicting declarations: public companion object, public companion object
2026-08-17T00:54:34.6976903Z e: file:///home/runner/work/AutoBOT/AutoBOT/app/src/main/java/com/autobot/app/ui/tasks/MonitorViewModel.kt:124:5 Only one companion object is allowed per class
2026-08-17T00:54:34.7006935Z e: file:///home/runner/work/AutoBOT/AutoBOT/app/src/main/java/com/autobot/app/ui/tasks/MonitorViewModel.kt:124:15 Conflicting declarations: public companion object, public companion object
2026-08-17T00:54:34.7036726Z e: file:///home/runner/work/AutoBOT/AutoBOT/app/src/main/java/com/autobot/app/ui/tasks/MonitorViewModel.kt:157:32 Unresolved reference: LOG_MAX_LINES
2026-08-17T00:54:34.7817074Z gradle/actions: Writing build results to /home/runner/work/_temp/.gradle-actions/build-results/__run_4-1786928040252.json
2026-08-17T00:54:34.8812532Z 
2026-08-17T00:54:34.8876255Z FAILURE: Build failed with an exception.
2026-08-17T00:54:34.8925481Z 
2026-08-17T00:54:34.8955851Z * What went wrong:
2026-08-17T00:54:34.8956610Z Execution failed for task ':app:compileDebugKotlin'.
2026-08-17T00:54:34.8958299Z > A failure occurred while executing org.jetbrains.kotlin.compilerRunner.GradleCompilerRunnerWithWorkers$GradleKotlinCompilerWorkAction
2026-08-17T00:54:34.8960056Z    > Compilation error. See log for more details
2026-08-17T00:54:34.8995289Z 
2026-08-17T00:54:34.9045720Z * Try:
2026-08-17T00:54:34.9046360Z 34 actionable tasks: 34 executed
2026-08-17T00:54:34.9050940Z > Run with --info or --debug option to get more log output.
2026-08-17T00:54:34.9051947Z > Run with --scan to get full insights.
2026-08-17T00:54:34.9093909Z > Get more help at https://help.gradle.org.
2026-08-17T00:54:34.9119395Z 
2026-08-17T00:54:34.9146128Z * Exception is:
2026-08-17T00:54:34.9183913Z org.gradle.api.tasks.TaskExecutionException: Execution failed for task ':app:compileDebugKotlin'.
2026-08-17T00:54:34.9216645Z 	at org.gradle.api.internal.tasks.execution.ExecuteActionsTaskExecuter.lambda$executeIfValid$1(ExecuteActionsTaskExecuter.java:148)
2026-08-17T00:54:34.9235846Z 	at org.gradle.internal.Try$Failure.ifSuccessfulOrElse(Try.java:282)
2026-08-17T00:54:34.9277113Z 	at org.gradle.api.internal.tasks.execution.ExecuteActionsTaskExecuter.executeIfValid(ExecuteActionsTaskExecuter.java:146)
2026-08-17T00:54:34.9308071Z 	at org.gradle.api.internal.tasks.execution.ExecuteActionsTaskExecuter.execute(ExecuteActionsTaskExecuter.java:134)
2026-08-17T00:54:34.9336463Z 	at org.gradle.api.internal.tasks.execution.FinalizePropertiesTaskExecuter.execute(FinalizePropertiesTaskExecuter.java:46)
2026-08-17T00:54:34.9347414Z 	at org.gradle.api.internal.tasks.execution.ResolveTaskExecutionModeExecuter.execute(ResolveTaskExecutionModeExecuter.java:51)
2026-08-17T00:54:34.9376201Z 	at org.gradle.api.internal.tasks.execution.SkipTaskWithNoActionsExecuter.execute(SkipTaskWithNoActionsExecuter.java:57)
2026-08-17T00:54:34.9400746Z 	at org.gradle.api.internal.tasks.execution.SkipOnlyIfTaskExecuter.execute(SkipOnlyIfTaskExecuter.java:74)
2026-08-17T00:54:34.9426488Z 	at org.gradle.api.internal.tasks.execution.CatchExceptionTaskExecuter.execute(CatchExceptionTaskExecuter.java:36)
2026-08-17T00:54:34.9456416Z 	at org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter$1.executeTask(EventFiringTaskExecuter.java:77)
2026-08-17T00:54:34.9466265Z 	at org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter$1.call(EventFiringTaskExecuter.java:55)
2026-08-17T00:54:34.9496435Z 	at org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter$1.call(EventFiringTaskExecuter.java:52)
2026-08-17T00:54:34.9526546Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$CallableBuildOperationWorker.execute(DefaultBuildOperationRunner.java:204)
2026-08-17T00:54:34.9550005Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$CallableBuildOperationWorker.execute(DefaultBuildOperationRunner.java:199)
2026-08-17T00:54:34.9576423Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$2.execute(DefaultBuildOperationRunner.java:66)
2026-08-17T00:54:34.9595400Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$2.execute(DefaultBuildOperationRunner.java:59)
2026-08-17T00:54:34.9627294Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:157)
2026-08-17T00:54:34.9656777Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:59)
2026-08-17T00:54:34.9686362Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.call(DefaultBuildOperationRunner.java:53)
2026-08-17T00:54:34.9701058Z 	at org.gradle.internal.operations.DefaultBuildOperationExecutor.call(DefaultBuildOperationExecutor.java:73)
2026-08-17T00:54:34.9719092Z 	at org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter.execute(EventFiringTaskExecuter.java:52)
2026-08-17T00:54:34.9746168Z 	at org.gradle.execution.plan.LocalTaskNodeExecutor.execute(LocalTaskNodeExecutor.java:42)
2026-08-17T00:54:34.9776567Z 	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$InvokeNodeExecutorsAction.execute(DefaultTaskExecutionGraph.java:331)
2026-08-17T00:54:34.9786361Z 	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$InvokeNodeExecutorsAction.execute(DefaultTaskExecutionGraph.java:318)
2026-08-17T00:54:34.9816685Z 	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$BuildOperationAwareExecutionAction.lambda$execute$0(DefaultTaskExecutionGraph.java:314)
2026-08-17T00:54:34.9841231Z 	at org.gradle.internal.operations.CurrentBuildOperationRef.with(CurrentBuildOperationRef.java:80)
2026-08-17T00:54:34.9847093Z 	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$BuildOperationAwareExecutionAction.execute(DefaultTaskExecutionGraph.java:314)
2026-08-17T00:54:34.9849338Z 	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$BuildOperationAwareExecutionAction.execute(DefaultTaskExecutionGraph.java:303)
2026-08-17T00:54:34.9851180Z 	at org.gradle.execution.plan.DefaultPlanExecutor$ExecutorWorker.execute(DefaultPlanExecutor.java:463)
2026-08-17T00:54:34.9852662Z 	at org.gradle.execution.plan.DefaultPlanExecutor$ExecutorWorker.run(DefaultPlanExecutor.java:380)
2026-08-17T00:54:34.9854521Z 	at org.gradle.internal.concurrent.ExecutorPolicy$CatchAndRecordFailures.onExecute(ExecutorPolicy.java:64)
2026-08-17T00:54:34.9856343Z 	at org.gradle.internal.concurrent.AbstractManagedExecutor$1.run(AbstractManagedExecutor.java:47)
2026-08-17T00:54:34.9858966Z Caused by: org.gradle.workers.internal.DefaultWorkerExecutor$WorkExecutionException: A failure occurred while executing org.jetbrains.kotlin.compilerRunner.GradleCompilerRunnerWithWorkers$GradleKotlinCompilerWorkAction
2026-08-17T00:54:34.9861460Z 	at org.gradle.workers.internal.DefaultWorkerExecutor$WorkItemExecution.waitForCompletion(DefaultWorkerExecutor.java:283)
2026-08-17T00:54:34.9863367Z 	at org.gradle.internal.work.DefaultAsyncWorkTracker.lambda$waitForItemsAndGatherFailures$2(DefaultAsyncWorkTracker.java:130)
2026-08-17T00:54:34.9864726Z 	at org.gradle.internal.Factories$1.create(Factories.java:31)
2026-08-17T00:54:34.9866200Z 	at org.gradle.internal.work.DefaultWorkerLeaseService.withoutLocks(DefaultWorkerLeaseService.java:336)
2026-08-17T00:54:34.9867828Z 	at org.gradle.internal.work.DefaultWorkerLeaseService.withoutLocks(DefaultWorkerLeaseService.java:319)
2026-08-17T00:54:34.9869441Z 	at org.gradle.internal.work.DefaultWorkerLeaseService.withoutLock(DefaultWorkerLeaseService.java:324)
2026-08-17T00:54:34.9871202Z 	at org.gradle.internal.work.DefaultAsyncWorkTracker.waitForItemsAndGatherFailures(DefaultAsyncWorkTracker.java:126)
2026-08-17T00:54:34.9873047Z 	at org.gradle.internal.work.DefaultAsyncWorkTracker.waitForItemsAndGatherFailures(DefaultAsyncWorkTracker.java:92)
2026-08-17T00:54:34.9875176Z 	at org.gradle.internal.work.DefaultAsyncWorkTracker.waitForAll(DefaultAsyncWorkTracker.java:78)
2026-08-17T00:54:34.9876732Z 	at org.gradle.internal.work.DefaultAsyncWorkTracker.waitForCompletion(DefaultAsyncWorkTracker.java:66)
2026-08-17T00:54:34.9878186Z 	at org.gradle.api.internal.tasks.execution.TaskExecution$3.run(TaskExecution.java:256)
2026-08-17T00:54:34.9879702Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$1.execute(DefaultBuildOperationRunner.java:29)
2026-08-17T00:54:34.9881434Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$1.execute(DefaultBuildOperationRunner.java:26)
2026-08-17T00:54:34.9883081Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$2.execute(DefaultBuildOperationRunner.java:66)
2026-08-17T00:54:34.9884755Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$2.execute(DefaultBuildOperationRunner.java:59)
2026-08-17T00:54:34.9886690Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:157)
2026-08-17T00:54:34.9888523Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:59)
2026-08-17T00:54:34.9889562Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.run(DefaultBuildOperationRunner.java:47)
2026-08-17T00:54:34.9890572Z 	at org.gradle.internal.operations.DefaultBuildOperationExecutor.run(DefaultBuildOperationExecutor.java:68)
2026-08-17T00:54:34.9896443Z 	at org.gradle.api.internal.tasks.execution.TaskExecution.executeAction(TaskExecution.java:233)
2026-08-17T00:54:34.9898944Z 	at org.gradle.api.internal.tasks.execution.TaskExecution.executeActions(TaskExecution.java:216)
2026-08-17T00:54:34.9900975Z 	at org.gradle.api.internal.tasks.execution.TaskExecution.executeWithPreviousOutputFiles(TaskExecution.java:199)
2026-08-17T00:54:34.9902879Z 	at org.gradle.api.internal.tasks.execution.TaskExecution.execute(TaskExecution.java:166)
2026-08-17T00:54:34.9904536Z 	at org.gradle.internal.execution.steps.ExecuteStep.executeInternal(ExecuteStep.java:105)
2026-08-17T00:54:34.9906610Z 	at org.gradle.internal.execution.steps.ExecuteStep.access$000(ExecuteStep.java:44)
2026-08-17T00:54:34.9908075Z 	at org.gradle.internal.execution.steps.ExecuteStep$1.call(ExecuteStep.java:59)
2026-08-17T00:54:34.9909467Z 	at org.gradle.internal.execution.steps.ExecuteStep$1.call(ExecuteStep.java:56)
2026-08-17T00:54:34.9912037Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$CallableBuildOperationWorker.execute(DefaultBuildOperationRunner.java:204)
2026-08-17T00:54:34.9914617Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$CallableBuildOperationWorker.execute(DefaultBuildOperationRunner.java:199)
2026-08-17T00:54:34.9917082Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$2.execute(DefaultBuildOperationRunner.java:66)
2026-08-17T00:54:34.9918962Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$2.execute(DefaultBuildOperationRunner.java:59)
2026-08-17T00:54:34.9920918Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:157)
2026-08-17T00:54:34.9922853Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:59)
2026-08-17T00:54:34.9924790Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.call(DefaultBuildOperationRunner.java:53)
2026-08-17T00:54:34.9926975Z 	at org.gradle.internal.operations.DefaultBuildOperationExecutor.call(DefaultBuildOperationExecutor.java:73)
2026-08-17T00:54:34.9928640Z 	at org.gradle.internal.execution.steps.ExecuteStep.execute(ExecuteStep.java:56)
2026-08-17T00:54:34.9930070Z 	at org.gradle.internal.execution.steps.ExecuteStep.execute(ExecuteStep.java:44)
2026-08-17T00:54:34.9931765Z 	at org.gradle.internal.execution.steps.RemovePreviousOutputsStep.execute(RemovePreviousOutputsStep.java:67)
2026-08-17T00:54:34.9933677Z 	at org.gradle.internal.execution.steps.RemovePreviousOutputsStep.execute(RemovePreviousOutputsStep.java:37)
2026-08-17T00:54:34.9935964Z 	at org.gradle.internal.execution.steps.CancelExecutionStep.execute(CancelExecutionStep.java:41)
2026-08-17T00:54:34.9937655Z 	at org.gradle.internal.execution.steps.TimeoutStep.executeWithoutTimeout(TimeoutStep.java:74)
2026-08-17T00:54:34.9939181Z 	at org.gradle.internal.execution.steps.TimeoutStep.execute(TimeoutStep.java:55)
2026-08-17T00:54:34.9940687Z 	at org.gradle.internal.execution.steps.CreateOutputsStep.execute(CreateOutputsStep.java:50)
2026-08-17T00:54:34.9942257Z 	at org.gradle.internal.execution.steps.CreateOutputsStep.execute(CreateOutputsStep.java:28)
2026-08-17T00:54:34.9944532Z 	at org.gradle.internal.execution.steps.CaptureStateAfterExecutionStep.executeDelegateBroadcastingChanges(CaptureStateAfterExecutionStep.java:100)
2026-08-17T00:54:34.9947237Z 	at org.gradle.internal.execution.steps.CaptureStateAfterExecutionStep.execute(CaptureStateAfterExecutionStep.java:72)
2026-08-17T00:54:34.9949413Z 	at org.gradle.internal.execution.steps.CaptureStateAfterExecutionStep.execute(CaptureStateAfterExecutionStep.java:50)
2026-08-17T00:54:34.9951413Z 	at org.gradle.internal.execution.steps.ResolveInputChangesStep.execute(ResolveInputChangesStep.java:40)
2026-08-17T00:54:34.9953260Z 	at org.gradle.internal.execution.steps.ResolveInputChangesStep.execute(ResolveInputChangesStep.java:29)
2026-08-17T00:54:34.9955285Z 	at org.gradle.internal.execution.steps.BuildCacheStep.executeWithoutCache(BuildCacheStep.java:179)
2026-08-17T00:54:34.9957109Z 	at org.gradle.internal.execution.steps.BuildCacheStep.lambda$execute$1(BuildCacheStep.java:70)
2026-08-17T00:54:34.9958402Z 	at org.gradle.internal.Either$Right.fold(Either.java:175)
2026-08-17T00:54:34.9960072Z 	at org.gradle.internal.execution.caching.CachingState.fold(CachingState.java:59)
2026-08-17T00:54:34.9961516Z 	at org.gradle.internal.execution.steps.BuildCacheStep.execute(BuildCacheStep.java:68)
2026-08-17T00:54:34.9962970Z 	at org.gradle.internal.execution.steps.BuildCacheStep.execute(BuildCacheStep.java:46)
2026-08-17T00:54:34.9964656Z 	at org.gradle.internal.execution.steps.StoreExecutionStateStep.execute(StoreExecutionStateStep.java:36)
2026-08-17T00:54:34.9966731Z 	at org.gradle.internal.execution.steps.StoreExecutionStateStep.execute(StoreExecutionStateStep.java:25)
2026-08-17T00:54:34.9968485Z 	at org.gradle.internal.execution.steps.RecordOutputsStep.execute(RecordOutputsStep.java:36)
2026-08-17T00:54:34.9970773Z 	at org.gradle.internal.execution.steps.RecordOutputsStep.execute(RecordOutputsStep.java:22)
2026-08-17T00:54:34.9972785Z 	at org.gradle.internal.execution.steps.SkipUpToDateStep.executeBecause(SkipUpToDateStep.java:91)
2026-08-17T00:54:34.9974557Z 	at org.gradle.internal.execution.steps.SkipUpToDateStep.lambda$execute$2(SkipUpToDateStep.java:55)
2026-08-17T00:54:34.9976438Z 	at org.gradle.internal.execution.steps.SkipUpToDateStep.execute(SkipUpToDateStep.java:55)
2026-08-17T00:54:34.9978006Z 	at org.gradle.internal.execution.steps.SkipUpToDateStep.execute(SkipUpToDateStep.java:37)
2026-08-17T00:54:34.9979587Z 	at org.gradle.internal.execution.steps.ResolveChangesStep.execute(ResolveChangesStep.java:65)
2026-08-17T00:54:34.9981258Z 	at org.gradle.internal.execution.steps.ResolveChangesStep.execute(ResolveChangesStep.java:36)
2026-08-17T00:54:34.9983391Z 	at org.gradle.internal.execution.steps.legacy.MarkSnapshottingInputsFinishedStep.execute(MarkSnapshottingInputsFinishedStep.java:37)
2026-08-17T00:54:34.9986085Z 	at org.gradle.internal.execution.steps.legacy.MarkSnapshottingInputsFinishedStep.execute(MarkSnapshottingInputsFinishedStep.java:27)
2026-08-17T00:54:34.9988253Z 	at org.gradle.internal.execution.steps.ResolveCachingStateStep.execute(ResolveCachingStateStep.java:76)
2026-08-17T00:54:34.9990090Z 	at org.gradle.internal.execution.steps.ResolveCachingStateStep.execute(ResolveCachingStateStep.java:37)
2026-08-17T00:54:34.9991713Z 	at org.gradle.internal.execution.steps.ValidateStep.execute(ValidateStep.java:108)
2026-08-17T00:54:34.9993475Z 	at org.gradle.internal.execution.steps.ValidateStep.execute(ValidateStep.java:55)
2026-08-17T00:54:34.9995757Z 	at org.gradle.internal.execution.steps.CaptureStateBeforeExecutionStep.execute(CaptureStateBeforeExecutionStep.java:71)
2026-08-17T00:54:34.9997924Z 	at org.gradle.internal.execution.steps.CaptureStateBeforeExecutionStep.execute(CaptureStateBeforeExecutionStep.java:45)
2026-08-17T00:54:35.0000037Z 	at org.gradle.internal.execution.steps.SkipEmptyWorkStep.executeWithNonEmptySources(SkipEmptyWorkStep.java:177)
2026-08-17T00:54:35.0001841Z 	at org.gradle.internal.execution.steps.SkipEmptyWorkStep.execute(SkipEmptyWorkStep.java:86)
2026-08-17T00:54:35.0003412Z 	at org.gradle.internal.execution.steps.SkipEmptyWorkStep.execute(SkipEmptyWorkStep.java:53)
2026-08-17T00:54:35.0005682Z 	at org.gradle.internal.execution.steps.RemoveUntrackedExecutionStateStep.execute(RemoveUntrackedExecutionStateStep.java:32)
2026-08-17T00:54:35.0008013Z 	at org.gradle.internal.execution.steps.RemoveUntrackedExecutionStateStep.execute(RemoveUntrackedExecutionStateStep.java:21)
2026-08-17T00:54:35.0010437Z 	at org.gradle.internal.execution.steps.legacy.MarkSnapshottingInputsStartedStep.execute(MarkSnapshottingInputsStartedStep.java:38)
2026-08-17T00:54:35.0012738Z 	at org.gradle.internal.execution.steps.LoadPreviousExecutionStateStep.execute(LoadPreviousExecutionStateStep.java:36)
2026-08-17T00:54:35.0015083Z 	at org.gradle.internal.execution.steps.LoadPreviousExecutionStateStep.execute(LoadPreviousExecutionStateStep.java:23)
2026-08-17T00:54:35.0017096Z 	at org.gradle.internal.execution.steps.CleanupStaleOutputsStep.execute(CleanupStaleOutputsStep.java:75)
2026-08-17T00:54:35.0018954Z 	at org.gradle.internal.execution.steps.CleanupStaleOutputsStep.execute(CleanupStaleOutputsStep.java:41)
2026-08-17T00:54:35.0021176Z 	at org.gradle.internal.execution.steps.ExecuteWorkBuildOperationFiringStep.lambda$execute$2(ExecuteWorkBuildOperationFiringStep.java:66)
2026-08-17T00:54:35.0023697Z 	at org.gradle.internal.execution.steps.ExecuteWorkBuildOperationFiringStep.execute(ExecuteWorkBuildOperationFiringStep.java:66)
2026-08-17T00:54:35.0026406Z 	at org.gradle.internal.execution.steps.ExecuteWorkBuildOperationFiringStep.execute(ExecuteWorkBuildOperationFiringStep.java:38)
2026-08-17T00:54:35.0028477Z 	at org.gradle.internal.execution.steps.AssignWorkspaceStep.lambda$execute$0(AssignWorkspaceStep.java:32)
2026-08-17T00:54:35.0030189Z 	at org.gradle.api.internal.tasks.execution.TaskExecution$4.withWorkspace(TaskExecution.java:293)
2026-08-17T00:54:35.0032098Z 	at org.gradle.internal.execution.steps.AssignWorkspaceStep.execute(AssignWorkspaceStep.java:30)
2026-08-17T00:54:35.0033777Z 	at org.gradle.internal.execution.steps.AssignWorkspaceStep.execute(AssignWorkspaceStep.java:21)
2026-08-17T00:54:35.0035642Z 	at org.gradle.internal.execution.steps.IdentityCacheStep.execute(IdentityCacheStep.java:37)
2026-08-17T00:54:35.0037306Z 	at org.gradle.internal.execution.steps.IdentityCacheStep.execute(IdentityCacheStep.java:27)
2026-08-17T00:54:35.0038806Z 	at org.gradle.internal.execution.steps.IdentifyStep.execute(IdentifyStep.java:47)
2026-08-17T00:54:35.0040227Z 	at org.gradle.internal.execution.steps.IdentifyStep.execute(IdentifyStep.java:34)
2026-08-17T00:54:35.0041806Z 	at org.gradle.internal.execution.impl.DefaultExecutionEngine$1.execute(DefaultExecutionEngine.java:64)
2026-08-17T00:54:35.0043922Z 	at org.gradle.api.internal.tasks.execution.ExecuteActionsTaskExecuter.executeIfValid(ExecuteActionsTaskExecuter.java:145)
2026-08-17T00:54:35.0046300Z 	at org.gradle.api.internal.tasks.execution.ExecuteActionsTaskExecuter.execute(ExecuteActionsTaskExecuter.java:134)
2026-08-17T00:54:35.0048450Z 	at org.gradle.api.internal.tasks.execution.FinalizePropertiesTaskExecuter.execute(FinalizePropertiesTaskExecuter.java:46)
2026-08-17T00:54:35.0050691Z 	at org.gradle.api.internal.tasks.execution.ResolveTaskExecutionModeExecuter.execute(ResolveTaskExecutionModeExecuter.java:51)
2026-08-17T00:54:35.0052928Z 	at org.gradle.api.internal.tasks.execution.SkipTaskWithNoActionsExecuter.execute(SkipTaskWithNoActionsExecuter.java:57)
2026-08-17T00:54:35.0055486Z 	at org.gradle.api.internal.tasks.execution.SkipOnlyIfTaskExecuter.execute(SkipOnlyIfTaskExecuter.java:74)
2026-08-17T00:54:35.0057435Z 	at org.gradle.api.internal.tasks.execution.CatchExceptionTaskExecuter.execute(CatchExceptionTaskExecuter.java:36)
2026-08-17T00:54:35.0059518Z 	at org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter$1.executeTask(EventFiringTaskExecuter.java:77)
2026-08-17T00:54:35.0061429Z 	at org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter$1.call(EventFiringTaskExecuter.java:55)
2026-08-17T00:54:35.0063313Z 	at org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter$1.call(EventFiringTaskExecuter.java:52)
2026-08-17T00:54:35.0065745Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$CallableBuildOperationWorker.execute(DefaultBuildOperationRunner.java:204)
2026-08-17T00:54:35.0068228Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$CallableBuildOperationWorker.execute(DefaultBuildOperationRunner.java:199)
2026-08-17T00:54:35.0070398Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$2.execute(DefaultBuildOperationRunner.java:66)
2026-08-17T00:54:35.0072299Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$2.execute(DefaultBuildOperationRunner.java:59)
2026-08-17T00:54:35.0074202Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:157)
2026-08-17T00:54:35.0076367Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:59)
2026-08-17T00:54:35.0078231Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.call(DefaultBuildOperationRunner.java:53)
2026-08-17T00:54:35.0080141Z 	at org.gradle.internal.operations.DefaultBuildOperationExecutor.call(DefaultBuildOperationExecutor.java:73)
2026-08-17T00:54:35.0082067Z 	at org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter.execute(EventFiringTaskExecuter.java:52)
2026-08-17T00:54:35.0083777Z 	at org.gradle.execution.plan.LocalTaskNodeExecutor.execute(LocalTaskNodeExecutor.java:42)
2026-08-17T00:54:35.0085969Z 	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$InvokeNodeExecutorsAction.execute(DefaultTaskExecutionGraph.java:331)
2026-08-17T00:54:35.0088214Z 	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$InvokeNodeExecutorsAction.execute(DefaultTaskExecutionGraph.java:318)
2026-08-17T00:54:35.0090910Z 	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$BuildOperationAwareExecutionAction.lambda$execute$0(DefaultTaskExecutionGraph.java:314)
2026-08-17T00:54:35.0093067Z 	at org.gradle.internal.operations.CurrentBuildOperationRef.with(CurrentBuildOperationRef.java:80)
2026-08-17T00:54:35.0095437Z 	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$BuildOperationAwareExecutionAction.execute(DefaultTaskExecutionGraph.java:314)
2026-08-17T00:54:35.0097919Z 	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$BuildOperationAwareExecutionAction.execute(DefaultTaskExecutionGraph.java:303)
2026-08-17T00:54:35.0099942Z 	at org.gradle.execution.plan.DefaultPlanExecutor$ExecutorWorker.execute(DefaultPlanExecutor.java:463)
2026-08-17T00:54:35.0101613Z 	at org.gradle.execution.plan.DefaultPlanExecutor$ExecutorWorker.run(DefaultPlanExecutor.java:380)
2026-08-17T00:54:35.0103339Z 	at org.gradle.internal.concurrent.ExecutorPolicy$CatchAndRecordFailures.onExecute(ExecutorPolicy.java:64)
2026-08-17T00:54:35.0105335Z 	at org.gradle.internal.concurrent.AbstractManagedExecutor$1.run(AbstractManagedExecutor.java:47)
2026-08-17T00:54:35.0107176Z Caused by: org.jetbrains.kotlin.gradle.tasks.CompilationErrorException: Compilation error. See log for more details
2026-08-17T00:54:35.0109034Z 	at org.jetbrains.kotlin.gradle.tasks.TasksUtilsKt.throwExceptionIfCompilationFailed(tasksUtils.kt:20)
2026-08-17T00:54:35.0110818Z 	at org.jetbrains.kotlin.compilerRunner.GradleKotlinCompilerWork.run(GradleKotlinCompilerWork.kt:141)
2026-08-17T00:54:35.0113093Z 	at org.jetbrains.kotlin.compilerRunner.GradleCompilerRunnerWithWorkers$GradleKotlinCompilerWorkAction.execute(GradleCompilerRunnerWithWorkers.kt:73)
2026-08-17T00:54:35.0115563Z 	at org.gradle.workers.internal.DefaultWorkerServer.execute(DefaultWorkerServer.java:63)
2026-08-17T00:54:35.0117170Z 	at org.gradle.workers.internal.NoIsolationWorkerFactory$1$1.create(NoIsolationWorkerFactory.java:66)
2026-08-17T00:54:35.0118882Z 	at org.gradle.workers.internal.NoIsolationWorkerFactory$1$1.create(NoIsolationWorkerFactory.java:62)
2026-08-17T00:54:35.0120628Z 	at org.gradle.internal.classloader.ClassLoaderUtils.executeInClassloader(ClassLoaderUtils.java:100)
2026-08-17T00:54:35.0122409Z 	at org.gradle.workers.internal.NoIsolationWorkerFactory$1.lambda$execute$0(NoIsolationWorkerFactory.java:62)
2026-08-17T00:54:35.0123924Z 	at org.gradle.workers.internal.AbstractWorker$1.call(AbstractWorker.java:44)
2026-08-17T00:54:35.0125372Z 	at org.gradle.workers.internal.AbstractWorker$1.call(AbstractWorker.java:41)
2026-08-17T00:54:35.0127248Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$CallableBuildOperationWorker.execute(DefaultBuildOperationRunner.java:204)
2026-08-17T00:54:35.0129654Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$CallableBuildOperationWorker.execute(DefaultBuildOperationRunner.java:199)
2026-08-17T00:54:35.0131795Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$2.execute(DefaultBuildOperationRunner.java:66)
2026-08-17T00:54:35.0133694Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$2.execute(DefaultBuildOperationRunner.java:59)
2026-08-17T00:54:35.0135798Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:157)
2026-08-17T00:54:35.0137706Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:59)
2026-08-17T00:54:35.0139582Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.call(DefaultBuildOperationRunner.java:53)
2026-08-17T00:54:35.0141471Z 	at org.gradle.internal.operations.DefaultBuildOperationExecutor.call(DefaultBuildOperationExecutor.java:73)
2026-08-17T00:54:35.0143308Z 	at org.gradle.workers.internal.AbstractWorker.executeWrappedInBuildOperation(AbstractWorker.java:41)
2026-08-17T00:54:35.0145259Z 	at org.gradle.workers.internal.NoIsolationWorkerFactory$1.execute(NoIsolationWorkerFactory.java:59)
2026-08-17T00:54:35.0146998Z 	at org.gradle.workers.internal.DefaultWorkerExecutor.lambda$submitWork$0(DefaultWorkerExecutor.java:170)
2026-08-17T00:54:35.0149350Z 	at org.gradle.internal.work.DefaultConditionalExecutionQueue$ExecutionRunner.runExecution(DefaultConditionalExecutionQueue.java:187)
2026-08-17T00:54:35.0151632Z 	at org.gradle.internal.work.DefaultConditionalExecutionQueue$ExecutionRunner.access$700(DefaultConditionalExecutionQueue.java:120)
2026-08-17T00:54:35.0153857Z 	at org.gradle.internal.work.DefaultConditionalExecutionQueue$ExecutionRunner$1.run(DefaultConditionalExecutionQueue.java:162)
2026-08-17T00:54:35.0155596Z 	at org.gradle.internal.Factories$1.create(Factories.java:31)
2026-08-17T00:54:35.0156995Z 	at org.gradle.internal.work.DefaultWorkerLeaseService.withLocks(DefaultWorkerLeaseService.java:264)
2026-08-17T00:54:35.0158806Z 	at org.gradle.internal.work.DefaultWorkerLeaseService.runAsWorkerThread(DefaultWorkerLeaseService.java:128)
2026-08-17T00:54:35.0160773Z 	at org.gradle.internal.work.DefaultWorkerLeaseService.runAsWorkerThread(DefaultWorkerLeaseService.java:133)
2026-08-17T00:54:35.0162858Z 	at org.gradle.internal.work.DefaultConditionalExecutionQueue$ExecutionRunner.runBatch(DefaultConditionalExecutionQueue.java:157)
2026-08-17T00:54:35.0165367Z 	at org.gradle.internal.work.DefaultConditionalExecutionQueue$ExecutionRunner.run(DefaultConditionalExecutionQueue.java:126)
2026-08-17T00:54:35.0166622Z 	... 2 more
2026-08-17T00:54:35.0166853Z 
2026-08-17T00:54:35.0166864Z 
2026-08-17T00:54:35.0167100Z BUILD FAILED in 37s
2026-08-17T00:54:35.3985691Z ##[error]Process completed with exit code 1.
2026-08-17T00:54:35.4053900Z Node 20 is being deprecated. This workflow is running with Node 24 by default. If you need to temporarily use Node 20, you can set the ACTIONS_ALLOW_USE_UNSECURE_NODE_VERSION=true environment variable. For more information see: https://github.blog/changelog/2025-09-19-deprecation-of-node-20-on-github-actions-runners/
2026-08-17T00:54:35.4056593Z ##[group]Run actions/upload-artifact@v4
2026-08-17T00:54:35.4057176Z with:
2026-08-17T00:54:35.4057590Z   name: build-logs
2026-08-17T00:54:35.4058203Z   path: app/build/reports/**
app/build/outputs/logs/**
**/*.log

2026-08-17T00:54:35.4058918Z   if-no-files-found: ignore
2026-08-17T00:54:35.4059429Z   retention-days: 7
2026-08-17T00:54:35.4059871Z   compression-level: 6
2026-08-17T00:54:35.4060329Z   overwrite: false
2026-08-17T00:54:35.4060793Z   include-hidden-files: false
2026-08-17T00:54:35.4061278Z env:
2026-08-17T00:54:35.4061647Z   GRADLE_VERSION: 8.5
2026-08-17T00:54:35.4062087Z   JAVA_VERSION: 17
2026-08-17T00:54:35.4062504Z   JAVA_HOME: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T00:54:35.4063055Z   JAVA_HOME_17_X64: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T00:54:35.4063518Z   GRADLE_ACTION_ID: gradle/actions/setup-gradle
2026-08-17T00:54:35.4063873Z   GRADLE_USER_HOME: /home/runner/.gradle
2026-08-17T00:54:35.4064206Z   GRADLE_BUILD_ACTION_SETUP_COMPLETED: true
2026-08-17T00:54:35.4064550Z   GRADLE_BUILD_ACTION_CACHE_RESTORED: true
2026-08-17T00:54:35.4065424Z   DEVELOCITY_INJECTION_INIT_SCRIPT_NAME: gradle-actions.inject-develocity.init.gradle
2026-08-17T00:54:35.4065981Z   DEVELOCITY_INJECTION_CUSTOM_VALUE: gradle-actions
2026-08-17T00:54:35.4066353Z   GITHUB_DEPENDENCY_GRAPH_ENABLED: false
2026-08-17T00:54:35.4066688Z   ANDROID_HOME: /usr/local/lib/android/sdk
2026-08-17T00:54:35.4067034Z   ANDROID_SDK_ROOT: /usr/local/lib/android/sdk
2026-08-17T00:54:35.4067401Z ##[endgroup]
2026-08-17T00:54:35.5886592Z (node:3134) [DEP0040] DeprecationWarning: The `punycode` module is deprecated. Please use a userland alternative instead.
2026-08-17T00:54:35.5888221Z (Use `node --trace-deprecation ...` to show where the warning was created)
2026-08-17T00:54:35.7588146Z With the provided path, there will be 1 file uploaded
2026-08-17T00:54:35.7597182Z Artifact name is valid!
2026-08-17T00:54:35.7598146Z Root directory input is valid!
2026-08-17T00:54:36.0797177Z Beginning upload of artifact content to blob storage
2026-08-17T00:54:36.1011618Z (node:3134) [DEP0169] DeprecationWarning: `url.parse()` behavior is not standardized and prone to errors that have security implications. Use the WHATWG URL API instead. CVEs are not issued for `url.parse()` vulnerabilities.
2026-08-17T00:54:36.3892652Z Uploaded bytes 8592
2026-08-17T00:54:36.4645639Z Finished uploading artifact content to blob storage!
2026-08-17T00:54:36.4647221Z SHA256 digest of uploaded artifact zip is cf9f421068ff1c6e10706cfe7db18e29bff1d1ef8df31f3c68a3e2d287a69400
2026-08-17T00:54:36.4648404Z Finalizing artifact upload
2026-08-17T00:54:36.6754329Z Artifact build-logs.zip successfully finalized. Artifact ID 9273014376
2026-08-17T00:54:36.6756131Z Artifact build-logs has been successfully uploaded! Final size is 8592 bytes. Artifact ID is 9273014376
2026-08-17T00:54:36.6762727Z Artifact download URL: https://github.com/Pikarziur/AutoBOT/actions/runs/31983293087/artifacts/9273014376
2026-08-17T00:54:36.7017755Z Node 20 is being deprecated. This workflow is running with Node 24 by default. If you need to temporarily use Node 20, you can set the ACTIONS_ALLOW_USE_UNSECURE_NODE_VERSION=true environment variable. For more information see: https://github.blog/changelog/2025-09-19-deprecation-of-node-20-on-github-actions-runners/
2026-08-17T00:54:36.7019106Z Post job cleanup.
2026-08-17T00:54:36.9424573Z In post-action step
2026-08-17T00:54:36.9439332Z ##[group]Stopping Gradle daemons
2026-08-17T00:54:36.9440836Z Stopping Gradle daemons for /home/runner/work/_temp/.gradle-actions/gradle-installations/installs/gradle-8.5
2026-08-17T00:54:36.9455220Z Stopping Gradle daemons for /home/runner/.gradle/wrapper/dists/gradle-8.5-bin/5t9huq95ubn472n8rpzujfbqh/gradle-8.5
2026-08-17T00:54:36.9463906Z [command]/home/runner/work/_temp/.gradle-actions/gradle-installations/installs/gradle-8.5/bin/gradle --stop
2026-08-17T00:54:36.9533478Z [command]/home/runner/.gradle/wrapper/dists/gradle-8.5-bin/5t9huq95ubn472n8rpzujfbqh/gradle-8.5/bin/gradle --stop
2026-08-17T00:54:38.4838273Z No Gradle daemons are running.
2026-08-17T00:54:38.5066062Z No Gradle daemons are running.
2026-08-17T00:54:38.5154151Z ##[endgroup]
2026-08-17T00:54:38.5157202Z Not performing cache-cleanup due to build failure
2026-08-17T00:54:38.5158269Z ##[group]Caching Gradle state
2026-08-17T00:54:39.1233376Z [command]/usr/bin/tar --posix -cf cache.tzst --exclude cache.tzst -P -C /home/runner/work/AutoBOT/AutoBOT --files-from manifest.txt --use-compress-program zstdmt
2026-08-17T00:54:41.5696471Z Sent 0 of 143458901 (0.0%), 0.0 MBs/sec
2026-08-17T00:54:42.5698622Z Sent 9241173 of 143458901 (6.4%), 4.4 MBs/sec
2026-08-17T00:54:43.5706947Z Sent 76350037 of 143458901 (53.2%), 24.3 MBs/sec
2026-08-17T00:54:44.5716879Z Sent 76350037 of 143458901 (53.2%), 18.2 MBs/sec
2026-08-17T00:54:45.5726260Z Sent 76350037 of 143458901 (53.2%), 14.6 MBs/sec
2026-08-17T00:54:46.5738591Z Sent 76350037 of 143458901 (53.2%), 12.1 MBs/sec
2026-08-17T00:54:47.5740541Z Sent 76350037 of 143458901 (53.2%), 10.4 MBs/sec
2026-08-17T00:54:48.5753267Z Sent 76350037 of 143458901 (53.2%), 9.1 MBs/sec
2026-08-17T00:54:49.5766516Z Sent 76350037 of 143458901 (53.2%), 8.1 MBs/sec
2026-08-17T00:54:50.5775471Z Sent 76350037 of 143458901 (53.2%), 7.3 MBs/sec
2026-08-17T00:54:51.5787732Z Sent 76350037 of 143458901 (53.2%), 6.6 MBs/sec
2026-08-17T00:54:52.5799912Z Sent 76350037 of 143458901 (53.2%), 6.1 MBs/sec
2026-08-17T00:54:53.5803351Z Sent 76350037 of 143458901 (53.2%), 5.6 MBs/sec
2026-08-17T00:54:54.5818722Z Sent 76350037 of 143458901 (53.2%), 5.2 MBs/sec
2026-08-17T00:54:55.5829472Z Sent 76350037 of 143458901 (53.2%), 4.8 MBs/sec
2026-08-17T00:54:56.5842836Z Sent 76350037 of 143458901 (53.2%), 4.5 MBs/sec
2026-08-17T00:54:57.5855250Z Sent 76350037 of 143458901 (53.2%), 4.3 MBs/sec
2026-08-17T00:54:58.5867358Z Sent 76350037 of 143458901 (53.2%), 4.0 MBs/sec
2026-08-17T00:54:59.5879694Z Sent 76350037 of 143458901 (53.2%), 3.8 MBs/sec
2026-08-17T00:55:00.5891456Z Sent 76350037 of 143458901 (53.2%), 3.6 MBs/sec
2026-08-17T00:55:01.5900624Z Sent 76350037 of 143458901 (53.2%), 3.5 MBs/sec
2026-08-17T00:55:02.5913350Z Sent 76350037 of 143458901 (53.2%), 3.3 MBs/sec
2026-08-17T00:55:03.5926355Z Sent 76350037 of 143458901 (53.2%), 3.2 MBs/sec
2026-08-17T00:55:04.5934007Z Sent 76350037 of 143458901 (53.2%), 3.0 MBs/sec
2026-08-17T00:55:05.5946531Z Sent 76350037 of 143458901 (53.2%), 2.9 MBs/sec
2026-08-17T00:55:06.5957849Z Sent 76350037 of 143458901 (53.2%), 2.8 MBs/sec
2026-08-17T00:55:07.5970632Z Sent 76350037 of 143458901 (53.2%), 2.7 MBs/sec
2026-08-17T00:55:08.5980798Z Sent 76350037 of 143458901 (53.2%), 2.6 MBs/sec
2026-08-17T00:55:09.5984180Z Sent 76350037 of 143458901 (53.2%), 2.5 MBs/sec
2026-08-17T00:55:10.5997990Z Sent 76350037 of 143458901 (53.2%), 2.4 MBs/sec
2026-08-17T00:55:11.6010260Z Sent 76350037 of 143458901 (53.2%), 2.3 MBs/sec
2026-08-17T00:55:12.6006393Z Sent 76350037 of 143458901 (53.2%), 2.3 MBs/sec
2026-08-17T00:55:13.6018078Z Sent 76350037 of 143458901 (53.2%), 2.2 MBs/sec
2026-08-17T00:55:14.6028084Z Sent 76350037 of 143458901 (53.2%), 2.1 MBs/sec
2026-08-17T00:55:15.6040382Z Sent 76350037 of 143458901 (53.2%), 2.1 MBs/sec
2026-08-17T00:55:16.6046710Z Sent 76350037 of 143458901 (53.2%), 2.0 MBs/sec
2026-08-17T00:55:17.6049673Z Sent 76350037 of 143458901 (53.2%), 2.0 MBs/sec
2026-08-17T00:55:18.6062225Z Sent 76350037 of 143458901 (53.2%), 1.9 MBs/sec
2026-08-17T00:55:19.6078805Z Sent 76350037 of 143458901 (53.2%), 1.9 MBs/sec
2026-08-17T00:55:20.6091072Z Sent 76350037 of 143458901 (53.2%), 1.8 MBs/sec
2026-08-17T00:55:21.6103564Z Sent 76350037 of 143458901 (53.2%), 1.8 MBs/sec
2026-08-17T00:55:22.6121735Z Sent 76350037 of 143458901 (53.2%), 1.7 MBs/sec
2026-08-17T00:55:23.6134129Z Sent 76350037 of 143458901 (53.2%), 1.7 MBs/sec
2026-08-17T00:55:24.6156463Z Sent 76350037 of 143458901 (53.2%), 1.7 MBs/sec
2026-08-17T00:55:25.6157491Z Sent 76350037 of 143458901 (53.2%), 1.6 MBs/sec
2026-08-17T00:55:26.6169957Z Sent 76350037 of 143458901 (53.2%), 1.6 MBs/sec
2026-08-17T00:55:27.6180165Z Sent 76350037 of 143458901 (53.2%), 1.5 MBs/sec
2026-08-17T00:55:28.6191981Z Sent 76350037 of 143458901 (53.2%), 1.5 MBs/sec
2026-08-17T00:55:29.6208470Z Sent 76350037 of 143458901 (53.2%), 1.5 MBs/sec
2026-08-17T00:55:30.6220412Z Sent 76350037 of 143458901 (53.2%), 1.5 MBs/sec
2026-08-17T00:55:31.6231580Z Sent 76350037 of 143458901 (53.2%), 1.4 MBs/sec
2026-08-17T00:55:32.6250978Z Sent 76350037 of 143458901 (53.2%), 1.4 MBs/sec
2026-08-17T00:55:33.6262713Z Sent 76350037 of 143458901 (53.2%), 1.4 MBs/sec
2026-08-17T00:55:34.6278565Z Sent 76350037 of 143458901 (53.2%), 1.3 MBs/sec
2026-08-17T00:55:35.6290614Z Sent 76350037 of 143458901 (53.2%), 1.3 MBs/sec
2026-08-17T00:55:36.6309249Z Sent 76350037 of 143458901 (53.2%), 1.3 MBs/sec
2026-08-17T00:55:37.6320919Z Sent 76350037 of 143458901 (53.2%), 1.3 MBs/sec
2026-08-17T00:55:38.6329532Z Sent 76350037 of 143458901 (53.2%), 1.3 MBs/sec
2026-08-17T00:55:39.6341611Z Sent 76350037 of 143458901 (53.2%), 1.2 MBs/sec
2026-08-17T00:55:40.6359867Z Sent 76350037 of 143458901 (53.2%), 1.2 MBs/sec
2026-08-17T00:55:41.6372345Z Sent 76350037 of 143458901 (53.2%), 1.2 MBs/sec
2026-08-17T00:55:42.6385285Z Sent 76350037 of 143458901 (53.2%), 1.2 MBs/sec
2026-08-17T00:55:43.6396675Z Sent 76350037 of 143458901 (53.2%), 1.2 MBs/sec
2026-08-17T00:55:44.6407442Z Sent 76350037 of 143458901 (53.2%), 1.1 MBs/sec
2026-08-17T00:55:45.6419762Z Sent 76350037 of 143458901 (53.2%), 1.1 MBs/sec
2026-08-17T00:55:46.6431764Z Sent 76350037 of 143458901 (53.2%), 1.1 MBs/sec
2026-08-17T00:55:47.6444161Z Sent 76350037 of 143458901 (53.2%), 1.1 MBs/sec
2026-08-17T00:55:48.6453651Z Sent 76350037 of 143458901 (53.2%), 1.1 MBs/sec
2026-08-17T00:55:49.6465088Z Sent 76350037 of 143458901 (53.2%), 1.1 MBs/sec
2026-08-17T00:55:50.6468054Z Sent 76350037 of 143458901 (53.2%), 1.0 MBs/sec
2026-08-17T00:55:51.6472595Z Sent 76350037 of 143458901 (53.2%), 1.0 MBs/sec
2026-08-17T00:55:52.6484583Z Sent 76350037 of 143458901 (53.2%), 1.0 MBs/sec
2026-08-17T00:55:53.6496979Z Sent 76350037 of 143458901 (53.2%), 1.0 MBs/sec
2026-08-17T00:55:54.6509729Z Sent 76350037 of 143458901 (53.2%), 1.0 MBs/sec
2026-08-17T00:55:55.6521408Z Sent 76350037 of 143458901 (53.2%), 1.0 MBs/sec
2026-08-17T00:55:56.6530185Z Sent 76350037 of 143458901 (53.2%), 1.0 MBs/sec
2026-08-17T00:55:57.6542112Z Sent 76350037 of 143458901 (53.2%), 0.9 MBs/sec
2026-08-17T00:55:58.6556186Z Sent 76350037 of 143458901 (53.2%), 0.9 MBs/sec
2026-08-17T00:55:59.6568761Z Sent 76350037 of 143458901 (53.2%), 0.9 MBs/sec
2026-08-17T00:56:00.6580928Z Sent 76350037 of 143458901 (53.2%), 0.9 MBs/sec
2026-08-17T00:56:01.6594685Z Sent 76350037 of 143458901 (53.2%), 0.9 MBs/sec
2026-08-17T00:56:02.6607354Z Sent 76350037 of 143458901 (53.2%), 0.9 MBs/sec
2026-08-17T00:56:03.6619452Z Sent 76350037 of 143458901 (53.2%), 0.9 MBs/sec
2026-08-17T00:56:04.6646136Z Sent 76350037 of 143458901 (53.2%), 0.9 MBs/sec
2026-08-17T00:56:05.6658300Z Sent 76350037 of 143458901 (53.2%), 0.9 MBs/sec
2026-08-17T00:56:06.6670347Z Sent 76350037 of 143458901 (53.2%), 0.8 MBs/sec
2026-08-17T00:56:07.6681948Z Sent 76350037 of 143458901 (53.2%), 0.8 MBs/sec
2026-08-17T00:56:08.6694558Z Sent 76350037 of 143458901 (53.2%), 0.8 MBs/sec
2026-08-17T00:56:09.6712971Z Sent 76350037 of 143458901 (53.2%), 0.8 MBs/sec
2026-08-17T00:56:10.6725513Z Sent 76350037 of 143458901 (53.2%), 0.8 MBs/sec
2026-08-17T00:56:11.6726575Z Sent 76350037 of 143458901 (53.2%), 0.8 MBs/sec
2026-08-17T00:56:12.6738674Z Sent 76350037 of 143458901 (53.2%), 0.8 MBs/sec
2026-08-17T00:56:13.6738565Z Sent 76350037 of 143458901 (53.2%), 0.8 MBs/sec
2026-08-17T00:56:14.6741376Z Sent 76350037 of 143458901 (53.2%), 0.8 MBs/sec
2026-08-17T00:56:15.6754227Z Sent 76350037 of 143458901 (53.2%), 0.8 MBs/sec
2026-08-17T00:56:16.6766161Z Sent 76350037 of 143458901 (53.2%), 0.8 MBs/sec
2026-08-17T00:56:17.6776655Z Sent 76350037 of 143458901 (53.2%), 0.7 MBs/sec
2026-08-17T00:56:18.6788762Z Sent 76350037 of 143458901 (53.2%), 0.7 MBs/sec
2026-08-17T00:56:19.6800005Z Sent 76350037 of 143458901 (53.2%), 0.7 MBs/sec
2026-08-17T00:56:20.6803729Z Sent 76350037 of 143458901 (53.2%), 0.7 MBs/sec
2026-08-17T00:56:21.6815803Z Sent 76350037 of 143458901 (53.2%), 0.7 MBs/sec
2026-08-17T00:56:22.6818582Z Sent 76350037 of 143458901 (53.2%), 0.7 MBs/sec
2026-08-17T00:56:23.6831279Z Sent 76350037 of 143458901 (53.2%), 0.7 MBs/sec
2026-08-17T00:56:24.6842939Z Sent 76350037 of 143458901 (53.2%), 0.7 MBs/sec
2026-08-17T00:56:25.6855174Z Sent 76350037 of 143458901 (53.2%), 0.7 MBs/sec
2026-08-17T00:56:26.6867640Z Sent 76350037 of 143458901 (53.2%), 0.7 MBs/sec
2026-08-17T00:56:27.6879848Z Sent 76350037 of 143458901 (53.2%), 0.7 MBs/sec
2026-08-17T00:56:28.5212705Z Sent 143458901 of 143458901 (100.0%), 1.3 MBs/sec
2026-08-17T00:56:28.8062083Z Saved cache entry with key gradle-home-v1|Linux-X64|build[266babc85e2a7f6e4c23c8d6be839361]-90c3697fe0e605356c1995aa011d3f84927b29c1 from /home/runner/.gradle/caches,/home/runner/.gradle/notifications,/home/runner/.gradle/.setup-gradle in 109698ms
2026-08-17T00:56:28.8063525Z ##[endgroup]
2026-08-17T00:56:28.8072667Z Generating Job Summary
2026-08-17T00:56:28.8089419Z Completed post-action step
2026-08-17T00:56:28.8289749Z Node 20 is being deprecated. This workflow is running with Node 24 by default. If you need to temporarily use Node 20, you can set the ACTIONS_ALLOW_USE_UNSECURE_NODE_VERSION=true environment variable. For more information see: https://github.blog/changelog/2025-09-19-deprecation-of-node-20-on-github-actions-runners/
2026-08-17T00:56:28.8291082Z Post job cleanup.
2026-08-17T00:56:28.9666882Z (node:3266) [DEP0040] DeprecationWarning: The `punycode` module is deprecated. Please use a userland alternative instead.
2026-08-17T00:56:28.9668537Z (Use `node --trace-deprecation ...` to show where the warning was created)
2026-08-17T00:56:28.9889054Z Node 20 is being deprecated. This workflow is running with Node 24 by default. If you need to temporarily use Node 20, you can set the ACTIONS_ALLOW_USE_UNSECURE_NODE_VERSION=true environment variable. For more information see: https://github.blog/changelog/2025-09-19-deprecation-of-node-20-on-github-actions-runners/
2026-08-17T00:56:28.9890423Z Post job cleanup.
2026-08-17T00:56:29.0894190Z [command]/usr/bin/git version
2026-08-17T00:56:29.0943556Z git version 2.54.0
2026-08-17T00:56:29.0988600Z Temporarily overriding HOME='/home/runner/work/_temp/534ca454-a833-4c55-8f7e-d22d5961cd58' before making global git config changes
2026-08-17T00:56:29.0990551Z Adding repository directory to the temporary git global config as a safe directory
2026-08-17T00:56:29.0997632Z [command]/usr/bin/git config --global --add safe.directory /home/runner/work/AutoBOT/AutoBOT
2026-08-17T00:56:29.1045127Z [command]/usr/bin/git config --local --name-only --get-regexp core\.sshCommand
2026-08-17T00:56:29.1088322Z [command]/usr/bin/git submodule foreach --recursive sh -c "git config --local --name-only --get-regexp 'core\.sshCommand' && git config --local --unset-all 'core.sshCommand' || :"
2026-08-17T00:56:29.1376578Z [command]/usr/bin/git config --local --name-only --get-regexp http\.https\:\/\/github\.com\/\.extraheader
2026-08-17T00:56:29.1404470Z http.https://github.com/.extraheader
2026-08-17T00:56:29.1418217Z [command]/usr/bin/git config --local --unset-all http.https://github.com/.extraheader
2026-08-17T00:56:29.1456308Z [command]/usr/bin/git submodule foreach --recursive sh -c "git config --local --name-only --get-regexp 'http\.https\:\/\/github\.com\/\.extraheader' && git config --local --unset-all 'http.https://github.com/.extraheader' || :"
2026-08-17T00:56:29.1752995Z [command]/usr/bin/git config --local --name-only --get-regexp ^includeIf\.gitdir:
2026-08-17T00:56:29.1797295Z [command]/usr/bin/git submodule foreach --recursive git config --local --show-origin --name-only --get-regexp remote.origin.url
2026-08-17T00:56:29.2222839Z Cleaning up orphan processes
2026-08-17T00:56:29.2510491Z ##[warning]Node.js 20 is deprecated. The following actions target Node.js 20 but are being forced to run on Node.js 24: actions/checkout@v4, actions/setup-java@v4, actions/upload-artifact@v4, gradle/actions/setup-gradle@v4. For more information see: https://github.blog/changelog/2025-09-19-deprecation-of-node-20-on-github-actions-runners/
