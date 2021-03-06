# Changelog

[npm history][1]

[1]: https://www.npmjs.com/package/@google/repo?activeTab=versions

### [2.2.2](https://www.github.com/googleapis/github-repo-automation/compare/v2.2.1...v2.2.2) (2019-10-12)


### Bug Fixes

* **deps:** update dependency ora to v4 ([#326](https://www.github.com/googleapis/github-repo-automation/issues/326)) ([88b2f1e](https://www.github.com/googleapis/github-repo-automation/commit/88b2f1e8e16ec6000e6b078d637f2d5424bce879))

### [2.2.1](https://www.github.com/googleapis/github-repo-automation/compare/v2.2.0...v2.2.1) (2019-08-02)


### Bug Fixes

* set commit title when merging PR ([#310](https://www.github.com/googleapis/github-repo-automation/issues/310)) ([a7b1bb0](https://www.github.com/googleapis/github-repo-automation/commit/a7b1bb0))

## [2.2.0](https://www.github.com/googleapis/github-repo-automation/compare/v2.1.2...v2.2.0) (2019-07-31)


### Features

* make samples/update-branch-protection.js is a flexible CLI ([#303](https://www.github.com/googleapis/github-repo-automation/issues/303)) ([b23c2b7](https://www.github.com/googleapis/github-repo-automation/commit/b23c2b7))

### [2.1.2](https://www.github.com/googleapis/github-repo-automation/compare/v2.1.1...v2.1.2) (2019-07-29)


### Bug Fixes

* **deps:** update dependency command-line-usage to v6 ([#299](https://www.github.com/googleapis/github-repo-automation/issues/299)) ([ab395a9](https://www.github.com/googleapis/github-repo-automation/commit/ab395a9))

### [2.1.1](https://www.github.com/googleapis/github-repo-automation/compare/v2.1.0...v2.1.1) (2019-06-05)


### Bug Fixes

* make other PR commands concurrent ([#289](https://www.github.com/googleapis/github-repo-automation/issues/289)) ([ec70b56](https://www.github.com/googleapis/github-repo-automation/commit/ec70b56))
* **deps:** update dependency axios to ^0.19.0 ([#291](https://www.github.com/googleapis/github-repo-automation/issues/291)) ([913c93c](https://www.github.com/googleapis/github-repo-automation/commit/913c93c))

## [2.1.0](https://www.github.com/googleapis/github-repo-automation/compare/v2.0.1...v2.1.0) (2019-05-29)


### Features

* add the `rename` command ([#284](https://www.github.com/googleapis/github-repo-automation/issues/284)) ([7991585](https://www.github.com/googleapis/github-repo-automation/commit/7991585))

### [2.0.1](https://www.github.com/googleapis/github-repo-automation/compare/v2.0.0...v2.0.1) (2019-05-23)


### Bug Fixes

* **deps:** update dependency tmp-promise to v2 ([#278](https://www.github.com/googleapis/github-repo-automation/issues/278)) ([a7a7b2d](https://www.github.com/googleapis/github-repo-automation/commit/a7a7b2d))
* **deps:** update dependency update-notifier to v3 ([#275](https://www.github.com/googleapis/github-repo-automation/issues/275)) ([d8e9529](https://www.github.com/googleapis/github-repo-automation/commit/d8e9529))

## [2.0.0](https://www.github.com/googleapis/github-repo-automation/compare/v1.1.0...v2.0.0) (2019-05-03)


### Bug Fixes

* stop supporting Node.js v6 ([#270](https://www.github.com/googleapis/github-repo-automation/issues/270)) ([02eb085](https://www.github.com/googleapis/github-repo-automation/commit/02eb085))
* **deps:** update dependency p-queue to v5 ([#261](https://www.github.com/googleapis/github-repo-automation/issues/261)) ([75e5bb6](https://www.github.com/googleapis/github-repo-automation/commit/75e5bb6))


### BREAKING CHANGES

* stop supporting Node.js v6 (#270)

## v1.1.0

04-18-2019 14:47 PDT

### New features
- feat: let user specify concurrency ([#258](https://github.com/googleapis/github-repo-automation/pull/258))
- feat: add `tag` command to apply labels to PRs ([#237](https://github.com/googleapis/github-repo-automation/pull/237))
- feat: repo check Kokoro status enabled, samples code for enabling Kokoro checks ([#183](https://github.com/googleapis/github-repo-automation/pull/183))

### Bug fixes
- fix: log message ([#193](https://github.com/googleapis/github-repo-automation/pull/193))
- fix: repo apply fails when untracked dirs were added ([#188](https://github.com/googleapis/github-repo-automation/pull/188))
- fix(deps): update dependency p-queue to v4 ([#252](https://github.com/googleapis/github-repo-automation/pull/252))
- fix: remove unused packages ([#249](https://github.com/googleapis/github-repo-automation/pull/249))
- fix: update sample for updating status checks ([#202](https://github.com/googleapis/github-repo-automation/pull/202))

### Docs
- docs: update links in contrib guide ([#246](https://github.com/googleapis/github-repo-automation/pull/246))
- docs: update contributing guide ([#242](https://github.com/googleapis/github-repo-automation/pull/242))
- docs: add lint/fix example to contributing guide ([#239](https://github.com/googleapis/github-repo-automation/pull/239))

### Internal changes
- chore(deps): update dependency nyc to v14 ([#262](https://github.com/googleapis/github-repo-automation/pull/262))
- chore: publish to npm using wombat ([#255](https://github.com/googleapis/github-repo-automation/pull/255))
- build: use per-repo publish token ([#254](https://github.com/googleapis/github-repo-automation/pull/254))
- build: Add docuploader credentials to node publish jobs ([#251](https://github.com/googleapis/github-repo-automation/pull/251))
- build: use node10 to run samples-test, system-test etc ([#250](https://github.com/googleapis/github-repo-automation/pull/250))
- build: update release configuration ([#248](https://github.com/googleapis/github-repo-automation/pull/248))
- chore(deps): update dependency mocha to v6 ([#247](https://github.com/googleapis/github-repo-automation/pull/247))
- build: use linkinator for docs test ([#245](https://github.com/googleapis/github-repo-automation/pull/245))
- build: create docs test npm scripts ([#244](https://github.com/googleapis/github-repo-automation/pull/244))
- build: test using @grpc/grpc-js in CI ([#243](https://github.com/googleapis/github-repo-automation/pull/243))
- chore(deps): update dependency eslint-config-prettier to v4 ([#238](https://github.com/googleapis/github-repo-automation/pull/238))
- build: ignore googleapis.com in doc link check ([#236](https://github.com/googleapis/github-repo-automation/pull/236))
- build: check for 404s in the docs ([#235](https://github.com/googleapis/github-repo-automation/pull/235))
- chore(deps): update dependency @types/ora to v3 ([#233](https://github.com/googleapis/github-repo-automation/pull/233))
- chore(deps): update dependency @types/sinon to v7 ([#232](https://github.com/googleapis/github-repo-automation/pull/232))
- chore(build): inject yoshi automation key ([#231](https://github.com/googleapis/github-repo-automation/pull/231))
- chore: update nyc and eslint configs ([#230](https://github.com/googleapis/github-repo-automation/pull/230))
- chore: fix publish.sh permission +x ([#228](https://github.com/googleapis/github-repo-automation/pull/228))
- fix(build): fix Kokoro release script ([#227](https://github.com/googleapis/github-repo-automation/pull/227))
- build: add Kokoro configs for autorelease ([#226](https://github.com/googleapis/github-repo-automation/pull/226))
- chore: always nyc report before calling codecov ([#223](https://github.com/googleapis/github-repo-automation/pull/223))
- chore: nyc ignore build/test by default ([#222](https://github.com/googleapis/github-repo-automation/pull/222))
- chore(build): update prettier config ([#220](https://github.com/googleapis/github-repo-automation/pull/220))
- chore(deps): update dependency @types/sinon to v5.0.7 ([#213](https://github.com/googleapis/github-repo-automation/pull/213))
- chore(build): update CI config ([#217](https://github.com/googleapis/github-repo-automation/pull/217))
- fix(build): fix system key decryption ([#214](https://github.com/googleapis/github-repo-automation/pull/214))
- refactor: drop octokit, just use rest ([#216](https://github.com/googleapis/github-repo-automation/pull/216))
- fix(deps): update dependency @octokit/rest to v16 ([#207](https://github.com/googleapis/github-repo-automation/pull/207))
- chore(deps): update dependency @types/p-queue to v3 ([#209](https://github.com/googleapis/github-repo-automation/pull/209))
- fix: Pin @types/sinon to last compatible version ([#210](https://github.com/googleapis/github-repo-automation/pull/210))
- chore: add a synth.metadata
- chore(deps): update dependency gts to ^0.9.0 ([#205](https://github.com/googleapis/github-repo-automation/pull/205))
- chore: update eslintignore config ([#204](https://github.com/googleapis/github-repo-automation/pull/204))
- chore: use latest npm on Windows ([#203](https://github.com/googleapis/github-repo-automation/pull/203))
- chore: update CircleCI config ([#201](https://github.com/googleapis/github-repo-automation/pull/201))
- chore: include build in eslintignore ([#198](https://github.com/googleapis/github-repo-automation/pull/198))
- chore(deps): update dependency eslint-plugin-node to v8 ([#194](https://github.com/googleapis/github-repo-automation/pull/194))
- chore: update issue templates ([#192](https://github.com/googleapis/github-repo-automation/pull/192))
- chore: remove old issue template ([#190](https://github.com/googleapis/github-repo-automation/pull/190))
- build: run tests on node11 ([#189](https://github.com/googleapis/github-repo-automation/pull/189))
- chores(build): run codecov on continuous builds ([#185](https://github.com/googleapis/github-repo-automation/pull/185))
- chores(build): do not collect sponge.xml from windows builds ([#186](https://github.com/googleapis/github-repo-automation/pull/186))
- chore: update new issue template ([#184](https://github.com/googleapis/github-repo-automation/pull/184))

## v1.0.0

### Fixes
- fix: `repo apply` command ([#179](https://github.com/googleapis/github-repo-automation/pull/179))
- fix: repair repo sync ([#154](https://github.com/googleapis/github-repo-automation/pull/154))

### New Features
- feat: split the approve command ([#164](https://github.com/googleapis/github-repo-automation/pull/164))

### Internal / Testing Changes
- build: fix codecov uploading on Kokoro ([#178](https://github.com/googleapis/github-repo-automation/pull/178))
- chore(deps): update dependency sinon to v7 ([#177](https://github.com/googleapis/github-repo-automation/pull/177))
- chore(deps): update dependency @types/meow to v5 ([#165](https://github.com/googleapis/github-repo-automation/pull/165))
- Update kokoro config ([#163](https://github.com/googleapis/github-repo-automation/pull/163))
- chore(deps): update dependency eslint-plugin-prettier to v3 ([#162](https://github.com/googleapis/github-repo-automation/pull/162))
- Update CI config ([#160](https://github.com/googleapis/github-repo-automation/pull/160))
- Don't publish sourcemaps ([#158](https://github.com/googleapis/github-repo-automation/pull/158))
- Re-generate library using /synth.py ([#157](https://github.com/googleapis/github-repo-automation/pull/157))
- Update kokoro config ([#156](https://github.com/googleapis/github-repo-automation/pull/156))
- test: remove appveyor config ([#155](https://github.com/googleapis/github-repo-automation/pull/155))
- Update kokoro config ([#153](https://github.com/googleapis/github-repo-automation/pull/153))
- Enable prefer-const in the eslint config ([#152](https://github.com/googleapis/github-repo-automation/pull/152))

## v0.3.0

### Features
- feat: print report after repo approve ([#148](https://github.com/googleapis/github-repo-automation/pull/148))
- feat: load repositories from sloth JSON config ([#143](https://github.com/googleapis/github-repo-automation/pull/143))
- feat: make repo exec async ([#111](https://github.com/googleapis/github-repo-automation/pull/111))
- feat: delete branch after approving and merging ([#116](https://github.com/googleapis/github-repo-automation/pull/116))

### Bug Fixes
- fix: make repo-check work ([#149](https://github.com/googleapis/github-repo-automation/pull/149))
- fix: actually delete branch ([#147](https://github.com/googleapis/github-repo-automation/pull/147))
- fix: proper ssh_url for github repos from json ([#145](https://github.com/googleapis/github-repo-automation/pull/145))
- fix: properly delete branch by git reference ([#139](https://github.com/googleapis/github-repo-automation/pull/139))
- fix: clone if dir does not exist ([#128](https://github.com/googleapis/github-repo-automation/pull/128))
- fix: update compilation errors due to new octokit ([#129](https://github.com/googleapis/github-repo-automation/pull/129))
- fix: speed up sync ([#121](https://github.com/googleapis/github-repo-automation/pull/121))
- fix: do not include archived repos ([#119](https://github.com/googleapis/github-repo-automation/pull/119))
- fix: repo apply CLI should not accept --execute/--command ([#115](https://github.com/googleapis/github-repo-automation/pull/115))

## Keepin' the lights on
- Enable no-var in eslint ([#146](https://github.com/googleapis/github-repo-automation/pull/146))
- chore(deps): update dependency nock to v10 ([#144](https://github.com/googleapis/github-repo-automation/pull/144))
- Update CI config ([#142](https://github.com/googleapis/github-repo-automation/pull/142))
- Fix sample tests ([#141](https://github.com/googleapis/github-repo-automation/pull/141))
- Retry npm install in CI ([#137](https://github.com/googleapis/github-repo-automation/pull/137))
- Update CI config ([#135](https://github.com/googleapis/github-repo-automation/pull/135))
- fix(deps): update dependency p-queue to v3 ([#134](https://github.com/googleapis/github-repo-automation/pull/134))
- chore(deps): update dependency nyc to v13 ([#133](https://github.com/googleapis/github-repo-automation/pull/133))
- add (dummy) system-test key ([#132](https://github.com/googleapis/github-repo-automation/pull/132))
- Add and run synth file ([#130](https://github.com/googleapis/github-repo-automation/pull/130))
- chore(deps): update dependency eslint-config-prettier to v3 ([#127](https://github.com/googleapis/github-repo-automation/pull/127))
- chore(deps): update dependency assert-rejects to v1 ([#125](https://github.com/googleapis/github-repo-automation/pull/125))
- chore: ignore package-lock.json ([#124](https://github.com/googleapis/github-repo-automation/pull/124))
- chore(deps): lock file maintenance ([#123](https://github.com/googleapis/github-repo-automation/pull/123))
- chore: use CircleCI for publish ([#109](https://github.com/googleapis/github-repo-automation/pull/109))
- chore: update renovate config ([#122](https://github.com/googleapis/github-repo-automation/pull/122))
- chore: throw on deprecation ([#120](https://github.com/googleapis/github-repo-automation/pull/120))
- chore(deps): lock file maintenance ([#118](https://github.com/googleapis/github-repo-automation/pull/118))
- chore(deps): update dependency typescript to v3 ([#117](https://github.com/googleapis/github-repo-automation/pull/117))
- chore: assert.deelEqual => assert.deepStrictEqual ([#114](https://github.com/googleapis/github-repo-automation/pull/114))
- chore: move mocha options to mocha.opts ([#110](https://github.com/googleapis/github-repo-automation/pull/110))
