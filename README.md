2026-08-17T04:25:16.8815322Z Current runner version: '2.336.0'
2026-08-17T04:25:16.8842851Z ##[group]Runner Image Provisioner
2026-08-17T04:25:16.8844165Z Hosted Compute Agent
2026-08-17T04:25:16.8844851Z Version: 20260729.566
2026-08-17T04:25:16.8845488Z Commit: cf7153fe6e25b664e8693c24944bf2b00355d109
2026-08-17T04:25:16.8846285Z Build Date: 2026-07-29T19:17:02Z
2026-08-17T04:25:16.8846970Z Worker ID: {a87a2660-56f2-48b1-83c8-4e27d8e8cbde}
2026-08-17T04:25:16.8847679Z Azure Region: westcentralus
2026-08-17T04:25:16.8848608Z ##[endgroup]
2026-08-17T04:25:16.8850083Z ##[group]Operating System
2026-08-17T04:25:16.8850790Z Ubuntu
2026-08-17T04:25:16.8851348Z 24.04.4
2026-08-17T04:25:16.8851868Z LTS
2026-08-17T04:25:16.8852570Z ##[endgroup]
2026-08-17T04:25:16.8853165Z ##[group]Runner Image
2026-08-17T04:25:16.8853773Z Image: ubuntu-24.04
2026-08-17T04:25:16.8854422Z Version: 20260810.271.1
2026-08-17T04:25:16.8855711Z Included Software: https://github.com/actions/runner-images/blob/ubuntu24/20260810.271/images/ubuntu/Ubuntu2404-Readme.md
2026-08-17T04:25:16.8857317Z Image Release: https://github.com/actions/runner-images/releases/tag/ubuntu24%2F20260810.271
2026-08-17T04:25:16.8858654Z ##[endgroup]
2026-08-17T04:25:16.8859956Z ##[group]GITHUB_TOKEN Permissions
2026-08-17T04:25:16.8862315Z Contents: read
2026-08-17T04:25:16.8863064Z Metadata: read
2026-08-17T04:25:16.8863641Z Packages: read
2026-08-17T04:25:16.8864245Z ##[endgroup]
2026-08-17T04:25:16.8866503Z Secret source: Actions
2026-08-17T04:25:16.8867548Z Prepare workflow directory
2026-08-17T04:25:16.9281814Z Prepare all required actions
2026-08-17T04:25:16.9329760Z Getting action download info
2026-08-17T04:25:17.2743448Z Download action repository 'actions/checkout@v4' (SHA:11d5960a326750d5838078e36cf38b85af677262)
2026-08-17T04:25:17.3686643Z Download action repository 'actions/setup-java@v4' (SHA:cf277c60eb25467037889841efdb72551f06f6c3)
2026-08-17T04:25:18.2363138Z Download action repository 'gradle/actions@v4' (SHA:ed408507eac070d1f99cc633dbcf757c94c7933a)
2026-08-17T04:25:19.7072098Z Download action repository 'android-actions/setup-android@v4' (SHA:40fd30fb8d7440372e1316f5d1809ec01dcd3699)
2026-08-17T04:25:20.1133859Z Download action repository 'actions/upload-artifact@v4' (SHA:ea165f8d65b6e75b540449e92b4886f43607fa02)
2026-08-17T04:25:20.3485911Z Complete job name: Build Android APK
2026-08-17T04:25:20.4252556Z Node 20 is being deprecated. This workflow is running with Node 24 by default. If you need to temporarily use Node 20, you can set the ACTIONS_ALLOW_USE_UNSECURE_NODE_VERSION=true environment variable. For more information see: https://github.blog/changelog/2025-09-19-deprecation-of-node-20-on-github-actions-runners/
2026-08-17T04:25:20.4260678Z ##[group]Run actions/checkout@v4
2026-08-17T04:25:20.4261118Z with:
2026-08-17T04:25:20.4261354Z   repository: Pikarziur/AutoBOT
2026-08-17T04:25:20.4263989Z   token: ***
2026-08-17T04:25:20.4264220Z   ssh-strict: true
2026-08-17T04:25:20.4264437Z   ssh-user: git
2026-08-17T04:25:20.4264657Z   persist-credentials: true
2026-08-17T04:25:20.4264924Z   clean: true
2026-08-17T04:25:20.4265158Z   sparse-checkout-cone-mode: true
2026-08-17T04:25:20.4265431Z   fetch-depth: 1
2026-08-17T04:25:20.4265648Z   fetch-tags: false
2026-08-17T04:25:20.4265870Z   show-progress: true
2026-08-17T04:25:20.4266092Z   lfs: false
2026-08-17T04:25:20.4266336Z   submodules: false
2026-08-17T04:25:20.4266559Z   set-safe-directory: true
2026-08-17T04:25:20.4266817Z   allow-unsafe-pr-checkout: false
2026-08-17T04:25:20.4267234Z env:
2026-08-17T04:25:20.4267430Z   GRADLE_VERSION: 8.5
2026-08-17T04:25:20.4267649Z   JAVA_VERSION: 17
2026-08-17T04:25:20.4267863Z ##[endgroup]
2026-08-17T04:25:20.5272694Z Syncing repository: Pikarziur/AutoBOT
2026-08-17T04:25:20.5274719Z ##[group]Getting Git version info
2026-08-17T04:25:20.5275322Z Working directory is '/home/runner/work/AutoBOT/AutoBOT'
2026-08-17T04:25:20.5276261Z [command]/usr/bin/git version
2026-08-17T04:25:20.5301014Z git version 2.54.0
2026-08-17T04:25:20.5325342Z ##[endgroup]
2026-08-17T04:25:20.5343577Z Temporarily overriding HOME='/home/runner/work/_temp/29abd08d-c281-441d-8b3d-be2872f59e39' before making global git config changes
2026-08-17T04:25:20.5345252Z Adding repository directory to the temporary git global config as a safe directory
2026-08-17T04:25:20.5350823Z [command]/usr/bin/git config --global --add safe.directory /home/runner/work/AutoBOT/AutoBOT
2026-08-17T04:25:20.5660641Z Deleting the contents of '/home/runner/work/AutoBOT/AutoBOT'
2026-08-17T04:25:20.5665324Z ##[group]Initializing the repository
2026-08-17T04:25:20.5670979Z [command]/usr/bin/git init /home/runner/work/AutoBOT/AutoBOT
2026-08-17T04:25:20.5752637Z hint: Using 'master' as the name for the initial branch. This default branch name
2026-08-17T04:25:20.5753537Z hint: will change to "main" in Git 3.0. To configure the initial branch name
2026-08-17T04:25:20.5754369Z hint: to use in all of your new repositories, which will suppress this warning,
2026-08-17T04:25:20.5755000Z hint: call:
2026-08-17T04:25:20.5755297Z hint:
2026-08-17T04:25:20.5755776Z hint: 	git config --global init.defaultBranch <name>
2026-08-17T04:25:20.5756324Z hint:
2026-08-17T04:25:20.5756793Z hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
2026-08-17T04:25:20.5757620Z hint: 'development'. The just-created branch can be renamed via this command:
2026-08-17T04:25:20.5758433Z hint:
2026-08-17T04:25:20.5758763Z hint: 	git branch -m <name>
2026-08-17T04:25:20.5759138Z hint:
2026-08-17T04:25:20.5759712Z hint: Disable this message with "git config set advice.defaultBranchName false"
2026-08-17T04:25:20.5760591Z Initialized empty Git repository in /home/runner/work/AutoBOT/AutoBOT/.git/
2026-08-17T04:25:20.5770705Z [command]/usr/bin/git remote add origin https://github.com/Pikarziur/AutoBOT
2026-08-17T04:25:20.5855307Z ##[endgroup]
2026-08-17T04:25:20.5856231Z ##[group]Disabling automatic garbage collection
2026-08-17T04:25:20.5856863Z [command]/usr/bin/git config --local gc.auto 0
2026-08-17T04:25:20.5892031Z ##[endgroup]
2026-08-17T04:25:20.5893011Z ##[group]Setting up auth
2026-08-17T04:25:20.5901513Z [command]/usr/bin/git config --local --name-only --get-regexp core\.sshCommand
2026-08-17T04:25:20.5945585Z [command]/usr/bin/git submodule foreach --recursive sh -c "git config --local --name-only --get-regexp 'core\.sshCommand' && git config --local --unset-all 'core.sshCommand' || :"
2026-08-17T04:25:20.6294968Z [command]/usr/bin/git config --local --name-only --get-regexp http\.https\:\/\/github\.com\/\.extraheader
2026-08-17T04:25:20.6337500Z [command]/usr/bin/git submodule foreach --recursive sh -c "git config --local --name-only --get-regexp 'http\.https\:\/\/github\.com\/\.extraheader' && git config --local --unset-all 'http.https://github.com/.extraheader' || :"
2026-08-17T04:25:20.6585403Z [command]/usr/bin/git config --local --name-only --get-regexp ^includeIf\.gitdir:
2026-08-17T04:25:20.6624789Z [command]/usr/bin/git submodule foreach --recursive git config --local --show-origin --name-only --get-regexp remote.origin.url
2026-08-17T04:25:20.6871649Z [command]/usr/bin/git config --local http.https://github.com/.extraheader AUTHORIZATION: basic ***
2026-08-17T04:25:20.6912706Z ##[endgroup]
2026-08-17T04:25:20.6913593Z ##[group]Fetching the repository
2026-08-17T04:25:20.6923764Z [command]/usr/bin/git -c protocol.version=2 fetch --no-tags --prune --no-recurse-submodules --depth=1 origin +84d5d5ce0b2bfeb338a30d7a2cbda3b8fab7d1b7:refs/remotes/origin/main
2026-08-17T04:25:21.2342871Z From https://github.com/Pikarziur/AutoBOT
2026-08-17T04:25:21.2343449Z  * [new ref]         84d5d5ce0b2bfeb338a30d7a2cbda3b8fab7d1b7 -> origin/main
2026-08-17T04:25:21.2376583Z ##[endgroup]
2026-08-17T04:25:21.2377213Z ##[group]Determining the checkout info
2026-08-17T04:25:21.2380136Z ##[endgroup]
2026-08-17T04:25:21.2387322Z [command]/usr/bin/git sparse-checkout disable
2026-08-17T04:25:21.2438748Z [command]/usr/bin/git config --local --unset-all extensions.worktreeConfig
2026-08-17T04:25:21.2473200Z ##[group]Checking out the ref
2026-08-17T04:25:21.2477995Z [command]/usr/bin/git checkout --progress --force -B main refs/remotes/origin/main
2026-08-17T04:25:21.2595024Z Switched to a new branch 'main'
2026-08-17T04:25:21.2597740Z branch 'main' set up to track 'origin/main'.
2026-08-17T04:25:21.2603658Z ##[endgroup]
2026-08-17T04:25:21.2648071Z [command]/usr/bin/git log -1 --format=%H
2026-08-17T04:25:21.2677001Z 84d5d5ce0b2bfeb338a30d7a2cbda3b8fab7d1b7
2026-08-17T04:25:21.2982672Z Node 20 is being deprecated. This workflow is running with Node 24 by default. If you need to temporarily use Node 20, you can set the ACTIONS_ALLOW_USE_UNSECURE_NODE_VERSION=true environment variable. For more information see: https://github.blog/changelog/2025-09-19-deprecation-of-node-20-on-github-actions-runners/
2026-08-17T04:25:21.2984281Z ##[group]Run actions/setup-java@v4
2026-08-17T04:25:21.2984548Z with:
2026-08-17T04:25:21.2984756Z   distribution: temurin
2026-08-17T04:25:21.2984993Z   java-version: 17
2026-08-17T04:25:21.2985214Z   java-package: jdk
2026-08-17T04:25:21.2985442Z   check-latest: false
2026-08-17T04:25:21.2985681Z   server-id: github
2026-08-17T04:25:21.2985902Z   server-username: GITHUB_ACTOR
2026-08-17T04:25:21.2986167Z   server-password: GITHUB_TOKEN
2026-08-17T04:25:21.2986423Z   overwrite-settings: true
2026-08-17T04:25:21.2986669Z   job-status: success
2026-08-17T04:25:21.2989439Z   token: ***
2026-08-17T04:25:21.2989649Z env:
2026-08-17T04:25:21.2989894Z   GRADLE_VERSION: 8.5
2026-08-17T04:25:21.2990132Z   JAVA_VERSION: 17
2026-08-17T04:25:21.2990348Z ##[endgroup]
2026-08-17T04:25:21.4683895Z ##[warning]setup-java v4 is deprecated and will no longer receive updates. Please migrate to actions/setup-java@v5.
2026-08-17T04:25:21.4691278Z ##[group]Installed distributions
2026-08-17T04:25:21.4725817Z Resolved Java 17.0.20+8 from tool-cache
2026-08-17T04:25:21.4726350Z Setting Java 17.0.20+8 as the default
2026-08-17T04:25:21.4736502Z (node:2313) [DEP0040] DeprecationWarning: The `punycode` module is deprecated. Please use a userland alternative instead.
2026-08-17T04:25:21.4737588Z (Use `node --trace-deprecation ...` to show where the warning was created)
2026-08-17T04:25:21.4739837Z Creating toolchains.xml for JDK version 17 from temurin
2026-08-17T04:25:21.4809359Z Writing to /home/runner/.m2/toolchains.xml
2026-08-17T04:25:21.4809804Z 
2026-08-17T04:25:21.4809961Z Java configuration:
2026-08-17T04:25:21.4810327Z   Distribution: temurin
2026-08-17T04:25:21.4810651Z   Version: 17.0.20+8
2026-08-17T04:25:21.4811178Z   Path: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T04:25:21.4811606Z 
2026-08-17T04:25:21.4812105Z ##[endgroup]
2026-08-17T04:25:21.4828610Z Creating settings.xml with server-id: github
2026-08-17T04:25:21.4862373Z Writing to /home/runner/.m2/settings.xml
2026-08-17T04:25:21.5213603Z Node 20 is being deprecated. This workflow is running with Node 24 by default. If you need to temporarily use Node 20, you can set the ACTIONS_ALLOW_USE_UNSECURE_NODE_VERSION=true environment variable. For more information see: https://github.blog/changelog/2025-09-19-deprecation-of-node-20-on-github-actions-runners/
2026-08-17T04:25:21.5215546Z ##[group]Run gradle/actions/setup-gradle@v4
2026-08-17T04:25:21.5215842Z with:
2026-08-17T04:25:21.5216061Z   gradle-version: 8.5
2026-08-17T04:25:21.5216303Z   cache-read-only: false
2026-08-17T04:25:21.5216675Z   validate-wrappers: false
2026-08-17T04:25:21.5217138Z   cache-disabled: false
2026-08-17T04:25:21.5217600Z   cache-write-only: false
2026-08-17T04:25:21.5218134Z   cache-overwrite-existing: false
2026-08-17T04:25:21.5218801Z   cache-cleanup: on-success
2026-08-17T04:25:21.5219416Z   gradle-home-cache-includes: caches
notifications

