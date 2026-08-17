2026-08-17T00:36:47.9079027Z Current runner version: '2.336.0'
2026-08-17T00:36:47.9107917Z ##[group]Runner Image Provisioner
2026-08-17T00:36:47.9109995Z Hosted Compute Agent
2026-08-17T00:36:47.9110626Z Version: 20260729.566
2026-08-17T00:36:47.9111305Z Commit: cf7153fe6e25b664e8693c24944bf2b00355d109
2026-08-17T00:36:47.9112065Z Build Date: 2026-07-29T19:17:02Z
2026-08-17T00:36:47.9112756Z Worker ID: {b4c10611-7a12-4d81-9051-384efdb2d0d8}
2026-08-17T00:36:47.9113540Z Azure Region: centralus
2026-08-17T00:36:47.9114208Z ##[endgroup]
2026-08-17T00:36:47.9115726Z ##[group]Operating System
2026-08-17T00:36:47.9116466Z Ubuntu
2026-08-17T00:36:47.9117008Z 24.04.4
2026-08-17T00:36:47.9117607Z LTS
2026-08-17T00:36:47.9118202Z ##[endgroup]
2026-08-17T00:36:47.9119034Z ##[group]Runner Image
2026-08-17T00:36:47.9119737Z Image: ubuntu-24.04
2026-08-17T00:36:47.9120323Z Version: 20260810.271.1
2026-08-17T00:36:47.9121756Z Included Software: https://github.com/actions/runner-images/blob/ubuntu24/20260810.271/images/ubuntu/Ubuntu2404-Readme.md
2026-08-17T00:36:47.9123227Z Image Release: https://github.com/actions/runner-images/releases/tag/ubuntu24%2F20260810.271
2026-08-17T00:36:47.9124278Z ##[endgroup]
2026-08-17T00:36:47.9125516Z ##[group]GITHUB_TOKEN Permissions
2026-08-17T00:36:47.9127903Z Contents: read
2026-08-17T00:36:47.9128588Z Metadata: read
2026-08-17T00:36:47.9129339Z Packages: read
2026-08-17T00:36:47.9129997Z ##[endgroup]
2026-08-17T00:36:47.9132242Z Secret source: Actions
2026-08-17T00:36:47.9133693Z Prepare workflow directory
2026-08-17T00:36:47.9546714Z Prepare all required actions
2026-08-17T00:36:47.9602569Z Getting action download info
2026-08-17T00:36:48.2232811Z Download action repository 'actions/checkout@v4' (SHA:11d5960a326750d5838078e36cf38b85af677262)
2026-08-17T00:36:48.7566799Z Download action repository 'actions/setup-java@v4' (SHA:cf277c60eb25467037889841efdb72551f06f6c3)
2026-08-17T00:36:49.3671659Z Download action repository 'gradle/actions@v4' (SHA:ed408507eac070d1f99cc633dbcf757c94c7933a)
2026-08-17T00:36:50.4935265Z Download action repository 'android-actions/setup-android@v4' (SHA:40fd30fb8d7440372e1316f5d1809ec01dcd3699)
2026-08-17T00:36:50.7366140Z Download action repository 'actions/upload-artifact@v4' (SHA:ea165f8d65b6e75b540449e92b4886f43607fa02)
2026-08-17T00:36:51.0535547Z Complete job name: Build Android APK
2026-08-17T00:36:51.1431356Z Node 20 is being deprecated. This workflow is running with Node 24 by default. If you need to temporarily use Node 20, you can set the ACTIONS_ALLOW_USE_UNSECURE_NODE_VERSION=true environment variable. For more information see: https://github.blog/changelog/2025-09-19-deprecation-of-node-20-on-github-actions-runners/
2026-08-17T00:36:51.1440828Z ##[group]Run actions/checkout@v4
2026-08-17T00:36:51.1441285Z with:
2026-08-17T00:36:51.1441535Z   repository: Pikarziur/AutoBOT
2026-08-17T00:36:51.1444219Z   token: ***
2026-08-17T00:36:51.1444452Z   ssh-strict: true
2026-08-17T00:36:51.1444675Z   ssh-user: git
2026-08-17T00:36:51.1444905Z   persist-credentials: true
2026-08-17T00:36:51.1445189Z   clean: true
2026-08-17T00:36:51.1445420Z   sparse-checkout-cone-mode: true
2026-08-17T00:36:51.1445713Z   fetch-depth: 1
2026-08-17T00:36:51.1445935Z   fetch-tags: false
2026-08-17T00:36:51.1446158Z   show-progress: true
2026-08-17T00:36:51.1446382Z   lfs: false
2026-08-17T00:36:51.1446634Z   submodules: false
2026-08-17T00:36:51.1446860Z   set-safe-directory: true
2026-08-17T00:36:51.1447125Z   allow-unsafe-pr-checkout: false
2026-08-17T00:36:51.1447552Z env:
2026-08-17T00:36:51.1447751Z   GRADLE_VERSION: 8.5
2026-08-17T00:36:51.1447968Z   JAVA_VERSION: 17
2026-08-17T00:36:51.1448175Z ##[endgroup]
2026-08-17T00:36:51.2519187Z Syncing repository: Pikarziur/AutoBOT
2026-08-17T00:36:51.2521113Z ##[group]Getting Git version info
2026-08-17T00:36:51.2521703Z Working directory is '/home/runner/work/AutoBOT/AutoBOT'
2026-08-17T00:36:51.2522682Z [command]/usr/bin/git version
2026-08-17T00:36:51.3863321Z git version 2.54.0
2026-08-17T00:36:51.3892939Z ##[endgroup]
2026-08-17T00:36:51.3908987Z Temporarily overriding HOME='/home/runner/work/_temp/ef89d156-6738-41e6-8f9d-cd31f4097900' before making global git config changes
2026-08-17T00:36:51.3910461Z Adding repository directory to the temporary git global config as a safe directory
2026-08-17T00:36:51.3914785Z [command]/usr/bin/git config --global --add safe.directory /home/runner/work/AutoBOT/AutoBOT
2026-08-17T00:36:51.4174195Z Deleting the contents of '/home/runner/work/AutoBOT/AutoBOT'
2026-08-17T00:36:51.4179318Z ##[group]Initializing the repository
2026-08-17T00:36:51.4183805Z [command]/usr/bin/git init /home/runner/work/AutoBOT/AutoBOT
2026-08-17T00:36:51.4772208Z hint: Using 'master' as the name for the initial branch. This default branch name
2026-08-17T00:36:51.4773159Z hint: will change to "main" in Git 3.0. To configure the initial branch name
2026-08-17T00:36:51.4773766Z hint: to use in all of your new repositories, which will suppress this warning,
2026-08-17T00:36:51.4774166Z hint: call:
2026-08-17T00:36:51.4774370Z hint:
2026-08-17T00:36:51.4774733Z hint: 	git config --global init.defaultBranch <name>
2026-08-17T00:36:51.4775063Z hint:
2026-08-17T00:36:51.4775365Z hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
2026-08-17T00:36:51.4775859Z hint: 'development'. The just-created branch can be renamed via this command:
2026-08-17T00:36:51.4776273Z hint:
2026-08-17T00:36:51.4776505Z hint: 	git branch -m <name>
2026-08-17T00:36:51.4776739Z hint:
2026-08-17T00:36:51.4777064Z hint: Disable this message with "git config set advice.defaultBranchName false"
2026-08-17T00:36:51.4777601Z Initialized empty Git repository in /home/runner/work/AutoBOT/AutoBOT/.git/
2026-08-17T00:36:51.4784900Z [command]/usr/bin/git remote add origin https://github.com/Pikarziur/AutoBOT
2026-08-17T00:36:51.5101251Z ##[endgroup]
2026-08-17T00:36:51.5101729Z ##[group]Disabling automatic garbage collection
2026-08-17T00:36:51.5106090Z [command]/usr/bin/git config --local gc.auto 0
2026-08-17T00:36:51.5147974Z ##[endgroup]
2026-08-17T00:36:51.5148582Z ##[group]Setting up auth
2026-08-17T00:36:51.5157995Z [command]/usr/bin/git config --local --name-only --get-regexp core\.sshCommand
2026-08-17T00:36:51.5200067Z [command]/usr/bin/git submodule foreach --recursive sh -c "git config --local --name-only --get-regexp 'core\.sshCommand' && git config --local --unset-all 'core.sshCommand' || :"
2026-08-17T00:36:51.7308087Z [command]/usr/bin/git config --local --name-only --get-regexp http\.https\:\/\/github\.com\/\.extraheader
2026-08-17T00:36:51.7352676Z [command]/usr/bin/git submodule foreach --recursive sh -c "git config --local --name-only --get-regexp 'http\.https\:\/\/github\.com\/\.extraheader' && git config --local --unset-all 'http.https://github.com/.extraheader' || :"
2026-08-17T00:36:51.7622513Z [command]/usr/bin/git config --local --name-only --get-regexp ^includeIf\.gitdir:
2026-08-17T00:36:51.7665726Z [command]/usr/bin/git submodule foreach --recursive git config --local --show-origin --name-only --get-regexp remote.origin.url
2026-08-17T00:36:51.7934705Z [command]/usr/bin/git config --local http.https://github.com/.extraheader AUTHORIZATION: basic ***
2026-08-17T00:36:51.7979652Z ##[endgroup]
2026-08-17T00:36:51.7980583Z ##[group]Fetching the repository
2026-08-17T00:36:51.7990581Z [command]/usr/bin/git -c protocol.version=2 fetch --no-tags --prune --no-recurse-submodules --depth=1 origin +2250069352764867eb8efd4a6db6503923b097e5:refs/remotes/origin/main
2026-08-17T00:36:52.2746917Z From https://github.com/Pikarziur/AutoBOT
2026-08-17T00:36:52.2747616Z  * [new ref]         2250069352764867eb8efd4a6db6503923b097e5 -> origin/main
2026-08-17T00:36:52.2947968Z ##[endgroup]
2026-08-17T00:36:52.2948435Z ##[group]Determining the checkout info
2026-08-17T00:36:52.2950746Z ##[endgroup]
2026-08-17T00:36:52.2957154Z [command]/usr/bin/git sparse-checkout disable
2026-08-17T00:36:52.3056142Z [command]/usr/bin/git config --local --unset-all extensions.worktreeConfig
2026-08-17T00:36:52.3094950Z ##[group]Checking out the ref
2026-08-17T00:36:52.3095866Z [command]/usr/bin/git checkout --progress --force -B main refs/remotes/origin/main
2026-08-17T00:36:52.3275022Z Switched to a new branch 'main'
2026-08-17T00:36:52.3276311Z branch 'main' set up to track 'origin/main'.
2026-08-17T00:36:52.3281584Z ##[endgroup]
2026-08-17T00:36:52.3332905Z [command]/usr/bin/git log -1 --format=%H
2026-08-17T00:36:52.3367100Z 2250069352764867eb8efd4a6db6503923b097e5
2026-08-17T00:36:52.3676719Z Node 20 is being deprecated. This workflow is running with Node 24 by default. If you need to temporarily use Node 20, you can set the ACTIONS_ALLOW_USE_UNSECURE_NODE_VERSION=true environment variable. For more information see: https://github.blog/changelog/2025-09-19-deprecation-of-node-20-on-github-actions-runners/
2026-08-17T00:36:52.3678396Z ##[group]Run actions/setup-java@v4
2026-08-17T00:36:52.3678952Z with:
2026-08-17T00:36:52.3679191Z   distribution: temurin
2026-08-17T00:36:52.3679451Z   java-version: 17
2026-08-17T00:36:52.3679698Z   java-package: jdk
2026-08-17T00:36:52.3679948Z   check-latest: false
2026-08-17T00:36:52.3680217Z   server-id: github
2026-08-17T00:36:52.3680479Z   server-username: GITHUB_ACTOR
2026-08-17T00:36:52.3680770Z   server-password: GITHUB_TOKEN
2026-08-17T00:36:52.3681046Z   overwrite-settings: true
2026-08-17T00:36:52.3681308Z   job-status: success
2026-08-17T00:36:52.3683856Z   token: ***
2026-08-17T00:36:52.3684090Z env:
2026-08-17T00:36:52.3684370Z   GRADLE_VERSION: 8.5
2026-08-17T00:36:52.3684625Z   JAVA_VERSION: 17
2026-08-17T00:36:52.3684867Z ##[endgroup]
2026-08-17T00:36:52.5388317Z ##[warning]setup-java v4 is deprecated and will no longer receive updates. Please migrate to actions/setup-java@v5.
2026-08-17T00:36:52.5397611Z ##[group]Installed distributions
2026-08-17T00:36:52.5600287Z Resolved Java 17.0.20+8 from tool-cache
2026-08-17T00:36:52.5600837Z Setting Java 17.0.20+8 as the default
2026-08-17T00:36:52.5611134Z (node:2310) [DEP0040] DeprecationWarning: The `punycode` module is deprecated. Please use a userland alternative instead.
2026-08-17T00:36:52.5611872Z (Use `node --trace-deprecation ...` to show where the warning was created)
2026-08-17T00:36:52.5614936Z Creating toolchains.xml for JDK version 17 from temurin
2026-08-17T00:36:52.5686818Z Writing to /home/runner/.m2/toolchains.xml
2026-08-17T00:36:52.5687538Z 
2026-08-17T00:36:52.5687890Z Java configuration:
2026-08-17T00:36:52.5688487Z   Distribution: temurin
2026-08-17T00:36:52.5690083Z   Version: 17.0.20+8
2026-08-17T00:36:52.5691012Z   Path: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T00:36:52.5691437Z 
2026-08-17T00:36:52.5691998Z ##[endgroup]
2026-08-17T00:36:52.5707876Z Creating settings.xml with server-id: github
2026-08-17T00:36:52.5758181Z Writing to /home/runner/.m2/settings.xml
2026-08-17T00:36:52.6149956Z Node 20 is being deprecated. This workflow is running with Node 24 by default. If you need to temporarily use Node 20, you can set the ACTIONS_ALLOW_USE_UNSECURE_NODE_VERSION=true environment variable. For more information see: https://github.blog/changelog/2025-09-19-deprecation-of-node-20-on-github-actions-runners/
2026-08-17T00:36:52.6151312Z ##[group]Run gradle/actions/setup-gradle@v4
2026-08-17T00:36:52.6151614Z with:
2026-08-17T00:36:52.6151830Z   gradle-version: 8.5
2026-08-17T00:36:52.6152073Z   cache-read-only: false
2026-08-17T00:36:52.6152322Z   validate-wrappers: false
2026-08-17T00:36:52.6152568Z   cache-disabled: false
2026-08-17T00:36:52.6152811Z   cache-write-only: false
2026-08-17T00:36:52.6153066Z   cache-overwrite-existing: false
2026-08-17T00:36:52.6153344Z   cache-cleanup: on-success
2026-08-17T00:36:52.6153644Z   gradle-home-cache-includes: caches
notifications

