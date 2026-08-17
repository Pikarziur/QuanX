2026-08-17T01:47:45.9720900Z Current runner version: '2.336.0'
2026-08-17T01:47:45.9746520Z ##[group]Runner Image Provisioner
2026-08-17T01:47:45.9747759Z Hosted Compute Agent
2026-08-17T01:47:45.9748359Z Version: 20260729.566
2026-08-17T01:47:45.9748960Z Commit: cf7153fe6e25b664e8693c24944bf2b00355d109
2026-08-17T01:47:45.9749730Z Build Date: 2026-07-29T19:17:02Z
2026-08-17T01:47:45.9750390Z Worker ID: {87368c4b-bbd3-44c7-a1e4-237aa4691b47}
2026-08-17T01:47:45.9751037Z Azure Region: westus3
2026-08-17T01:47:45.9751818Z ##[endgroup]
2026-08-17T01:47:45.9753168Z ##[group]Operating System
2026-08-17T01:47:45.9753756Z Ubuntu
2026-08-17T01:47:45.9754257Z 24.04.4
2026-08-17T01:47:45.9754762Z LTS
2026-08-17T01:47:45.9755257Z ##[endgroup]
2026-08-17T01:47:45.9755770Z ##[group]Runner Image
2026-08-17T01:47:45.9756320Z Image: ubuntu-24.04
2026-08-17T01:47:45.9756877Z Version: 20260810.271.1
2026-08-17T01:47:45.9758067Z Included Software: https://github.com/actions/runner-images/blob/ubuntu24/20260810.271/images/ubuntu/Ubuntu2404-Readme.md
2026-08-17T01:47:45.9759499Z Image Release: https://github.com/actions/runner-images/releases/tag/ubuntu24%2F20260810.271
2026-08-17T01:47:45.9760352Z ##[endgroup]
2026-08-17T01:47:45.9761798Z ##[group]GITHUB_TOKEN Permissions
2026-08-17T01:47:45.9764114Z Contents: read
2026-08-17T01:47:45.9764699Z Metadata: read
2026-08-17T01:47:45.9765223Z Packages: read
2026-08-17T01:47:45.9765795Z ##[endgroup]
2026-08-17T01:47:45.9767873Z Secret source: Actions
2026-08-17T01:47:45.9768865Z Prepare workflow directory
2026-08-17T01:47:46.0134754Z Prepare all required actions
2026-08-17T01:47:46.0203144Z Getting action download info
2026-08-17T01:47:46.3325279Z Download action repository 'actions/checkout@v4' (SHA:11d5960a326750d5838078e36cf38b85af677262)
2026-08-17T01:47:46.4922613Z Download action repository 'actions/setup-java@v4' (SHA:cf277c60eb25467037889841efdb72551f06f6c3)
2026-08-17T01:47:47.4957263Z Download action repository 'gradle/actions@v4' (SHA:ed408507eac070d1f99cc633dbcf757c94c7933a)
2026-08-17T01:47:49.2190456Z Download action repository 'android-actions/setup-android@v4' (SHA:40fd30fb8d7440372e1316f5d1809ec01dcd3699)
2026-08-17T01:47:49.7446653Z Download action repository 'actions/upload-artifact@v4' (SHA:ea165f8d65b6e75b540449e92b4886f43607fa02)
2026-08-17T01:47:50.2042991Z Complete job name: Build Android APK
2026-08-17T01:47:50.2664661Z Node 20 is being deprecated. This workflow is running with Node 24 by default. If you need to temporarily use Node 20, you can set the ACTIONS_ALLOW_USE_UNSECURE_NODE_VERSION=true environment variable. For more information see: https://github.blog/changelog/2025-09-19-deprecation-of-node-20-on-github-actions-runners/
2026-08-17T01:47:50.2672239Z ##[group]Run actions/checkout@v4
2026-08-17T01:47:50.2672707Z with:
2026-08-17T01:47:50.2673067Z   repository: Pikarziur/AutoBOT
2026-08-17T01:47:50.2675338Z   token: ***
2026-08-17T01:47:50.2675652Z   ssh-strict: true
2026-08-17T01:47:50.2675997Z   ssh-user: git
2026-08-17T01:47:50.2676294Z   persist-credentials: true
2026-08-17T01:47:50.2676656Z   clean: true
2026-08-17T01:47:50.2676980Z   sparse-checkout-cone-mode: true
2026-08-17T01:47:50.2677384Z   fetch-depth: 1
2026-08-17T01:47:50.2677663Z   fetch-tags: false
2026-08-17T01:47:50.2677965Z   show-progress: true
2026-08-17T01:47:50.2678321Z   lfs: false
2026-08-17T01:47:50.2678662Z   submodules: false
2026-08-17T01:47:50.2678981Z   set-safe-directory: true
2026-08-17T01:47:50.2679328Z   allow-unsafe-pr-checkout: false
2026-08-17T01:47:50.2679747Z env:
2026-08-17T01:47:50.2680037Z   GRADLE_VERSION: 8.5
2026-08-17T01:47:50.2680329Z   JAVA_VERSION: 17
2026-08-17T01:47:50.2680618Z ##[endgroup]
2026-08-17T01:47:50.3687861Z Syncing repository: Pikarziur/AutoBOT
2026-08-17T01:47:50.3690553Z ##[group]Getting Git version info
2026-08-17T01:47:50.3691776Z Working directory is '/home/runner/work/AutoBOT/AutoBOT'
2026-08-17T01:47:50.3692978Z [command]/usr/bin/git version
2026-08-17T01:47:50.3815374Z git version 2.54.0
2026-08-17T01:47:50.3832948Z ##[endgroup]
2026-08-17T01:47:50.3846332Z Temporarily overriding HOME='/home/runner/work/_temp/257f62a7-c14c-4aa5-9db2-97cc8624a88c' before making global git config changes
2026-08-17T01:47:50.3848050Z Adding repository directory to the temporary git global config as a safe directory
2026-08-17T01:47:50.3852095Z [command]/usr/bin/git config --global --add safe.directory /home/runner/work/AutoBOT/AutoBOT
2026-08-17T01:47:50.3885411Z Deleting the contents of '/home/runner/work/AutoBOT/AutoBOT'
2026-08-17T01:47:50.3886947Z ##[group]Initializing the repository
2026-08-17T01:47:50.3890115Z [command]/usr/bin/git init /home/runner/work/AutoBOT/AutoBOT
2026-08-17T01:47:50.3956872Z hint: Using 'master' as the name for the initial branch. This default branch name
2026-08-17T01:47:50.3957675Z hint: will change to "main" in Git 3.0. To configure the initial branch name
2026-08-17T01:47:50.3958248Z hint: to use in all of your new repositories, which will suppress this warning,
2026-08-17T01:47:50.3958748Z hint: call:
2026-08-17T01:47:50.3959138Z hint:
2026-08-17T01:47:50.3959667Z hint: 	git config --global init.defaultBranch <name>
2026-08-17T01:47:50.3960184Z hint:
2026-08-17T01:47:50.3960710Z hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
2026-08-17T01:47:50.3961724Z hint: 'development'. The just-created branch can be renamed via this command:
2026-08-17T01:47:50.3962385Z hint:
2026-08-17T01:47:50.3962756Z hint: 	git branch -m <name>
2026-08-17T01:47:50.3963148Z hint:
2026-08-17T01:47:50.3963719Z hint: Disable this message with "git config set advice.defaultBranchName false"
2026-08-17T01:47:50.3964591Z Initialized empty Git repository in /home/runner/work/AutoBOT/AutoBOT/.git/
2026-08-17T01:47:50.3967899Z [command]/usr/bin/git remote add origin https://github.com/Pikarziur/AutoBOT
2026-08-17T01:47:50.3999616Z ##[endgroup]
2026-08-17T01:47:50.4000395Z ##[group]Disabling automatic garbage collection
2026-08-17T01:47:50.4003812Z [command]/usr/bin/git config --local gc.auto 0
2026-08-17T01:47:50.4031542Z ##[endgroup]
2026-08-17T01:47:50.4032282Z ##[group]Setting up auth
2026-08-17T01:47:50.4038965Z [command]/usr/bin/git config --local --name-only --get-regexp core\.sshCommand
2026-08-17T01:47:50.4067124Z [command]/usr/bin/git submodule foreach --recursive sh -c "git config --local --name-only --get-regexp 'core\.sshCommand' && git config --local --unset-all 'core.sshCommand' || :"
2026-08-17T01:47:50.4453474Z [command]/usr/bin/git config --local --name-only --get-regexp http\.https\:\/\/github\.com\/\.extraheader
2026-08-17T01:47:50.4485685Z [command]/usr/bin/git submodule foreach --recursive sh -c "git config --local --name-only --get-regexp 'http\.https\:\/\/github\.com\/\.extraheader' && git config --local --unset-all 'http.https://github.com/.extraheader' || :"
2026-08-17T01:47:50.4684894Z [command]/usr/bin/git config --local --name-only --get-regexp ^includeIf\.gitdir:
2026-08-17T01:47:50.4715567Z [command]/usr/bin/git submodule foreach --recursive git config --local --show-origin --name-only --get-regexp remote.origin.url
2026-08-17T01:47:50.4894336Z [command]/usr/bin/git config --local http.https://github.com/.extraheader AUTHORIZATION: basic ***
2026-08-17T01:47:50.4924519Z ##[endgroup]
2026-08-17T01:47:50.4925091Z ##[group]Fetching the repository
2026-08-17T01:47:50.4933222Z [command]/usr/bin/git -c protocol.version=2 fetch --no-tags --prune --no-recurse-submodules --depth=1 origin +11a37562b6a2eb855584b2d8092f1232349873c3:refs/remotes/origin/main
2026-08-17T01:47:51.0335600Z From https://github.com/Pikarziur/AutoBOT
2026-08-17T01:47:51.0336689Z  * [new ref]         11a37562b6a2eb855584b2d8092f1232349873c3 -> origin/main
2026-08-17T01:47:51.0358703Z ##[endgroup]
2026-08-17T01:47:51.0359759Z ##[group]Determining the checkout info
2026-08-17T01:47:51.0360829Z ##[endgroup]
2026-08-17T01:47:51.0367888Z [command]/usr/bin/git sparse-checkout disable
2026-08-17T01:47:51.0408559Z [command]/usr/bin/git config --local --unset-all extensions.worktreeConfig
2026-08-17T01:47:51.0435408Z ##[group]Checking out the ref
2026-08-17T01:47:51.0449638Z [command]/usr/bin/git checkout --progress --force -B main refs/remotes/origin/main
2026-08-17T01:47:51.0518598Z Switched to a new branch 'main'
2026-08-17T01:47:51.0519537Z branch 'main' set up to track 'origin/main'.
2026-08-17T01:47:51.0525025Z ##[endgroup]
2026-08-17T01:47:51.0557492Z [command]/usr/bin/git log -1 --format=%H
2026-08-17T01:47:51.0579197Z 11a37562b6a2eb855584b2d8092f1232349873c3
2026-08-17T01:47:51.0888715Z Node 20 is being deprecated. This workflow is running with Node 24 by default. If you need to temporarily use Node 20, you can set the ACTIONS_ALLOW_USE_UNSECURE_NODE_VERSION=true environment variable. For more information see: https://github.blog/changelog/2025-09-19-deprecation-of-node-20-on-github-actions-runners/
2026-08-17T01:47:51.0890216Z ##[group]Run actions/setup-java@v4
2026-08-17T01:47:51.0890540Z with:
2026-08-17T01:47:51.0890868Z   distribution: temurin
2026-08-17T01:47:51.0891398Z   java-version: 17
2026-08-17T01:47:51.0891718Z   java-package: jdk
2026-08-17T01:47:51.0892064Z   check-latest: false
2026-08-17T01:47:51.0892374Z   server-id: github
2026-08-17T01:47:51.0892684Z   server-username: GITHUB_ACTOR
2026-08-17T01:47:51.0893010Z   server-password: GITHUB_TOKEN
2026-08-17T01:47:51.0893321Z   overwrite-settings: true
2026-08-17T01:47:51.0893659Z   job-status: success
2026-08-17T01:47:51.0895827Z   token: ***
2026-08-17T01:47:51.0896118Z env:
2026-08-17T01:47:51.0896445Z   GRADLE_VERSION: 8.5
2026-08-17T01:47:51.0896734Z   JAVA_VERSION: 17
2026-08-17T01:47:51.0897046Z ##[endgroup]
2026-08-17T01:47:51.2477607Z ##[warning]setup-java v4 is deprecated and will no longer receive updates. Please migrate to actions/setup-java@v5.
2026-08-17T01:47:51.2489756Z ##[group]Installed distributions
2026-08-17T01:47:51.2714719Z Resolved Java 17.0.20+8 from tool-cache
2026-08-17T01:47:51.2715377Z Setting Java 17.0.20+8 as the default
2026-08-17T01:47:51.2724745Z (node:2100) [DEP0040] DeprecationWarning: The `punycode` module is deprecated. Please use a userland alternative instead.
2026-08-17T01:47:51.2726484Z (Use `node --trace-deprecation ...` to show where the warning was created)
2026-08-17T01:47:51.2727932Z Creating toolchains.xml for JDK version 17 from temurin
2026-08-17T01:47:51.2793484Z Writing to /home/runner/.m2/toolchains.xml
2026-08-17T01:47:51.2793990Z 
2026-08-17T01:47:51.2794163Z Java configuration:
2026-08-17T01:47:51.2794734Z   Distribution: temurin
2026-08-17T01:47:51.2795257Z   Version: 17.0.20+8
2026-08-17T01:47:51.2795860Z   Path: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T01:47:51.2796269Z 
2026-08-17T01:47:51.2796982Z ##[endgroup]
2026-08-17T01:47:51.2816797Z Creating settings.xml with server-id: github
2026-08-17T01:47:51.2817395Z Writing to /home/runner/.m2/settings.xml
2026-08-17T01:47:51.3180906Z Node 20 is being deprecated. This workflow is running with Node 24 by default. If you need to temporarily use Node 20, you can set the ACTIONS_ALLOW_USE_UNSECURE_NODE_VERSION=true environment variable. For more information see: https://github.blog/changelog/2025-09-19-deprecation-of-node-20-on-github-actions-runners/
2026-08-17T01:47:51.3184002Z ##[group]Run gradle/actions/setup-gradle@v4
2026-08-17T01:47:51.3184685Z with:
2026-08-17T01:47:51.3185148Z   gradle-version: 8.5
2026-08-17T01:47:51.3185588Z   cache-read-only: false
2026-08-17T01:47:51.3186052Z   validate-wrappers: false
2026-08-17T01:47:51.3186489Z   cache-disabled: false
2026-08-17T01:47:51.3186895Z   cache-write-only: false
2026-08-17T01:47:51.3187375Z   cache-overwrite-existing: false
2026-08-17T01:47:51.3187826Z   cache-cleanup: on-success
2026-08-17T01:47:51.3188355Z   gradle-home-cache-includes: caches
notifications