2026-08-17T04:25:21.5220086Z   add-job-summary: always
2026-08-17T04:25:21.5220702Z   add-job-summary-as-pr-comment: never
2026-08-17T04:25:21.5221166Z   dependency-graph: disabled
2026-08-17T04:25:21.5221669Z   dependency-graph-report-dir: dependency-graph-reports
2026-08-17T04:25:21.5222273Z   dependency-graph-continue-on-failure: true
2026-08-17T04:25:21.5222779Z   build-scan-publish: false
2026-08-17T04:25:21.5223502Z   allow-snapshot-wrappers: false
2026-08-17T04:25:21.5223954Z   gradle-home-cache-strict-match: false
2026-08-17T04:25:21.5224430Z   workflow-job-context: null
2026-08-17T04:25:21.5228950Z   github-token: ***
2026-08-17T04:25:21.5229296Z env:
2026-08-17T04:25:21.5229600Z   GRADLE_VERSION: 8.5
2026-08-17T04:25:21.5230006Z   JAVA_VERSION: 17
2026-08-17T04:25:21.5230977Z   JAVA_HOME: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T04:25:21.5232589Z   JAVA_HOME_17_X64: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T04:25:21.5233609Z ##[endgroup]
2026-08-17T04:25:21.9430005Z Merged default JDK locations into /home/runner/.m2/toolchains.xml
2026-08-17T04:25:21.9430851Z Preparing cache for cleanup.
2026-08-17T04:25:21.9435029Z ##[group]Restore Gradle state from cache
2026-08-17T04:25:22.1495906Z Cache hit for restore-key: gradle-home-v1|Linux-X64|build[266babc85e2a7f6e4c23c8d6be839361]-d9d4a4fd93dca7dad88e367e0d821c3912983b78
2026-08-17T04:25:23.3620231Z Received 33554432 of 143684940 (23.4%), 32.0 MBs/sec
2026-08-17T04:25:24.1028714Z Received 143684940 of 143684940 (100.0%), 78.8 MBs/sec
2026-08-17T04:25:24.1094907Z Cache Size: ~137 MB (143684940 B)
2026-08-17T04:25:24.1096332Z [command]/usr/bin/tar -xf /home/runner/work/_temp/4c22d81d-b394-4f85-8711-23584628a656/cache.tzst -P -C /home/runner/work/AutoBOT/AutoBOT --use-compress-program unzstd
2026-08-17T04:25:25.2809079Z Cache restored successfully
2026-08-17T04:25:25.2886402Z Restored cache entry with key gradle-home-v1|Linux-X64|build[266babc85e2a7f6e4c23c8d6be839361]-84d5d5ce0b2bfeb338a30d7a2cbda3b8fab7d1b7 to /home/runner/.gradle/caches,/home/runner/.gradle/notifications,/home/runner/.gradle/.setup-gradle in 3343ms
2026-08-17T04:25:25.4845029Z Cache hit for: gradle-instrumented-jars-v1-51f7fa110302be2ccd6873a27b166ac8
2026-08-17T04:25:25.4898939Z Cache hit for: gradle-kotlin-dsl-v1-86903c45d6b8a8330f048b9beae0c1ea
2026-08-17T04:25:25.4905466Z Cache hit for: gradle-wrapper-zips-v1-e89a30cff1b7b918cfe1273c9c8e4a34
2026-08-17T04:25:25.4943386Z Cache hit for: gradle-groovy-dsl-v1-a590fbee8347fb464225ccd14a8c37d2
2026-08-17T04:25:25.4950842Z Cache hit for: gradle-dependencies-v1-ca33a97c11bd8dec625e8d54280f9120
2026-08-17T04:25:25.5109364Z Cache hit for: gradle-generated-gradle-jars-v1-fa001ab82c3596b4e27ec78f191b889f
2026-08-17T04:25:25.9923955Z Received 98340 of 98340 (100.0%), 0.3 MBs/sec
2026-08-17T04:25:25.9925028Z Cache Size: ~0 MB (98340 B)
2026-08-17T04:25:25.9949391Z [command]/usr/bin/tar -xf /home/runner/work/_temp/1fcfdec3-3860-44cf-a828-2afa746c6c49/cache.tzst -P -C /home/runner/work/AutoBOT/AutoBOT --use-compress-program unzstd
2026-08-17T04:25:26.0366200Z Cache restored successfully
2026-08-17T04:25:26.0370582Z Restored cache entry with key gradle-kotlin-dsl-v1-86903c45d6b8a8330f048b9beae0c1ea to /home/runner/.gradle/caches/*/kotlin-dsl/accessors/*/,/home/runner/.gradle/caches/*/kotlin-dsl/scripts/*/ in 745ms
2026-08-17T04:25:26.0854654Z Received 109838 of 109838 (100.0%), 0.3 MBs/sec
2026-08-17T04:25:26.0855427Z Cache Size: ~0 MB (109838 B)
2026-08-17T04:25:26.0878689Z [command]/usr/bin/tar -xf /home/runner/work/_temp/667ce5d2-f536-4be4-baa5-3f5a9edf0f50/cache.tzst -P -C /home/runner/work/AutoBOT/AutoBOT --use-compress-program unzstd
2026-08-17T04:25:26.1069466Z Cache restored successfully
2026-08-17T04:25:26.1071376Z Restored cache entry with key gradle-groovy-dsl-v1-a590fbee8347fb464225ccd14a8c37d2 to /home/runner/.gradle/caches/*/groovy-dsl/*/ in 816ms
2026-08-17T04:25:26.7111637Z Received 37748736 of 328896045 (11.5%), 35.9 MBs/sec
2026-08-17T04:25:26.7131576Z Received 20971520 of 131966939 (15.9%), 20.0 MBs/sec
2026-08-17T04:25:26.7211997Z Received 12582912 of 89747838 (14.0%), 12.0 MBs/sec
2026-08-17T04:25:26.7353581Z Received 12582912 of 36784583 (34.2%), 12.0 MBs/sec
2026-08-17T04:25:26.9536116Z Received 36784583 of 36784583 (100.0%), 28.8 MBs/sec
2026-08-17T04:25:26.9538081Z Cache Size: ~35 MB (36784583 B)
2026-08-17T04:25:27.0401579Z [command]/usr/bin/tar -xf /home/runner/work/_temp/08c13bb3-b8e7-488d-92bd-1fd18a48afc5/cache.tzst -P -C /home/runner/work/AutoBOT/AutoBOT --use-compress-program unzstd
2026-08-17T04:25:27.3923286Z Received 89747838 of 89747838 (100.0%), 51.2 MBs/sec
2026-08-17T04:25:27.3924483Z Cache Size: ~86 MB (89747838 B)
2026-08-17T04:25:27.4143683Z Cache restored successfully
2026-08-17T04:25:27.4558723Z Restored cache entry with key gradle-generated-gradle-jars-v1-fa001ab82c3596b4e27ec78f191b889f to /home/runner/.gradle/caches/8.5/generated-gradle-jars/gradle-api-8.5.jar in 2164ms
2026-08-17T04:25:27.4735774Z [command]/usr/bin/tar -xf /home/runner/work/_temp/b3efd40c-c9d4-4d9f-b02e-d6c904bbe8fb/cache.tzst -P -C /home/runner/work/AutoBOT/AutoBOT --use-compress-program unzstd
2026-08-17T04:25:27.6960300Z Received 131966939 of 131966939 (100.0%), 63.5 MBs/sec
2026-08-17T04:25:27.6961236Z Cache Size: ~126 MB (131966939 B)
2026-08-17T04:25:27.7144303Z Received 159383552 of 328896045 (48.5%), 75.6 MBs/sec
2026-08-17T04:25:27.7343208Z [command]/usr/bin/tar -xf /home/runner/work/_temp/2180ef39-f647-4b54-884c-c6b6d5fe7522/cache.tzst -P -C /home/runner/work/AutoBOT/AutoBOT --use-compress-program unzstd
2026-08-17T04:25:28.1394147Z Cache restored successfully
2026-08-17T04:25:28.1499611Z Restored cache entry with key gradle-wrapper-zips-v1-e89a30cff1b7b918cfe1273c9c8e4a34 to /home/runner/.gradle/wrapper/dists/gradle-8.5-bin/5t9huq95ubn472n8rpzujfbqh in 2858ms
2026-08-17T04:25:28.3588026Z Cache restored successfully
2026-08-17T04:25:28.3624791Z Restored cache entry with key gradle-instrumented-jars-v1-51f7fa110302be2ccd6873a27b166ac8 to /home/runner/.gradle/caches/jars-*/*/ in 3071ms
2026-08-17T04:25:28.7183612Z Received 328896045 of 328896045 (100.0%), 104.0 MBs/sec
2026-08-17T04:25:28.7185692Z Cache Size: ~314 MB (328896045 B)
2026-08-17T04:25:28.7214057Z [command]/usr/bin/tar -xf /home/runner/work/_temp/6582012b-981a-4709-990b-27c755cb415a/cache.tzst -P -C /home/runner/work/AutoBOT/AutoBOT --use-compress-program unzstd
2026-08-17T04:25:29.4706971Z Cache restored successfully
2026-08-17T04:25:29.9421477Z Restored cache entry with key gradle-dependencies-v1-ca33a97c11bd8dec625e8d54280f9120 to /home/runner/.gradle/caches/modules-*/files-*/*/*/*/* in 4650ms
2026-08-17T04:25:29.9680219Z ##[endgroup]
2026-08-17T04:25:30.1475628Z ##[group]Provision Gradle 8.5
2026-08-17T04:25:33.3971201Z Cache hit for: gradle-8.5
2026-08-17T04:25:34.3744601Z Received 132239594 of 132239594 (100.0%), 136.8 MBs/sec
2026-08-17T04:25:34.3746039Z Cache Size: ~126 MB (132239594 B)
2026-08-17T04:25:34.3771908Z [command]/usr/bin/tar -xf /home/runner/work/_temp/db9e23cf-1d31-498a-abdc-0e639736a777/cache.tzst -P -C /home/runner/work/AutoBOT/AutoBOT --use-compress-program unzstd
2026-08-17T04:25:34.5414894Z Cache restored successfully
2026-08-17T04:25:34.5481828Z Restored Gradle distribution gradle-8.5 from cache to /home/runner/work/_temp/.gradle-actions/gradle-installations/downloads/gradle-8.5-bin.zip
2026-08-17T04:25:34.5499598Z [command]/usr/bin/unzip -o -q /home/runner/work/_temp/.gradle-actions/gradle-installations/downloads/gradle-8.5-bin.zip
2026-08-17T04:25:35.6029853Z Extracted Gradle 8.5 to /home/runner/work/_temp/.gradle-actions/gradle-installations/installs/gradle-8.5
2026-08-17T04:25:35.6031907Z Provisioned Gradle executable /home/runner/work/_temp/.gradle-actions/gradle-installations/installs/gradle-8.5/bin/gradle
2026-08-17T04:25:35.6033095Z ##[endgroup]
2026-08-17T04:25:35.6234326Z ##[group]Run if [ -f "gradle/wrapper/gradle-wrapper.jar" ]; then
2026-08-17T04:25:35.6234952Z [36;1mif [ -f "gradle/wrapper/gradle-wrapper.jar" ]; then[0m
2026-08-17T04:25:35.6235502Z [36;1m  echo "✅ gradle-wrapper.jar already exists, skip generation"[0m
2026-08-17T04:25:35.6235969Z [36;1m  ls -la gradle/wrapper/[0m
2026-08-17T04:25:35.6236290Z [36;1m  exit 0[0m
2026-08-17T04:25:35.6236546Z [36;1mfi[0m
2026-08-17T04:25:35.6236795Z [36;1m[0m
2026-08-17T04:25:35.6237213Z [36;1mecho "⚠️ gradle-wrapper.jar not found. Generating via gradle command..."[0m
2026-08-17T04:25:35.6237735Z [36;1mecho "gradle version: $(gradle --version)"[0m
2026-08-17T04:25:35.6238781Z [36;1mgradle wrapper --gradle-version "$GRADLE_VERSION" --distribution-type bin --no-daemon[0m
2026-08-17T04:25:35.6239282Z [36;1m[0m
2026-08-17T04:25:35.6239599Z [36;1mif [ -f "gradle/wrapper/gradle-wrapper.jar" ]; then[0m
2026-08-17T04:25:35.6240105Z [36;1m  echo "✅ Generated gradle-wrapper.jar successfully:"[0m
2026-08-17T04:25:35.6240499Z [36;1m  ls -la gradle/wrapper/[0m
2026-08-17T04:25:35.6240809Z [36;1melse[0m
2026-08-17T04:25:35.6241126Z [36;1m  echo "❌ Failed to generate gradle-wrapper.jar"[0m
2026-08-17T04:25:35.6241494Z [36;1m  ls -la gradle/ || true[0m
2026-08-17T04:25:35.6241785Z [36;1m  exit 1[0m
2026-08-17T04:25:35.6242034Z [36;1mfi[0m
2026-08-17T04:25:35.6286396Z shell: /usr/bin/bash --noprofile --norc -e -o pipefail {0}
2026-08-17T04:25:35.6286819Z env:
2026-08-17T04:25:35.6287079Z   GRADLE_VERSION: 8.5
2026-08-17T04:25:35.6287359Z   JAVA_VERSION: 17
2026-08-17T04:25:35.6287769Z   JAVA_HOME: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T04:25:35.6288660Z   JAVA_HOME_17_X64: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T04:25:35.6289152Z   GRADLE_ACTION_ID: gradle/actions/setup-gradle
2026-08-17T04:25:35.6289521Z   GRADLE_USER_HOME: /home/runner/.gradle
2026-08-17T04:25:35.6289891Z   GRADLE_BUILD_ACTION_SETUP_COMPLETED: true
2026-08-17T04:25:35.6290266Z   GRADLE_BUILD_ACTION_CACHE_RESTORED: true
2026-08-17T04:25:35.6290771Z   DEVELOCITY_INJECTION_INIT_SCRIPT_NAME: gradle-actions.inject-develocity.init.gradle
2026-08-17T04:25:35.6291304Z   DEVELOCITY_INJECTION_CUSTOM_VALUE: gradle-actions
2026-08-17T04:25:35.6291691Z   GITHUB_DEPENDENCY_GRAPH_ENABLED: false
2026-08-17T04:25:35.6292021Z ##[endgroup]
2026-08-17T04:25:35.7469312Z ✅ gradle-wrapper.jar already exists, skip generation
2026-08-17T04:25:35.7486527Z total 12
2026-08-17T04:25:35.7486974Z drwxr-xr-x 2 runner runner 4096 Aug 17 04:25 .
2026-08-17T04:25:35.7487579Z drwxr-xr-x 3 runner runner 4096 Aug 17 04:25 ..
2026-08-17T04:25:35.7488345Z -rw-r--r-- 1 runner runner 1797 Aug 17 04:25 gradle-wrapper.jar
2026-08-17T04:25:35.7524870Z ##[group]Run chmod +x gradlew
2026-08-17T04:25:35.7525233Z [36;1mchmod +x gradlew[0m
2026-08-17T04:25:35.7565824Z shell: /usr/bin/bash -e {0}
2026-08-17T04:25:35.7566153Z env:
2026-08-17T04:25:35.7566406Z   GRADLE_VERSION: 8.5
2026-08-17T04:25:35.7566688Z   JAVA_VERSION: 17
2026-08-17T04:25:35.7567086Z   JAVA_HOME: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T04:25:35.7567655Z   JAVA_HOME_17_X64: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T04:25:35.7568135Z   GRADLE_ACTION_ID: gradle/actions/setup-gradle
2026-08-17T04:25:35.7568767Z   GRADLE_USER_HOME: /home/runner/.gradle
2026-08-17T04:25:35.7569121Z   GRADLE_BUILD_ACTION_SETUP_COMPLETED: true
2026-08-17T04:25:35.7569493Z   GRADLE_BUILD_ACTION_CACHE_RESTORED: true
2026-08-17T04:25:35.7570006Z   DEVELOCITY_INJECTION_INIT_SCRIPT_NAME: gradle-actions.inject-develocity.init.gradle
2026-08-17T04:25:35.7570563Z   DEVELOCITY_INJECTION_CUSTOM_VALUE: gradle-actions
2026-08-17T04:25:35.7570996Z   GITHUB_DEPENDENCY_GRAPH_ENABLED: false
2026-08-17T04:25:35.7571339Z ##[endgroup]
2026-08-17T04:25:35.8507374Z ##[group]Run android-actions/setup-android@v4
2026-08-17T04:25:35.8507756Z with:
2026-08-17T04:25:35.8508042Z   accept-android-sdk-licenses: true
2026-08-17T04:25:35.8508632Z   log-accepted-android-sdk-licenses: false
2026-08-17T04:25:35.8509028Z   cmdline-tools-version: 14742923
2026-08-17T04:25:35.8509346Z env:
2026-08-17T04:25:35.8509596Z   GRADLE_VERSION: 8.5
2026-08-17T04:25:35.8509883Z   JAVA_VERSION: 17
2026-08-17T04:25:35.8510275Z   JAVA_HOME: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T04:25:35.8510842Z   JAVA_HOME_17_X64: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T04:25:35.8511334Z   GRADLE_ACTION_ID: gradle/actions/setup-gradle
2026-08-17T04:25:35.8511700Z   GRADLE_USER_HOME: /home/runner/.gradle
2026-08-17T04:25:35.8512050Z   GRADLE_BUILD_ACTION_SETUP_COMPLETED: true
2026-08-17T04:25:35.8512630Z   GRADLE_BUILD_ACTION_CACHE_RESTORED: true
2026-08-17T04:25:35.8513178Z   DEVELOCITY_INJECTION_INIT_SCRIPT_NAME: gradle-actions.inject-develocity.init.gradle
2026-08-17T04:25:35.8513720Z   DEVELOCITY_INJECTION_CUSTOM_VALUE: gradle-actions
2026-08-17T04:25:35.8514097Z   GITHUB_DEPENDENCY_GRAPH_ENABLED: false
2026-08-17T04:25:35.8514418Z ##[endgroup]
2026-08-17T04:25:36.0965388Z Found preinstalled sdkmanager in /usr/local/lib/android/sdk/cmdline-tools/latest with following source.properties:
2026-08-17T04:25:36.0966268Z Pkg.Revision=12.0
2026-08-17T04:25:36.0966698Z Pkg.Path=cmdline-tools;12.0
2026-08-17T04:25:36.0967183Z Pkg.Desc=Android SDK Command-line Tools
2026-08-17T04:25:36.0967490Z 
2026-08-17T04:25:36.0967632Z Wrong version in preinstalled sdkmanager
2026-08-17T04:25:36.0968502Z Downloading commandline tools from https://dl.google.com/android/repository/commandlinetools-linux-14742923_latest.zip
2026-08-17T04:25:36.9378986Z [command]/usr/bin/unzip -o -q /home/runner/work/_temp/1eb92e65-2600-4751-9b2e-59b51a44b27a
2026-08-17T04:25:37.8348509Z Accepting Android SDK licenses
2026-08-17T04:25:41.0056770Z ##[group]Run echo "ANDROID_HOME=$ANDROID_HOME"
2026-08-17T04:25:41.0057223Z [36;1mecho "ANDROID_HOME=$ANDROID_HOME"[0m
2026-08-17T04:25:41.0057616Z [36;1mecho "sdkmanager path: $(which sdkmanager)"[0m
2026-08-17T04:25:41.0058007Z [36;1msdkmanager --install \[0m
2026-08-17T04:25:41.0058766Z [36;1m  "platforms;android-34" \[0m
2026-08-17T04:25:41.0059216Z [36;1m  "build-tools;34.0.0" \[0m
2026-08-17T04:25:41.0059542Z [36;1m  "platform-tools" \[0m
2026-08-17T04:25:41.0059857Z [36;1m  "ndk;25.2.9519653" \[0m
2026-08-17T04:25:41.0060162Z [36;1m  "cmake;3.22.1"[0m
2026-08-17T04:25:41.0060485Z [36;1mecho "✅ SDK components installed"[0m
2026-08-17T04:25:41.0060943Z [36;1msdkmanager --list_installed || sdkmanager --list | head -50[0m
2026-08-17T04:25:41.0102581Z shell: /usr/bin/bash --noprofile --norc -e -o pipefail {0}
2026-08-17T04:25:41.0103003Z env:
2026-08-17T04:25:41.0103258Z   GRADLE_VERSION: 8.5
2026-08-17T04:25:41.0103543Z   JAVA_VERSION: 17
2026-08-17T04:25:41.0103973Z   JAVA_HOME: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T04:25:41.0104530Z   JAVA_HOME_17_X64: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T04:25:41.0105013Z   GRADLE_ACTION_ID: gradle/actions/setup-gradle
2026-08-17T04:25:41.0105370Z   GRADLE_USER_HOME: /home/runner/.gradle
2026-08-17T04:25:41.0105719Z   GRADLE_BUILD_ACTION_SETUP_COMPLETED: true
2026-08-17T04:25:41.0106085Z   GRADLE_BUILD_ACTION_CACHE_RESTORED: true
2026-08-17T04:25:41.0106588Z   DEVELOCITY_INJECTION_INIT_SCRIPT_NAME: gradle-actions.inject-develocity.init.gradle
2026-08-17T04:25:41.0107118Z   DEVELOCITY_INJECTION_CUSTOM_VALUE: gradle-actions
2026-08-17T04:25:41.0107492Z   GITHUB_DEPENDENCY_GRAPH_ENABLED: false
2026-08-17T04:25:41.0107831Z   ANDROID_HOME: /usr/local/lib/android/sdk
2026-08-17T04:25:41.0108185Z   ANDROID_SDK_ROOT: /usr/local/lib/android/sdk
2026-08-17T04:25:41.0108714Z ##[endgroup]
2026-08-17T04:25:41.0173218Z ANDROID_HOME=/usr/local/lib/android/sdk
2026-08-17T04:25:41.0185839Z sdkmanager path: /usr/local/lib/android/sdk/cmdline-tools/20.0/bin/sdkmanager
2026-08-17T04:25:41.8699881Z Loading package information...                                                  
2026-08-17T04:25:41.9580570Z Loading local repository...                                                     
2026-08-17T04:25:41.9581898Z [                                       ] 3% Loading local repository...        
2026-08-17T04:25:41.9676585Z [                                       ] 3% Fetch remote repository...         
2026-08-17T04:25:42.2300924Z [=                                      ] 3% Fetch remote repository...         
2026-08-17T04:25:42.3500017Z [=                                      ] 4% Fetch remote repository...         
2026-08-17T04:25:42.3820350Z [=                                      ] 5% Fetch remote repository...         
2026-08-17T04:25:42.4391270Z [==                                     ] 5% Fetch remote repository...         
2026-08-17T04:25:42.5053525Z [==                                     ] 6% Fetch remote repository...         
2026-08-17T04:25:42.5829904Z [==                                     ] 7% Fetch remote repository...         
2026-08-17T04:25:42.5869623Z [==                                     ] 7% Computing updates...               
2026-08-17T04:25:42.5961075Z [===                                    ] 8% Computing updates...               
2026-08-17T04:25:42.6096914Z [===                                    ] 10% Computing updates...              
2026-08-17T04:25:42.9825517Z [===                                    ] 10% Installing CMake 3.22.1           
2026-08-17T04:25:43.0265310Z [===                                    ] 10% Downloading cmake-3.22.1-linux.zip
2026-08-17T04:25:43.0847475Z [====                                   ] 10% Downloading cmake-3.22.1-linux.zip
2026-08-17T04:25:43.1563202Z [====                                   ] 11% Downloading cmake-3.22.1-linux.zip
2026-08-17T04:25:43.2204752Z [====                                   ] 12% Downloading cmake-3.22.1-linux.zip
2026-08-17T04:25:43.2826369Z [=====                                  ] 13% Downloading cmake-3.22.1-linux.zip
2026-08-17T04:25:43.3381081Z [=====                                  ] 14% Downloading cmake-3.22.1-linux.zip
2026-08-17T04:25:43.3727120Z [=====                                  ] 15% Downloading cmake-3.22.1-linux.zip
2026-08-17T04:25:43.4004017Z [======                                 ] 15% Downloading cmake-3.22.1-linux.zip
2026-08-17T04:25:43.4624689Z [======                                 ] 16% Downloading cmake-3.22.1-linux.zip
2026-08-17T04:25:43.5255947Z [======                                 ] 17% Downloading cmake-3.22.1-linux.zip
2026-08-17T04:25:43.5877851Z [=======                                ] 18% Downloading cmake-3.22.1-linux.zip
2026-08-17T04:25:43.6500220Z [=======                                ] 19% Downloading cmake-3.22.1-linux.zip
2026-08-17T04:25:43.6775655Z [=======                                ] 20% Downloading cmake-3.22.1-linux.zip
2026-08-17T04:25:43.7120234Z [========                               ] 20% Downloading cmake-3.22.1-linux.zip
2026-08-17T04:25:43.7561176Z [========                               ] 21% Downloading cmake-3.22.1-linux.zip
2026-08-17T04:25:43.9476824Z [========                               ] 21% Unzipping...                      
2026-08-17T04:25:43.9689667Z [========                               ] 21% Unzipping... bin/cmake            
2026-08-17T04:25:44.0022518Z [========                               ] 22% Unzipping... bin/cmake            
2026-08-17T04:25:44.0361846Z [=========                              ] 23% Unzipping... bin/cmake            
2026-08-17T04:25:44.0646366Z [=========                              ] 24% Unzipping... bin/cmake            
2026-08-17T04:25:44.0685675Z [=========                              ] 24% Unzipping... bin/ctest            
2026-08-17T04:25:44.0833061Z [=========                              ] 25% Unzipping... bin/ctest            
2026-08-17T04:25:44.0982654Z [==========                             ] 25% Unzipping... bin/ctest            
2026-08-17T04:25:44.1284654Z [==========                             ] 26% Unzipping... bin/ctest            
2026-08-17T04:25:44.1557913Z [==========                             ] 27% Unzipping... bin/ctest            
2026-08-17T04:25:44.1644108Z [===========                            ] 28% Unzipping... bin/ctest            
2026-08-17T04:25:44.1850849Z [===========                            ] 28% Unzipping... bin/cpack            
2026-08-17T04:25:44.2149620Z [===========                            ] 29% Unzipping... bin/cpack            
2026-08-17T04:25:44.2308526Z [===========                            ] 30% Unzipping... bin/cpack            
2026-08-17T04:25:44.2427194Z [============                           ] 30% Unzipping... bin/cpack            
2026-08-17T04:25:44.2562048Z [============                           ] 31% Unzipping... bin/cpack            
2026-08-17T04:25:44.2567901Z [============                           ] 31% Unzipping... share/vim/vimfiles/in
2026-08-17T04:25:44.2577224Z [============                           ] 31% Unzipping... share/vim/vimfiles/sy
2026-08-17T04:25:44.2580448Z [============                           ] 31% Unzipping... share/aclocal/cmake.m
2026-08-17T04:25:44.2585348Z [============                           ] 31% Unzipping... share/emacs/site-lisp
2026-08-17T04:25:44.2595489Z [============                           ] 31% Unzipping... share/cmake-3.22/incl
2026-08-17T04:25:44.6193795Z [============                           ] 31% Unzipping... share/cmake-3.22/Help
2026-08-17T04:25:44.6288978Z [============                           ] 31% Unzipping... share/cmake-3.22/Temp
2026-08-17T04:25:44.6325753Z [============                           ] 32% Unzipping... share/cmake-3.22/Temp
2026-08-17T04:25:44.8170606Z [============                           ] 32% Unzipping... share/cmake-3.22/Modu
2026-08-17T04:25:44.8177698Z [============                           ] 32% Unzipping... share/bash-completion
2026-08-17T04:25:44.8182293Z [============                           ] 32% Unzipping... doc/cmake-3.22/Copyri
2026-08-17T04:25:44.8184708Z [============                           ] 32% Unzipping... doc/cmake-3.22/cmzlib
2026-08-17T04:25:44.8187473Z [============                           ] 32% Unzipping... doc/cmake-3.22/cmzstd
2026-08-17T04:25:44.8190431Z [============                           ] 32% Unzipping... doc/cmake-3.22/cmnght
2026-08-17T04:25:44.8193323Z [============                           ] 32% Unzipping... doc/cmake-3.22/cmsys/
2026-08-17T04:25:44.8196091Z [============                           ] 32% Unzipping... doc/cmake-3.22/cmcurl
2026-08-17T04:25:44.8198959Z [============                           ] 32% Unzipping... doc/cmake-3.22/cmlibr
2026-08-17T04:25:44.8201829Z [============                           ] 32% Unzipping... doc/cmake-3.22/cmliba
2026-08-17T04:25:44.8204617Z [============                           ] 32% Unzipping... doc/cmake-3.22/cmlibl
2026-08-17T04:25:44.8207338Z [============                           ] 32% Unzipping... doc/cmake-3.22/cmlibu
2026-08-17T04:25:44.8220793Z [============                           ] 32% Unzipping... doc/openssl-1.1.1l/LI
2026-08-17T04:25:44.8222148Z [============                           ] 32% Unzipping... source.properties    
2026-08-17T04:25:44.8244230Z [============                           ] 32% Unzipping... bin/ninja            
2026-08-17T04:25:44.8247446Z [============                           ] 32% Unzipping... doc/ninja/LICENSE    
2026-08-17T04:25:44.8252365Z [============                           ] 32% Unzipping... share/cmake-3.22/Modu
2026-08-17T04:25:44.8349114Z [=============                          ] 33% Unzipping... share/cmake-3.22/Modu
2026-08-17T04:25:45.1494878Z [=====================                  ] 55% Unzipping... share/cmake-3.22/Modu
2026-08-17T04:25:45.1975375Z [=====================                  ] 55% Installing NDK (Side by side) 25.2
2026-08-17T04:25:45.3547215Z [=====================                  ] 55% Downloading android-ndk-r25c-linux
2026-08-17T04:25:45.5806385Z [======================                 ] 55% Downloading android-ndk-r25c-linux
2026-08-17T04:25:45.6909498Z [======================                 ] 56% Downloading android-ndk-r25c-linux
2026-08-17T04:25:45.7831633Z [======================                 ] 57% Downloading android-ndk-r25c-linux
2026-08-17T04:25:45.8752111Z [=======================                ] 58% Downloading android-ndk-r25c-linux
2026-08-17T04:25:45.9620920Z [=======================                ] 59% Downloading android-ndk-r25c-linux
2026-08-17T04:25:46.0132069Z [=======================                ] 60% Downloading android-ndk-r25c-linux
2026-08-17T04:25:46.0540799Z [========================               ] 60% Downloading android-ndk-r25c-linux
2026-08-17T04:25:46.1454744Z [========================               ] 61% Downloading android-ndk-r25c-linux
2026-08-17T04:25:46.2490891Z [========================               ] 62% Downloading android-ndk-r25c-linux
2026-08-17T04:25:46.3439147Z [=========================              ] 63% Downloading android-ndk-r25c-linux
2026-08-17T04:25:46.4396001Z [=========================              ] 64% Downloading android-ndk-r25c-linux
2026-08-17T04:25:46.4850019Z [=========================              ] 65% Downloading android-ndk-r25c-linux
2026-08-17T04:25:46.5408697Z [==========================             ] 65% Downloading android-ndk-r25c-linux
2026-08-17T04:25:46.6069429Z [==========================             ] 66% Downloading android-ndk-r25c-linux
2026-08-17T04:25:46.8199962Z [==========================             ] 66% Unzipping... share/cmake-3.22/Modu
2026-08-17T04:25:46.8202753Z [==========================             ] 66% Unzipping... android-ndk-r25c/    
2026-08-17T04:25:46.8203986Z [==========================             ] 66% Unzipping... android-ndk-r25c/CHAN
2026-08-17T04:25:46.8205208Z [==========================             ] 66% Unzipping... android-ndk-r25c/wrap
2026-08-17T04:25:46.8731170Z [==========================             ] 66% Unzipping... android-ndk-r25c/preb
2026-08-17T04:25:46.8926294Z [==========================             ] 66% Unzipping... android-ndk-r25c/buil
2026-08-17T04:25:46.8946100Z [==========================             ] 66% Unzipping... android-ndk-r25c/NOTI
2026-08-17T04:25:46.8956225Z [==========================             ] 66% Unzipping... android-ndk-r25c/ndk-
2026-08-17T04:25:46.8981675Z [==========================             ] 66% Unzipping... android-ndk-r25c/NOTI
2026-08-17T04:25:46.8987109Z [==========================             ] 66% Unzipping... android-ndk-r25c/meta
2026-08-17T04:25:46.8992710Z [==========================             ] 66% Unzipping... android-ndk-r25c/ndk-
2026-08-17T04:25:46.9017087Z [==========================             ] 66% Unzipping... android-ndk-r25c/pyth
2026-08-17T04:25:47.3552191Z [==========================             ] 66% Unzipping... android-ndk-r25c/sour
2026-08-17T04:25:47.3933442Z [==========================             ] 66% Unzipping... android-ndk-r25c/simp
2026-08-17T04:25:47.5712881Z [==========================             ] 67% Unzipping... android-ndk-r25c/simp
2026-08-17T04:25:47.5714063Z [==========================             ] 67% Unzipping... android-ndk-r25c/ndk-
2026-08-17T04:25:47.5715266Z [==========================             ] 67% Unzipping... android-ndk-r25c/READ
2026-08-17T04:25:48.0107211Z [==========================             ] 67% Unzipping... android-ndk-r25c/tool
2026-08-17T04:25:48.7329800Z [===========================            ] 68% Unzipping... android-ndk-r25c/tool
2026-08-17T04:25:49.3734864Z [===========================            ] 69% Unzipping... android-ndk-r25c/tool
2026-08-17T04:25:49.6941399Z [===========================            ] 70% Unzipping... android-ndk-r25c/tool
2026-08-17T04:25:50.0396674Z [============================           ] 70% Unzipping... android-ndk-r25c/tool
2026-08-17T04:25:51.0614047Z [============================           ] 71% Unzipping... android-ndk-r25c/tool
2026-08-17T04:25:52.1245383Z [============================           ] 72% Unzipping... android-ndk-r25c/tool
2026-08-17T04:25:52.8589083Z [=============================          ] 73% Unzipping... android-ndk-r25c/tool
2026-08-17T04:25:53.5841743Z [=============================          ] 74% Unzipping... android-ndk-r25c/tool
2026-08-17T04:25:53.9548729Z [=============================          ] 75% Unzipping... android-ndk-r25c/tool
2026-08-17T04:25:54.3029960Z [==============================         ] 75% Unzipping... android-ndk-r25c/tool
2026-08-17T04:25:55.0334654Z [==============================         ] 76% Unzipping... android-ndk-r25c/tool
2026-08-17T04:25:55.5559520Z [==============================         ] 77% Unzipping... android-ndk-r25c/tool
2026-08-17T04:25:55.5560642Z [==============================         ] 77% Unzipping... android-ndk-r25c/ndk-
2026-08-17T04:25:55.6447593Z [==============================         ] 77% Unzipping... android-ndk-r25c/shad
2026-08-17T04:25:55.7453628Z [==============================         ] 78% Unzipping... android-ndk-r25c/shad
2026-08-17T04:25:55.7454526Z [=======================================] 100% Unzipping... android-ndk-r25c/sha
2026-08-17T04:25:55.7495266Z 
2026-08-17T04:25:55.7727809Z ✅ SDK components installed
2026-08-17T04:25:56.5880548Z Loading package information...                                                  
2026-08-17T04:25:56.6713767Z Loading local repository...                                                     
2026-08-17T04:25:56.6751805Z [=========                              ] 25% Loading local repository...       
2026-08-17T04:25:56.6752624Z Installed packages:
2026-08-17T04:25:56.6896925Z   Path                               | Version       | Description                      | Location                          
2026-08-17T04:25:56.6916403Z   -------                            | -------       | -------                          | -------                           
2026-08-17T04:25:56.6932414Z   build-tools;34.0.0                 | 34.0.0        | Android SDK Build-Tools 34       | build-tools/34.0.0                
2026-08-17T04:25:56.6943656Z   build-tools;35.0.0                 | 35.0.0        | Android SDK Build-Tools 35       | build-tools/35.0.0                
2026-08-17T04:25:56.6945165Z   build-tools;35.0.1                 | 35.0.1        | Android SDK Build-Tools 35.0.1   | build-tools/35.0.1                
2026-08-17T04:25:56.6954073Z   build-tools;36.0.0                 | 36.0.0        | Android SDK Build-Tools 36       | build-tools/36.0.0                
2026-08-17T04:25:56.6961838Z   build-tools;36.1.0                 | 36.1.0        | Android SDK Build-Tools 36.1     | build-tools/36.1.0                
2026-08-17T04:25:56.6968913Z   build-tools;37.0.0                 | 37.0.0        | Android SDK Build-Tools 37       | build-tools/37.0.0                
2026-08-17T04:25:56.6982077Z   cmake;3.22.1                       | 3.22.1        | CMake 3.22.1                     | cmake/3.22.1                      
2026-08-17T04:25:56.6990728Z   cmake;3.31.5                       | 3.31.5        | CMake 3.31.5                     | cmake/3.31.5                      
2026-08-17T04:25:56.6998459Z   cmake;4.1.2                        | 4.1.2         | CMake 4.1.2                      | cmake/4.1.2                       
2026-08-17T04:25:56.7002229Z   extras;android;m2repository        | 47.0.0        | Android Support Repository       | extras/android/m2repository       
2026-08-17T04:25:56.7005067Z   extras;google;google_play_services | 49            | Google Play services             | extras/google/google_play_services
2026-08-17T04:25:56.7013848Z   extras;google;m2repository         | 58            | Google Repository                | extras/google/m2repository        
2026-08-17T04:25:56.7015168Z   ndk;25.2.9519653                   | 25.2.9519653  | NDK (Side by side) 25.2.9519653  | ndk/25.2.9519653                  
2026-08-17T04:25:56.7016815Z   ndk;27.3.13750724                  | 27.3.13750724 | NDK (Side by side) 27.3.13750724 | ndk/27.3.13750724                 
2026-08-17T04:25:56.7022435Z   ndk;28.2.13676358                  | 28.2.13676358 | NDK (Side by side) 28.2.13676358 | ndk/28.2.13676358                 
2026-08-17T04:25:56.7026275Z   ndk;29.0.14206865                  | 29.0.14206865 | NDK (Side by side) 29.0.14206865 | ndk/29.0.14206865                 
2026-08-17T04:25:56.7031318Z   platform-tools                     | 37.0.1        | Android SDK Platform-Tools       | platform-tools                    
2026-08-17T04:25:56.7034908Z   platforms;android-34               | 3             | Android SDK Platform 34          | platforms/android-34              
2026-08-17T04:25:56.7047903Z   platforms;android-34-ext10         | 1             | Android SDK Platform 34-ext10    | platforms/android-34-ext10        
2026-08-17T04:25:56.7049650Z   platforms;android-34-ext11         | 1             | Android SDK Platform 34-ext11    | platforms/android-34-ext11        
2026-08-17T04:25:56.7051677Z   platforms;android-34-ext12         | 1             | Android SDK Platform 34-ext12    | platforms/android-34-ext12        
2026-08-17T04:25:56.7053517Z   platforms;android-34-ext8          | 1             | Android SDK Platform 34-ext8     | platforms/android-34-ext8         
2026-08-17T04:25:56.7055413Z   platforms;android-35               | 2             | Android SDK Platform 35          | platforms/android-35              
2026-08-17T04:25:56.7057524Z   platforms;android-35-ext14         | 1             | Android SDK Platform 35-ext14    | platforms/android-35-ext14        
2026-08-17T04:25:56.7060529Z   platforms;android-35-ext15         | 1             | Android SDK Platform 35-ext15    | platforms/android-35-ext15        
2026-08-17T04:25:56.7062572Z   platforms;android-36               | 2             | Android SDK Platform 36          | platforms/android-36              
2026-08-17T04:25:56.7065082Z   platforms;android-36-ext18         | 1             | Android SDK Platform 36-ext18    | platforms/android-36-ext18        
2026-08-17T04:25:56.7067220Z   platforms;android-36-ext19         | 1             | Android SDK Platform 36-ext19    | platforms/android-36-ext19        
2026-08-17T04:25:56.7069516Z   platforms;android-36.1             | 1             | Android SDK Platform 36.1        | platforms/android-36.1            
2026-08-17T04:25:56.7071455Z   platforms;android-37.0             | 2             | Android SDK Platform 37.0        | platforms/android-37.0            
2026-08-17T04:25:56.7072945Z   platforms;android-37.1             | 1             | Android SDK Platform 37.1        | platforms/android-37.1            
2026-08-17T04:25:56.7076516Z   platforms;android-37.2-beta1       | 1             | Android SDK Platform 37.2-beta1  | platforms/android-37.2-beta1      
2026-08-17T04:25:56.7078764Z   platforms;android-37.2-beta2       | 2             | Android SDK Platform 37.2-beta2  | platforms/android-37.2-beta2      
2026-08-17T04:25:56.7084674Z 
2026-08-17T04:25:56.7222407Z ##[group]Run if [ -f "gradle/wrapper/gradle-wrapper.jar" ]; then
2026-08-17T04:25:56.7222952Z [36;1mif [ -f "gradle/wrapper/gradle-wrapper.jar" ]; then[0m
2026-08-17T04:25:56.7223430Z [36;1m  ./gradlew assembleDebug --stacktrace --no-daemon[0m
2026-08-17T04:25:56.7223819Z [36;1melse[0m
2026-08-17T04:25:56.7224183Z [36;1m  echo "⚠️ wrapper jar missing, using gradle directly"[0m
2026-08-17T04:25:56.7224663Z [36;1m  gradle assembleDebug --stacktrace --no-daemon[0m
2026-08-17T04:25:56.7225034Z [36;1mfi[0m
2026-08-17T04:25:56.7284652Z shell: /usr/bin/bash --noprofile --norc -e -o pipefail {0}
2026-08-17T04:25:56.7285066Z env:
2026-08-17T04:25:56.7285638Z   GRADLE_VERSION: 8.5
2026-08-17T04:25:56.7286060Z   JAVA_VERSION: 17
2026-08-17T04:25:56.7287190Z   JAVA_HOME: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T04:25:56.7287786Z   JAVA_HOME_17_X64: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T04:25:56.7289676Z   GRADLE_ACTION_ID: gradle/actions/setup-gradle
2026-08-17T04:25:56.7290463Z   GRADLE_USER_HOME: /home/runner/.gradle
2026-08-17T04:25:56.7290960Z   GRADLE_BUILD_ACTION_SETUP_COMPLETED: true
2026-08-17T04:25:56.7291670Z   GRADLE_BUILD_ACTION_CACHE_RESTORED: true
2026-08-17T04:25:56.7292204Z   DEVELOCITY_INJECTION_INIT_SCRIPT_NAME: gradle-actions.inject-develocity.init.gradle
2026-08-17T04:25:56.7294292Z   DEVELOCITY_INJECTION_CUSTOM_VALUE: gradle-actions
2026-08-17T04:25:56.7294677Z   GITHUB_DEPENDENCY_GRAPH_ENABLED: false
2026-08-17T04:25:56.7295023Z   ANDROID_HOME: /usr/local/lib/android/sdk
2026-08-17T04:25:56.7295897Z   ANDROID_SDK_ROOT: /usr/local/lib/android/sdk
2026-08-17T04:25:56.7296314Z ##[endgroup]
2026-08-17T04:25:56.7940491Z Error: Could not find or load main class org.gradle.wrapper.GradleWrapperMain
2026-08-17T04:25:56.7941754Z Caused by: java.lang.ClassNotFoundException: org.gradle.wrapper.GradleWrapperMain
2026-08-17T04:25:56.8000154Z ##[error]Process completed with exit code 1.
2026-08-17T04:25:56.8076106Z Node 20 is being deprecated. This workflow is running with Node 24 by default. If you need to temporarily use Node 20, you can set the ACTIONS_ALLOW_USE_UNSECURE_NODE_VERSION=true environment variable. For more information see: https://github.blog/changelog/2025-09-19-deprecation-of-node-20-on-github-actions-runners/
2026-08-17T04:25:56.8077477Z ##[group]Run actions/upload-artifact@v4
2026-08-17T04:25:56.8077847Z with:
2026-08-17T04:25:56.8078128Z   name: build-logs
2026-08-17T04:25:56.8078736Z   path: app/build/reports/**
app/build/outputs/logs/**
**/*.log