2026-08-17T00:36:52.6153975Z   add-job-summary: always
2026-08-17T00:36:52.6154301Z   add-job-summary-as-pr-comment: never
2026-08-17T00:36:52.6154596Z   dependency-graph: disabled
2026-08-17T00:36:52.6154909Z   dependency-graph-report-dir: dependency-graph-reports
2026-08-17T00:36:52.6155284Z   dependency-graph-continue-on-failure: true
2026-08-17T00:36:52.6155601Z   build-scan-publish: false
2026-08-17T00:36:52.6156096Z   allow-snapshot-wrappers: false
2026-08-17T00:36:52.6156588Z   gradle-home-cache-strict-match: false
2026-08-17T00:36:52.6156882Z   workflow-job-context: null
2026-08-17T00:36:52.6159730Z   github-token: ***
2026-08-17T00:36:52.6159954Z env:
2026-08-17T00:36:52.6160159Z   GRADLE_VERSION: 8.5
2026-08-17T00:36:52.6160392Z   JAVA_VERSION: 17
2026-08-17T00:36:52.6160729Z   JAVA_HOME: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T00:36:52.6161223Z   JAVA_HOME_17_X64: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T00:36:52.6161608Z ##[endgroup]
2026-08-17T00:36:54.2761520Z Merged default JDK locations into /home/runner/.m2/toolchains.xml
2026-08-17T00:36:54.2763190Z Preparing cache for cleanup.
2026-08-17T00:36:54.2767029Z ##[group]Restore Gradle state from cache
2026-08-17T00:36:54.4357352Z Cache hit for restore-key: gradle-home-v1|Linux-X64|build[266babc85e2a7f6e4c23c8d6be839361]-3d748ac8b00b8440bde120304a1fe669ccf0b669
2026-08-17T00:36:55.6036217Z Received 96468992 of 143459626 (67.2%), 91.9 MBs/sec
2026-08-17T00:36:56.0560844Z Received 143459626 of 143459626 (100.0%), 94.3 MBs/sec
2026-08-17T00:36:56.0589393Z Cache Size: ~137 MB (143459626 B)
2026-08-17T00:36:56.0689865Z [command]/usr/bin/tar -xf /home/runner/work/_temp/dbb04a5e-0a4f-4601-9912-4382d29851d5/cache.tzst -P -C /home/runner/work/AutoBOT/AutoBOT --use-compress-program unzstd
2026-08-17T00:36:57.1056141Z Cache restored successfully
2026-08-17T00:36:57.1131006Z Restored cache entry with key gradle-home-v1|Linux-X64|build[266babc85e2a7f6e4c23c8d6be839361]-2250069352764867eb8efd4a6db6503923b097e5 to /home/runner/.gradle/caches,/home/runner/.gradle/notifications,/home/runner/.gradle/.setup-gradle in 2835ms
2026-08-17T00:36:57.2450418Z Cache hit for: gradle-generated-gradle-jars-v1-fa001ab82c3596b4e27ec78f191b889f
2026-08-17T00:36:57.2461588Z Cache hit for: gradle-wrapper-zips-v1-e89a30cff1b7b918cfe1273c9c8e4a34
2026-08-17T00:36:57.2526877Z Cache hit for: gradle-instrumented-jars-v1-289570630d9f1eeabb0c939ab04670fd
2026-08-17T00:36:57.2531910Z Cache hit for: gradle-kotlin-dsl-v1-86903c45d6b8a8330f048b9beae0c1ea
2026-08-17T00:36:57.2560588Z Cache hit for: gradle-groovy-dsl-v1-df4ccfff3656846e3168e11ba2954a00
2026-08-17T00:36:57.2588593Z Cache hit for: gradle-dependencies-v1-ca33a97c11bd8dec625e8d54280f9120
2026-08-17T00:36:57.5968293Z Received 98340 of 98340 (100.0%), 0.5 MBs/sec
2026-08-17T00:36:57.5969205Z Cache Size: ~0 MB (98340 B)
2026-08-17T00:36:57.5994524Z [command]/usr/bin/tar -xf /home/runner/work/_temp/5225309d-4e15-486e-8a3d-b2c64627fba0/cache.tzst -P -C /home/runner/work/AutoBOT/AutoBOT --use-compress-program unzstd
2026-08-17T00:36:57.6368059Z Cache restored successfully
2026-08-17T00:36:57.6373789Z Restored cache entry with key gradle-kotlin-dsl-v1-86903c45d6b8a8330f048b9beae0c1ea to /home/runner/.gradle/caches/*/kotlin-dsl/accessors/*/,/home/runner/.gradle/caches/*/kotlin-dsl/scripts/*/ in 522ms
2026-08-17T00:36:57.6490735Z Received 109102 of 109102 (100.0%), 0.4 MBs/sec
2026-08-17T00:36:57.6491382Z Cache Size: ~0 MB (109102 B)
2026-08-17T00:36:57.6514796Z [command]/usr/bin/tar -xf /home/runner/work/_temp/bc14d7db-451f-4895-b7c7-11b2597ae589/cache.tzst -P -C /home/runner/work/AutoBOT/AutoBOT --use-compress-program unzstd
2026-08-17T00:36:57.6684004Z Cache restored successfully
2026-08-17T00:36:57.6686664Z Restored cache entry with key gradle-groovy-dsl-v1-df4ccfff3656846e3168e11ba2954a00 to /home/runner/.gradle/caches/*/groovy-dsl/*/ in 553ms
2026-08-17T00:36:58.1512106Z Received 36784583 of 36784583 (100.0%), 45.3 MBs/sec
2026-08-17T00:36:58.1514193Z Cache Size: ~35 MB (36784583 B)
2026-08-17T00:36:58.1791482Z [command]/usr/bin/tar -xf /home/runner/work/_temp/016d8595-7c0e-4303-af6a-864d88bc2350/cache.tzst -P -C /home/runner/work/AutoBOT/AutoBOT --use-compress-program unzstd
2026-08-17T00:36:58.4170603Z Received 62914560 of 131966939 (47.7%), 58.6 MBs/sec
2026-08-17T00:36:58.4189680Z Received 50331648 of 89746985 (56.1%), 47.4 MBs/sec
2026-08-17T00:36:58.4405381Z Received 41943040 of 328896045 (12.8%), 39.1 MBs/sec
2026-08-17T00:36:58.5350218Z Cache restored successfully
2026-08-17T00:36:58.5466277Z Restored cache entry with key gradle-generated-gradle-jars-v1-fa001ab82c3596b4e27ec78f191b889f to /home/runner/.gradle/caches/8.5/generated-gradle-jars/gradle-api-8.5.jar in 1433ms
2026-08-17T00:36:58.7240083Z Received 89746985 of 89746985 (100.0%), 64.9 MBs/sec
2026-08-17T00:36:58.7240692Z Cache Size: ~86 MB (89746985 B)
2026-08-17T00:36:58.7624454Z [command]/usr/bin/tar -xf /home/runner/work/_temp/95253cdf-5bb6-4ac6-8794-36220d95a28a/cache.tzst -P -C /home/runner/work/AutoBOT/AutoBOT --use-compress-program unzstd
2026-08-17T00:36:58.8811371Z Received 131966939 of 131966939 (100.0%), 84.7 MBs/sec
2026-08-17T00:36:58.8889588Z Cache Size: ~126 MB (131966939 B)
2026-08-17T00:36:58.9179452Z [command]/usr/bin/tar -xf /home/runner/work/_temp/cbb1fcdc-6d52-4424-ab20-bd34e6429d48/cache.tzst -P -C /home/runner/work/AutoBOT/AutoBOT --use-compress-program unzstd
2026-08-17T00:36:59.2740747Z Cache restored successfully
2026-08-17T00:36:59.2875034Z Restored cache entry with key gradle-wrapper-zips-v1-e89a30cff1b7b918cfe1273c9c8e4a34 to /home/runner/.gradle/wrapper/dists/gradle-8.5-bin/5t9huq95ubn472n8rpzujfbqh in 2173ms
2026-08-17T00:36:59.4460271Z Received 197132288 of 328896045 (59.9%), 92.8 MBs/sec
2026-08-17T00:36:59.6179402Z Cache restored successfully
2026-08-17T00:36:59.6237711Z Restored cache entry with key gradle-instrumented-jars-v1-289570630d9f1eeabb0c939ab04670fd to /home/runner/.gradle/caches/jars-*/*/ in 2508ms
2026-08-17T00:37:00.1413028Z Received 328896045 of 328896045 (100.0%), 115.2 MBs/sec
2026-08-17T00:37:00.1413977Z Cache Size: ~314 MB (328896045 B)
2026-08-17T00:37:00.1523581Z [command]/usr/bin/tar -xf /home/runner/work/_temp/006dc5fa-61f7-4a67-87b7-11d1601174b6/cache.tzst -P -C /home/runner/work/AutoBOT/AutoBOT --use-compress-program unzstd
2026-08-17T00:37:00.6437028Z Cache restored successfully
2026-08-17T00:37:00.9675808Z Restored cache entry with key gradle-dependencies-v1-ca33a97c11bd8dec625e8d54280f9120 to /home/runner/.gradle/caches/modules-*/files-*/*/*/*/* in 3851ms
2026-08-17T00:37:00.9926325Z ##[endgroup]
2026-08-17T00:37:01.0787594Z ##[group]Provision Gradle 8.5
2026-08-17T00:37:07.4875119Z Cache hit for: gradle-8.5
2026-08-17T00:37:08.5203950Z Received 104857600 of 132239594 (79.3%), 99.9 MBs/sec
2026-08-17T00:37:08.7572656Z Received 132239594 of 132239594 (100.0%), 102.0 MBs/sec
2026-08-17T00:37:08.7574329Z Cache Size: ~126 MB (132239594 B)
2026-08-17T00:37:08.7645939Z [command]/usr/bin/tar -xf /home/runner/work/_temp/fb167bc7-8be2-4663-9152-772e4e95ac04/cache.tzst -P -C /home/runner/work/AutoBOT/AutoBOT --use-compress-program unzstd
2026-08-17T00:37:08.9486821Z Cache restored successfully
2026-08-17T00:37:08.9552923Z Restored Gradle distribution gradle-8.5 from cache to /home/runner/work/_temp/.gradle-actions/gradle-installations/downloads/gradle-8.5-bin.zip
2026-08-17T00:37:08.9570749Z [command]/usr/bin/unzip -o -q /home/runner/work/_temp/.gradle-actions/gradle-installations/downloads/gradle-8.5-bin.zip
2026-08-17T00:37:10.0199453Z Extracted Gradle 8.5 to /home/runner/work/_temp/.gradle-actions/gradle-installations/installs/gradle-8.5
2026-08-17T00:37:10.0201188Z Provisioned Gradle executable /home/runner/work/_temp/.gradle-actions/gradle-installations/installs/gradle-8.5/bin/gradle
2026-08-17T00:37:10.0202617Z ##[endgroup]
2026-08-17T00:37:10.0436547Z ##[group]Run if [ -f "gradle/wrapper/gradle-wrapper.jar" ]; then
2026-08-17T00:37:10.0437179Z [36;1mif [ -f "gradle/wrapper/gradle-wrapper.jar" ]; then[0m
2026-08-17T00:37:10.0437714Z [36;1m  echo "✅ gradle-wrapper.jar already exists, skip generation"[0m
2026-08-17T00:37:10.0438195Z [36;1m  ls -la gradle/wrapper/[0m
2026-08-17T00:37:10.0438518Z [36;1m  exit 0[0m
2026-08-17T00:37:10.0439071Z [36;1mfi[0m
2026-08-17T00:37:10.0439321Z [36;1m[0m
2026-08-17T00:37:10.0439719Z [36;1mecho "⚠️ gradle-wrapper.jar not found. Generating via gradle command..."[0m
2026-08-17T00:37:10.0440247Z [36;1mecho "gradle version: $(gradle --version)"[0m
2026-08-17T00:37:10.0441044Z [36;1mgradle wrapper --gradle-version "$GRADLE_VERSION" --distribution-type bin --no-daemon[0m
2026-08-17T00:37:10.0441543Z [36;1m[0m
2026-08-17T00:37:10.0441867Z [36;1mif [ -f "gradle/wrapper/gradle-wrapper.jar" ]; then[0m
2026-08-17T00:37:10.0442396Z [36;1m  echo "✅ Generated gradle-wrapper.jar successfully:"[0m
2026-08-17T00:37:10.0442798Z [36;1m  ls -la gradle/wrapper/[0m
2026-08-17T00:37:10.0443102Z [36;1melse[0m
2026-08-17T00:37:10.0443417Z [36;1m  echo "❌ Failed to generate gradle-wrapper.jar"[0m
2026-08-17T00:37:10.0443791Z [36;1m  ls -la gradle/ || true[0m
2026-08-17T00:37:10.0444091Z [36;1m  exit 1[0m
2026-08-17T00:37:10.0444345Z [36;1mfi[0m
2026-08-17T00:37:10.0489795Z shell: /usr/bin/bash --noprofile --norc -e -o pipefail {0}
2026-08-17T00:37:10.0490226Z env:
2026-08-17T00:37:10.0490494Z   GRADLE_VERSION: 8.5
2026-08-17T00:37:10.0490780Z   JAVA_VERSION: 17
2026-08-17T00:37:10.0491182Z   JAVA_HOME: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T00:37:10.0491780Z   JAVA_HOME_17_X64: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T00:37:10.0492259Z   GRADLE_ACTION_ID: gradle/actions/setup-gradle
2026-08-17T00:37:10.0492642Z   GRADLE_USER_HOME: /home/runner/.gradle
2026-08-17T00:37:10.0492990Z   GRADLE_BUILD_ACTION_SETUP_COMPLETED: true
2026-08-17T00:37:10.0493371Z   GRADLE_BUILD_ACTION_CACHE_RESTORED: true
2026-08-17T00:37:10.0493882Z   DEVELOCITY_INJECTION_INIT_SCRIPT_NAME: gradle-actions.inject-develocity.init.gradle
2026-08-17T00:37:10.0494428Z   DEVELOCITY_INJECTION_CUSTOM_VALUE: gradle-actions
2026-08-17T00:37:10.0494794Z   GITHUB_DEPENDENCY_GRAPH_ENABLED: false
2026-08-17T00:37:10.0495120Z ##[endgroup]
2026-08-17T00:37:10.0590289Z ⚠️ gradle-wrapper.jar not found. Generating via gradle command...
2026-08-17T00:37:10.5975846Z gradle version: 
2026-08-17T00:37:10.5976438Z ------------------------------------------------------------
2026-08-17T00:37:10.5976915Z Gradle 8.5
2026-08-17T00:37:10.5977273Z ------------------------------------------------------------
2026-08-17T00:37:10.5977534Z 
2026-08-17T00:37:10.5977667Z Build time:   2023-11-29 14:08:57 UTC
2026-08-17T00:37:10.5978060Z Revision:     28aca86a7180baa17117e0e5ba01d8ea9feca598
2026-08-17T00:37:10.5978316Z 
2026-08-17T00:37:10.5978449Z Kotlin:       1.9.20
2026-08-17T00:37:10.5978906Z Groovy:       3.0.17
2026-08-17T00:37:10.5979284Z Ant:          Apache Ant(TM) version 1.10.13 compiled on January 4 2023
2026-08-17T00:37:10.5979739Z JVM:          17.0.20 (Eclipse Adoptium 17.0.20+8)
2026-08-17T00:37:10.5980110Z OS:           Linux 6.17.0-1022-azure amd64
2026-08-17T00:37:11.2004563Z To honour the JVM settings for this build a single-use Daemon process will be forked. For more on this, please refer to https://docs.gradle.org/8.5/userguide/gradle_daemon.html#sec:disabling_the_daemon in the Gradle documentation.
2026-08-17T00:37:12.6991970Z Daemon will be stopped at the end of the build 
2026-08-17T00:37:22.9996543Z 
2026-08-17T00:37:23.0007063Z > Configure project :app
2026-08-17T00:37:23.0012970Z Checking the license for package NDK (Side by side) 25.2.9519653 in /usr/local/lib/android/sdk/licenses
2026-08-17T00:37:23.0014376Z License for package NDK (Side by side) 25.2.9519653 accepted.
2026-08-17T00:37:23.0015860Z Preparing "Install NDK (Side by side) 25.2.9519653 v.25.2.9519653".
2026-08-17T00:37:39.2992145Z "Install NDK (Side by side) 25.2.9519653 v.25.2.9519653" ready.
2026-08-17T00:37:39.2992815Z Installing NDK (Side by side) 25.2.9519653 in /usr/local/lib/android/sdk/ndk/25.2.9519653
2026-08-17T00:37:39.3991050Z "Install NDK (Side by side) 25.2.9519653 v.25.2.9519653" complete.
2026-08-17T00:37:39.8992209Z "Install NDK (Side by side) 25.2.9519653 v.25.2.9519653" finished.
2026-08-17T00:37:41.6991822Z 
2026-08-17T00:37:41.7000160Z > Task :wrapper
2026-08-17T00:37:41.7673713Z gradle/actions: Writing build results to /home/runner/work/_temp/.gradle-actions/build-results/__run-1786927035062.json
2026-08-17T00:37:41.7677135Z 
2026-08-17T00:37:41.7689133Z BUILD SUCCESSFUL in 31s
2026-08-17T00:37:41.7690136Z 1 actionable task: 1 executed
2026-08-17T00:37:42.0914972Z ✅ Generated gradle-wrapper.jar successfully:
2026-08-17T00:37:42.0931263Z total 56
2026-08-17T00:37:42.0931720Z drwxr-xr-x 2 runner runner  4096 Aug 17 00:37 .
2026-08-17T00:37:42.0932401Z drwxr-xr-x 3 runner runner  4096 Aug 17 00:37 ..
2026-08-17T00:37:42.0933072Z -rw-r--r-- 1 runner runner 43462 Aug 17 00:37 gradle-wrapper.jar
2026-08-17T00:37:42.0933897Z -rw-r--r-- 1 runner runner   250 Aug 17 00:37 gradle-wrapper.properties
2026-08-17T00:37:42.0974469Z ##[group]Run chmod +x gradlew
2026-08-17T00:37:42.0974887Z [36;1mchmod +x gradlew[0m
2026-08-17T00:37:42.1029763Z shell: /usr/bin/bash -e {0}
2026-08-17T00:37:42.1030128Z env:
2026-08-17T00:37:42.1030415Z   GRADLE_VERSION: 8.5
2026-08-17T00:37:42.1030733Z   JAVA_VERSION: 17
2026-08-17T00:37:42.1031165Z   JAVA_HOME: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T00:37:42.1031782Z   JAVA_HOME_17_X64: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T00:37:42.1032324Z   GRADLE_ACTION_ID: gradle/actions/setup-gradle
2026-08-17T00:37:42.1032755Z   GRADLE_USER_HOME: /home/runner/.gradle
2026-08-17T00:37:42.1033151Z   GRADLE_BUILD_ACTION_SETUP_COMPLETED: true
2026-08-17T00:37:42.1033554Z   GRADLE_BUILD_ACTION_CACHE_RESTORED: true
2026-08-17T00:37:42.1034100Z   DEVELOCITY_INJECTION_INIT_SCRIPT_NAME: gradle-actions.inject-develocity.init.gradle
2026-08-17T00:37:42.1034681Z   DEVELOCITY_INJECTION_CUSTOM_VALUE: gradle-actions
2026-08-17T00:37:42.1035143Z   GITHUB_DEPENDENCY_GRAPH_ENABLED: false
2026-08-17T00:37:42.1035686Z ##[endgroup]
2026-08-17T00:37:42.1166788Z ##[group]Run android-actions/setup-android@v4
2026-08-17T00:37:42.1167203Z with:
2026-08-17T00:37:42.1167521Z   accept-android-sdk-licenses: true
2026-08-17T00:37:42.1167921Z   log-accepted-android-sdk-licenses: false
2026-08-17T00:37:42.1168421Z   cmdline-tools-version: 14742923
2026-08-17T00:37:42.1169290Z env:
2026-08-17T00:37:42.1169726Z   GRADLE_VERSION: 8.5
2026-08-17T00:37:42.1170336Z   JAVA_VERSION: 17
2026-08-17T00:37:42.1171008Z   JAVA_HOME: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T00:37:42.1171791Z   JAVA_HOME_17_X64: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T00:37:42.1172501Z   GRADLE_ACTION_ID: gradle/actions/setup-gradle
2026-08-17T00:37:42.1173120Z   GRADLE_USER_HOME: /home/runner/.gradle
2026-08-17T00:37:42.1173698Z   GRADLE_BUILD_ACTION_SETUP_COMPLETED: true
2026-08-17T00:37:42.1174328Z   GRADLE_BUILD_ACTION_CACHE_RESTORED: true
2026-08-17T00:37:42.1175166Z   DEVELOCITY_INJECTION_INIT_SCRIPT_NAME: gradle-actions.inject-develocity.init.gradle
2026-08-17T00:37:42.1176004Z   DEVELOCITY_INJECTION_CUSTOM_VALUE: gradle-actions
2026-08-17T00:37:42.1176656Z   GITHUB_DEPENDENCY_GRAPH_ENABLED: false
2026-08-17T00:37:42.1177158Z ##[endgroup]
2026-08-17T00:37:42.2005970Z Found preinstalled sdkmanager in /usr/local/lib/android/sdk/cmdline-tools/latest with following source.properties:
2026-08-17T00:37:42.2007047Z Pkg.Revision=12.0
2026-08-17T00:37:42.2007461Z Pkg.Path=cmdline-tools;12.0
2026-08-17T00:37:42.2007809Z Pkg.Desc=Android SDK Command-line Tools
2026-08-17T00:37:42.2008047Z 
2026-08-17T00:37:42.2008192Z Wrong version in preinstalled sdkmanager
2026-08-17T00:37:42.2009881Z Downloading commandline tools from https://dl.google.com/android/repository/commandlinetools-linux-14742923_latest.zip
2026-08-17T00:37:43.1584033Z [command]/usr/bin/unzip -o -q /home/runner/work/_temp/d22f88c3-f10e-4a6f-982c-89d2c6410dac
2026-08-17T00:37:44.0540595Z Accepting Android SDK licenses
2026-08-17T00:37:46.6756904Z ##[group]Run echo "ANDROID_HOME=$ANDROID_HOME"
2026-08-17T00:37:46.6757366Z [36;1mecho "ANDROID_HOME=$ANDROID_HOME"[0m
2026-08-17T00:37:46.6757761Z [36;1mecho "sdkmanager path: $(which sdkmanager)"[0m
2026-08-17T00:37:46.6758143Z [36;1msdkmanager --install \[0m
2026-08-17T00:37:46.6758477Z [36;1m  "platforms;android-34" \[0m
2026-08-17T00:37:46.6759160Z [36;1m  "build-tools;34.0.0" \[0m
2026-08-17T00:37:46.6759687Z [36;1m  "platform-tools" \[0m
2026-08-17T00:37:46.6759990Z [36;1m  "ndk;25.2.9519653" \[0m
2026-08-17T00:37:46.6760292Z [36;1m  "cmake;3.22.1"[0m
2026-08-17T00:37:46.6760622Z [36;1mecho "✅ SDK components installed"[0m
2026-08-17T00:37:46.6761072Z [36;1msdkmanager --list_installed || sdkmanager --list | head -50[0m
2026-08-17T00:37:46.6803362Z shell: /usr/bin/bash --noprofile --norc -e -o pipefail {0}
2026-08-17T00:37:46.6803772Z env:
2026-08-17T00:37:46.6804031Z   GRADLE_VERSION: 8.5
2026-08-17T00:37:46.6804317Z   JAVA_VERSION: 17
2026-08-17T00:37:46.6804752Z   JAVA_HOME: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T00:37:46.6805319Z   JAVA_HOME_17_X64: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T00:37:46.6805806Z   GRADLE_ACTION_ID: gradle/actions/setup-gradle
2026-08-17T00:37:46.6806195Z   GRADLE_USER_HOME: /home/runner/.gradle
2026-08-17T00:37:46.6806547Z   GRADLE_BUILD_ACTION_SETUP_COMPLETED: true
2026-08-17T00:37:46.6806936Z   GRADLE_BUILD_ACTION_CACHE_RESTORED: true
2026-08-17T00:37:46.6807446Z   DEVELOCITY_INJECTION_INIT_SCRIPT_NAME: gradle-actions.inject-develocity.init.gradle
2026-08-17T00:37:46.6807979Z   DEVELOCITY_INJECTION_CUSTOM_VALUE: gradle-actions
2026-08-17T00:37:46.6808357Z   GITHUB_DEPENDENCY_GRAPH_ENABLED: false
2026-08-17T00:37:46.6808982Z   ANDROID_HOME: /usr/local/lib/android/sdk
2026-08-17T00:37:46.6809417Z   ANDROID_SDK_ROOT: /usr/local/lib/android/sdk
2026-08-17T00:37:46.6809942Z ##[endgroup]
2026-08-17T00:37:46.6877508Z ANDROID_HOME=/usr/local/lib/android/sdk
2026-08-17T00:37:46.6892506Z sdkmanager path: /usr/local/lib/android/sdk/cmdline-tools/20.0/bin/sdkmanager
2026-08-17T00:37:47.8405242Z Loading package information...                                                  
2026-08-17T00:37:47.9680633Z Loading local repository...                                                     
2026-08-17T00:37:47.9681716Z [                                       ] 3% Loading local repository...        
2026-08-17T00:37:47.9790187Z [                                       ] 3% Fetch remote repository...         
2026-08-17T00:37:48.2891117Z [=                                      ] 3% Fetch remote repository...         
2026-08-17T00:37:48.3658867Z [=                                      ] 4% Fetch remote repository...         
2026-08-17T00:37:48.3985223Z [=                                      ] 5% Fetch remote repository...         
2026-08-17T00:37:48.4443577Z [==                                     ] 5% Fetch remote repository...         
2026-08-17T00:37:48.5180438Z [==                                     ] 6% Fetch remote repository...         
2026-08-17T00:37:48.5970515Z [==                                     ] 7% Fetch remote repository...         
2026-08-17T00:37:48.5990663Z [==                                     ] 7% Computing updates...               
2026-08-17T00:37:48.6100443Z [===                                    ] 8% Computing updates...               
2026-08-17T00:37:48.6245634Z [===                                    ] 10% Computing updates...              
2026-08-17T00:37:49.0310327Z [===                                    ] 10% Installing CMake 3.22.1           
2026-08-17T00:37:49.1268097Z [===                                    ] 10% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:37:49.1898424Z [====                                   ] 10% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:37:49.2552144Z [====                                   ] 11% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:37:49.2923016Z [====                                   ] 12% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:37:49.3102612Z [=====                                  ] 13% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:37:49.3301201Z [=====                                  ] 14% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:37:49.3366623Z [=====                                  ] 15% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:37:49.3432140Z [======                                 ] 15% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:37:49.3588620Z [======                                 ] 16% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:37:49.3674642Z [======                                 ] 17% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:37:49.3776936Z [=======                                ] 18% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:37:49.3909217Z [=======                                ] 19% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:37:49.3950841Z [=======                                ] 20% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:37:49.3981895Z [========                               ] 20% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:37:49.4058359Z [========                               ] 21% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:37:49.4153598Z [========                               ] 22% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:37:49.4220293Z [=========                              ] 23% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:37:49.4307301Z [=========                              ] 24% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:37:49.4346617Z [=========                              ] 25% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:37:49.4379154Z [==========                             ] 25% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:37:49.4459719Z [==========                             ] 26% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:37:49.4538381Z [==========                             ] 27% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:37:49.4657089Z [===========                            ] 28% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:37:49.4718811Z [===========                            ] 29% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:37:49.4745789Z [===========                            ] 30% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:37:49.4786962Z [============                           ] 30% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:37:49.4841215Z [============                           ] 31% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:37:49.4932965Z [============                           ] 32% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:37:49.4934568Z [============                           ] 33% Downloading cmake-3.22.1-linux.zip
2026-08-17T00:37:49.6606199Z [============                           ] 33% Unzipping...                      
2026-08-17T00:37:49.6648469Z [============                           ] 33% Unzipping... bin/cmake            
2026-08-17T00:37:49.6848333Z [=============                          ] 33% Unzipping... bin/cmake            
2026-08-17T00:37:49.7014591Z [=============                          ] 34% Unzipping... bin/cmake            
2026-08-17T00:37:49.7098160Z [=============                          ] 35% Unzipping... bin/cmake            
2026-08-17T00:37:49.7188938Z [==============                         ] 35% Unzipping... bin/cmake            
2026-08-17T00:37:49.7374272Z [==============                         ] 36% Unzipping... bin/cmake            
2026-08-17T00:37:49.7524618Z [==============                         ] 37% Unzipping... bin/cmake            
2026-08-17T00:37:49.7658100Z [===============                        ] 38% Unzipping... bin/cmake            
2026-08-17T00:37:49.7740426Z [===============                        ] 39% Unzipping... bin/cmake            
2026-08-17T00:37:49.7860407Z [===============                        ] 39% Unzipping... bin/ctest            
2026-08-17T00:37:49.7927580Z [===============                        ] 40% Unzipping... bin/ctest            
2026-08-17T00:37:49.7999778Z [================                       ] 40% Unzipping... bin/ctest            
2026-08-17T00:37:49.8158047Z [================                       ] 41% Unzipping... bin/ctest            
2026-08-17T00:37:49.8325254Z [================                       ] 42% Unzipping... bin/ctest            
2026-08-17T00:37:49.8500651Z [=================                      ] 43% Unzipping... bin/ctest            
2026-08-17T00:37:49.8632085Z [=================                      ] 44% Unzipping... bin/ctest            
2026-08-17T00:37:49.8701342Z [=================                      ] 45% Unzipping... bin/ctest            
2026-08-17T00:37:49.8767632Z [==================                     ] 45% Unzipping... bin/ctest            
2026-08-17T00:37:49.8794201Z [==================                     ] 46% Unzipping... bin/ctest            
2026-08-17T00:37:49.8943599Z [==================                     ] 46% Unzipping... bin/cpack            
2026-08-17T00:37:49.9099699Z [==================                     ] 47% Unzipping... bin/cpack            
2026-08-17T00:37:49.9243462Z [===================                    ] 48% Unzipping... bin/cpack            
2026-08-17T00:37:49.9406909Z [===================                    ] 49% Unzipping... bin/cpack            
2026-08-17T00:37:49.9490499Z [===================                    ] 50% Unzipping... bin/cpack            
2026-08-17T00:37:49.9556245Z [====================                   ] 50% Unzipping... bin/cpack            
2026-08-17T00:37:49.9689723Z [====================                   ] 51% Unzipping... bin/cpack            
2026-08-17T00:37:49.9764929Z [====================                   ] 52% Unzipping... bin/cpack            
2026-08-17T00:37:49.9782845Z [====================                   ] 52% Unzipping... share/vim/vimfiles/in
2026-08-17T00:37:49.9814957Z [====================                   ] 52% Unzipping... share/vim/vimfiles/sy
2026-08-17T00:37:49.9839963Z [====================                   ] 52% Unzipping... share/aclocal/cmake.m
2026-08-17T00:37:49.9864412Z [====================                   ] 52% Unzipping... share/emacs/site-lisp
2026-08-17T00:37:49.9866926Z [====================                   ] 52% Unzipping... share/cmake-3.22/incl
2026-08-17T00:37:50.2443383Z [====================                   ] 52% Unzipping... share/cmake-3.22/Help
2026-08-17T00:37:50.3877467Z [=====================                  ] 53% Unzipping... share/cmake-3.22/Help
2026-08-17T00:37:50.4016677Z [=====================                  ] 53% Unzipping... share/cmake-3.22/Temp
2026-08-17T00:37:50.4592095Z [=====================                  ] 53% Unzipping... share/cmake-3.22/Modu
2026-08-17T00:37:50.6193134Z [=====================                  ] 54% Unzipping... share/cmake-3.22/Modu
2026-08-17T00:37:50.6199751Z [=====================                  ] 54% Unzipping... share/bash-completion
2026-08-17T00:37:50.6203273Z [=====================                  ] 54% Unzipping... doc/cmake-3.22/Copyri
2026-08-17T00:37:50.6205434Z [=====================                  ] 54% Unzipping... doc/cmake-3.22/cmzlib
2026-08-17T00:37:50.6208039Z [=====================                  ] 54% Unzipping... doc/cmake-3.22/cmzstd
2026-08-17T00:37:50.6210724Z [=====================                  ] 54% Unzipping... doc/cmake-3.22/cmnght
2026-08-17T00:37:50.6213384Z [=====================                  ] 54% Unzipping... doc/cmake-3.22/cmsys/
2026-08-17T00:37:50.6216396Z [=====================                  ] 54% Unzipping... doc/cmake-3.22/cmcurl
2026-08-17T00:37:50.6219498Z [=====================                  ] 54% Unzipping... doc/cmake-3.22/cmlibr
2026-08-17T00:37:50.6222562Z [=====================                  ] 54% Unzipping... doc/cmake-3.22/cmliba
2026-08-17T00:37:50.6225537Z [=====================                  ] 54% Unzipping... doc/cmake-3.22/cmlibl
2026-08-17T00:37:50.6229321Z [=====================                  ] 54% Unzipping... doc/cmake-3.22/cmlibu
2026-08-17T00:37:50.6233013Z [=====================                  ] 54% Unzipping... doc/openssl-1.1.1l/LI
2026-08-17T00:37:50.6234770Z [=====================                  ] 54% Unzipping... source.properties    
2026-08-17T00:37:50.6266671Z [=====================                  ] 54% Unzipping... bin/ninja            
2026-08-17T00:37:50.6269738Z [=====================                  ] 54% Unzipping... doc/ninja/LICENSE    
2026-08-17T00:37:50.6275264Z [=====================                  ] 54% Unzipping... share/cmake-3.22/Modu
2026-08-17T00:37:50.6371597Z [=====================                  ] 55% Unzipping... share/cmake-3.22/Modu
2026-08-17T00:37:50.6374272Z [=======================================] 100% Unzipping... share/cmake-3.22/Mod
2026-08-17T00:37:50.7579508Z 
2026-08-17T00:37:50.7817344Z ✅ SDK components installed
2026-08-17T00:37:51.6299279Z Loading package information...                                                  
2026-08-17T00:37:51.7148890Z Loading local repository...                                                     
2026-08-17T00:37:51.7179544Z [=========                              ] 25% Loading local repository...       
2026-08-17T00:37:51.7180700Z Installed packages:
2026-08-17T00:37:51.7330935Z   Path                               | Version       | Description                      | Location                          
2026-08-17T00:37:51.7346942Z   -------                            | -------       | -------                          | -------                           
2026-08-17T00:37:51.7364442Z   build-tools;34.0.0                 | 34.0.0        | Android SDK Build-Tools 34       | build-tools/34.0.0                
2026-08-17T00:37:51.7372420Z   build-tools;35.0.0                 | 35.0.0        | Android SDK Build-Tools 35       | build-tools/35.0.0                
2026-08-17T00:37:51.7378602Z   build-tools;35.0.1                 | 35.0.1        | Android SDK Build-Tools 35.0.1   | build-tools/35.0.1                
2026-08-17T00:37:51.7385862Z   build-tools;36.0.0                 | 36.0.0        | Android SDK Build-Tools 36       | build-tools/36.0.0                
2026-08-17T00:37:51.7393349Z   build-tools;36.1.0                 | 36.1.0        | Android SDK Build-Tools 36.1     | build-tools/36.1.0                
2026-08-17T00:37:51.7399999Z   build-tools;37.0.0                 | 37.0.0        | Android SDK Build-Tools 37       | build-tools/37.0.0                
2026-08-17T00:37:51.7413163Z   cmake;3.22.1                       | 3.22.1        | CMake 3.22.1                     | cmake/3.22.1                      
2026-08-17T00:37:51.7422471Z   cmake;3.31.5                       | 3.31.5        | CMake 3.31.5                     | cmake/3.31.5                      
2026-08-17T00:37:51.7430868Z   cmake;4.1.2                        | 4.1.2         | CMake 4.1.2                      | cmake/4.1.2                       
2026-08-17T00:37:51.7435940Z   extras;android;m2repository        | 47.0.0        | Android Support Repository       | extras/android/m2repository       
2026-08-17T00:37:51.7440041Z   extras;google;google_play_services | 49            | Google Play services             | extras/google/google_play_services
2026-08-17T00:37:51.7446583Z   extras;google;m2repository         | 58            | Google Repository                | extras/google/m2repository        
2026-08-17T00:37:51.7448243Z   ndk;25.2.9519653                   | 25.2.9519653  | NDK (Side by side) 25.2.9519653  | ndk/25.2.9519653                  
2026-08-17T00:37:51.7451968Z   ndk;27.3.13750724                  | 27.3.13750724 | NDK (Side by side) 27.3.13750724 | ndk/27.3.13750724                 
2026-08-17T00:37:51.7455821Z   ndk;28.2.13676358                  | 28.2.13676358 | NDK (Side by side) 28.2.13676358 | ndk/28.2.13676358                 
2026-08-17T00:37:51.7459842Z   ndk;29.0.14206865                  | 29.0.14206865 | NDK (Side by side) 29.0.14206865 | ndk/29.0.14206865                 
2026-08-17T00:37:51.7465111Z   platform-tools                     | 37.0.1        | Android SDK Platform-Tools       | platform-tools                    
2026-08-17T00:37:51.7469475Z   platforms;android-34               | 3             | Android SDK Platform 34          | platforms/android-34              
2026-08-17T00:37:51.7473083Z   platforms;android-34-ext10         | 1             | Android SDK Platform 34-ext10    | platforms/android-34-ext10        
2026-08-17T00:37:51.7476557Z   platforms;android-34-ext11         | 1             | Android SDK Platform 34-ext11    | platforms/android-34-ext11        
2026-08-17T00:37:51.7480423Z   platforms;android-34-ext12         | 1             | Android SDK Platform 34-ext12    | platforms/android-34-ext12        
2026-08-17T00:37:51.7483980Z   platforms;android-34-ext8          | 1             | Android SDK Platform 34-ext8     | platforms/android-34-ext8         
2026-08-17T00:37:51.7487951Z   platforms;android-35               | 2             | Android SDK Platform 35          | platforms/android-35              
2026-08-17T00:37:51.7492325Z   platforms;android-35-ext14         | 1             | Android SDK Platform 35-ext14    | platforms/android-35-ext14        
2026-08-17T00:37:51.7495242Z   platforms;android-35-ext15         | 1             | Android SDK Platform 35-ext15    | platforms/android-35-ext15        
2026-08-17T00:37:51.7498804Z   platforms;android-36               | 2             | Android SDK Platform 36          | platforms/android-36              
2026-08-17T00:37:51.7501052Z   platforms;android-36-ext18         | 1             | Android SDK Platform 36-ext18    | platforms/android-36-ext18        
2026-08-17T00:37:51.7503345Z   platforms;android-36-ext19         | 1             | Android SDK Platform 36-ext19    | platforms/android-36-ext19        
2026-08-17T00:37:51.7506185Z   platforms;android-36.1             | 1             | Android SDK Platform 36.1        | platforms/android-36.1            
2026-08-17T00:37:51.7509041Z   platforms;android-37.0             | 2             | Android SDK Platform 37.0        | platforms/android-37.0            
2026-08-17T00:37:51.7512134Z   platforms;android-37.1             | 1             | Android SDK Platform 37.1        | platforms/android-37.1            
2026-08-17T00:37:51.7514802Z   platforms;android-37.2-beta1       | 1             | Android SDK Platform 37.2-beta1  | platforms/android-37.2-beta1      
2026-08-17T00:37:51.7517212Z   platforms;android-37.2-beta2       | 2             | Android SDK Platform 37.2-beta2  | platforms/android-37.2-beta2      
2026-08-17T00:37:51.7525887Z 
2026-08-17T00:37:51.7674895Z ##[group]Run if [ -f "gradle/wrapper/gradle-wrapper.jar" ]; then
2026-08-17T00:37:51.7675780Z [36;1mif [ -f "gradle/wrapper/gradle-wrapper.jar" ]; then[0m
2026-08-17T00:37:51.7676595Z [36;1m  ./gradlew assembleDebug --stacktrace --no-daemon[0m
2026-08-17T00:37:51.7677240Z [36;1melse[0m
2026-08-17T00:37:51.7677814Z [36;1m  echo "⚠️ wrapper jar missing, using gradle directly"[0m
2026-08-17T00:37:51.7678598Z [36;1m  gradle assembleDebug --stacktrace --no-daemon[0m
2026-08-17T00:37:51.7679424Z [36;1mfi[0m
2026-08-17T00:37:51.7737963Z shell: /usr/bin/bash --noprofile --norc -e -o pipefail {0}
2026-08-17T00:37:51.7738447Z env:
2026-08-17T00:37:51.7739052Z   GRADLE_VERSION: 8.5
2026-08-17T00:37:51.7739376Z   JAVA_VERSION: 17
2026-08-17T00:37:51.7739814Z   JAVA_HOME: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T00:37:51.7740448Z   JAVA_HOME_17_X64: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T00:37:51.7741076Z   GRADLE_ACTION_ID: gradle/actions/setup-gradle
2026-08-17T00:37:51.7741492Z   GRADLE_USER_HOME: /home/runner/.gradle
2026-08-17T00:37:51.7741878Z   GRADLE_BUILD_ACTION_SETUP_COMPLETED: true
2026-08-17T00:37:51.7742303Z   GRADLE_BUILD_ACTION_CACHE_RESTORED: true
2026-08-17T00:37:51.7742907Z   DEVELOCITY_INJECTION_INIT_SCRIPT_NAME: gradle-actions.inject-develocity.init.gradle
2026-08-17T00:37:51.7743501Z   DEVELOCITY_INJECTION_CUSTOM_VALUE: gradle-actions
2026-08-17T00:37:51.7743924Z   GITHUB_DEPENDENCY_GRAPH_ENABLED: false
2026-08-17T00:37:51.7744315Z   ANDROID_HOME: /usr/local/lib/android/sdk
2026-08-17T00:37:51.7744715Z   ANDROID_SDK_ROOT: /usr/local/lib/android/sdk
2026-08-17T00:37:51.7745099Z ##[endgroup]
2026-08-17T00:37:52.3835247Z To honour the JVM settings for this build a single-use Daemon process will be forked. For more on this, please refer to https://docs.gradle.org/8.5/userguide/gradle_daemon.html#sec:disabling_the_daemon in the Gradle documentation.
2026-08-17T00:37:53.3818318Z Daemon will be stopped at the end of the build 
2026-08-17T00:38:00.7821532Z > Task :app:preBuild UP-TO-DATE
2026-08-17T00:38:00.7822662Z > Task :app:preDebugBuild UP-TO-DATE
2026-08-17T00:38:00.7823611Z > Task :app:mergeDebugNativeDebugMetadata NO-SOURCE
2026-08-17T00:38:00.7870190Z > Task :app:checkKotlinGradlePluginConfigurationErrors
2026-08-17T00:38:01.5830324Z > Task :app:generateDebugResValues
2026-08-17T00:38:01.5839861Z > Task :app:dataBindingMergeDependencyArtifactsDebug
2026-08-17T00:38:01.5862180Z > Task :app:generateDebugResources
2026-08-17T00:38:03.9860292Z > Task :app:packageDebugResources
2026-08-17T00:38:05.1801497Z > Task :app:parseDebugLocalResources
2026-08-17T00:38:05.1849743Z > Task :app:mergeDebugResources
2026-08-17T00:38:05.2820442Z > Task :app:checkDebugAarMetadata
2026-08-17T00:38:05.4820846Z > Task :app:dataBindingGenBaseClassesDebug
2026-08-17T00:38:05.4840486Z > Task :app:mapDebugSourceSetPaths
2026-08-17T00:38:05.5799635Z > Task :app:createDebugCompatibleScreenManifests
2026-08-17T00:38:05.5809963Z > Task :app:extractDeepLinksDebug
2026-08-17T00:38:05.7810563Z > Task :app:processDebugMainManifest
2026-08-17T00:38:05.8813361Z > Task :app:processDebugManifest
2026-08-17T00:38:05.9806440Z > Task :app:javaPreCompileDebug
2026-08-17T00:38:05.9820926Z > Task :app:mergeDebugShaders
2026-08-17T00:38:05.9822860Z > Task :app:compileDebugShaders NO-SOURCE
2026-08-17T00:38:05.9829651Z > Task :app:generateDebugAssets UP-TO-DATE
2026-08-17T00:38:06.0802076Z > Task :app:mergeDebugAssets
2026-08-17T00:38:06.0803373Z > Task :app:processDebugManifestForPackage
2026-08-17T00:38:06.3824895Z > Task :app:compressDebugAssets
2026-08-17T00:38:06.3825982Z > Task :app:desugarDebugFileDependencies
2026-08-17T00:38:06.4840333Z > Task :app:checkDebugDuplicateClasses
2026-08-17T00:38:07.1837692Z 
2026-08-17T00:38:07.1870427Z > Task :app:configureCMakeDebug[arm64-v8a]
2026-08-17T00:38:07.1901485Z [CXX5304] This version only understands SDK XML versions up to 3 but an SDK XML file of version 4 was encountered. This can happen if you use versions of Android Studio and the command-line tools that were released at different times.
2026-08-17T00:38:07.1904963Z [CXX5304] This version only understands SDK XML versions up to 3 but an SDK XML file of version 4 was encountered. This can happen if you use versions of Android Studio and the command-line tools that were released at different times.
2026-08-17T00:38:07.3803260Z 
2026-08-17T00:38:07.3840355Z > Task :app:mergeLibDexDebug
2026-08-17T00:38:07.4814598Z > Task :app:processDebugResources
2026-08-17T00:38:07.9821099Z > Task :app:buildCMakeDebug[arm64-v8a]
2026-08-17T00:38:09.1826658Z > Task :app:configureCMakeDebug[x86_64]
2026-08-17T00:38:10.1802728Z > Task :app:buildCMakeDebug[x86_64]
2026-08-17T00:38:10.1841957Z > Task :app:mergeDebugJniLibFolders
2026-08-17T00:38:10.5800034Z > Task :app:mergeDebugNativeLibs
2026-08-17T00:38:12.0824379Z > Task :app:validateSigningDebug
2026-08-17T00:38:12.1810576Z > Task :app:writeDebugAppMetadata
2026-08-17T00:38:12.1860271Z > Task :app:writeDebugSigningConfigVersions
2026-08-17T00:38:12.3830438Z > Task :app:stripDebugDebugSymbols
2026-08-17T00:38:23.6827119Z > Task :app:mergeExtDexDebug
2026-08-17T00:38:29.1819438Z 
2026-08-17T00:38:29.1826901Z > Task :app:compileDebugKotlin FAILED
2026-08-17T00:38:29.1850187Z e: file:///home/runner/work/AutoBOT/AutoBOT/app/src/main/java/com/autobot/app/ui/home/HomeFragment.kt:62:13 Unresolved reference: isShowText
2026-08-17T00:38:29.1852267Z e: file:///home/runner/work/AutoBOT/AutoBOT/app/src/main/java/com/autobot/app/ui/settings/SettingsFragment.kt:45:13 Unresolved reference: isShowText
2026-08-17T00:38:29.1904481Z e: file:///home/runner/work/AutoBOT/AutoBOT/app/src/main/java/com/autobot/app/ui/tasks/MonitorViewModel.kt:12:30 Unresolved reference: TaskMode
2026-08-17T00:38:29.1910608Z e: file:///home/runner/work/AutoBOT/AutoBOT/app/src/main/java/com/autobot/app/ui/tasks/MonitorViewModel.kt:44:15 Conflicting declarations: public companion object, public companion object
2026-08-17T00:38:29.1940488Z e: file:///home/runner/work/AutoBOT/AutoBOT/app/src/main/java/com/autobot/app/ui/tasks/MonitorViewModel.kt:124:5 Only one companion object is allowed per class
2026-08-17T00:38:29.1963334Z e: file:///home/runner/work/AutoBOT/AutoBOT/app/src/main/java/com/autobot/app/ui/tasks/MonitorViewModel.kt:124:15 Conflicting declarations: public companion object, public companion object
2026-08-17T00:38:29.2021241Z e: file:///home/runner/work/AutoBOT/AutoBOT/app/src/main/java/com/autobot/app/ui/tasks/MonitorViewModel.kt:157:32 Unresolved reference: LOG_MAX_LINES
2026-08-17T00:38:29.2820917Z gradle/actions: Writing build results to /home/runner/work/_temp/.gradle-actions/build-results/__run_4-1786927074939.json
2026-08-17T00:38:29.3797290Z 
2026-08-17T00:38:29.3798408Z FAILURE: Build failed with an exception.
2026-08-17T00:38:29.3799325Z 
2026-08-17T00:38:29.3812399Z * What went wrong:
2026-08-17T00:38:29.3813100Z Execution failed for task ':app:compileDebugKotlin'.
2026-08-17T00:38:29.3814571Z > A failure occurred while executing org.jetbrains.kotlin.compilerRunner.GradleCompilerRunnerWithWorkers$GradleKotlinCompilerWorkAction
2026-08-17T00:38:29.3815446Z    > Compilation error. See log for more details
2026-08-17T00:38:29.3815718Z 
2026-08-17T00:38:29.3815847Z * Try:
2026-08-17T00:38:29.3816277Z > Run with --info or --debug option to get more log output.
2026-08-17T00:38:29.3816756Z > Run with --scan to get full insights.
2026-08-17T00:38:29.3817222Z > Get more help at https://help.gradle.org.
2026-08-17T00:38:29.3817503Z 
2026-08-17T00:38:29.3817657Z * Exception is:
2026-08-17T00:38:29.3818396Z org.gradle.api.tasks.TaskExecutionException: Execution failed for task ':app:compileDebugKotlin'.
2026-08-17T00:38:29.3820434Z 	at org.gradle.api.internal.tasks.execution.ExecuteActionsTaskExecuter.lambda$executeIfValid$1(ExecuteActionsTaskExecuter.java:148)
2026-08-17T00:38:29.3838298Z 	at org.gradle.internal.Try$Failure.ifSuccessfulOrElse(Try.java:282)
2026-08-17T00:38:29.3840243Z 	at org.gradle.api.internal.tasks.execution.ExecuteActionsTaskExecuter.executeIfValid(ExecuteActionsTaskExecuter.java:146)
2026-08-17T00:38:29.3842043Z 	at org.gradle.api.internal.tasks.execution.ExecuteActionsTaskExecuter.execute(ExecuteActionsTaskExecuter.java:134)
2026-08-17T00:38:29.3843963Z 	at org.gradle.api.internal.tasks.execution.FinalizePropertiesTaskExecuter.execute(FinalizePropertiesTaskExecuter.java:46)
2026-08-17T00:38:29.3846042Z 	at org.gradle.api.internal.tasks.execution.ResolveTaskExecutionModeExecuter.execute(ResolveTaskExecutionModeExecuter.java:51)
2026-08-17T00:38:29.3847615Z 	at org.gradle.api.internal.tasks.execution.SkipTaskWithNoActionsExecuter.execute(SkipTaskWithNoActionsExecuter.java:57)
2026-08-17T00:38:29.3850572Z 	at org.gradle.api.internal.tasks.execution.SkipOnlyIfTaskExecuter.execute(SkipOnlyIfTaskExecuter.java:74)
2026-08-17T00:38:29.3851938Z 	at org.gradle.api.internal.tasks.execution.CatchExceptionTaskExecuter.execute(CatchExceptionTaskExecuter.java:36)
2026-08-17T00:38:29.3853083Z 	at org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter$1.executeTask(EventFiringTaskExecuter.java:77)
2026-08-17T00:38:29.3854114Z 	at org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter$1.call(EventFiringTaskExecuter.java:55)
2026-08-17T00:38:29.3855102Z 	at org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter$1.call(EventFiringTaskExecuter.java:52)
2026-08-17T00:38:29.3856280Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$CallableBuildOperationWorker.execute(DefaultBuildOperationRunner.java:204)
2026-08-17T00:38:29.3857600Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$CallableBuildOperationWorker.execute(DefaultBuildOperationRunner.java:199)
2026-08-17T00:38:29.3859009Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$2.execute(DefaultBuildOperationRunner.java:66)
2026-08-17T00:38:29.3861530Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$2.execute(DefaultBuildOperationRunner.java:59)
2026-08-17T00:38:29.3863830Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:157)
2026-08-17T00:38:29.3865633Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:59)
2026-08-17T00:38:29.3867425Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.call(DefaultBuildOperationRunner.java:53)
2026-08-17T00:38:29.3870210Z 	at org.gradle.internal.operations.DefaultBuildOperationExecutor.call(DefaultBuildOperationExecutor.java:73)
2026-08-17T00:38:29.3872080Z 	at org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter.execute(EventFiringTaskExecuter.java:52)
2026-08-17T00:38:29.3873733Z 	at org.gradle.execution.plan.LocalTaskNodeExecutor.execute(LocalTaskNodeExecutor.java:42)
2026-08-17T00:38:29.3875563Z 	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$InvokeNodeExecutorsAction.execute(DefaultTaskExecutionGraph.java:331)
2026-08-17T00:38:29.3877750Z 	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$InvokeNodeExecutorsAction.execute(DefaultTaskExecutionGraph.java:318)
2026-08-17T00:38:29.3880336Z 	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$BuildOperationAwareExecutionAction.lambda$execute$0(DefaultTaskExecutionGraph.java:314)
2026-08-17T00:38:29.3882330Z 	at org.gradle.internal.operations.CurrentBuildOperationRef.with(CurrentBuildOperationRef.java:80)
2026-08-17T00:38:29.3884355Z 	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$BuildOperationAwareExecutionAction.execute(DefaultTaskExecutionGraph.java:314)
2026-08-17T00:38:29.3886628Z 	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$BuildOperationAwareExecutionAction.execute(DefaultTaskExecutionGraph.java:303)
2026-08-17T00:38:29.3888524Z 	at org.gradle.execution.plan.DefaultPlanExecutor$ExecutorWorker.execute(DefaultPlanExecutor.java:463)
2026-08-17T00:38:29.3890701Z 	at org.gradle.execution.plan.DefaultPlanExecutor$ExecutorWorker.run(DefaultPlanExecutor.java:380)
2026-08-17T00:38:29.3892565Z 	at org.gradle.internal.concurrent.ExecutorPolicy$CatchAndRecordFailures.onExecute(ExecutorPolicy.java:64)
2026-08-17T00:38:29.3894163Z 	at org.gradle.internal.concurrent.AbstractManagedExecutor$1.run(AbstractManagedExecutor.java:47)
2026-08-17T00:38:29.3896799Z Caused by: org.gradle.workers.internal.DefaultWorkerExecutor$WorkExecutionException: A failure occurred while executing org.jetbrains.kotlin.compilerRunner.GradleCompilerRunnerWithWorkers$GradleKotlinCompilerWorkAction
2026-08-17T00:38:29.3899592Z 	at org.gradle.workers.internal.DefaultWorkerExecutor$WorkItemExecution.waitForCompletion(DefaultWorkerExecutor.java:283)
2026-08-17T00:38:29.3901558Z 	at org.gradle.internal.work.DefaultAsyncWorkTracker.lambda$waitForItemsAndGatherFailures$2(DefaultAsyncWorkTracker.java:130)
2026-08-17T00:38:29.3902972Z 	at org.gradle.internal.Factories$1.create(Factories.java:31)
2026-08-17T00:38:29.3904326Z 	at org.gradle.internal.work.DefaultWorkerLeaseService.withoutLocks(DefaultWorkerLeaseService.java:336)
2026-08-17T00:38:29.3906026Z 	at org.gradle.internal.work.DefaultWorkerLeaseService.withoutLocks(DefaultWorkerLeaseService.java:319)
2026-08-17T00:38:29.3907696Z 	at org.gradle.internal.work.DefaultWorkerLeaseService.withoutLock(DefaultWorkerLeaseService.java:324)
2026-08-17T00:38:29.3910962Z 	at org.gradle.internal.work.DefaultAsyncWorkTracker.waitForItemsAndGatherFailures(DefaultAsyncWorkTracker.java:126)
2026-08-17T00:38:29.3913016Z 	at org.gradle.internal.work.DefaultAsyncWorkTracker.waitForItemsAndGatherFailures(DefaultAsyncWorkTracker.java:92)
2026-08-17T00:38:29.3914779Z 	at org.gradle.internal.work.DefaultAsyncWorkTracker.waitForAll(DefaultAsyncWorkTracker.java:78)
2026-08-17T00:38:29.3916455Z 	at org.gradle.internal.work.DefaultAsyncWorkTracker.waitForCompletion(DefaultAsyncWorkTracker.java:66)
2026-08-17T00:38:29.3918002Z 	at org.gradle.api.internal.tasks.execution.TaskExecution$3.run(TaskExecution.java:256)
2026-08-17T00:38:29.3921253Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$1.execute(DefaultBuildOperationRunner.java:29)
2026-08-17T00:38:29.3923452Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$1.execute(DefaultBuildOperationRunner.java:26)
2026-08-17T00:38:29.3925246Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$2.execute(DefaultBuildOperationRunner.java:66)
2026-08-17T00:38:29.3927015Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$2.execute(DefaultBuildOperationRunner.java:59)
2026-08-17T00:38:29.3929235Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:157)
2026-08-17T00:38:29.3931076Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:59)
2026-08-17T00:38:29.3932846Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.run(DefaultBuildOperationRunner.java:47)
2026-08-17T00:38:29.3934595Z 	at org.gradle.internal.operations.DefaultBuildOperationExecutor.run(DefaultBuildOperationExecutor.java:68)
2026-08-17T00:38:29.3936271Z 	at org.gradle.api.internal.tasks.execution.TaskExecution.executeAction(TaskExecution.java:233)
2026-08-17T00:38:29.3937882Z 	at org.gradle.api.internal.tasks.execution.TaskExecution.executeActions(TaskExecution.java:216)
2026-08-17T00:38:29.3977293Z 	at org.gradle.api.internal.tasks.execution.TaskExecution.executeWithPreviousOutputFiles(TaskExecution.java:199)
2026-08-17T00:38:29.3979304Z 	at org.gradle.api.internal.tasks.execution.TaskExecution.execute(TaskExecution.java:166)
2026-08-17T00:38:29.3980786Z 	at org.gradle.internal.execution.steps.ExecuteStep.executeInternal(ExecuteStep.java:105)
2026-08-17T00:38:29.3982195Z 	at org.gradle.internal.execution.steps.ExecuteStep.access$000(ExecuteStep.java:44)
2026-08-17T00:38:29.3983454Z 	at org.gradle.internal.execution.steps.ExecuteStep$1.call(ExecuteStep.java:59)
2026-08-17T00:38:29.3984688Z 	at org.gradle.internal.execution.steps.ExecuteStep$1.call(ExecuteStep.java:56)
2026-08-17T00:38:29.3986530Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$CallableBuildOperationWorker.execute(DefaultBuildOperationRunner.java:204)
2026-08-17T00:38:29.3989568Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$CallableBuildOperationWorker.execute(DefaultBuildOperationRunner.java:199)
2026-08-17T00:38:29.3991672Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$2.execute(DefaultBuildOperationRunner.java:66)
2026-08-17T00:38:29.3993472Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$2.execute(DefaultBuildOperationRunner.java:59)
2026-08-17T00:38:29.3995290Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:157)
2026-08-17T00:38:29.3997072Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:59)
2026-08-17T00:38:29.3999095Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.call(DefaultBuildOperationRunner.java:53)
2026-08-17T00:38:29.4000807Z 	at org.gradle.internal.operations.DefaultBuildOperationExecutor.call(DefaultBuildOperationExecutor.java:73)
2026-08-17T00:38:29.4002499Z 	at org.gradle.internal.execution.steps.ExecuteStep.execute(ExecuteStep.java:56)
2026-08-17T00:38:29.4003724Z 	at org.gradle.internal.execution.steps.ExecuteStep.execute(ExecuteStep.java:44)
2026-08-17T00:38:29.4005255Z 	at org.gradle.internal.execution.steps.RemovePreviousOutputsStep.execute(RemovePreviousOutputsStep.java:67)
2026-08-17T00:38:29.4006989Z 	at org.gradle.internal.execution.steps.RemovePreviousOutputsStep.execute(RemovePreviousOutputsStep.java:37)
2026-08-17T00:38:29.4008580Z 	at org.gradle.internal.execution.steps.CancelExecutionStep.execute(CancelExecutionStep.java:41)
2026-08-17T00:38:29.4012202Z 	at org.gradle.internal.execution.steps.TimeoutStep.executeWithoutTimeout(TimeoutStep.java:74)
2026-08-17T00:38:29.4013441Z 	at org.gradle.internal.execution.steps.TimeoutStep.execute(TimeoutStep.java:55)
2026-08-17T00:38:29.4014692Z 	at org.gradle.internal.execution.steps.CreateOutputsStep.execute(CreateOutputsStep.java:50)
2026-08-17T00:38:29.4016354Z 	at org.gradle.internal.execution.steps.CreateOutputsStep.execute(CreateOutputsStep.java:28)
2026-08-17T00:38:29.4018423Z 	at org.gradle.internal.execution.steps.CaptureStateAfterExecutionStep.executeDelegateBroadcastingChanges(CaptureStateAfterExecutionStep.java:100)
2026-08-17T00:38:29.4021100Z 	at org.gradle.internal.execution.steps.CaptureStateAfterExecutionStep.execute(CaptureStateAfterExecutionStep.java:72)
2026-08-17T00:38:29.4023134Z 	at org.gradle.internal.execution.steps.CaptureStateAfterExecutionStep.execute(CaptureStateAfterExecutionStep.java:50)
2026-08-17T00:38:29.4024988Z 	at org.gradle.internal.execution.steps.ResolveInputChangesStep.execute(ResolveInputChangesStep.java:40)
2026-08-17T00:38:29.4026711Z 	at org.gradle.internal.execution.steps.ResolveInputChangesStep.execute(ResolveInputChangesStep.java:29)
2026-08-17T00:38:29.4028398Z 	at org.gradle.internal.execution.steps.BuildCacheStep.executeWithoutCache(BuildCacheStep.java:179)
2026-08-17T00:38:29.4030211Z 	at org.gradle.internal.execution.steps.BuildCacheStep.lambda$execute$1(BuildCacheStep.java:70)
2026-08-17T00:38:29.4031309Z 	at org.gradle.internal.Either$Right.fold(Either.java:175)
2026-08-17T00:38:29.4033390Z 	at org.gradle.internal.execution.caching.CachingState.fold(CachingState.java:59)
2026-08-17T00:38:29.4034657Z 	at org.gradle.internal.execution.steps.BuildCacheStep.execute(BuildCacheStep.java:68)
2026-08-17T00:38:29.4036044Z 	at org.gradle.internal.execution.steps.BuildCacheStep.execute(BuildCacheStep.java:46)
2026-08-17T00:38:29.4037621Z 	at org.gradle.internal.execution.steps.StoreExecutionStateStep.execute(StoreExecutionStateStep.java:36)
2026-08-17T00:38:29.4039567Z 	at org.gradle.internal.execution.steps.StoreExecutionStateStep.execute(StoreExecutionStateStep.java:25)
2026-08-17T00:38:29.4041158Z 	at org.gradle.internal.execution.steps.RecordOutputsStep.execute(RecordOutputsStep.java:36)
2026-08-17T00:38:29.4042636Z 	at org.gradle.internal.execution.steps.RecordOutputsStep.execute(RecordOutputsStep.java:22)
2026-08-17T00:38:29.4044457Z 	at org.gradle.internal.execution.steps.SkipUpToDateStep.executeBecause(SkipUpToDateStep.java:91)
2026-08-17T00:38:29.4046013Z 	at org.gradle.internal.execution.steps.SkipUpToDateStep.lambda$execute$2(SkipUpToDateStep.java:55)
2026-08-17T00:38:29.4047537Z 	at org.gradle.internal.execution.steps.SkipUpToDateStep.execute(SkipUpToDateStep.java:55)
2026-08-17T00:38:29.4049230Z 	at org.gradle.internal.execution.steps.SkipUpToDateStep.execute(SkipUpToDateStep.java:37)
2026-08-17T00:38:29.4050720Z 	at org.gradle.internal.execution.steps.ResolveChangesStep.execute(ResolveChangesStep.java:65)
2026-08-17T00:38:29.4052155Z 	at org.gradle.internal.execution.steps.ResolveChangesStep.execute(ResolveChangesStep.java:36)
2026-08-17T00:38:29.4054109Z 	at org.gradle.internal.execution.steps.legacy.MarkSnapshottingInputsFinishedStep.execute(MarkSnapshottingInputsFinishedStep.java:37)
2026-08-17T00:38:29.4056374Z 	at org.gradle.internal.execution.steps.legacy.MarkSnapshottingInputsFinishedStep.execute(MarkSnapshottingInputsFinishedStep.java:27)
2026-08-17T00:38:29.4073427Z 	at org.gradle.internal.execution.steps.ResolveCachingStateStep.execute(ResolveCachingStateStep.java:76)
2026-08-17T00:38:29.4075194Z 	at org.gradle.internal.execution.steps.ResolveCachingStateStep.execute(ResolveCachingStateStep.java:37)
2026-08-17T00:38:29.4076731Z 	at org.gradle.internal.execution.steps.ValidateStep.execute(ValidateStep.java:108)
2026-08-17T00:38:29.4078096Z 	at org.gradle.internal.execution.steps.ValidateStep.execute(ValidateStep.java:55)
2026-08-17T00:38:29.4080048Z 	at org.gradle.internal.execution.steps.CaptureStateBeforeExecutionStep.execute(CaptureStateBeforeExecutionStep.java:71)
2026-08-17T00:38:29.4082099Z 	at org.gradle.internal.execution.steps.CaptureStateBeforeExecutionStep.execute(CaptureStateBeforeExecutionStep.java:45)
2026-08-17T00:38:29.4084060Z 	at org.gradle.internal.execution.steps.SkipEmptyWorkStep.executeWithNonEmptySources(SkipEmptyWorkStep.java:177)
2026-08-17T00:38:29.4085794Z 	at org.gradle.internal.execution.steps.SkipEmptyWorkStep.execute(SkipEmptyWorkStep.java:86)
2026-08-17T00:38:29.4087623Z 	at org.gradle.internal.execution.steps.SkipEmptyWorkStep.execute(SkipEmptyWorkStep.java:53)
2026-08-17T00:38:29.4089938Z 	at org.gradle.internal.execution.steps.RemoveUntrackedExecutionStateStep.execute(RemoveUntrackedExecutionStateStep.java:32)
2026-08-17T00:38:29.4092059Z 	at org.gradle.internal.execution.steps.RemoveUntrackedExecutionStateStep.execute(RemoveUntrackedExecutionStateStep.java:21)
2026-08-17T00:38:29.4094279Z 	at org.gradle.internal.execution.steps.legacy.MarkSnapshottingInputsStartedStep.execute(MarkSnapshottingInputsStartedStep.java:38)
2026-08-17T00:38:29.4096433Z 	at org.gradle.internal.execution.steps.LoadPreviousExecutionStateStep.execute(LoadPreviousExecutionStateStep.java:36)
2026-08-17T00:38:29.4098464Z 	at org.gradle.internal.execution.steps.LoadPreviousExecutionStateStep.execute(LoadPreviousExecutionStateStep.java:23)
2026-08-17T00:38:29.4100525Z 	at org.gradle.internal.execution.steps.CleanupStaleOutputsStep.execute(CleanupStaleOutputsStep.java:75)
2026-08-17T00:38:29.4102344Z 	at org.gradle.internal.execution.steps.CleanupStaleOutputsStep.execute(CleanupStaleOutputsStep.java:41)
2026-08-17T00:38:29.4104393Z 	at org.gradle.internal.execution.steps.ExecuteWorkBuildOperationFiringStep.lambda$execute$2(ExecuteWorkBuildOperationFiringStep.java:66)
2026-08-17T00:38:29.4106644Z 	at org.gradle.internal.execution.steps.ExecuteWorkBuildOperationFiringStep.execute(ExecuteWorkBuildOperationFiringStep.java:66)
2026-08-17T00:38:29.4109014Z 	at org.gradle.internal.execution.steps.ExecuteWorkBuildOperationFiringStep.execute(ExecuteWorkBuildOperationFiringStep.java:38)
2026-08-17T00:38:29.4110971Z 	at org.gradle.internal.execution.steps.AssignWorkspaceStep.lambda$execute$0(AssignWorkspaceStep.java:32)
2026-08-17T00:38:29.4112616Z 	at org.gradle.api.internal.tasks.execution.TaskExecution$4.withWorkspace(TaskExecution.java:293)
2026-08-17T00:38:29.4114231Z 	at org.gradle.internal.execution.steps.AssignWorkspaceStep.execute(AssignWorkspaceStep.java:30)
2026-08-17T00:38:29.4116103Z 	at org.gradle.internal.execution.steps.AssignWorkspaceStep.execute(AssignWorkspaceStep.java:21)
2026-08-17T00:38:29.4117691Z 	at org.gradle.internal.execution.steps.IdentityCacheStep.execute(IdentityCacheStep.java:37)
2026-08-17T00:38:29.4119362Z 	at org.gradle.internal.execution.steps.IdentityCacheStep.execute(IdentityCacheStep.java:27)
2026-08-17T00:38:29.4120768Z 	at org.gradle.internal.execution.steps.IdentifyStep.execute(IdentifyStep.java:47)
2026-08-17T00:38:29.4122117Z 	at org.gradle.internal.execution.steps.IdentifyStep.execute(IdentifyStep.java:34)
2026-08-17T00:38:29.4123675Z 	at org.gradle.internal.execution.impl.DefaultExecutionEngine$1.execute(DefaultExecutionEngine.java:64)
2026-08-17T00:38:29.4125632Z 	at org.gradle.api.internal.tasks.execution.ExecuteActionsTaskExecuter.executeIfValid(ExecuteActionsTaskExecuter.java:145)
2026-08-17T00:38:29.4127636Z 	at org.gradle.api.internal.tasks.execution.ExecuteActionsTaskExecuter.execute(ExecuteActionsTaskExecuter.java:134)
2026-08-17T00:38:29.4130006Z 	at org.gradle.api.internal.tasks.execution.FinalizePropertiesTaskExecuter.execute(FinalizePropertiesTaskExecuter.java:46)
2026-08-17T00:38:29.4132123Z 	at org.gradle.api.internal.tasks.execution.ResolveTaskExecutionModeExecuter.execute(ResolveTaskExecutionModeExecuter.java:51)
2026-08-17T00:38:29.4134172Z 	at org.gradle.api.internal.tasks.execution.SkipTaskWithNoActionsExecuter.execute(SkipTaskWithNoActionsExecuter.java:57)
2026-08-17T00:38:29.4136076Z 	at org.gradle.api.internal.tasks.execution.SkipOnlyIfTaskExecuter.execute(SkipOnlyIfTaskExecuter.java:74)
2026-08-17T00:38:29.4137977Z 	at org.gradle.api.internal.tasks.execution.CatchExceptionTaskExecuter.execute(CatchExceptionTaskExecuter.java:36)
2026-08-17T00:38:29.4140095Z 	at org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter$1.executeTask(EventFiringTaskExecuter.java:77)
2026-08-17T00:38:29.4141907Z 	at org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter$1.call(EventFiringTaskExecuter.java:55)
2026-08-17T00:38:29.4144356Z 	at org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter$1.call(EventFiringTaskExecuter.java:52)
2026-08-17T00:38:29.4146403Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$CallableBuildOperationWorker.execute(DefaultBuildOperationRunner.java:204)
2026-08-17T00:38:29.4148858Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$CallableBuildOperationWorker.execute(DefaultBuildOperationRunner.java:199)
2026-08-17T00:38:29.4150920Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$2.execute(DefaultBuildOperationRunner.java:66)
2026-08-17T00:38:29.4152776Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$2.execute(DefaultBuildOperationRunner.java:59)
2026-08-17T00:38:29.4154584Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:157)
2026-08-17T00:38:29.4156388Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:59)
2026-08-17T00:38:29.4158176Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.call(DefaultBuildOperationRunner.java:53)
2026-08-17T00:38:29.4160093Z 	at org.gradle.internal.operations.DefaultBuildOperationExecutor.call(DefaultBuildOperationExecutor.java:73)
2026-08-17T00:38:29.4161898Z 	at org.gradle.api.internal.tasks.execution.EventFiringTaskExecuter.execute(EventFiringTaskExecuter.java:52)
2026-08-17T00:38:29.4163487Z 	at org.gradle.execution.plan.LocalTaskNodeExecutor.execute(LocalTaskNodeExecutor.java:42)
2026-08-17T00:38:29.4165347Z 	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$InvokeNodeExecutorsAction.execute(DefaultTaskExecutionGraph.java:331)
2026-08-17T00:38:29.4167529Z 	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$InvokeNodeExecutorsAction.execute(DefaultTaskExecutionGraph.java:318)
2026-08-17T00:38:29.4170112Z 	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$BuildOperationAwareExecutionAction.lambda$execute$0(DefaultTaskExecutionGraph.java:314)
2026-08-17T00:38:29.4172410Z 	at org.gradle.internal.operations.CurrentBuildOperationRef.with(CurrentBuildOperationRef.java:80)
2026-08-17T00:38:29.4174468Z 	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$BuildOperationAwareExecutionAction.execute(DefaultTaskExecutionGraph.java:314)
2026-08-17T00:38:29.4176835Z 	at org.gradle.execution.taskgraph.DefaultTaskExecutionGraph$BuildOperationAwareExecutionAction.execute(DefaultTaskExecutionGraph.java:303)
2026-08-17T00:38:29.4179010Z 	at org.gradle.execution.plan.DefaultPlanExecutor$ExecutorWorker.execute(DefaultPlanExecutor.java:463)
2026-08-17T00:38:29.4180631Z 	at org.gradle.execution.plan.DefaultPlanExecutor$ExecutorWorker.run(DefaultPlanExecutor.java:380)
2026-08-17T00:38:29.4182335Z 	at org.gradle.internal.concurrent.ExecutorPolicy$CatchAndRecordFailures.onExecute(ExecutorPolicy.java:64)
2026-08-17T00:38:29.4184006Z 	at org.gradle.internal.concurrent.AbstractManagedExecutor$1.run(AbstractManagedExecutor.java:47)
2026-08-17T00:38:29.4185747Z Caused by: org.jetbrains.kotlin.gradle.tasks.CompilationErrorException: Compilation error. See log for more details
2026-08-17T00:38:29.4187528Z 	at org.jetbrains.kotlin.gradle.tasks.TasksUtilsKt.throwExceptionIfCompilationFailed(tasksUtils.kt:20)
2026-08-17T00:38:29.4189421Z 	at org.jetbrains.kotlin.compilerRunner.GradleKotlinCompilerWork.run(GradleKotlinCompilerWork.kt:141)
2026-08-17T00:38:29.4191609Z 	at org.jetbrains.kotlin.compilerRunner.GradleCompilerRunnerWithWorkers$GradleKotlinCompilerWorkAction.execute(GradleCompilerRunnerWithWorkers.kt:73)
2026-08-17T00:38:29.4193512Z 	at org.gradle.workers.internal.DefaultWorkerServer.execute(DefaultWorkerServer.java:63)
2026-08-17T00:38:29.4195058Z 	at org.gradle.workers.internal.NoIsolationWorkerFactory$1$1.create(NoIsolationWorkerFactory.java:66)
2026-08-17T00:38:29.4196738Z 	at org.gradle.workers.internal.NoIsolationWorkerFactory$1$1.create(NoIsolationWorkerFactory.java:62)
2026-08-17T00:38:29.4198445Z 	at org.gradle.internal.classloader.ClassLoaderUtils.executeInClassloader(ClassLoaderUtils.java:100)
2026-08-17T00:38:29.4200634Z 	at org.gradle.workers.internal.NoIsolationWorkerFactory$1.lambda$execute$0(NoIsolationWorkerFactory.java:62)
2026-08-17T00:38:29.4202091Z 	at org.gradle.workers.internal.AbstractWorker$1.call(AbstractWorker.java:44)
2026-08-17T00:38:29.4203355Z 	at org.gradle.workers.internal.AbstractWorker$1.call(AbstractWorker.java:41)
2026-08-17T00:38:29.4205199Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$CallableBuildOperationWorker.execute(DefaultBuildOperationRunner.java:204)
2026-08-17T00:38:29.4207511Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$CallableBuildOperationWorker.execute(DefaultBuildOperationRunner.java:199)
2026-08-17T00:38:29.4209685Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$2.execute(DefaultBuildOperationRunner.java:66)
2026-08-17T00:38:29.4211412Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner$2.execute(DefaultBuildOperationRunner.java:59)
2026-08-17T00:38:29.4213274Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:157)
2026-08-17T00:38:29.4215088Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.execute(DefaultBuildOperationRunner.java:59)
2026-08-17T00:38:29.4216888Z 	at org.gradle.internal.operations.DefaultBuildOperationRunner.call(DefaultBuildOperationRunner.java:53)
2026-08-17T00:38:29.4218909Z 	at org.gradle.internal.operations.DefaultBuildOperationExecutor.call(DefaultBuildOperationExecutor.java:73)
2026-08-17T00:38:29.4220717Z 	at org.gradle.workers.internal.AbstractWorker.executeWrappedInBuildOperation(AbstractWorker.java:41)
2026-08-17T00:38:29.4222378Z 	at org.gradle.workers.internal.NoIsolationWorkerFactory$1.execute(NoIsolationWorkerFactory.java:59)
2026-08-17T00:38:29.4224042Z 	at org.gradle.workers.internal.DefaultWorkerExecutor.lambda$submitWork$0(DefaultWorkerExecutor.java:170)
2026-08-17T00:38:29.4226266Z 	at org.gradle.internal.work.DefaultConditionalExecutionQueue$ExecutionRunner.runExecution(DefaultConditionalExecutionQueue.java:187)
2026-08-17T00:38:29.4228427Z 	at org.gradle.internal.work.DefaultConditionalExecutionQueue$ExecutionRunner.access$700(DefaultConditionalExecutionQueue.java:120)
2026-08-17T00:38:29.4230649Z 	at org.gradle.internal.work.DefaultConditionalExecutionQueue$ExecutionRunner$1.run(DefaultConditionalExecutionQueue.java:162)
2026-08-17T00:38:29.4232087Z 	at org.gradle.internal.Factories$1.create(Factories.java:31)
2026-08-17T00:38:29.4233431Z 	at org.gradle.internal.work.DefaultWorkerLeaseService.withLocks(DefaultWorkerLeaseService.java:264)
2026-08-17T00:38:29.4235230Z 	at org.gradle.internal.work.DefaultWorkerLeaseService.runAsWorkerThread(DefaultWorkerLeaseService.java:128)
2026-08-17T00:38:29.4237090Z 	at org.gradle.internal.work.DefaultWorkerLeaseService.runAsWorkerThread(DefaultWorkerLeaseService.java:133)
2026-08-17T00:38:29.4239233Z 	at org.gradle.internal.work.DefaultConditionalExecutionQueue$ExecutionRunner.runBatch(DefaultConditionalExecutionQueue.java:157)
2026-08-17T00:38:29.4241316Z 	at org.gradle.internal.work.DefaultConditionalExecutionQueue$ExecutionRunner.run(DefaultConditionalExecutionQueue.java:126)
2026-08-17T00:38:29.4242514Z 	... 2 more
2026-08-17T00:38:29.4242755Z 
2026-08-17T00:38:29.4242767Z 
2026-08-17T00:38:29.4243012Z BUILD FAILED in 37s
2026-08-17T00:38:29.4243597Z 34 actionable tasks: 34 executed
2026-08-17T00:38:29.7881334Z ##[error]Process completed with exit code 1.
2026-08-17T00:38:29.7950781Z Node 20 is being deprecated. This workflow is running with Node 24 by default. If you need to temporarily use Node 20, you can set the ACTIONS_ALLOW_USE_UNSECURE_NODE_VERSION=true environment variable. For more information see: https://github.blog/changelog/2025-09-19-deprecation-of-node-20-on-github-actions-runners/
2026-08-17T00:38:29.7952062Z ##[group]Run actions/upload-artifact@v4
2026-08-17T00:38:29.7952396Z with:
2026-08-17T00:38:29.7952639Z   name: build-logs
2026-08-17T00:38:29.7953177Z   path: app/build/reports/**
app/build/outputs/logs/**
**/*.log