2026-08-17T01:47:51.3188925Z   add-job-summary: always
2026-08-17T01:47:51.3189515Z   add-job-summary-as-pr-comment: never
2026-08-17T01:47:51.3190095Z   dependency-graph: disabled
2026-08-17T01:47:51.3190639Z   dependency-graph-report-dir: dependency-graph-reports
2026-08-17T01:47:51.3191407Z   dependency-graph-continue-on-failure: true
2026-08-17T01:47:51.3191954Z   build-scan-publish: false
2026-08-17T01:47:51.3192600Z   allow-snapshot-wrappers: false
2026-08-17T01:47:51.3193164Z   gradle-home-cache-strict-match: false
2026-08-17T01:47:51.3193672Z   workflow-job-context: null
2026-08-17T01:47:51.3196917Z   github-token: ***
2026-08-17T01:47:51.3197249Z env:
2026-08-17T01:47:51.3197592Z   GRADLE_VERSION: 8.5
2026-08-17T01:47:51.3198037Z   JAVA_VERSION: 17
2026-08-17T01:47:51.3198469Z   JAVA_HOME: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T01:47:51.3199111Z   JAVA_HOME_17_X64: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T01:47:51.3199574Z ##[endgroup]
2026-08-17T01:47:52.8651811Z Merged default JDK locations into /home/runner/.m2/toolchains.xml
2026-08-17T01:47:52.8654143Z Preparing cache for cleanup.
2026-08-17T01:47:52.8657657Z ##[group]Restore Gradle state from cache
2026-08-17T01:47:53.0800530Z Cache hit for restore-key: gradle-home-v1|Linux-X64|build[266babc85e2a7f6e4c23c8d6be839361]-e2a29d9c64614040e9d9580d96098419c53b7444
2026-08-17T01:47:54.3436719Z Received 25165824 of 143657121 (17.5%), 24.0 MBs/sec
2026-08-17T01:47:55.3092452Z Received 143657121 of 143657121 (100.0%), 69.7 MBs/sec
2026-08-17T01:47:55.3093724Z Cache Size: ~137 MB (143657121 B)
2026-08-17T01:47:55.3128868Z [command]/usr/bin/tar -xf /home/runner/work/_temp/7dd62798-d16e-44ff-bc0d-bc9067457a99/cache.tzst -P -C /home/runner/work/AutoBOT/AutoBOT --use-compress-program unzstd
2026-08-17T01:47:55.9329701Z Cache restored successfully
2026-08-17T01:47:55.9403944Z Restored cache entry with key gradle-home-v1|Linux-X64|build[266babc85e2a7f6e4c23c8d6be839361]-11a37562b6a2eb855584b2d8092f1232349873c3 to /home/runner/.gradle/caches,/home/runner/.gradle/notifications,/home/runner/.gradle/.setup-gradle in 3073ms
2026-08-17T01:47:56.1629790Z Cache hit for: gradle-kotlin-dsl-v1-86903c45d6b8a8330f048b9beae0c1ea
2026-08-17T01:47:56.1644091Z Cache hit for: gradle-wrapper-zips-v1-e89a30cff1b7b918cfe1273c9c8e4a34
2026-08-17T01:47:56.1648050Z Cache hit for: gradle-groovy-dsl-v1-150600ffcaa7fbb3198c872a084c1a2f
2026-08-17T01:47:56.1723508Z Cache hit for: gradle-instrumented-jars-v1-caf4045168917df53ac1e3736974fe3a
2026-08-17T01:47:56.1726991Z Cache hit for: gradle-dependencies-v1-ca33a97c11bd8dec625e8d54280f9120
2026-08-17T01:47:56.1758983Z Cache hit for: gradle-generated-gradle-jars-v1-fa001ab82c3596b4e27ec78f191b889f
2026-08-17T01:47:56.6947826Z Received 98340 of 98340 (100.0%), 0.3 MBs/sec
2026-08-17T01:47:56.6948596Z Cache Size: ~0 MB (98340 B)
2026-08-17T01:47:56.6974257Z [command]/usr/bin/tar -xf /home/runner/work/_temp/f420bfb7-d028-49ac-8898-b3a40caba6d3/cache.tzst -P -C /home/runner/work/AutoBOT/AutoBOT --use-compress-program unzstd
2026-08-17T01:47:56.7196201Z Cache restored successfully
2026-08-17T01:47:56.7198518Z Restored cache entry with key gradle-kotlin-dsl-v1-86903c45d6b8a8330f048b9beae0c1ea to /home/runner/.gradle/caches/*/kotlin-dsl/accessors/*/,/home/runner/.gradle/caches/*/kotlin-dsl/scripts/*/ in 777ms
2026-08-17T01:47:56.7411608Z Received 109241 of 109241 (100.0%), 0.3 MBs/sec
2026-08-17T01:47:56.7412300Z Cache Size: ~0 MB (109241 B)
2026-08-17T01:47:56.7432968Z [command]/usr/bin/tar -xf /home/runner/work/_temp/98f67d5a-34c5-4184-876d-6d4990a1b269/cache.tzst -P -C /home/runner/work/AutoBOT/AutoBOT --use-compress-program unzstd
2026-08-17T01:47:56.7531504Z Cache restored successfully
2026-08-17T01:47:56.7533106Z Restored cache entry with key gradle-groovy-dsl-v1-150600ffcaa7fbb3198c872a084c1a2f to /home/runner/.gradle/caches/*/groovy-dsl/*/ in 811ms
2026-08-17T01:47:57.0663790Z Received 36784583 of 36784583 (100.0%), 42.6 MBs/sec
2026-08-17T01:47:57.0664634Z Cache Size: ~35 MB (36784583 B)
2026-08-17T01:47:57.0837108Z [command]/usr/bin/tar -xf /home/runner/work/_temp/a64eeead-efe2-4f8b-841b-9269143a1b17/cache.tzst -P -C /home/runner/work/AutoBOT/AutoBOT --use-compress-program unzstd
2026-08-17T01:47:57.3275335Z Cache restored successfully
2026-08-17T01:47:57.3290000Z Restored cache entry with key gradle-generated-gradle-jars-v1-fa001ab82c3596b4e27ec78f191b889f to /home/runner/.gradle/caches/8.5/generated-gradle-jars/gradle-api-8.5.jar in 1388ms
2026-08-17T01:47:57.4046432Z Received 29360128 of 328896045 (8.9%), 28.0 MBs/sec
2026-08-17T01:47:57.4195998Z Received 8388608 of 89747557 (9.3%), 8.0 MBs/sec
2026-08-17T01:47:57.4343145Z Received 12582912 of 131966939 (9.5%), 12.0 MBs/sec
2026-08-17T01:47:58.0303025Z Received 89747557 of 89747557 (100.0%), 53.2 MBs/sec
2026-08-17T01:47:58.0304569Z Cache Size: ~86 MB (89747557 B)
2026-08-17T01:47:58.0665978Z [command]/usr/bin/tar -xf /home/runner/work/_temp/f32dfaa8-9af1-452c-a2dd-463dbf4914c6/cache.tzst -P -C /home/runner/work/AutoBOT/AutoBOT --use-compress-program unzstd
2026-08-17T01:47:58.4224639Z Received 131966939 of 131966939 (100.0%), 63.3 MBs/sec
2026-08-17T01:47:58.4225718Z Cache Size: ~126 MB (131966939 B)
2026-08-17T01:47:58.4230062Z Received 159383552 of 328896045 (48.5%), 75.3 MBs/sec
2026-08-17T01:47:58.4568964Z [command]/usr/bin/tar -xf /home/runner/work/_temp/f9cf5453-7316-4958-909e-60ea0dc5754e/cache.tzst -P -C /home/runner/work/AutoBOT/AutoBOT --use-compress-program unzstd
2026-08-17T01:47:58.6965089Z Cache restored successfully
2026-08-17T01:47:58.7033924Z Restored cache entry with key gradle-wrapper-zips-v1-e89a30cff1b7b918cfe1273c9c8e4a34 to /home/runner/.gradle/wrapper/dists/gradle-8.5-bin/5t9huq95ubn472n8rpzujfbqh in 2762ms
2026-08-17T01:47:58.8086602Z Cache restored successfully
2026-08-17T01:47:58.8183335Z Restored cache entry with key gradle-instrumented-jars-v1-caf4045168917df53ac1e3736974fe3a to /home/runner/.gradle/caches/jars-*/*/ in 2875ms
2026-08-17T01:47:59.3769171Z Received 328896045 of 328896045 (100.0%), 105.5 MBs/sec
2026-08-17T01:47:59.3771775Z Cache Size: ~314 MB (328896045 B)
2026-08-17T01:47:59.3925895Z [command]/usr/bin/tar -xf /home/runner/work/_temp/2b426189-34bb-487d-b737-33a30ad9631b/cache.tzst -P -C /home/runner/work/AutoBOT/AutoBOT --use-compress-program unzstd
2026-08-17T01:47:59.7265584Z Cache restored successfully
2026-08-17T01:47:59.7384202Z Restored cache entry with key gradle-dependencies-v1-ca33a97c11bd8dec625e8d54280f9120 to /home/runner/.gradle/caches/modules-*/files-*/*/*/*/* in 3796ms
2026-08-17T01:47:59.7894043Z ##[endgroup]
2026-08-17T01:47:59.9038952Z ##[group]Provision Gradle 8.5
2026-08-17T01:48:03.9360822Z Cache hit for: gradle-8.5
2026-08-17T01:48:05.1663984Z Received 29360128 of 132239594 (22.2%), 28.0 MBs/sec
2026-08-17T01:48:05.9402604Z Received 132239594 of 132239594 (100.0%), 71.0 MBs/sec
2026-08-17T01:48:05.9404620Z Cache Size: ~126 MB (132239594 B)
2026-08-17T01:48:05.9480562Z [command]/usr/bin/tar -xf /home/runner/work/_temp/7481f38f-3b6b-4a5b-b004-40f14c8d029d/cache.tzst -P -C /home/runner/work/AutoBOT/AutoBOT --use-compress-program unzstd
2026-08-17T01:48:06.0652454Z Cache restored successfully
2026-08-17T01:48:06.0704523Z Restored Gradle distribution gradle-8.5 from cache to /home/runner/work/_temp/.gradle-actions/gradle-installations/downloads/gradle-8.5-bin.zip
2026-08-17T01:48:06.0719285Z [command]/usr/bin/unzip -o -q /home/runner/work/_temp/.gradle-actions/gradle-installations/downloads/gradle-8.5-bin.zip
2026-08-17T01:48:07.1056906Z Extracted Gradle 8.5 to /home/runner/work/_temp/.gradle-actions/gradle-installations/installs/gradle-8.5
2026-08-17T01:48:07.1058096Z Provisioned Gradle executable /home/runner/work/_temp/.gradle-actions/gradle-installations/installs/gradle-8.5/bin/gradle
2026-08-17T01:48:07.1059430Z ##[endgroup]
2026-08-17T01:48:07.1205772Z ##[group]Run if [ -f "gradle/wrapper/gradle-wrapper.jar" ]; then
2026-08-17T01:48:07.1206545Z [36;1mif [ -f "gradle/wrapper/gradle-wrapper.jar" ]; then[0m
2026-08-17T01:48:07.1207183Z [36;1m  echo "✅ gradle-wrapper.jar already exists, skip generation"[0m
2026-08-17T01:48:07.1207744Z [36;1m  ls -la gradle/wrapper/[0m
2026-08-17T01:48:07.1208159Z [36;1m  exit 0[0m
2026-08-17T01:48:07.1208538Z [36;1mfi[0m
2026-08-17T01:48:07.1208907Z [36;1m[0m
2026-08-17T01:48:07.1209427Z [36;1mecho "⚠️ gradle-wrapper.jar not found. Generating via gradle command..."[0m
2026-08-17T01:48:07.1209999Z [36;1mecho "gradle version: $(gradle --version)"[0m
2026-08-17T01:48:07.1210871Z [36;1mgradle wrapper --gradle-version "$GRADLE_VERSION" --distribution-type bin --no-daemon[0m
2026-08-17T01:48:07.1211723Z [36;1m[0m
2026-08-17T01:48:07.1212174Z [36;1mif [ -f "gradle/wrapper/gradle-wrapper.jar" ]; then[0m
2026-08-17T01:48:07.1212821Z [36;1m  echo "✅ Generated gradle-wrapper.jar successfully:"[0m
2026-08-17T01:48:07.1213337Z [36;1m  ls -la gradle/wrapper/[0m
2026-08-17T01:48:07.1213744Z [36;1melse[0m
2026-08-17T01:48:07.1214177Z [36;1m  echo "❌ Failed to generate gradle-wrapper.jar"[0m
2026-08-17T01:48:07.1214641Z [36;1m  ls -la gradle/ || true[0m
2026-08-17T01:48:07.1215115Z [36;1m  exit 1[0m
2026-08-17T01:48:07.1215491Z [36;1mfi[0m
2026-08-17T01:48:07.1243072Z shell: /usr/bin/bash --noprofile --norc -e -o pipefail {0}
2026-08-17T01:48:07.1243575Z env:
2026-08-17T01:48:07.1243984Z   GRADLE_VERSION: 8.5
2026-08-17T01:48:07.1244392Z   JAVA_VERSION: 17
2026-08-17T01:48:07.1244921Z   JAVA_HOME: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T01:48:07.1245542Z   JAVA_HOME_17_X64: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T01:48:07.1246124Z   GRADLE_ACTION_ID: gradle/actions/setup-gradle
2026-08-17T01:48:07.1246761Z   GRADLE_USER_HOME: /home/runner/.gradle
2026-08-17T01:48:07.1247234Z   GRADLE_BUILD_ACTION_SETUP_COMPLETED: true
2026-08-17T01:48:07.1247756Z   GRADLE_BUILD_ACTION_CACHE_RESTORED: true
2026-08-17T01:48:07.1248332Z   DEVELOCITY_INJECTION_INIT_SCRIPT_NAME: gradle-actions.inject-develocity.init.gradle
2026-08-17T01:48:07.1248953Z   DEVELOCITY_INJECTION_CUSTOM_VALUE: gradle-actions
2026-08-17T01:48:07.1249435Z   GITHUB_DEPENDENCY_GRAPH_ENABLED: false
2026-08-17T01:48:07.1249854Z ##[endgroup]
2026-08-17T01:48:07.2108353Z ⚠️ gradle-wrapper.jar not found. Generating via gradle command...
2026-08-17T01:48:07.7218688Z gradle version: 
2026-08-17T01:48:07.7219585Z ------------------------------------------------------------
2026-08-17T01:48:07.7220492Z Gradle 8.5
2026-08-17T01:48:07.7221331Z ------------------------------------------------------------
2026-08-17T01:48:07.7221911Z 
2026-08-17T01:48:07.7222278Z Build time:   2023-11-29 14:08:57 UTC
2026-08-17T01:48:07.7223058Z Revision:     28aca86a7180baa17117e0e5ba01d8ea9feca598
2026-08-17T01:48:07.7223604Z 
2026-08-17T01:48:07.7223944Z Kotlin:       1.9.20
2026-08-17T01:48:07.7224627Z Groovy:       3.0.17
2026-08-17T01:48:07.7225464Z Ant:          Apache Ant(TM) version 1.10.13 compiled on January 4 2023
2026-08-17T01:48:07.7226310Z JVM:          17.0.20 (Eclipse Adoptium 17.0.20+8)
2026-08-17T01:48:07.7227108Z OS:           Linux 6.17.0-1022-azure amd64
2026-08-17T01:48:08.2657623Z To honour the JVM settings for this build a single-use Daemon process will be forked. For more on this, please refer to https://docs.gradle.org/8.5/userguide/gradle_daemon.html#sec:disabling_the_daemon in the Gradle documentation.
2026-08-17T01:48:09.2673260Z Daemon will be stopped at the end of the build 
2026-08-17T01:48:16.9667678Z 
2026-08-17T01:48:16.9685603Z > Configure project :app
2026-08-17T01:48:16.9689223Z Checking the license for package NDK (Side by side) 25.2.9519653 in /usr/local/lib/android/sdk/licenses
2026-08-17T01:48:17.0672003Z License for package NDK (Side by side) 25.2.9519653 accepted.
2026-08-17T01:48:17.0673312Z Preparing "Install NDK (Side by side) 25.2.9519653 v.25.2.9519653".
2026-08-17T01:48:41.0673819Z "Install NDK (Side by side) 25.2.9519653 v.25.2.9519653" ready.
2026-08-17T01:48:41.0675193Z Installing NDK (Side by side) 25.2.9519653 in /usr/local/lib/android/sdk/ndk/25.2.9519653
2026-08-17T01:48:41.0723020Z "Install NDK (Side by side) 25.2.9519653 v.25.2.9519653" complete.
2026-08-17T01:48:41.1654413Z "Install NDK (Side by side) 25.2.9519653 v.25.2.9519653" finished.
2026-08-17T01:48:42.7665429Z 
2026-08-17T01:48:42.7692816Z > Task :wrapper
2026-08-17T01:48:42.7698358Z gradle/actions: Writing build results to /home/runner/work/_temp/.gradle-actions/build-results/__run-1786931290720.json
2026-08-17T01:48:42.7724576Z 
2026-08-17T01:48:42.7752774Z BUILD SUCCESSFUL in 34s
2026-08-17T01:48:42.7755822Z 1 actionable task: 1 executed
2026-08-17T01:48:43.1172337Z ✅ Generated gradle-wrapper.jar successfully:
2026-08-17T01:48:43.1184978Z total 56
2026-08-17T01:48:43.1185420Z drwxr-xr-x 2 runner runner  4096 Aug 17 01:48 .
2026-08-17T01:48:43.1186011Z drwxr-xr-x 3 runner runner  4096 Aug 17 01:48 ..
2026-08-17T01:48:43.1186554Z -rw-r--r-- 1 runner runner 43462 Aug 17 01:48 gradle-wrapper.jar
2026-08-17T01:48:43.1187418Z -rw-r--r-- 1 runner runner   250 Aug 17 01:48 gradle-wrapper.properties
2026-08-17T01:48:43.1228369Z ##[group]Run chmod +x gradlew
2026-08-17T01:48:43.1228866Z [36;1mchmod +x gradlew[0m
2026-08-17T01:48:43.1253610Z shell: /usr/bin/bash -e {0}
2026-08-17T01:48:43.1254110Z env:
2026-08-17T01:48:43.1254465Z   GRADLE_VERSION: 8.5
2026-08-17T01:48:43.1254923Z   JAVA_VERSION: 17
2026-08-17T01:48:43.1255471Z   JAVA_HOME: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T01:48:43.1256151Z   JAVA_HOME_17_X64: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T01:48:43.1256750Z   GRADLE_ACTION_ID: gradle/actions/setup-gradle
2026-08-17T01:48:43.1257247Z   GRADLE_USER_HOME: /home/runner/.gradle
2026-08-17T01:48:43.1257701Z   GRADLE_BUILD_ACTION_SETUP_COMPLETED: true
2026-08-17T01:48:43.1258172Z   GRADLE_BUILD_ACTION_CACHE_RESTORED: true
2026-08-17T01:48:43.1258814Z   DEVELOCITY_INJECTION_INIT_SCRIPT_NAME: gradle-actions.inject-develocity.init.gradle
2026-08-17T01:48:43.1259475Z   DEVELOCITY_INJECTION_CUSTOM_VALUE: gradle-actions
2026-08-17T01:48:43.1260080Z   GITHUB_DEPENDENCY_GRAPH_ENABLED: false
2026-08-17T01:48:43.1260492Z ##[endgroup]
2026-08-17T01:48:43.1369912Z ##[group]Run android-actions/setup-android@v4
2026-08-17T01:48:43.1370414Z with:
2026-08-17T01:48:43.1370800Z   accept-android-sdk-licenses: true
2026-08-17T01:48:43.1371584Z   log-accepted-android-sdk-licenses: false
2026-08-17T01:48:43.1372101Z   cmdline-tools-version: 14742923
2026-08-17T01:48:43.1372961Z env:
2026-08-17T01:48:43.1373345Z   GRADLE_VERSION: 8.5
2026-08-17T01:48:43.1373810Z   JAVA_VERSION: 17
2026-08-17T01:48:43.1374301Z   JAVA_HOME: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T01:48:43.1374951Z   JAVA_HOME_17_X64: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T01:48:43.1375523Z   GRADLE_ACTION_ID: gradle/actions/setup-gradle
2026-08-17T01:48:43.1376115Z   GRADLE_USER_HOME: /home/runner/.gradle
2026-08-17T01:48:43.1376548Z   GRADLE_BUILD_ACTION_SETUP_COMPLETED: true
2026-08-17T01:48:43.1377030Z   GRADLE_BUILD_ACTION_CACHE_RESTORED: true
2026-08-17T01:48:43.1377777Z   DEVELOCITY_INJECTION_INIT_SCRIPT_NAME: gradle-actions.inject-develocity.init.gradle
2026-08-17T01:48:43.1378401Z   DEVELOCITY_INJECTION_CUSTOM_VALUE: gradle-actions
2026-08-17T01:48:43.1378893Z   GITHUB_DEPENDENCY_GRAPH_ENABLED: false
2026-08-17T01:48:43.1379325Z ##[endgroup]
2026-08-17T01:48:43.2123320Z Found preinstalled sdkmanager in /usr/local/lib/android/sdk/cmdline-tools/latest with following source.properties:
2026-08-17T01:48:43.2124629Z Pkg.Revision=12.0
2026-08-17T01:48:43.2125269Z Pkg.Path=cmdline-tools;12.0
2026-08-17T01:48:43.2125922Z Pkg.Desc=Android SDK Command-line Tools
2026-08-17T01:48:43.2126406Z 
2026-08-17T01:48:43.2126683Z Wrong version in preinstalled sdkmanager
2026-08-17T01:48:43.2127780Z Downloading commandline tools from https://dl.google.com/android/repository/commandlinetools-linux-14742923_latest.zip
2026-08-17T01:48:44.6757428Z [command]/usr/bin/unzip -o -q /home/runner/work/_temp/18aa5067-e4e1-476d-898d-90804ed8e312
2026-08-17T01:48:45.6238375Z Accepting Android SDK licenses
2026-08-17T01:48:47.6853326Z ##[group]Run echo "ANDROID_HOME=$ANDROID_HOME"
2026-08-17T01:48:47.6853880Z [36;1mecho "ANDROID_HOME=$ANDROID_HOME"[0m
2026-08-17T01:48:47.6854404Z [36;1mecho "sdkmanager path: $(which sdkmanager)"[0m
2026-08-17T01:48:47.6854900Z [36;1msdkmanager --install \[0m
2026-08-17T01:48:47.6855367Z [36;1m  "platforms;android-34" \[0m
2026-08-17T01:48:47.6855839Z [36;1m  "build-tools;34.0.0" \[0m
2026-08-17T01:48:47.6856448Z [36;1m  "platform-tools" \[0m
2026-08-17T01:48:47.6856898Z [36;1m  "ndk;25.2.9519653" \[0m
2026-08-17T01:48:47.6857332Z [36;1m  "cmake;3.22.1"[0m
2026-08-17T01:48:47.6857777Z [36;1mecho "✅ SDK components installed"[0m
2026-08-17T01:48:47.6858350Z [36;1msdkmanager --list_installed || sdkmanager --list | head -50[0m
2026-08-17T01:48:47.6883782Z shell: /usr/bin/bash --noprofile --norc -e -o pipefail {0}
2026-08-17T01:48:47.6884408Z env:
2026-08-17T01:48:47.6884796Z   GRADLE_VERSION: 8.5
2026-08-17T01:48:47.6885222Z   JAVA_VERSION: 17
2026-08-17T01:48:47.6885897Z   JAVA_HOME: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T01:48:47.6886556Z   JAVA_HOME_17_X64: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T01:48:47.6887204Z   GRADLE_ACTION_ID: gradle/actions/setup-gradle
2026-08-17T01:48:47.6887695Z   GRADLE_USER_HOME: /home/runner/.gradle
2026-08-17T01:48:47.6888194Z   GRADLE_BUILD_ACTION_SETUP_COMPLETED: true
2026-08-17T01:48:47.6888676Z   GRADLE_BUILD_ACTION_CACHE_RESTORED: true
2026-08-17T01:48:47.6889288Z   DEVELOCITY_INJECTION_INIT_SCRIPT_NAME: gradle-actions.inject-develocity.init.gradle
2026-08-17T01:48:47.6889921Z   DEVELOCITY_INJECTION_CUSTOM_VALUE: gradle-actions
2026-08-17T01:48:47.6890494Z   GITHUB_DEPENDENCY_GRAPH_ENABLED: false
2026-08-17T01:48:47.6890950Z   ANDROID_HOME: /usr/local/lib/android/sdk
2026-08-17T01:48:47.6891689Z   ANDROID_SDK_ROOT: /usr/local/lib/android/sdk
2026-08-17T01:48:47.6892144Z ##[endgroup]
2026-08-17T01:48:47.6941916Z ANDROID_HOME=/usr/local/lib/android/sdk
2026-08-17T01:48:47.6952769Z sdkmanager path: /usr/local/lib/android/sdk/cmdline-tools/20.0/bin/sdkmanager
2026-08-17T01:48:48.5040289Z Loading package information...                                                  
2026-08-17T01:48:48.5978858Z Loading local repository...                                                     
2026-08-17T01:48:48.5980229Z [                                       ] 3% Loading local repository...        
2026-08-17T01:48:48.6074493Z [                                       ] 3% Fetch remote repository...         
2026-08-17T01:48:48.8754141Z [=                                      ] 3% Fetch remote repository...         
2026-08-17T01:48:48.9926640Z [=                                      ] 4% Fetch remote repository...         
2026-08-17T01:48:49.0210519Z [=                                      ] 5% Fetch remote repository...         
2026-08-17T01:48:49.0716600Z [==                                     ] 5% Fetch remote repository...         
2026-08-17T01:48:49.1340257Z [==                                     ] 6% Fetch remote repository...         
2026-08-17T01:48:49.2073355Z [==                                     ] 7% Fetch remote repository...         
2026-08-17T01:48:49.2083422Z [==                                     ] 7% Computing updates...               
2026-08-17T01:48:49.2172893Z [===                                    ] 8% Computing updates...               
2026-08-17T01:48:49.2309410Z [===                                    ] 10% Computing updates...              
2026-08-17T01:48:49.5943119Z [===                                    ] 10% Installing CMake 3.22.1           
2026-08-17T01:48:49.6355213Z [===                                    ] 10% Downloading cmake-3.22.1-linux.zip
2026-08-17T01:48:49.6663074Z [====                                   ] 10% Downloading cmake-3.22.1-linux.zip
2026-08-17T01:48:49.6964485Z [====                                   ] 11% Downloading cmake-3.22.1-linux.zip
2026-08-17T01:48:49.7172743Z [====                                   ] 12% Downloading cmake-3.22.1-linux.zip
2026-08-17T01:48:49.7360664Z [=====                                  ] 13% Downloading cmake-3.22.1-linux.zip
2026-08-17T01:48:49.7539145Z [=====                                  ] 14% Downloading cmake-3.22.1-linux.zip
2026-08-17T01:48:49.7604927Z [=====                                  ] 15% Downloading cmake-3.22.1-linux.zip
2026-08-17T01:48:49.7651269Z [======                                 ] 15% Downloading cmake-3.22.1-linux.zip
2026-08-17T01:48:49.7749115Z [======                                 ] 16% Downloading cmake-3.22.1-linux.zip
2026-08-17T01:48:49.7861457Z [======                                 ] 17% Downloading cmake-3.22.1-linux.zip
2026-08-17T01:48:49.7947781Z [=======                                ] 18% Downloading cmake-3.22.1-linux.zip
2026-08-17T01:48:49.8057419Z [=======                                ] 19% Downloading cmake-3.22.1-linux.zip
2026-08-17T01:48:49.8093434Z [=======                                ] 20% Downloading cmake-3.22.1-linux.zip
2026-08-17T01:48:49.8134811Z [========                               ] 20% Downloading cmake-3.22.1-linux.zip
2026-08-17T01:48:49.8239523Z [========                               ] 21% Downloading cmake-3.22.1-linux.zip
2026-08-17T01:48:49.8316683Z [========                               ] 22% Downloading cmake-3.22.1-linux.zip
2026-08-17T01:48:49.8396070Z [=========                              ] 23% Downloading cmake-3.22.1-linux.zip
2026-08-17T01:48:49.8494100Z [=========                              ] 24% Downloading cmake-3.22.1-linux.zip
2026-08-17T01:48:49.8533667Z [=========                              ] 25% Downloading cmake-3.22.1-linux.zip
2026-08-17T01:48:49.8573001Z [==========                             ] 25% Downloading cmake-3.22.1-linux.zip
2026-08-17T01:48:49.8668627Z [==========                             ] 26% Downloading cmake-3.22.1-linux.zip
2026-08-17T01:48:49.8746314Z [==========                             ] 27% Downloading cmake-3.22.1-linux.zip
2026-08-17T01:48:49.8842941Z [===========                            ] 28% Downloading cmake-3.22.1-linux.zip
2026-08-17T01:48:49.8914263Z [===========                            ] 29% Downloading cmake-3.22.1-linux.zip
2026-08-17T01:48:49.8951726Z [===========                            ] 30% Downloading cmake-3.22.1-linux.zip
2026-08-17T01:48:49.9009778Z [============                           ] 30% Downloading cmake-3.22.1-linux.zip
2026-08-17T01:48:49.9084581Z [============                           ] 31% Downloading cmake-3.22.1-linux.zip
2026-08-17T01:48:49.9167681Z [============                           ] 32% Downloading cmake-3.22.1-linux.zip
2026-08-17T01:48:49.9176189Z [============                           ] 33% Downloading cmake-3.22.1-linux.zip
2026-08-17T01:48:50.0499343Z [============                           ] 33% Unzipping...                      
2026-08-17T01:48:50.0537576Z [============                           ] 33% Unzipping... bin/cmake            
2026-08-17T01:48:50.0735733Z [=============                          ] 33% Unzipping... bin/cmake            
2026-08-17T01:48:50.0910133Z [=============                          ] 34% Unzipping... bin/cmake            
2026-08-17T01:48:50.0999364Z [=============                          ] 35% Unzipping... bin/cmake            
2026-08-17T01:48:50.1126055Z [==============                         ] 35% Unzipping... bin/cmake            
2026-08-17T01:48:50.1318489Z [==============                         ] 36% Unzipping... bin/cmake            
2026-08-17T01:48:50.1478741Z [==============                         ] 37% Unzipping... bin/cmake            
2026-08-17T01:48:50.1624156Z [===============                        ] 38% Unzipping... bin/cmake            
2026-08-17T01:48:50.2282797Z [===============                        ] 39% Unzipping... bin/cmake            
2026-08-17T01:48:50.2432215Z [===============                        ] 39% Unzipping... bin/ctest            
2026-08-17T01:48:50.2526171Z [===============                        ] 40% Unzipping... bin/ctest            
2026-08-17T01:48:50.2628851Z [================                       ] 40% Unzipping... bin/ctest            
2026-08-17T01:48:50.2847217Z [================                       ] 41% Unzipping... bin/ctest            
2026-08-17T01:48:50.3063620Z [================                       ] 42% Unzipping... bin/ctest            
2026-08-17T01:48:50.3229352Z [=================                      ] 43% Unzipping... bin/ctest            
2026-08-17T01:48:50.3400893Z [=================                      ] 44% Unzipping... bin/ctest            
2026-08-17T01:48:50.3492597Z [=================                      ] 45% Unzipping... bin/ctest            
2026-08-17T01:48:50.3580714Z [==================                     ] 45% Unzipping... bin/ctest            
2026-08-17T01:48:50.3605570Z [==================                     ] 46% Unzipping... bin/ctest            
2026-08-17T01:48:50.3800929Z [==================                     ] 46% Unzipping... bin/cpack            
2026-08-17T01:48:50.4007648Z [==================                     ] 47% Unzipping... bin/cpack            
2026-08-17T01:48:50.4203383Z [===================                    ] 48% Unzipping... bin/cpack            
2026-08-17T01:48:50.4376153Z [===================                    ] 49% Unzipping... bin/cpack            
2026-08-17T01:48:50.4456617Z [===================                    ] 50% Unzipping... bin/cpack            
2026-08-17T01:48:50.4517955Z [====================                   ] 50% Unzipping... bin/cpack            
2026-08-17T01:48:50.4654000Z [====================                   ] 51% Unzipping... bin/cpack            
2026-08-17T01:48:50.4743559Z [====================                   ] 52% Unzipping... bin/cpack            
2026-08-17T01:48:50.4750167Z [====================                   ] 52% Unzipping... share/vim/vimfiles/in
2026-08-17T01:48:50.4763883Z [====================                   ] 52% Unzipping... share/vim/vimfiles/sy
2026-08-17T01:48:50.4765453Z [====================                   ] 52% Unzipping... share/aclocal/cmake.m
2026-08-17T01:48:50.4770237Z [====================                   ] 52% Unzipping... share/emacs/site-lisp
2026-08-17T01:48:50.4775013Z [====================                   ] 52% Unzipping... share/cmake-3.22/incl
2026-08-17T01:48:50.6778239Z [====================                   ] 52% Unzipping... share/cmake-3.22/Help
2026-08-17T01:48:50.7355946Z [=====================                  ] 53% Unzipping... share/cmake-3.22/Help
2026-08-17T01:48:50.7425674Z [=====================                  ] 53% Unzipping... share/cmake-3.22/Temp
2026-08-17T01:48:50.7689760Z [=====================                  ] 53% Unzipping... share/cmake-3.22/Modu
2026-08-17T01:48:50.8360655Z [=====================                  ] 54% Unzipping... share/cmake-3.22/Modu
2026-08-17T01:48:50.8363422Z [=====================                  ] 54% Unzipping... share/bash-completion
2026-08-17T01:48:50.8365939Z [=====================                  ] 54% Unzipping... doc/cmake-3.22/Copyri
2026-08-17T01:48:50.8367135Z [=====================                  ] 54% Unzipping... doc/cmake-3.22/cmzlib
2026-08-17T01:48:50.8368384Z [=====================                  ] 54% Unzipping... doc/cmake-3.22/cmzstd
2026-08-17T01:48:50.8369623Z [=====================                  ] 54% Unzipping... doc/cmake-3.22/cmnght
2026-08-17T01:48:50.8370907Z [=====================                  ] 54% Unzipping... doc/cmake-3.22/cmsys/
2026-08-17T01:48:50.8372182Z [=====================                  ] 54% Unzipping... doc/cmake-3.22/cmcurl
2026-08-17T01:48:50.8373458Z [=====================                  ] 54% Unzipping... doc/cmake-3.22/cmlibr
2026-08-17T01:48:50.8374784Z [=====================                  ] 54% Unzipping... doc/cmake-3.22/cmliba
2026-08-17T01:48:50.8376188Z [=====================                  ] 54% Unzipping... doc/cmake-3.22/cmlibl
2026-08-17T01:48:50.8377635Z [=====================                  ] 54% Unzipping... doc/cmake-3.22/cmlibu
2026-08-17T01:48:50.8379637Z [=====================                  ] 54% Unzipping... doc/openssl-1.1.1l/LI
2026-08-17T01:48:50.8386141Z [=====================                  ] 54% Unzipping... source.properties    
2026-08-17T01:48:50.8407165Z [=====================                  ] 54% Unzipping... bin/ninja            
2026-08-17T01:48:50.8409195Z [=====================                  ] 54% Unzipping... doc/ninja/LICENSE    
2026-08-17T01:48:50.8412722Z [=====================                  ] 54% Unzipping... share/cmake-3.22/Modu
2026-08-17T01:48:50.8473938Z [=====================                  ] 55% Unzipping... share/cmake-3.22/Modu
2026-08-17T01:48:50.8492700Z [=======================================] 100% Unzipping... share/cmake-3.22/Mod
2026-08-17T01:48:50.9545274Z 
2026-08-17T01:48:50.9736343Z ✅ SDK components installed
2026-08-17T01:48:51.7346700Z Loading package information...                                                  
2026-08-17T01:48:51.8170221Z Loading local repository...                                                     
2026-08-17T01:48:51.8202003Z [=========                              ] 25% Loading local repository...       
2026-08-17T01:48:51.8202857Z Installed packages:
2026-08-17T01:48:51.8314819Z   Path                               | Version       | Description                      | Location                          
2026-08-17T01:48:51.8325205Z   -------                            | -------       | -------                          | -------                           
2026-08-17T01:48:51.8340064Z   build-tools;34.0.0                 | 34.0.0        | Android SDK Build-Tools 34       | build-tools/34.0.0                
2026-08-17T01:48:51.8344996Z   build-tools;35.0.0                 | 35.0.0        | Android SDK Build-Tools 35       | build-tools/35.0.0                
2026-08-17T01:48:51.8349945Z   build-tools;35.0.1                 | 35.0.1        | Android SDK Build-Tools 35.0.1   | build-tools/35.0.1                
2026-08-17T01:48:51.8359346Z   build-tools;36.0.0                 | 36.0.0        | Android SDK Build-Tools 36       | build-tools/36.0.0                
2026-08-17T01:48:51.8364816Z   build-tools;36.1.0                 | 36.1.0        | Android SDK Build-Tools 36.1     | build-tools/36.1.0                
2026-08-17T01:48:51.8392708Z   build-tools;37.0.0                 | 37.0.0        | Android SDK Build-Tools 37       | build-tools/37.0.0                
2026-08-17T01:48:51.8394109Z   cmake;3.22.1                       | 3.22.1        | CMake 3.22.1                     | cmake/3.22.1                      
2026-08-17T01:48:51.8395573Z   cmake;3.31.5                       | 3.31.5        | CMake 3.31.5                     | cmake/3.31.5                      
2026-08-17T01:48:51.8396834Z   cmake;4.1.2                        | 4.1.2         | CMake 4.1.2                      | cmake/4.1.2                       
2026-08-17T01:48:51.8398187Z   extras;android;m2repository        | 47.0.0        | Android Support Repository       | extras/android/m2repository       
2026-08-17T01:48:51.8399757Z   extras;google;google_play_services | 49            | Google Play services             | extras/google/google_play_services
2026-08-17T01:48:51.8401426Z   extras;google;m2repository         | 58            | Google Repository                | extras/google/m2repository        
2026-08-17T01:48:51.8402921Z   ndk;25.2.9519653                   | 25.2.9519653  | NDK (Side by side) 25.2.9519653  | ndk/25.2.9519653                  
2026-08-17T01:48:51.8404315Z   ndk;27.3.13750724                  | 27.3.13750724 | NDK (Side by side) 27.3.13750724 | ndk/27.3.13750724                 
2026-08-17T01:48:51.8405717Z   ndk;28.2.13676358                  | 28.2.13676358 | NDK (Side by side) 28.2.13676358 | ndk/28.2.13676358                 
2026-08-17T01:48:51.8407058Z   ndk;29.0.14206865                  | 29.0.14206865 | NDK (Side by side) 29.0.14206865 | ndk/29.0.14206865                 
2026-08-17T01:48:51.8409053Z   platform-tools                     | 37.0.1        | Android SDK Platform-Tools       | platform-tools                    
2026-08-17T01:48:51.8414754Z   platforms;android-34               | 3             | Android SDK Platform 34          | platforms/android-34              
2026-08-17T01:48:51.8419404Z   platforms;android-34-ext10         | 1             | Android SDK Platform 34-ext10    | platforms/android-34-ext10        
2026-08-17T01:48:51.8421469Z   platforms;android-34-ext11         | 1             | Android SDK Platform 34-ext11    | platforms/android-34-ext11        
2026-08-17T01:48:51.8423727Z   platforms;android-34-ext12         | 1             | Android SDK Platform 34-ext12    | platforms/android-34-ext12        
2026-08-17T01:48:51.8425473Z   platforms;android-34-ext8          | 1             | Android SDK Platform 34-ext8     | platforms/android-34-ext8         
2026-08-17T01:48:51.8435198Z   platforms;android-35               | 2             | Android SDK Platform 35          | platforms/android-35              
2026-08-17T01:48:51.8436998Z   platforms;android-35-ext14         | 1             | Android SDK Platform 35-ext14    | platforms/android-35-ext14        
2026-08-17T01:48:51.8438919Z   platforms;android-35-ext15         | 1             | Android SDK Platform 35-ext15    | platforms/android-35-ext15        
2026-08-17T01:48:51.8440710Z   platforms;android-36               | 2             | Android SDK Platform 36          | platforms/android-36              
2026-08-17T01:48:51.8442685Z   platforms;android-36-ext18         | 1             | Android SDK Platform 36-ext18    | platforms/android-36-ext18        
2026-08-17T01:48:51.8444479Z   platforms;android-36-ext19         | 1             | Android SDK Platform 36-ext19    | platforms/android-36-ext19        
2026-08-17T01:48:51.8446336Z   platforms;android-36.1             | 1             | Android SDK Platform 36.1        | platforms/android-36.1            
2026-08-17T01:48:51.8447982Z   platforms;android-37.0             | 2             | Android SDK Platform 37.0        | platforms/android-37.0            
2026-08-17T01:48:51.8449565Z   platforms;android-37.1             | 1             | Android SDK Platform 37.1        | platforms/android-37.1            
2026-08-17T01:48:51.8451465Z   platforms;android-37.2-beta1       | 1             | Android SDK Platform 37.2-beta1  | platforms/android-37.2-beta1      
2026-08-17T01:48:51.8453658Z   platforms;android-37.2-beta2       | 2             | Android SDK Platform 37.2-beta2  | platforms/android-37.2-beta2      
2026-08-17T01:48:51.8454659Z 
2026-08-17T01:48:51.8648691Z ##[group]Run if [ -f "gradle/wrapper/gradle-wrapper.jar" ]; then
2026-08-17T01:48:51.8649378Z [36;1mif [ -f "gradle/wrapper/gradle-wrapper.jar" ]; then[0m
2026-08-17T01:48:51.8649988Z [36;1m  ./gradlew assembleDebug --stacktrace --no-daemon[0m
2026-08-17T01:48:51.8650595Z [36;1melse[0m
2026-08-17T01:48:51.8651215Z [36;1m  echo "⚠️ wrapper jar missing, using gradle directly"[0m
2026-08-17T01:48:51.8651847Z [36;1m  gradle assembleDebug --stacktrace --no-daemon[0m
2026-08-17T01:48:51.8652526Z [36;1mfi[0m
2026-08-17T01:48:51.8678275Z shell: /usr/bin/bash --noprofile --norc -e -o pipefail {0}
2026-08-17T01:48:51.8678803Z env:
2026-08-17T01:48:51.8679192Z   GRADLE_VERSION: 8.5
2026-08-17T01:48:51.8679584Z   JAVA_VERSION: 17
2026-08-17T01:48:51.8680095Z   JAVA_HOME: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T01:48:51.8680751Z   JAVA_HOME_17_X64: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T01:48:51.8681731Z   GRADLE_ACTION_ID: gradle/actions/setup-gradle
2026-08-17T01:48:51.8682226Z   GRADLE_USER_HOME: /home/runner/.gradle
2026-08-17T01:48:51.8682779Z   GRADLE_BUILD_ACTION_SETUP_COMPLETED: true
2026-08-17T01:48:51.8683302Z   GRADLE_BUILD_ACTION_CACHE_RESTORED: true
2026-08-17T01:48:51.8683887Z   DEVELOCITY_INJECTION_INIT_SCRIPT_NAME: gradle-actions.inject-develocity.init.gradle
2026-08-17T01:48:51.8684547Z   DEVELOCITY_INJECTION_CUSTOM_VALUE: gradle-actions
2026-08-17T01:48:51.8685037Z   GITHUB_DEPENDENCY_GRAPH_ENABLED: false
2026-08-17T01:48:51.8685544Z   ANDROID_HOME: /usr/local/lib/android/sdk
2026-08-17T01:48:51.8686063Z   ANDROID_SDK_ROOT: /usr/local/lib/android/sdk
2026-08-17T01:48:51.8686540Z ##[endgroup]
2026-08-17T01:48:52.4159322Z To honour the JVM settings for this build a single-use Daemon process will be forked. For more on this, please refer to https://docs.gradle.org/8.5/userguide/gradle_daemon.html#sec:disabling_the_daemon in the Gradle documentation.
2026-08-17T01:48:53.2156066Z Daemon will be stopped at the end of the build 
2026-08-17T01:48:59.8183696Z > Task :app:preBuild UP-TO-DATE
2026-08-17T01:48:59.9141863Z > Task :app:preDebugBuild UP-TO-DATE
2026-08-17T01:48:59.9195974Z > Task :app:mergeDebugNativeDebugMetadata NO-SOURCE
2026-08-17T01:48:59.9213225Z > Task :app:checkKotlinGradlePluginConfigurationErrors
2026-08-17T01:49:00.5155921Z > Task :app:dataBindingMergeDependencyArtifactsDebug
2026-08-17T01:49:00.5163541Z > Task :app:generateDebugResValues
2026-08-17T01:49:00.5166509Z > Task :app:generateDebugResources
2026-08-17T01:49:02.6142424Z > Task :app:packageDebugResources
2026-08-17T01:49:03.3158447Z > Task :app:mapDebugSourceSetPaths
2026-08-17T01:49:03.4152900Z > Task :app:createDebugCompatibleScreenManifests
2026-08-17T01:49:03.4182803Z > Task :app:extractDeepLinksDebug
2026-08-17T01:49:03.5172874Z > Task :app:checkDebugAarMetadata
2026-08-17T01:49:03.5173865Z > Task :app:parseDebugLocalResources
2026-08-17T01:49:03.8150869Z > Task :app:mergeDebugResources
2026-08-17T01:49:03.9154019Z > Task :app:processDebugMainManifest
2026-08-17T01:49:04.2171480Z > Task :app:dataBindingGenBaseClassesDebug
2026-08-17T01:49:04.3142960Z > Task :app:processDebugManifest
2026-08-17T01:49:04.3162796Z > Task :app:javaPreCompileDebug
2026-08-17T01:49:04.3192574Z > Task :app:mergeDebugShaders
2026-08-17T01:49:04.3222449Z > Task :app:compileDebugShaders NO-SOURCE
2026-08-17T01:49:04.3252545Z > Task :app:generateDebugAssets UP-TO-DATE
2026-08-17T01:49:04.4149457Z > Task :app:mergeDebugAssets
2026-08-17T01:49:04.4172914Z > Task :app:compressDebugAssets
2026-08-17T01:49:04.6143080Z > Task :app:desugarDebugFileDependencies
2026-08-17T01:49:04.6144267Z > Task :app:checkDebugDuplicateClasses
2026-08-17T01:49:05.0162203Z 
2026-08-17T01:49:05.0173408Z > Task :app:configureCMakeDebug[arm64-v8a]
2026-08-17T01:49:05.0176080Z [CXX5304] This version only understands SDK XML versions up to 3 but an SDK XML file of version 4 was encountered. This can happen if you use versions of Android Studio and the command-line tools that were released at different times.
2026-08-17T01:49:05.0179490Z [CXX5304] This version only understands SDK XML versions up to 3 but an SDK XML file of version 4 was encountered. This can happen if you use versions of Android Studio and the command-line tools that were released at different times.
2026-08-17T01:49:05.2161877Z 
2026-08-17T01:49:05.2193461Z > Task :app:processDebugManifestForPackage
2026-08-17T01:49:05.2194589Z > Task :app:mergeLibDexDebug
2026-08-17T01:49:05.9159786Z > Task :app:buildCMakeDebug[arm64-v8a]
2026-08-17T01:49:06.1162923Z > Task :app:configureCMakeDebug[x86_64]
2026-08-17T01:49:06.5182850Z > Task :app:processDebugResources
2026-08-17T01:49:06.6153165Z > Task :app:buildCMakeDebug[x86_64]
2026-08-17T01:49:07.5202785Z > Task :app:mergeDebugJniLibFolders
2026-08-17T01:49:07.9173022Z > Task :app:mergeDebugNativeLibs
2026-08-17T01:49:10.1194568Z > Task :app:validateSigningDebug
2026-08-17T01:49:10.2162635Z > Task :app:writeDebugAppMetadata
2026-08-17T01:49:10.2202989Z > Task :app:writeDebugSigningConfigVersions
2026-08-17T01:49:10.3185638Z > Task :app:stripDebugDebugSymbols
2026-08-17T01:49:19.1162833Z > Task :app:mergeExtDexDebug
2026-08-17T01:49:25.3140095Z 
2026-08-17T01:49:25.3193970Z e: file:///home/runner/work/AutoBOT/AutoBOT/app/src/main/java/com/autobot/app/ui/tasks/TasksScreen.kt:196:57 Unresolved reference: ScreenRotation
2026-08-17T01:49:25.3195403Z > Task :app:compileDebugKotlin FAILED
2026-08-17T01:49:25.4176548Z gradle/actions: Writing build results to /home/runner/work/_temp/.gradle-actions/build-results/__run_4-1786931334660.json
2026-08-17T01:49:25.4211742Z 
2026-08-17T01:49:25.4292702Z FAILURE: Build failed with an exception.
2026-08-17T01:49:25.4381680Z 
2026-08-17T01:49:25.4382808Z 34 actionable tasks: 34 executed
2026-08-17T01:49:25.4412730Z * What went wrong:
2026-08-17T01:49:25.4442670Z Execution failed for task ':app:compileDebugKotlin'.
2026-08-17T01:49:25.4473340Z > A failure occurred while executing org.jetbrains.kotlin.compilerRunner.GradleCompilerRunnerWithWorkers$GradleKotlinCompilerWorkAction
2026-08-17T01:49:25.4502325Z    > Compilation error. See log for more details
2026-08-17T01:49:25.4531605Z 
2026-08-17T01:49:25.4561926Z * Try:
2026-08-17T01:49:25.4592311Z > Run with --info or --debug option to get more log output.
2026-08-17T01:49:25.4622066Z > Run with --scan to get full insights.
2026-08-17T01:49:25.4632273Z > Get more help at https://help.gradle.org.
2026-08-17T01:49:25.4651451Z 
2026-08-17T01:49:25.4671897Z * Exception is:
2026-08-17T01:49:25.4693229Z org.gradle.api.tasks.TaskExecutionException: Execution failed for task ':app:compileDebugKotlin'.
2026-08-17T01:49:25.4695283Z 	at org.gradle.api.internal.tasks.execution.ExecuteActionsTaskExecuter.lambda$executeIfValid$1(ExecuteActionsTaskExecuter.java:148)
2026-08-17T01:49:25.4697124Z 	at org.gradle.internal.Try$Failure.ifSuccessfulOrElse(Try.java:282)
2026-08-17T01:49:25.4698761Z 	at org.gradle.api.internal.tasks.execution.ExecuteActionsTaskExecuter.executeIfValid(ExecuteActionsTaskExecuter.java:146)
2026-08-17T01:49:25.4700838Z 	at org.gradle.api.internal.tasks.execution.ExecuteActionsTaskExecuter.execute(ExecuteActionsTaskExecuter.java:134)
2026-08-17T01:49:25.4703164Z 	at org.gradle.api.internal.tasks.execution.FinalizePropertiesTaskExecuter.execute(FinalizePropertiesTaskExecuter.java:46)
2026-08-17T01:49:25.4705074Z 	at org.gradle.api.internal.tasks.execution.ResolveTaskExecutionModeExecuter.execute(ResolveTaskExecutionModeExecuter.java:51)
2026-08-17T01:49:25.4707155Z 	at org.gradle.api.internal.tasks.execution.SkipTaskWithNoActionsExecuter.execute(SkipTaskWithNoActionsExecuter.java:57)
2026-08-17T01:49:25.4709113Z 	at org.gradle.api.internal.tasks.execution.SkipOnlyIfTaskExecuter.execute(SkipOnlyIfTaskExecuter.java:74)
2026-08-17T01:49:25.4711056Z 	at org.gradle.api.internal.tasks.execution.CatchExceptionTaskExecuter.execute(CatchExceptionTaskExecuter.java:36)
2026-08-17T01:49:25.4713159Z 	at org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter$1.executeTask(EventFiringTaskExecuter.java:77)
2026-08-17T01:49:25.4715437Z 	at org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter$1.call(EventFiringTaskExecuter.java:55)
2026-08-17T01:49:25.4717232Z 	at org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter$1.call(EventFiringTaskExecuter.java:52)
2026-08-17T01:49:25.4719268Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$CallableBuildOperationWorker.execute(DefaultBuildOperationRunner.java:204)
2026-08-17T01:49:25.4721521Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$CallableBuildOperationWorker.execute(DefaultBuildOperationRunner.java:199)
2026-08-17T01:49:25.4723594Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$2.execute(DefaultBuildOperationRunner.java:66)
2026-08-17T01:49:25.4889937Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$2.execute(DefaultBuildOperationRunner.java:59)
2026-08-17T01:49:25.4891987Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:157)
2026-08-17T01:49:25.4893831Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:59)
2026-08-17T01:49:25.4895753Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.call(DefaultBuildOperationRunner.java:53)
2026-08-17T01:49:25.4897481Z 	at org.gradle.internal.operations.DefaultBuildOperationExecutor.call(DefaultBuildOperationExecutor.java:73)
2026-08-17T01:49:25.4899185Z 	at org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter.execute(EventFiringTaskExecuter.java:52)
2026-08-17T01:49:25.4900757Z 	at org.gradle.execution.plan.LocalTaskNodeExecutor.execute(LocalTaskNodeExecutor.java:42)
2026-08-17T01:49:25.4902782Z 	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$InvokeNodeExecutorsAction.execute(DefaultTaskExecutionGraph.java:331)
2026-08-17T01:49:25.4904793Z 	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$InvokeNodeExecutorsAction.execute(DefaultTaskExecutionGraph.java:318)
2026-08-17T01:49:25.4907293Z 	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$BuildOperationAwareExecutionAction.lambda$execute$0(DefaultTaskExecutionGraph.java:314)
2026-08-17T01:49:25.4909144Z 	at org.gradle.internal.operations.CurrentBuildOperationRef.with(CurrentBuildOperationRef.java:80)
2026-08-17T01:49:25.4910986Z 	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$BuildOperationAwareExecutionAction.execute(DefaultTaskExecutionGraph.java:314)
2026-08-17T01:49:25.4913268Z 	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$BuildOperationAwareExecutionAction.execute(DefaultTaskExecutionGraph.java:303)
2026-08-17T01:49:25.4915068Z 	at org.gradle.execution.plan.DefaultPlanExecutor$ExecutorWorker.execute(DefaultPlanExecutor.java:463)
2026-08-17T01:49:25.4916566Z 	at org.gradle.execution.plan.DefaultPlanExecutor$ExecutorWorker.run(DefaultPlanExecutor.java:380)
2026-08-17T01:49:25.4918181Z 	at org.gradle.internal.concurrent.ExecutorPolicy$CatchAndRecordFailures.onExecute(ExecutorPolicy.java:64)
2026-08-17T01:49:25.4919758Z 	at org.gradle.internal.concurrent.AbstractManagedExecutor$1.run(AbstractManagedExecutor.java:47)
2026-08-17T01:49:25.4922337Z Caused by: org.gradle.workers.internal.DefaultWorkerExecutor$WorkExecutionException: A failure occurred while executing org.jetbrains.kotlin.compilerRunner.GradleCompilerRunnerWithWorkers$GradleKotlinCompilerWorkAction
2026-08-17T01:49:25.4924557Z 	at org.gradle.workers.internal.DefaultWorkerExecutor$WorkItemExecution.waitForCompletion(DefaultWorkerExecutor.java:283)
2026-08-17T01:49:25.4926250Z 	at org.gradle.internal.work.DefaultAsyncWorkTracker.lambda$waitForItemsAndGatherFailures$2(DefaultAsyncWorkTracker.java:130)
2026-08-17T01:49:25.4927460Z 	at org.gradle.internal.Factories$1.create(Factories.java:31)
2026-08-17T01:49:25.4928558Z 	at org.gradle.internal.work.DefaultWorkerLeaseService.withoutLocks(DefaultWorkerLeaseService.java:336)
2026-08-17T01:49:25.4929975Z 	at org.gradle.internal.work.DefaultWorkerLeaseService.withoutLocks(DefaultWorkerLeaseService.java:319)
2026-08-17T01:49:25.4931837Z 	at org.gradle.internal.work.DefaultWorkerLeaseService.withoutLock(DefaultWorkerLeaseService.java:324)
2026-08-17T01:49:25.4935803Z 	at org.gradle.internal.work.DefaultAsyncWorkTracker.waitForItemsAndGatherFailures(DefaultAsyncWorkTracker.java:126)
2026-08-17T01:49:25.4940191Z 	at org.gradle.internal.work.DefaultAsyncWorkTracker.waitForItemsAndGatherFailures(DefaultAsyncWorkTracker.java:92)
2026-08-17T01:49:25.4942018Z 	at org.gradle.internal.work.DefaultAsyncWorkTracker.waitForAll(DefaultAsyncWorkTracker.java:78)
2026-08-17T01:49:25.4943551Z 	at org.gradle.internal.work.DefaultAsyncWorkTracker.waitForCompletion(DefaultAsyncWorkTracker.java:66)
2026-08-17T01:49:25.4944996Z 	at org.gradle.api.internal.tasks.execution.TaskExecution$3.run(TaskExecution.java:256)
2026-08-17T01:49:25.4946411Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$1.execute(DefaultBuildOperationRunner.java:29)
2026-08-17T01:49:25.4948045Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$1.execute(DefaultBuildOperationRunner.java:26)
2026-08-17T01:49:25.4949680Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$2.execute(DefaultBuildOperationRunner.java:66)
2026-08-17T01:49:25.4951412Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$2.execute(DefaultBuildOperationRunner.java:59)
2026-08-17T01:49:25.4953882Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:157)
2026-08-17T01:49:25.4955549Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:59)
2026-08-17T01:49:25.4957245Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.run(DefaultBuildOperationRunner.java:47)
2026-08-17T01:49:25.4958964Z 	at org.gradle.internal.operations.DefaultBuildOperationExecutor.run(DefaultBuildOperationExecutor.java:68)
2026-08-17T01:49:25.4960481Z 	at org.gradle.api.internal.tasks.execution.TaskExecution.executeAction(TaskExecution.java:233)
2026-08-17T01:49:25.4962485Z 	at org.gradle.api.internal.tasks.execution.TaskExecution.executeActions(TaskExecution.java:216)
2026-08-17T01:49:25.4964088Z 	at org.gradle.api.internal.tasks.execution.TaskExecution.executeWithPreviousOutputFiles(TaskExecution.java:199)
2026-08-17T01:49:25.4965586Z 	at org.gradle.api.internal.tasks.execution.TaskExecution.execute(TaskExecution.java:166)
2026-08-17T01:49:25.4966932Z 	at org.gradle.internal.execution.steps.ExecuteStep.executeInternal(ExecuteStep.java:105)
2026-08-17T01:49:25.4968171Z 	at org.gradle.internal.execution.steps.ExecuteStep.access$000(ExecuteStep.java:44)
2026-08-17T01:49:25.4969349Z 	at org.gradle.internal.execution.steps.ExecuteStep$1.call(ExecuteStep.java:59)
2026-08-17T01:49:25.4970500Z 	at org.gradle.internal.execution.steps.ExecuteStep$1.call(ExecuteStep.java:56)
2026-08-17T01:49:25.4972195Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$CallableBuildOperationWorker.execute(DefaultBuildOperationRunner.java:204)
2026-08-17T01:49:25.4974195Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$CallableBuildOperationWorker.execute(DefaultBuildOperationRunner.java:199)
2026-08-17T01:49:25.4975844Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$2.execute(DefaultBuildOperationRunner.java:66)
2026-08-17T01:49:25.4977232Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$2.execute(DefaultBuildOperationRunner.java:59)
2026-08-17T01:49:25.4978865Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:157)
2026-08-17T01:49:25.4980451Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:59)
2026-08-17T01:49:25.4982724Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.call(DefaultBuildOperationRunner.java:53)
2026-08-17T01:49:25.4984367Z 	at org.gradle.internal.operations.DefaultBuildOperationExecutor.call(DefaultBuildOperationExecutor.java:73)
2026-08-17T01:49:25.4985939Z 	at org.gradle.internal.execution.steps.ExecuteStep.execute(ExecuteStep.java:56)
2026-08-17T01:49:25.4987050Z 	at org.gradle.internal.execution.steps.ExecuteStep.execute(ExecuteStep.java:44)
2026-08-17T01:49:25.4988332Z 	at org.gradle.internal.execution.steps.RemovePreviousOutputsStep.execute(RemovePreviousOutputsStep.java:67)
2026-08-17T01:49:25.4989937Z 	at org.gradle.internal.execution.steps.RemovePreviousOutputsStep.execute(RemovePreviousOutputsStep.java:37)
2026-08-17T01:49:25.4991580Z 	at org.gradle.internal.execution.steps.CancelExecutionStep.execute(CancelExecutionStep.java:41)
2026-08-17T01:49:25.4993056Z 	at org.gradle.internal.execution.steps.TimeoutStep.executeWithoutTimeout(TimeoutStep.java:74)
2026-08-17T01:49:25.4994353Z 	at org.gradle.internal.execution.steps.TimeoutStep.execute(TimeoutStep.java:55)
2026-08-17T01:49:25.4995629Z 	at org.gradle.internal.execution.steps.CreateOutputsStep.execute(CreateOutputsStep.java:50)
2026-08-17T01:49:25.4996962Z 	at org.gradle.internal.execution.steps.CreateOutputsStep.execute(CreateOutputsStep.java:28)
2026-08-17T01:49:25.4998869Z 	at org.gradle.internal.execution.steps.CaptureStateAfterExecutionStep.executeDelegateBroadcastingChanges(CaptureStateAfterExecutionStep.java:100)
2026-08-17T01:49:25.5000904Z 	at org.gradle.internal.execution.steps.CaptureStateAfterExecutionStep.execute(CaptureStateAfterExecutionStep.java:72)
2026-08-17T01:49:25.5002842Z 	at org.gradle.internal.execution.steps.CaptureStateAfterExecutionStep.execute(CaptureStateAfterExecutionStep.java:50)
2026-08-17T01:49:25.5004495Z 	at org.gradle.internal.execution.steps.ResolveInputChangesStep.execute(ResolveInputChangesStep.java:40)
2026-08-17T01:49:25.5006060Z 	at org.gradle.internal.execution.steps.ResolveInputChangesStep.execute(ResolveInputChangesStep.java:29)
2026-08-17T01:49:25.5007620Z 	at org.gradle.internal.execution.steps.BuildCacheStep.executeWithoutCache(BuildCacheStep.java:179)
2026-08-17T01:49:25.5009101Z 	at org.gradle.internal.execution.steps.BuildCacheStep.lambda$execute$1(BuildCacheStep.java:70)
2026-08-17T01:49:25.5010428Z 	at org.gradle.internal.Either$Right.fold(Either.java:175)
2026-08-17T01:49:25.5011831Z 	at org.gradle.internal.execution.caching.CachingState.fold(CachingState.java:59)
2026-08-17T01:49:25.5013135Z 	at org.gradle.internal.execution.steps.BuildCacheStep.execute(BuildCacheStep.java:68)
2026-08-17T01:49:25.5014470Z 	at org.gradle.internal.execution.steps.BuildCacheStep.execute(BuildCacheStep.java:46)
2026-08-17T01:49:25.5015884Z 	at org.gradle.internal.execution.steps.StoreExecutionStateStep.execute(StoreExecutionStateStep.java:36)
2026-08-17T01:49:25.5017332Z 	at org.gradle.internal.execution.steps.StoreExecutionStateStep.execute(StoreExecutionStateStep.java:25)
2026-08-17T01:49:25.5018816Z 	at org.gradle.internal.execution.steps.RecordOutputsStep.execute(RecordOutputsStep.java:36)
2026-08-17T01:49:25.5020165Z 	at org.gradle.internal.execution.steps.RecordOutputsStep.execute(RecordOutputsStep.java:22)
2026-08-17T01:49:25.5021619Z 	at org.gradle.internal.execution.steps.SkipUpToDateStep.executeBecause(SkipUpToDateStep.java:91)
2026-08-17T01:49:25.5023031Z 	at org.gradle.internal.execution.steps.SkipUpToDateStep.lambda$execute$2(SkipUpToDateStep.java:55)
2026-08-17T01:49:25.5024365Z 	at org.gradle.internal.execution.steps.SkipUpToDateStep.execute(SkipUpToDateStep.java:55)
2026-08-17T01:49:25.5025610Z 	at org.gradle.internal.execution.steps.SkipUpToDateStep.execute(SkipUpToDateStep.java:37)
2026-08-17T01:49:25.5026854Z 	at org.gradle.internal.execution.steps.ResolveChangesStep.execute(ResolveChangesStep.java:65)
2026-08-17T01:49:25.5028027Z 	at org.gradle.internal.execution.steps.ResolveChangesStep.execute(ResolveChangesStep.java:36)
2026-08-17T01:49:25.5029583Z 	at org.gradle.internal.execution.steps.legacy.MarkSnapshottingInputsFinishedStep.execute(MarkSnapshottingInputsFinishedStep.java:37)
2026-08-17T01:49:25.5031450Z 	at org.gradle.internal.execution.steps.legacy.MarkSnapshottingInputsFinishedStep.execute(MarkSnapshottingInputsFinishedStep.java:27)
2026-08-17T01:49:25.5033183Z 	at org.gradle.internal.execution.steps.ResolveCachingStateStep.execute(ResolveCachingStateStep.java:76)
2026-08-17T01:49:25.5034651Z 	at org.gradle.internal.execution.steps.ResolveCachingStateStep.execute(ResolveCachingStateStep.java:37)
2026-08-17T01:49:25.5035911Z 	at org.gradle.internal.execution.steps.ValidateStep.execute(ValidateStep.java:108)
2026-08-17T01:49:25.5037122Z 	at org.gradle.internal.execution.steps.ValidateStep.execute(ValidateStep.java:55)
2026-08-17T01:49:25.5038593Z 	at org.gradle.internal.execution.steps.CaptureStateBeforeExecutionStep.execute(CaptureStateBeforeExecutionStep.java:71)
2026-08-17T01:49:25.5040322Z 	at org.gradle.internal.execution.steps.CaptureStateBeforeExecutionStep.execute(CaptureStateBeforeExecutionStep.java:45)
2026-08-17T01:49:25.5042281Z 	at org.gradle.internal.execution.steps.SkipEmptyWorkStep.executeWithNonEmptySources(SkipEmptyWorkStep.java:177)
2026-08-17T01:49:25.5043709Z 	at org.gradle.internal.execution.steps.SkipEmptyWorkStep.execute(SkipEmptyWorkStep.java:86)
2026-08-17T01:49:25.5044955Z 	at org.gradle.internal.execution.steps.SkipEmptyWorkStep.execute(SkipEmptyWorkStep.java:53)
2026-08-17T01:49:25.5046656Z 	at org.gradle.internal.execution.steps.RemoveUntrackedExecutionStateStep.execute(RemoveUntrackedExecutionStateStep.java:32)
2026-08-17T01:49:25.5048513Z 	at org.gradle.internal.execution.steps.RemoveUntrackedExecutionStateStep.execute(RemoveUntrackedExecutionStateStep.java:21)
2026-08-17T01:49:25.5050423Z 	at org.gradle.internal.execution.steps.legacy.MarkSnapshottingInputsStartedStep.execute(MarkSnapshottingInputsStartedStep.java:38)
2026-08-17T01:49:25.5052312Z 	at org.gradle.internal.execution.steps.LoadPreviousExecutionStateStep.execute(LoadPreviousExecutionStateStep.java:36)
2026-08-17T01:49:25.5053919Z 	at org.gradle.internal.execution.steps.LoadPreviousExecutionStateStep.execute(LoadPreviousExecutionStateStep.java:23)
2026-08-17T01:49:25.5055522Z 	at org.gradle.internal.execution.steps.CleanupStaleOutputsStep.execute(CleanupStaleOutputsStep.java:75)
2026-08-17T01:49:25.5057271Z 	at org.gradle.internal.execution.steps.CleanupStaleOutputsStep.execute(CleanupStaleOutputsStep.java:41)
2026-08-17T01:49:25.5060622Z 	at org.gradle.internal.execution.steps.ExecuteWorkBuildOperationFiringStep.lambda$execute$2(ExecuteWorkBuildOperationFiringStep.java:66)
2026-08-17T01:49:25.5062801Z 	at org.gradle.internal.execution.steps.ExecuteWorkBuildOperationFiringStep.execute(ExecuteWorkBuildOperationFiringStep.java:66)
2026-08-17T01:49:25.5064559Z 	at org.gradle.internal.execution.steps.ExecuteWorkBuildOperationFiringStep.execute(ExecuteWorkBuildOperationFiringStep.java:38)
2026-08-17T01:49:25.5066229Z 	at org.gradle.internal.execution.steps.AssignWorkspaceStep.lambda$execute$0(AssignWorkspaceStep.java:32)
2026-08-17T01:49:25.5067533Z 	at org.gradle.api.internal.tasks.execution.TaskExecution$4.withWorkspace(TaskExecution.java:293)
2026-08-17T01:49:25.5068737Z 	at org.gradle.internal.execution.steps.AssignWorkspaceStep.execute(AssignWorkspaceStep.java:30)
2026-08-17T01:49:25.5070122Z 	at org.gradle.internal.execution.steps.AssignWorkspaceStep.execute(AssignWorkspaceStep.java:21)
2026-08-17T01:49:25.5071804Z 	at org.gradle.internal.execution.steps.IdentityCacheStep.execute(IdentityCacheStep.java:37)
2026-08-17T01:49:25.5073000Z 	at org.gradle.internal.execution.steps.IdentityCacheStep.execute(IdentityCacheStep.java:27)
2026-08-17T01:49:25.5075279Z 	at org.gradle.internal.execution.steps.IdentifyStep.execute(IdentifyStep.java:47)
2026-08-17T01:49:25.5076402Z 	at org.gradle.internal.execution.steps.IdentifyStep.execute(IdentifyStep.java:34)
2026-08-17T01:49:25.5077584Z 	at org.gradle.internal.execution.impl.DefaultExecutionEngine$1.execute(DefaultExecutionEngine.java:64)
2026-08-17T01:49:25.5079057Z 	at org.gradle.api.internal.tasks.execution.ExecuteActionsTaskExecuter.executeIfValid(ExecuteActionsTaskExecuter.java:145)
2026-08-17T01:49:25.5080585Z 	at org.gradle.api.internal.tasks.execution.ExecuteActionsTaskExecuter.execute(ExecuteActionsTaskExecuter.java:134)
2026-08-17T01:49:25.5082804Z 	at org.gradle.api.internal.tasks.execution.FinalizePropertiesTaskExecuter.execute(FinalizePropertiesTaskExecuter.java:46)
2026-08-17T01:49:25.5084708Z 	at org.gradle.api.internal.tasks.execution.ResolveTaskExecutionModeExecuter.execute(ResolveTaskExecutionModeExecuter.java:51)
2026-08-17T01:49:25.5086606Z 	at org.gradle.api.internal.tasks.execution.SkipTaskWithNoActionsExecuter.execute(SkipTaskWithNoActionsExecuter.java:57)
2026-08-17T01:49:25.5088345Z 	at org.gradle.api.internal.tasks.execution.SkipOnlyIfTaskExecuter.execute(SkipOnlyIfTaskExecuter.java:74)
2026-08-17T01:49:25.5090000Z 	at org.gradle.api.internal.tasks.execution.CatchExceptionTaskExecuter.execute(CatchExceptionTaskExecuter.java:36)
2026-08-17T01:49:25.5091838Z 	at org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter$1.executeTask(EventFiringTaskExecuter.java:77)
2026-08-17T01:49:25.5093528Z 	at org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter$1.call(EventFiringTaskExecuter.java:55)
2026-08-17T01:49:25.5095129Z 	at org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter$1.call(EventFiringTaskExecuter.java:52)
2026-08-17T01:49:25.5096983Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$CallableBuildOperationWorker.execute(DefaultBuildOperationRunner.java:204)
2026-08-17T01:49:25.5099063Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$CallableBuildOperationWorker.execute(DefaultBuildOperationRunner.java:199)
2026-08-17T01:49:25.5100928Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$2.execute(DefaultBuildOperationRunner.java:66)
2026-08-17T01:49:25.5102714Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$2.execute(DefaultBuildOperationRunner.java:59)
2026-08-17T01:49:25.5104358Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:157)
2026-08-17T01:49:25.5105979Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:59)
2026-08-17T01:49:25.5107855Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.call(DefaultBuildOperationRunner.java:53)
2026-08-17T01:49:25.5109395Z 	at org.gradle.internal.operations.DefaultBuildOperationExecutor.call(DefaultBuildOperationExecutor.java:73)
2026-08-17T01:49:25.5110920Z 	at org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter.execute(EventFiringTaskExecuter.java:52)
2026-08-17T01:49:25.5112473Z 	at org.gradle.execution.plan.LocalTaskNodeExecutor.execute(LocalTaskNodeExecutor.java:42)
2026-08-17T01:49:25.5114018Z 	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$InvokeNodeExecutorsAction.execute(DefaultTaskExecutionGraph.java:331)
2026-08-17T01:49:25.5115645Z 	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$InvokeNodeExecutorsAction.execute(DefaultTaskExecutionGraph.java:318)
2026-08-17T01:49:25.5117504Z 	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$BuildOperationAwareExecutionAction.lambda$execute$0(DefaultTaskExecutionGraph.java:314)
2026-08-17T01:49:25.5119368Z 	at org.gradle.internal.operations.CurrentBuildOperationRef.with(CurrentBuildOperationRef.java:80)
2026-08-17T01:49:25.5121261Z 	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$BuildOperationAwareExecutionAction.execute(DefaultTaskExecutionGraph.java:314)
2026-08-17T01:49:25.5123073Z 	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$BuildOperationAwareExecutionAction.execute(DefaultTaskExecutionGraph.java:303)
2026-08-17T01:49:25.5124865Z 	at org.gradle.execution.plan.DefaultPlanExecutor$ExecutorWorker.execute(DefaultPlanExecutor.java:463)
2026-08-17T01:49:25.5126197Z 	at org.gradle.execution.plan.DefaultPlanExecutor$ExecutorWorker.run(DefaultPlanExecutor.java:380)
2026-08-17T01:49:25.5127580Z 	at org.gradle.internal.concurrent.ExecutorPolicy$CatchAndRecordFailures.onExecute(ExecutorPolicy.java:64)
2026-08-17T01:49:25.5128941Z 	at org.gradle.internal.concurrent.AbstractManagedExecutor$1.run(AbstractManagedExecutor.java:47)
2026-08-17T01:49:25.5130668Z Caused by: org.jetbrains.kotlin.gradle.tasks.CompilationErrorException: Compilation error. See log for more details
2026-08-17T01:49:25.5132573Z 	at org.jetbrains.kotlin.gradle.tasks.TasksUtilsKt.throwExceptionIfCompilationFailed(tasksUtils.kt:20)
2026-08-17T01:49:25.5134024Z 	at org.jetbrains.kotlin.compilerRunner.GradleKotlinCompilerWork.run(GradleKotlinCompilerWork.kt:141)
2026-08-17T01:49:25.5135835Z 	at org.jetbrains.kotlin.compilerRunner.GradleCompilerRunnerWithWorkers$GradleKotlinCompilerWorkAction.execute(GradleCompilerRunnerWithWorkers.kt:73)
2026-08-17T01:49:25.5137358Z 	at org.gradle.workers.internal.DefaultWorkerServer.execute(DefaultWorkerServer.java:63)
2026-08-17T01:49:25.5138648Z 	at org.gradle.workers.internal.NoIsolationWorkerFactory$1$1.create(NoIsolationWorkerFactory.java:66)
2026-08-17T01:49:25.5139946Z 	at org.gradle.workers.internal.NoIsolationWorkerFactory$1$1.create(NoIsolationWorkerFactory.java:62)
2026-08-17T01:49:25.5141519Z 	at org.gradle.internal.classloader.ClassLoaderUtils.executeInClassloader(ClassLoaderUtils.java:100)
2026-08-17T01:49:25.5143047Z 	at org.gradle.workers.internal.NoIsolationWorkerFactory$1.lambda$execute$0(NoIsolationWorkerFactory.java:62)
2026-08-17T01:49:25.5144340Z 	at org.gradle.workers.internal.AbstractWorker$1.call(AbstractWorker.java:44)
2026-08-17T01:49:25.5145406Z 	at org.gradle.workers.internal.AbstractWorker$1.call(AbstractWorker.java:41)
2026-08-17T01:49:25.5146899Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$CallableBuildOperationWorker.execute(DefaultBuildOperationRunner.java:204)
2026-08-17T01:49:25.5148788Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$CallableBuildOperationWorker.execute(DefaultBuildOperationRunner.java:199)
2026-08-17T01:49:25.5150317Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$2.execute(DefaultBuildOperationRunner.java:66)
2026-08-17T01:49:25.5151710Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$2.execute(DefaultBuildOperationRunner.java:59)
2026-08-17T01:49:25.5153066Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:157)
2026-08-17T01:49:25.5154711Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:59)
2026-08-17T01:49:25.5156077Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.call(DefaultBuildOperationRunner.java:53)
2026-08-17T01:49:25.5157536Z 	at org.gradle.internal.operations.DefaultBuildOperationExecutor.call(DefaultBuildOperationExecutor.java:73)
2026-08-17T01:49:25.5158978Z 	at org.gradle.workers.internal.AbstractWorker.executeWrappedInBuildOperation(AbstractWorker.java:41)
2026-08-17T01:49:25.5160382Z 	at org.gradle.workers.internal.NoIsolationWorkerFactory$1.execute(NoIsolationWorkerFactory.java:59)
2026-08-17T01:49:25.5161850Z 	at org.gradle.workers.internal.DefaultWorkerExecutor.lambda$submitWork$0(DefaultWorkerExecutor.java:170)
2026-08-17T01:49:25.5163549Z 	at org.gradle.internal.work.DefaultConditionalExecutionQueue$ExecutionRunner.runExecution(DefaultConditionalExecutionQueue.java:187)
2026-08-17T01:49:25.5165331Z 	at org.gradle.internal.work.DefaultConditionalExecutionQueue$ExecutionRunner.access$700(DefaultConditionalExecutionQueue.java:120)
2026-08-17T01:49:25.5167065Z 	at org.gradle.internal.work.DefaultConditionalExecutionQueue$ExecutionRunner$1.run(DefaultConditionalExecutionQueue.java:162)
2026-08-17T01:49:25.5168316Z 	at org.gradle.internal.Factories$1.create(Factories.java:31)
2026-08-17T01:49:25.5169394Z 	at org.gradle.internal.work.DefaultWorkerLeaseService.withLocks(DefaultWorkerLeaseService.java:264)
2026-08-17T01:49:25.5170786Z 	at org.gradle.internal.work.DefaultWorkerLeaseService.runAsWorkerThread(DefaultWorkerLeaseService.java:128)
2026-08-17T01:49:25.5172408Z 	at org.gradle.internal.work.DefaultWorkerLeaseService.runAsWorkerThread(DefaultWorkerLeaseService.java:133)
2026-08-17T01:49:25.5174004Z 	at org.gradle.internal.work.DefaultConditionalExecutionQueue$ExecutionRunner.runBatch(DefaultConditionalExecutionQueue.java:157)
2026-08-17T01:49:25.5175910Z 	at org.gradle.internal.work.DefaultConditionalExecutionQueue$ExecutionRunner.run(DefaultConditionalExecutionQueue.java:126)
2026-08-17T01:49:25.5177031Z 	... 2 more
2026-08-17T01:49:25.5177345Z 
2026-08-17T01:49:25.5177457Z 
2026-08-17T01:49:25.5177764Z BUILD FAILED in 33s
2026-08-17T01:49:25.9041867Z ##[error]Process completed with exit code 1.
2026-08-17T01:49:25.9106207Z Node 20 is being deprecated. This workflow is running with Node 24 by default. If you need to temporarily use Node 20, you can set the ACTIONS_ALLOW_USE_UNSECURE_NODE_VERSION=true environment variable. For more information see: https://github.blog/changelog/2025-09-19-deprecation-of-node-20-on-github-actions-runners/
2026-08-17T01:49:25.9107347Z ##[group]Run actions/upload-artifact@v4
2026-08-17T01:49:25.9107677Z with:
2026-08-17T01:49:25.9107931Z   name: build-logs
2026-08-17T01:49:25.9108286Z   path: app/build/reports/**
app/build/outputs/logs/**
**/*.log