2026-08-17T04:25:56.8079179Z   if-no-files-found: ignore
2026-08-17T04:25:56.8079498Z   retention-days: 7
2026-08-17T04:25:56.8079782Z   compression-level: 6
2026-08-17T04:25:56.8080075Z   overwrite: false
2026-08-17T04:25:56.8080353Z   include-hidden-files: false
2026-08-17T04:25:56.8080660Z env:
2026-08-17T04:25:56.8080910Z   GRADLE_VERSION: 8.5
2026-08-17T04:25:56.8081184Z   JAVA_VERSION: 17
2026-08-17T04:25:56.8081613Z   JAVA_HOME: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T04:25:56.8082173Z   JAVA_HOME_17_X64: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T04:25:56.8082776Z   GRADLE_ACTION_ID: gradle/actions/setup-gradle
2026-08-17T04:25:56.8083313Z   GRADLE_USER_HOME: /home/runner/.gradle
2026-08-17T04:25:56.8083922Z   GRADLE_BUILD_ACTION_SETUP_COMPLETED: true
2026-08-17T04:25:56.8084528Z   GRADLE_BUILD_ACTION_CACHE_RESTORED: true
2026-08-17T04:25:56.8085304Z   DEVELOCITY_INJECTION_INIT_SCRIPT_NAME: gradle-actions.inject-develocity.init.gradle
2026-08-17T04:25:56.8086025Z   DEVELOCITY_INJECTION_CUSTOM_VALUE: gradle-actions
2026-08-17T04:25:56.8086628Z   GITHUB_DEPENDENCY_GRAPH_ENABLED: false
2026-08-17T04:25:56.8101644Z   ANDROID_HOME: /usr/local/lib/android/sdk
2026-08-17T04:25:56.8102223Z   ANDROID_SDK_ROOT: /usr/local/lib/android/sdk
2026-08-17T04:25:56.8102732Z ##[endgroup]
2026-08-17T04:25:56.9792137Z (node:2743) [DEP0040] DeprecationWarning: The `punycode` module is deprecated. Please use a userland alternative instead.
2026-08-17T04:25:56.9793028Z (Use `node --trace-deprecation ...` to show where the warning was created)
2026-08-17T04:25:56.9974815Z No files were found with the provided path: app/build/reports/**
2026-08-17T04:25:56.9975400Z app/build/outputs/logs/**
2026-08-17T04:25:56.9975794Z **/*.log. No artifacts will be uploaded.
2026-08-17T04:25:57.0268596Z Node 20 is being deprecated. This workflow is running with Node 24 by default. If you need to temporarily use Node 20, you can set the ACTIONS_ALLOW_USE_UNSECURE_NODE_VERSION=true environment variable. For more information see: https://github.blog/changelog/2025-09-19-deprecation-of-node-20-on-github-actions-runners/
2026-08-17T04:25:57.0270828Z Post job cleanup.
2026-08-17T04:25:57.2659456Z In post-action step
2026-08-17T04:25:57.2670034Z ##[group]Stopping Gradle daemons
2026-08-17T04:25:57.2671393Z ##[endgroup]
2026-08-17T04:25:57.2692193Z ##[group]Provision Gradle >= 8.11
2026-08-17T04:25:58.1570803Z Cache hit for: gradle-8.11
2026-08-17T04:25:59.3850831Z Received 33554432 of 136585574 (24.6%), 32.0 MBs/sec
2026-08-17T04:26:00.3213836Z Received 136585574 of 136585574 (100.0%), 67.2 MBs/sec
2026-08-17T04:26:00.3217003Z Cache Size: ~130 MB (136585574 B)
2026-08-17T04:26:00.3257633Z [command]/usr/bin/tar -xf /home/runner/work/_temp/746d5caf-59e5-43da-b7f1-db622ccdb9f0/cache.tzst -P -C /home/runner/work/AutoBOT/AutoBOT --use-compress-program unzstd
2026-08-17T04:26:00.5024454Z Cache restored successfully
2026-08-17T04:26:00.5091342Z Restored Gradle distribution gradle-8.11 from cache to /home/runner/work/_temp/.gradle-actions/gradle-installations/downloads/gradle-8.11-bin.zip
2026-08-17T04:26:00.5109194Z [command]/usr/bin/unzip -o -q /home/runner/work/_temp/.gradle-actions/gradle-installations/downloads/gradle-8.11-bin.zip
2026-08-17T04:26:01.6180383Z Extracted Gradle 8.11 to /home/runner/work/_temp/.gradle-actions/gradle-installations/installs/gradle-8.11
2026-08-17T04:26:01.6182541Z Provisioned Gradle executable /home/runner/work/_temp/.gradle-actions/gradle-installations/installs/gradle-8.11/bin/gradle
2026-08-17T04:26:01.6183639Z ##[endgroup]
2026-08-17T04:26:01.6190176Z ##[group]Executing Gradle to clean up caches
2026-08-17T04:26:01.6190696Z Cleaning up caches last used before 1786940721943
2026-08-17T04:26:01.6195025Z [command]/home/runner/work/_temp/.gradle-actions/gradle-installations/installs/gradle-8.11/bin/gradle -g /home/runner/.gradle -I init.gradle --info --no-daemon --no-scan --build-cache -DGITHUB_DEPENDENCY_GRAPH_ENABLED=false -DGRADLE_ACTIONS_SKIP_BUILD_RESULT_CAPTURE=true noop
2026-08-17T04:26:02.1067564Z Initialized native services in: /home/runner/.gradle/native
2026-08-17T04:26:02.1080278Z Initialized jansi services in: /home/runner/.gradle/native
2026-08-17T04:26:02.3171355Z To honour the JVM settings for this build a single-use Daemon process will be forked. For more on this, please refer to https://docs.gradle.org/8.11/userguide/gradle_daemon.html#sec:disabling_the_daemon in the Gradle documentation.
2026-08-17T04:26:02.3218946Z Starting process 'Gradle build daemon'. Working directory: /home/runner/.gradle/daemon/8.11 Command: /usr/lib/jvm/temurin-17-jdk-amd64/bin/java --add-opens=java.base/java.lang=ALL-UNNAMED --add-opens=java.base/java.lang.invoke=ALL-UNNAMED --add-opens=java.base/java.util=ALL-UNNAMED --add-opens=java.prefs/java.util.prefs=ALL-UNNAMED --add-exports=jdk.compiler/com.sun.tools.javac.api=ALL-UNNAMED --add-exports=jdk.compiler/com.sun.tools.javac.util=ALL-UNNAMED --add-opens=java.base/java.util=ALL-UNNAMED --add-opens=java.prefs/java.util.prefs=ALL-UNNAMED --add-opens=java.base/java.nio.charset=ALL-UNNAMED --add-opens=java.base/java.net=ALL-UNNAMED --add-opens=java.base/java.util.concurrent.atomic=ALL-UNNAMED --add-opens=java.xml/javax.xml.namespace=ALL-UNNAMED -XX:MaxMetaspaceSize=384m -XX:+HeapDumpOnOutOfMemoryError -Xms256m -Xmx512m -Dfile.encoding=UTF-8 -Duser.country -Duser.language=en -Duser.variant -cp /home/runner/work/_temp/.gradle-actions/gradle-installations/installs/gradle-8.11/lib/gradle-daemon-main-8.11.jar -javaagent:/home/runner/work/_temp/.gradle-actions/gradle-installations/installs/gradle-8.11/lib/agents/gradle-instrumentation-agent-8.11.jar org.gradle.launcher.daemon.bootstrap.GradleDaemon 8.11
2026-08-17T04:26:02.3235620Z Successfully started process 'Gradle build daemon'
2026-08-17T04:26:03.3180438Z An attempt to start the daemon took 0.974 secs.
2026-08-17T04:26:03.4162643Z The client will now receive all logging from the daemon (pid: 2846). The daemon log file: /home/runner/.gradle/daemon/8.11/daemon-2846.out.log
2026-08-17T04:26:03.4163878Z Daemon will be stopped at the end of the build 
2026-08-17T04:26:03.7164191Z Using 4 worker leases.
2026-08-17T04:26:03.9171012Z Received JVM installation metadata from '/usr/lib/jvm/temurin-17-jdk-amd64': {JAVA_HOME=/usr/lib/jvm/temurin-17-jdk-amd64, JAVA_VERSION=17.0.20, JAVA_VENDOR=Eclipse Adoptium, RUNTIME_NAME=OpenJDK Runtime Environment, RUNTIME_VERSION=17.0.20+8, VM_NAME=OpenJDK 64-Bit Server VM, VM_VERSION=17.0.20+8, VM_VENDOR=Eclipse Adoptium, OS_ARCH=amd64}
2026-08-17T04:26:04.2179686Z Watching the file system is configured to be enabled if available
2026-08-17T04:26:04.3162947Z Now considering [/home/runner/work/_temp/dummy-cleanup-project] as hierarchies to watch
2026-08-17T04:26:04.3198179Z File system watching is active
2026-08-17T04:26:04.7163585Z Caching disabled for Groovy DSL script compilation (cp_init) because:
2026-08-17T04:26:04.7164673Z   Build cache is disabled
2026-08-17T04:26:04.7165279Z   Not worth caching.
2026-08-17T04:26:04.7166588Z Compiling initialization script '/home/runner/work/_temp/dummy-cleanup-project/init.gradle' using SubsetScriptTransformer.
2026-08-17T04:26:05.4195437Z Caching disabled for Groovy DSL script compilation (init) because:
2026-08-17T04:26:05.4197942Z   Build cache is disabled
2026-08-17T04:26:05.4198843Z   Not worth caching.
2026-08-17T04:26:05.4200302Z Compiling initialization script '/home/runner/work/_temp/dummy-cleanup-project/init.gradle' using BuildScriptTransformer.
2026-08-17T04:26:06.3163562Z gradle/actions: Not capturing build results
2026-08-17T04:26:06.4165363Z Starting Build
2026-08-17T04:26:06.5180082Z Settings evaluated using settings file '/home/runner/work/_temp/dummy-cleanup-project/settings.gradle'.
2026-08-17T04:26:06.5221551Z Using local directory build cache for the root build (location = /home/runner/.gradle/caches/build-cache-1, remove unused entries = older than 2026-08-17 04:25:21 UTC).
2026-08-17T04:26:06.6165189Z Projects loaded. Root project using build file '/home/runner/work/_temp/dummy-cleanup-project/build.gradle'.
2026-08-17T04:26:06.6166513Z Included projects: [root project 'dummy-cleanup-project']
2026-08-17T04:26:06.8179093Z 
2026-08-17T04:26:06.8189363Z > Configure project :
2026-08-17T04:26:06.8199952Z Evaluating root project 'dummy-cleanup-project' using build file '/home/runner/work/_temp/dummy-cleanup-project/build.gradle'.
2026-08-17T04:26:06.8201286Z All projects evaluated.
2026-08-17T04:26:06.9171417Z Task name matched 'noop'
2026-08-17T04:26:06.9205552Z Selected primary task 'noop' from project :
2026-08-17T04:26:06.9206768Z Tasks to be executed: [task ':noop']
2026-08-17T04:26:06.9207552Z Tasks that were excluded: []
2026-08-17T04:26:06.9208770Z Resolve mutations for :noop (Thread[Execution worker,5,main]) started.
2026-08-17T04:26:06.9209944Z :noop (Thread[Execution worker,5,main]) started.
2026-08-17T04:26:07.0196515Z 
2026-08-17T04:26:07.0204942Z > Task :noop UP-TO-DATE
2026-08-17T04:26:07.0228908Z Skipping task ':noop' as it has no actions.
2026-08-17T04:26:07.0229460Z 
2026-08-17T04:26:07.0229723Z BUILD SUCCESSFUL in 5s
2026-08-17T04:26:07.0230987Z Build cache (/home/runner/.gradle/caches/build-cache-1) removing files not accessed on or after Mon Aug 17 04:25:21 UTC 2026.
2026-08-17T04:26:07.0232525Z Build cache (/home/runner/.gradle/caches/build-cache-1) cleanup deleted 0 files/directories.
2026-08-17T04:26:07.0233753Z Build cache (/home/runner/.gradle/caches/build-cache-1) cleaned up in 0.004 secs.
2026-08-17T04:26:07.1170324Z groovy-dsl (/home/runner/.gradle/caches/8.11/groovy-dsl) removing files not accessed on or after Mon Aug 17 04:25:21 UTC 2026.
2026-08-17T04:26:07.1189701Z groovy-dsl (/home/runner/.gradle/caches/8.11/groovy-dsl) cleanup deleted 2 files/directories.
2026-08-17T04:26:07.1191145Z groovy-dsl (/home/runner/.gradle/caches/8.11/groovy-dsl) cleaned up in 0.02 secs.
2026-08-17T04:26:07.2166417Z jars (/home/runner/.gradle/caches/jars-9) cleanup deleted 0 files/directories.
2026-08-17T04:26:07.2182329Z jars (/home/runner/.gradle/caches/jars-9) removing files not accessed on or after Mon Aug 17 04:25:21 UTC 2026.
2026-08-17T04:26:07.4169239Z jars (/home/runner/.gradle/caches/jars-9) cleanup deleted 161 files/directories.
2026-08-17T04:26:07.4184694Z jars (/home/runner/.gradle/caches/jars-9) cleaned up in 0.258 secs.
2026-08-17T04:26:07.4186302Z Artifact transforms cache (/home/runner/.gradle/caches/8.11/transforms) removing files not accessed on or after Mon Aug 17 04:25:21 UTC 2026.
2026-08-17T04:26:07.4189204Z Artifact transforms cache (/home/runner/.gradle/caches/8.11/transforms) cleanup deleted 0 files/directories.
2026-08-17T04:26:07.4190800Z Artifact transforms cache (/home/runner/.gradle/caches/8.11/transforms) cleaned up in 0.0 secs.
2026-08-17T04:26:07.4192668Z dependencies-accessors (/home/runner/.gradle/caches/8.11/dependencies-accessors) removing files not accessed on or after Mon Aug 17 04:25:21 UTC 2026.
2026-08-17T04:26:07.4194831Z dependencies-accessors (/home/runner/.gradle/caches/8.11/dependencies-accessors) cleanup deleted 0 files/directories.
2026-08-17T04:26:07.4196747Z dependencies-accessors (/home/runner/.gradle/caches/8.11/dependencies-accessors) cleaned up in 0.0 secs.
2026-08-17T04:26:07.4198468Z artifact cache (/home/runner/.gradle/caches/modules-2) cleanup deleted 0 files/directories.
2026-08-17T04:26:07.4200469Z artifact cache (/home/runner/.gradle/caches/modules-2) [subdir: /home/runner/.gradle/caches/modules-2/resources-2.1] cleanup deleted 0 files/directories.
2026-08-17T04:26:07.4203379Z artifact cache (/home/runner/.gradle/caches/modules-2) [subdir: /home/runner/.gradle/caches/modules-2/resources-2.1] removing files not accessed on or after Mon Aug 17 04:25:21 UTC 2026.
2026-08-17T04:26:07.4205838Z artifact cache (/home/runner/.gradle/caches/modules-2) [subdir: /home/runner/.gradle/caches/modules-2/resources-2.1] cleanup deleted 0 files/directories.
2026-08-17T04:26:07.4208040Z artifact cache (/home/runner/.gradle/caches/modules-2) [subdir: /home/runner/.gradle/caches/modules-2/files-2.1] cleanup deleted 0 files/directories.
2026-08-17T04:26:07.4210718Z artifact cache (/home/runner/.gradle/caches/modules-2) [subdir: /home/runner/.gradle/caches/modules-2/files-2.1] removing files not accessed on or after Mon Aug 17 04:25:21 UTC 2026.
2026-08-17T04:26:07.6166388Z artifact cache (/home/runner/.gradle/caches/modules-2) [subdir: /home/runner/.gradle/caches/modules-2/files-2.1] cleanup deleted 910 files/directories.
2026-08-17T04:26:07.7182613Z artifact cache (/home/runner/.gradle/caches/modules-2) [subdir: /home/runner/.gradle/caches/modules-2/metadata-2.107] cleanup deleted 1 files/directories.
2026-08-17T04:26:08.5175328Z artifact cache (/home/runner/.gradle/caches/modules-2) cleanup deleted 1 files/directories.
2026-08-17T04:26:08.5186682Z artifact cache (/home/runner/.gradle/caches/modules-2) cleaned up in 1.13 secs.
2026-08-17T04:26:08.6074408Z ##[endgroup]
2026-08-17T04:26:08.6075083Z ##[group]Caching Gradle state
2026-08-17T04:26:08.6765460Z [command]/usr/bin/tar --posix -cf cache.tzst --exclude cache.tzst -P -C /home/runner/work/AutoBOT/AutoBOT --files-from manifest.txt --use-compress-program zstdmt
2026-08-17T04:26:08.7003393Z [command]/usr/bin/tar --posix -cf cache.tzst --exclude cache.tzst -P -C /home/runner/work/AutoBOT/AutoBOT --files-from manifest.txt --use-compress-program zstdmt
2026-08-17T04:26:09.2570058Z Sent 71054 of 71054 (100.0%), 0.2 MBs/sec
2026-08-17T04:26:09.2788108Z Sent 109810 of 109810 (100.0%), 0.3 MBs/sec
2026-08-17T04:26:09.4636016Z Saved cache entry with key gradle-instrumented-jars-v1-9c61e5415aae9d176cd4e9f7c7745359 from /home/runner/.gradle/caches/jars-*/*/ in 808ms
2026-08-17T04:26:09.4787346Z Saved cache entry with key gradle-groovy-dsl-v1-49c99d70bf79c1bbad517b6bf2fc4bee from /home/runner/.gradle/caches/*/groovy-dsl/*/ in 805ms
2026-08-17T04:26:09.4958387Z [command]/usr/bin/tar --posix -cf cache.tzst --exclude cache.tzst -P -C /home/runner/work/AutoBOT/AutoBOT --files-from manifest.txt --use-compress-program zstdmt
2026-08-17T04:26:09.9724704Z Sent 52521 of 52521 (100.0%), 0.2 MBs/sec
2026-08-17T04:26:10.1765412Z Saved cache entry with key gradle-home-v1|Linux-X64|build[266babc85e2a7f6e4c23c8d6be839361]-84d5d5ce0b2bfeb338a30d7a2cbda3b8fab7d1b7 from /home/runner/.gradle/caches,/home/runner/.gradle/notifications,/home/runner/.gradle/.setup-gradle in 690ms
2026-08-17T04:26:10.1766762Z ##[endgroup]
2026-08-17T04:26:10.1772419Z Generating Job Summary
2026-08-17T04:26:10.1785722Z Completed post-action step
2026-08-17T04:26:10.2006411Z Node 20 is being deprecated. This workflow is running with Node 24 by default. If you need to temporarily use Node 20, you can set the ACTIONS_ALLOW_USE_UNSECURE_NODE_VERSION=true environment variable. For more information see: https://github.blog/changelog/2025-09-19-deprecation-of-node-20-on-github-actions-runners/
2026-08-17T04:26:10.2007970Z Post job cleanup.
2026-08-17T04:26:10.3419853Z (node:2937) [DEP0040] DeprecationWarning: The `punycode` module is deprecated. Please use a userland alternative instead.
2026-08-17T04:26:10.3421375Z (Use `node --trace-deprecation ...` to show where the warning was created)
2026-08-17T04:26:10.3668818Z Node 20 is being deprecated. This workflow is running with Node 24 by default. If you need to temporarily use Node 20, you can set the ACTIONS_ALLOW_USE_UNSECURE_NODE_VERSION=true environment variable. For more information see: https://github.blog/changelog/2025-09-19-deprecation-of-node-20-on-github-actions-runners/
2026-08-17T04:26:10.3670363Z Post job cleanup.
2026-08-17T04:26:10.4675110Z [command]/usr/bin/git version
2026-08-17T04:26:10.4717610Z git version 2.54.0
2026-08-17T04:26:10.4754380Z Temporarily overriding HOME='/home/runner/work/_temp/12c762fd-c3d5-4478-a260-70c626284294' before making global git config changes
2026-08-17T04:26:10.4756081Z Adding repository directory to the temporary git global config as a safe directory
2026-08-17T04:26:10.4759899Z [command]/usr/bin/git config --global --add safe.directory /home/runner/work/AutoBOT/AutoBOT
2026-08-17T04:26:10.4801254Z [command]/usr/bin/git config --local --name-only --get-regexp core\.sshCommand
2026-08-17T04:26:10.4839257Z [command]/usr/bin/git submodule foreach --recursive sh -c "git config --local --name-only --get-regexp 'core\.sshCommand' && git config --local --unset-all 'core.sshCommand' || :"
2026-08-17T04:26:10.5112435Z [command]/usr/bin/git config --local --name-only --get-regexp http\.https\:\/\/github\.com\/\.extraheader
2026-08-17T04:26:10.5141341Z http.https://github.com/.extraheader
2026-08-17T04:26:10.5153792Z [command]/usr/bin/git config --local --unset-all http.https://github.com/.extraheader
2026-08-17T04:26:10.5192023Z [command]/usr/bin/git submodule foreach --recursive sh -c "git config --local --name-only --get-regexp 'http\.https\:\/\/github\.com\/\.extraheader' && git config --local --unset-all 'http.https://github.com/.extraheader' || :"
2026-08-17T04:26:10.5500784Z [command]/usr/bin/git config --local --name-only --get-regexp ^includeIf\.gitdir:
2026-08-17T04:26:10.5539770Z [command]/usr/bin/git submodule foreach --recursive git config --local --show-origin --name-only --get-regexp remote.origin.url
2026-08-17T04:26:10.5966842Z Cleaning up orphan processes
2026-08-17T04:26:10.6297706Z ##[warning]Node.js 20 is deprecated. The following actions target Node.js 20 but are being forced to run on Node.js 24: actions/checkout@v4, actions/setup-java@v4, actions/upload-artifact@v4, gradle/actions/setup-gradle@v4. For more information see: https://github.blog/changelog/2025-09-19-deprecation-of-node-20-on-github-actions-runners/