2026-08-17T00:38:29.7953580Z   if-no-files-found: ignore
2026-08-17T00:38:29.7953867Z   retention-days: 7
2026-08-17T00:38:29.7954133Z   compression-level: 6
2026-08-17T00:38:29.7954400Z   overwrite: false
2026-08-17T00:38:29.7954663Z   include-hidden-files: false
2026-08-17T00:38:29.7954951Z env:
2026-08-17T00:38:29.7955185Z   GRADLE_VERSION: 8.5
2026-08-17T00:38:29.7955444Z   JAVA_VERSION: 17
2026-08-17T00:38:29.7955842Z   JAVA_HOME: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T00:38:29.7956388Z   JAVA_HOME_17_X64: /opt/hostedtoolcache/Java_Temurin-Hotspot_jdk/17.0.20-8/x64
2026-08-17T00:38:29.7956861Z   GRADLE_ACTION_ID: gradle/actions/setup-gradle
2026-08-17T00:38:29.7957206Z   GRADLE_USER_HOME: /home/runner/.gradle
2026-08-17T00:38:29.7957542Z   GRADLE_BUILD_ACTION_SETUP_COMPLETED: true
2026-08-17T00:38:29.7957895Z   GRADLE_BUILD_ACTION_CACHE_RESTORED: true
2026-08-17T00:38:29.7958384Z   DEVELOCITY_INJECTION_INIT_SCRIPT_NAME: gradle-actions.inject-develocity.init.gradle
2026-08-17T00:38:29.7959153Z   DEVELOCITY_INJECTION_CUSTOM_VALUE: gradle-actions
2026-08-17T00:38:29.7959568Z   GITHUB_DEPENDENCY_GRAPH_ENABLED: false
2026-08-17T00:38:29.7959904Z   ANDROID_HOME: /usr/local/lib/android/sdk
2026-08-17T00:38:29.7960257Z   ANDROID_SDK_ROOT: /usr/local/lib/android/sdk
2026-08-17T00:38:29.7960589Z ##[endgroup]
2026-08-17T00:38:29.9714821Z (node:3213) [DEP0040] DeprecationWarning: The `punycode` module is deprecated. Please use a userland alternative instead.
2026-08-17T00:38:29.9715758Z (Use `node --trace-deprecation ...` to show where the warning was created)
2026-08-17T00:38:30.1050015Z With the provided path, there will be 1 file uploaded
2026-08-17T00:38:30.1051769Z Artifact name is valid!
2026-08-17T00:38:30.1052475Z Root directory input is valid!
2026-08-17T00:38:30.3119009Z Beginning upload of artifact content to blob storage
2026-08-17T00:38:30.3321368Z (node:3213) [DEP0169] DeprecationWarning: `url.parse()` behavior is not standardized and prone to errors that have security implications. Use the WHATWG URL API instead. CVEs are not issued for `url.parse()` vulnerabilities.
2026-08-17T00:38:30.4713462Z Uploaded bytes 8592
2026-08-17T00:38:30.5144749Z Finished uploading artifact content to blob storage!
2026-08-17T00:38:30.5145942Z SHA256 digest of uploaded artifact zip is ee17eed9d1cf40d3aceed4032745328a7bc8465af7a571b01146e0e500184d13
2026-08-17T00:38:30.5146976Z Finalizing artifact upload
2026-08-17T00:38:30.6893857Z Artifact build-logs.zip successfully finalized. Artifact ID 9272796193
2026-08-17T00:38:30.6895167Z Artifact build-logs has been successfully uploaded! Final size is 8592 bytes. Artifact ID is 9272796193
2026-08-17T00:38:30.6901866Z Artifact download URL: https://github.com/Pikarziur/AutoBOT/actions/runs/31982535124/artifacts/9272796193
2026-08-17T00:38:30.7158425Z Node 20 is being deprecated. This workflow is running with Node 24 by default. If you need to temporarily use Node 20, you can set the ACTIONS_ALLOW_USE_UNSECURE_NODE_VERSION=true environment variable. For more information see: https://github.blog/changelog/2025-09-19-deprecation-of-node-20-on-github-actions-runners/
2026-08-17T00:38:30.7160051Z Post job cleanup.
2026-08-17T00:38:30.9731919Z In post-action step
2026-08-17T00:38:30.9749580Z ##[group]Stopping Gradle daemons
2026-08-17T00:38:30.9750715Z Stopping Gradle daemons for /home/runner/work/_temp/.gradle-actions/gradle-installations/installs/gradle-8.5
2026-08-17T00:38:30.9766224Z Stopping Gradle daemons for /home/runner/.gradle/wrapper/dists/gradle-8.5-bin/5t9huq95ubn472n8rpzujfbqh/gradle-8.5
2026-08-17T00:38:30.9774432Z [command]/home/runner/work/_temp/.gradle-actions/gradle-installations/installs/gradle-8.5/bin/gradle --stop
2026-08-17T00:38:30.9843872Z [command]/home/runner/.gradle/wrapper/dists/gradle-8.5-bin/5t9huq95ubn472n8rpzujfbqh/gradle-8.5/bin/gradle --stop
2026-08-17T00:38:32.4944191Z No Gradle daemons are running.
2026-08-17T00:38:32.5430232Z No Gradle daemons are running.
2026-08-17T00:38:32.5631556Z ##[endgroup]
2026-08-17T00:38:32.5633421Z Not performing cache-cleanup due to build failure
2026-08-17T00:38:32.5634323Z ##[group]Caching Gradle state
2026-08-17T00:38:33.1135014Z [command]/usr/bin/tar --posix -cf cache.tzst --exclude cache.tzst -P -C /home/runner/work/AutoBOT/AutoBOT --files-from manifest.txt --use-compress-program zstdmt
2026-08-17T00:38:35.3833076Z Sent 9239221 of 143456949 (6.4%), 8.8 MBs/sec
2026-08-17T00:38:36.0492385Z Sent 143456949 of 143456949 (100.0%), 82.1 MBs/sec
2026-08-17T00:38:36.2360948Z Saved cache entry with key gradle-home-v1|Linux-X64|build[266babc85e2a7f6e4c23c8d6be839361]-2250069352764867eb8efd4a6db6503923b097e5 from /home/runner/.gradle/caches,/home/runner/.gradle/notifications,/home/runner/.gradle/.setup-gradle in 3137ms
2026-08-17T00:38:36.2363180Z ##[endgroup]
2026-08-17T00:38:36.2368180Z Generating Job Summary
2026-08-17T00:38:36.2385005Z Completed post-action step
2026-08-17T00:38:36.2607354Z Node 20 is being deprecated. This workflow is running with Node 24 by default. If you need to temporarily use Node 20, you can set the ACTIONS_ALLOW_USE_UNSECURE_NODE_VERSION=true environment variable. For more information see: https://github.blog/changelog/2025-09-19-deprecation-of-node-20-on-github-actions-runners/
2026-08-17T00:38:36.2608864Z Post job cleanup.
2026-08-17T00:38:36.4058497Z (node:3318) [DEP0040] DeprecationWarning: The `punycode` module is deprecated. Please use a userland alternative instead.
2026-08-17T00:38:36.4060024Z (Use `node --trace-deprecation ...` to show where the warning was created)
2026-08-17T00:38:36.4304922Z Node 20 is being deprecated. This workflow is running with Node 24 by default. If you need to temporarily use Node 20, you can set the ACTIONS_ALLOW_USE_UNSECURE_NODE_VERSION=true environment variable. For more information see: https://github.blog/changelog/2025-09-19-deprecation-of-node-20-on-github-actions-runners/
2026-08-17T00:38:36.4307115Z Post job cleanup.
2026-08-17T00:38:36.5341353Z [command]/usr/bin/git version
2026-08-17T00:38:36.5387952Z git version 2.54.0
2026-08-17T00:38:36.5431660Z Temporarily overriding HOME='/home/runner/work/_temp/54a5f2ef-6b9f-4a96-bf4c-6338ac632fcc' before making global git config changes
2026-08-17T00:38:36.5433466Z Adding repository directory to the temporary git global config as a safe directory
2026-08-17T00:38:36.5439342Z [command]/usr/bin/git config --global --add safe.directory /home/runner/work/AutoBOT/AutoBOT
2026-08-17T00:38:36.5489638Z [command]/usr/bin/git config --local --name-only --get-regexp core\.sshCommand
2026-08-17T00:38:36.5535692Z [command]/usr/bin/git submodule foreach --recursive sh -c "git config --local --name-only --get-regexp 'core\.sshCommand' && git config --local --unset-all 'core.sshCommand' || :"
2026-08-17T00:38:36.5870373Z [command]/usr/bin/git config --local --name-only --get-regexp http\.https\:\/\/github\.com\/\.extraheader
2026-08-17T00:38:36.5900784Z http.https://github.com/.extraheader
2026-08-17T00:38:36.5915748Z [command]/usr/bin/git config --local --unset-all http.https://github.com/.extraheader
2026-08-17T00:38:36.5974044Z [command]/usr/bin/git submodule foreach --recursive sh -c "git config --local --name-only --get-regexp 'http\.https\:\/\/github\.com\/\.extraheader' && git config --local --unset-all 'http.https://github.com/.extraheader' || :"
2026-08-17T00:38:36.6275067Z [command]/usr/bin/git config --local --name-only --get-regexp ^includeIf\.gitdir:
2026-08-17T00:38:36.6320403Z [command]/usr/bin/git submodule foreach --recursive git config --local --show-origin --name-only --get-regexp remote.origin.url
2026-08-17T00:38:36.6774552Z Cleaning up orphan processes
2026-08-17T00:38:36.7134135Z ##[warning]Node.js 20 is deprecated. The following actions target Node.js 20 but are being forced to run on Node.js 24: actions/checkout@v4, actions/setup-java@v4, actions/upload-artifact@v4, gradle/actions/setup-gradle@v4. For more information see: https://github.blog/changelog/2025-09-19-deprecation-of-node-20-on-github-actions-runners/