2026-08-17T01:49:25.9108688Z   if-no-files-found: ignore
2026-08-17T01:49:25.9108999Z   retention-days: 7
2026-08-17T01:49:25.9109273Z   compression-level: 6
2026-08-17T01:49:25.9109548Z   overwrite: false
2026-08-17T01:49:25.9109820Z   include-hidden-files: false
2026-08-17T01:49:25.9110158Z env:
2026-08-17T01:49:25.9110407Z   GRADLE_VERSION: 8.5
2026-08-17T01:49:25.9110704Z   JAVA_VERSION: 17
2026-08-17T01:49:25.9111522Z   JAVA_HOME: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T01:49:25.9112050Z   JAVA_HOME_17_X64: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T01:49:25.9112535Z   GRADLE_ACTION_ID: gradle/actions/setup-gradle
2026-08-17T01:49:25.9112950Z   GRADLE_USER_HOME: /home/runner/.gradle
2026-08-17T01:49:25.9113295Z   GRADLE_BUILD_ACTION_SETUP_COMPLETED: true
2026-08-17T01:49:25.9113640Z   GRADLE_BUILD_ACTION_CACHE_RESTORED: true
2026-08-17T01:49:25.9114130Z   DEVELOCITY_INJECTION_INIT_SCRIPT_NAME: gradle-actions.inject-develocity.init.gradle
2026-08-17T01:49:25.9114713Z   DEVELOCITY_INJECTION_CUSTOM_VALUE: gradle-actions
2026-08-17T01:49:25.9115213Z   GITHUB_DEPENDENCY_GRAPH_ENABLED: false
2026-08-17T01:49:25.9115561Z   ANDROID_HOME: /usr/local/lib/android/sdk
2026-08-17T01:49:25.9115959Z   ANDROID_SDK_ROOT: /usr/local/lib/android/sdk
2026-08-17T01:49:25.9116337Z ##[endgroup]
2026-08-17T01:49:26.0702340Z (node:3004) [DEP0040] DeprecationWarning: The `punycode` module is deprecated. Please use a userland alternative instead.
2026-08-17T01:49:26.0703547Z (Use `node --trace-deprecation ...` to show where the warning was created)
2026-08-17T01:49:26.1964823Z With the provided path, there will be 1 file uploaded
2026-08-17T01:49:26.1970881Z Artifact name is valid!
2026-08-17T01:49:26.1971964Z Root directory input is valid!
2026-08-17T01:49:26.4788042Z Beginning upload of artifact content to blob storage
2026-08-17T01:49:26.4964658Z (node:3004) [DEP0169] DeprecationWarning: `url.parse()` behavior is not standardized and prone to errors that have security implications. Use the WHATWG URL API instead. CVEs are not issued for `url.parse()` vulnerabilities.
2026-08-17T01:49:26.7190553Z Uploaded bytes 8592
2026-08-17T01:49:26.7814691Z Finished uploading artifact content to blob storage!
2026-08-17T01:49:26.7815816Z SHA256 digest of uploaded artifact zip is 71c4384889a5cafa61e1688d67f67d87635e1177fe2f8bafb440b2de5e30cfa2
2026-08-17T01:49:26.7816830Z Finalizing artifact upload
2026-08-17T01:49:27.0042798Z Artifact build-logs.zip successfully finalized. Artifact ID 9273811568
2026-08-17T01:49:27.0043956Z Artifact build-logs has been successfully uploaded! Final size is 8592 bytes. Artifact ID is 9273811568
2026-08-17T01:49:27.0050345Z Artifact download URL: https://github.com/Pikarziur/AutoBOT/actions/runs/31986009623/artifacts/9273811568
2026-08-17T01:49:27.0250421Z Node 20 is being deprecated. This workflow is running with Node 24 by default. If you need to temporarily use Node 20, you can set the ACTIONS_ALLOW_USE_UNSECURE_NODE_VERSION=true environment variable. For more information see: https://github.blog/changelog/2025-09-19-deprecation-of-node-20-on-github-actions-runners/
2026-08-17T01:49:27.0251930Z Post job cleanup.
2026-08-17T01:49:27.2680742Z In post-action step
2026-08-17T01:49:27.2693134Z ##[group]Stopping Gradle daemons
2026-08-17T01:49:27.2694392Z Stopping Gradle daemons for /home/runner/work/_temp/.gradle-actions/gradle-installations/installs/gradle-8.5
2026-08-17T01:49:27.2707653Z Stopping Gradle daemons for /home/runner/.gradle/wrapper/dists/gradle-8.5-bin/5t9huq95ubn472n8rpzujfbqh/gradle-8.5
2026-08-17T01:49:27.2713410Z [command]/home/runner/work/_temp/.gradle-actions/gradle-installations/installs/gradle-8.5/bin/gradle --stop
2026-08-17T01:49:27.2767736Z [command]/home/runner/.gradle/wrapper/dists/gradle-8.5-bin/5t9huq95ubn472n8rpzujfbqh/gradle-8.5/bin/gradle --stop
2026-08-17T01:49:28.5900086Z No Gradle daemons are running.
2026-08-17T01:49:28.6297209Z No Gradle daemons are running.
2026-08-17T01:49:28.6362913Z ##[endgroup]
2026-08-17T01:49:28.6363922Z Not performing cache-cleanup due to build failure
2026-08-17T01:49:28.6365002Z ##[group]Caching Gradle state
2026-08-17T01:49:29.0332803Z [command]/usr/bin/tar --posix -cf cache.tzst --exclude cache.tzst -P -C /home/runner/work/AutoBOT/AutoBOT --files-from manifest.txt --use-compress-program zstdmt
2026-08-17T01:49:31.3402428Z Sent 9428849 of 143646577 (6.6%), 9.0 MBs/sec
2026-08-17T01:49:32.3410582Z Sent 143646577 of 143646577 (100.0%), 68.5 MBs/sec
2026-08-17T01:49:32.6067360Z Saved cache entry with key gradle-home-v1|Linux-X64|build[266babc85e2a7f6e4c23c8d6be839361]-11a37562b6a2eb855584b2d8092f1232349873c3 from /home/runner/.gradle/caches,/home/runner/.gradle/notifications,/home/runner/.gradle/.setup-gradle in 3586ms
2026-08-17T01:49:32.6068570Z ##[endgroup]
2026-08-17T01:49:32.6073324Z Generating Job Summary
2026-08-17T01:49:32.6086490Z Completed post-action step
2026-08-17T01:49:32.6250698Z Node 20 is being deprecated. This workflow is running with Node 24 by default. If you need to temporarily use Node 20, you can set the ACTIONS_ALLOW_USE_UNSECURE_NODE_VERSION=true environment variable. For more information see: https://github.blog/changelog/2025-09-19-deprecation-of-node-20-on-github-actions-runners/
2026-08-17T01:49:32.6252139Z Post job cleanup.
2026-08-17T01:49:32.7632535Z (node:3111) [DEP0040] DeprecationWarning: The `punycode` module is deprecated. Please use a userland alternative instead.
2026-08-17T01:49:32.7633318Z (Use `node --trace-deprecation ...` to show where the warning was created)
2026-08-17T01:49:32.7762539Z Node 20 is being deprecated. This workflow is running with Node 24 by default. If you need to temporarily use Node 20, you can set the ACTIONS_ALLOW_USE_UNSECURE_NODE_VERSION=true environment variable. For more information see: https://github.blog/changelog/2025-09-19-deprecation-of-node-20-on-github-actions-runners/
2026-08-17T01:49:32.7763720Z Post job cleanup.
2026-08-17T01:49:32.8626665Z [command]/usr/bin/git version
2026-08-17T01:49:32.8662699Z git version 2.54.0
2026-08-17T01:49:32.8697074Z Temporarily overriding HOME='/home/runner/work/_temp/9572f80f-da07-4bfd-8faf-9fa113f1db40' before making global git config changes
2026-08-17T01:49:32.8698617Z Adding repository directory to the temporary git global config as a safe directory
2026-08-17T01:49:32.8704032Z [command]/usr/bin/git config --global --add safe.directory /home/runner/work/AutoBOT/AutoBOT
2026-08-17T01:49:32.8740080Z [command]/usr/bin/git config --local --name-only --get-regexp core\.sshCommand
2026-08-17T01:49:32.8772377Z [command]/usr/bin/git submodule foreach --recursive sh -c "git config --local --name-only --get-regexp 'core\.sshCommand' && git config --local --unset-all 'core.sshCommand' || :"
2026-08-17T01:49:32.9004460Z [command]/usr/bin/git config --local --name-only --get-regexp http\.https\:\/\/github\.com\/\.extraheader
2026-08-17T01:49:32.9024939Z http.https://github.com/.extraheader
2026-08-17T01:49:32.9034854Z [command]/usr/bin/git config --local --unset-all http.https://github.com/.extraheader
2026-08-17T01:49:32.9064934Z [command]/usr/bin/git submodule foreach --recursive sh -c "git config --local --name-only --get-regexp 'http\.https\:\/\/github\.com\/\.extraheader' && git config --local --unset-all 'http.https://github.com/.extraheader' || :"
2026-08-17T01:49:32.9275735Z [command]/usr/bin/git config --local --name-only --get-regexp ^includeIf\.gitdir:
2026-08-17T01:49:32.9307676Z [command]/usr/bin/git submodule foreach --recursive git config --local --show-origin --name-only --get-regexp remote.origin.url
2026-08-17T01:49:32.9662133Z Cleaning up orphan processes
2026-08-17T01:49:32.9897655Z ##[warning]Node.js 20 is deprecated. The following actions target Node.js 20 but are being forced to run on Node.js 24: actions/checkout@v4, actions/setup-java@v4, actions/upload-artifact@v4, gradle/actions/setup-gradle@v4. For more information see: https://github.blog/changelog/2025-09-19-deprecation-of-node-20-on-github-actions-runners/
